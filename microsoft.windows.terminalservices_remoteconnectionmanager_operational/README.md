# Microsoft Windows Terminalservices Remoteconnectionmanager Operational parser
For fcp SmartConnector

## Installation
Copy fcp directory in $ARCSIGHT_HOME$/current/user/agent/

Restart SmartConnector

## Log example
```
Raw Event : {"System":{"EventId":"1149","Version":"0","Channel":"Microsoft-Windows-TerminalServices-RemoteConnectionManager/Operational","ProviderName":"Microsoft-Windows-TerminalServices-RemoteConnectionManager","Computer":"xxx","EventRecordID":"1605","Keywords":"None","Level":"Informational","Opcode":"Info","Task":"None","ProcessID":"2288","ThreadID":"9140","TimeCreated":"1583222880546","UserId":"NT AUTHORITY\\NETWORK SERVICE"},"EventData":{},"UserData":{"EventXML":{"@_xmlns_":"Event_NS","Param1":"xxx","Param2":"xxx","Param3":"xxx.xxx.xxx.xxx"}}}
```

## If long name problem
https://helpdeskgeek.com/how-to/how-to-fix-filename-is-too-long-issue-in-windows/
