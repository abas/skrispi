# BAB I
## PENDAHULUAN
### 1.1 LATAR BELAKANG
Saat ini banyak sekali teknologi – teknologi yang di kembangkan oleh developer atau pengembang software, ada berbagai macam tipe dan juga karakteristik seperti perangkat lunak dalam bidang kesehatan, pertanian, sosial media maupun berbelanjaan dengan memanfaatkan internet. Salah satu dari beberapa tipe tersebut yang saat ini masih menjadi sepuluh besar yaitu dari bidan perbelanjaan atau biasa di sebuh dengan belanja online e-commerce. Perkembangan teknologi informasi dapat membantu  cara hidup kita menjadi lebih modern, lebih mudah dan lebih praktis dalam kehidupan sehari-hari [1]. 

Aplikasi titip jual beli sepatu online Tukutu yang mempunyai ciri khas tersendiri yaitu dengan memberikan jaminan keaslian dari sepatu yang dijual. Dalam aplikasi Tukutu ada beberapa spesifikasi dari sepatu bekas, langka sampai sepatu baru dari beberapa brand  ternama maupun brand local. Hal ini tentu memudahkan komunitas pecinta sepatu original dalam memilah atau mencari tempat dimana harus membeli sepatu yang mereka inginkan. Aplikasi Tukutu saat ini sudah memasuki perangkat lunak berjalan mobile apps yang terintegrasi dengan RESTFull API sebagai tempat untuk mengirim atau menerima data atau record.

![](./images/img/cicd.png)

Continuous Integration – Integrasi berkelanjutan merupakan penerapan pengembangan perangkat lunak yang dapat melakukan kompilasi dan pengujian secara automatis [2], seperti misalnya pengembang sedang melakukan perubahan pada sebuah sistem, dalam satu waktu perubahan tersebut yang telah dilakukan versioning dapat secara otomatis melakukan builing system dan pengujian secara otomatis. Continuous Delivery – Pengiriman berkelanjutan adalah kemampuan untuk mendapatkan semua jenis perubahan dari sebuah sistem kemudian akan dilanjutkan dengan pemasangan perubahan sistem tersebut ke server production atau secara bertahap [3]. Telegram BOT - sebuah akun khusus tanpa nomor yang dapat menghandle sebuah Command dari pengguna dan memberikan jawaban sesuai fungsionalitas Command. Akun tersebut berfungsi sebagai antarmuka dari sistem yang berjalan yang berkomunikasi melalui Telegram Bot API [4].
	
SSH atau biasa di sebut secure shell, adalah salah satu perangkat lunak yang menyediakan login access secara aman. Konsep dari ssh seperti remote untuk mengakses sebuah perangkat dari jauh dengan protocol yang rumit. SSH menggunakan kriptografi yang unik serta kuat untuk memberikan otentikasi dan kerahasiaan [5], ssh di gunakan oleh system administrator (SysAdmin) untuk mengakses server yang mereka kelola.
	
System Administrator (SysAdmin) memiliki persan dalam konfigurasi, penanganan masalah dan pertahanan sistem komputer rumit yang terdiri dari beberapa komponen, misal : system management basis data, server servis, server aplikasi, load balancer, dan server-server lain yang di distribusikan di beberapa jaringan platform system operasi [6]. Dalam sebuah kasus pengembang dari tahap pengembangan sampai tahap produksi, sisi operasional server melakukan deployment dengan cara masuk memaluli SSH-SERVER kemudian baru melakukan configurasi pada sistem tersebut dengan memasukan beberapa baris perintah bash script. Begitupun apabila pengembang melakukan perubahan setiap saat dan sisi operasional harus melakukan perulangan yang sama sehingga langkah tersebut menjadi berulang-ulang dan tidak efisien. 

Dari masalah yang telah diuraikan maka penulis melakukan penelitian yang berjudul “IMPLEMENTASI INTEGRASI BERKELANJUTAN DAN PENGIRIMAN PADA LAYANAN MIKRO TUKUTU MENGGUNAKAN TELEGRAM BOT DAN NODEJS” sebagai pemecahan masalah ci/cd yang berada di servis mikro Tukutu. Kenapa kita harus menggunakan CI/CD dan apa manfaat dari CI/CD itu sendiri terdapat pada efisiensi dalam pengelolaan setiap service yang telah didefinisi atau di konfigurasi, misalkan ada lebih dari 100 servis kita hanya melakukan setup satu kali untuk kebutuhan selanjutnya, CI/CD juga akan menguntungkan dari sisi developer karena dia bisa langsung tau apa yang salah dan apa yang harus di perbaiki tanpa harus di beritahu oleh SysAdmin.

### 1.2 RUMUSAN MASALAH
Berdasarkan latar belakang yang telah dijelaskan, maka di dapatkan rumusa masalah sebagai berikut :
1. Bagaimana merancang dan mengimplementasikan integrasi berkelanjutan dan pengiriman berkelanjutan (CI/CD) pada microservice di tukutu

### 1.3 BATASAN MASALAH
Dalam penelitian ini terdapat batasan masalah sehingga pembahasan yang dilakukan tidak menyimpang dari tujuan penelitian. Berikut batasa masalah yang di dapat:
1. CI/CD dibuat menggunakan NodeJS.
2. CI/CD dilImplementasi pada Telegram BOT.
3. Bot hanya bisa mengeksekusi perintah jika username pada akun telegram terdaftar pada environment.
4. Selain super Admin Bot hanya bisa menerima perintah yang ada pada daftar.
5. Bot terintegrasi dengan git version control.
6. Perintah pada Bot akan dilanjutkan dengan eksekusi sebuah file.
7. Dalam sebuah group, bot bisa mengeksekusi perintah dengan melakukan mention.
8. Beberapa perintah dalam terminal tidak dapat dieksekusi Bot bahkan oleh super admin, untuk menjaga sistem tetap aman.

### 1.4 TUJUAN PENELITIAN
Adapun tujuan yang dilakukan penelitian ini:
1. Merancang dan implementasi CI/CD menggunakan Telegram BOT pada microservice Tukutu.

### 1.5 MANFAAT PENELITIAN
Manfaat yang diperoleh dari penilitian ini:

#### 1.5.1 Bagi Akademik
1. Sebagai indikator sejauh mana pemahaman yang telah di dapat saat menuntut ilmu di Universitas Dian Nuswantoro.
2. Menambah jenis penelitian pada Universitas Dian Nuswantoro yang dapat digunakan sebagai referensi penelitian lainnya.
3. Menjalin hubungan kerja sama antara Universitas Dian Nuswantoro dan Tukutu.

#### 1.5.2 Bagi Tukutu
1. Menjalin hubungan kerja sama antara Tukutu dan Universiatas Dian Nuswantoro.
2. Dengan adanya penelitian ini, Tukutu dapat terbantu pada sistem jual belinya.

#### 1.5.3 Bagi Penulis
1. Menambah pengetahuan dan pengalaman kerja pada instansi tempat penelitian dilakukan.
2. Penulis dapat mengembangkan ilmu yang telah di dapat selama berada di Universitas Dian Nuswantoro.

#### 1.5.4 Bagi Pembaca
1. Menambah wawasan tentang CI/CD.
2. Dapat digunakan sebagai bahan refrensi penelitian dan pengembangan selanjutnya. 