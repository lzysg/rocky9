vi /etc/NetworkManager/system-connections/ens33.nmconnection
[connection]
....
[ipv4]
address1=192.168.1.1
dns=192.168.1.1
mail-fail=false
method=manual

nmcli c reload /etc/NetworkManager/system-connections/ens33.nmconnection
nmcli c up /etc/NetworkManager/system-connections/ens33.nmconnection
