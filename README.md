## PENJELASAN

![Screenshot (70)](https://github.com/arjuna46/ProjekUAS/assets/147571007/494b6536-0378-4ee2-908e-c40db51e8724)

Fungsi akhir() yang Anda berikan terlihat seperti bagian akhir dari program, di mana perhitungan total harga, potongan harga, pembayaran, kembalian, dan pesan terakhir dilakukan. Di bawah ini adalah penjelasan untuk setiap bagian dari fungsi tersebut:
oin-poin penting dari fungsi akhir():

- Perulangan for harga in total:: Ini akan mencetak subtotal dan perhitungan lainnya sebanyak elemen yang ada dalam list total. Namun,    sebaiknya perulangan ini dihapus karena tampaknya tidak diperlukan.

- Perhitungan Diskon: Berdasarkan total pembelian (a), diskon dihitung sesuai dengan kondisi tertentu.

- Pembayaran dan Kembalian: Pengguna diminta untuk memasukkan jumlah pembayaran, dan kembalian dihitung.

- Pesan Penutup: Menampilkan pesan terima kasih sebagai penutup transaksi.

-Catatan Akhir: Terdapat pemanggilan fungsi daftar_barang() di bagian terakhir kode. Harap dicatat bahwa fungsi ini harus didefinisikan sebelumnya dalam program agar tidak terjadi kesalahan.

-Saran: Pertimbangkan untuk memindahkan pemanggilan daftar_barang() ke bagian awal program atau sebelum fungsi akhir(). Ini akan memastikan bahwa fungsi daftar_barang() sudah didefinisikan sebelum digunakan.
