---
author:
  name: "Jeremy Albert"
date: 2020-04-19
linktitle: 
type:
- post
- posts
title: 2FA, Yang Salah Pengguna atau Pemilik Aplikasi?
weight: 10
series:
- Hugo 101
tags : [
    "keluhkesah",
    "2fa"
]
---


## Pengantar

Two Factor Authentication atau yang biasa disingkat 2FA adalah fitur keamanan tambahan dimana kita sebagai pengguna diharuskan untuk melakukan proses verifikasi sebanyak dua kali. Biasanya pengguna akan diminta untuk memasukkan password lalu setelah berhasil akan dikirimkan SMS kepada nomor yang terdaftar pada akun tersebut. Sayangnya masih ada pengguna yang acuh terhadap hal tersebut. Alhasil banyak kasus terjadi terkait social-engineering.

Social-engineering adalah pendekatan berteknologi rendah yang dirancang oleh seseorang untuk membuat anda memberikan informasi pribadi / data sensitif lainnya dengan tujuan menipu. Pendekatan ini dapat dilakukan secara online maupun offline. Contohnya adalah saat ada seseorang menghubungi anda dan berkedok bahwa dia utusan dari gojek lalu meminta kode OTP pada nomor anda yang terdaftar di aplikasi Gojek. Orang itu sudah melakukan kegiataan social-engineering. Tujuannya? Bisa saja menguras saldo GoPay anda / melakukan transaksi hingga saldo anda nol. Praktek lainnya adalah phising. Apa pula itu phising? Singkatnya adalah jika anda dikirimi suatu isian dapat berupa website / form / lainnya oleh seseorang dan isiannya berkaitan dengan data sensitif seperti email, password, no kartu ATM, dan lainnya. Biasanya data - data itu digunakan untuk melakukan tindakan kriminal.

