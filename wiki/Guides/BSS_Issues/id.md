---
tags:
- I can't submit my own beatmap!
- beatmap submission system issues
---
# Masalah BSS

*Halaman utama: [Panduan](/wiki/Guides).*

*Catatan: Jangan gunakan panduan ini untuk mencuri beatmap orang lain!*

Apabila [BSS](/wiki/BSS) (Metode Pengajuan Beatmap) tidak mengizinkan Anda untuk mengirim beatmap Anda sebab Anda tidak memilikinya lakukan hal berikut:

1.  Akses folder beatmapset.
    -    Anda dapat mengaksesnya dengan mudah dengan akses `Berkas` lalu `Buka Folder Lagu` dalam [editor beatmap](/wiki/beatmap_editor).
2.  Keluar dari osu! (Ini untuk memastikan perubahan telah diterapkan dengan baik.)
3.  Buka berkas difficulty `.osu` dengan editor teks apapun (seperti Notepad).
4.  Masukkan nama pengguna Anda untuk `Creator`. (Apabila nama pengguna Anda memiliki spasi, gunakan spasi.)
5.  Atur `BeatmapID` menjadi `0`.
6.  Atur `BeatmapSetID` menjadi `-1`.
7.  Pastikan nama folder beatmap tidak diawali dengan angka-angka.
    -    Contoh `1000 - Judul Lagu` seharusnya `Judul Lagu`.
8.  Hapus berkas(-berkas) dalam  folder `SubmissionCache`. Ini terletak di folder instalasi osu!.
9.  Buka kembali osu! dan coba unggah beatmapmu lagi.
10.  Apabila ini gagal, coba petunjuk dibawah.

---

Apabila kau masih mengalami masalah, ikuti petunjuk berikut:

1.  Ekspor beatmap menggunakan editor beatmap.
    1.  `Berkas` lalu `Ekspor Map`.
2.  Keluar dari editor beatmap lalu hapus beatmapset di osu!.
3.  Keluar dari osu!
4.  Pergi ke beatmapset terekspor dan ubah ekstensi dari `.osz` menjadi `.zip` (anda perlu ekstensi berkas agar terlihat dari opsi folder windows untuk melakukan ini).
5.  Ekstrak `.zip` file ini.
6.  Buka berkas difficulty `.osu` dengan teks editor apapun (seperti Notepad).
7.  Masukkan apapun sebagi nama pengguna untuk `Creator`, tetapi jangan gunakan nama pengguna Anda.
8.  Atur `BeatmapID` menjadi `0`.
9.  Atur `BeatmapSetID` menjadi `-1`.
10.  Setelah Anda selesai, arsipkan berkas-berkas kembali ke dalam berkas `.zip`.
11.  Ubah berkas `.zip` ini kembali ke `.osz`.
12.  Impor ke osu! dan coba unggah kembali.
13.  Apabila ini gagal, Anda mungkin ingin membuat topik baru di [subforum Bantuan](/community/forums/5) untuk mencari bantuan lebih lanjut.
