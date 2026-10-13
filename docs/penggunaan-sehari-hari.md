1. Pendahuluan

Sebagai mahasiswa Teknik Elektro Otomasi, kegiatan belajar tidak hanya berfokus pada teori, tetapi juga mencakup praktikum, pemrograman, perancangan rangkaian, pengujian perangkat, dan pengerjaan proyek secara berkelompok.

Dalam kegiatan tersebut, GitHub dapat digunakan sebagai tempat menyimpan dokumentasi pembelajaran, mengelola source code, mencatat perkembangan proyek, dan berkolaborasi dengan anggota tim.

GitHub bukan hanya tempat mengunggah program yang sudah selesai. Platform ini juga dapat membantu mencatat proses belajar, menyimpan hasil eksperimen, dan mengevaluasi perkembangan kemampuan teknis dari waktu ke waktu.

2. GitHub untuk Mencatat Materi Perkuliahan

Setiap mempelajari materi baru, saya dapat membuat catatan dalam format Markdown dan menyimpannya di repository GitHub.

Materi yang dapat dicatat meliputi:

Dasar-dasar kelistrikan dan elektronika.

Hukum Ohm, tegangan, arus, resistansi, dan daya.

Analisis rangkaian listrik.

Elektronika analog dan digital.

Sistem kendali dan otomasi.

Dasar pemrograman C++.

Mikrokontroler dan embedded system.

Sensor, aktuator, dan komunikasi data.

Git, GitHub, dan dokumentasi proyek.

Contoh struktur direktori catatan:

catatan-kuliah/
├── README.md
├── elektronika-dasar/
│   ├── hukum-ohm.md
│   ├── analisis-rangkaian.md
│   └── komponen-elektronika.md
├── pemrograman/
│   └── dasar-cpp.md
├── mikrokontroler/
│   └── dasar-mikrokontroler.md
└── sistem-kendali/
    └── pengantar-kendali.md

Dengan struktur tersebut, materi dapat dikelompokkan berdasarkan bidang sehingga lebih mudah dicari ketika mempersiapkan kuis, ujian, atau praktikum.

3. GitHub untuk Kegiatan Praktikum

Praktikum merupakan bagian penting dalam pendidikan Teknik Elektro Otomasi. Selain melakukan percobaan, mahasiswa perlu mencatat konfigurasi rangkaian, parameter pengujian, hasil pengamatan, dan kesimpulan.

GitHub dapat digunakan untuk menyimpan:

Tujuan praktikum.

Diagram rangkaian dan wiring.

Daftar komponen yang digunakan.

Source code program.

Parameter dan konfigurasi pengujian.

Hasil pengamatan dan analisis.

Kesimpulan serta saran perbaikan.

Contoh struktur dokumentasi praktikum:

praktikum-elektronika/
├── README.md
├── rangkaian/
│   └── diagram-rangkaian.pdf
├── kode/
│   └── pengujian-led.ino
├── hasil-pengujian/
│   └── hasil-pengamatan.md
└── laporan/
    └── laporan-praktikum.md

Setiap perubahan program dapat dicatat menggunakan commit. Jika program sebelumnya bekerja dengan baik tetapi perubahan terbaru menimbulkan masalah, riwayat Git dapat membantu menelusuri bagian yang berubah.

GitHub tidak menggantikan kebutuhan melakukan pengujian fisik, pengukuran dengan instrumen, atau mengikuti prosedur keselamatan laboratorium.

4. GitHub untuk Proyek Mikrokontroler

Dalam proyek mikrokontroler, program biasanya mengalami banyak revisi. Pin sensor dapat berubah, nilai parameter perlu disesuaikan, atau metode komunikasi perlu diperbaiki.

Saya dapat menggunakan GitHub untuk menyimpan:

Source code Arduino, ESP32, atau STM32.

Konfigurasi pin input dan output.

Program pembacaan sensor.

Program pengendalian aktuator.

Implementasi komunikasi I2C, UART, SPI, atau protokol lain.

Diagram wiring dan skematik.

Catatan debugging serta hasil pengujian.

Contoh struktur proyek:

proyek-mikrokontroler/
├── README.md
├── firmware/
│   ├── src/
│   └── include/
├── hardware/
│   ├── schematic/
│   └── wiring.md
├── docs/
│   ├── cara-kerja.md
│   └── hasil-pengujian.md
└── tests/
    └── catatan-debugging.md

Sebagai contoh, ketika membuat sistem indikator baterai, saya dapat mencatat perubahan pembacaan tegangan, konfigurasi pin analog, tampilan LCD, dan hasil pengujian indikator peringatan.

