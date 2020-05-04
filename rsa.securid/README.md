# RSA SecurID parser
For syslog SmartConnector

## Installation
Copy flexagent directory in $ARCSIGHT_HOME$/current/user/agent/

Restart SmartConnector

## Log example
```
<14>2018-03-07 09:32:25,008, , audit.runtime.com.rsa.ims.authn.impl.AuthenticationBrokerImpl, INFO, xxx,xxx,xxx.xxx.xxx.xxx,xxx.xxx.xxx.xxx,AUTHN_LOGIN_EVENT,13002,SUCCESS,AUTHN_METHOD_SUCCESS,xxx,xxx,xxx,xxx,xxx,xxx,xxx,xxx,xxx,xxx.xxx.xxx.xxx,REMOTEACCESSV3,7,xxx,SecurID_Native,,,AUTHN_LOGIN_EVENT,6,4,xxx,RemoteAccess,xxx,Citrix Remote Access,xxx,xxx,,\n
```
