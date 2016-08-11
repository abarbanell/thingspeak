# thingspeak

Some scripts, tools and others related to thingspeak.com 

- server_stats.sh: a script to feed server stats into thingspeak for analysis. It requires an API key which is not included in the script, it comes from config.sh which is not in the repository, but should look like

```
#!/bin/sh

export THINGSPEAK_SERVER_CHANNEL_WRITE_KEY='YOURKEYGOESHERE'

```

