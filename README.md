# Notice

* This installer will install Zabbix Agent 3.4
* The config file is in /etc/zabbix/
* The iptables save in /etc/iptables.za.rules
* Startup script is in /etc/rc.local, if zabbix agent could not start on boot, please check your rc.local
* Support Systems: Centos 5/6 (i386/x86_64),7 x86_64;  Debian 7/8/9 (i386/x86_64); Ubuntu 14/16/18 (i386/x86_64)

---

# Usage

### Download

### Run

```
bash Zabbix.sh <arguments>
```

or

```
chmod +x Zabbix.sh
Zabbix.sh <arguments>
```

### Arguments

```
Zabbix.sh [-s <zabbix server ip(s)>] [-n <zabbix host name>]
```