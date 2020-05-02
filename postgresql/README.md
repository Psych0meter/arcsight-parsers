# Postgresql parser
For Folder file SmartConnector

## Installation
Configuration file : pgaudit

Copy flexagent directory in $ARCSIGHT_HOME$/current/user/agent/

Add following lines in agent.properties :
```
agents[0].mode=PersistFile
agents[0].modeoptions=processed
```

Restart SmartConnector
