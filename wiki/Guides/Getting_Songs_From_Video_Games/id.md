Mendapatkan Lagu-Lagu dari Permainan Video
===============================

Tutorial ini ditujukan kepada mapper yang ingin sebuah lagu dari permainan video, terutama konsol seperti PS2, GCN/Wii, Xbox 360, dsb. Ini dapat termasuk konsol portabel dan yang lebih lama (Lihat SNES, PS1, PSP, N64, NDS, dsb.) tetapi itu membutuhkan hal yang lebih banyak untuk mendapatkan musik dari mereka.

Sebelum Anda mulai
----------------

-   **foobar2000.** Tutorial ini menggunakan v1.1.15 yang merupakan versi rilis stabil terbaru ketika tutorial ini ditulis.
    *Unduh:* <http://www.foobar2000.org/download>
-   **vgmstream decoder plugin.** Tutorial ini akan menggunakan plugin foobar2000 (Versi yang digunakan: r1002) tetapi jika Anda tahu bagaimana cara menggunakan versi standalone, Anda dapat menggunakan itu.
    *Unduh foobar2000:* <http://www.foobar2000.org/components/view/foo_input_vgmstream>
    *Versi standalone:* <http://hcs64.com/vgmstream.html>
-   **LAME Encoder.** Ini dibutuhkan untuk mengubah lagu ke format MP3 sehingga Anda dapat memuat lagu di [osu!](/wiki/Glossary) dan mulai membuat map!
    *Unduh:* <http://www.rarewares.org> (Pilih Lame Bundles dalam menu MP3)
-   **Sebuah backup yang telah diekstrak dari game Anda.** Ini dibutuhkan untuk mendapatkan lagu yang Anda inginkan. Namun, Anda sebaiknya mendapatkan backup sendiri.
    Tutorial ini akan menggunakan *Paper Mario: The Thousand Year Door* sebagai permainan kita.

Memulai
-----------

![Inside of our music folder. Look that we are on the sound/stream folder.](GameMusicTutorial-Screen1.jpg "Inside of our music folder. Look that we are on the sound/stream folder.")

Pertama unduh dan pasang aplikasi yang dibutuhkan di dalam komputer Anda (Jika Anda belum melakukan ini). Ketika Anda sudah memasang mereka, buka foobar2000 dan buka Windows Explorer ke folder music dimana Anda mengekstrak backup.
*Catatan: Nama folder dapat bervariasi tergantung dari permainan. Nama-nama yang biasa untuk folder musik adalah **stream, sound, bgm, music**.*
*Catatan 2: Beberapa permainan menggunakan ekstensi berbeda atau tanpa ekstensi sama sekali disebabkan oleh limitasi engine/ocehan programer/apapun alasannya. Biasanya pencarian Google dapat memberikan Anda informasi mengenai permainan tersebut.*

Memuat lagu kita
----------------

Ketika Anda dalam folder musik permainan, waktunya untuk memuat lagu ke foobar2000. Untuk melakukan itu, pilih semua file dalam folder dan tarik mereka ke jendela foobar. Ketika lagu sudah dimuat, dengarkan satu persatu sampai Anda mendapatkan lagu yang diinginkan. Dalam tutorial ini, kami mencari *Chapter 3 Boss Battle Theme* (Kami tidak bisa memberitahu nama asli untuk mereka yang masih bermain permainan itu :p) maka file kita adalah **btl\_gns1\_32k.stm**.
Silakan mendengarkan lagunya.

Converting
----------

Once you have the song that you are converting, right-click the song in the playlist, select *Convert* and then the *...* option. This will bring you to a dialog so you can select how the conversion will be done.

This list will give you the correct setup for converting them to osu!:

-   **Output Format:** Format: MP3 (LAME), V2. *(The bitrate will setup itself to 190kbps)*
-   **Destination:** Output folder: source file folder.
    Output type: tracks into individual files.
    File name pattern: %title%
-   **Processing:** Hard -6dB limiter. *(Optional)*
-   **Other:** When finished: do nothing.

*Note: If you haven't converted to MP3 in foobar2000 before, the converter will ask you to locate **lame.exe**. Navigate to the folder where you have extracted **lame.exe** and select the file.*

Once you have your options set, click the *Save* button and when it asks to overwrite the preset, click in *Save as new*. Give it a name so you can convert future songs quickly. Once you are ready to convert, click on the *Convert* button so the conversion process can start. Once it's finished, search the folder for the resulting file. In our case, the file is **btl\_gns1\_32k.mp3**.

Finishing
---------

Once we have our converted file, load it in foobar2000 or in your prefered music player to check if the song converted to your linking, if not, review the conversion settings until you have an appropriate file. Once the file is ready, drag it into osu!'s window, fill in the tags and start mapping!
