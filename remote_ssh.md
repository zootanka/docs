https://help.ubuntu.com/lts/serverguide/openssh-server.html

sudo ufw allow 22

/etc/ssh/sshd_config
add AllowUsers zootanka

/etc/ssh/ssh_config
enable Port 22
