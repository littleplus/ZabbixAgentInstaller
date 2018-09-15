# Notice

* This installer will install Zabbix Agent 3.4
* The config file is in /etc/zabbix/
* The iptables save in /etc/iptables.za.rules
* Startup script is in /etc/rc.local, if zabbix agent could not start on boot, please check your rc.local
* Support Systems: Centos 5/6 (i386/x86_64),7 x86_64;  Debian 7/8/9 (i386/x86_64); Ubuntu 14/16/18 (i386/x86_64)
* You can manage the zabbix agent by service zabbix-agent <start|stop|restart>

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
./Zabbix.sh <arguments>
```

### Arguments

```
Zabbix.sh [-s <zabbix server ip(s)>] [-n <zabbix host name>]
```

# Licence

DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE 

Version 2, December 2004 

 Copyright (C) 2018 littleplus

 Everyone is permitted to copy and distribute verbatim or modified 
 copies of this license document, and changing it is allowed as long 
 as the name is changed. 

            DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE 
   TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION 

  0. You just DO WHAT THE FUCK YOU WANT TO.
