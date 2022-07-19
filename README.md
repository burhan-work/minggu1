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
4. **git commit** digunakan untuk melakukan commit pada perubahan ke head. Ingat bahwa perubahan apapun yang di-commit tidak akan langsung ke remote repository. *Commit* menyimpan riwayat perubahan data pada file.
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
12. **git push** digunakan untuk mengirimkan perubahan ke *master branch* dari *remote repository* yang berhubungan dengan direktori kerja.
13. **git remote** akan membuat *user* terhubung ke *remote repository*.

## GitHub *Introduction*
GitHub merupakan layanan *cloud* yang berguna untuk menyimpan dan mengelola sebuah *project* yang dinamakan *repository*. Cara kerja pada GitHub harus terkoneksi pada internet sehingga tidak perlu meng-*install* sebuah *software* ke dalam perangkat keras. Hal ini memberikan keringanan penyimpanan komputer yang digunakan karena file *project* tersimpan oleh *cloud* GitHub. 

Konsep kerja GitHub pada dasarnya sama dengan Git yaitu dapat menulis *source code* secara individu atau tim. *User interface* yang tersedia pada GitHub lebih menarik dan mudah dipahami oleh pengguna awal. Pekerjaan secara tim, pengguna juga bisa melihat siapa penulis kode dan tanggal berapa kode tersebut dibuat.

# HTML
HTML merupakan bahasa dasar untuk membuat web.

## HTML *Introduction*
HTML merupakan singkatan dari *HyperText Markup Language* yang digunakan untuk menampilkan konten pada browser. HTML adalah sebuah bahasa yang menggunakan *markup* atau penanda untuk membuat halaman web. Contoh konten yang dapat ditampilkan seperti Text, Image, Video, Link, dan masih banyak lainnya. HTML ini sendiri bersifat statis dimana hanya bertugas menampilkan konten yang diminta oleh developer.

HTML bukanlah sebuah bahasa pemrograman, artinya HTML tidak bisa dinamis mengolah data. Untuk memudahkan dan menambah produktifitas dalam membuat HTML, dibutuhkan yang namanya *tools*. Ada 2 *tools* utama yang harus dipersiapkan untuk membuat HTML yaitu *Browser* dan *Code Editor*.

 ### *Visual Studio Code*
 *Visual Studio Code* adalah sebuah *code editor* gratis yang dikembangkan oleh tim *engineer* Microsoft yang bisa dijalankan di perangkat *desktop* berbasis Windows, Linux, dan MacOS. *Visual Studio Code* merupakan paket *all in one*, artinya bisa digunakan untuk bahasa pemrograman apapun.

 Beberapa keunggulan dari *Visual Studio Code* di antaranya:
 
 1. Mudah untuk mengelola *extention*,
 2. Memiliki *extention* yang banyak,
 3. Kontribusi tampilan,
 4. Dukungan bahasa,
 5. Text editor gratis,
 6. Dapat membuat *Snippet* sendiri,
 7. Mudah dalam memahami dan mempelajari *coding*,
 8. Dapat membuat *website* secara praktis, dan
 9. Dapat mendesain *website* dengan mudah.

## Dasar-dasar HTML
HTML bisa dituliskan tanpa *structure* dan bisa tetap menjalankannya. Akan tetapi untuk menjalankannya dengan baik diperlukan HTML *Structure*.

### HTML *Structure*
HTML tersusun sebagai kesatuan dari sebuah tingkatan (*family tree relationship*). Saat sebuah *element* berada di dalam *element* lain, maka disebut *child element*. *Element* yang berada diatas *element* lain disebut *parent element*.

### HTML *Anatomy*
1. Tag Pembuka: Terdiri dari nama dari elemen. Tag adalah sebuah penanda awalan dan akhiran dari sebuah elemen di HTML. Tag dibuat dengan kurung siku (<...>), lalu di dalamnya berisi nama tag dan kadang juga ditambahkan dengan atribut.
2. Konten: Teks yang akan muncul di dalam *browser*.
3. Tag Penutup: Fungsinya sama seperti tag pembuka. Tag penutup dibedakan dengan adanya garis miring (</>).

