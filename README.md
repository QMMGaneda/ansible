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
