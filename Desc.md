## Router:

Setiap router akan memiliki IP di jaringan yang berbeda (misalnya, 192.168.1.1, 192.168.2.1, dan 192.168.3.1). 
Router ini juga berfungsi sebagai gateway untuk masing-masing jaringan lokal di bawahnya.
## Subnet:

Setiap jaringan lokal akan menggunakan subnet mask 255.255.255.0 (/24), yang memungkinkan hingga 254 perangkat pada masing-masing subnet.
## PC dan Switch:

Setiap PC akan mendapatkan IP secara manual atau otomatis dari router dengan jaringan sesuai dengan router yang terhubung.
Rincian Alokasi IP
Router 1 (Subnet 192.168.1.0/24)

IP Router 1: 192.168.1.1 (Gateway untuk jaringan ini) <br>
Switch: Tidak memerlukan IP (kecuali jika switch yang digunakan adalah switch yang dikelola, maka bisa diberikan IP untuk akses manajemen, misalnya 192.168.1.2) <br>
PC yang terhubung ke Router 1: <br>
PC 1: 192.168.1.10 <br>
PC 2: 192.168.1.11 <br>
PC 3: 192.168.1.12 <br>
PC 4: 192.168.1.13 <br>
Router 2 (Subnet 192.168.2.0/24) <br>

IP Router 2: 192.168.2.1 (Gateway untuk jaringan ini) <br>
Switch: 192.168.2.2 (jika diperlukan) <br>
PC yang terhubung ke Router 2: <br>
PC 5: 192.168.2.10 <br>
PC 6: 192.168.2.11 <br>
PC 7: 192.168.2.12 <br>
PC 8: 192.168.2.13 <br>
Router 3 (Subnet 192.168.3.0/24) <br>

IP Router 3: 192.168.3.1 (Gateway untuk jaringan ini) <br>
Switch: 192.168.3.2 (jika diperlukan) <br>
PC yang terhubung ke Router 3: <br>
PC 9: 192.168.3.10 <br>
PC 10: 192.168.3.11 <br>
PC 11: 192.168.3.12 <br>
PC 12: 192.168.3.13 <br>
Alokasi IP Summary <br>
Router 1: 192.168.1.1 (Subnet: 192.168.1.0/24, Gateway: 192.168.1.1) <br>
Router 2: 192.168.2.1 (Subnet: 192.168.2.0/24, Gateway: 192.168.2.1) <br>
Router 3: 192.168.3.1 (Subnet: 192.168.3.0/24, Gateway: 192.168.3.1) <br>
Dengan konfigurasi ini: <br>

Setiap jaringan lokal di bawah router yang berbeda akan menggunakan rentang IP berbeda untuk menghindari konflik.<br>
Semua PC dalam satu jaringan dapat saling berkomunikasi, dan masing-masing jaringan dapat mengakses internet melalui gateway (router).
