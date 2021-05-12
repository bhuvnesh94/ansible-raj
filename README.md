# ansible-raj
Target machine- Windows
Ansible machine- Linux

Use Case:
1. Database install- mysql, oracle
2. Cloud machine as host

--Ansible--
1. Ansible is a automation tool that is used to manage configuration of the remote system or on premisis system. 
Automation tool -- you should have knowledage  of manually deploying things.
Windows uses exe as a installer.

2. Ansible is written in python.

3. Ansible is agentless architecture.

How ansible then connect with windows and linux machine?

--> client_ip and user_name and login details
--> To connect with linux machine it requires ssh(default port 22)
--> To connect with windows machine it requires winrm(The WinRM port for HTTP is 5985 while the WinRm port for HTTPS is 5986, by default.)
--> Python is sometime required.

4. Ansible server is not able to install on windows

5. Ansible install link - https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html

6. RHEL8 -- centos
> RPM --redhat package manager 
> DNF --Dandified YUM
> 
> REDHAT yum as a installer
> 
> Ansible is written in python
> 
> apt / yum / dnf
> exe/ rpm/ deb/ rpm
> 
> After installing ansible
> 
> 1. configuration file
> 2. inventory file -- host entries
> 3. ansible uses modules(written in python)
> 4. ansible can connect to hosts via password or passwordless
