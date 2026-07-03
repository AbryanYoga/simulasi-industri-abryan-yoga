## 1. Informasi Dataset
- **Nama File** : `penjualan.csv`
- **Jumlah Baris** : 126 baris data transaksi.
- **Pemisah (Seperator)** : Menggunakan tanda titik koma (`:`).

## 2. Struktur Kolom yang Diidentifikasi
Dataset ini memiliki beberapa kolom yaitu :
1.  `id_transaksi` : ID unik untuk setiap transaksi penjualan
2.  `nama_produk` : Kode atau identitas produk yang terjual
3.  `waktu` : Infromasi tanggal dan jam transaksi
4.  `nama_pembeli` : Nama pelanggan (banyak yang di isi tanda strip `-`)
5.  `jumlah` : Banyaknya kuantitas barang yang dibeli
6.  `harga` : Harga jual per unit produk
7.  `hpp` : Harga Pokok Penjualan (modal awal produk)
8.  `total` : Total nilai transaksi atau keuntungan bersih

## 3. Catatan Pengamatan Awal
- Format data menggunakan pembatas titik koma (`:`) sehingga perlu penanganan khusus saat dibaca di jupyter Notebook nanti
- Kolom waktu masih berupa format teks dan perlu dikonversi ke tipe data tanggal (datetime)