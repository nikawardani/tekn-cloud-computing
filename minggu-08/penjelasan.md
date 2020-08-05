<h1>Screenshot_1.png</h1>

![gambar1](minggu-08/Screenshot_1.png)
praktikum ini langkah pertama yang harus dilakukan adalah mengecek docker compose yang ada, yang dilakukan dengan cara memberikan perintah docker-compose – v dari perintah tersebut diketahui terdapat docker-compose dengan version 1.21.2 dengan build a133471.


![gambar2](minggu-08/Screenshot_2.png)
Setelah mengetahui version docker-compose langkah selanjutnya adalah membuat direktori docker-compose dengan memberikan perintah mkdir docker-compose setelah membuat direktori docker-compose kemudian masuk pada direktori tersebut dengan memberikan perintah cd docker-compose/.

![gambar3](minggu-08/Screenshot_3.png)
Kemudian  perlu  melakukan  install  docker  compose  dengan  versi  1.16.1  agar  tidak  terjadi kesalahan dalam version dengan memberikan perintah curl -L https://github.com/docker/compose/releases/download/1.16.1/docker-compose-`uname -s`-`uname -m` > /usr/local/bin/docker-compose


![gambar4](minggu-08/Screenshot_4.png)
Setelah melakukan install docker kemudian menjalankan docker-compose tersebut dengan perintah chmod +x /usr/local/bin/docker-compose

![gambar5](minggu-08/Screenshot_5.png)
Setelah melakukan install docker kemudian menjalankan docker-compose tersebut dengan perintah chmod +x /usr/local/bin/docker-compose

![gambar6](minggu-08/Screenshot_6.png)
Setelah menjalankan perintah chmod +x /usr/local/bin/docker-compose . Kemudian langkah selanjutnya membuat direktori dockercompose dengan memberikan perintah mkdir dockercompose lalu masuk pada direktori tersebut dengan memberikan perintah cd dockercompose. Kemudian membuat direktori dengan nama webapp dengan memberikan perintah mkdir webapp.

![gambar7](minggu-08/Screenshot_7.png)
membuat file Dockerfile dengan memberikan perintah vim webapp/Dockerfile. fileDockerfile ini berada pada direktori webapp. Dengan memasukkan kode seperti dibawah ini. Untuk menyimpan/save kode tersebut dilakukan dengan cara tekan esc kemudian :wq

![gambar8, gambar 9 dan gambar 10 ](minggu-08/Screenshot_8.png/minggu-08/Screenshot_9.png/minggu-08/Screenshot_10.png,  )
Setelah membuat Dockerfile selanjutnya membuat docker-compose.yml dengan memberikan perintah vim docker-compose.yml . Dengan memasukkan kode seperti dibawah ini
