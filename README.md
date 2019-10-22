# Ansible-Install-Jenkins-Centos7
Ansible playbook to install a Jenkins server using ssh
Target OS: Centos 7
Command for execute playbook: 

ansible-playbook -i 192.168.0.X, -u root --extra-vars ansible_ssh_pass=Password123 ansible-install-jenkins-centos7.yml

You will need to configuree the host "192.168.0.X" the user "root" and password "Password123" with your target
server credentials.