### HTML *Element*
HTML *element* didefinisikan dengan *opening tag*, *content*, dan *closing tag*. Elemen dalam HTML adalah sebuah komponen yang menyusun dokumen HTML. Elemen kadang juga disebut sebagai *node*, karena ia merupakan salah satu jenis *node* yang menyusun dokumen HTML dalam diagram HTML *tree*.

### HTML *Attributes*
Attribut merupakan *properties* dari sebuah HTML *Element*. Atribut adalah kata khusus yang berada di dalam tag pembuka. Atribut juga disebut sebagai *modifier* yang akan menentukan perilaku dari elemen. Atribut dapat ditambahkan pada elemen manapun.

### HTML *Comment*
*Comment* pada HTML adalah sebuah *tag/element* yang digunakan untuk meninggalkan sebuah catatan pada dokumen HTML. Catatan tersebut bisa berupa deskripsi/tujuan suatu bagian kode HTML, atau juga bisa digunakan untuk memberikan rekomendasi, atau bahkan untuk menyembunyikan sementara sebuah kode HTML dengan tujuan *debug*. Komentar pada HTML akan diabaikan oleh *web browser*, ia tidak akan ditampilkan sehingga *user* tidak akan melihat apa-apa. *Comment* bahkan bisa mempermudah orang lain untuk memahami struktur kode HTML dan akan membuat kode semakin mudah dibaca.

## Cara Menjalankan HTML
HTML bisa dijalankan dengan cara mencari lokasi file HTML yang sudah dibuat dan disimpan, lalu membukanya *via browser*. Kekurangan menggunakan cara ini yaitu perlu *refresh* halaman jika ada perubahan *content*. Cara lain yaitu menggunakan *Live Server* pada *Visual Studio Code*.

## Cara Membaca Dokumentasi
Untuk melihat seluruh *element* yang disediakan oleh HTML, kita bisa cek dokumentasi yang disediakan. Tidak perlu menghafal seluruh HTML *Element*, cukup mengetahui format konten seperti apa yang dibutuhkan, lalu kita bisa cek pada dokumentasi *syntax element* tersebut.

## HTML *Tag Populer*

### IMG
*Tag* **img** digunakan untuk menampilkan gambar. Gambar dapat ditampilkan melalui file lokal komputer atau menggunakan *link* dari internet. *src* atau *source* adalah  atribut untuk memberitahukan sumber gambar.

### Video
Jika **img** untuk menampilkan gambar, maka sesuai namanya *tag* **video** untuk menampilkan video. Video merupakan *double closing tag* sehingga konten ditaruh di antara *opening* dan *closing*.

### *Table*
Tabel adalah hal yang umum dan sering digunakan dalam *website*. Tabel adalah daftar yang berisi susunan informasi atau data yang ditampilkan dalam bentuk baris dan kolom. Dengan tabel, data atau informasi yang ditampilkan akan terlihat rapi, atau bahkan dalam bentuk struktur yang lebih kompleks. Tujuan pembuatan tabel adalah untuk menyajikan informasi data secara ringkas dalam bentuk daftar, sehingga akan lebih mudah untuk dibaca. Terdapat 3 *tag* utama sebagai syarat untuk membuat tabel HTML, antara lain: *tag* **table**, **tr**, dan **td**. Selain 3 *tag* tersebut, terdapat juga *tag* lain yang bersifat opsional antara lain: *tag* **thead**, **tbody**, **th**, **tfoot**, dan sebagainya.

### HTML *Form*
*Form* merupakan bagian pada HTML yang dapat digunakan untuk membuat elemen *Form* pada halaman Web. Berikut merupakan beberapa elemen *Form*:
1. **Text fields** digunakan ketika pengguna ingin mengisi *field* seperti kata, angka, dan lainnya.
Pada umumnya *text field* pada *browser* diberi kapasitas sebanyak 20 karakter.
2. **Text area** merupakan elemen yang dapat menyimpan kata dan dapat diperluas jika pengguna memasukkan lebih banyak *text* sehingga dapat dimasukkan pada elemen *text area*.
3. **Radio Buttons** digunakan ketika memerlukan *form* yang dapat memilih salah satu di antara beberapa pilihan.
4. **Checkbox** digunakan ketika memerlukan form yang dapat memilih lebih dari satu pilihan.
5. **Drop-down box** biasanya digunakan ketika memilih satu pilihan di antara banyak pilihan.
6. **Button** digunakan untuk membuat sebuah tombol, sehingga pengguna dapat melakukan suatu aksi.

