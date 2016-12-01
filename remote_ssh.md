https://help.ubuntu.com/lts/serverguide/openssh-server.html

sudo ufw allow 22

/etc/ssh/sshd_config
add AllowUsers zootanka

/etc/ssh/ssh_config
enable Port 22

netstat -anp | grep sshd

ufw verbose

mkdir ~/.ssh
chmod 700 ~/.ssh
ssh-keygen -t rsa
ssh-copy-id zootanka@192.168.1.13
