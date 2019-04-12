# BAB II
## TINJAUAN PUSTAKA
### 2.1 Tinjauan Studi

Pada penelitian ini salah satu topik yang berhubungan dengan yang peniliti angkat adalah sebuah buku pada tahun 2017 dengan judul “Xamarin Continuous Integration and Delivery” oleh versluis, G. yang membahas tentang kenapa kita perlu sebuah Automation Pipeline atau dengan kata lain mengotomatisasikan serangkaian proses menjadi lebih efisien, dari buku tersebut dikatakan bahwa pengulangan adalah suatu yang tidak begitu bagus bagi manusia, namun hal ini berbeda dengan komputer yang perannya sangat cocok untuk melakukan hal yang sama berulang-ulang[7], pengujiannya pada chapter 6 Integration Tests into Your Build menarik sebuah kesimpulan pada kondisi tertentu Automation Pipeline akan lebih bagus digunakan ketika kita melakukan banyak proses sekaligus (multip roccess).

Penelitian lain dengan judul “A Spoonful of DevOps help the GI go Down” pada tahun 2018, yang di temukan oleh Alexandra Elbakyan. Penelitian tersebut membahas tentang Genetic Improvement (GI) yang berfokus pada peningkatan otomatis dari pengembangan perangkat sebuah lunak. Genetic Improvement (GI) bertujuan untuk meningkatkan pengembangan perangkat lunak yang ada melalui pencarian transformasi dan evaluasi secara otomatis, otomatisasi pengembangan dan pengoperasian perangkat lunak secara end-to-end untuk evolusi itu sendiri. Hasil dari penelitian tersebut menyampaikan bahwa otomatisasi dalam sekala proses menghilangkan hambatan dalam proses development sampai ke produksi sebuah perangkat lunak[8].

Penelitian berikutnya dengan judul “Continuous Deployment of Software Intensive Products and Services: A Systematic Mapping Study” tahun 2015. Memebuat penelitian tentang bagaimana cara membuat suatu struktur pipeline development dengan tahapan yang praktis dan tool yang sudah dikembangkan digunakan kembali pada penelitian utama, didasarkan bagaimana cara membuat sebuah produk lebih cepat di kirim ke customer atau pengguna lebih cepat dari sebelumnya, karena hal ini mempengaruhi proses bisnis[9].

