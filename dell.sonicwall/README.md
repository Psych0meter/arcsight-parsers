# Dell Sonicwall parser
For syslog SmartConnector

## Installation
Copy flexagent directory in $ARCSIGHT_HOME$/current/user/agent/

Restart SmartConnector

## Log example
```
id=firewall sn=xxx time="2018-01-26 07:58:37 UTC" fw=xxx.xxx.xxx.xxx pri=1 c=32 m=1391 pktdatId=xxx pktdatNum="2/2" pktdatEnc="xxx" n=0 src=xxx.xxx.xxx.xxx:x:X5 dst=xxx.xxx.xxx.xxx:x
```
