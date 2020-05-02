# CheckPoint parser
For syslog SmartConnector

## Installation
Copy flexagent directory in $ARCSIGHT_HOME$/current/user/agent/

Restart SmartConnector

## Log example
"ContentVersion: 1; Uuid: {0x59f1ca80,0x102,0xf800030a,0xc0001000}; SequenceNum: <max_null>; Flags: 16384; Action: accept; Origin: xxx.xxx.xxx.xxx; IfDir: >; InterfaceName: bond1.214; Alert: ; LogId: <max_null>; OriginSicName: CN=xxx; OriginSicName: CN=xxx,O=xxx; log_type: log; is_first_for_luuid: 131072; inzone: Internal; outzone: Local; service_id: icmp-proto; ICMP: Echo Request; src: xxx.xxx.xxx.xxx; dst: xxx.xxx.xxx.xxx; proto: 1; ICMP Type: 8; ICMP Code: 0; xlatedst: xxx.xxx.xxx.xxx; NAT_rulenum: 0; NAT_addtnl_rulenum: 0; rule: 0; message_info: Implied rule; aba_customer: SMC User; date: 26Oct2017; hour: 13:44:00; type: log; Interface: < bond1.214; ProductName: VPN-1 & FireWall-1; xlatedport_svc: ; xlatesport_svc: ;",""
