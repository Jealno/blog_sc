---
author:
  name: "Jeremy Albert"
date: 2020-05-01
linktitle: 
type:
- post
- posts
title: Telkom, Rasionalkan Kebijakanmu!
weight: 10
series:
- Hugo 101
tags : [
    "keluhkesah",
    "telkom"
]
---


## Pengantar

Siapa orang Indonesia yang tidak tahu tentang Telkom? Ya betul salah satu BUMN terbesar di Indonesia yang bergerak di bidang telekomunikasi. Produknya sudah tidak asing di telinga kita seperti untuk end-user adalah Indihome, Telkomsel serta kawanannya, @wifi.id dan by.U. Sedangkan untuk enterprise ada produk khusus yaitu ASTINet. 

Dengan statusnya sebagai BUMN, tentu saja Telkom mampu untuk menjangkau area terluar Indonesia yang sulit untuk dijangkau oleh perusahaan telekomunikasi lainnya. Telkom juga mampu untuk menyediakan layanan yang lebih baik khususnya dalam ketersediaan sinyal yang stabil. Hal tersebut sejalan dengan [tagline Pak Erick Thohir](https://republika.co.id/berita/q8ptgz370/harapan-erick-thohir-dengan-emtaglineem-bumn-untuk-indonesia) yaitu `BUMN Untuk Indonesia`.

Pelanggan produk Telkom pun tidak main - main angkanya. Hanya dari Telkomsel saja, Telkom sudah mempunyai [170 juta pelanggan](https://rmco.id/baca-berita/ekonomi-bisnis/22590/sabet-penghargaan-brand-of-the-year-jumlah-pelanggan-telkomsel-tembus-170-juta-lebih). Untuk Indihome, ada sekitar [7 juta pelanggan](https://www.suara.com/tekno/2020/02/24/163153/indihome-ditargetkan-punya-13-juta-pelanggan-baru-di-2020) dan ditargetkan tahun 2020 menjadi 8,3 juta pelanggan. Jika kita bandingkan dengan total jumlah penduduk Indonesia, 267,7 juta, Telkom sudah menguasai 65% dari total populasi. 

Data diatas menggambarkan bahwa Telkom memang `BUMN Untuk Indonesia`. Lalu kenapa saya membuat judul yang berbanding terbalik dari data diatas? Bukannya dengan mempunyai pelanggan sebanyak itu lantas pelayanannya memang yang terbaik? `Oh belum tentu.`


## Permasalahan

Memangnya apa yang salah dengan layanan Telkom? Apakah Telkom berbuat sesuatu yang salah? Apakah Telkom menutupi sesuatu dari pelanggannya?

## Pembahasan

Sebelum melanjutkan pembahasan yang mendalam, saya ingin mengapresiasi Telkom Group karena sudah memberikan pelayanan yang terbaik yang dapat dilakukan. Saya pun pelanggan indihome dan by.U, merasa cukup puas dengan pelayanan yang diberikan. Contohnya adalah mayoritas tempat yang saya datangi pasti terdapat sinyal Telkomsel dan ketika ISP lain tidak dapat menjangkau wilayah saya, indihome dapat menjangkaunya. Tetapi tidak ada produk yang sempurna. Pasti ada saja hal yang masih kurang dan dapat diperbaiki. Hal itulah yang membuat saya membuat tulisan ini. Dalam tulisan ini, saya juga memberikan beberapa solusi yang dapat di-implementasikan pada sistem Telkom.

Jika kita melihat di forum / group / surat pembaca / web seperti [Media Konsumen](mediakonsumen.com), banyak sekali yang mengeluhkan layanan Telkom. Mulai dari indihome hingga Telkomselnya. Ada yang mengeluhkan lambatnya internet, sulit saat ingin memasang indihome, jawaban CS yang membingungkan, kebijakan yang sering berubah - ubah, sistem FUP yang merugikan konsumen dan lainnya. Saya tidak akan membahas semuanya. Saya hanya akan membahas 2 hal yang saya alami juga yaitu sistem FUP yang merugikan konsumen dan kebijakan yang sering berubah - ubah.

Sebelum melanjutkan membaca, saya ingin memberikan info tambahan guna memahami tulisan berikutnya. Angka Mbps yang terdapat di brosur / website indihome itu satuannya adalah bit atau `b kecil`. Sedangkan satuan yang kita pakai dalam kehidupan sehari - hari adalah byte atau `B besar.` 

Apa maksudnya satuan yang kita pakai dalam kehidupan sehari - hari? Jika kalian menggunakan aplikasi seperti IDM di Windows / net speed indicator di Android, rata - rata aplikasi itu menggunakan satuan byte atau `B besar.` Lalu bagaimana cara mengkonversi `bit` ke `byte`? Mudah saya tinggal dibagi dengan 8. Contohnya adalah ketika saya berlangganan 10Mbps maka konversinya menjadi:
```
Cara 1
10Mbps : 8 = 1.25MBps

Cara 2
10.000Kbps : 8 = 1.250KBps

Catatan:
- 1MB/b = 1000KB/b
Dibaca: 1 Mega byte / bit sama dengan 1000 Kilo byte / bit.

- MB/b > KB/b
Dibaca: Mega byte / bit lebih besar daripada Kilo byte / bit 
```

### Sistem FUP Yang Merugikan Konsumen
Jika kita membaca kebijakan Telkom tentang [Fair Usage Policy (FUP)](https://www.indihome.co.id/pusat-bantuan/indipedia/detail/Fair+Usage+Policy+%28FUP%29), memang betul kebijakan FUP adalah syarat yang tidak dapat dipisahkan saat kita ingin berlangganan indihome dan Telkom berhak mengubah ketentuan kebijakan FUP kapanpun mereka mau. 

Tapi apakah masuk akal jika bandwith diturunkan begitu drastis sementara pelanggan harus membayar `penuh setiap bulan` dan tidak mendapatkan bandwith yang seharusnya di-dapatkan? Setelah saya mencoba untuk mencari alasan kenapa Telkom membuat kebijakan FUP seperti ini, ditemukan [artikel dari CNN](https://www.cnnindonesia.com/teknologi/20160209171225-213-109825/telkom-ungkap-alasan-terapkan-fup-di-indihome) yang mengatakan bahwa kebijakan FUP diterapkan karena adanya pelanggan yang menggunakan bandwidth secara berlebihan. What? Hanya karena kelakuan dari beberapa oknum lalu yang kena dampaknya semua pelanggan indihome? 

Hei anda pembuat kebijakan di Telkom, sepertinya anda perlu belajar dari FirstMedia. Analoginya adalah jika salah satu jari anda terinfeksi, solusinya bukan memotong tangannya, melainkan potong saja jari yang terinfeksi tersebut.

![](/FUP_FM.png)

Seperti yang sudah disebutkan di atas, saya juga pelanggan indihome. Paketan yang saya gunakan adalah Learning From Home 2P 10Mbps. Paketan murah? Iya betul, sebulan hanya membayar Rp 200.000. `Yaelah bro ada harga = ada kualitas.` Pasti opini seperti itu akan muncul, sekali lagi ini bukan masalah harga yang dibayarkan tetapi ada logika yang perlu diluruskan. Anda mau tau seberapa tersiksanya saya tiap bulan karena kebijakan FUP Telkom? Silahkan simak gambar dibawah ini.

![](/FUP_LFH.png)

Miris bukan? 
- Saat saya melewati FUP1 (100GB), maka bandwith saya tersisa 50% dari 10Mbps yaitu 625KBps. 
- Yang parahnya, saat melewati FUP2 (200GB), bandwith saya hanya tersisa 30% dari 10Mbps yaitu 375KBps. 

Hal ini pasti juga dialami oleh pelanggan indihome 10Mbps lainnya sejak bulan April 2020. Saya tidak tahu apakah ini kebijakan FUP selama pandemi corona / akan diubah lagi skema persenannya. Dan setelah melihat gambar diatas, akan ada 2 pertanyaan yang muncul yaitu:
1. Pelanggan indihome lainnya = Eh apa itu? Dapet darimana grafik seperti itu?
2. Telkom = Wah anak ini dapat meteran FUPnya darimana?

Tenang - tenang akan saya jawab, begini jawaban saya:
1. Untuk pelanggan indihome lainnya itu disebut meteran FUP. Seharusnya kalian juga bisa melihatnya saat datang ke plasa. Itu adalah hak anda sebagai pelanggan untuk mengetahui FUP yang berlaku pada paketan yang anda pakai.
2. Untuk telkom, saya mendapatkan ini dari internal anda sendiri. Beliau berkeyakinan bahwa mengetahui meteran FUP itu adalah hak pelanggan. Tidak boleh ada info yang ditutup-tutupi dari pelanggan.

Anda mau yang lebih miris? Saya mempunyai kenalan yang memasang indihome 300Mbps. Biaya yang harus dia bayarkan tiap bulannya adalah kurang lebih Rp 3.000.000. Tetapi masih juga terkena sistem FUP. Silahkan lihat gambar dibawah ini.

![](/300.png)

Memang betul bahwa 20% dari 300Mbps masih sangat besar yaitu 7.5MBps. Tetapi apakah masuk akal pelanggan membayar penuh sebesar 3 juta sedangkan hanya mendapatkan 7.5MBps setelah penggunaan melewati 4TB?

Kritik selanjutnya adalah tidak adanya transparansi tentang besaran FUP di brosur paket / website [indihome](https://www.indihome.co.id/). Saya sadar betul jika anda melakukan itu, maka kemungkinan angka penjualan anda akan menurun karena pelanggan merasa dirugikan / ragu / dan lainnya. Seingat saya Telkom sempat melakukan hal itu tetapi tidak tahu mengapa halaman tentang detail FUP sudah menghilang dari websitenya.

Lalu solusinya apa? Katanya mau menawarkan solusi. Mana solusinya? Sabar hei, dibawah ini akan saya berikan beberapa skenario untuk menyelesaikan masalah FUP yang merugikan konsumen:
1. __Telkom ngotot menggunakan sistem FUP.__ Ok tidak masalah jika anda ingin terus menggunakan sistem itu ke semua pelanggan. Tetapi tolong lebih masuk akal pemotongan bandwithnya dan jangan ada FUP2, 3, 4, dll. Gunakan saja FUP0 (Full Bandwith) dan FUP1 (Pemotongan 20%) untuk paket 10Mbps. Untuk paketan diatasnya, buatlah rasio yang masuk akal seperti yang saya sarankan untuk paket 10Mbps. Perkiraaan saya dibalik FUP ini pasti ada hitungan bisnis yang sangat menguntungkan pihak Telkom. Kenapa begitu? Telkom dapat menekan biaya sewa bandwith menjadi semurah mungkin dan tetap mendapatkan pembayaran penuh tiap bulan dari pelanggannya. Ya Telkom memang perusahaan yang mencari laba sebanyak - banyaknya, tetapi tidak semua cara dihalalkan dong. Dan perilaku ini tidak sejalan dengan tagline `BUMN Untuk Indonesia.` Jika saya boleh mengutip kata - kata dari Pak Erick Thohir, ``mana akhlaknya?``
2. __Manajemen bandwith pelanggan.__ Manajemen yang saya maksud adalah mengatur bandwith pelanggan berdasarkan trafficnya. Untuk solusi ini saya menemukannya dari [sebuah thread di kaskus](https://www.kaskus.co.id/show_post/53bd57676208819b1f8b46e0/7/-), solusi ini juga diduga diterapkan oleh FirstMedia. Silahkan cari kata `shaping` di dalam thread tersebut.
3. __Gunakan AI / pre-programmed robots untuk mendeteksi oknum yang meng-abuse bandwith.__ Idealnya solusi ini yang seharusnya diterapkan. Karena seperti yang sudah ditulis di atas bahwa yang harusnya dipangkas adalah oknum yang nakal, bukan malah membuat kebijakan yang merugikan semua pelanggan indihome.

### Kebijakan Yang Sering Berubah - Ubah
Banyak yang mengatakan bahwa Telkom menerapkan otonomi daerah, yang artinya tiap regional dapat mengatur kebijakannya masing - masing sesuai kebutuhan. Ya betul, saya juga setuju karena tiap daerah mempunyai kebutuhannya masing - masing dan __hanya JIKA kebijakan itu diterapkan dengan benar.__

Pada tanggal 24 Februari 2020, saya sedang ada di kota Semarang dan tinggal di rumah sodara yang memasang indihome 10Mbps. Saya mengkontak salah satu kenalan internal Telkom untuk mengecek apakah internet yang saya pakai sudah FUP / belum. Ternyata sudah FUP melewati 400GB. Dan betul saja ketika saya coba streaming di Youtube, saya hanya mendapatkan 330KBps.

![](/FUP_24Feb.png)

Pada tanggal 27 Februari 2020, pagi hari saya mencoba melakukan download file dan kaget bercampur senang bisa mendapatkan speed sebesar 1.3MBps. Tetapi setelah saya berpikir ulang, seharusnya FUP kan di-reset per tanggal 1 tiap bulannya, ini belum tanggal 1 tetapi kenapa sudah kereset? Lalu saya tanya ke kenalan internal Telkom untuk memastikan internet yang saya gunakan FUP / tidak. Ternyata masih FUP. Aneh bukan? FUP pada waktu itu hanya dipotong 40% dari 10Mbps, jadi seharusnya saya hanya bisa mendapatkan maksimal 750KBps.

![](/FUP_27Feb.png)

Karena saya ingin meminta kejelasan, pada tanggal 18 maret 2020 akhirnya saya datang ke Plasa Telkom Semarang, Jalan Pahlawan No 10. Aneh ya terlampau jauh tanggalnya? Iya maaf saya sibuk saat awal maret. Saya coba tanyakan ke CS dan dikatakan bahwa paketan saya dinaikkan menjadi Streamix 2P 20Mbps tanpa konfirmasi terlebih dahulu sejak tanggal 27 Februari 2020. What? Tanpa konfirmasi? Yang benar saja woi! 

![](/PaketBerubah.png)

Lalu saya menanyakan ulang kenapa bisa ada kenaikan paket tiba - tiba seperti itu. CSnya menjawab `Iya bapak ini adalah kebijakan dari Telkom. Jika bapak tidak berkenan, silahkan bapak menurunkan paketannya kembali ke semula.` Mbak - mbak CS diluar sana, saya menghargai pekerjaan anda karena anda adalah garda terdepan yang berhubungan dengan pelanggan, saya tidak menyalahkan anda. Yang saya salahkan adalah mengapa Telkom membuat kebijakan seperti itu khususnya di kota Semarang? 

Sepengetahuan saya, memang betul paket 3P 10Mbps indihome sekarang sudah dihilangkan untuk pelanggan baru, tetapi anda tidak bisa semena - mena menaikkan paket pelanggan lama yang masih 3P 10Mbps dong. Bayangkan pelanggan anda yang memang hanya mampu membayar 3P 10Mbps lalu anda naikan ke 2P 20Mbps, bagaimana jika pelanggan tidak bisa membayar? Ujung - ujungnya bakal anda matikan internetnya bukan? Dan sekaligus anda kehilangan 1 pelanggan.

Pasti ada yang heran lagi kenapa saya bisa mendapatkan data tersebut? Ya saya dapat data itu dari salah satu internal Telkom. Tetapi untuk pelanggan lainnya, sebenarnya kalian bisa melihat data itu saat datang ke plasa dengan bilang ke CS `Mbak/mas saya mau lihat rincian indihome saya dong.` Kenalan internal saya berkeyakinan bahwa itu juga adalah hak pelanggan untuk mengetahui rincian tagihannya.

Solusi atas masalah ini? Mudah saja, yaitu:
1. __Selalu komunikasi apapun kepada pelanggan.__ Jika diperlukan rombak aplikasi MyIndihome, sediakan 1 section untuk pemberitahuan rutin.
2. __Rampingkan susunan perusahaan / Perbaiki cara komunikasi internal.__ Kenapa ini penting? Karena selalu saja ada penjelasan berbeda antara pegawai satu dengan lainnya. Pegawai A bilang 1, pegawai B bilang 2, pegawai C bilang 3. Yang ujungnya dipusingkan adalah pelanggan. 


## Kesimpulan
Hai petinggi Telkom, saya tau anda adalah perusahaan besar di Indonesia. Bahkan laba bersih anda pada Q3 2019 menembus Rp 16,45T. Pasti anda dituntut tiap tahunnya untuk menghasilkan laba yang lebih besar. Terkadang saya kasihan juga dengan kalian karena di posisi serba salah. Saya bukan tipe konsumen yang hanya menuntut kok pak/bu petinggi Telkom. Saya memikirkan juga dari aspek bisnisnya seperti apa. Contohnya ketika anda memasukkan inject `p01.notifa.info` / `welcome.indihome.co.id` atau yang kalian sebut sebagai `kendedes`, saya tidak masalah. Memang begitulah cara dunia digital bekerja. Tetapi rasanya tidak pantas jika anda menekan bandwith pelanggan anda demi mendapatkan laba yang lebih besar. Balik lagi ke kalimat favorit Pak Erick Thohir yaitu `mana akhlaknya?`

Pasti anda petinggi Telkom adalah orang - orang hebat, buktinya anda sekarang berada di puncak pimpinan telkom. Yuk benahi telkom dengan cara mengevaluasi semua kebijakan yang sering dikeluhkan oleh masyarakat. Mulai dari kebijakan FUP dulu deh. Saya kenal beberapa orang yang tidak memasang indihome hanya karena ada sistem FUP. Bayangkan jika anda merombak kebijakan itu, banyak sekali potensi pemasangan baru indihome. Setelah itu, anda bisa menyelesaikan cara komunikasi internal sehingga tidak terjadi perbedaan penjelasan. Coba deh sekali - kali bapak dan ibu menengok forum / grup, pasti ada saja yang mengeluhkan perbedaan penjelasan antara 1 CS dan CS lainnya.

Akhir kata, saya meminta maaf jikalau gambar yang saya masukkan diatas adalah rahasia internal kalian. Tetapi menurut saya, itu adalah `HAK PELANGGAN.` Pelanggan perlu tahu 100% mengenai produk yang mereka pakai. Jika anda ingin mengkontak saya, telusuri saja blog ini. Anda bisa menemukan kontak saya dengan mudah. 