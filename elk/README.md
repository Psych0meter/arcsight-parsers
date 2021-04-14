JSON example :

```{"@timestamp":"2021-04-13T06:00:38.780Z",
"tags":["TAG1","TAG2"],
"lgst_in":"HOSTNAME",
"ecs":{
	"version":"1.6.0"
	},
"agent":{
	"type":"filebeat",
	"name":"HOSTNAME",
	"ephemeral_id":"ID",
	"hostname":"HOSTNAME",
	"version":"7.11.2",
	"id":"ID"
	},
"message":"Apr 13 08:00:37 HOST systemd: Started Session SESSION_ID of user root.",
"input":{
	"type":"log"
	},
"@version":"1",
"log":{
	"file":{
		"path":"/var/log/messages"
		},
	"offset":1230087
	},
"redis_list":"beats",
"stype":"linux"}
```
