Buat 1 VM di BitnetGio dengan spesifikasi sebagai berikut Gateway 1 CPU, 1 GB RAM, 60 GB Storage 
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Frontend/Screenshot%20from%202023-12-19%2020-19-11.png?raw=true)
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Frontend/Screenshot%20from%202023-12-23%2017-17-46.png?raw=true)

Setelah server sudah dibuat maka langkah selanjutnya adalah membuat user baru
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Frontend/Screenshot%20from%202023-12-23%2018-14-56.png?raw=true)
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Frontend/Screenshot%20from%202023-12-23%2018-15-05.png?raw=true)

Jangan lupa untuk melakukan update dan upgrade
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Frontend/Screenshot%20from%202023-12-23%2018-39-46.png?raw=true)

Buatlah user baru pada server dan izinkan server tersebut
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Frontend/Screenshot%20from%202023-12-23%2018-50-07.png?raw=true)
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Frontend/Screenshot%20from%202023-12-23%2021-03-24.png?raw=true)

Implementasikan penggunaan ssh pada server yang sudah di buat
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Frontend/Screenshot%20from%202023-12-23%2021-10-11.png?raw=true)
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Frontend/Screenshot%20from%202023-12-23%2021-10-27.png?raw=true)

kemudian buat ssh pada lokal dan implementasian pada server
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Frontend/Screenshot%20from%202023-12-23%2022-25-49.png?raw=true)
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Frontend/Screenshot%20from%202023-12-23%2022-31-41.png?raw=true)
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Frontend/Screenshot%20from%202023-12-23%2022-31-51.png?raw=true)

Deploy aplikasi wayshub frontend dengan menggunakan node js v14
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Frontend/Screenshot%20from%202023-12-23%2022-58-26.png?raw=true)
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Frontend/Screenshot%20from%202023-12-23%2023-09-42.png?raw=true)

Menginstal npm
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Frontend/Screenshot%20from%202023-12-23%2023-12-30.png?raw=true)

Kemudian menjalankan aplikasi
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Frontend/Screenshot%20from%202023-12-23%2023-14-50.png?raw=true)

Instal pm2 secara global untuk menjalankan aplikasi dibalik layar
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Frontend/Screenshot%20from%202023-12-23%2023-24-55.png?raw=true)
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Frontend/Screenshot%20from%202023-12-23%2023-32-53.png?raw=true)

Aplikasi sudah berjalan
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Frontend/Screenshot%20from%202023-12-23%2023-33-06.png?raw=true)

Jika ingin menghentikan aplikasi maka gunakan perintah pm2 stop
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Frontend/Screenshot%20from%202023-12-23%2023-38-33.png?raw=true)

Kemudian install nginx
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Frontend/Screenshot%20from%202023-12-23%2023-43-13.png?raw=true)

Kemudian buat reverse proxy
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Frontend/Screenshot%20from%202023-12-24%2000-38-03.png?raw=true)
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Frontend/Screenshot%20from%202023-12-24%2001-09-13.png?raw=true)

Nginx telah sukses dibuat
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Frontend/Screenshot%20from%202023-12-24%2001-09-13.png?raw=true)

Kemudian jalankan aplikasi
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Frontend/Screenshot%20from%202023-12-26%2016-40-59.png?raw=true)


