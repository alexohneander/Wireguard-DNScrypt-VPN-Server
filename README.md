# Wireguard-DNScrypt-VPN-Server

### New Version 2020.12.28 running / testing
### major changes : words like black* to block* and white* to allwo* , and some small other changes.

## In under 5 minutes* with just a few klicks
### Setup Wireguard VPN Server,
#### incl. ipv4 and ipv6
#### incl. DNScrypt / DNSSEC (unbound)
#### incl. Ad-, Maleware-, ..., Blocking
#### incl. 10 ready client config files  ( one with QR-Code in terminal )
##### add_client.sh / remove_client.sh under development in tools

## How to install :
#### the server has to be prepared with my script base_setup.sh
##### if the base is not installed, the script below will download this one for you.
----------------------------------------

###### For Ubuntu 20.04 :
```
wget -O  wireguard-dkms_dnscrypt_blocklist.sh https://raw.githubusercontent.com/zzzkeil/Wireguard-DNScrypt-VPN-Server/master/debian_ubuntu/wireguard-dkms_dnscrypt_blocklist.sh

chmod +x wireguard-dkms_dnscrypt_blocklist.sh

./wireguard-dkms_dnscrypt_blocklist.sh
```
-----------------------------------------

@ the end you see the QR Code for your wiregaurd app.
example:
[![example](https://zeroaim.de/img/wgexsqr.png)](https://github.com/zzzkeil/Wireguard-DNScrypt-VPN-Server)

-----------------------------------------





( *less then 5 minutes on my v-server together with base_setup.sh ) 
