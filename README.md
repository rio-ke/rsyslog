# rsyslog
syslog-server


```cmd
sudo vim /etc/rsyslog.conf
rsyslogd -f /etc/rsyslog.conf -N1
sudo systemctl restart rsyslog
sudo systemctl status rsyslog
sudo netstat -tulnp | grep rsyslog
```

_Reference_

[rsyslog install and configuration](https://kifarunix.com/setup-rsyslog-server-on-ubuntu-20-04/)

[**rsyslog_to_wazuh**](https://wazuh.com/blog/how-to-configure-rsyslog-client-to-send-events-to-wazuh/)
