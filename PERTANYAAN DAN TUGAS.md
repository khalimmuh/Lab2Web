<!DOCTYPE html>
<html>
<head>
</head>
<body>

</body>
</html>
<h2>PERTANYAAN DAN TUGAS</h2>

<h3>1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.</h3>
<p>melakukan penambahan dan perubahan url(efk.jpg) dan mengubah beberapa nilai 
<img width="655" alt="SOAL1_1" src="https://user-images.githubusercontent.com/81312138/113503124-08abbc80-955a-11eb-8f14-98820807a2b8.PNG">
<img width="656" alt="SOAL1_2" src="https://user-images.githubusercontent.com/81312138/113503129-0ba6ad00-955a-11eb-8c45-f2cde2714c3c.PNG">
<img width="600" alt="SOAL1" src="https://user-images.githubusercontent.com/81312138/113502252-49ed9d80-9555-11eb-83d7-a925c094a7eb.PNG"></P>
<h3>2.Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan 
penjelasannya!</h3>
<p>H1 {..}tag Selector ini   artinya istilah untuk selector yang akan memilih elemen berdasarkan tag h1 pilihan semua elemen h1  
#intro h1 {...} ID Selector digunakan untuk menyeleksi elemen berdasarkan ID tertentu. Dalam penggunaannya, ID selector diawali dengan tanda pagar (#) atau hash, #intro h1 {...} tersebut menyeleksi element yang memiliki attribute ID dengan value "intro" 
selector #intro h1 {...} ini merupakan selector untuk menentukan bagian yang hanya ada satu pada halaman dan juga menentukan style nya. Jadi selector ini tidak bisa dipanggil lebih dari satu. Jika ada dua, maka hanya bekerja pada bagian pertama saja.
</p>
<h3> 3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada 
elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan 
penjelasan dan contohnya!</h3>
<img width="600" alt="dek1" src="https://user-images.githubusercontent.com/81312138/113503549-ccc62680-955c-11eb-8bdc-3b7f61bc7f85.PNG">
<img width="600" alt="dek2" src="https://user-images.githubusercontent.com/81312138/113503551-ce8fea00-955c-11eb-80a5-6197e4129db5.PNG">
<p>Css dengan mode internal merubah warna paragraf menjadi warna biru,
Css dengan mode inline merubah warna paragraf menjadi warna merah,
Css dengan mode external merubah warna paragraf menjadi warna hijau.yang jadi pertanyaan paragraf akan berganti menjadi warna apa ?  ketika ada beberapa kode css yang menggunakan selector p digunakan secara bersamaan, yang membedakan hanya sumber dari kode cssnya, yaitu dari mode internal, external, dan inline,  ini adalah maksud dari prioritas dari css berdasarkan sumber kodenya.</P>
<img width="500" alt="dek3" src="https://user-images.githubusercontent.com/81312138/113503552-d0f24400-955c-11eb-9f95-c0c8985fd0fe.PNG">
  
<p>penjelasan :

Paragraf pertama karena menggunakan mode inline, maka text paragraf berwarna merah
Paragraf kedua karena tidak menggunakan mode inline, sehingga mendapatkan warna biru effect dari kode css dari mode internal
maka bisa disimpulkan ketika ada satu objek di HTML yang mendapatkan beberapa kode css secara bersamaan, dari beberapa mode style css, maka urutannya adalah:</p>
<p>Mode inline style lebih diutamakan untuk digunakan, yaitu kode css yang ditulis di tag itu sendiri.
Setelah mode inline yang diutamakan adalah mode internal style, yaitu kode css yang ditulis di antara tag <style></style>
Setelah mode internal style, baru yang digunakan adalah mode external style, yaitu kode css yang ditulis di file lain, dan harus di linkkan dengan file html ketika akan menggunakan kode cssnya.</p>
 
<p>karena prioritas tersebut paragraf pertama mendapatkan warna merah karena menggunakan mode inline style, dan paragraf kedua mendapatkan warna biru karena tidak menggunakan inline style, sehingga mendapatkan effect dari kode css dengan mode internal style.<p>

 <h3>4.Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut 
terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? 
Berikan penjelasan dan contohnya! (p id="paragraf-1" class="text-paragraf") </h3>
<p>Atribut id adalah atribut yang bisa diberikan kepada tag apapun di dalam HTML. Atribut id bisa diibaratkan sebagai ‘identitas’ dari sebuah tag. Di dalam sebuah halaman, tidak boleh ada atribut id yang sama, namun setiap tag tidak harus memiliki atribut id.<img width="667" alt="41" src="https://user-images.githubusercontent.com/81312138/113503826-8a054e00-955e-11eb-9674-616a6fb5b05b.PNG">
<img width="600" alt="42" src="https://user-images.githubusercontent.com/81312138/113503829-8b367b00-955e-11eb-8d3a-95e2b3489c63.PNG"></p>
<p> memilih elemen berdasarkan nama class yang diberikan. class dibuat dengan memilih text paragraf dapat  digunakan pada elemen yang kita inginkan.
Sebuah elemen HTML dapat menggunakan satu atau lebih class.<img width="500" alt="43" src="https://user-images.githubusercontent.com/81312138/113503831-8c67a800-955e-11eb-8eb4-d8ff63bf349c.PNG">
</p>