Dengan demikian, repository tidak hanya berisi program akhir, tetapi juga dokumentasi yang menjelaskan bagaimana sistem dirancang dan diuji.

5. GitHub untuk Proyek Robotika dan Sistem Otomasi

Proyek robotika menggabungkan beberapa bidang, seperti mekanika, elektronika, pemrograman, sensor, aktuator, dan sistem kendali.

GitHub dapat digunakan untuk mengelola bagian-bagian tersebut secara terstruktur.

Contoh pekerjaan yang dapat didokumentasikan:

Algoritma navigasi robot.

Pembacaan sensor jarak dan sensor garis.

Pengendalian motor.

Logika pergerakan dan penghindaran rintangan.

Diagram hubungan antara sensor, kontroler, dan aktuator.

Konfigurasi perangkat lunak.

Hasil simulasi dan pengujian robot.

Misalnya, ketika mengembangkan algoritma navigasi, saya dapat membuat branch khusus untuk menguji algoritma baru tanpa langsung mengubah program utama.

Jika hasil pengujian belum sesuai, saya dapat memperbaiki branch tersebut atau membandingkan perubahan dengan versi sebelumnya.

Untuk proyek yang menggunakan ROS 2, repository juga dapat menyimpan source code package, file konfigurasi, launch file, serta dokumentasi cara menjalankan sistem. File hasil build atau file berukuran besar sebaiknya dikelola sesuai kebutuhan proyek, bukan diunggah semuanya tanpa pertimbangan.

6. GitHub untuk Desain Rangkaian dan PCB

Selain program, pekerjaan mahasiswa Teknik Elektro Otomasi juga dapat mencakup perancangan skematik dan PCB menggunakan perangkat lunak seperti KiCad.

GitHub dapat digunakan untuk menyimpan file proyek yang relevan, misalnya:

File skematik.

File layout PCB.

Daftar komponen atau Bill of Materials.

Diagram koneksi antarperangkat.

Catatan perubahan desain.

Dokumentasi revisi perangkat keras.

Setiap revisi desain dapat disertai pesan commit yang menjelaskan perubahan, misalnya penambahan konektor sensor atau perubahan rangkaian regulator tegangan.

Untuk file proyek tertentu, saya perlu memastikan semua berkas pendukung ikut tersimpan. Saya juga perlu menguji kembali desain dan memeriksa hasil render atau tampilan PCB karena perubahan teks saja tidak selalu cukup untuk memastikan desain benar.

7. GitHub untuk Belajar di Luar Jam Kuliah

Kegiatan belajar tidak berhenti setelah perkuliahan selesai. Saya dapat menggunakan GitHub untuk mendokumentasikan pembelajaran mandiri dan eksperimen kecil.

Contoh kegiatan:

Membuat rangkuman materi elektronika.

Berlatih pemrograman C++.

Mencoba simulasi rangkaian.

Mempelajari datasheet komponen.

Membuat program pembacaan sensor.

Mencatat kesalahan yang ditemukan saat debugging.

Menyimpan hasil eksperimen dan ide proyek.

Menuliskan hal-hal yang belum dipahami untuk dipelajari kembali.

Catatan eksperimen sebaiknya berisi tujuan, metode, hasil, dan kesimpulan. Jika percobaan gagal, hasil tersebut tetap dapat didokumentasikan karena dapat membantu memahami penyebab kegagalan dan mencegah pengulangan kesalahan yang sama.

8. GitHub untuk Mengelola Tugas dan Proyek Kelompok

Dalam tugas kelompok, anggota tim dapat mengerjakan bagian yang berbeda. Misalnya, satu anggota menangani perangkat keras, anggota lain mengerjakan firmware, dan anggota lainnya menulis dokumentasi.

Branch memungkinkan pekerjaan tersebut dikembangkan secara terpisah.

Contoh pembagian pekerjaan:

Branch

Tanggung jawab

docs/materi

Menulis materi dan dokumentasi

feature/sensor

Mengembangkan pembacaan sensor

feature/control

Mengembangkan sistem kendali

docs/testing

Mencatat prosedur dan hasil pengujian

Setelah pekerjaan selesai, anggota tim dapat mengirim perubahan ke GitHub dan membuat Pull Request untuk ditinjau sebelum digabungkan ke branch utama.

Issues dapat digunakan untuk mencatat masalah, pembagian tugas, dan ide pengembangan. Dengan demikian, progres kerja lebih mudah dipantau dan keputusan teknis dapat ditelusuri.

