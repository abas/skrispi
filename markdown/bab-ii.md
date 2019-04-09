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

#### 2.2.1 ssh
Protokol Secure Shell (SSH) adalah protokol untuk login jarak jauh yang aman dan layanan jaringan aman lainnya melalui jaringan yang tidak aman. Protokol SSH terdiri dari tiga komponen utama: Transport Layer Protocol menyediakan otentikasi server, kerahasiaan, dan integritas dengan kerahasiaan ke depan yang sempurna. Protokol Otentikasi Pengguna mengautentikasi klien ke server. Protokol Koneksi melipatgandakan terowongan terenkripsi menjadi beberapa saluran logis. Detail protokol ini dijelaskan dalam dokumen terpisah.

Metode Secure Shell (SSH) digunakan untuk melakukan remote-login atau masuk pada suatu sistem dari jarak jauh pada jaringan yang tidak aman. Secure Shell (SSH) sendiri terbagi menjadi 3 komponen :
- Protocol Transport Layer [SSH-TRANS]
menyediakan otentikasi server, kerahasiaan, dan integritas. Secara opsional dapat juga memberikan kompresi. Lapisan transport biasanya dijalankan melalui koneksi TCP / IP,
- Protokol Otentikasi Pengguna [SSH-USERAUTH] 
mengotentikasi pengguna sisi klien ke server. Ini berjalan di atas protokol layer transport.
- The Connection Protocol [SSH-CONNECT] 
melipatgandakan terowongan terenkripsi menjadi beberapa saluran logis. Itu berjalan di atas protokol otentikasi pengguna.

#### 2.2.2 nodejs
#### bash script
#### linux
#### docker dan docker-compose
#### ci/cd
#### circle ci
#### git
#### terminal
#### pm2
#### telegram
#### telegram bot api

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

