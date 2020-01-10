# Latihan VCS

* Buatlah satu repository **Latihan01**,
* Buat file **Readme.md**, lalu isi file tersebut dengan penjelasan **(tutorial)** cara penggunaan **git**, dan langkah - langkahnya lengkapi juga dengan **screenshoot** prosesnya.

## Apasih VCS dan Git itu ?
**Version Control System** atau **VCS** merupakan sebuah sistem yang merekam perubahan - perubahan dari satu atau sekumpulan berkas dari waktu ke waktu, sehingga anda dapat melihat kembali setiap perubahannya. **Git** sendiri merupakan salah satu **DVCS (Distributed Version Control System)** yang paling populer saat ini. Lebih tepatnya **Git** adalah perangkat lunak pengendali versi atau proyek manajemen kode perangkat lunak yang diciptakan oleh Linus Torvalds, yang pada awalnya ditujukan untuk pengembangan kernel Linux. 

# Bagaimana Cara Memjalankan Aplikasi Git ?

## 1) Langkah Awal 
Instal terlebih dahulu **Git** dengan cara mendownloadnya di halaman **http://git-scm.com/download** serta sesuaikan dengan kebutuhan dan kemampuan sistem operasi masing masing.

![1](https://user-images.githubusercontent.com/56512562/72118577-189f1580-3384-11ea-80ca-da9534cb1f42.png)

### Proses Instalasi

![2](https://user-images.githubusercontent.com/56512562/72118671-72074480-3384-11ea-9c52-d8b1c0e08695.png)

Silahkan klik tombol **Next** hingga selesai

## 2) Registrasi Akun Github

![3](https://user-images.githubusercontent.com/56512562/72118749-bf83b180-3384-11ea-9644-a2bffe1c33d5.png)

Silahkan kunjungi https://github.com untuk melakukan registrasi. 

### Bagaimana Cara Registrasinya ?

![3](https://user-images.githubusercontent.com/56512562/72118876-2acd8380-3385-11ea-9c97-0d0a670cc2f3.png)

* Klik **Sign Up** yang berada pada sudut kanan atas halaman anda

![4](https://user-images.githubusercontent.com/56512562/72118948-6e27f200-3385-11ea-9648-842f20b5e3a7.png)

* Selanjutnya mengisi data diri
  * Mengisi **Nama Pengguna** dikolom **Username**
  * Mengisi **Alamat Email** dikolom **Email Address**
  * Mengisi **Kata Sandi** dikolom **Password**
  
Setelah terisi semua segera vertifikasi akun anda dengan memasukan **Kode Vertifikasi** yang segera akan anda dapatkan **via email**.

## 3) Buat Repository Baru
Setelah memvertifikasi akun github anda, pastikan anda telah masuk ke akun github anda.

### Bagaimana cara membuat repository baru ?

![5](https://user-images.githubusercontent.com/56512562/72119136-f27a7500-3385-11ea-8922-dc8603feba08.png)

* Klik ikon **"+"** yang berada disudut kanan atas halaman anda dan klik **"New Repository"**

![5](https://user-images.githubusercontent.com/56512562/72118953-708a4c00-3385-11ea-8918-c2e21c265b87.png)

* Setelah itu buat **nama repository kamu sesuai kebutuhan kamu** dikolom **"Repository Name"**, namun untuk memudahkan kali ini kita akan menggunakan nama repository **"Latihan01"**.

## Mengaplikasikan Git

Selanjutnya ditahap ini buka aplikasi yang telah anda instal tadi. Gunakan **"Git Bash"**.

### Bagaimana menenmukan Git Bash ?
Mudah saja. Buka **Menu >> All Program >> Git >> Git Bash**. Atau lebih mudahnya lagi menggunakan pencarian dengan mengetikan **"Git Bash"**.

### Bagaimana untuk menjalankan program ?
* Mengkonfigurasikan akun **Github** anda didalam **Git Bash**
```
$ git config --global user.name "nama_pengguna"
$ git config -- global user.email email_pengguna@mail.com
```
* Memeriksa lokasi penyimpanan
```
$ pwd
```
* Memindahkan dan membuat repository lokal
```
$ cd d:
$ mkdir latihan01
$ cd latihan01
```
![6](https://user-images.githubusercontent.com/56512562/72119591-8731a280-3387-11ea-87e0-6b8b539b5838.png)
