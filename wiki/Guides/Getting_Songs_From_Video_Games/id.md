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

Mengubah
----------

Setelah Anda memiliki lagu yang ingin Anda ubah, klik kanan pada lagu yang ada di daftar putar, pilih *Convert* dan opsi *...*. Ini akan membawa Anda ke sebuah dialog sehingga Anda dapat memilih bagaimana pengubahan dapat dilakukan.

Daftar ini akan memberikan Anda pengaturan yang benar untuk mengubah mereka ke osu!:
<!--->
    Butuh bantuan disini. (Review)
<!--->
-   **Output Format:** Format: MP3 (LAME), V2. *(Bitrate akan mengatur dirinya sendiri ke 190kbps)*
-   **Destination:** Folder output: Folder file utama.
    Tipe output: Koleksi lagu menjadi file individual.
    Pola nama file: %judul%
-   **Processing:** Keras pembatas -6dB.*(Opsional)*
-   **Other:** Ketika selesai: jangan lakukan apapun.

*Catatan: Jika Anda belum pernah mengubah ke MP3 dalam foobar2000 sebelumnya, pengubah akan menanyakan untuk mencari **lame.exe**. Navigasikan ke folder dimana Anda mengekstrak **lame.exe** dan pilih filenya.*

Setelah Anda mengatur opsi-opsi yang ada, klik tombol *Save* dan ketika itu menanyakan untuk menimpa preset, klik pada *Save as new*. Berikan itu sebuah nama sehingga Anda dapat mengubah lagu dikemudian hari lebih cepat. Ketika Anda siap mengubah, klik pada tombol *Conver* sehingga proses pengubahan dapat dimulai. Setelah selesai, cari folder yang memuat file hasil. Pada kasus kita, file itu adalah **btl\_gns1\_32k.mp3**. 

Penyelesaian
---------

Ketika kita sudah mengubah file kita, muat itu pada foobar2000 atau pada pemutar musik kesukaan Anda untuk mengecek apakah lagu yang diubah sudah sesuai, jika tidak, lihat ulang pengaturan pengubah sampai anda dapat file yang cocok. Ketika file tersebut siap, tarik itu ke window osu!, isi label dan mulai membuat map!
