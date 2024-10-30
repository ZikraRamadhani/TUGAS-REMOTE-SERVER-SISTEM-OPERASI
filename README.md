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
5. Apabila sudah diinstall, cek status OpenSSH dengan menggunakan command "$ sudo apt status ssh"
6. Apabila OpenSSH sudah dalam kondisi aktif, lakukan cek ip adress untuk menyambungkan server dengan Linux Desktop dengan menggunakan command "$ ip a"
7. Buka machine Linux Desktop
8. Install OpenSSH di terminal dengan menggunakan command "$ sudo apt install openssh-client"
9. Setelah terinstall, cek status OpenSSH dengan menggunakan command "$ sudo apt status ssh"
10. Apabila OpenSSH sudah berjalan, input command "username@ipadress" untuk menyambungkan server dengan Linux Desktop (username : zkraaa, ip adress : 192.168.52.95)
11. Server sudah tersambung. 
