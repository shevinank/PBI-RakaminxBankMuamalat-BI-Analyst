# Dashboard Digital User Churn – Final Task VIX BI Analyst Bank Muamalat

Proyek ini merupakan tugas akhir dari program **Virtual Internship Experience** yang diselenggarakan oleh **Bank Muamalat** dengan **Rakamin Academy**. Tugas ini berfokus pada analisis data transaksi penjualan dari berbagai kota dan kategori produk, serta pembuatan dashboard interaktif untuk menghasilkan insight dan strategi bisnis.

---

## Tools dan Teknologi yang Digunakan

- **Google BigQuery** – Untuk ekstraksi dan transformasi data
- **Microsoft Excel** – Untuk pembersihan data & pembuatan tabel master
- **Looker Studio** – Untuk pembuatan dashboard visual interaktif

---

## Struktur Proyek

| Folder / File | Keterangan |
|---------------|------------|
| `data/` | Berisi dataset mentah atau contoh data (Customers, Orders, Products, Product Categories) |
| `sql/` | Berisi query SQL untuk membersihkan dan menggabungkan data |
| `visuals/` | Berisi screenshot dari dashboard akhir & insight visual |
| `presentation/` | File presentasi tugas akhir (PPTX) |
| `README.md` | Dokumentasi proyek ini |

---

## Ringkasan Studi Kasus

Sebagai BI Analyst di PT Sejahtera Bersama, tugas kami adalah:

- Mengolah data dari 4 tabel: `Customers`, `Orders`, `Product Categories`, dan `Products`
- Membuat tabel master berdasarkan urutan tanggal transaksi, yang memuat:
  - `cust_email`, `cust_city`, `order_date`, `order_qty`, `product_name`, `product_price`, `category_name`, dan `total_sales`
- Membangun **dashboard interaktif** menggunakan Looker Studio
- Memberikan **rekomendasi berbasis data** untuk menjaga dan meningkatkan penjualan

---

## Hasil Dashboard

🔗 [Klik di sini untuk melihat dashboard](https://link-dashboard-lookerstudio.com)

![Preview Dashboard](visuals/dashboard_preview.png)

---

## Insight & Rekomendasi Bisnis

1. **Bundling produk mahal & murah** → Meningkatkan rata-rata nilai transaksi
2. **Promosi di kota besar** → Menjaga loyalitas pelanggan utama
3. **Analisis musiman & promo akhir tahun** → Mengatasi penurunan penjualan tahunan
4. **Segmentasi pelanggan untuk email marketing** → Meningkatkan efektivitas kampanye
5. **Analisis performa produk lemah** → Ganti atau tingkatkan kategori yang buruk
6. **Dorong repeat order** → Berikan insentif ke pelanggan baru & tidak aktif

---

## Sekian dan Terima Kasih

