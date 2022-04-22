# senimandigital.php_mysql_bootstrap_vue_magic

Mahasiswa sudah harus mulai menentukan arah pemrograman-nya sendiri. Ada banyak pertimbangan bagi mahasiswa dalam memilih Frontend Framework, seperti:

1. Vue, Sangat cocok dipelajari oleh mahasiswa perantau dan akan pulang kampung. Dimana tidak akan ada programmer lain-nya dikampung yang bisa diajak kerjasama. Menguasai Vue akan mudah menguasai Framework lain seperti Angular dan React.
2. React, Sangat cocok dipelajari oleh mahasiswa yang akan bekerja di Ibukota, di ibukota relative banyak orang-orang yang menguasai React sehingga lebih mudah mencari pekerjaan dengan React di Ibukota.
3. jQuery, sangat cocok untuk modal awal setiap programmer dalam membangun portofolio. mempelajari jQuery jauh lebih mudah daripada mempelajari penggunaan Vue dan React. Jika kita sudah bisa memprediksi bahwa dimasa depan kita tidak akan bekerja dibawah naungan sebuah perusahaan, maka jQuery adalah pilihan framework yang tepat.

Tulisan diatas hanya sebagai pembuka untuk pencerahan, kenyataan-nya ketika anda memilih untuk menggunakan variant dari Senimandigital Framework, pemilihan Backend dan Frontend Framework bukan lagi hal yang penting. Bersama senimandigital anda akan diajak melihat pemrograman dalam presfektif yang benar-benar baru.

# Magic Programing

Magic programming adalah konsep pemrograman yang kami gagas untuk mengeliminasi perbedaan dalam berbagai bahasa pemrograman. Apa yang dilakukan dengan magic programming adalah:

1. Memfokuskan pemrograman pada satu arsitektur, yaitu: "html".
2. Memanfaatkan parameter universal sebagai basis dalam pemrograman.

## Magic Parameter
Apapun framework yang kita gunakan, semua framework tanpa kecuali dapat membaca URL parameter. Sehingga jauh lebih bijak jika kita membangun aplikasi berorientasi URL parameter, perhatikan contoh-contoh berikut:

### ?magic\[image\]\[captcha\]\[default\]
Dengan mengakses URL seperti contoh diatas, maka seluruh proses akan dihentikan dan webserver akan memberikan respon balik berupa sebuah gambar yang berisikan kode captcha.

### ?magic\[image\]\[rotate\]\[text\]=Column Rotate Header
Dengan mengakses URL Diatas, maka seluruh proses akan dibatalkan dan webserver akan memberikan repon balik berupa sebuah gambar yang berisikan text, lalu gambar tersebut akan di rotasi 45 derajat sebelum dikirim ke browser.

Berdasarkan contoh diatas, kita dapat melanjutkan untuk membuat schema lain-nya sesuai kebutuhan dalam pengembangan. Dengan menggunakan pola magic seperti ini, kita bisa menggunakan lebih dari satu framework dalam proyek. Dimana programer hanya perlu melakukan komunikasi data menggunakan URL Parameter.

## Karakteristik Magic Programming
Magic programming bukan sesuatu yang bisa di klaim oleh semua orang, karena magic programming harus memiliki karakterisitik seperti:
1. **Artificial Intelegence**: Setiap programmer bisa saja menulis kode program dengan auto handling, tapi auto handling saja belum cukup untuk mengatakan bahwa algoritma sudah menerapkan konsep magic. Cara termudah untuk mendapatkan pengakuan bahwa algoritma yang kita tulis sudah layak disebut menerapkan kosep magic programming adalah dengan adanya bukti upaya dan peningkatan kecerdasan pemroses.
2. **Stack Collaboration**: Stack Collaboration sejatinya hanya dapat dimplementasikan dalam arsitektur system fullstack, sedangkan untuk aplikasi yang lebih terpusat pada arsitektur single stack, konsep magic programming kemungkinan besar tidak akan dapat tercapai dengan mudah. Meskipun dalam praktek-nya konsep magic programming dalam arsitektur fullstack mungkin saja untuk dilakukan, tapi dampak-nya hanya akan bersifat terbatas pada lingkungan-nya sendiri.
3. **Reusable Component & Service** Reusable Component adalah hal biasa dalam pemrograman, dimana component dapat digunakan kembali dalam bagian aplikasi yang lain selama masih bekerja didalam lingkungan Framework yang sama, tapi buka seperti itu yang dimaksudkan sebagai Reusable Component & Service didalam magic programming. Dalam konsep magic programming, Reusable Component & Service memiliki makna sebagai mana adanya, dimana Component dan Service dapat digunakan kembali pada framework yang berbeda bahkan dan dapat pula digunakan pada aplikasi yang berbeda tanpa batasan ruang lingkup sama sekali.

## Goal Magic Programming

1. **The True Crean Code**: Clean Code sejauh ini diartikan sebagai "Implementasi pemilihan kode terbaik yang to the point, tanpa tambahan atau kehadiran algoritma sampah". Tapi dalam konsep magic programming Clean Code berarti kode program hanya berisi file html yang diembeded dengan "behavior". Dengan demikian programmer hanya perlu mengerti kode html untuk membuat Aplikasi. Sedangkan pemroses sisi backend dan frontend handling itu akan menjadi tugas dari framework-nya.
2. **Behavior Management**: Dalam magic programing kode program tidak lagi dilihat dari sudut pandang Object, Class dan Methodnya tetapi magic programming akan melihat kode program dari sudut pandang "_behavior_"-nya.
