# Ansible Role for Papertrails RemoteSyslog2

[![Build Status](https://travis-ci.org/YtoTech/ansible-remote_syslog2.svg?branch=master)](https://travis-ci.org/YtoTech/ansible-remote_syslog2)

A Simple Role to install Remote Syslog 2

## Role Variables

```yaml
remote_syslog_package_url: https://github.com/papertrail/remote_syslog2/releases/download/v0.13/remote_syslog_linux_amd64.tar.gz
remote_syslog_files: []
remote_syslog_host: logs.papertrailapp.com
remote_syslog_port: 1234
remote_syslog_protocol: tls
```




## to forward log files you are interested to paper tail
add the path of the file in the remote_syslog_files
overited the variable for remote_syslog_port to port you are assigned by papertail

## License

MIT
