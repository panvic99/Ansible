# Ansible
sudo apt-get update
sudo apt-get -y install pip
sudo apt-get -y install ansible
mkdir Ansible
cd Ansible/
touch ansible.pem
git clone https://github.com/panvic99/Ansible.git
cd Ansible/
git pull -- for changes


ansible-playbook playbook1.yml -i hosts.ini

