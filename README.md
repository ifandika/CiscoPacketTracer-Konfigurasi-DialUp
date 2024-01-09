## Cisco Packet Tracer: Konfigurasi DialUp
DialUp adalah 

## Langkah-langkah
1.Membuat topologi jaringan, dan perangkat yang digunakan.
```Txt
PC
- Jumlah 2
- DHCP Client
Server DNS
- IP: 8.8.8.8
Server Web Server
- IP: 
Router 1891
Cloud
```
![](resource/img/)

2.Pada Router konfigurasi IP ke server.
```Bash
Router> en
Router# config t
Routet(config)# interface fa0/0 
Routet(config)# ip address ...
Routet(config)# no shutdown
Routet(config)# exit
Routet(config)# interface fa0/1
Routet(config)# ip address ...
Routet(config)# no shutdown
Routet(config)# exit
```