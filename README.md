# MarXray
## Tested only on Ubuntu 20.04 <br>
Ini Marzban (https://github.com/Gozargah/Marzban) yang saya modif agar vmess bisa multipath dan semua bisa ssl+nonssl
  
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
cd /root/marzban
lalu
docker compose down
docker compose up -d



