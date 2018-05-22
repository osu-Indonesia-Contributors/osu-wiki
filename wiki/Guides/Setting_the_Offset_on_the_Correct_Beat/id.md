Mengatur Offset dalam Ketukan yang Benar
========================================

[*About Offset Interval* by Alace](https://osu.ppy.sh/community/forums/topics/20998)

Kebanyakan pemain osu tidak jago pada musik, maka kita mendapati beberapa map dengan sebuah masalah:

**Tick putih panjang tidak mengikuti awalan bagian yang sebenarnya**

Pembagi pertama dari sebuah bagian adalah sebuah ketukan berat. Lihat contohnya

***Lagu 4/4:***

**0** 0 0 0 **0** 0 0 0 **0** 0 0 0 **0** 0 0 0

***Lagu 3/4:***

**0** 0 0 **0** 0 0 **0** 0 0 **0** 0 0

Dimana **0** adalah ketukan berat, maka kamu tidak perlu mengatur offset pada itu.

OKOK marilah kita lihat pada contoh ranked map: [Toyosaki Aki - Miracle Happy Day](https://osu.ppy.sh/beatmapsets/11023/)

-   kiou2 menaruh sebuah offset pada 85ms, maka tick putih panjang tidak mengikuti ketukan berat, yang berarti salah. Lihat pada gambar X.

Jika kiou2 menaruh offsetnya pada 527, tick putih panjang akan mengikuti ketukan berat, yang benar. Lihat pada gambar O.

Maka, kita harus memastikan bahwa offset diatur pada ketukan berat.

Saya harap ini membantu.