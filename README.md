# ansible-playbooks

git repo to host my ansible playbooks used in my home lab 

- custom.yml 	- a playbook that downloads and run a custom.sh script
- install_tools.yml - a playbook that installs my favourite os tools
- iptables.yml	- a playbook to disable the iptables service
- new.yml	- a playbook that includes other playbooks to be used to configure a new host
- ntp.yml 	- a playbook to configure timezone and enable ntp timezone
- reboot.yml	- reboots the target host
- selinux.yml 	- disables selinux via cli and on next reboot
- snmp.yml	- installs and enables snmp
- spacewalk.yml	- configures the target server to become a spacewalk client
- vnstat.yml	- configures and starts vnstat
- yum_update.yml - yum updates hosts
