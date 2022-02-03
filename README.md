# Script V-Code (Version 1)
 Welcome Dear😊

 <h2 align="center">AutoScript VPN By V-Code <img src="https://img.shields.io/badge/Version-1.6-blue.svg"></h2>


<h2 align="center"> Supported Linux Distribution</h2>
<p align="center"><img src="https://d33wubrfki0l68.cloudfront.net/5911c43be3b1da526ed609e9c55783d9d0f6b066/9858b/assets/img/debian-ubuntu-hover.png"></p>
<p align="center"><img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%2010&message=Buster&color=blue"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%2011&message=Bullseye&color=blue"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2018&message=18.04 LTS&color=blue"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2020&message=20.04 LTS&color=blue"></p>

<p align="center"><img src="https://img.shields.io/badge/Service-OpenSSH-success.svg"> <img src="https://img.shields.io/badge/Service-Dropbear-success.svg">  <img src="https://img.shields.io/badge/Service-Websocket-success.svg"> <img src="https://img.shields.io/badge/Service-BadVPN-success.svg">  <img src="https://img.shields.io/badge/Service-Stunnel-success.svg">  <img src="https://img.shields.io/badge/Service-OpenVPN-success.svg">  <img src="https://img.shields.io/badge/Service-Squid3-success.svg">  <img   src="https://img.shields.io/badge/Service-Webmin-success.svg">  <img src="https://img.shields.io/badge/Service-OHP-success.svg">  <img
src="https://img.shields.io/badge/Service-Xray-success.svg">  <img
src="https://img.shields.io/badge/Service-V2ray-success.svg">  <img src= "https://img.shields.io/badge/Service-SSR-success.svg">  <img src="https://img.shields.io/badge/Service-Trojan-success.svg">  <img src="https://img.shields.io/badge/Service-WireGuard-success.svg"> <img src="https://img.shields.io/badge/Service-Shadowsocks-success.svg">

## Commands : <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=powershell&label=Shell&message=Bash%20Script&color=lightgray">

## Update & Upgrade First Your VPS for Debian 10 & 11

  ```html
  apt-get update && apt-get upgrade -y && update-grub && sleep 2 && reboot

  ```

## Update & Upgrade First Your VPS for Ubuntu 18.04 & 20.04

  ```html
  apt-get update && apt-get upgrade -y && apt dist-upgrade -y && update-grub && sleep 2 && reboot

  ```
 
## Installation Script

  ```html
  sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl && wget https://raw.githubusercontent.com/coding006/x-code/main/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh

  ```
 
 ## Copy & paste 👇👇 to your VPS if ERROR (WG & SSTP ONLY)
 ## Wireguard

  ```html
  echo "deb http://deb.debian.org/debian/ unstable main" >/etc/apt/sources.list.d/unstable.list
printf 'Package: *\nPin: release a=unstable\nPin-Priority: 90\n' >/etc/apt/preferences.d/limit-unstable
apt update
apt install -y wireguard-tools iptables iptables-persistent
apt install -y linux-headers-$(uname -r)

  ```
 
  ## SSTP

  ```html
  wget https://raw.githubusercontent.com/coding006/x-code/main/install/sstp.sh && chmod +x sstp.sh && screen -S sstp ./sstp.sh
 rm -f /root/sstp.sh

  ```

## Info :

 ## Script for Sell Only. Contact owner on Telegram @Virtual_NW <a href="https://t.me/Virtual_NW" target=”_blank”><img src="https://img.shields.io/static/v1?style=for-the-badge&logo=Telegram&label=Telegram&message=Click%20Here&color=blue"></a>

 ## For Buy Script : Contact Telegram @Virtual_NW <a href="https://t.me/Virtual_NW" target=”_blank”><img src="https://img.shields.io/static/v1?style=for-the-badge&logo=Telegram&label=Telegram&message=Click%20Here&color=blue"></a>

 ## Main Menu
 
![Screenshot_20220203_061910](https://user-images.githubusercontent.com/96321013/152276028-439a0810-3097-41cb-9e47-c7d92874fc5d.jpg)

  ## Status Running
 
![IMG_20220204_040910](https://user-images.githubusercontent.com/96321013/152420954-3109dbf8-98d7-47f7-af2d-043d4cd309ee.jpg)

  ## Service & Port
 
![IMG_20220204_040923](https://user-images.githubusercontent.com/96321013/152421172-03bb47c0-1e8f-40bf-8663-65fb20726b26.jpg)


## Description :

  Service & Port

  - OpenSSH                 : 22
  - OpenVPN                 : TCP 1194, UDP 2200, SSL 110
  - Stunnel4                : 222, 777
  - Dropbear                : 442, 109
  - OHP Dropbear            : 8585
  - OHP SSH                 : 8686
  - OHP OpenVPN             : 8787
  - Websocket SSH(HTTP)     : 2081
  - Websocket SSL(HTTPS)    : 222
  - Websocket OpenVPN       : 2084
  - Squid Proxy             : 3128, 8080, 8000
  - Badvpn                  : 7100, 7200, 7300
  - Nginx                   : 81
  - Wireguard               : 5820
  - L2TP/IPSEC VPN          : 1701
  - PPTP VPN                : 1732
  - SSTP VPN                : 444
  - Shadowsocks-R           : 1443-1543
  - SS-OBFS TLS             : 2443-2543
  - SS-OBFS HTTP            : 3443-3543
  - XRAY Vmess TLS          : 443
  - XRAY Vmess None TLS     : 80
  - XRAY Vless TLS          : 8443
  - XRAY Vless None TLS     : 8880
  - XRAY Vless Xtls DIRECT  : 9443
  - XRAY Vmess Grpc TLS     : 2083
  - XRAY Vless Grpc TLS     : 880
  - XRAY Trojan TCP TLS     : 2087
  - XRAY Trojan GRPC TLS    : 2087

 >>> Server Information & Other Features
   - Timezone                 : Asia/Kuala_Lumpur (GMT +8)
   - Fail2Ban                 : [ON]
   - DDOS Dflate              : [ON]
   - IPtables                 : [ON]
   - Auto-Reboot              : [OFF]
   - IPv6                     : [OFF]
   - Auto-Remove-Expired      : [ON]
   - Auto Delete Expired Account
   - Fully automatic script
   - VPS settings
   - Admin Control
   - Change port
   - Full Orders For Various Services

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## Telegram

[V-Code](https://t.me/Virtual_NW)

[Group V-Code](https://t.me/+HtRm-s0MLBgxODZl)

[Channel V-Code](https://t.me/Virtual_NW_Channel)

## Credit :

*   V-Code

*   Project X

*   V2ray

<p align="center">
  <a><img src="https://img.shields.io/badge/Copyright%20©-VCode%20AutoScriptVPN%202022.%20All%20rights%20reserved...-blueviolet.svg" style="max-width:200%;">
    </p>
   </p>
