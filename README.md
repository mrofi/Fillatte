Fillatte
========
Aplikasi File Sharing Berbasis Kampus

Created by

Analisa Kebutuhan Sistem :
Tafakur (10.230.0060)
Analisa Proses :
Anugrah Fajar Putranto (10.230.0040)
Desain Database :
Syamsul Fatah (10.230.0095)
Desain Interface :
Bryan Ary Virgiawan (10.230.0007)
Coding :
Mokhamad Rofi'udin (10.230.0157)
Testing :
Muhammad Lutfi (10.230.0067)
Illustration

Dalam kegiatan kampus, dosen sering memberikan tugas kepada mahasiswa, biasanya dalam bentuk makalah hardcopy tapi sering juga dalam bentuk softcopy. Tidak jarang pula, dosen meminta tugas dikumpulkan via email.

Di samping itu, modul-Modul dari dosen juga sangat dibutuhkan mahasiswa. Kalau semua mahasiswa meminta modul langsung ke dosen maka akan terjadi antrian panjang di depan kelas. Pemandangan yang aneh, bukan?

Illustration (part 2)

Dari kedua ilustrasi di atas, dapat ditarik pertanyaan. Kenapa modul tidak ditaruh di sebuah server dan mahasiswa bebas mengunduhnya kapan saja?

Kami mencoba menjawab dengan membuat aplikasi yang bisa digunakan mahasiswa untuk mengunduh modul-modul pembelajaran dan tempat untuk mengunggah tugas-tugas yang secara historis terdokumentasi dengan baik. Sebuah aplikasi yang bisa memudahkan dosen maupun mahasiswa.

Fillatte.

Aplikasi Client-Server yang dibuat khusus bagi kalangan akademik untuk berbagi file antara dosen dan mahasiswa.

Tujuannya agar dosen lebih mudah membagikan modul kepada para mahasiswanya dan mempermudah dalam melacak tugas yang dikumpulkan mahasiswa.

Bagi mahasiswa, aplikasi ini membantu dalam hal penyimpanan portofolio tugas yang telah dikumpulkan karena aplikasi ini mendokumentasi semua file yang telah diupload berdasarkan kronologinya.

Component

Server
Client
Database
Storage
Must

Aplikasi file sharing ini haruslah fleksibel.
Bisa diakses di mana saja dan kapan saja.
Mudah dalam pengembangan dan pemeliharan.
Challege Accepted

Web Technology is The Answer

Fleksibel
Bisa diakses di mana saja dan kapan saja selama server hidup dan ada jaringan internet
Mendukung Konten Dinamis
Dalam era informasi yang serba cepat ini, konten dinamis sudah menjadi menu wajib
Mendukung Mobilitas
Hampir semua handphone dan perangkat bergerak mendukung teknologi ini. Why not?
Mudah Dikembangkan
Teknologi web adalah teknologi yang banyak diadopsi oleh para pengembang software. Pengembangan aplikasi web lebih mudah karena tidak memerlukan compiler. Perubahan code program bisa langsung dilihat.
Ingredients

Bahasa Pemrograman PHP
Bahasa Pemrograman yang populer untuk web. Bukan yang terbaik tapi dukungan dari komunitas yang membuat PHP unggul.
Server Linux
Seperti yang dikatakan para master. Komputer Server ya Linux. Karena aplikasi ini menggunakan PHP sebagai core-nya, pilihan ke server linux adalah yang terbaik.
Web Server Apache
Web Server terbaik untuk menjalankan PHP adalah Apache. Sebuah proyek Open Source dengan modul yang cukup lengkap.
Ingredients (part 2)

DBMS MySQL
Database Management System yang ringan tapi powerfull dalam penggunakan. Mendukung berbagai aplikasi dan Sistem Operasi. Sekali lagi, MySQL cocok digunakan pada lingkungan web.
File Hosting
Tergantung pada tiap-tiap kampus. Biasanya dijadikan satu dengan web server yang sudah ada di kampus atau membuatnya terpisah. Ini sangatlah optional. Tapi yang jelas, penyimpanan file haruslah terintegrasi dengan sistem.
Framework PHP CodeIgniter
CodeIgniter adalah framework PHP yang ringan tapi bisa diandalkan.
We

Introduce

Fillatte.

What exactly Fillatte is?

Let's analyze it!

Rancangan Sistem

Dasar Kerja Sistem berbasis Web

Kinerja Sistem
Keterangan:

Permintaan data berupa URL (request) dari browser ke server.
Pengiriman data berupa HTML (response) dari server ke browser.
Permintaan record berupa Query (request) dari server ke database.
Pengiriman record berupa Array (response) dari database ke server.
Analisa Pengguna Sistem

Pengguna	Deskripsi Kebutuhan dalam Sistem
Tamu	Cuma bisa mengunduh file yang di share secara public
Mahasiswa	Dapat mengunduh file non-public
Dapat mengunggah file (tugas) untuk dikirim ke dosen
Dosen	Bisa membuat halaman baru sesuai makul
Melihat seluruh hasil upload'an dari mahasiswa
Administrator	Mengatur semua aktivitas, user, file dan manajemen admin
Diagram FLowchart

flowchart
Desain ERD

erd
Diagram Use Case

use case
Diagram Activity

diagram
Diagram Class

class_diagram
Desain Database FIllatte.

Desain Database


Desain Interace Fillatte.

Diagram Sekuen Tamu


DIagram Sekuen Mahasiswa


Diagram Sekuen Dosen


LKT

LKT Login


LKT Browse


LKT Page


Penjelasan Lengkap mengenai Desain Interface akan disampaikan bersama penjelasan implementasi. 
(Coding & Testing)

