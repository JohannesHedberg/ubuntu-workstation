sudo apt-get install software-properties-common
sudo apt-add-repository ppa:ansible/ansible
sudo apt-get update
sudo apt-get install ansible

sudo ansible-pull -U git@github.com:JohannesHedberg/ansible/ubuntu-workstation.git

