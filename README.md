# *Unix Command Line*
*Unix Command Line* artinya baris perintah dalam *Unix* (sebuah sistem operasi komputer).

## *Introduction to* CLI
*Command Line Interface* (CLI) adalah antarmuka pengguna berbasis teks (UI) yang digunakan untuk menjalankan program, mengelola file komputer, dan berinteraksi dengan komputer. Setelah sistem komputer berjalan, CLI-nya terbuka di layar kosong dengan prompt perintah dan perintah dapat dimasukkan.

## *Shell*
*Shell* adalah antarmuka pengguna yang bertanggung jawab untuk memproses semua perintah yang diketik di CLI. *Shell* membaca dan menafsirkan perintah dan menginstruksikan sistem operasi untuk melakukan tugas seperti yang diminta.

## File *System*
File *System* merupakan sebuah proses yang mengatur di mana dan bagaimana sebuah data disimpan dan diakses dalam *disk* penyimpanan. 

## *Windows Shell*
Di *Windows Shell*, kita dapat mengetikkan perintah dan itu akan berjalan di jendela prompt perintah hitam untuk melakukan tugas. Kita dapat mengetikkan satu perintah pada jendela CMD atau kombinasi perintah tergantung pada kebutuhan. Perintah akan berjalan dalam urutan di mana satu perintah akan dieksekusi setelah satu sama lain.

### *Terminal Basic* & *Basic Command*
1. *Command* untuk Navigasi
   - **pwd** (*print working directory*) digunakan untuk mengetahui direktori mana yang saat ini sedang dibuka.
   - **ls** (*list*) digunakan untuk melihat isi folder yang ada di perangkat komputer. Perintah **ls** terbagi lagi menjadi 3 jenis berdasarkan fungsinya, yakni:
      - **ls -R** untuk membuat daftar file,
      - **ls -a** untuk menampilkan data-data yang tersembunyi, dan
      - **ls -al** untuk memuat informasi lebih detail terkait direktori, seperti *size*, *permission* hingga *owner*).
   - **cd** (*change directory*) digunakan untuk membuka folder yang ingin dibuka secara cepat (berpindah direktori).
2. *Command* untuk Melihat Isi File
   - **head** digunakan untuk melihat beberapa line awal dari sebuah file text.
   - **tail** digunakan untuk melihat beberapa line akhir dari sebuah file text.
   - **cat** digunakan untuk melihat seluruh isi sebuah file.
3. *Command* untuk Membuat File dan Direktori
   - **touch** digunakan untuk membuat file baru.
   - **mkdir** digunakan untuk membuat direktori baru.
4. *Command* untuk Menyalin, Memindahkan, dan Menghapus File dan Direktori
   - **cp** digunakan untuk melakukan penyalinan (*copy paste*) file. 
   - **cp -R** digunakan untuk melakukan penyalinan (*copy paste*) direktori.
   - **mv** digunakan untuk memindahkan file dan dapat digunakan untuk *rename*.
   - **mv -R** digunakan untuk memindahkan direktori.
   - **rm** digunakan uuntuk menghapus file.
   - **rm -R** atau **rm -d** digunakan uuntuk menghapus direktori.

# Git dan GitHub Dasar
Git dan GitHub merupakan dua platform yang didirikan oleh satu perusahaan dengan tujuan sama serta fitur yang berbeda. Kedua platform ini sangat membantu pekerjaan programmer dalam menyusun kode script secara tim.

## *Version Control System* (VCS)
*Version Control System* (VCS) adalah sebuah sistem yang melakukan *source code management* (SCM) )untuk mengelola perubahan di setiap dokumen, program komputer, website, dan kumpulan pemrograman lainnya. VCS disini berfungsi untuk membantu penyimpanan berupa *history* tanpa menyimpan file baru, yang tersimpan hanya perubahan data, Sehingga kapasitas penyimpanan file menjadi ringan.

## Git *Introduction*
Git adalah *tools* untuk programmer. Git merupakan *software* berbasis *Version Control System* (VCS) yang bertugas untuk mencatat perubahan seluruh file atau *repository* suatu *project*.
*Repository* adalah direktori proyek yang dibuat.

1 *Repository* =  1 Proyek = 1 Direktori

File -file yg disimpan menggunakan git akan terlacak seluruh perubahannya, termasuk siapa yang mengubah.

### Perintah Dasar Git
1. **git init** digunakan untuk membuat repositori baru.
2. **git status** digunakan untuk menampilkan daftar file yang berubah bersama dengan file yang ingin di tambahkan atau di-commit.
3. **git add** bisa digunakan untuk menambahkan file ke index.
4. **git commit** digunakan untuk melakukan commit pada perubahan ke head. Ingat bahwa perubahan apapun yang di-commit tidak akan langsung ke remote repository.
5. **git log** merupakan perintah yang akan menampilkan daftar commits yang ada di branch beserta detail-nya.
6. **git checkout** digunakan untuk mengembalikan kondisi file proyek seperti waktu yang dituju. Akan tetapi, ini bersifat temporer (sementara). Pengembalian ini tidak disimpan dalam database Git. Bisa dikatakan perintah **git checkout** sebagai perintah untuk mengecek kondisi file di setiap commit. Selain itu juga, perintah ini digunakan untuk berpindah dan membuat cabang. Ini bisa digunakan untuk membuat perubahan baru berdasarkan kode di masa lalu.
7. **git reset**, akan mengembalikan file ke kondisi sebelumnya, kemudian menghapus catatan sejarah commit beikutnya. Perintah ini memiliki tiga argumen atau opsi utama, yaitu:
   - **--soft** akan mengebalikan dengan kondisi file dalam keadaan staged.
   - **--mixed** akan mengebalikan dengan kondisi file dalam keadaan *modified*.
   - **--hard** akan mengebalikan dengan kondisi file dalam keadaan *commited*.
8. **git revert** akan mengembalikan file dengan tidak menghapus sejarah *commit*. Jika menggunakan **git reset**, *commit* terakhir akan hilang. *Revert* akan akan mengambil kondisi file yang ada di masa lalu, kemudian menggabungkannya dengan commit terakhir.
9. **git branch** bisa digunakan untuk me-*list*, membuat atau menghapus *branch*.
10. **git merge** digunakan untuk menggabungkan sebuah *branch* ke *branch* aktif.
11. **git config** digunakan untuk mengatur konfigurasi tertentu sesuai keinginan pengguna, seperti email, algoritma untuk diff, username, format file, dll.

# HTML

# CSS

# *Algorithm*

