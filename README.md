# MarXray 
## Tested only on Ubuntu 20.04 <br>
Ini Marzban (https://github.com/Gozargah/Marzban) yang saya tambahi nginx agar vmess bisa multipath dan semua bisa ssl+nonssl
  
  ```html
 apt-get update && apt-get upgrade -y && apt dist-upgrade -y && update-grub && reboot
 ```
 ```html
 wget https://raw.githubusercontent.com/Agunxzzz/MarXray/main/sslmar.sh && chmod 755 sslmar.sh && ./sslmar.sh
 ```
 
  harus ada domain dulu
 
buka webnya dengan mengunjungi http://domainmu:8880/dashboard <br>
user: admin <br>
pass: admin

user pass bisa diganti dengan command
```html
nano /root/marzban/env
 ```
setelah disimpan, silahkan masuk ke folder marzban dengan 
```html
cd /root/marzban
 ```
lalu
```html
docker compose down && docker compose up -d
 ```
 
 Saat masuk, setting host di menu kanan atas <br>
 ![Screenshot_20230404-154004_Termius](https://raw.githubusercontent.com/Agunxzzz/MarXray/main/vmess.png)
 ![Screenshot_20230404-154004_Termius](https://raw.githubusercontent.com/Agunxzzz/MarXray/main/vless.png)
 ![Screenshot_20230404-154004_Termius](https://raw.githubusercontent.com/Agunxzzz/MarXray/main/trojan.png)
 <br>
 id.jateng.tech diatas, ganti dengan domainmu <br>
 vless ntls diatas typo, yg bener port 80 <br>
Bingung? PM aja :<a href="https://t.me/mochvpn" target=”_blank”><img src="https://img.shields.io/static/v1?style=for-the-badge&logo=Telegram&label=Telegram&message=Click%20Here&color=blue"></a><br>
<br>
# Telegram Bot
Marzban comes with an integrated Telegram bot that can handle server management, user creation and removal, and send notifications. This bot can be easily enabled by following a few simple steps, and it provides a convenient way to interact with Marzban without having to log in to the server every time.
<br>
To enable Telegram Bot:
<br>
set TELEGRAM_API_TOKEN to your bot's API Token<br>
set TELEGRAM_ADMIN_ID to your Telegram account's numeric ID, you can get your ID from @userinfobot

