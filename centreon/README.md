# Centreon parser
For syslog SmartConnector

Works only for Centreon V2.8.x

## Installation
Copy flexagent directory in $ARCSIGHT_HOME$/current/user/agent/

Restart SmartConnector

Centreon logs must be formwarded via syslog

Logs must be prefixed by centreon.log_type

### e.g.
/var/log/centreon/login.log --> centreon.login

/var/log/centreon/centreontrapd.log --> centreon.centreontrapd

...
