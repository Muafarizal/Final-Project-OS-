# FINAL PROJECT OS SERVER - 23.83.0962

Membuat Layanan Web Server di **Ubuntu Desktop 22.04.3** dengan spesifikasi berikut:
- **RAM**: 4 GB  
- **Processor**: 4 CPU  
- **Disk**: 32 GB

## Daftar Isi
1. [1. Web Server (Apache)](#1-web-server-apache)
2. [2. PHP](#2-php)
3. [3. Samba](#3-samba)
4. [4. SSH Server](#4-ssh-server)
5. [5. FTP Server (vsftpd)](#5-ftp-server-vsftpd)
6. [6. Proxy Server (Squid)](#6-proxy-server-squid)

---

## 1. Web Server (Apache)
Penjelasan tentang instalasi dan konfigurasi Web Server (Apache).
### 1.1 Install Apache
Langkah 1: Install Apache
```
sudo apt install apache2 -y
```
### 1.2 Konfigurasi Apache
Langkah 2: Periksa status Apache
```
sudo service apache2 status
```
Langkah 3: Izinkan port 80 
```
sudo ufw allow 80/tcp
```
Langkah 4: Buka browser dan akses 
```
https://server-ip-address
```
![Hasil](hasil apache.png)
## 2. PHP
