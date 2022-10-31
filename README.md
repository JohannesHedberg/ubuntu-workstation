# How to run:
```
sudo apt-get install -y software-properties-common  
sudo apt install -y git
sudo apt-add-repository ppa:ansible/ansible  
sudo apt-get update  
sudo apt-get install -y ansible  
sudo ansible-pull -U https://github.com/JohannesHedberg/ubuntu-workstation.git
```


# This ansible playbook will run the following tasks: 
### Users:
Create user "ansible" and add it to sudoers, which will run the ansible tasks.

### Repositories:
Add repositories for:  
github cli  
brave  
spotify  

### Packages:
snapd  
apt-transport-https  
curl  
brave-browser  
notepadqq  
git  
gh  
konsole  
vim  
spotify-client  
pwgen  
subnetcalc  
nmap  
flameshot  
tree  
xsel  
gnome-tweaks  
gnome-shell-extensions  
neofetch  
nordpass  
bridge-utils  
cpu-checker  
libvirt-clients  
libvirt-daemon  
qemu  
qemu-kvm  
virt-manager  


### Gnome:
create git folder in home  
create .themes folder in home  
copy the nord theme for gnome to /usr/share/.themes and apply it  
install python-psutil which will enable setting things like wallpaper with this playbook  
set wallpaper and lock screen background  
set profile pic  


### Commands:
add the alias "clipboard" which will copy contents of command output to clipboard. example:  
`echo "hello" | clipboard`  
enable pgup and pgdown to search in bash history in /etc/inputrc

### Cron:
set a cronjob that will check this repo for changes every 10 min and run this playbook if there's been an update 