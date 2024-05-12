# thm
a cli client to connect to Hack the box or other openvpn

### Instalation
```
sudo wget https://raw.githubusercontent.com/chukfinley/htb/main/thm -O /usr/bin/thm
sudo chmod +x /usr/bin/thm
sudo mkdir -p /etc/thm/
sudo cp youropenvpnlocation /etc/thm/thm.ovpn
```

### Usage

Connect
```
sudo thm c
```
Disconnect
```
sudo thm d
```
Status shows output of the connect command
```
sudo thm s
```