[#table] Tabel 2.1 Daftar Penelitian
| No | Peneliti | Judul | Tool | Hasil |
|----|----------|-------|------|-------|
| 01 | Ferry Satria, Tira Sundara, Hertog Nugroho, Malayusfi ([#bug:year-format]) | Pemantau Ruangan MenggunakanRaspberry Pi Terintegrasi Dengan BotTelegram Dan Halaman Web | Raspberry Pi | Semakin  besar  nilai  delta  threshold  yang digunakan maka semakin semakin sedikit juga motion yang dideteksi. |
| 02 | Rob van der Valk, Patrizio Pelliccione, Patricia Lago, Rogardt Heldal, Eric Knauss, Jacob Juul (2018) | Transparency and Contracts: Continuous Integration and Delivery in the Automotive Ecosystem | Atlas.ti | Transparansi bukanlah kondisi yang diperlukan untuk CI&D antar organisasi. Namun, transparansi dianggap sebagai positif karena menciptakan efek sinergis positif dalam hal efisiensi, kepercayaan, dan saling pengertian, sambil menghindari situasi stres yang tidak perlu. |
| 03 | Eric Knauss1, Aminah Yussuf, Kelly Blincoe, Daniela Damian, Alessia Knauss (2016) | Continuous clarification and emergent requirements flows in open-commercial software ecosystems | IBM’s Collaborative Lifecycle Management | saluran informasi terbuka mendukung aksi strategis global dan aksi just-in-time lokal. Baik tindakan global maupun lokal diperlukan untuk menjadikan ekosistem perangkat lunak sebagai mitra bisnis yang kompetitif, tetapi untuk memungkinkan keduanya, arus informasi bottomup dan horizontal perlu ditangani secara sistematis. |
| 04 | Ricardo Colomo-Palacios, Eduardo Fernandes, Pedro Soto-Acosta, Xabier Larrucea (2018) | A case analysis of enabling continuous software deployment through knowledge management | Meta4 | tekanan terhadap adopsi DevOps bersifat internal dan eksternal. Misalnya, teknologi terkini, ketersediaan teknologi, efektivitas dan manfaat yang dilaporkan diidentifikasi sebagai tekanan eksternal utama. Pada saat yang sama, adopsi DevOps terbukti mampu meningkatkan waktu dan kualitas siklus. Namun, responden berpendapat bahwa meskipun efek di tingkat perusahaan terbatas, arsitektur layanan mikro dapat memperluas manfaat DevOps di luar sisi teknis. |

### 2.2 Landasan Teori

Berikut merupakan landasan teori yang digunakan di penilitian ini, sumber dari landasan teori berikut berupa literatur jurnal, buku, dan juga official website.

#### 2.2.1 Continuous Integration And Delivery (ci/cd)
Continuous Integration merupakan sebuah teknik pada pengembangan software dimana pengembang dengan melakukan pembaruan atau perubahan pada sebuah repository jika suatu waktu terdapat perubahan pada kode sumber source code baru, serta mengotomatisasikan build & test dengan hasil berupa sebuah produk jadi. Apabila terjadi sebuah kesalahan, error, atau bug pada sebuah microservice atau aplikasi software dalam build/test maka tim pengembang dapat dengan segera melakukan bug fixing sehingga produk dapat di tingkatkan, dan juga dapat mengurangi waktu untuk melakukan validasi sebuah update.

Continuous Delivery adalah sebuah teknik pada pengembangan software atau aplikasi ketika pengembang melakukan sebuah perubahan atau update source-code, build & testing yang kemudian akan otomatis sistem akan melakukan deploying sumber yang terlah di perbarui ke sebuah environment produksi, akan tetapi jika suatu ketika sebauh kode sumber terdapat sebuah error atau bug, maka dengan otomatis sistem akan melakukan roll-back pada perubahan sebelumnya karena Continuous Delivery berkaitan dengan proses bisnis. Apabila Continuous Delivery dapat berjalan dengan tanpa kendala tim pengembang bisa melanjutkan 

#### 2.2.2 SSH
Protokol Secure Shell (SSH) adalah protokol untuk login jarak jauh yang aman dan layanan jaringan aman lainnya melalui jaringan yang tidak aman. Protokol SSH terdiri dari tiga komponen utama: Transport Layer Protocol menyediakan otentikasi server, kerahasiaan, dan integritas dengan kerahasiaan ke depan yang sempurna. Protokol Otentikasi Pengguna mengautentikasi klien ke server. Protokol Koneksi melipatgandakan terowongan terenkripsi menjadi beberapa saluran logis. Detail protokol ini dijelaskan dalam dokumen terpisah[10].

Metode Secure Shell (SSH) digunakan untuk melakukan remote-login atau masuk pada suatu sistem dari jarak jauh pada jaringan yang tidak aman. Secure Shell (SSH) sendiri terbagi menjadi 3 komponen :
- Protocol Transport Layer [SSH-TRANS]
menyediakan otentikasi server, kerahasiaan, dan integritas. Secara opsional dapat juga memberikan kompresi. Lapisan transport biasanya dijalankan melalui koneksi TCP / IP,
- Protokol Otentikasi Pengguna [SSH-USERAUTH] 
mengotentikasi pengguna sisi klien ke server. Ini berjalan di atas protokol layer transport.
- The Connection Protocol [SSH-CONNECT] 
melipatgandakan terowongan terenkripsi menjadi beberapa saluran logis. Itu berjalan di atas protokol otentikasi pengguna.

#### 2.2.3 NodeJS
NodeJS merupakan sebuah runtime JavaScript yang didorong peristiwa asinkron, Node dirancang untuk membangun aplikasi jaringan yang dapat diskalakan. Dalam contoh "hello world" berikut, banyak koneksi dapat ditangani secara bersamaan. Pada setiap koneksi callback diaktifkan, tetapi jika tidak ada pekerjaan yang harus dilakukan, Node akan tertidur (sleep mode).
![](../images/img/NodeJS-example.png)

Dengan popularitas Node.js, asynchronous, pemrograman eventdriven telah menyebar luas di aplikasi sisi server. Meskipun secara konsep sederhana, pemrograman berbasis event bisa membosankan dan rawan kesalahan. Semantik kompleks dari event-loop Node.js, ditambah dengan berbagai rasa eksekusi asinkron dalam JavaScript, dengan mudah menyebabkan bug[11]. Pada sebuah Makalah yang berjudul "Reasoning about the Node.js event loop using async graphs" memperkenalkan model baru yang disebut Async Graph untuk alasan tentang perilaku runtime aplikasi dan interaksinya dengan loop peristiwa Node.js. Berdasarkan model, Penulis telah mengembangkan AsyncG, alat untuk secara otomatis membangun dan menganalisis Grafik Async dari aplikasi yang sedang berjalan, dan untuk mengidentifikasi bug yang terkait dengan semua sumber eksekusi asinkron di Node.js. AsyncG kompatibel dengan fitur bahasa ECMAScript terbaru dan dapat (de) diaktifkan saat runtime. Dalam evaluasi kami, kami menunjukkan bagaimana AsyncG dapat digunakan untuk mengidentifikasi bug di aplikasi Node.js di dunia nyata.

Event-Driven dari Node.js dan event-loop secara konseptual sederhana: loop peristiwa mendengarkan kejadian dan memicu pengendali peristiwa misalnya pemanggilan kembali fungsi callback ketika suatu peristiwa terjadi. Perulangan event di Node.js sendiri dijalankan oleh satu threads, tetapi ia dapat mensurvei peristiwa dari threads lainnya misalkan threads asli untu I/O, dan dengan demikian membuat Node.js mampu menangani ribuan permintaan klien secara bersamaan (asynchronous)

Ada beberapa modul atau library dasar node.js yang dapat mentranslasikan sebuah string menjadi sebuah perintah dasar console, dari library tersebut dapat lagi dikembangkan menjadi modul-modul kecil yang sangat berguna, misalkan untuk membuat perintah baru seperti memasukkan perintah console yang di ambil dari sebuah package binary dari sebuah program kecil. dari sini dapat dilakukan pemrograman secara modular dimana untuk pengembangan jangka panjang akan lebih nyaman dan mudah.

#### 2.2.4 BASH
BASH adalah file teks biasa yang berisi serangkaian perintah. Perintah-perintah ini adalah campuran dari perintah yang biasanya kita ketik ouselves pada baris perintah (seperti ls atau cp misalnya) dan perintah yang bisa kita ketik pada baris perintah tetapi umumnya tidak (Anda akan menemukan ini pada beberapa halaman berikutnya ). BASH berjalan pada Unix shell, interpreter baris perintah atau shell yang menyediakan antarmuka pengguna baris perintah untuk sistem operasi mirip Unix. Shell adalah bahasa perintah interaktif dan bahasa scripting, dan digunakan oleh sistem operasi untuk mengontrol eksekusi sistem menggunakan skrip shell. Pengguna biasanya berinteraksi dengan shell Unix menggunakan emulator terminal; Namun, operasi langsung melalui koneksi perangkat keras serial atau Secure Shell adalah umum untuk sistem server. Semua shell Unix menyediakan wildcarding nama file, perpipaan, di sini dokumen substitusi perintah, variabel, dan struktur kontrol untuk pengujian kondisi dan iterasi.

Dalam suatu kasus, perintah command line biasanya di eksekusi pada sebuah console atau terminal dari sebuah sistem operasi itu sendiri, dalam hal lain terdapat deretan atau runtutan perintah command line yang di satukan menjadi sebuah file yang bisa disebut sebagai wizard-script atau bash-script. Bash scripting biasanya digunakan sebagai file automasi dari sebuah perintah yang sering diulang untuk menghemat waktu pada penulisan command line.

#### 2.2.5 Sistem Operasi Linux
Linux adalah keluarga sistem operasi perangkat lunak bebas dan sumber terbuka yang berbasis pada kernel Linux, kernel sistem operasi yang pertama kali dirilis pada 17 September 1991 oleh Linus Torvalds. Linux biasanya dikemas dalam distribusi Linux (atau singkatnya distro). Distribusi mencakup kernel Linux dan perangkat lunak serta perpustakaan sistem pendukung, banyak di antaranya disediakan oleh Proyek GNU. Banyak distribusi Linux menggunakan kata "Linux" dalam namanya, tetapi Free Software Foundation menggunakan nama GNU / Linux untuk menekankan pentingnya perangkat lunak GNU.

Linux pada awalnya dikembangkan untuk komputer pribadi berdasarkan arsitektur Intel x86, tetapi sejak itu porting ke lebih banyak platform daripada sistem operasi lain. Linux adalah sistem operasi terkemuka di server dan sistem besi besar lainnya seperti komputer mainframe, dan satu-satunya OS yang digunakan pada superkomputer TOP 500 (sejak November 2017, setelah secara bertahap menghilangkan semua pesaing). Ini digunakan oleh sekitar 2,3 persen komputer desktop. Chromebook, yang menjalankan Chrome OS berbasis kernel Linux.

Linux juga berjalan pada sistem tertanam, yaitu perangkat yang sistem operasinya biasanya dibangun di dalam firmware dan sangat disesuaikan dengan sistem. Ini termasuk router, kontrol otomatisasi, televisi, perekam video digital, konsol gim video, dan jam tangan pintar. Banyak ponsel pintar dan komputer tablet menjalankan Android dan turunan Linux lainnya. Karena dominasi Android pada smartphone, Linux memiliki basis instalasi terbesar dari semua sistem operasi serba guna.

Linux adalah salah satu contoh paling menonjol dari kolaborasi perangkat lunak bebas dan sumber terbuka. Kode sumber dapat digunakan, dimodifikasi, dan didistribusikan — secara komersial atau non-komersial — oleh siapa pun di bawah ketentuan lisensi masing-masing, seperti Lisensi Publik Umum GNU.

#### 2.2.6 docker dan docker-compose
Docker adalah program komputer yang melakukan virtualisasi tingkat sistem operasi. Ini pertama kali dirilis pada 2013 dan dikembangkan oleh Docker, Inc. Docker digunakan untuk menjalankan paket perangkat lunak yang disebut container. container diisolasi dari satu sama lain dan menggabungkan aplikasi mereka sendiri, alat, perpustakaan dan file konfigurasi; mereka dapat berkomunikasi satu sama lain melalui saluran yang jelas. Semua kontainer dijalankan oleh kernel sistem operasi tunggal dan karenanya lebih ringan dari mesin virtual. container dibuat dari gambar yang menentukan konten tepatnya. Gambar sering dibuat dengan menggabungkan dan memodifikasi gambar standar yang diunduh dari repositori publik.

Docker dikembangkan terutama untuk Linux, di mana ia menggunakan fitur isolasi sumber daya dari kernel Linux seperti cgroups dan ruang nama kernel, dan sistem file yang dapat digunakan oleh serikat pekerja seperti OverlayFS dan lainnya untuk memungkinkan kontainer independen berjalan dalam satu contoh Linux, menghindari overhead memulai dan memelihara mesin virtual (VM). Dukungan kernel Linux untuk ruang nama sebagian besar, mengisolasi pandangan aplikasi dari lingkungan operasi, termasuk pohon proses, jaringan, ID pengguna dan sistem file yang dipasang, sementara cgroup kernel menyediakan pembatasan sumber daya untuk memori dan CPU. Sejak versi 0.9, Docker menyertakan libcontainer library sebagai caranya sendiri untuk secara langsung menggunakan fasilitas virtualisasi yang disediakan oleh kernel Linux, selain menggunakan antarmuka virtualisasi abstrak melalui libvirt, LXC dan systemd-nspawn.

Membangun di atas fasilitas yang disediakan oleh kernel Linux (terutama cgroups dan namespaces), container Docker, tidak seperti mesin virtual, tidak memerlukan atau menyertakan sistem operasi yang terpisah. Sebagai gantinya, ia bergantung pada fungsionalitas kernel dan menggunakan isolasi sumber daya untuk CPU dan memori, dan memisahkan ruang nama untuk mengisolasi pandangan aplikasi dari sistem operasi. Docker mengakses fitur-fitur virtualisasi kernel Linux baik secara langsung menggunakan perpustakaan libcontainer, yang tersedia pada Docker 0.9, atau secara tidak langsung melalui libvirt, LXC (Linux Containers) atau systemd-nspawn.

Sistem container membuat pengembangan menjadi lebih fleksibel, sistem yang terisolasi serta pemisahan setiap environment atau modul tidak mempengaruhi service-service lain yang telah berjalan, serta keamanan pada lokalisasi service dan scalling yang mudah. 

Compose (docker-compose) merupakan alat untuk mendefinisikan dan menjalankan aplikasi yang kompleks dengan Docker. Dengan Compose, Anda mendefinisikan aplikasi multi-container dalam satu file, lalu memutarkan aplikasi Anda dalam satu perintah tunggal yang melakukan semua yang perlu dilakukan untuk menjalankannya. Dalam hal ini lebih praktis dalam menjalankan sebuah service karena dalam satu file dapat meringkas banyak service container.

#### 2.2.8 git
#### 2.2.9 terminal
#### 2.2.10 pm2
#### 2.2.11 telegram
#### 2.2.12 telegram bot api

### 2.3 Deskripsi Tempat KKI

PT. Dian Nuswantoro Teknologi dan Informasi merupakan perusahaan di bidang teknologi komputerisasi yang berdiri sejak tahun 2006. PT Dian Nuswantoro Teknologi dan Informasi ini lebih dikelan dengan nama PT Dinustek berfokus pada pelayanan tentang informasi dan teknologi (IT) , Layanan jaringan internet (Internet Service Provider) dan layanan pembuatan aplikasi (Software Development). Informasi tentang PT Dinustek :
Alamat : Jl. Arjuna No 36 ,Kota Semarang, Jawa Tengah, Indonesia.
Telepon : (024) 3568492
Email : marketing@dinustek.com
Website : www.dinustek.com

### 2.4 Logo dan Makna Tempat KKI

![](../images/img/logo-dnt.png)

Logo PT Dinustek terbagi menjadi 3 (tiga) bagian yaitu :
1. Simbol Api
Simbol api berwarna oranye melambangkan solusi untuk klien yang bermaksud memberikan penyelesaian masalah terbaik dari sisi teknologi dan informasi bagi bisnis klien.
2. Warna Biru
Warna biru melambangkan solusi teknologi informasi yang kami tawarkan dapat dipercaya kehandalan bagi klien.
3. Bentuk Huruf
Huruf-huruf yang tersusun berbentuk small caps melambangkan keramah-tamahan perusahaan kepada klien, dan nuansa kekeluargaan di perusahaan. Bentuk huruf yang dinamis namun kuat menggambarkan tim perusahaan yang kreatif dan solid.

### 2.5 Struktur Organisasi Tempat KKI

Struktur organisasi PT Dinustek:
##### 2.5.1. Direktur Utama
Mohamad Sidiq, S.Si., M. Kom
##### 2.5.2. Direktur
Dr. Pulung Nurtantio Andono, ST, M. Kom
##### 2.5.3. Manager of Software Department
Abu Salam, M. Kom
##### 2.5.4. Kepala Divisi Startup Software
Moh. Tofa Nurzaki, S. Kom

### 2.6. Visi dan Misi Tempat KKI

Visi : Menjadi perusahaan teknologi informasi dan komunikasi kelas dunia.

Misi : Memberikan solusi keseluruhan teknologi informasi dan komunikasi untuk klien.

