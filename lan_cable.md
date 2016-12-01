1) two ubuntu machines
ifconfig eth0 10.0.0.1 up
ifconfig eth0 10.0.0.2 up

2)persist eth setting
auto enp0s10
iface enp0s10 inet static
address 10.0.0.2
netmask 255.255.255.0
