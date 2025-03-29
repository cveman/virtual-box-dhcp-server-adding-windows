# virtual-box-dhcp-server-adding-windows

goto:
C:\Program Files\Oracle\VirtualBox>

command:
VBoxManage dhcpserver add --network=KaliLAB --server-ip=192.168.3.1 --netmask=255.255.255.0 --lower-ip=192.168.3.2 --upper-ip=192.168.3.254 --enable
