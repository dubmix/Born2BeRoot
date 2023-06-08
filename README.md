# Born2BeRoot

Born2BeRoot cmds

rocky debian?

 VM
software instead of hardware
can be used to test, can have several

APT is lower level
package manager
aptitude better. smarter

apparmor
security system MAC
sudo aa-status

password rules
sudo nano /etc/login.defs

lvm
logical volume manager
much more flexibilty
form of storage visualisation

ufw
use specific ports for added security

ssh
secure shell. auth mechanism between a client and a host, encrypts

cron
command line utility to schedule commands
sudo crontab -u root -e
cd usr/local/bin
sudo service cron stop


ssh pdelanno@ip -p 4242
sudo ufw status
sudo systemctl status ssh
getent group sudo
getent group user42
sudo adduser new username
sudo groupadd groupname
sudo usermod -aG groupname username
sudo chage -l username
sudo userdel -r username
sudo groupdel -r groupname
hostnamectl
hostnamectl set-hostname new_hostname
sudo shutdown now/exit
sudo nano /etc/hosts
lsblk -> partitions
dpkg -l | grep sudo
sudo ufw status numbered
sudo ufw allow 808
sudo ufw delete rule number
sudo systemctl status ssh

