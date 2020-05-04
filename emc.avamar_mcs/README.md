# EMC Avamar MCS parser
For syslog SmartConnector

## Installation
Copy flexagent directory in $ARCSIGHT_HOME$/current/user/agent/

Restart SmartConnector

## Log example
```
CR::CLIENT::EDIT: <Code> 22211 <Type> AUDIT <Severity> OK <Category> SECURITY <User> root <HwSource> xxx <Summary> Client was updated. <nodeName> xxx <clientid> xxx <old-modifiedDate> Thu Nov 16 00:00:00 CET 2017 <action> update <fullName> xxx <display-nodeName> xxx <new-modifiedDate> Mon Dec 04 15:03:04 CET 2017 <nodeAddress> xxx.xxx.xxx.xxx
```
