# Microsoft DHCP parser
For directory reader SmartConnector

## Installation
Configuration folder : EnterpriseVaultAudit

Copy flexagent directory in $ARCSIGHT_HOME$/current/user/agent/

Restart SmartConnector

## Log example
```
24,03/06/20,00:00:45,Database Cleanup Begin,,,,,0,6,,,,,,,,,
```

## Documentation

### Log format
```
ID,Date,Time,Description,IP Address,Host Name,MAC Address,User Name, TransactionID, QResult,Probationtime, CorrelationID,Dhcid,VendorClass(Hex),VendorClass(ASCII),UserClass(Hex),UserClass(ASCII),RelayAgentInformation,DnsRegError.
```

### ID
```
00	The log was started.
01	The log was stopped.
02	The log was temporarily paused due to low disk space.
10	A new IP address was leased to a client.
11	A lease was renewed by a client.
12	A lease was released by a client.
13	An IP address was found to be in use on the network.
14	A lease request could not be satisfied because the scope's address pool was exhausted.
15	A lease was denied.
16	A lease was deleted.
17	A lease was expired and DNS records for an expired leases have not been deleted.
18	A lease was expired and DNS records were deleted.
20	A BOOTP address was leased to a client.
21	A dynamic BOOTP address was leased to a client.
22	A BOOTP request could not be satisfied because the scope's address pool for BOOTP was exhausted.
23	A BOOTP IP address was deleted after checking to see it was not in use.
24	IP address cleanup operation has began.
25	IP address cleanup statistics.
30	DNS update request to the named DNS server.
31	DNS update failed.
32	DNS update successful.
33	Packet dropped due to NAP policy.
34	DNS update request failed.as the DNS update request queue limit exceeded.
35	DNS update request failed.
36	Packet dropped because the server is in failover standby role or the hash of the client ID does not match.
50+	Codes above 50 are used for Rogue Server Detection information.
```

### QResult
```
0  NoQuarantine
1  Quarantine
2  Drop Packet
3  Probation
6  No Quarantine Information 
```
