# Mengedit Audio

_Lihat lebih lanjut [Basic MP3 Modifications](/wiki/Beatmap_Editor_Guides/Basic_MP3_Modifications)_

[osu!academy](/wiki/Announcements/osu!academy) sudah membahas pada [Episode 15: Audio Encoding (4:02)](http://www.youtube.com/watch?v=muu3HkG38kk).
Episode itu juga berisi tentang bagaimana cara menginstall dan menggunakan Audacity dengan kemampuan ekspor `.mp3` LAME.

Artikel ini bertujuan sebagai petunjuk untuk membantu Anda melakukan perubahan-perubahan kecil untuk file audiomu untuk membuat beatmap.
Dengan menambahkan ini, Anda dapat membantu sesama beatmapper untuk membuat file audio yang pas untuk kebutuhan apapun.

_Tanpa maksud apapun ini adalah software yang hanya Anda dapat gunakan, tentunya ini hanya daftar dari yang telah menambahkannya disini._
_Jika Anda tahu peralatan-peralatan lain yang dapat digunakan dan dijelaskan cara penggunaannya untuk bagian penjelasan dibawah, tolong tambahkan mereka._

## Audacity (dan LAME)

[Audacity](http://audacity.sourceforge.net/download/) adalah software open source pengubah dan perekam audio.
Untuk menggunakan ini secara benar untuk `.mp3`, Anda akan perlu menggunakan LAME.

[LAME](http://lame.sourceforge.net/) adalah sebuah `.mp3` encoding library yang dapat membuat Audacity mengekspor file suara di dalam `.mp3` format ketika menggunakan bit rates yang berbeda.
Untuk menginstall LAME pada Audacity, rujuk ke [Audacity wiki](http://wiki.audacityteam.org/index.php?title=Lame_Installation#Windows_Instructions).

### Menurunkan Bit Rate

Install Audacity dan LAME, buka Audacity dan ikuti langkah berikut:

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

Install Audacity dan LAME, buka Audacity dan ikuti langkah berikut:

1. Open the `.mp3` file that you want to loop.
2. Click and drag to highlight the parts you want to loop.
   - Rarely, it would be the start to the end of the music.
   - Sometimes the chorus or refrain is where looping is done best.
3. Press `Ctrl` + `C`, or
   1. Click `Edit`
   2. Click `Copy`
4. Find a location for where you can loop the part you have copied.
   - This could be the end of the part you had highlighed.
5. Press `Ctrl` + `V`, or
   1. Click `Edit`
   2. Click `Paste`
6. Play through the entire music and make sure that the loop sounds good.
7. Repeat as needed.
8. Press `Ctrl` + `Shift` + `E`, or
   1. Click `File`.
   2. Click `Export Audio...`.
3. Change "Save as type:" to `MP3 Files`
4. In the "Format Options", click on `Average` as the bit rate mode.
5. Navigate to the location you want to save the file as.
   - You could rename the file too.
6. Click `Save`.

### Cropping

Install Audacity and LAME, open Audacity then follow these steps:

1. Open the `.mp3` file that you want to crop.
2. Click and drag to highlight the parts you want to crop.
   - This should be the long outro that you don't want to map.
3. Press `Delete`.
4. Click and drag the last 3 to 5 seconds towards the end.
5. Click `Effect`.
5. Click `Fade Out`.
6. Press `Ctrl` + `Shift` + `E`, or
   1. Click `File`.
   2. Click `Export Audio...`.
7. Change "Save as type:" to `MP3 Files`
8. In the "Format Options", click on `Average` as the bit rate mode.
9. Navigate to the location you want to save the file as.
   - You could rename the file too.
10. Click `Save`.

## mp3DirectCut

[mp3DirectCut](http://mpesch3.de1.cc/mp3dc.html) is a free to use audio editing software.
This tool is recommended when you only want to raise/lower the volume or crop the audio as it doesn't require you to re-encode the audio, meaning less quailty loss.

### Looping

Install and open mp3DirectCut, then follow these steps:

1. Open the `.mp3` file that you want to loop.
2. Click and drag to highlight the parts you want to loop.
   - Rarely, it would be the start to the end of the music.
   - Sometimes the chorus or refrain is where looping is done best.
3. Press `Ctrl` + `C`, or
   1. Click `Edit`
   2. Click `Copy`
4. Find a location for where you can loop the part you have copied.
   - This could be the end of the part you had highlighed.
5. Press `Ctrl` + `V`, or
   1. Click `Edit`
   2. Click `Paste`
6. Play through the entire music and make sure that the loop sounds good.
7. Repeat as needed.
8. Press `Ctrl` + `W`, or
   1. Click `File`.
   2. Click `Save complete audio...`.
9. Navigate to the location you want to save the file as.
   - You could rename the file too.
10. Click `Save`.

### Cropping

Install and open mp3DirectCut, then follow these steps:

1. Open the `.mp3` file that you want to crop.
2. Click and drag to highlight the parts you want to crop.
   - This should be the long outro that you don't want to map.
3. Press `Delete`.
4. Click and drag the last 3 to 5 seconds towards the end.
5. Press `Ctrl` + `F`, or
   1. Click `Edit`.
   2. Click `Simple fade to/from position`.
6. Press `Ctrl` + `W`, or
   1. Click `File`.
   2. Click `Save complete audio...`.
7. Navigate to the location you want to save the file as.
   - You could rename the file too.
8. Click `Save`.

### Adjusting the Volume

Install and open mp3DirectCut, then follow these steps:

1. Open the `.mp3` file that you want to adjust.
2. Press `Ctrl` + `A` to select all.
3. Press `Ctrl` + `G`, or
   1. Click `Edit`
   2. Click `Gain...`
4. Check the `Lock Sliders` checkbox.
5. Take the left slider and lower it.
   - The dB (decibels) you set it to will vary, just try various volumes until you get it right.
6. When you are satisfied, press `OK`.
7. Press `Ctrl` + `W`, or
   1. Click `File`.
   2. Click `Save complete audio...`.
8. Navigate to the location you want to save the file as.
   - You could rename the file too.
9. Click `Save`.