# Microsoft Windows parser
For syslog SmartConnector

## Installation
Copy flexagent directory in $ARCSIGHT_HOME$/current/user/agent/

Restart SmartConnector

## Log example
<13> xxx 09/04/2018 09:08:04 AM####LogName=Security####SourceName=Microsoft Windows security auditing.####EventCode=5152####EventType=0####Type=Information####ComputerName=xxx####TaskCategory=Filtering Platform Packet Drop####OpCode=Info####RecordNumber=59244160####Keywords=Audit Failure####Message=The Windows Filtering Platform has blocked a packet.############Application Information:######	Process ID:		0######	Application Name:	-############Network Information:######	Direction:		Inbound######	Source Address:		xxx.xxx.xxx.xxx######	Source Port:		57621######	Destination Address:	xxx.xxx.xxx.xxx######	Destination Port:		57621######	Protocol:		17############Filter Information:######	Filter Run-Time ID:	74003######	Layer Name:		Transport######	Layer Run-Time ID:	13

