# Pulsesecure parser
For syslog SmartConnector

## Installation
Copy flexagent directory in $ARCSIGHT_HOME$/current/user/agent/

Restart SmartConnector

## Log example
```
<13> xxx Feb 22 06:56:11 xxx  2018-02-22T06:56:09+01:00  xxx PulseSecure: id=firewall time="2018-02-22 06:56:09" pri=6 fw=xxx.xxx.xxx.xxx vpn=xxx ivs=Default Network user=xxx realm="xxx" roles="xxx" proto= src=xxx.xxx.xxx.xxx dst= dstname= type=vpn op= arg="" result= sent= rcvd= agent="" duration= msg="NWC23508: Key Exchange number 39 occurred for user with NCIP xxx.xxx.xxx.xxx "
```