## *Semantic* HTML
*Semantic* artinya menggunakan elemen HTML yang sesuai dengan kebutuhan konten, dengan kata lain elemen semantik adalah elemen-elemen yang menyatakan makna atau tujuan dari elemen itu sendiri. Salah satu keuntungan menggunakan elemen semantik adalah dokumen HTML akan mudah untuk dibaca. Kegunaan lain dari *semantic* adalah meningkatkan *Accessibility*, meningkatkan SEO, dan lebih mudah di*maintain*.

## *Deploy* HTML
*Deploy* adalah sebuah proses untuk menyebarkan aplikasi yang sudah dikerjakan supaya bisa digunakan oleh orang-orang. Cara men-*deploy* aplikasi yang sudah dikerjakan adalah dengan menggunakan *tools* bernama *Netlify*. Caranya yaitu masuk ke netlify.com lalu *register* seperti biasa menggunakan *email* atau github. Setelah itu masuk ke *tab* **Sites** lalu *drag and drop* seluruh folder html yang ingin di-*deploy*.

# CSS
CSS yaitu singkatan dari *Cascading Style Sheets*.

## CSS *Introduction*
CSS adalah bahasa pemrograman yang digunakan untuk mengatur tampilan elemen yang tertulis dalam bahasa *mark-up*, seperti HTML (membangun laman HTML). CSS berfungsi untuk memisahkan konten dari tampilan visualnya di situs. Dengan CSS, developer bisa mengubah warna menggunakan *font custom*, *editing text format*, mengatur tata letak, dan lainnya.

## Struktur CSS
CSS memiliki struktur kode dan sintaks dasar yang terdiri dari tiga bagian penting antara lain:
1. Selektor (*selector*) merupakan kata kunci untuk menentukan elemen HTML yang akan kita beri gaya (*style*).
2. Blok Deklarasi: Dalam CSS deklarasi berisi properti dari selektor dan nilai dari properti tersebut. Deklarasi diawali dan diakhiri dengan kurung kurawal {….}. Hal inilah yang menghasilkan blok deklarasi.
3. Properti dan Nilainya: Properti merupakan atribut atau aturan yang akan diterapkan oleh elemen yang dipilih (selektor). Untuk mendefinisikan nilai properti, kita perlu menggunakan tanda titik dua (:) setelah penulisan nama properti. Jika terdapat lebih dari satu properti dalam blok deklarasi maka tiap properti harus kita pisahkan dengan titik koma (;).

## CSS *Comment*
CSS *Comment* adalah teks yang tidak ditampilkan dan ditafsirkan oleh browser sehingga tidak mempengaruhi desain.Dengan menggunakan CSS *Comment*, kita dapat memberikan penjelasan maksud dari line code yang kita kerjakan. Selain itu, kita juga bisa memanfaatkan komentar untuk mencegah kode CSS tertentu dieksekusi.

## Tiga Cara Menggunakan CSS
Untuk memasukkan CSS kepada HTML terdapat 3 cara, yaitu:
1. CSS *Inline*

   Cara pertama dan paling singkat adalah menggunakan CSS *Inline*. CSS *inline* adalah sebuah kode CSS yang disematkan pada elemen apa pun di dalam **body** HTML, langsung menggunakan atribut **style**.
2. CSS *Internal*

   Cara yang kedua adalah menggunakan CSS *internal*. CSS *internal* adalah CSS yang diletakkan pada bagian **head** suatu halaman HTML.
3. CSS Eksternal

   Cara ketiga untuk menambahkan CSS ke dalam sebuah halaman HTML adalah menggunakan CSS Eksternal. Yang dimaksud eksternal adalah kita membuat file tersendiri yang berekstensi ( .css). Kemudian file tersebut kita hubungkan ke dalam halaman HTML menggunakan tag **link**. Pada penggunaan CSS eksternal kita tidak perlu menggunakan tag **style**.

