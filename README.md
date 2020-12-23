#Spam Filtering
spam filtering adalah layanan untuk menyaring pesan yang masuk dan mengklasifikasikannya menjadi pesan yang bersifat spam ataupun bukan. 
Pesan yang telah teridentifikasi sebagai pesan yang bersifat  spam akan secara otomatis masuk ke dalam file spam dan tidak ditampilkan
kepada pengguna.
Namun dalam penggunaannya Terdapat beberapa kekurangan yang ditemukan, Kelemahan yang ditemukan pada aplikasi spam filtering yaitu seperti tidak dapat mengidentifikasi pesan spam dari suatu pola pesan baru yang belum pernah dilatih oleh mesin.Sehingga Dibutuhkan Proses Training terlebih dahulu untuk dapat mempermudah sistem untuk mengkalasisfikasin kategori pesan.

## Keterangan Pada Pengaplikasian Proyek
* Proyek ini mengidentifikasi bagaimana cara aplikasi spam filtering dalam
mendeteksi berbagai variasi pesan yang belum pernah ada pada training
set.
* Proyek ini menggunakan metode naïve bayes dalam pengerjaanya.
* Training dataset yang digunakan berasal dari source pesan spam dan
pesan tidak spam yang sudah tersedia sebelumya.
* Input yang diterima berbasis teks dalam bahasa Indonesia.



### Penjelasan Cara Kerja
```Sh
Tahapan dimulai dengan proses pengumumpulan data, pengumpulan data yang
akan disimpan didalam database, data yang telah ada pada database akan
memasuki tahapan preprocessing yang mana data akan dihitung probabilitas di
setiap atribut yang ada menggunakan algoritma Naïve Bayes, dan dilanjutkan pada
tahapan klasifikasi untuk menentukan apakah data berupa email tadi termasuk
email spam ataupun email Ham. 

Data yang telah diklasifikaskan akan kembali
disimpan kedalam database sebagai data training untuk mempermudah
pengklasifikasian data baru. Hal yang sama juga akan dilakukan jika system telah
menerima inputan berupa email baru, data email baru akan diklasifikasikan
sebagai data email spam ataupun email ham, dan akan disimpan kembali ke
database sebagai data training untuk memperkaya pengetahuan sistem mengenai
klasifikasi data email.
```
