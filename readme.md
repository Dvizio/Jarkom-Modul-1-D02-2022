# Praktikum Jaringan Komputer Modul 1

### Soal 1
Sebutkan web server yang digunakan pada "monta.if.its.ac.id"! 

#### Jawab
##### Filter : 
```http.host eq monta.if.its.ac.id```
Display filter ```http.host eq monta.if.its.ac.id``` digunakan untuk menampilkan paket http yang memiliki host ```monta.if.its.ac.id```

![image](https://user-images.githubusercontent.com/82019030/192073904-3da8684d-31e8-4198-ad1c-d3ac298965a6.png)

Setelah mendapatkan daftar diatas, pilihlah salah satu paket lalu kita follow http stream pada paket tersebut. Hal ini akan menampilkan detail http, lalu cari yang memiliki data server seperti berikut

![image](https://user-images.githubusercontent.com/82019030/192073947-d5d9bba7-e6e3-4dc4-8da9-954317e14309.png)

Dengan informasi diatas, tertulis bahwa web server yang digunakan pada ```monta.if.its.ac.id``` adalah **nginx/1.10.3**

### Soal 2
Ishaq sedang bingung mencari topik ta untuk semester ini , lalu ia datang ke website monta dan menemukan detail topik pada website “monta.if.its.ac.id” , judul TA apa yang dibuka oleh ishaq ?

#### Jawab
##### Filter :
```http.host eq monta.if.its.ac.id```
Gunakan filter yang digunakan pada soal 1, lalu export object sebagai http pada paket yang mengandung **detail topik**

![image](https://user-images.githubusercontent.com/82019030/192074082-9b37cf59-0fd9-42f2-8862-ad6c3be53a48.png)

Setelah kita export, kita ganti jenis file tersebut menjadi html dengan menambahkan ```.html``` pada nama file tersebut

![image](https://user-images.githubusercontent.com/82019030/192074113-84682dfb-6a03-433b-a731-bc65bf42356b.png)

Setelah itu dibuka dan kita bisa melihat bahwa Ishaq membuka **Evaluasi unjuk kerja User Space Filesystem (FUSE) oleh WAHYU SUADI**

![image](https://user-images.githubusercontent.com/82019030/192074155-20385a43-aa92-40c7-965a-ddf7e4e5d46a.png)
