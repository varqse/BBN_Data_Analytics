# BBN Data Analytics

## Final Project for Big Data Analytics

**2602202021 - Alvin Ariyanto Putra**  
**2602181004 - Ishvara Pranidhana Lakshmana**

Dalam project ini, kami menganalisis data penjualan *Bakso Bakar Nyonya* selama bulan September. Analisis ini bertujuan untuk memberikan wawasan mengenai pola konsumsi, preferensi pelanggan, dan tren pasar yang dapat digunakan untuk meningkatkan kinerja bisnis.

---

### Potensi Pasar dan Ketersediaan Data

1. **Potensi Pasar yang Besar**  
   Bakso merupakan makanan favorit masyarakat Indonesia lintas generasi. Hal ini mengindikasikan adanya pasar yang luas dan permintaan yang stabil untuk produk *Bakso Bakar Nyonya*.

2. **Ketersediaan Data yang Lengkap**  
   UMKM *Bakso Bakar Nyonya* memiliki catatan data penjualan dan operasional yang terstruktur, memungkinkan kami melakukan analisis yang mendalam dan akurat.

3. **Relevansi dengan Konsep Big Data Analytics for Business**  
   Melalui analisis data penjualan *Bakso Bakar Nyonya*, kami dapat mengidentifikasi pola konsumsi, preferensi pelanggan, serta tren pasar yang relevan untuk mendukung pengambilan keputusan bisnis berbasis data.

---

### Langkah Analisis

#### 1. Pre-Processing Data
- **Membersihkan Kolom/Data Kosong**: Menghapus atau melengkapi data yang tidak valid atau kosong untuk memastikan kualitas data.
- **Menyeleksi Data yang Penting**: Memilih fitur atau kolom yang relevan untuk proses analisis dan prediksi.

#### 2. Model Algoritma

**Regresi Linear**  
- **Definisi**: Model ini digunakan untuk memprediksi pendapatan per jam dengan asumsi bahwa hubungan antara waktu dan pendapatan bersifat linier.
- **Aplikasi**: Cocok untuk data yang menunjukkan peningkatan jam kerja yang konsisten diikuti oleh peningkatan pendapatan.
- **Alasan Memilih**:  
  - *Simplicity*: Mudah dipahami dan diinterpretasikan.
  - *Hubungan Linier*: Efektif untuk data yang memiliki hubungan linier.
  - *Prediksi Efisien*: Memberikan prediksi yang akurat untuk pendapatan berdasarkan variabel waktu.

_(![image](https://github.com/user-attachments/assets/9a10505e-4fd9-4bb4-89bc-5890ebb7fd82)
)_

**Regresi Polinomial**  
- **Definisi**: Model ini digunakan untuk menangkap pola data dengan fluktuasi yang lebih kompleks dibandingkan regresi linear, menggunakan jam untuk memprediksi pendapatan.
- **Aplikasi**: Menganalisis pendapatan per jam dan mengidentifikasi pola umum dalam data dengan fluktuasi yang lebih tinggi.
- **Alasan Memilih**:  
  - *Fleksibilitas*: Dapat menangkap hubungan non-linier dalam data.
  - *Kemampuan Model*: Lebih akurat untuk data yang memiliki pola fluktuasi signifikan.
  - *Visualisasi yang Jelas*: Memudahkan interpretasi hasil melalui kurva prediksi.

_(![image](https://github.com/user-attachments/assets/f5653348-be19-4c92-966e-0a450e156bf5)
)_

**Forecasting**  
- **Definisi**: Model ini digunakan untuk menganalisis data penjualan dan memprediksi tren di masa depan menggunakan metode deret waktu.
- **Aplikasi**: Memproyeksikan penjualan harian selama 30 hari ke depan, termasuk batas atas dan bawah prediksi.
- **Alasan Memilih**:  
  - *Analisis Tren*: Mengidentifikasi tren penjualan dari data historis.
  - *Metode Deret Waktu*: Menangkap fluktuasi musiman dan pola dalam data.
  - *Proyeksi Jangka Pendek*: Berguna untuk perencanaan selama 30 hari ke depan.

_(![image](https://github.com/user-attachments/assets/5256e06d-b335-444d-9067-a346fa4cedc2)
)_

---

### Visualisasi Data

1. **Grafik Model Regresi Linear**  
   _(![image](https://github.com/user-attachments/assets/2de90a21-9150-43ca-81dd-3995149fcc32)
)_

2. **Grafik Model Regresi Polinomial**  
   _(![image](https://github.com/user-attachments/assets/d69b8ff3-5bcd-427a-9508-6dfddfcd4518)
)_

3. **Grafik Model Forecasting**  
   _(![image](https://github.com/user-attachments/assets/5f9531c6-d05a-423f-9423-a10850541a3b)
)_

4. **Produk Paling Laris**  
   _(![image](https://github.com/user-attachments/assets/c7e8c5f1-0fcb-4e35-880d-05d7629d8bd6)
)_

5. **Penjualan Harian**  
   _(![penjualanharian](https://github.com/user-attachments/assets/7102bcaf-123b-4ed2-bb75-6015c219c752)
)_

6. **Penjualan Berdasarkan Jam**
   _(![image](https://github.com/user-attachments/assets/d60fdbc2-fbc5-4de7-af6e-38cb07543420)
)_

---

Untuk harapannya proyek analisis ini bisa membantu Warung Bakso Bakar Nyonya dengan mengidentifikasi produk terlaris dan tren penjualan. Hasilnya menunjukkan bahwa bakso bakar menyumbang 40% dari total penjualan, dengan rata-rata 150 porsi terjual pada akhir pekan. Model forecasting memprediksi peningkatan penjualan bulan depan. Informasi ini memungkinkan warung untuk mengoptimalkan stok, menyesuaikan jam operasional, dan merancang strategi pemasaran yang lebih efektif, meningkatkan efisiensi dan keuntungan.


