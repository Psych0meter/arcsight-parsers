# Citrix NetScaler parser
For syslog SmartConnector

## Installation
Copy flexagent directory in $ARCSIGHT_HOME$/current/user/agent/

Restart SmartConnector

## Log example for audit
```
03/05/2021:06:18:42 GMT  0-PPE-0 : default SSLLOG SSL_HANDSHAKE_ISSUERNAME 73444401 0 :  SPCBId 54281671 - IssuerName " DC=xxx,DC=xxx,CN=xxx"\0x0a
03/05/2021:06:18:42 GMT  0-PPE-0 : default SSLLOG SSL_HANDSHAKE_SUBJECTNAME 73444402 0 :  SPCBId 54281671 - SubjectName " CN=xxx"\0x0a
03/05/2021:06:18:42 GMT  0-PPE-0 : default TCP CONN_TERMINATE 73444403 0 :  Source x.x.x.x:443 - Destination x.x.x.x:53936 - Start Time 03/05/2021:06:18:42 GMT - End Time 03/05/2021:06:18:42 GMT - Total_bytes_send 227 - Total_bytes_recv 1 \0x0a
03/05/2021:06:18:43 GMT  0-PPE-0 : default SSLLOG SSL_HANDSHAKE_SUCCESS 73444404 0 :  Backend SPCBId 54281688 - ServerIP x.x.x.x - ServerPort 443 - ProtocolVersion TLSv1.2 - CipherSuite "xxx TLSv1.2 Non-Export 128-bit" - Session New - SERVER_AUTHENTICATED -SerialNumber "xxx" - SignatureAlgorithm "sha1WithRSAEncryption" - ValidFrom "Aug 18 08:02:05 2020 GMT" - ValidTo "Dec  1 09:38:59 2021 GMT" - HandshakeTime 3 ms\0x0a
```
