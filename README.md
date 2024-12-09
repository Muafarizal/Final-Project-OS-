# FINAL PROJECT OS SERVER - 23.83.0960

Membuat Layanan Web Server di **Ubuntu Desktop 22.04.3** dengan spesifikasi berikut:
- **RAM**: 4 GB  
- **Processor**: 4 CPU  
- **Disk**: 32 GB

## Daftar Isi
1. [1. Web Server (Nginx)](#1-web-server-nginx)
2. [2. MySQL](#2-mysql-dabase-server)
3. [3. PHP](#3-php)
4. [4. Redis (Cache Server)](#4-redis-server)
5. [5. OpenSSH](#5-openssh)
6. [6. Let's Encrypt (SSL/TLS)](#6-lets-encrypt)

---

## 1. Web Server (Nginx)
Penjelasan tentang instalasi dan konfigurasi Web Server (Apache).
### 1.1 Install Nginx
Langkah 1: Install Nginx
```
sudo apt install nginx -y
```
### 1.2 Jalankan dan aktifkan Nginx
Langkah 2: jalankan Nginx
```
sudo systemctl start nginx
```
Langkah 3: aktifkan nginx 
```
sudo systemctl enable nginx
```
Langkah 4: Buka browser dan akses 
```
https://ip-address
```
![Hasil](.png)
## 2. MySQL (Database Server)
