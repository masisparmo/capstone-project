# capstone-project
Capstone Project oleh **ISPARMO** untuk HACKTIV8 - Student Development Initiative wave 3 (Juni 2025)

Data Classification and Summarization Using IBM Granite

\[ONLINE\] Data Batch 5

**Analisis Data Historis Banjir di Jakarta (2008-2025) Menggunakan Python dan AI (IBM Granite) Untuk Memberikan Rekomendasi Mitigasi Kepada Pemerintah Daerah Propinsi Jakarta**

**Project Overview**

Banjir merupakan salah satu bencana hidrometeorologi yang secara konsisten melanda DKI Jakarta hampir setiap tahun dan telah menjadi isu krusial yang berdampak luas terhadap berbagai sektor kehidupan. Proyek ini bertujuan untuk menganalisis data historis kejadian banjir di DKI Jakarta dari periode 2008 hingga 2025 untuk mengidentifikasi pola dan tren utama bencana banjir (kapan dan di mana), menyajikan wawasan (insight) yang mendalam, dan memberikan rekomendasi strategis yang konkret dan bisa ditindaklanjuti (actionable) kepada Pemerintah Provinsi DKI Jakarta. 
Pendekatan proyek ini adalah analisis kuantitatif menggunakan Python (Pandas, Matplotlib, Seaborn) dan diperkaya dengan wawasan dari AI melalui Large Language Model (LLM) IBM Granite untuk menerjemahkan data menjadi rekomendasi kebijakan yang solid.

**Raw Dataset**

Link Dataset yang digunakan dalam analisis ini adalah data historis kejadian banjir di Jakarta dari tahun 2008 hingga 2025 yang telah dibersihkan.

Data ini bersumber dari portal data publik Badan Nasional Penanggulangan Bencana (BNPB). Tautan ke Dataset: [https://dibi.bnpb.go.id/superset/dashboard/2/](https://dibi.bnpb.go.id/superset/dashboard/2/) 

Notebook Analisis: https://colab.research.google.com/drive/1RuBahifUv_ETdrYcit4tUd12r3qBtuDG?usp=sharing

**Insight & Findings**

Analisis data menghasilkan 3 temuan kunci yang saling berkaitan:

1.  Tren Tahunan Fluktuatif dengan Puncak Ekstrem pada 2020 Jumlah kejadian banjir sangat bervariasi setiap tahun, dengan puncak tertinggi terjadi pada tahun 2020 (59 insiden). Ini menandakan adanya faktor pemicu eksternal selain musim, seperti anomali cuaca (La Niña).
    
2.  Pola Musiman yang Jelas: Puncak di Bulan Februari Secara konsisten, puncak kejadian banjir terjadi pada bulan Februari (84 kejadian akumulatif), sejalan dengan puncak musim penghujan. Ini memberikan jendela waktu yang spesifik untuk meningkatkan kesiapsiagaan.
    
3.  Episentrum Banjir: Jakarta Timur & Jakarta Selatan Analisis spasial menunjukkan Jakarta Timur (130 kejadian) dan Jakarta Selatan (108 kejadian) adalah dua wilayah yang paling rentan dan sering terdampak banjir. Ini menjadi area prioritas untuk intervensi.
    

**AI Support Explanation**

Dalam proyek ini, Artificial Intelligence (AI) dalam bentuk LLM IBM Granite memainkan peran krusial sebagai akselerator wawasan dan konsultan kebijakan virtual. AI tidak menggantikan analisis data fundamental, melainkan memperkaya dan mempertajam hasilnya dengan cara:

Menyusun Informasi: Merangkai data kuantitatif menjadi narasi analisis yang logis.

Hipotesis Penyebab: Membantu mengidentifikasi akar masalah yang lebih dalam berdasarkan pola data.

Memberikan Rekomendasi: Mengklasifikasikan saran menjadi kategori jangka pendek, menengah, dan panjang, sehingga lebih mudah untuk dieksekusi oleh pemangku kebijakan. AI berfungsi sebagai jembatan antara data mentah dan kebijakan strategis yang bisa ditindaklanjuti.

(laporan lengkap ada di file pdf di dalam repo ini, atau download di: [https://github.com/masisparmo/capstone-project/blob/main/Laporan%20Capstone%20Project%20-%20Hacktiv8%20-%20Data%20Batch%205%20Jun%202025.pdf] )
