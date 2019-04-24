# BAB IV
## PENERAPAN SISTEM DAN PEMBAHASAN
### 4.1. Gambaran Umum Sistem
#### 4.1.1. Tukutu
![gambar_aplikasi_tukutu](link)
PT Dian Nuswantoro Teknologi adalah perusahaan pengembangan perangkat lunak berbasis web maupun mobile, Aplikasi Tukutu dikembangkan di PT Dinustek. Tukutu merupakan aplikasi yang digunakan untuk jual beli sepatu secara online dengan target merket yaitu pecinta sepatu, yang ingin membeli atau mungkin menjual sepatu koleksi mereka ke masyarakat umum. Tujuan pengembangan Aplikasi Tukutu lebih untuk membantu para pemilik merk sepatu lokal untuk dapat memasarkan produk mereka sehingga diharapkan dapat bersaing dengan merk internasional yang sudah lebih dahulu dikenal oleh masyarakat luas. Platform Mobile dipilih karena sebagian besar target market place pengguna merupakan pengguna Aplikasi smartphone.

#### 4.1.2. Telegram Bot Tukutu
![gambar_telegram_bot](link)
Telegram Bot Tukutu adalah Bot Telegram yang dikembangkan di PT Dinustek yang digunakan untuk melakukan remote terhadap server tukutu, dan juga sebagai alat untuk melakukan integrasi kelanjutan dan pemasangan. selain itu bot dapat mentranslasikan sebuah text menjadi command line pada server apa bila terjadi hal yang tidak di inginkan dalam keadaan darurat Bot dapat menjadi jalan pertama dalam penanganan server. Fokus pada Bot ini sendiri adalah untuk menjalankan Update pada Microservice yang terintegrasi dengan Git.

Telegram Bot Tukutu dikembangkan dengan teknologi NodeJS yang di kombinasi dengan Shell Script, pesan yang dikirim dari Telegram Bot Tukutu di translasikan menjadi sebuah command line, pada Telegram Bot Tukutu terdapat 2 jenis perintah, yaitu pertama perintah langsung (terdefinisi) merupakan perintah yang sudah diatur menjadi perintah default dan menjadi perintah sekali jalan, kemudian yang kedua adalah perintah kostum (custom) merupakan perintah yang diciptakan dari kreasi System Administrator itu sendiri. Kedua perintah tersebut berawal dari sebuah pesan string yang dikirim dari Telegram Bot Tukutu kemudian di pecah dari perintah utama dan perintah parameter, kemudian text atau String yang sudah tertrlansasi menjadi sebuah perintah Command Line akan di jalankan dalam interpreter Shell yang akan mengeluarkan Stdout dan Stderr, Stdout merupakan keluaran dari perintah yang dijalankan dan Stderr merupakan keluaran berupa pesan error apabila terjadi sebuah error dari perintah yang dijalankan.

### 4.2. Analisa Kebutuhan Sistem
#### 4.2.1. Identifikasi Aktor
#### 4.2.2. Activity Diagram
#### 4.2.3. Usecase Diagram
#### 4.2.4. Activity Diagram

### 4.3. Implementasi Kode Program

### 4.4. Pengujian