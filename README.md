# UAS-Pakahmadroihan-PPL
## Abstrak
usaha rental Playstation adalah satu-satunya dari usaha rental yang menyewakan mainan Playstation (PS) yang berlokasi Tigaraksa Tangerang Banten, Permasalahan utama dalam usaha rental PlayStation adalah ketidak efisienan data yang hanya ditulis di kertas, menyebabkan risiko kehilangan, kerusakan, kesulitan pencarian, dan lainya. Solusi yang diajukan adalah sistem sewa PlayStation berbasis web yang menyajikan informasi dari berbagai jenis Console yang tersedia. Penelitian ini bertujuan untuk merancang dan mengimplementasikan sistem informasi berbasis web guna meningkatkan efisiensi dan efektivitas operasional di "Rumah Playstation" Tigaraksa, Kabupaten Tangerang. Metode penelitian meliputi observasi, wawancara, dan studi literatur, menggunakan metode pengembangan sistem waterfall. Hasil menunjukkan sistem mampu menampilkan jenis PlayStation, menghasilkan kwitansi, memproses penyewaan oleh admin, dan membantu dalam pengelolaan data pelanggan. Sistem ini diharapkan memperluas jangkauan pemasaran dan meningkatkan omset usaha. 
## Abstract
The Playstation rental business is the only rental business that rents out Playstation (PS) toys located in Tigaraksa, Tangerang, Banten. The main problem in the PlayStation rental business is the inefficiency of data which is only written on paper, causing the risk of loss, damage, difficulty searching, and so on. The solution presented is a web-based PlayStation rental system that provides information on the various types of consoles available. This research aims to design and implement a web-based information system to improve operational efficiency and effectiveness at the Tigaraksa "Playstation House", Tangerang Regency. Research methods include observation, interviews, and literature study, using the waterfall system development method. The results show that the system is able to display the type of PlayStation, generate receipts, process rentals by admin, and assist in managing customer data. This system expands marketing reach and increases business turnover. 
Keywords--- Rental, Information System, Playstation, Waterfall, Web.
## PENDAHULUAN
Perkembangan teknologi informasi yang pesat memengaruhi berbagai sektor, termasuk industri hiburan. Salah satu bentuk hiburan populer, terutama di kalangan generasi muda, adalah permainan video. Usaha rental PlayStation (PS) menjadi solusi bagi penggemar game yang ingin menikmati berbagai permainan tanpa perlu membeli konsol dan game sendiri. Di Tigaraksa, Tangerang, terdapat usaha rental bernama "Rumah Playstation". Namun, usaha ini menghadapi kendala dalam pengelolaan data yang masih dilakukan secara manual dengan mencatat di kertas. Metode ini rentan terhadap kehilangan dan kerusakan data serta menyulitkan pencarian informasi. Di era digital saat ini, sistem manual seperti ini kurang efisien. Untuk mengatasi masalah tersebut, diperlukan sistem informasi berbasis web yang dapat meningkatkan efisiensi operasional. Sistem ini dirancang untuk menyajikan informasi konsol, memproses penyewaan, dan mengelola data pelanggan dengan lebih baik. Penelitian ini menggunakan metode pengembangan sistem waterfall, melibatkan observasi, wawancara, dan studi literatur untuk memahami kebutuhan usaha. Dengan adanya sistem berbasis web, "Rumah Playstation" diharapkan dapat meningkatkan efisiensi, memperluas pemasaran, dan meningkatkan pendapatan. Sistem ini juga diharapkan menjadi referensi bagi usaha sejenis di daerah lain.
## PERMASALAHAN
Pada saat ini usaha rental console sudah menjadi hal yang sering ditemukan, segala kalangan mau muda ataupun tua bisa menikmati sensasi bermain game console keluaran terbaru tanpa harus membelinya.  Rental PlayStation Point merupakan salah satu dari banyaknya usaha rental yang berkembang, yang   menyewakan mainan console PlayStation (PS) namun, sistem pengolahan data pada usaha penyewaan console ini masih menggunakan metode lama yaitu cukup dengan pena dan buku besar. Sehingga menimbulkan beberapa kendala seperti buku rusak, sobek, basah, atau hilang dan bisa jadi adanya kesalahan penulisan pada buku tersebut, jadi akan banyak memakan waktu dan tenaga. Hal tersebut dapat mempengaruhi turunnya kinerja dalam usaha tersebut. Maka dari pada itu diperlukan sistem informasi pendukung dalam pengolahan data agar tidak rentan terjadi kesalahan dalam pendataan pelanggan, peminjaman, pengembalian, dan lainnya. Metode Software Development Life Cycle (SDLC) adalah metode yang digunakan untuk merancang sistem informasi pada PlayStation Point ini, kemudian software  visual studio code  digunakan untuk merancang Proyek ini dengan menggunakan bahasa pemograman Php dan database MySql Tujuan penelitian adalah untuk merancang penggunaan Sistem Informasi Rental Playstation di Rental PlayStation Point Berbasis Web, selain itu peneliti berharap agar pihak perusahaan dapat memahami maksud dari sistem aplikasi ini dan memudahkan pihak perusahaan dalam melakukan semua kegiatan yang berkaitan dengan transaksi peminjaman
### METODE PENGUMPULAN DATA

