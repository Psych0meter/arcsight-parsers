# Trendmicro Officescan parser
For syslog and winc SmartConnector

## Installation
- Syslog : Copy flexagent directory in $ARCSIGHT_HOME$/current/user/agent/
- Winc : Copy fcp directory in $ARCSIGHT_HOME$/current/user/agent/

Restart SmartConnector

## Log example for syslog
SLF_INCIDENT_EVT_VIRUS_FOUND_QUARANTINE_SUCCESS Security product="OfficeScan" Security product node="xxx" Security product IP="xxx.xxx.xxx.xxx" Event time="11/29/2017 2:27 PM (UTC)" Virus="Unauthorized File Encryption" Infected file="xxx" File path="xxx" Action taken="Move" Result="File quarantined" Infection destination="xxx" Infection destination IP="xxx.xxx.xxx.xxx" Infection source="N/A" Infection source IP="" Destination IP="" Source IP="" Domain="xxx" ScanMethod="Real-time Scan" User="xxx" Managing server entity="xxx"
