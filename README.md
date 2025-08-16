# CAPSTONE_BUNGARAN-PAKPAHAN
Capstone Projek dengan judul Dampak COVID-19 terhadap Mobilitas Masyarakat

# Judul Proyek

Analisis Dampak COVID-19 terhadap Mobilitas Masyarakat Menggunakan Data Publik dan Model AI

# Tujuan Proyek

Tujuan dari proyek ini adalah untuk menganalisis perubahan perilaku mobilitas masyarakat selama pandemi COVID-19, dengan fokus pada sektor-sektor utama seperti tempat kerja, area perbelanjaan, taman, stasiun transit, dan area residensial. Dengan menggunakan data mobilitas publik dari Google dan alat bantu AI seperti Prophet dan IBM Granite AI, proyek ini bertujuan untuk:

Mengidentifikasi tren mobilitas dari awal pandemi (Februari 2020) hingga pasca-pandemi (Desember 2023).
Menggali insight dan pola perubahan perilaku masyarakat akibat kebijakan pembatasan sosial dan transisi ke new normal.
Melakukan prediksi mobilitas di masa depan sebagai bahan pertimbangan perencanaan kebijakan dan strategi sektor publik.

# Data berupa .csv
Global_Mobility_Report.csv

# Insight & findings

**1. Dampak Langsung Pandemi terhadap Semua Jenis Mobilitas**
Temuan:
Semua kategori mobilitas mengalami penurunan drastis mulai Maret 2020, bersamaan dengan penerapan lockdown global.
Penurunan paling tajam terjadi pada:
Transit Stations: hingga -80%
Retail & Recreation: hingga -70%
Workplaces: -60% s.d. -70% di awal pandemi
Sebaliknya, mobilitas Residential meningkat secara signifikan (+20% hingga +30%) karena masyarakat lebih banyak tinggal di rumah.

Insight:
Mobilitas masyarakat sangat responsif terhadap kebijakan pembatasan sosial dan keadaan darurat, terutama pada awal pandemi. Pergeseran signifikan dari ruang publik ke aktivitas domestik terlihat nyata.

**2. Perbedaan Pola Pemulihan Antar Negara**
Temuan:
USA dan Italy mulai mengalami pemulihan mobilitas lebih cepat (akhir 2020 – awal 2021), terutama pada sektor rekreasi dan retail.
Indonesia dan India cenderung pulih lebih lambat dan tidak konsisten.
Italy menunjukkan pola siklus naik-turun seiring gelombang pandemi kedua dan ketiga.
Insight:
Tingkat vaksinasi, kedisiplinan masyarakat, serta kesiapan infrastruktur digital mempengaruhi kecepatan pemulihan mobilitas. Negara dengan strategi mitigasi dan vaksinasi yang cepat pulih lebih stabil.

**3. Perubahan Jangka Panjang dalam Pola Kerja**
Temuan:
Mobilitas ke tempat kerja (Workplaces) belum kembali ke baseline bahkan di akhir 2023.
Rata-rata mobilitas sektor ini tetap di bawah -10% hingga -20% di banyak negara.
Sektor Residential tidak kembali ke level normal pra-pandemi.
Insight:
Sistem kerja hybrid dan remote yang diadopsi selama pandemi kemungkinan menjadi norma baru. Banyak perusahaan tetap mempertahankan fleksibilitas kerja karena efisiensi biaya dan preferensi karyawan.


# AI support explanation
Google Colab (Python)
Pandas dan Matplotlib / Seaborn untuk eksplorasi dan visualisasi data
Prophet (Facebook) untuk prediksi deret waktu (time series)
IBM Granite AI untuk interpretasi otomatis insight dan rekomendasi berbasis AI generatif (simulasi naratif)
