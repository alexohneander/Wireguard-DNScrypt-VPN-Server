# Wireguard-DNScrypt-VPN-Server  x86 / arm64

### Version 2022.05.06
major changes : 
 - add support for ubuntu 22.04
 - all other things i forgot :)

## **Setup Wireguard VPN Server fast and easy  - with ** 
* DNScrypt with anonymized_dns / DNSSEC (unbound)
* Ad-, Maleware-, ..., Blocking
* 3 config files  for your clients
* add or remove clients with add_client.sh / remove_client.sh 
* backup, restore and unistall options

## How to install :  
* Use a fresh / clean and  up to date  **server** os   debian or ubuntu
* Copy the lines for your system below, and run it and follow the instructions  
* My script base_setup.sh need to installed -> [repository](https://gitlab.com/zzzkeil/base_setups)  
   * if not installed, base_setup.sh will downloaded for you, just follow the instructions.  

----------------------------------------

###### Server x86 - Debian 11 and Ubuntu 20.04 / 22.04 :
```
wget -O  wireguard-dnscrypt_blocklist_x86.sh https://codeberg.org/zzzkeil/Wireguard-DNScrypt-VPN-Server/raw/branch/master/debian_ubuntu/wireguard-dnscrypt_blocklist_x86.sh
chmod +x wireguard-dnscrypt_blocklist_x86.sh
./wireguard-dnscrypt_blocklist_x86.sh
```


@ the end you see the QR Code for your wiregaurd app.

-----------------------------------------





###### Server arm64 - Ubuntu 20.04 (status: not finished) :
<details>
  <summary>Click to expand!</summary>
  
```
(testing on a pi 4 on my home network)

is currently in maintenance - comming back in a few .....? - 

```
 </details>
-----------------------------------------

## How to add or remove clients :
```
run ./add_client.sh or ./remove_client.sh
```


## How to backup or restore settings :
```
run ./wg_config_backup.sh or ./wg_config_restore.sh
```
-----------------------------------------


# Other repository : Wireguard-tor-server gateway

https://gitlab.com/zzzkeil/wireguard-dnscrypt-tor-server 

** project target

    encrypted wireguard vpn connection to server
    all traffic from wireguard clients will go over tor network
    dns nameresulotion over dnscrypt (Anonymized DNS) with blocklists
    onion (darknet) nameresulotion over dnscrypt forward to tor


###### BETA ----  Server x86 - Debian 11 and Ubuntu 20.04 / 22.04  :
```
wget -O  beta-wireguard-tor-dnscrypt_blocklist_x86.sh https://gitlab.com/zzzkeil/wireguard-dnscrypt-tor-server/-/raw/main/debian_ubuntu/wireguard-tor-dnscrypt_blocklist_x86.sh
chmod +x beta-wireguard-tor-dnscrypt_blocklist_x86.sh
./beta-wireguard-tor-dnscrypt_blocklist_x86.sh
```

