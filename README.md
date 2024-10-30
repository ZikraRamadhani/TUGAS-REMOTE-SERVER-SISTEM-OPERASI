# TUGAS-REMOTE-SERVER-SISTEM-OPERASI

Nama : Muhammad Zikra Ramadhani Andrian
Kelas : SK3A
NIM : 09011282328091
Mata Kuliah : Sistem Operasi

Laporan Percobaan Pengaplikasian Remote Server Linux Ubuntu dengan Linux Desktop Ubuntu

Tujuan Percobaan :
1. Mengetahui hal hal mengenai remote server linux
2. Mengetahui cara melakukan remote server di linux

Bahan yang diperlukan :
1. VirtualBox Machine
2. File pack iso Linux Desktop dan Linux Server

Langkah - Langkah :
1. Install pack iso Linux Desktop (24.04) dan Linux Server (24.04.01)
2. Buka VMbox, dan buat machine menggunakan file pack iso yang sudah diinstall (Linux Desktop dan Linux Server)
3. Jalankan machine yang sudah dibuat, dan buka machine Linux Server
4. Install OpenSSH di Linux Server dengan command "$ sudo install openssh-server"
![alt text](https://github.com/ZikraRamadhani/TUGAS-REMOTE-SERVER-SISTEM-OPERASI/blob/images/Screenshot%202024-10-30%20221818.png?raw=true)
6. Apabila sudah diinstall, cek status OpenSSH dengan menggunakan command "$ sudo apt status ssh"
7. Apabila OpenSSH sudah dalam kondisi aktif, lakukan cek ip adress untuk menyambungkan server dengan Linux Desktop dengan menggunakan command "$ ip a"
![alt text](https://github.com/ZikraRamadhani/TUGAS-REMOTE-SERVER-SISTEM-OPERASI/blob/images/Screenshot%202024-10-30%20221843.png?raw=true)
9. Buka machine Linux Desktop
10. Install OpenSSH di terminal dengan menggunakan command "$ sudo apt install openssh-client"
![alt text](https://github.com/ZikraRamadhani/TUGAS-REMOTE-SERVER-SISTEM-OPERASI/blob/images/Screenshot%202024-10-30%20221557.png?raw=true)
12. Setelah terinstall, cek status OpenSSH dengan menggunakan command "$ sudo apt status ssh"
13. Apabila OpenSSH sudah berjalan, input command "username@ipadress" untuk menyambungkan server dengan Linux Desktop (username : zkraaa, ip adress : 192.168.52.95)
![alt text](https://github.com/ZikraRamadhani/TUGAS-REMOTE-SERVER-SISTEM-OPERASI/blob/images/Screenshot%202024-10-30%20221749.png?raw=true)
15. Server sudah tersambung. 
