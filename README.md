# ansible
sudo systemctl start ssh

sudo apt-get install openssh-server

sudo apt-get install sshpass

ip addr

ansible webservers -m ping

ansible webservers -m command -a "/bin/echo hello world"

run the ansible playbook >> ansible-playbook -v test_apache_playbook.yaml

run the ansible playbook >> ansible-playbook -v install_apache_playbook.yaml

Verify if apache is installed >> sudo systemctl status apache2

Examine the two files that will be modified by the playbook >> cat /etc/apache2/ports.conf

Examine the two files that will be modified by the playbook >> cat /etc/apache2/sites-available/000-default.conf

run the ansible playbook >> ansible-playbook install_apache_options_playbook.yaml

Examine the two files that will be modified by the playbook >> cat /etc/apache2/ports.conf

**CSR1000V**

ansible

ansible --version

cat /etc/ansible/ansible.cfg | more

cat ansible.cfg

ping 192.168.211.129

mkdir backups

ansible-playbook backup_cisco_router_playbook.yaml 

ansible-playbook backup_cisco_router_playbook.yaml -i hosts

cat show_run_CSR1kv.txt

cat hosts

mkdir ios_configurations

ansible-playbook -v cisco_router_ipv6_config_playbook.yaml

cat ios_configurations/IPv6_output_CSR1kv.txt 




