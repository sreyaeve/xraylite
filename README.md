<!DOCTYPE html>
  
<h2 align="center"> AutoScript Xray Lite</h2>
<p align="center"><img src="https://d33wubrfki0l68.cloudfront.net/5911c43be3b1da526ed609e9c55783d9d0f6b066/9858b/assets/img/debian-ubuntu-hover.png"width="400"></p>
<p align="center"><img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%209&message=Stretch&color=purple"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%2010&message=Buster&color=purple">  <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2018&message=Lts&color=red"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2020&message=Lts&color=red">
</p>
  
  ##  NO Register IP
This is a Free installation, sorry if u find a bug

<br>

  ### Recommended Os

<br>

Ubuntu 20 LTS
<br>
</b>

  ##  Informasi Service dan Port

<br>

[Service]<br>
Xray Vmess<br>
Xray Vless<br>
Xray Trojan<br>
Shadowsocks<br>
[Port]<br>
TLS/HTTPS = 443, 8443, 2053, 2083, 2087<br>
Non TLS/HTTP = 80, 2082, 8880, 8080, 2086, 2052<br>
[Fitur]<br>
Vmess Support Custom Path dan Multi Path<br>
Autodelete Expired Account<br>
Backup & Restore<br>
<br>
<br>
Update Repo Khusus Debian 10 <br>
  
  ```html
apt update -y && apt upgrade -y && apt dist-upgrade -y && reboot
  ```
  
Update Repo Khusus Ubuntu 20 LTS<br>
  
  ```html
apt-get update && apt-get upgrade -y && apt dist-upgrade -y && update-grub && reboot
 ```

Link Instalasi<br>

  ```html
apt update -y && apt upgrade -y && sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/sreyaeve/xraylite/main/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh
 ```

