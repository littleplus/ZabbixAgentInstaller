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

# Licence

BSD 2-Clause License

Copyright (c) 2018, littleplus
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice, this
  list of conditions and the following disclaimer.

* Redistributions in binary form must reproduce the above copyright notice,
  this list of conditions and the following disclaimer in the documentation
  and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
