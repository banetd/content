# content

nxlog_ssl_config_windows.conf
Used to receive Syslog over TLS from a source, then send the received message via syslog to an SIEM aggregator destination. 

ms_nps.conf
Used to read Network Policy Server events from a Windows Server, rename the message field attributes to a conforming taxonomy for your SIEM of choice, and send that output in JSON. 
