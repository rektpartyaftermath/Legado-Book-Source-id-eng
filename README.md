# Legado-Book-Source-id-eng

## Pengenalan
### Fungsi Legado
Legado adalah aplikasi open source yang ditujukan untuk membaca novel dengan sumber(source) novel yang bisa dengan mudah diedit dan ditambah oleh pengguna.
Selain itu, Legado juga bisa digunakan untuk membaca buku lokal dengan format epub dan txt.
### Penginstallan
Untuk menginstall aplikasi Legado, diperlukan perangkat android minimal android lollipop, 
tempat mendownloadnya, bisa ke [sini](https://android.izzysoft.de/repo/apk/io.legado.app.release)
### Penggunaaan
Aplikasi ini masih menggunakan bahasa inggris, dan cina, jadi untuk penggunaanya akan lebih susah
untuk yang tidak paham.
Coba-coba saja, nanti akan paham sedikit demi sedikit.
### Menambahkan sumber(Source) novel
Ketika pertama di install, aplikasi ini tidak memiliki sumber novel sama sekali, untuk menambahkan 
sumber novel, anda bisa mengunduh file bookSource.json di repositori ini(klik view code), kemudian
buka Legado lalu ke tab me(tab yang paling kanan bawah), kemudian ke source management, klik titik tiga di pojok kanan atas, pilih import local, pilih app file picker, kemudian cari file yang diunduh tadi.
Untuk saat ini, hanya terdapat 4 source novel, yaitu:
- MTLNovel English
- LightNovelPub (cuma bisa urut dari tanggal, ga bisa search)
- MTLNovel Id
- NovelRingan (cuma bisa search)

Itupun masih belum 100% selesai, sebagian dari source tsb, masih dalam pengembangan, namun sudah bisa digunakan untuk membaca novel.  
Untuk MTLNovel, tidak didukung fitur search novel, namun kolom search ini bisa digunakan untuk
menambahkan 1 judul ke Legado, dengan cara, buka sebuah novel dari mtlnovel, pastikan alamat nya sebagai berikut: https://mtlnovel.com/judul-novel/ , kemudian hapus dan sisakan bagian /judul-novel/, lalu hapus lagi garis miring nya(/) menyisakan hanya judul-novel , lalu copy teks tsb, kemudian paste kan ke tab search di dalam aplikasi Legado.  
Kedepannya diharapkan bisa lebih banyak dan komplit source nya.
Khusus untuk LightNovelPub, setiap sebelum digunakan, sentuh dan tahan LightNovelPub di tab Discovery, kemudian akan muncul opsi Login, pilih opsi Login, tunggu hingga cloudflare scan nya selesai dan terus dialihkan ke home LightNovelPub, lalu tekan centang di pojok kanan atas, ulangi langkah ini jika hasil Discovery kosong(empty).
### Membuat source sendiri
Untuk mengedit atau membuat source, bisa dilakukan dalam tab me>source management, Legado menggunakan Jsoup untuk memparse html dari source tsb, ada juga sintaks-sintaks tertentu yang digunakan Legado, info lebih lanjut bisa ke sini, web tutor nya masih dalam bahasa cina, namun anda bisa menggunakan chrome translate untuk menerjemahkannya, sangat kompleks dan ga jelas bagi saya.

