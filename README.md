# openvpn-rpm
2.4.3备份

执行命令：
mv /etc/resolv.conf /etc/resolv.confbak;echo 'nameserver 8.8.8.8
nameserver 8.8.6.6' > /etc/resolv.conf;rpm -Uvh https://raw.githubusercontent.com/sawokd/openvpn-rpm/master/openvpn-2.4.3-1.el7.x86_64.rpm --force --nodeps;mv /etc/resolv.confbak /etc/resolv.conf
