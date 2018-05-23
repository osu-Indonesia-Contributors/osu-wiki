Mengganti Teks Judul
=====================

[*Changing the Title Text : The Guide* by: Ekaru](https://osu.ppy.sh/community/forums/topics/14513)

Bagaimana cara mengubahnya
-------------------------

Sayangnya, kamu tidak dapat melakukan ini sendirian. Minta saja [QAT](https://osu.ppy.sh/help/wiki/People/Quality_Assurance_Team) untuk mengganti itu. Hanya mereka yang dapat melakukan itu, jadi berikan saja mereka sebuah catatan tentang apa yang kamu inginkan, dan apabila hal itu cukup beralasan, kamu akan mendapatkan teks judul baru pada mapmu! Gampang, bukan?!

Mengapa Saya harus mengganti itu?
------------

Jika digunakan secara tepat, itu dapat menambah efek tertentu (dengan cara yang baik!) pada sebuah map. Ini mengganti presentasi mapmu secara efektif jika digunakan secara tepat dengan mengganti elemen dan waktu kemunculan judul. Jika kamu seorang storyboarder, ini mungkin akan menjadi keuntungan besar untukmu!

-   Sebuah contoh efektif yaitu [Noisestorm - Solar (Shiirn)](https://osu.ppy.sh/beatmapsets/33483/)
-   Kamu dapat membagi judul jika terlalu panjang untuk sebuah baris: [IOSYS - Kanbu de Todomatte Sugu Tokeru ~ Kyouki no Udongein (DJPop)](https://osu.ppy.sh/beatmapsets/1391/), [Amane - Yume goro mo, Kinou no Koto -Rolling Contact Remix- (TicClick)](https://osu.ppy.sh/beatmapsets/57560/)

Info Umum
-------------

Kirim sebuah PP (pesan pribadi) dengan ini untuk seorang member QAT.

-   Sintaksnya sebagai berikut:

`[firstOption:firstValue,secondOption:secondValue]` dan seterusnya, sebagainya; lihat disitu tidak ada spasi diantara tanda baca

-   Kamu dapat membagi teks judul menjadi baris-baris menggunakan karakter pipa, `|`
-   Pemformatan teks tidak dapat diatur menjadi kata-kata atau simbol-simbol terpisah. Sebagai gantinya, itu berlaku pada sebaris (lihat diatas). Opsi pemformatan seharusnya di awal baris;
-   Baris-baris kosong diperbolehkan, tetapi tolong perhatikan spasi. Standar ukuran font sudah agak besar, dan 3 atau 4 baris dapat memakan seluruh spasi layar;

Apa yang dapat diganti?
--------------------

### Warna dari teks

`colour:R.G.B`

R, G dan B adalah nilai diantara 0 dan 255, dipisahkan oleh titik. Juga catat itu "colo**u**r", sebuah pengejaan kata Inggris Britania dari "warna".

### Waktu munculnya

`time:N`

Waktu dalam milidetik dari awal lagu dimana judul mulai memudar masuk. Itu dipengaruhi oleh sebuah pudar, yang ke 1/20 waktu tunggu dalam ms

### Lama munculnya

`hold:N`

Seberapa lama teks bertahan dalam layar, termasuk memudar masuk dan keluar.

### Ketebalan

`bold:1 or 0`

1 berarti barisnya ditebalkan, 0 — berarti itu biasa saja.

### Ukuran font

`size:N`

Ukuran font dalam [points][Points Link].

Setingan awal
----------

Setingan awal baru untuk setiap map tanpa perubahan artis/judul yang baru dikirim/perbarui adalah:

`[size:20,bold:0]ArtistUnicode|TitleUnicode`

Nilai settingan awal, jika tidak ditentukan:

-   time: previous line + 500
-   bold: 1
-   size: 40
-   colour: 255.255.255
-   hold: 6000

Contoh
----------

`[time:672,size:30,colour:255.0.0,hold:1000]Line 1|[bold:0]Line 2`

Baris pertama akan mulai memudar masuk selama 50 ms pada 672, menjadi warna merah, dan menjadi berukuran sedang dan tebal, memudar keluar ke 0 pada 1672. Baris ke 2 akan memudar masuk selama 300 ms pada 1172 dan memudar menjadi 0 pada 7172, menjadi putih, dan besar tetapi tidak tebal.

[Points Link]: https://en.wikipedia.org/wiki/Point_(typography)
