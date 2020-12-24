Informasi :
# Update Module :
apt update && apt upgrade -y && update-grub

# Debian 10 :

wget -O install.sh "https://github.com/sshsedang/debian10/blob/main/install.sh?raw=true" && chmod +x install.sh && ./install.sh

# Untuk vps yang tidak langsung akses ke root :
Setiap login vps melalui terminal jalankan perintah "sudo -i"

1. sudo -i 
2. apt install wget -y && wget -O install.sh "https://github.com/sshsedang/debian10/blob/main/install.sh?raw=true" && chmod +x install.sh && ./install.sh

# Catatan :
Jika error saat mendownload silahkan jalankan perintah dibawah ini

echo "nameserver 8.8.8.8" > /etc/resolv.conf && echo "nameserver 8.8.4.4" >> /etc/resolv.conf

# Fiture :
- SSH 
- SSR
- Shadowsocks
- SSTP / L2TP 
- Openvpn
- Wireguard

# Dibuat Oleh :
Wegare
https://github.com/wagare123
