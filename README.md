# debian 10
wget -O install.sh "https://github.com/wegare123/vps-debian/blob/main/install.sh?raw=true" && chmod +x install.sh && ./install.sh

# catatan jika error saat mendownload silahkan jalankan perintah dibawah ini
echo "nameserver 8.8.8.8" > /etc/resolv.conf && echo "nameserver 8.8.4.4" >> /etc/resolv.conf