Dikutip dari [Liputan6](https://www.liputan6.com/tekno/read/4162756/jumlah-kasus-penipuan-online-selama-2019-terbanyak) kasus social-engineering ini sudah menyentuh angka 2.300. Memprihatinkan bukan? `SANGAT.` Seharusnya baju yang dibeli untuk lebaran malah akhirnya hanya bisa memakai baju lebaran yang lama. Seharusnya akan ada seorang anak yang senang dibelikan HP baru tetapi pada akhirnya anak tersebut hanya murung di pojokan kamar. Seharusnya tabungan yang sudah dikumpulkan sejak 10 tahun lalu yang rencananya akan digunakan untuk haji, raib begitu saja.

Yang sangat disayangkan adalah respon dari para pemilik aplikasi. Mereka memang baik membantu penyelidikan hingga tuntas. Tetapi tidak berusaha semaksimal mungkin untuk menutup kerannya. Selama ini yang dilakukan hanya himbauan, himbauan, dan himbauan. Isi dari SMS kode OTP hanya bersifat himbauan untuk tidak menyebarkan kode OTP tersebut. Apakah cara itu efektif? Jika efektif, kenapa masih saja ada kasus social-engineering? Apa pemilik aplikasi kehabisan ide untuk mengedukasi penggunanya terkait keamanan akun?

## Permasalahan

Salahnya ada di sisi siapa? Pengguna yang acuh dan tidak teredukasi? Pemilik aplikasi yang sepertinya kehabisan ide untuk mengedukasi penggunanya? 

## Pembahasan
Secara pribadi, edukasi hanya menggunakan teks adalah sesuatu yang membosankan dan kecil jangkauannya. Mungkin bagi anda yang sedang membaca ini, hal itu cukup. Tetapi ada segmen lainnya yang mengatakan itu tidak cukup. Apalagi di jaman serba modern seperti sekarang, inovasi harus terus dilakukan.

### Solusi Untuk Pemilik Aplikasi
Langsung saja ke solusi yang ingin saya berikan kepada para pemilik aplikasi yang membaca tulisan ini.
1. Petakan terlebih dahulu pengguna anda. Tanpa saya minta, tentu anda semua sudah memiliki peta data tersebut. Data digital itu tambang emas bukan? Hehehe.
2. Lakukan survei tentang apakah pengguna anda keberatan dengan kebijakan 2FA. Jika iya, sertakan alasannya.
3. Jika alasannya adalah ribet dan bertele - tele maka itu tugas selanjutnya yaitu mengedukasi. Perkiraan saya kebanyakan orang tidak menggunakan 2FA karena alasan ribet dan bertele - tele.
4. Jika perlu, lakukan survei lagi kepada pengguna anda tentang konten edukasi apa yang mereka sukai.
5. Lakukan edukasi dengan cara yang berbeda. Bisa sesuai dengan inputan para pengguna anda / lakukan improve dari inputan pengguna anda / kombinasi antara inputan pengguna dan peta pengguna anda. Bosen pak/bu dengan edukasi deretan teks saja. Asli deh suwer.
6. Letakkan konten edukasi keamanan akun pada tempat yang tepat. Jika perlu, highlight konten tersebut. Jangan hanya memikirkan hitungan bisnis ya pak/bu. Tentu jika anda menaruh konten itu pada tempat strategis, akan mengurangi slot iklan anda. Tentu saya mengerti itu, saya mikir dua sisi kok. Tetapi mendingan anda kehilangan pengguna karena dianggap tidak serius tentang edukasi keamanan akun / anda menaruh pada tempat yang strategis dan sekaligus memberikan nilai yang `beda` dibandingkan aplikasi lainnya?

Saya berkeyakinan 100% masalah ini selesai jika anda para pemilik aplikasi berkomitmen tentang keamanan akun pengguna. Saya akan memberikan 2 contoh aplikasi yang menurut saya cukup memperhatikan keamanan akun penggunanya, yaitu [Jenius by BTPN](https://www.jenius.com/en/) dan [Telegram](https://telegram.org/). 
1. Jenius. Aplikasi itu mempunyai tingkat keamanan yang sangat tinggi. Ketika mengubah pengaturan yang sensitif, pengguna diharuskan untuk memasukkan password. Jenius juga memiliki menu `login session` yang berfungsi untuk mengatur akun pengguna terkoneksi dengan device apa saja.
2. Telegram. Reputasinya tentang keamanan dan privasi pengguna tidak perlu diragukan lagi. Salah satunya adalah `login session`. Loh kok sama dengan yang dimiliki oleh Jenius? Eits, ada bedanya loh. Ketika pengguna login pada device baru, secara otomatis Telegram akan membuatkan session baru di menunya dan pengguna di-limitasi untuk menghapus session lamanya di device yang baru di-loginkan. Limitasi ini berlaku 24 jam jika saya tidak salah.

Anda mendapatkan poinnya bukan? Tidak mengerti? Ok saya bantu jelaskan, sebagai berikut:
1. Anda dapat membuat fitur `login session` seperti yang ada di aplikasi Jenius dan Telegram. Sehingga pengguna dapat mengontrol akunnya sudah login ke device apa saja. 
2. Berikan limitasi ke pengguna saat melakukan proses login ke device baru. Tujuannya adalah menghindari perubahan pengaturan sensitif yang ada pada akun. Misalnya adalah mengubah limitasi transaksi maksimal, transfer saldo, dan lain - lain.

Ditambah ada 2 peraturan yang mewajibkan 2FA pada bank dan layanan digital di Indonesia, antara lain:
1. [PBI nomor 20/6/PBI 2018 Tentang Uang Elektronik pasal 37 ayat 2](https://www.bi.go.id/id/peraturan/sistem-pembayaran/Documents/PBI-200618.pdf)
2. [POJK nomor 12/POJK.03/2018 Tentang Penyelenggaraan Layanan Perbankan Digital Oleh Bank Umum pasal 11 ayat 4](https://www.ojk.go.id/id/regulasi/Documents/Pages/Penyelenggaraan-Layanan-Perbankan-Digital-oleh-Bank-Umum/POJK%2012-2018.pdf). 

Hei anda pegawai yang berada di perusahaan aplikasi besar, saya tau anda orang pintar. Buktinya anda dapat bekerja disana sedangkan saya hanya menulis di blog yang di-hosting secara gratis. Tolonglah buat terobosan - terobosan baru. Saya sebagai developer merasa sedih ketika kasus baru terkait social-engineering bermunculan lagi dan lagi di media sosial. Ini isu yang sudah lama bukan? Anda menyerah menangani isu ini? Anda lebih memikirkan hitungan bisnis tanpa memikirkan ekosistemnya?

### Solusi Untuk Pengguna Aplikasi
Ya saya paham betul 2FA adalah hal yang meribetkan hidup kita. Kenyataan hidup saja sudah ribet, ditambah harus menghapalkan kode tambahan. Tetapi sekarang jaman sudah makin maju dan kita tidak bisa membendung hal itu, yang bisa kita lakukan adalah menyesuaikan diri. 

Saya beri 3 sikon yang kemungkinan bisa terjadi:
1. Anda tidak mengaktifkan 2FA dan memberikan kode OTP pada penipu, lalu anda akan repot berurusan dengan pihak polisi dan pemilik aplikasi untuk mengusut pelakunya.
2. Anda mengaktifkan 2FA dan masih saja memberikan kode OTP kepada penipu, akhirnya akan sama dengan poin 1.
3. Anda rela mengorbankan sedikit keribetan dengan mengaktifkan 2FA dan tidak memberikan kode kepada siapapun, akhirnya anda bisa terbebas dari masalah yang justru membuat anda sangat pusing. Uang hilang / ditipu tentu akan membuat anda lebih ribet daripada hanya sekedar mengaktifkan 2FA.

## Kesimpulan
Pada akhirnya, social-engineering dapat terselesaikan jika pemilik aplikasi dapat menjalankan tugasnya dengan baik dan pengguna mematuhi peraturan yang telah dibuat. Jangan saling tunggu - tungguan dan saling menyalahkan. Jangan sampai kalimat dibawah ini terucap lagi:

`Pemilik Aplikasi: Ah itu kan bagaimana penggunanya saja. Mereka bodoh sih udah ditulis pake huruf kapital pada SMS OTP tetapi tetep bandel dengan memberikan kodenya pada orang lain.`

`Pengguna Aplikasi: Ah ini developer aplikasinya tidak jago. Masa keamanan aplikasinya dapat ditembus segitu mudahnya. Ga cocok tuh gajinya dengan produk yang telah dibuat.`

Saling berbuat yang terbaik di masing - masing sisi. Dari sisi pemilik aplikasi, usahakan semaksimal mungkin untuk terus menekan angka kasus social-engineering. Dari sisi pengguna aplikasi, baca, tonton dan ikuti anjuran dari pemilik aplikasi. Harapan saya ke depannya proteksi 2FA ini diwajibkan untuk semua aplikasi, tidak hanya aplikasi e-commerce/bank/layanan digital lainnya, tetapi menjangkau aplikasi yang berpotensi jadi sasaran social-engineering.