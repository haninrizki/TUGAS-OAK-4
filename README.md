**NAMA: M.HANINDITA RIZKI PRATAMA**

**KELAS: SKU2B**

**NIM: 09011182429010**


**1. Jelaskan Struktur Antar Hubungan dan Beri Contohnya?**

Struktur antar hubungan (atau dikenal dengan interconnection structure) merujuk pada cara perangkat-perangkat dalam sebuah sistem komputer dihubungkan dan berkomunikasi satu sama lain. Dalam konteks sistem komputer, struktur ini menggambarkan hubungan fisik dan logis antara komponen seperti CPU, memori, perangkat input/output (I/O), dan perangkat lain.
Tiga jenis struktur antar hubungan yang umum dalam sistem komputer adalah:

Bus: Sebuah jalur atau saluran yang digunakan untuk mentransfer data antara komponen. Bus dapat digunakan untuk menghubungkan berbagai komponen dalam sistem komputer, seperti CPU, memori, dan perangkat I/O.
Contoh: Bus data yang menghubungkan CPU dan memori dalam sebuah komputer untuk mentransfer data.

Switch: Alat yang menghubungkan berbagai perangkat dalam jaringan untuk mentransfer data antara mereka, dengan memilih jalur yang paling optimal berdasarkan pengaturan jaringan.
Contoh: Switch Ethernet yang menghubungkan komputer dalam jaringan lokal (LAN).

Crossbar: Struktur interkoneksi yang memungkinkan komunikasi simultan antara beberapa perangkat. Biasanya digunakan dalam sistem dengan banyak prosesor.
Contoh: Sistem multiprosesor di mana crossbar digunakan untuk menghubungkan berbagai prosesor dan memori.

**2. Bila Terlalu Banyak Modul atau Perangkat Dihubungkan pada Bus, Maka Akan Terjadi Penurunan Kinerja. Sebutkan Penyebabnya?**

Penurunan kinerja pada bus yang menghubungkan banyak perangkat dapat terjadi karena beberapa alasan utama:

Batasan Bandwidth: Setiap bus memiliki batasan dalam hal kecepatan transfer data. Ketika terlalu banyak perangkat terhubung ke bus, maka bandwidth yang tersedia untuk setiap perangkat akan terbagi, mengakibatkan penurunan kecepatan transfer data untuk semua perangkat.

Bottleneck: Bus hanya dapat menangani sejumlah data pada satu waktu. Jika terlalu banyak perangkat yang mengakses bus secara bersamaan, maka akan terjadi antrean atau penundaan (bottleneck) yang memperlambat seluruh sistem.

**3. Umumnya Perangkat Berprioritas Paling Rendah Memiliki Waktu Tunggu Rata-Rata yang Paling Singkat. Dengan Dasar Ini Biasanya CPU Diberi Prioritas Tertinggi pada SBI. Sebutkan Alasan Perangkat Berprioritas 16 Memiliki Waktu Tunggu Rata-Rata Paling Rendah? Dibawah Kondisi Seperti Apa Keadaan Diatas Tidak Berlaku?**

Alasan Perangkat Berprioritas 16 Memiliki Waktu Tunggu Rata-Rata Paling Rendah: Pada sistem pengendalian input/output (SBI), perangkat dengan prioritas lebih rendah (seperti prioritas 16) biasanya diberikan kesempatan untuk mengakses CPU lebih cepat, karena perangkat ini biasanya tidak membutuhkan proses yang rumit atau mendalam. Hal ini mengurangi waktu tunggu karena perangkat ini sering kali diproses lebih cepat dan tidak menuntut banyak perhatian CPU. Biasanya, perangkat dengan prioritas rendah membutuhkan lebih sedikit waktu untuk menyelesaikan tugas-tugas mereka.

Kondisi di mana keadaan ini tidak berlaku: Namun, pernyataan ini tidak berlaku dalam kondisi di mana:

Perangkat berprioritas rendah membutuhkan pengolahan data yang besar atau kompleks: Dalam situasi ini, meskipun perangkat memiliki prioritas rendah, proses yang lebih kompleks dapat menyebabkan waktu tunggu yang lebih lama.

CPU sangat sibuk atau sedang dalam kondisi overload: Jika CPU sedang sibuk menangani tugas yang sangat padat dari perangkat dengan prioritas lebih tinggi, maka perangkat dengan prioritas lebih rendah akan memiliki waktu tunggu yang lebih lama, bahkan jika mereka memiliki prioritas lebih rendah.

Jika ada kesalahan atau gangguan pada perangkat dengan prioritas rendah: Gangguan atau kesalahan pada perangkat berprioritas rendah dapat menyebabkan keterlambatan atau masalah lainnya, yang akhirnya meningkatkan waktu tunggu rata-rata mereka.

Kontensi: Ketika banyak perangkat mencoba menggunakan bus yang sama pada waktu yang bersamaan, ini menyebabkan terjadinya kontensi, di mana perangkat yang tidak mendapatkan akses harus menunggu, yang meningkatkan waktu respons.

Keterbatasan Kapasitas: Beberapa bus memiliki kapasitas terbatas untuk menangani jumlah perangkat atau volume data tertentu. Ketika jumlah perangkat yang terhubung melebihi kapasitas ini, kinerja sistem akan menurun.
