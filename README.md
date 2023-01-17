
## Script Information Features
- CPU MIN 1 CORE
- RAM 1GB
- VMESS WS TLS 443
- VMESS WS NON TLS 80
- VMESS GRPC 443
- VLESS WS TLS 443
- VLESS WS NON TLS 80
- VLESS GRPC 443
- TROJAN/TROJAN GO WS TLS 443
- TROJAN/TROJAN GO GRPC 443
- SHADOWSOCKS WS 443
- SHADOWSOCKS GRPC 443
- IPv6 : [OFF]
- Timezone : Asia/Jakarta (GMT +7)
 
<h3 align="center">Installation</h3>

## 1.
<img src="https://img.shields.io/badge/Update%20_&_%20Upgrade-green">

  ```html
apt-get update && apt-get upgrade -y && update-grub && sleep 2 && reboot
```

## 2.0
<img src="https://img.shields.io/badge/Login_Root%20VPS-green">

* Login ke VPS dan Aktifkan Root Sementara

  
```html
sudo su
cd
cd
```

### 3.

  <img src="https://img.shields.io/badge/Install_Layanan_Xray%20-green">


```html
rm -rf setup.sh && apt-get update && apt-get upgrade && apt install curl && apt install screen && wget -q https://raw.githubusercontent.com/firdaus-rx/xray/main/setup.sh && chmod +x setup.sh && screen -S Xray ./setup.sh
```

<h3 align="center">Additional Info</h3>
Recommended OS :

- Ubuntu 18.04 & 20.04 x64 bit
