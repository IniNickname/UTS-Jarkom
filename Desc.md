## Router:

Setiap router akan memiliki IP di jaringan yang berbeda (misalnya, 192.168.1.1, 192.168.2.1, dan 192.168.3.1). 
Router ini juga berfungsi sebagai gateway untuk masing-masing jaringan lokal di bawahnya.
Subnet:

Setiap jaringan lokal akan menggunakan subnet mask 255.255.255.0 (/24), yang memungkinkan hingga 254 perangkat pada masing-masing subnet.
PC dan Switch:

Setiap PC akan mendapatkan IP secara manual atau otomatis dari router dengan jaringan sesuai dengan router yang terhubung.
Rincian Alokasi IP
Router 1 (Subnet 192.168.1.0/24)

IP Router 1: 192.168.1.1 (Gateway untuk jaringan ini)
Switch: Tidak memerlukan IP (kecuali jika switch yang digunakan adalah switch yang dikelola, maka bisa diberikan IP untuk akses manajemen, misalnya 192.168.1.2)
PC yang terhubung ke Router 1:
PC 1: 192.168.1.10
PC 2: 192.168.1.11
PC 3: 192.168.1.12
PC 4: 192.168.1.13
Router 2 (Subnet 192.168.2.0/24)

IP Router 2: 192.168.2.1 (Gateway untuk jaringan ini)
Switch: 192.168.2.2 (jika diperlukan)
PC yang terhubung ke Router 2:
PC 5: 192.168.2.10
PC 6: 192.168.2.11
PC 7: 192.168.2.12
PC 8: 192.168.2.13
Router 3 (Subnet 192.168.3.0/24)

IP Router 3: 192.168.3.1 (Gateway untuk jaringan ini)
Switch: 192.168.3.2 (jika diperlukan)
PC yang terhubung ke Router 3:
PC 9: 192.168.3.10
PC 10: 192.168.3.11
PC 11: 192.168.3.12
PC 12: 192.168.3.13
Alokasi IP Summary
Router 1: 192.168.1.1 (Subnet: 192.168.1.0/24, Gateway: 192.168.1.1)
Router 2: 192.168.2.1 (Subnet: 192.168.2.0/24, Gateway: 192.168.2.1)
Router 3: 192.168.3.1 (Subnet: 192.168.3.0/24, Gateway: 192.168.3.1)
Dengan konfigurasi ini:

Setiap jaringan lokal di bawah router yang berbeda akan menggunakan rentang IP berbeda untuk menghindari konflik.
Semua PC dalam satu jaringan dapat saling berkomunikasi, dan masing-masing jaringan dapat mengakses internet melalui gateway (router).