Dalam pengumpulan data menggunakan metode Research & Development peneliti melakukan:
Studi Pustaka (Literature Study)
Studi yang dilakukan peneliti adalah browsing internet mengenai judul yang diambil dalam penelitian sebagai referensi penyusunan Tugas ini.
Studi lapangan (Field Study)
pengamatan atau observasi dilakukan di Rental Playstation Point secara langsung untuk mengamati aktivitas dalam proses penyewaan dan hasil dari observasi ini peneliti menilai bahwa sangat rentan terjadi kesalahan, kerusakan maupun kehilangan pada media kertas yang digunakan untuk proses transaksi peminjaman selain itu juga peneliti menilai kinerja admin yang cukup memakan waktu dalam bekerja karena harus menulis kedalam buku pelanggan dan buku laporan.




### LANGKAH-LANGKAH PENGEMBANGAN SISTEM

Software Devlopment Life Cycle (SDLC) Merupakan proses pengembangan atau mengubah suatu sistem  perangkat lunak dengan menggunakan  model-model dan metodelogi yang di gunakan orang untuk mengembangkan sistem perangkat lunak yang terdiri dari tahap-tahap yaitu (Planing)  atau rencana, (Analysis) atau analisis, (desgin atau desain, (Implementation) atau implementasi, (testing) atau testing, dan (maintenacne) atau Perawatan.

 
### SKEMA HARDWARE
●	Computer yang Digunakan oleh admin untuk melakukan pendaftaran pelanggan, peminjaman, pengembalian, dan sebagainya.
●	Wifi yang digunakan supaya Computer dan perangkat lainya mampu mengakses internet
●	Laptop yang Digunakan untuk merancang proyek ini.


### SKEMA SOFTWARE
●	Text editor menggunakan Visual Studio Code atau Sublime juga bisa.
●	Bahasa pemograman menggunakan PHP 
●	Untuk menyimpan data kedalam data base disini kami menggunakan MySQL

### SKEMA DATABASE
Terdapat 5 Table di Database yaitu, Admin, Pelanggan, Peminjaman, Pengembalian, dan Console. Itu semua tersimpan di database bernama Console
Tabel console untuk Menyimpan data jenis console yang tersedia untuk disewa.
terdiri dari
id_console: ID unik untuk setiap console.
jenis_console: Jenis console (misalnya PS5, Xbox, dll.).
harga_sewa: Harga sewa per periode tertentu.

Tabel pelanggan untuk Menyimpan informasi pelanggan yang menyewa console.
id_pelanggan: ID unik pelanggan.
nama: Nama pelanggan.
alamat: Alamat pelanggan.
telepon: Nomor telepon pelanggan.

Tabel peminjaman untuk Menyimpan data transaksi peminjaman console oleh pelanggan.
id_peminjaman: ID unik peminjaman.
nama: ID pelanggan yang meminjam console.
console: ID console yang dipinjam.
tgl_pinjam: Tanggal mulai peminjaman.
tgl_kembali: Perkiraan tanggal pengembalian.
harga: Harga yang harus dibayar.
jaminan: Jaminan yang diberikan pelanggan.

Tabel pengembalian Menyimpan data pengembalian console setelah dipinjam.
id_pengembalian: ID unik pengembalian.
nama: ID pelanggan yang mengembalikan console.
tgl_pinjam: Tanggal saat console dipinjam.
tgl_kembali: Tanggal saat console dikembalikan.
console: ID console yang dikembalikan.
jaminan: Jaminan yang dikembalikan atau diubah.

Tabel admin
Menyimpan data admin yang mengelola sistem.
id_admin: ID unik admin.
username: Nama pengguna admin.
password: Kata sandi admin.

# Hubungan Antar Tabel:
peminjaman terhubung dengan pelanggan (pelanggan meminjam console).
peminjaman terhubung dengan console (console yang dipinjam).
pengembalian terhubung dengan peminjaman (untuk mencatat pengembalian console).
pengembalian terhubung dengan console (console yang dikembalikan).
Sistem ini membantu dalam mengelola proses penyewaan console, mencatat transaksi peminjaman dan pengembalian, serta mengelola data pelanggan dan admin.

# Skema Actor (USE CASE)
Aktor (Pengguna Sistem) Tidak Ditampilkan
Diagram ini lebih fokus pada proses dalam sistem daripada siapa yang menggunakannya. Biasanya, aktor dalam sistem ini bisa berupa pelanggan dan admin/operator.
Use Case (Fungsi dalam Sistem)

Data Pelanggan & Input Pelanggan
Sistem memiliki fitur untuk mengelola data pelanggan. Saat ada pelanggan baru, sistem akan memasukkan (input) informasi pelanggan ke dalam database.

Peminjaman & Pengembalian
Pelanggan bisa melakukan peminjaman barang, dan dalam proses ini, sistem akan mencatat informasi peminjaman.
Saat pelanggan mengembalikan barang, sistem akan memperbarui status peminjaman.
Pengembalian barang di-include dalam peminjaman, artinya setiap peminjaman pasti memiliki proses pengembalian.

Data Console & Input Console
Sistem juga memiliki data console untuk mengelola informasi yang dimasukkan ke dalam sistem. Input console digunakan untuk memasukkan data baru ke dalam database.

Manipulasi Data
Sistem dapat melakukan manipulasi data, misalnya mengedit, menghapus, atau memperbarui informasi yang sudah ada.
Hubungan Include

Beberapa fungsi dalam sistem saling terkait. Misalnya, peminjaman membutuhkan proses pengembalian, sehingga ada hubungan Include antara kedua proses ini.
Input pelanggan dan input console juga berkaitan dengan data pelanggan dan data console.
Secara keseluruhan, diagram ini menunjukkan bagaimana data pelanggan dan peminjaman barang dikelola dalam sistem, termasuk pencatatan, manipulasi, dan hubungan antar proses yang ada

## DIAGRAM
[Gambar Diagram penyewaan] (https://imagekit.io/tools/asset-public-link?detail=%7B%22name%22%3A%22DIAGRAM%20PENYEWAAN.png%22%2C%22type%22%3A%22image%2Fpng%22%2C%22signedurl_expire%22%3A%222028-02-03T16%3A32%3A56.511Z%22%2C%22signedUrl%22%3A%22https%3A%2F%2Fmedia-hosting.imagekit.io%2F%2F02d280739c174c2f%2FDIAGRAM%2520PENYEWAAN.png%3FExpires%3D1833208377%26Key-Pair-Id%3DK2ZIVPTIP2VGHC%26Signature%3DHxnBY7RbhjVwUnKjvhciTy-NnM7fpKWEAesflJUdOTLNfG7acdsNxQ6ln9iKfDu7lvpYmJfiejJCYSCLOfoMiqSfgIMosx-Row7ZwvbVZrvbS-w7OQxDt1fCrht1DlRhhWqoee1uGbdcmtkCGXV1m26hlgovKMBo4Sxsj4Ez6OqzvpNswgW8~S~F5yZa~3MFKnFvqBCxJnBPNvElpqxnmxNMwOVmSY3nTfrSAxzKeSArJF5WpigdZyss~hvxeupuWBj5U6yawMgBTgjcpF0or98sOvdzRY1YINyB0wJrWU6XQDsmPDcM6lvKx9WHjU5z7vhKdMPLntXgEooT9tDx6g__%22%7D)

[Gambar Diagram pengembalian] (https://imagekit.io/tools/asset-public-link?detail=%7B%22name%22%3A%22DIAGRAM%20PENGEMBALIAN.png%22%2C%22type%22%3A%22image%2Fpng%22%2C%22signedurl_expire%22%3A%222028-02-03T16%3A47%3A57.227Z%22%2C%22signedUrl%22%3A%22https%3A%2F%2Fmedia-hosting.imagekit.io%2F%2Fbf7540b55adb43f3%2FDIAGRAM%2520PENGEMBALIAN.png%3FExpires%3D1833209277%26Key-Pair-Id%3DK2ZIVPTIP2VGHC%26Signature%3DMLeMhCiRJeBqNxAFZkVQFwr9blG3Vv0y-1YgftGmRhR7CKvrhkPSd8Z5hPhnZQ-8bNMPGPOmsPyntwgRUBnMODvm18jpY66eFSNtNhLlYb4NFdAoYOp48THw6o1zGtOyfklSpIjmh0~GeFS6SqzeU-zqw5P1Q8DpYRzWO6ToPD21Azmy-jtOhhCPAR-aTdNdIi2S3naPG75G0UvRIxSDWyaYSv1jP68TRfljQ1ZCpDByAcMs9hFuIGD3XJx0gNV59rmPaKUYS9LTjaFtszUgcQWPWeLofasEqJ6b3kHSHrfey7yzym0oF-1EjQW4DmY6Q-06TPJ7nGIaowIjV8jvug__%22%7D)

[Gambar Use Case] (https://imagekit.io/tools/asset-public-link?detail=%7B%22name%22%3A%22USE%20CASE.png%22%2C%22type%22%3A%22image%2Fpng%22%2C%22signedurl_expire%22%3A%222028-02-03T16%3A48%3A55.165Z%22%2C%22signedUrl%22%3A%22https%3A%2F%2Fmedia-hosting.imagekit.io%2F%2F53c80cbba8e347d5%2FUSE%2520CASE.png%3FExpires%3D1833209335%26Key-Pair-Id%3DK2ZIVPTIP2VGHC%26Signature%3DEQX9CBmJvSQfqTTbdZr5S7OKbrMqTb918-pVk01qbXTiW8vJpEkFXVPQ2DASjVwGQ7Jz1yXn~SC-M7EseboTWr6KdRQkyiI9FrkFYxTd2f9yOA3VDX6rwiy0VOTas9paY5l3q8skumYbth7jH4E4lkRgVM1fb02NMWux-aYmrOHLNtiWTkmf81BgrxZSSZ~90ghflxJUctGFquhpTamh9MvLRsIq1okDwOpdXPIKsfb4QaXXLJuhLuyVhxqWopPw04df91vTBmGCvLRZ5-tOVWE45pHy3qScj-XP5FGTa-YYsqxDzcvD8-WRCQqw5adDuj-OlYnhxO3ZABbI26TgpA__%22%7D)
