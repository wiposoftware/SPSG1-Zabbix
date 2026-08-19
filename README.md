# SPSG1-Zabbix
Zabbix template for Shelly Plug S gen 1 device <br/>
<img width="320" height="241" alt="shellyplugs" src="https://github.com/user-attachments/assets/6ecf131f-3f6d-4862-a05e-d7de4ce28304" />
<br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>
Data is read from your Shelly Plug S gen 1 device via HTTP RPC requests.


This zabbix template is created with Zabbix version 5.2. But you should be ably to import it in later version.

- import the template in zabbix.
- create a host in zabbix
- as host interface use agent and fill in the IP of the SPSG1 device
- if your SPSG1 has password protection create or change these macros:
  - {$SHPLGS_USER}  -> fill in admin when using pwd protected S1G3 device
  - {$SHPLGS_PWD}  -> fill in your S1G3 password.