## CSS - *Tag Name*
Kita bisa menggunakan Tag Elemen HTML secara langsung pada CSS. Jika menggunakan Tag Elemen, maka ini bersifat global. Global artinya akan mempengaruhi seluruh Tag Elemen HTML yang ada pada file tersebut

## CSS - *Class Name*
Kita bisa menggunakan attribut **class** pada elemen HTML, kemudian memanggil nama **class** tersebut pada CSS. HTML yang memiliki **class** yang sama, akan mempunyai *styling* yang sama saat digunakan pada CSS. Gunakan (.) saat memanggil **class** pada CSS.

## CSS - *Multiple Class*
Kita dapat menggunakan lebih dari 1 **class** yang berbeda untuk 1 elemen HTML. Contoh kasus: Kita memiliki 2 heading. Kemudian kita ingin memiliki warna yang sama, tapi kita ingin format *heading* yang satu huruf besar (*uppercase*) dan *heading* yang huruf kecil (*lowercase*).

## CSS - ID *Name*
Berbeda dengan *Class Name*. ID *Name* bersifat unik yang artinya hanya ada 1 nama ID pada 1 elemen HTML. Biasanya digunakan jika hanya ada 1 elemen pada 1 *page*. Contohnya *navigation header* dan *footer*. Tidak mungkin kan ada 2 *footer* dalam 1 *page*? Nah jadi kita bisa gunakan ID jika elemen tersebut unik dan hanya ada 1. Gunakan (#namaID) saat memanggil elemen ID HTML pada CSS.

## Perbedaan *Class Name* dan ID *Name*
Jika hanya ada 1 elemen pada file/halaman HTML, maka gunakan ID *Name* . Contohnya *navigation* dan *footer*. Jika akan ada beberapa elemen HTML yang memiliki *styling*/*desain* yang sama, maka gunakan *Class Name*. Contoh: Kita ingin Heading Blog kita memiliki desain yang sama dan kita ingin setiap link memiliki *styling*/*desain* yang sama.

## *Chaining Selectors*
*Chaining selector* dapat kita gunakan pada *case*/kasus berikut, yaitu ketika kita memiliki 3 tag elemen HTML pada CSS, namun kita ingin ada 1 elemen HTML yang memiliki styling berbeda.

## *Nested Element*
Konsep CSS sama dengan HTML yaitu setiap elemen memiliki *parent* dan *child*.

## !*important* CSS
**!important** CSS berada di level paling atas dari **ID** dan **Class**. Maksudnya adalah jika pada *styling* CSS kita menggunakan **!important**, maka *styling* sebelumnya baik itu ID *Name* atau *Class Name* akan di-*override*.

## *Multiple Selector*
Sebagai programmer handal, kita perlu latihan dan terbiasa membuat kode yang efektif. Jangan mengerjakan kode yang sama berulang kali. Pada CSS kita bisa membuat kode lebih efisien dan tidak repetitive (melakukan hal yang sama berulang-ulang).

## *Flexbox*
*Flexbox* adalah cara untuk mengatur *layout*. *Flexbox* direkomendasikan karena penggunaannya yang mudah dan didukung oleh kebanyakan *browser*. *Flexbox* memiliki kemampuan untuk menyesuaikan *layout* secara otomatis dan konsepnya sederhana. *Flexbox* memiliki 1 *parent*/*container* dan bisa beberapa *child*/*item*.

### *Ordering and Orientation*
1. **flex-direction**

   Properti **flex-direction** digunakan untuk mengatur letak item *child*. Terdapat 4 *value* **flex-direction** yang harus diketahui:
      - **row (default)**: secara *default* letak item *child* membentuk sebuah baris dari kiri ke kanan.
      - **row-reverse**: letak item *child* membentuk sebuah baris dari kanan ke kiri.
      - **column**: letak item *child* membentuk sebuah baris dari atas ke bawah.
      - **column-reverse**: letak item *child* membentuk sebuah baris dari bawah ke atas.
2. **flex-wrap**

   **Flex** secara *default* akan membuat tata letak *item children* dalam 1 *line* saja. **Flex** akan menyesuaikan *space* yang ada. Namun jika kamu ingin membatasi jumlah *item children* dalam 1 *line* lalu *item children* yang lain akan pindah ke posisi *line* yang baru, maka kita bisa menggunakan **flex-wrap**. Properti **flex-wrap** memiliki 3 *value*, di antaranya:
      - **no-wrap (default)**: secara *default* , **flex** tidak menggunakan **flex-wrap**.
      - **wrap**: **flex** *item* akan memiliki beberapa *line* dari atas ke bawah  jika *space* dalam 1 *line* sudah *full width*.
      - **wrap-reverse**: kebalikan dari **wrap** yaitu **flex** *item* akan memiliki beberapa *line* dari bawah ke atas  jika *space* dalam 1 *line* sudah *full width*.
3. **flex-flow**

   Properti **flex-flow** digunakan sebagai *shortcut* untuk *set up* **flex-direction** dan **flex-wrap** bersamaan. Terdapat 4 *value* pada **flex-flow**:
      - **row nowrap**,
      - **column wrap**,
      - **column reverse**, dan
      - **row-reverse wrap-reverse**.
4. **Order**

   Properti **order** pada **flex** adalah berfungsi untuk *ordering item* mana yang ingin kita atur posisinya berdasarkan urutan *order*. Terdapat 3 *value* dari properti **order**:
      - **-1** : *Item child* yang di-*set order* -1, maka *item child* tersebut akan berada di *ordering* paling awal atau paling kiri.
      - **0 (default)** : **Flex** secara *default* memiliki *order* 0 pada setiap *item child*. Ini berarti **0** akan membuat *item child* sesuai urutan pada HTML.
      - **1**: *Item child* yang di-*set order* 1, maka *item child* tersebut akan berada di *ordering* paling akhir atau paling kanan.
### *Alignment*
1. **justify-content**

   Properti **justify-content** digunakan untuk mengatur tata letak dan *space* antar *item child* secara horizontal atau *main axis*. **justify-content** memiliki 6 *value* yaitu:
      - **flex-start**,
      - **flex-end**,
      - **center**,
      - **space-between**,
      - **space-around**, dan
      - **space-evenly**.
2. **align-items**

   Properti **align-items** digunakan untuk mengatur *align* dari *item child* secara vertikal atau *cross axis*. **align-items** memiliki 5 value:
      - **flex-start**,
      - **flex-end**,
      - **center**,
      - **baseline**, dan
      - **stretch**.
3. **align-self**

   Properti **align-self** digunakan untuk mengatur *align item* pada masing-masing *item*. **align-self** memiliki 5 *value* yang sama dengan **align-items**:
      - **flex-start**,
      - **flex-end**,
      - **center**,
      - **baseline**, dan
      - **stretch**.
4. **align-content**

   Properti **align-content** memiliki konsep yang sama seperti **justify-content**. **align-content** digunakan untuk mengatur tata letak dan *space* antar *item child* secara vertikal atau *cross axis*. **align-content** akan berjalan jika *item* lebih dari 1 *line*. **align-content** memiliki *value* yang sama dengan **justify-content**, bedanya ada 1 tambahan *value* yaitu **stretch**.

### *Flexibility*
1. **flex-grow**

   Properti **flex-grow** dapat mengatur *size* suatu *item child* pada *flexbox*. *Value* dari properti **flex-grow** adalah *number* dan tidak boleh negatif.
2. **flex-shrink**

   **flex-shrink** adalah properti yang membuat *size* suatu *item child* mengecil secara relatif terhadap *item child* yang lainnya. *Value* dari properti **flex-shrink** adalah *number* (*Number* negatif dianggap tidak valid). Semakin besar *value number* dari properti ini, maka semakin kecil *size* dari suatu *item child*.
3. **flex-basis**

   **flex-basis** adalah properti yang sama fungsinya seperti **width**. **flex-basis** mengatur *width* dari setiap *item child*. Jika kita telah menggunakan **width**, maka **flex-basis** akan melakukan *override* properti **width**. Namun, **flex-basis** tidak akan berjalan jika kita telah menggunakan **min-width** dan **max-width**. Properti **flex-basis** memiliki *value*:
      - **auto**,
      - **number**,
      - **initial**, dan
      - **inherit**.

# *Algorithm*

