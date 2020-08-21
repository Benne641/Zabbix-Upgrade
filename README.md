# Zabbix-Upgrade
In place upgrade of Zabbix from 3.0 to 5.0 on centos 7 

What this till do (TLDR)
 backup the current zabbix configs (not the sql DB that will be on you)
 upgrade all of the zabbix componets and infrastructure. 
 upgrade php to 7.4 (required)
 enable the new web frontend for zabbix
 put the zabbix config from the old install back in place  
 restart http and zabbix 

If you have zabbix up when you run this you can reload ip/zabbix and you should see v5
