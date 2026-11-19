# data-mining-assesment-kelompok6
## Praktikum Association Rule Mining (ARM) – Apotek

## Deskripsi
Repository ini berisi dokumentasi dan hasil praktikum Data Mining mengenai **Association Rule Mining (ARM)**. Praktikum ini menggunakan dataset transaksi apotek untuk menemukan pola hubungan antarproduk yang sering dibeli secara bersamaan menggunakan algoritma Apriori dan FP-Growth.

## Tujuan Praktikum
1. Melakukan pra-pemrosesan data transaksi menggunakan metode One-Hot Encoding.
2. Menemukan frequent itemset menggunakan algoritma Apriori.
3. Membentuk aturan asosiasi berdasarkan Support, Confidence, dan Lift.
4. Menganalisis pengaruh perubahan nilai minimum support.
5. Membandingkan performa algoritma Apriori dan FP-Growth.

## Dataset
Dataset yang digunakan merupakan data transaksi apotek dengan jumlah **60 transaksi** dan **12 jenis produk**.

Beberapa produk yang terdapat dalam dataset:
- Masker Medis
- Vitamin C
- Hand Sanitizer
- Plester Luka
- Suplemen Vitamin B
- Betadine
- Termometer
- Paracetamol
- Oralit
- Alkohol Swab
- Tisu Antiseptik
- Minyak Kayu Putih

## Metode dan Algoritma
Praktikum ini menggunakan beberapa metode berikut:
- **One-Hot Encoding:** Mengubah data transaksi menjadi matriks biner.
- **Apriori:** Menemukan kombinasi produk yang sering muncul.
- **FP-Growth:** Menemukan frequent itemset menggunakan struktur FP-Tree.
- **Association Rules:** Menghasilkan aturan asosiasi berdasarkan nilai Support, Confidence, dan Lift.

## Tools dan Library
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Mlxtend

## Struktur Repository
```text
Praktikum-ARM-Apotek/
│
├── Praktikum_Association Rule Mining_Apotek.ipynb
├── Laporan_Praktikum_ARM_Apotek_Kelompok 6.docx
├── apotek_transactions.csv
├── apotek_transactions_onehot.csv
└── README.md
Praktikum-ARM-MarketBasketAnalysis/
│
├── Praktikum_Association Rule Mining_(Market Basket Analysis).ipynb
├── Tugas_Praktikum_ARM_5.1d4.ipynb
├── Tugas_Praktikum_ARM_5.2.ipynb
├── Tugas_Praktikum_ARM_5.3.ipynb
├── transactions_arm_praktikum.csv
└── transactions_arm_praktikum_onehot.csv
```

## Hasil Praktikum
Berdasarkan hasil pengujian:
- Ditemukan 28 frequent itemset menggunakan nilai minimum support 0.10.
- Dihasilkan 12 aturan asosiasi dengan minimum confidence 0.60.
- Aturan asosiasi tertinggi memiliki nilai Lift sebesar 5.000.
- Apriori dan FP-Growth menghasilkan 28 frequent itemset yang identik.
- FP-Growth memiliki waktu eksekusi 1.25 ms, sedangkan Apriori 2.04 ms.

## Kesimpulan
Berdasarkan praktikum yang telah dilakukan, Association Rule Mining dapat digunakan untuk mengetahui pola pembelian produk yang sering muncul secara bersamaan pada transaksi apotek. Hasil analisis dapat dimanfaatkan sebagai bahan pertimbangan dalam penataan produk dan penyusunan strategi penjualan, seperti bundling produk.

---

**Mata Kuliah:** Data Mining (Assesment Kamis 15.00)
**Topik:** Association Rule Mining (Market Basket Analysis)  
**Studi Kasus:** Transaksi Apotek
