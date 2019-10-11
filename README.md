# Cara Membuat Repositori VCS Baru

<p>Dalam petunjuk ini, saya akan membahas bagaimana cara membuat repositori baru.</p>
Dimulai dari Instalasi perangkat lunak Git sampai repositori baru dibuat.
Di sini saya akan menggunakan Github.com sebagai VCS yang akan kita pakai dalam petunjuk ini, dan dengan menggunakan sistem operasi Windows. Mungkin cara yang akan saya gunakan disini akan sedikit berbeda dengan cara yang digunakan pada sistem operasi Linux dan Mac OS X.

## 1. Permulaan
Pertama kita akan menginstall perangkat lunak yang bernama "Git", silahkan anda download dari halaman "http://git-scm.com/download" tanpa tanda petik.

![gambar web git-scm](https://github.com/antonmartinus72/latihan1/blob/master/img/Img_1.png)

Silahkan anda download sesuai versi sistem operasi dan arsitektur yang anda pakai. Disini saya menggunakan sistem operasi Windows dengan arsitektur 64 bit.

### Instalasi

<p>Silahkan anda buka file instalasi git yang sudah anda download tadi.
Setelah anda membuka file tersebut, maka akan muncul tampilan seperti dibawah ini :</p>

![gambar instalasi git](https://github.com/antonmartinus72/latihan1/blob/master/img/Img_2.png)

Saya rekomendasikan anda untuk menggunakan pengaturan default. Silahkan klik **"Next"** sampai instalasi selesai.

## 2. Membuat akun Github
<p>Selanjutnya anda harus mempunyai akun github terlebih dahulu, jika anda belum pernah mendaftar silahkan ikuti langkah-langkah berikut.</p>  
Silahkan anda kunjungi website github.com maka akan terlihat tampilan seperti dibawah ini :

![gambar halaman github](https://github.com/antonmartinus72/LatihanVCS/blob/master/img/Img_3.png)

Lalu anda klik **Sign Up** pada pojok kanan atas halaman. 
Berikut tampilan pendaftaran github :

![gambar daftar github](https://github.com/antonmartinus72/LatihanVCS/blob/master/img/Img_4.png)

Anda akan masuk pada halaman pendaftaran **Step 1**.
Silahkan isi **Username**, **Email address** dan **Password** anda.
Silahkan lakukan **Verify account** dengan benar.
Klik **"Create an account"** di akhir halaman **Step 1**

**Catatan :**

* Pastikan pengisian Username tidak menggunakan **spasi**.
* Isi Email address dengan alamat email yang anda gunakan dan bisa di akses saat ini.
* Pastikan pengisian data sudah berubah menjadi tanda centang "**✓**" berwarna hijau, yang menandakan **Username** atau **Email address** yang anda masukan bisa digunakan oleh anda.
* Usahakan untuk meminimalisir kesalahan saat melakukan "Verify account" pada saat pengisian data.

Jika data sudah berhasil anda isi, maka anda bisa melanjutkan ke **Step 2** dan **Step 3**.
Pada **Step 3**, Verifikasi akan dikirimkan oleh Github dalam bentuk email ke alamat email yang telah anda masukan pada **tahap pengisian data** atau **Step 1**.

### Selanjutnya adalah langkah membuat repositori baru dalam github.

Silahkan anda ikon "**+"** pada sudut kanan atas halaman lalu pilih "**New repository**" seperti gambar di bawah ini :

![Img membuat repo](https://github.com/antonmartinus72/LatihanVCS/blob/master/img/Img_5.png)

Maka akan muncul tampilan seperti di bawah ini :

![Img tampilan membuat repositori](https://github.com/antonmartinus72/LatihanVCS/blob/master/img/Img_6.png)

Isi "Repository name" dengan nama yang anda inginkan. Tetapi mari kita gunakan nama **"Latihan1"** sebagai permulaan, agar bisa lebih mudah mengikuti petunjuk ini di bagian selanjutnya.

# 3. Menggunakan Git
Jika anda sudah menyelesaikan tahap satu, anda bisa mengikuti petunjuk bagaimana menggunakan git. Silahkan anda buka aplikasi yang sudah anda install pada petunjuk nomor 1 yaitu **"Git Bash"**. Anda juga bisa menggunakan Command Prompt (CMD), namun karena menggunakan git bash lebih mudah saat ini, jadi mari ikuti langkah ini.  
Biasanya Git Bash ini bisa dibuka langsung dengan cara "klik kanan" di desktop maupun windows explorer. Namun sebagai permulaan saya akan membuka aplikasi dari **Start Menu > All programs > Git > Git Bash** atau dengan mengetikan langsung "Git Bash" pada **Start Menu** di sistem operasi Windows.  

Tampilah git bash akan seperti ini :

![img git bash]()

Silahkan ketikan kode berikut untuk melakukan memperkenalkan diri anda agar tidak terjadi masalah pada saat nanti :
$ git config --global user.name "namasaya"
$ git config --global user.email emailsaya

**Contoh :**
```
$ git config --global user.name "namasaya"  
$ git config --global user.email emailsaya@mail.com  
```
Selanjutnya kita akan cek lokasi direktori kita saat ini :
```
$ pwd
```






