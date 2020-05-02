# Centreon parser
For directory reader SmartConnector

Works only for Centreon V2.8.x

## Installation
Copy flexagent directory in $ARCSIGHT_HOME$/current/user/agent/

Restart SmartConnector


Each parser must be linked to a directory :
- centreon.sdkrfilereader.properties : /var/log/centreon/
- centreon_broker.sdkrfilereader.properties : /var/log/centreon-broker/
- centreon_engine.sdkrfilereader.properties : /var/log/centreon-engine/
