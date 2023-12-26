Membuat VM pada BiznetGio dengan spesifikasi 2 CPU 2 GB RAM 60 GB Storage
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Backend/Screenshot%20from%202023-12-26%2011-06-29.png?raw=true)
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Backend/Screenshot%20from%202023-12-26%2011-06-29.png?raw=true)

Langkah selanjutnya yaitu membuat server
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Backend/Screenshot%20from%202023-12-26%2011-48-54.png?raw=true)

Seetelah server di buat, maka langah selanjutnya yaitu membuat user baru dan mengizinkan user tersebut
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Backend/Screenshot%20from%202023-12-26%2012-02-55.png?raw=true)
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Backend/Screenshot%20from%202023-12-26%2012-06-33.png?raw=true)
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Backend/Screenshot%20from%202023-12-26%2012-09-23.png?raw=true)

Kemudian install mysql untuk membuat database
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Backend/Screenshot%20from%202023-12-26%2012-43-42.png?raw=true)

Kemudia setup secure_instalation
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Backend/Screenshot%20from%202023-12-26%2012-59-05.png?raw=true)

Untuk melindungi database maka buatlah password untuk root user
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Backend/Screenshot%20from%202023-12-26%2013-11-28.png?raw=true)
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Backend/Screenshot%20from%202023-12-26%2013-18-05.png?raw=true)

Setelah password dibuat,maka untu login ke user akan diminta untu memasukkan password
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Backend/Screenshot%20from%202023-12-26%2013-18-51.png?raw=true)

Kemudia buat user baru pada mysql
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Backend/Screenshot%20from%202023-12-26%2013-24-46.png?raw=true)
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Backend/Screenshot%20from%202023-12-26%2013-29-40.png?raw=true)

Kemudia buat database baru pada mysql dan membuat priveleges supaya database dapat diakses
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Backend/Screenshot%20from%202023-12-26%2013-37-33.png?raw=true)

Jangan lupa untuk mengubah mysql bind address pada`/etc/mysql/mysql.conf.d/mysqld.cnf
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Backend/Screenshot%20from%202023-12-26%2014-40-21.png?raw=true)
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Backend/Screenshot%20from%202023-12-26%2014-53-45.png?raw=true)

Deploy aplikasi wayshub-backend dan setup konfigurasi wayshub-backend/config/config.json
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Backend/Screenshot%20from%202023-12-26%2014-55-06.png?raw=true)
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Backend/Screenshot%20from%202023-12-26%2014-58-34.png?raw=true)

Menginstal sequelize-cli
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Backend/Screenshot%20from%202023-12-26%2015-04-39.png?raw=true)
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Backend/Screenshot%20from%202023-12-26%2015-06-10.png?raw=true)

KEmudian running migration
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Backend/Screenshot%20from%202023-12-26%2015-08-15.png?raw=true)

Setelah itu mysql sudah bisa dideploy ke server
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Backend/Screenshot%20from%202023-12-26%2015-11-43.png?raw=true)
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Backend/Screenshot%20from%202023-12-26%2015-11-52.png?raw=true)

Deploy aplikasi pada pm2
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Backend/Screenshot%20from%202023-12-26%2015-18-57.png?raw=true)
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Backend/Screenshot%20from%202023-12-26%2016-01-18.png?raw=true)

Clone aplikasi wayshub-frontend
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Backend/Screenshot%20from%202023-12-26%2016-03-51.png?raw=true)
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Backend/Screenshot%20from%202023-12-26%2016-37-08.png?raw=true)

Install npm
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Backend/Screenshot%20from%202023-12-26%2016-38-51.png?raw=true)

Jalankan apliasi
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Backend/Screenshot%20from%202023-12-26%2016-40-54.png?raw=true)
![alt text](https://github.com/irma2909/devops19-dumbways-irma/blob/master/SS%20Deploy%20Aplikasi%20Backend/Screenshot%20from%202023-12-26%2016-40-59.png?raw=true)
