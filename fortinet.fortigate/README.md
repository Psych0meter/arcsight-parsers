# Fortinet Fortigate parser
For syslog SmartConnector

## Installation
Copy flexagent directory in $ARCSIGHT_HOME$/current/user/agent/

Restart SmartConnector

## Log example
<13> xxx Feb 21 11:25:48 xxx.xxx.xxx.xxx date=2018-02-21 time=11:25:48 logver=52 devid=xxx devname=wxx logid=0000000013 type=traffic subtype=forward level=notice vd=xxx srcip=xxx.xxx.xxx.xxx srcname=xxx srcport=xxx srcintf="xxx" dstip=xxx.xxx.xxx.xxx dstport=xxx dstintf="xxx" poluuid=xxx sessionid=xxx proto=6 action=close policyid=364 dstcountry="Reserved" srccountry="Reserved" trandisp=noop service=SQUID duration=1 sentbyte=132 rcvdbyte=92 sentpkt=3 rcvdpkt=2 devtype="Windows PC" osname="Windows" osversion="7 (x64)" unauthuser="xxx" unauthusersource="mapi" mastersrcmac=xx:xx:xx:xx:xx:xx srcmac=xx:xx:xx:xx:xx:xx
