pada repository ini berisikan source membuat aplikasi sederhana menggunakan bahasa pemrograman PHP 7.1, database MySQL, dan apache web server. Pembuatan aplikasi ini adalah sebagai berikut :

#buat file docker-compose.yml dan Dockerfile, kemudian buat folder "dump" dan folder "www". folder "dump" berisikan database yang akan digunakan untuk aplikasi yang akan anda buat. Dan folder "www" berisikan file index.php, cofig.php, dll untuk menjalankan crud PHP.

#di dalam docker-compose saya menggunakan php7.1 sebagai bahasa pemrograman, apache sebagai web server, dan mysql sebagai database server.
didalam file Dockerfile berisikan pemanggilan image php 7.1 yang akan saya gunakan.

#untuk menjalankan docker compose gunakan perintah "docker-compose up -d"