---
author:
  name: "Jeremy Albert"
date: 2020-04-16
linktitle: 
type:
- post
- posts
title: Telegram, Apa Rahasiamu?
weight: 10
series:
- Hugo 101
tags : [
    "keluhkesah",
    "telegram"
]
---


## Pengantar

Telegram adalah salah satu dari sekian banyaknya aplikasi instant-messaging yang tersedia di Android & iOS. Banyak kelebihan yang ditawarkan dan sulit disaingi oleh aplikasi kompetitor. Seperti unlimited storage, member grup yang mampu mencapai 200,000 orang, dapat mengatur perangkat yang login, pengelompokan chat yang dapat diatur bebas oleh pengguna, open-source, API manajemen bot, privasi diutamakan, tidak ada iklan, enkripsi yang ketat dan masih banyak lainnya. Siapa yang tidak tergiur dengan semua kelebihan tersebut? Dan yang perlu diingat, Telegram tidak memungut biaya sepeserpun alias ```GRATIS``` dari penggunanya.

Saat ini pengguna bulanan Telegram sudah mencapai [300 juta orang](https://www.sec.gov/litigation/complaints/2019/comp-pr2019-212.pdf) di seluruh dunia. Banyak yang memanfaatkannya untuk membuat grup komunitas sampai grup chit-chat. Dari grup yang berfaedah hingga yang tidak berfaedah. Secara pribadi dengan hadirnya Telegram memberikan banyak hal positif mulai dari bertemu orang - orang hebat hingga mendapatkan ilmu dari berbagai bidang secara cuma - cuma.

Hadirnya Telegram juga memberikan culture-shock bagi industri IT. Kenapa? Telegram menjunjung tinggi privasi pengguna. Hal itu sangat bertolak belakang dengan industri IT saat ini yang selalu berusaha untuk merekam / mengambil data penggunanya. Tujuan dilakukannya perekaman / pengambilan data pengguna sejatinya untuk funding dan tentu saja mencari profit sebesar - besarnya. Karena Telegram mengambil jalan yang bertolak belakang dengan industri maka Pavel Durov harus [mengeluarkan dana dari kantong pribadinya](https://telegram.org/faq#q-how-are-you-going-to-make-money-out-of-this) untuk membiayai semua infrastruktur dan gaji pegawainya.

## Permasalahan

Dengan penjabaran di bagian pengantar, apa pengguna Telegram pernah bertanya tentang cara Telegram menutup semua biaya infrastrukturnya? Atau penggunanya malah terlena dengan layanan yang diberikan? 

## Pembahasan

Sebelum membuat aplikasi Telegram, Pavel Durov adalah pendiri dari VK.com. Perusahaan itu dia dirikan tahun 2006 dan memutuskan untuk menjual sahamnya pada tahun 2013 - 2014 dengan banyaknya drama di balik proses tersebut. Dari penjualan saham yang dimilikinya, estimasi total uang yang didapatkan Durov adalah $300 juta.

Pada tahun 2018, Durov mendapatkan suntikan dana yang besar senilai $1.7 milyar. Rencananya dana itu akan digunakan untuk membuat [TON, sebuah sistem blockchain](https://telegram.org/blog/ton-gram-notice) yang di-integrasikan dengan aplikasi Telegram. Dengan hanya menambah total dana yang Durov dapatkan saat menjual VK dan suntikan dana pada tahun 2018, sepertinya Durov dapat membuat segalanya menjadi kenyataan. Ditambah dengan fakta dari [Forbes](https://www.forbes.com/profile/pavel-durov/#45a61f4714c5) bahwa total kekayaannya adalah $3.4 milyar (Per 16-4-2020). Saya hanya memasukan data tentang kekayaan Durov yang infonya dapat dicari di internet.

### Pengeluaran
Sekarang kita akan memulai untuk melakukan perhitungan matematika sederhana untuk meng-estimasi total pengeluaran Telegram dalam 1 bulan, sebagai berikut:

1. __Unlimited Storage.__ Jika melihat [pricing yang terdapat di Google Suite](https://gsuite.google.com/pricing.html), untuk mendapatkan Drive Unlimited `minimal` memilih plan `$12/bulan`. Karena di dalam plan itu terdapat layanan lainnya selain drive unlimited, jadi kita dapat mengasumsikan jika hanya drive unlimitednya saja maka biayanya menjadi `$1/bulan`.

```
Biaya Unlimited Storage Per User
Total = Total User x Biaya unlimited Storage/bulan
Total = 300 juta orang x $1/bulan
Total = $300 juta/bulan

Angka yang fantastis bukan? 
Ingat, ini hanya baru dari unlimited storagenya.
```

2. __Gaji Pegawai.__ Menurut [Craft](https://craft.co/telegram-messenger), total pegawai yang dimiliki Telegram adalah 351 orang (Per Desember 2019). Kita asumsikan rata - rata gaji per bulan masing - masing adalah Rp. 5.000.000,-
```
Gaji 351 Pegawai Telegram
Total = Total Pegawai x Asumsi Gaji/bulan
Total = 351 orang x Rp 5.000.000,-/bulan
Total = Rp 1.755.000.000,-/bulan

Jika diubah ke dalam mata uang dollar ($1 = Rp 10.000,-) menjadi $175.500/bulan.
```

3. __Data Center.__ Menurut [Om Sadal](https://t.me/tentangtelegram/119382), Telegram memiliki DC sebanyak 5 buah. Dikarenakan sulitnya mencari angka pasti mengenai total pengeluaran DC, saya menggunakan data dari [James Hamilton](https://perspectives.mvdirona.com/2010/09/overall-data-center-costs/) yang mengatakan bahwa perkiraan pengeluaran per bulan untuk DC yang ideal adalah $3,5 juta/bulan. Sayangnya data itu dibuat sudah dari tahun 2010 sehingga pasti ada pergeseran nominal, bisa naik maupun turun.
```
Data Center Telegram
Total = Total DC x Biaya/bulan
Total = 5 x $3.5 juta/bulan
Total = $17.5 juta/bulan
```

Jika poin 1 - 3 ditotal, maka pengeluaran Telegram dalam 1 bulan adalah sebagai berikut:
```
Biaya Unlimited Storage 300 juta pengguna   = $300 juta/bulan
Gaji 351 Pegawai                            = $175.000/bulan
5 Data Center                               = $17.5 juta/bulan
                                            ------------------- +
                                              $317.675.000/bulan
```
### Pemasukan
Sekarang kita akan menghitung total kekayaan Durov berdasarkan tulisan yang sudah dibuat sebelumnya.
```
Hasil Penjualan VK      = $300 juta
Suntikan Dana 2018      = $1.7 milyar
Kekayaan Durov Per 2020 = $3.4 milyar
                        -------------+
                          $5.4 milyar
```

### Hitungan Antara Pemasukan dan Pengeluaran
```
Total Dana Yang Dimiliki Durov    = $5.4 milyar
Pengeluaran Telegram Per Bulan    = $317.675.000

Maka usia Telegram hanya tersisa 17 bulan saja.
```
Tolong diingat ini adalah hitungan yang sangat kasar. Kenapa dibilang begitu? 
1. Saya tidak menghitung biaya operasional Telegram dari tahun 14 Agustus 2013 - 16 April 2020.
2. Saya menambahkan dana hasil penjualan VK yang mungkin saja sudah habis untuk operasional dari tahun 2013.
3. Penggunaan data tahun 2010 tentang nominal pengeluaran data center.


## Kesimpulan
Apa anda sudah membaca semua perhitungan diatas? Hal itulah yang membuat saya hingga hari ini masih meragukan sumber dana operasional Telegram. Saya sempat berpikir apa memang ada orang yang berhati malaikat hingga merelakan kekayaannya untuk menyediakan aplikasi yang gratis, tidak ada iklan, dan privasi diutamakan. Jika memang Durov melakukan itu, maka kita bisa memberikan predikat `Privacy Saver` kepadanya. Jika ternyata  `"privasi diutamakan"` adalah kebohongan belaka, maka pasti ada agenda lain di balik aplikasi Telegram.

Berulang kali saya membahas hal ini di grup [Tentang Telegram](https://t.me/tentangtelegram). Sebelumnya terima kasih bagi admin telah mengijinkan saya membahas hal ini. Kenapa saya berterima kasih? Menurut saya jika topik ini diangkat cukup `menyerang` pihak Telegram, apalagi saya mengangkat topik itu di grup yang dikhususkan untuk pembahasan Telegram. Sewaktu ketika [Om Sadal](https://t.me/sadal) memberikan sudut pandang menarik yaitu bisa saja Telegram merugi selayaknya layanan lainnya  hingga nanti di suatu titik Durov akan menjualnya untuk mengembalikan semua dana yang telah dia investasikan. Poin yang menarik memang. Tetapi agar Durov dapat mencapai titik itu, maka diperlukan dana backup terus - menerus yang jumlahnya sangat fantastis yaitu $300 juta/bulan. Itu dana yang sangat besar.

Dengan hitung-hitungan diatas, secara pribadi saya menjadi sedikit ragu terhadap salah satu kelebihan Telegram, yaitu `"privasi diutamakan"`. Maaf jika terkesan negative-thinking karena begitulah cara industri IT tetap berjalan dengan cara mengolah lalu menggunakan data pengguna untuk iklan/penelitian/dan lain-lain. Sekarang kita coba hitung ulang dengan cara anggaplah biaya unlimited storage itu dipangkas menjadi $0.5/bulan, tetap saja per bulannya Telegram dibebani tagihan $150 juta hanya untuk storage. 

Mungkin memang ada permainan di balik Telegram. Ntah permainan apa itu. Bisa saja `"jahat"` / Telegram melakukan hal yang sama dengan pelaku industri IT lainnya yaitu mengolah dan menggunakan data penggunanya. Tetapi kenapa belum ketahuan? Karena enkripsi dari aplikasi Telegram sangat rumit dan diklaim paling aman untuk aplikasi instant-messaging. Saya rasa hanya tinggal menunggu waktu hingga ada yang bisa memecahkan enkripsi tersebut.

Kalimat penutupnya adalah di jaman serba IT seperti sekarang, data adalah tambang emas. Tambang emas bukan lagi tanah yang harus digali di ujung dunia melainkan data yang dipanen melalui produk digital.