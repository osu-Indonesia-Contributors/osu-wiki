# Mengedit Audio

_Lihat lebih lanjut [Basic MP3 Modifications](/wiki/Beatmap_Editor_Guides/Basic_MP3_Modifications)_

[osu!academy](/wiki/Announcements/osu!academy) sudah membahas pada [Episode 15: Audio Encoding (4:02)](http://www.youtube.com/watch?v=muu3HkG38kk).
Episode itu juga berisi tentang bagaimana cara memasang dan menggunakan Audacity dengan kemampuan ekspor `.mp3` LAME.

Artikel ini bertujuan sebagai petunjuk untuk membantu Anda melakukan perubahan-perubahan kecil untuk file audiomu untuk membuat beatmap.
Dengan menambahkan ini, Anda dapat membantu sesama beatmapper untuk membuat file audio yang pas untuk kebutuhan apapun.

_Tanpa maksud apapun ini adalah software yang hanya Anda dapat gunakan, tentunya ini hanya daftar dari yang telah menambahkannya disini._
_Jika Anda tahu peralatan-peralatan lain yang dapat digunakan dan dijelaskan cara penggunaannya untuk bagian penjelasan dibawah, tolong tambahkan mereka._

## Audacity (dan LAME)

[Audacity](http://audacity.sourceforge.net/download/) adalah software open source pengubah dan perekam audio.
Untuk menggunakan ini secara benar untuk `.mp3`, Anda akan perlu menggunakan LAME.

[LAME](http://lame.sourceforge.net/) adalah sebuah `.mp3` encoding library yang dapat membuat Audacity mengekspor file suara di dalam `.mp3` format ketika menggunakan bit rates yang berbeda.
Untuk memasang LAME pada Audacity, rujuk ke [Audacity wiki](http://wiki.audacityteam.org/index.php?title=Lame_Installation#Windows_Instructions).

### Menurunkan Bit Rate

Pasang Audacity dan LAME, buka Audacity dan ikuti langkah-langkah berikut:

1. Buka file `.mp3` yang ingin Anda turunkan bit ratenya.
2. Tekan `Ctrl` + `Shift` + `E`, atau
    1. Klik `File`.
    2. Klik `Export Audio...`.
3. Ubah "Save as type:" menjadi `MP3 Files`
4. Dalam "Format Options", klik pada `Average` sebagai mode bit rate.
5. Navigasikan ke lokasi dimana Anda mau untuk menyimpan file.
    - Anda juga dapat mengubah nama file.
6. Klik `Save`.

### Perulangan

Pasang Audacity dan LAME, buka Audacity dan ikuti langkah-langkah berikut:

1. Buka file `.mp3` yang Anda mau ulangi.
2. Klik dan tarik untuk menandai bagian yang mau Anda ulangi.
    - Sangat jarang, itu akan menjadi akhir dari musik.
    - Terkadang chorus atau reffrein yang diulang menjadi bagus.
3. Tekan `Ctrl` + `C`, atau
    1. Klik `Edit`
    2. Klik `Copy`
4. Cari sebuah tempat untuk dimana Anda dapat mengulang bagian yang Anda salin.
5. Press `Ctrl` + `V`, atau
    1. Klik `Edit`
    2. Klik `Paste`
6. Mainkan seluruh bagian musik dan pastikan bahwa bagian ulang terdengar bagus.
7. Ulangi sebanyak yang dibutuhkan
8. Tekan `Ctrl` + `Shift` + `E`, atau
    1. Klik `File`
    2. Klik `Export Audio...`.
9. Ubah "Save as type:" ke `MP3 Files`
10. Dalam "Format Option", klik pada `Average` sebagai mode bit rate.
11. Klik `Save`.

### Memotong

Pasang Audacity dan LAME, buka Audacity dan ikuti langkah-langkah berikut:

1. Buka file `.mp3` yang ingin Anda potong.
2. Klik dan tarik untuk menandai bagian yang mau Anda potong.
    - Ini seharusnya menjadi outro panjang yang tidak ingin Anda map.
3. Tekan `Delete`.
4. Klik dan tarik 3 sampai 5 detik terakhir pada akhiran.
5. Klik `Effect`.
6. Klik `Fade Out`.
7. Tekan `Ctrl` + `Shift` + `E`, atau
    1. Klik `File`.
    2. Klik `Export Audio...`.
8. Ubah "Save as type:" menjadi `MP3 Files`
9. Dalam "Format Options", klik pada `Average` sebagai mode bit rate.
10. Navigasikan ke lokasi dimana Anda ingin simpan file tersebut.
    - Anda dapat mengubah nama file juga.
11. Klik `Save`.

## mp3DirectCut

[mp3DirectCut](http://mpesch3.de1.cc/mp3dc.html) adalah software pengubah audio gratis.
Alat ini direkomendasikan ketika Anda hanya ingin menaikan/menurunkan volume atau memotong audio sebagaimana ini tidak membutuhkan Anda me-encode ulang audio, yang berarti lebih sedikit kehilangan kualitas.

### Perulangan

Pasang dan buka mp3DirectCut, kemudian ikuti langkah-langkah berikut:

1. Buka file `.mp3` yang Anda mau ulangi.
2. Klik dan tarik untuk menandai bagian yang mau Anda ulangi.
    - Sangat jarang, itu akan menjadi akhir dari musik.
    - Terkadang chorus atau reffrein yang diulang menjadi bagus.
3. Tekan `Ctrl` + `C`, atau
    1. Klik `Edit`
    2. Klik `Copy`
4. Cari sebuah tempat untuk dimana Anda dapat mengulang bagian yang Anda salin.
5. Press `Ctrl` + `V`, atau
    1. Klik `Edit`
    2. Klik `Paste`
6. Mainkan seluruh bagian musik dan pastikan bahwa bagian ulang terdengar bagus.
7. Ulangi sebanyak yang dibutuhkan
8. Tekan `Ctrl` + `W`, atau
    1. Klik `File`
    2. Klik `Save complete audio...`.
9. Navigasikan ke lokasi dimana Anda ingin menyimpan file.
    - Anda dapat mengubah nama file juga.
10. Klik `Save`.

### Memotong

Pasang dan buka mp3DirectCut, kemudian ikuti langkah-langkah berikut:

1. Buka file `.mp3` yang ingin Anda potong.
2. Klik dan tarik untuk menandai bagian yang mau Anda potong.
    - Ini seharusnya menjadi outro panjang yang tidak ingin Anda map.
3. Tekan `Delete`.
4. Klik dan tarik 3 sampai 5 detik terakhir pada akhiran.
5. Tekan `Ctrl` + `F`, atau
    1. Klik `Edit`
    2. Klik `Simple fade to/from position`.
6. Tekan `Ctrl` + `W`, atau
    1. Klik `File`
    2. Klik `Save complete audio...`.
7. Navigasikan ke lokasi dimana Anda ingin menyimpan file.
    - Anda dapat mengubah nama file juga.
8. Klik `Save`.

### Mengatur volume

Pasang dan buka mp3DirectCut, kemudian ikuti langkah-langkah berikut:

1. Buka file `.mp3` yang Anda ingin atur.
2. Tekan `Ctrl` + `A` untuk memilih semua.
3. Tekan `Ctrl` + `G`, atau
    1. Klik `Edit`
    2. Klik `Gain...`
4. Markahi checkbox `Lock Sliders`.
5. Ambil geseran kiri dan turunkan itu.
    - dB (desibel) yang Anda atur akan beragam, coba saja beragam volume sampai Anda merasa itu bagus.
6. Ketika Anda puas, tekan `OK`.
7. Tekan `Ctrl` + `W`, atau
    1. Klik `File`
    2. Klik `Save complete audio...`.
8. Navigasikan ke lokasi dimana Anda ingin menyimpan file.
    - Anda dapat mengubah nama file juga.
9. Klik `Save`.
