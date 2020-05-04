# CheckPoint audit parser
For syslog SmartConnector

## Installation
Copy flexagent directory in $ARCSIGHT_HOME$/current/user/agent/

Restart SmartConnector

## Log example
```
<15>cpd: Audit logs: 'state? 11| objectName? Interfaces|administrator? admin| operation? Set Object| facility? Web-UI| message? Logical interface (ethx) is configured with IP address xxx.xxx.xxx.xxx/xx ' message is being updated with 'state? 10| objectName? Interfaces|administrator? admin| operation? Set Object| facility? Web-UI| message? Logical interface (ethx) is configured with IP address xxx.xxx.xxx.xxx/xx '
```
