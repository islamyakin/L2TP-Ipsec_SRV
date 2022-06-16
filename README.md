# L2TP/IPsec Server on Ubuntu 20.04
### Untuk memudahkan instalasi dan konfigurasi L2TP/IPsec VPN server kita gunakan script installer dari [INI](https://github.com/islamyakin/L2TP-Ipsec_SRV/) di GitHub.
Download installernya.
```
wget https://raw.githubusercontent.com/islamyakin/L2TP-Ipsec_SRV/main/vpnsetupservera.sh -O installervpn.sh
```
```
sh installervpn.sh	
```
# Menambah User
Download script untuk menambah user vpnuser.sh
```
wget -O vpnuser.sh https://raw.githubusercontent.com/hwdsl2/setup-ipsec-vpn/master/extras/add_vpn_user.sh	
```
Jalankan scriptnya disertai dengan username dan password yang mau dibuat.
```
sh vpnuser.sh 'username' 'password'
```
Selamat mencoba 🙂
Special Thanks to Lin Song
