# Lab2Web
Tugas Web Program membuat HTML dan CSS
Pertanyaan 1
Lakukan Eksperimen mengacu dengan CSS Cheat Sheet yang diberikan
Jawaban 1
Saya melakukan eksperimen dengan membuat web sederhana
![webeksperimen](https://user-images.githubusercontent.com/59334580/113514722-711a8e00-959a-11eb-94d4-da8ded932c35.png)
Pertanyaan 2
Perbedaan deklarasi h1 dengan #intro h1
Jawaban 2
deklarasi h1 digunakan untuk semua elemen h1 sedangan #intro h1 digunakan hanya untuk id yang bernama intro.
contoh (h1)Hello Saya Fikri(h1) lalu di file CSS kita deklarasi seperti berikut.
.h1 {
color: white;
}
maka semua elemen h1 akan berwarna putih
namun, jika kita menggunakan
(div id="intro")
  (h1)
  Saya Fikri
  (h1)
(div)
(h1)
  Mahasiswa UPB
(h1)
lalu di file CSS kita deklarasi seperti berikut.
#intro {
color: blue;
}
maka yang akan terjadi adalah tulisan "saya Fikri" akan berwarna biru, sedangkan Mahasiswa UPB tidak berwarna biru.
Pertanyaan 3
Apa bila deklarasi CSS secara internal,ditambah CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi mana yang akan ditampilkan pada browser?
Jawaban 3
yang akan ditampilkan adalah inline CSS
![#6 penambahan_css](https://user-images.githubusercontent.com/59334580/113515011-0cf8c980-959c-11eb-9b76-557416303588.png)
Pertanyaan 4
Pada HTML terdapat ID dan Class, jika keduanya terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
Jawaban 4
Yang akan ditampilkan adalah deklarasi dari ID, pada pertanyaan kali ini saya membuat contoh untuk mengubah warna pada text.
.text-paragraf{
    color: white;
}
#paragraf-1 {
    color: blue;
}
setelah saya coba ternyata di browser text menampilkan warna biru
![#7 id_dan_class](https://user-images.githubusercontent.com/59334580/113515151-e9824e80-959c-11eb-940c-54acd9d58bd5.png)
