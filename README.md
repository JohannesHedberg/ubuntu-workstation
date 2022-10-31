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
spotify-client  
pwgen  
subnetcalc  
nmap  
flameshot  
tree  
xsel  
neofetch  
virt-manager  
nordpass  
prospect-mail  
bridge-utils  
cpu-checker  
libvirt-clients  
libvirt-daemon  
qemu  
qemu-kvm  


### Gnome:
create a git folder in home  
create a hidden themes folder in home  
copy the nord blueish theme for gnome to .themes and apply it  
install python-psutil which will enable setting things like wallpaper with this playbook  
set wallpaper and lock screen background  
install nord theme for spotify  
install nord theme for vim    

### Commands:
add the alias "clipboard" which will copy contents of command output to clipboard. example:  
`echo "hello" | clipboard` 

### Cron:
set a cronjob that will check this repo for changes every 10 min and run this playbook if there's been an update 