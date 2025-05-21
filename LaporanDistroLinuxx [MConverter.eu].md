# DAFTAR ISI {#daftar-isi .unnumbered}

#   {#section .TOC-Heading .unnumbered}

[KATA PENGANTAR [i](#kata-pengantar)](#kata-pengantar)

[DAFTAR ISI [ii](#daftar-isi)](#daftar-isi)

[BAB I PENDAHULUAN [1](#bab-i-pendahuluan)](#bab-i-pendahuluan)

[1.1. Latar Belakang [1](#latar-belakang)](#latar-belakang)

[1.2. Rumusan Masalah [1](#rumusan-masalah)](#rumusan-masalah)

[1.3. Tujuan Penulisan [2](#tujuan-penulisan)](#tujuan-penulisan)

[BAB II LANDASAN TEORI
[3](#bab-ii-landasan-teori)](#bab-ii-landasan-teori)

[2.1 Sistem Operasi [3](#sistem-operasi)](#sistem-operasi)

[2.2 Linux [4](#linux)](#linux)

[2.3 Distro Linux [5](#distro-linux)](#distro-linux)

[BAB III PEMBAHASAN [7](#bab-iii-pembahasan)](#bab-iii-pembahasan)

[3.1 Analisis dan Desain Sistem
[7](#analisis-dan-desain-sistem)](#analisis-dan-desain-sistem)

[3.2 Tampilan Distro Linux
[7](#tampilan-distro-linux)](#tampilan-distro-linux)

[BAB III PENUTUP [8](#bab-iii-penutup)](#bab-iii-penutup)

[3.1. Kesimpulan [8](#_Toc185632632)](#_Toc185632632)

[DAFTAR PUSTAKA [9](#daftar-pustaka)](#daftar-pustaka)

#  {#section-1 .unnumbered}

#  {#section-2 .unnumbered}

# BAB I PENDAHULUAN {#bab-i-pendahuluan .unnumbered}

## Latar Belakang

> Kebutuhan akan sistem operasi yang andal, fleksibel, dan hemat biaya
> bagi komunitas kreatif sangat diperlukan. Dalam dunia desain grafis,
> akses ke perangkat lunak yang powerful sering kali terkendala oleh
> mahalnya lisensi dan spesifikasi perangkat keras. Ubuntu, sebagai
> distribusi Linux yang berbasis open-source, menawarkan solusi
> alternatif dengan menyediakan lingkungan kerja yang stabil, dukungan
> perangkat keras yang luas, dan akses ke berbagai alat kreatif seperti
> GIMP, Inkscape, Blender, dan Krita. Selain itu, turunan Ubuntu seperti
> Ubuntu Studio dirancang khusus untuk profesional kreatif dengan
> pre-instalasi perangkat lunak multimedia. Melalui laporan ini,
> diharapkan desainer dapat memahami manfaat Ubuntu, memanfaatkan
> ekosistemnya secara maksimal, dan mengadopsinya untuk kebutuhan
> kreatif mereka, sekaligus mengurangi ketergantungan pada perangkat
> lunak komersial berbayar.
>
> Proses instalasi Ubuntu sebagai sistem operasi untuk kebutuhan
> desainer bukan hanya tentang memasang perangkat lunak semata, tetapi
> juga melibatkan konfigurasi yang mendetail agar semua perangkat keras,
> seperti tablet grafis, dan perangkat lunak desain dapat bekerja secara
> optimal. Instalasi ini mencakup pengaturan jaringan, kompatibilitas
> perangkat keras kreatif, keamanan, serta penyesuaian lingkungan
> desktop untuk mendukung alur kerja kreatif. Oleh karena itu, dalam
> laporan ini akan dibahas secara rinci proses instalasi sistem operasi
> distribusi Linux Ubuntu yang difokuskan untuk kebutuhan desainer
> grafis. Laporan ini diharapkan dapat menjadi panduan praktis yang
> membantu desainer atau studio kreatif dalam menyiapkan sistem yang
> efisien, aman, dan mendukung proses kreatif secara maksimal.

## Rumusan Masalah

> Dalam pengembangan teknologi untuk mendukung komunitas kreatif, banyak
> desainer yang menghadapi kendala dalam memilih sistem operasi yang
> sesuai dengan kebutuhan profesional mereka. Beberapa masalah utama
> yang muncul meliputi:

1.  Tingginya biaya lisensi perangkat lunak desain komersial dan sistem
    operasi berbayar.

2.  Kurangnya panduan yang spesifik untuk instalasi dan konfigurasi
    sistem operasi yang mendukung perangkat keras seperti tablet grafis
    dan layar beresolusi tinggi.

3.  Keterbatasan pengetahuan mengenai distribusi Linux, seperti Ubuntu,
    yang menawarkan alternatif efisien untuk desainer grafis.

4.  Minimnya dokumentasi praktis yang berfokus pada konfigurasi
    lingkungan kerja kreatif untuk mendukung alur kerja desainer secara
    optimal.

## Tujuan Penulisan

> Laporan ini disusun dengan tujuan sebagai berikut:

1.  Memberikan panduan langkah demi langkah mengenai proses instalasi
    Ubuntu yang difokuskan untuk kebutuhan desainer grafis.

2.  Menyediakan informasi tentang konfigurasi perangkat keras dan
    perangkat lunak kreatif untuk mendukung produktivitas desainer.

3.  Mengedukasi komunitas kreatif tentang manfaat Ubuntu sebagai sistem
    operasi alternatif yang stabil, hemat biaya, dan ramah pengguna.

4.  Membantu desainer atau studio kreatif dalam menciptakan lingkungan
    kerja yang efisien, aman, dan mendukung berbagai aktivitas desain
    grafis.

5.  Mendokumentasikan proses instalasi dan konfigurasi sebagai referensi
    praktis bagi desainer yang ingin mengadopsi solusi berbasis
    open-source.

# BAB II LANDASAN TEORI {#bab-ii-landasan-teori .unnumbered}

## Sistem Operasi

Sistem operasi (Operating System/OS) adalah perangkat lunak utama dalam
sebuah sistem komputer yang berfungsi sebagai penghubung antara
perangkat keras (hardware) dan perangkat lunak (software) dengan
pengguna (user). Sistem operasi bertugas mengelola sumber daya komputer
seperti CPU, memori, perangkat input/output, dan memastikan aplikasi
dapat berjalan dengan efisien serta sesuai dengan kebutuhan pengguna.
Menurut Silberschatz et al. (2018), sistem operasi dapat didefinisikan
sebagai sebuah program yang bertindak sebagai perantara antara pengguna
dan perangkat keras komputer.

Sistem operasi memiliki beberapa fungsi utama yang sangat penting untuk
menjaga kinerja komputer dan perangkat lainnya. Salah satu fungsi
utamanya adalah manajemen proses, yang meliputi pengelolaan eksekusi
program, penjadwalan proses, penanganan multitasking, dan sinkronisasi
antar proses. Fungsi penting lainnya adalah manajemen memori, di mana
sistem operasi bertugas mengalokasikan dan membebaskan memori utama,
memastikan data dan aplikasi memiliki ruang yang cukup untuk dijalankan
dengan lancar. Selain itu, manajemen file juga menjadi bagian penting
dari fungsi sistem operasi, yang mengatur penyimpanan, pengambilan, dan
manipulasi data pada sistem file di perangkat penyimpanan.

Sistem operasi juga mengelola perangkat keras input dan output (I/O)
seperti printer, mouse, dan keyboard, memastikan komunikasi yang efisien
antara perangkat tersebut dan sistem. Keamanan dan proteksi juga menjadi
perhatian utama, di mana sistem operasi menyediakan mekanisme untuk
melindungi data dan sistem dari akses yang tidak sah atau potensi
kerusakan. Terakhir, sistem operasi menyediakan antarmuka pengguna yang
memungkinkan interaksi antara pengguna dan perangkat keras, baik melalui
command line maupun antarmuka grafis (GUI). Semua fungsi ini bekerja
bersama-sama untuk memastikan sistem operasi dapat mendukung kinerja
perangkat secara optimal.

## Linux

Linux adalah sistem operasi berbasis Unix yang dikembangkan oleh Linus
Torvalds pada tahun 1991. Sistem ini menggunakan kernel open source,
memungkinkan siapa saja untuk mempelajari, memodifikasi, dan
mendistribusikannya secara bebas. Tanenbaum (2015) menyebutkan bahwa
Linux adalah contoh utama perangkat lunak bebas dan open source (FOSS)
yang telah merevolusi pengembangan dan penggunaan sistem operasi.
Karakteristik utama Linux meliputi sifat open source di bawah lisensi
GNU General Public License (GPL), yang memberi akses pengguna untuk
mengubah kode sumber sesuai kebutuhan. Kernel Linux dikenal memiliki
portabilitas tinggi, dapat dijalankan pada berbagai perangkat keras dari
komputer pribadi hingga superkomputer dan perangkat IoT. Stabilitas dan
keamanan adalah ciri khas lainnya, membuatnya menjadi pilihan utama
untuk server, sistem embedded, dan lingkungan profesional. Selain itu,
Linux memiliki modularitas tinggi, yang memungkinkan pengguna untuk
memilih dan mengkonfigurasi komponen sistem operasi sesuai kebutuhan.

Distribusi Linux, atau yang sering disebut \"distro\", adalah sistem
operasi lengkap yang dibangun di atas kernel Linux dan menyertakan
berbagai perangkat lunak tambahan. Beberapa distribusi populer antara
lain Ubuntu yang dikenal karena kemudahan penggunaan dan komunitas
besar, Debian yang terkenal dengan stabilitasnya, Fedora yang fokus pada
inovasi teknologi dengan perangkat lunak terbaru, CentOS yang sering
digunakan untuk server karena kestabilan dan keamanannya, dan Ubuntu
Studio yang dirancang khusus untuk kebutuhan multimedia dan kreatif
seperti desain grafis, editing video, dan audio. Keunggulan Linux
meliputi biaya nol karena sifat open source-nya yang tidak memerlukan
biaya lisensi, komunitas global yang menyediakan dukungan dan
dokumentasi, fleksibilitas yang memungkinkan penyesuaian untuk berbagai
kebutuhan, dan stabilitas jangka panjang yang menjadikannya ideal untuk
server dan aplikasi kritis.

Untuk desainer grafis, distribusi seperti Ubuntu Studio menawarkan alat
kreatif yang telah terinstal seperti GIMP, Inkscape, Blender, dan Krita.
Fleksibilitas Linux memungkinkan konfigurasi untuk mendukung perangkat
keras kreatif seperti tablet grafis dan monitor resolusi tinggi. Dengan
komunitas open source yang terus berkembang, Linux semakin menjadi
sistem operasi yang ramah pengguna, kaya fitur, dan mendukung berbagai
kebutuhan modern seperti kontainerisasi (Docker), pengelolaan big data,
dan pengembangan kreatif berbasis AI. Tinjauan ini memberikan pemahaman
tentang perkembangan Linux dan relevansinya sebagai solusi bagi berbagai
kebutuhan pengguna, termasuk dalam dunia kreatif dan desain grafis.

## Distro Linux

> Distribusi Linux, atau yang lebih dikenal dengan istilah \"distro
> Linux,\" adalah paket sistem operasi yang dibangun di atas kernel
> Linux dan mencakup berbagai perangkat lunak tambahan seperti sistem
> manajemen paket, antarmuka pengguna, perangkat lunak aplikasi, dan
> utilitas lainnya. Menurut Sobell (2017), distro Linux merupakan versi
> lengkap dari sistem operasi yang disesuaikan untuk kebutuhan tertentu,
> baik itu untuk server, desktop, maupun penggunaan khusus lainnya.
> Setiap distro Linux biasanya memiliki beberapa komponen utama,
> termasuk kernel Linux yang merupakan inti dari sistem operasi dan
> mengelola perangkat keras serta sumber daya sistem. Selain itu,
> terdapat sistem manajemen paket seperti APT untuk Debian/Ubuntu atau
> YUM/DNF untuk Fedora, yang berfungsi untuk menginstal, memperbarui,
> dan menghapus perangkat lunak. Distribusi ini juga mencakup lingkungan
> desktop (DE) yang menyediakan antarmuka pengguna grafis, memudahkan
> interaksi dengan sistem melalui GNOME, KDE, XFCE, atau LXDE. Selain
> itu, distribusi Linux juga dilengkapi dengan perangkat lunak bawaan
> seperti browser web, editor teks, dan alat manajemen file.
>
> Distribusi Linux dikelompokkan berdasarkan tujuan dan penggunaannya.
> Untuk desktop, contohnya adalah Ubuntu yang mudah digunakan dan
> memiliki komunitas besar, serta Linux Mint yang fokus pada kemudahan
> migrasi dari Windows. Untuk server, ada Debian yang terkenal dengan
> stabilitasnya dan CentOS/AlmaLinux yang populer untuk server dengan
> kebutuhan jangka panjang. Ada juga distribusi khusus seperti Kali
> Linux yang dirancang untuk keamanan siber dan pengujian penetrasi,
> serta Ubuntu Studio yang didesain untuk kebutuhan multimedia seperti
> desain grafis, editing video, dan audio. Keunggulan distribusi Linux
> antara lain kustomisasi tinggi, memungkinkan pengguna memilih distro
> yang sesuai dengan kebutuhan mereka, komunitas besar yang menyediakan
> dukungan teknis, biaya nol karena semua distribusi Linux bebas
> digunakan tanpa biaya lisensi, serta keamanan dan stabilitas yang
> dirancang untuk jangka panjang. Beberapa distribusi Linux juga
> dirancang khusus untuk mendukung pekerjaan kreatif, seperti Ubuntu
> Studio yang menawarkan perangkat lunak seperti GIMP, Inkscape,
> Blender, dan Ardour yang sudah terinstal, serta Fedora Design Suite
> yang mengoptimalkan alat desain grafis seperti Darktable dan Scribus.
>
> Namun, ada beberapa tantangan dalam penggunaan distribusi Linux,
> seperti kurva belajar yang mungkin tinggi bagi pengguna baru,
> kompatibilitas perangkat keras yang memerlukan konfigurasi tambahan
> untuk perangkat modern, dan dukungan perangkat lunak komersial yang
> tidak selalu tersedia untuk Linux. Distribusi Linux memainkan peran
> penting dalam industri kreatif dengan mengurangi ketergantungan pada
> perangkat lunak komersial berlisensi. Dengan alat-alat open source
> yang kaya fitur, distribusi ini menawarkan solusi hemat biaya dan
> fleksibel untuk desainer grafis, editor video, dan profesional kreatif
> lainnya. Tinjauan pustaka ini menunjukkan bahwa distribusi Linux tidak
> hanya sebagai solusi teknologi alternatif, tetapi juga platform yang
> dapat disesuaikan untuk berbagai kebutuhan, termasuk mendukung
> kreativitas dan inovasi.

1.  **  
    **

# BAB III PEMBAHASAN {#bab-iii-pembahasan .unnumbered}

## Analisis dan Desain Sistem

> Untuk desainer grafis dan kreatif, sebagian besar pekerjaan
> membutuhkan berbagai perangkat lunak desain yang memerlukan
> konfigurasi khusus. Untuk memenuhi kebutuhan tersebut, pengguna sering
> kali harus menginstal berbagai perangkat lunak seperti GIMP, Inkscape,
> Figma, Karbon dan lainnya secara manual satu per satu pada perangkat
> mereka. Proses ini tidak hanya memakan waktu tetapi juga kurang
> praktis, terutama jika dilakukan pada banyak perangkat sekaligus,
> seperti di studio desain atau organisasi kreatif lainnya. Oleh karena
> itu, diperlukan sebuah distribusi Linux yang secara khusus dirancang
> untuk desainer, dengan perangkat lunak kreatif yang sudah terinstal
> dan siap digunakan. Solusi ini akan membantu menciptakan lingkungan
> kerja yang efisien dan mendukung produktivitas tanpa perlu instalasi
> perangkat lunak tambahan secara manual.
>
> Pada distro linux yang akan kami buat menggunakan linux ubuntu versi
> 20.04 sebagai basis dasar dari linux yang digunakan. Untuk aplikasi
> yang akan dimasukkan untuk menunjang pembelajaran didalam laboratorium
> adalah sebagai berikut:

1.  GIMP

> ![](media/image2.jpeg){width="2.9995713035870515in"
> height="1.5748031496062993in"}
>
> GIMP (GNU Image Manipulation Program) merupakan aplikasi pengolah
> gambar open source yang menjadi alternatif utama Adobe Photoshop di
> sistem operasi Linux. Pada distribusi Linux, GIMP hadir sebagai
> perangkat lunak bawaan yang sangat powerful untuk kebutuhan editing
> foto dan desain grafis. Integrasi GIMP dengan sistem operasi Linux
> sangat mulus karena sama-sama berbasis open source, sehingga pengguna
> dapat dengan mudah menginstal, memperbarui, dan mengkustomisasi
> aplikasi melalui package manager distribusi masing-masing. GIMP
> mendukung berbagai format file gambar dan memiliki antarmuka yang
> dapat disesuaikan dengan kebutuhan pengguna Linux. Performa GIMP pada
> distribusi Linux umumnya sangat baik karena optimalisasi sistem dan
> dukungan komunitas yang kuat dalam pengembangan serta pemecahan
> masalah.

2.  Inkscape

> ![](media/image3.jpeg){width="2.9995713035870515in"
> height="1.5748031496062993in"}
>
> Inkscape merupakan perangkat lunak editor grafis vektor yang sangat
> populer di lingkungan Linux. Aplikasi ini berjalan dengan sangat baik
> pada berbagai distribusi Linux karena sifatnya yang open source dan
> terintegrasi sempurna dengan sistem operasi berbasis Linux. Pada
> distribusi Linux seperti Ubuntu, Linux Mint, atau Fedora, Inkscape
> dapat diinstal dengan mudah melalui package manager bawaan atau
> melalui terminal menggunakan perintah apt atau dnf.

3.  Figma

> Figma merupakan aplikasi desain antarmuka yang populer dan dapat
> dijalankan pada sistem operasi Linux melalui beberapa metode. Pada
> distribusi Linux, Figma dapat diakses melalui browser web seperti
> Chrome atau Firefox sebagai aplikasi berbasis web. Namun, untuk
> penggunaan yang lebih optimal, pengguna Linux dapat menginstal Figma
> Desktop melalui Flatpak atau menggunakan aplikasi alternatif seperti
> Figma for Linux yang dikembangkan komunitas.

4.  PhotoFlare

> ![](media/image4.jpeg){width="2.9995713035870515in"
> height="1.5748031496062993in"}
>
> PhotoFlare adalah aplikasi pengedit gambar yang ringan dan mudah
> digunakan, dirancang khusus untuk sistem operasi Linux. Aplikasi ini
> menawarkan alternatif sederhana namun powerful untuk pengeditan foto
> dasar, mirip dengan Microsoft Paint di Windows namun dengan fitur yang
> lebih lengkap. Pada sistem operasi Linux, PhotoFlare dapat
> diintegrasikan dengan baik di berbagai distribusi seperti Ubuntu,
> Linux Mint, dan Fedora melalui paket instalasi yang tersedia di
> repositori resmi maupun melalui file AppImage.

5.  LibreOffice

> ![](media/image5.jpeg){width="2.9995713035870515in"
> height="1.5748031496062993in"}
>
> LibreOffice merupakan perangkat lunak perkantoran open source yang
> menjadi alternatif utama dari Microsoft Office di sistem operasi
> Linux. Aplikasi ini hadir secara default di sebagian besar distribusi
> Linux dan menawarkan kompabilitas yang baik dengan format dokumen
> Microsoft Office. LibreOffice terdiri dari beberapa komponen utama
> seperti Writer untuk pengolah kata, Calc untuk spreadsheet, Impress
> untuk presentasi, Draw untuk grafis, Base untuk database, dan Math
> untuk formula matematika.

6.  Karbon

> ![](media/image6.jpeg){width="2.9995713035870515in"
> height="1.5748031496062993in"}
>
> Karbon pada sistem operasi Linux merupakan sebuah aplikasi vektor
> grafis yang menjadi bagian dari KOffice suite, sekarang dikenal
> sebagai Calligra Suite. Aplikasi ini dirancang khusus untuk membuat
> dan mengedit gambar berbasis vektor dengan antarmuka yang intuitif.
> Karbon menyediakan berbagai fitur dasar untuk menggambar bentuk
> geometris, kurva Bézier, dan jalur yang kompleks. Pengguna dapat
> dengan mudah memanipulasi objek menggunakan berbagai alat transformasi
> seperti rotasi, penskalaan, dan pemindahan.

## Tampilan Distro Linux

## ![](media/image7.jpeg){width="2.9880982064741906in" height="1.5748031496062993in"}  {#section-3}

# BAB III PENUTUP {#bab-iii-penutup .unnumbered}

1.  

2.  

3.  

## Kesimpulan

> Distribusi Linux Ubuntu memiliki potensi besar sebagai solusi sistem
> operasi yang efisien dan hemat biaya bagi desainer grafis. Dengan
> fokus pada fleksibilitas dan keterjangkauan, Ubuntu memungkinkan
> desainer untuk mengakses berbagai perangkat lunak kreatif sumber
> terbuka, seperti GIMP, Inkscape, Figma, Karbon, PhotoFlare,
> LibreOffice, dan Karbon tanpa memerlukan lisensi berbayar. Distribusi
> ini juga mendukung perangkat keras modern, seperti tablet grafis dan
> layar beresolusi tinggi, melalui proses konfigurasi yang dapat
> disesuaikan dengan kebutuhan kreatif. Selain itu, turunan Ubuntu
> seperti Ubuntu Studio menawarkan lingkungan kerja yang dioptimalkan
> untuk mendukung alur kerja kreatif secara langsung tanpa instalasi
> perangkat lunak tambahan.
>
> Laporan ini menunjukkan bahwa dengan panduan instalasi dan konfigurasi
> yang tepat, Ubuntu dapat menjadi alternatif yang handal untuk memenuhi
> kebutuhan desainer grafis, baik individu maupun organisasi.
> Pengadopsian distribusi ini tidak hanya meningkatkan efisiensi kerja
> tetapi juga memperkuat filosofi penggunaan perangkat lunak bebas dan
> sumber terbuka dalam dunia kreatif.

# DAFTAR PUSTAKA {#daftar-pustaka .unnumbered}

Negus, C. (2020). *Linux Bible* (10th ed.). Wiley.

Nemeth, E., Snyder, G., Hein, T. R., Whaley, B., & Mackin, D. (2017).
*UNIX and Linux System Administration Handbook* (5th ed.).
Addison-Wesley Professional.

Silberschatz, A., Galvin, P. B., & Gagne, G. (2018). *Operating System
Concepts* (10th ed.). Wiley.

Sobell, M. G. (2017). *A Practical Guide to Linux Commands, Editors, and
Shell Programming* (4th ed.). Prentice Hall.

Shotts, W. E. (2019). *The Linux Command Line: A Complete Introduction*
(2nd ed.). No Starch Press.

Tanenbaum, A. S., & Bos, H. (2015). *Modern Operating Systems* (4th
ed.). Pearson.
