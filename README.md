# rsyslog
syslog-server


```cmd
sudo vim /etc/rsyslog.conf
rsyslogd -f /etc/rsyslog.conf -N1
sudo systemctl restart rsyslog
sudo systemctl status rsyslog
sudo netstat -tulnp | grep rsyslog
```
