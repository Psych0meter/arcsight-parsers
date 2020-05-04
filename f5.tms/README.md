# F5 TMS parser
For syslog SmartConnector

## Installation
Copy flexagent directory in $ARCSIGHT_HOME$/current/user/agent/

Restart SmartConnector

## Log example
```
<13> xxx Mar 15 08:51:02 xxx notice tmsh[2020]: 01420002:5: AUDIT - pid=2020 user=root folder=/Common module=(tmos)# status=[Command OK] cmd_data=show sys mcp-state field-fmt
```
