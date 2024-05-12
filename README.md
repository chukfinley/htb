# htb
a cli client to connect to Hack the box or other openvpn

### Instalation
```
sudo wget https://raw.githubusercontent.com/chukfinley/htb/main/htb -O /usr/bin/htb
sudo chmod +x /usr/bin/htb
sudo mkdir -p /etc/htb/
sudo cp youropenvpnlocation /etc/htb/htb.ovpn
```

### Usage

Connect
```
sudo htb connect
```
Disconnect
```
sudo htb disconenct
```
