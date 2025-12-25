# SQL Portfolio: Customer Transactions Analysis

## Deskripsi
Project ini bertujuan untuk menganalisis **perilaku pelanggan, kontribusi pendapatan, serta loyalitas pelanggan**
berdasarkan data transaksi menggunakan SQL.

Analisis dilakukan untuk menjawab pertanyaan bisnis seperti:
- Produk dan kategori apa yang paling menghasilkan pendapatan?
- Bagaimana perilaku pelanggan dalam melakukan pembelian?
- Apakah pelanggan berlangganan lebih loyal dibandingkan non-berlangganan?
- Bagaimana dampak diskon terhadap pembelian pelanggan?

Project ini dibuat sebagai bagian dari **portfolio SQL** untuk menunjukkan kemampuan analisis data
menggunakan query SQL dasar hingga menengah.

---

## About the Data
Dataset terdiri dari satu tabel transaksi pelanggan:

**Table Name:** `customer_transactions_final`

Kolom utama:
- `customer_id` : ID unik pelanggan  
- `age`, `age_group` : usia dan kelompok usia pelanggan  
- `gender` : jenis kelamin  
- `item_purchased` : produk yang dibeli  
- `category` : kategori produk  
- `purchase_amount` : nilai transaksi  
- `season` : musim pembelian  
- `review_rating` : rating pelanggan  
- `subscription_status` : status berlangganan  
- `discount_applied` : status diskon  
- `previous_purchases` : jumlah pembelian sebelumnya  
- `payment_method` : metode pembayaran  
- `frequency_of_purchases_days` : jarak hari antar pembelian  

---

## Use Case & Analysis Scope

### 1. Customer Behavior Analysis
Menganalisis pola perilaku pelanggan berdasarkan:
- Frekuensi pembelian
- Riwayat pembelian sebelumnya
- Segmentasi usia dan gender
- Kepuasan pelanggan (review rating)
- Identifikasi pelanggan berisiko churn

---

### 2. Revenue Contribution Analysis
Menganalisis kontribusi pendapatan dari:
- Total transaksi dan total revenue
- Kategori produk dan item terlaris
- Pendapatan berdasarkan season
- Pelanggan dengan nilai transaksi tertinggi

---

### 3. Subscription & Loyalty Analysis
Menganalisis loyalitas pelanggan melalui:
- Perbandingan nilai pembelian pelanggan berlangganan vs non-berlangganan
- Segmentasi pelanggan berdasarkan `age_group` dan `subscription_status`
- Indikator loyalitas seperti:
  - Repeat purchase (`previous_purchases`)
  - Frekuensi pembelian (`frequency_of_purchases_days`)
  - Customer Lifetime Value (CLV) sederhana
- Identifikasi pelanggan bernilai tinggi namun berpotensi churn

---

### 4. Marketing Strategy Insights
Menyediakan insight untuk mendukung strategi marketing, antara lain:
- Dampak diskon terhadap nilai dan frekuensi pembelian
- Kategori produk unggulan di setiap season
- Preferensi metode pembayaran berdasarkan kelompok usia
- Identifikasi segmen pelanggan prioritas untuk promosi

---

## Key Insights (Ringkasan)
- Pelanggan berlangganan cenderung memiliki nilai pembelian lebih tinggi
- Diskon meningkatkan frekuensi pembelian, namun tidak selalu meningkatkan nilai transaksi
- Beberapa pelanggan bernilai tinggi memiliki tingkat kepuasan di bawah rata-rata
- Setiap season memiliki kategori produk unggulan yang berbeda

---

## Tools & Skills
- SQL (Aggregation, CTE, Window Function)
- Customer Segmentation
- Loyalty & Revenue Analysis
- Business Insight Generation

---

## Notes
Project ini berfokus pada eksplorasi dan analisis data menggunakan SQL.
Hasil query dapat dikembangkan lebih lanjut menjadi dashboard atau analisis lanjutan
menggunakan tools visualisasi.
