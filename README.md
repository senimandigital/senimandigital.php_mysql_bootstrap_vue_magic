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
Dengan mengakses URL Diatas, maka seluruh proses akan dibatalkan dan webserver akan memberikan repon balik berupa sebuah gambar yang berisikan text, lalu gambar tersebut akan di rotasi 45 derajat.

Berdasarkan contoh diatas, kita dapat melanjutkan untuk membuat schema lain-nya sesuai kebutuhan dalam pengembangan. Dengan menggunakan pola magic seperti ini, kita bisa menggunakan lebih dari satu framework dalam proyek. Dimana programer hanya perlu berkomunikasi data menggunakan URL Parameter.