9. Contoh Rutinitas Penggunaan GitHub

Berikut contoh rutinitas yang dapat diterapkan selama kegiatan kuliah dan pengerjaan proyek.

Sebelum kuliah atau praktikum

Membaca kembali catatan dari pertemuan sebelumnya.

Memeriksa dokumentasi atau source code yang akan digunakan.

Menyiapkan daftar pertanyaan tentang materi yang belum dipahami.

Setelah kuliah

Merangkum materi yang dipelajari.

Menambahkan contoh perhitungan atau program.

Menyimpan catatan ke repository.

Membuat commit setelah perubahan diperiksa.

Saat mengerjakan proyek

Membuat branch untuk fitur atau dokumentasi baru.

Mencatat perubahan source code dan konfigurasi.

Menguji perubahan.

Menuliskan hasil pengujian dan masalah yang ditemukan.

Mengirim perubahan ke GitHub jika sudah siap.

Sebelum mengakhiri sesi belajar

Memeriksa file yang berubah dengan git status.

Memastikan tidak ada file penting yang tertinggal.

Membuat commit dengan pesan yang jelas.

Melakukan push jika perubahan perlu dicadangkan di GitHub.

Mencatat target belajar untuk sesi berikutnya.

Rutinitas tersebut dapat disesuaikan dengan jadwal kuliah, praktikum, dan tenggat tugas.

10. Dokumentasi Kesalahan dan Debugging

Kesalahan merupakan bagian dari proses belajar teknik. Daripada hanya memperbaiki program tanpa mencatat penyebabnya, saya dapat membuat dokumentasi debugging.

Format catatan yang dapat digunakan:

# Catatan Debugging

## Masalah
Jelaskan gejala yang ditemukan.

## Kondisi Awal
Catat konfigurasi perangkat dan program.

## Analisis
Tuliskan kemungkinan penyebab masalah.

## Perbaikan
Jelaskan perubahan yang dilakukan.

## Hasil Pengujian
Tuliskan apakah masalah sudah terselesaikan.

## Kesimpulan
Catat pelajaran yang diperoleh.

Catatan seperti ini membantu saya memahami proses pemecahan masalah dan dapat menjadi referensi ketika menghadapi kendala serupa pada proyek berikutnya.

11. Keamanan dan Pengelolaan File

Ketika menggunakan GitHub, saya perlu memastikan repository tidak berisi informasi rahasia atau file yang tidak diperlukan.

Praktik yang perlu diterapkan:

Tidak mengunggah password, token akses, atau private key.

Menggunakan .gitignore untuk mengecualikan file sementara dan hasil build yang tidak perlu.

Memeriksa perubahan sebelum commit.

Memastikan file yang dibagikan tidak memuat data pribadi atau kredensial perangkat.

Membuat cadangan tambahan untuk data penting jika diperlukan.

Memahami bahwa repository publik dapat diakses oleh orang lain.

GitHub bukan pengganti seluruh sistem pencadangan. File proyek penting sebaiknya dikelola dengan strategi penyimpanan dan pencadangan yang sesuai.

12. Evaluasi Perkembangan Kemampuan

Repository dapat menjadi portofolio proses belajar, bukan sekadar kumpulan tugas.

Saya dapat mengevaluasi perkembangan dengan memeriksa:

Konsistensi catatan pembelajaran.

Jumlah eksperimen yang terdokumentasi.

Perbaikan program dari satu versi ke versi berikutnya.

Kemampuan menjelaskan keputusan desain.

Hasil pengujian yang dapat diulang.

Kontribusi dalam proyek kelompok.

Kualitas dokumentasi dan struktur repository.

Jumlah commit saja tidak selalu menunjukkan kualitas belajar. Yang lebih penting adalah isi perubahan, pemahaman terhadap materi, dan kemampuan menerapkan pengetahuan dalam proyek nyata.

13. Kesimpulan

Bagi mahasiswa Teknik Elektro Otomasi, GitHub dapat berfungsi sebagai catatan belajar, tempat penyimpanan source code, dokumentasi praktikum, pengelola proyek robotika, dan sarana kolaborasi.

Dengan membiasakan diri mencatat proses, mengelola versi, menguji perubahan, dan menyusun dokumentasi yang baik, saya dapat membangun pola kerja yang lebih terstruktur. Kebiasaan tersebut juga membantu mempersiapkan diri menghadapi proyek rekayasa yang lebih kompleks di lingkungan akademik maupun profesional.