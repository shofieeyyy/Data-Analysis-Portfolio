# Shofiyatul Fajriyah - Data Analyst Portfolio

## About
Hi, saya Shofiyatul Fajriyah! Saya seorang Data Analyst dengan minat besar dalam mengolah data mentah menjadi insight bisnis yang dapat ditindaklanjuti. Saya senang menggunakan tools seperti Microsoft Excel untuk melakukan data cleaning, exploratory data analysis (EDA), pivot table, hingga membangun interactive dashboard, serta Python untuk analisis data yang lebih mendalam dan fleksibel guna mendukung pengambilan keputusan berbasis data (data-driven decision making).

Repository ini dibuat untuk menampilkan skill, membagikan proyek, dan mendokumentasikan progres saya di bidang Data Analytics / Data Science.

## Table of Contents
- [About](#about)
- [Portfolio Projects](#portfolio-projects)
  - [Sales Performance Analysis - Superstore](#sales-performance-analysis---superstore)
  - [Dashboard Penjualan - Superstore (Power BI)](#dashboard-penjualan---superstore-power-bi)
  - [Analisis Data Netflix (Python)](#analisis-data-netflix-python)
- [Tools & Skills](#tools--skills)
- [Contact](#contact)

## Portfolio Projects

### Sales Performance Analysis - Superstore

**Role:** Data Analyst (Portfolio Project)

**Tools:** Microsoft Excel (Data Cleaning, Pivot Table, Pivot Chart, Dashboard, Slicer)

**Goal:** Mengevaluasi performa penjualan perusahaan Superstore, mengidentifikasi produk dan wilayah yang memberikan kontribusi terbesar terhadap profit, serta memberikan rekomendasi bisnis berbasis data.

**Description:** Superstore merupakan perusahaan ritel yang menjual berbagai kategori produk kepada pelanggan di berbagai wilayah di Amerika Serikat. Dataset yang digunakan adalah Sample Superstore Sales dengan total 9.994 transaksi. Analisis dilakukan melalui tahapan Data Cleaning (memeriksa missing value, duplikat, tipe data numerik, outlier, dan konsistensi penulisan), Exploratory Data Analysis (EDA), Pivot Table, hingga pembuatan Interactive Dashboard.

**Skills:** Data cleaning, exploratory data analysis, pivot table, dashboard building, business insight reporting.

**Key Results:**
- Total penjualan: **$2.296.195,59**
- Total profit: **$286.241,42**
- Unit terjual: **37.820 unit**
- Profit margin: **12%**

**Business Insights:**
- **Category Performance:** Kategori Technology menyumbang 36,4% dari total profit perusahaan. Furniture memiliki penjualan tinggi namun profit sangat rendah, sedangkan Office Supplies menghasilkan profit tinggi meski penjualannya lebih rendah dibanding Furniture.
- **Sub-Category Performance:** Produk Copiers menjadi penyumbang profit terbesar, sementara Tables menghasilkan kerugian terbesar.
- **Regional Performance:** Region West memberikan kontribusi terbesar terhadap penjualan maupun profit, sedangkan Region South memiliki penjualan paling rendah.
- **Customer Segment:** Segmen Consumer merupakan kontributor utama terhadap penjualan dan profit perusahaan.

**Strategic Recommendations:**
1. Fokus meningkatkan investasi pada kategori Technology karena memiliki kombinasi penjualan dan profit terbaik.
2. Evaluasi kategori Furniture, khususnya subkategori Tables dan Bookcase, dengan meninjau kembali strategi diskon, harga jual, dan biaya distribusi.
3. Pertahankan performa Region West sebagai acuan praktik terbaik, sekaligus kembangkan strategi pemasaran untuk Region South.
4. Perluas promosi untuk produk Copiers, Phones, dan Accessories karena terbukti menghasilkan profit tinggi.
5. Lakukan evaluasi terhadap produk dengan profit negatif; pertimbangkan pengurangan stok atau penghentian penjualan jika perbaikan tidak signifikan.

**Business Impact:** Melalui analisis ini, manajemen Superstore dapat mengidentifikasi kategori produk paling menguntungkan, mengetahui wilayah dengan performa terbaik dan terendah, mengoptimalkan strategi penjualan berdasarkan profit (bukan hanya volume), mengurangi kerugian dari subkategori dengan profit negatif, dan mendukung pengambilan keputusan berbasis data.

**Conclusion:** Superstore menunjukkan performa bisnis yang positif dengan total penjualan mencapai $2,29 juta dan total profit sebesar $286 ribu. Kategori Technology, Region West, dan segmen Consumer menjadi kontributor utama keberhasilan perusahaan. Namun, kategori Furniture — khususnya subkategori Table dan Bookcase — menghasilkan profit rendah bahkan negatif, menunjukkan bahwa peningkatan penjualan saja tidak cukup; profitabilitas setiap kategori produk perlu menjadi fokus utama.

---

### Dashboard Penjualan - Superstore (Power BI)

**Role:** Data Analyst (Portfolio Project)

**Tools:** Power BI

**Goal:** Membangun dashboard interaktif untuk memvisualisasikan performa penjualan Superstore, memudahkan monitoring KPI utama seperti total sales, profit, dan tren penjualan berdasarkan kategori, wilayah, dan segmen pelanggan.

**Description:** Proyek ini merupakan pengembangan dari analisis Sales Performance Superstore, kali ini diimplementasikan dalam bentuk dashboard Power BI yang interaktif. Dashboard memungkinkan eksplorasi data secara dinamis melalui filter dan visualisasi yang saling terhubung, sehingga insight bisnis dapat diakses dengan lebih cepat dan intuitif dibandingkan laporan statis.

**Dashboard Overview:**
- **KPI Cards:** Total Sales (2.30M), Total Profit (286.24K), Total Quantity (38K)
- **Slicers:** Region, Segment, Category
- **Sales by Category:** Bar chart perbandingan penjualan antar kategori (Technology, Furniture, Office Supplies)
- **Profit by Category:** Bar chart perbandingan profit antar kategori
- **Sales by Region:** Bar chart penjualan berdasarkan wilayah (West, East, Central, South)
- **Sales by Segment:** Donut chart proporsi penjualan berdasarkan segmen (Consumer, Corporate, Home Office)
- **Sum of Sales by State:** Peta interaktif sebaran penjualan di seluruh negara bagian Amerika Serikat

**File:** [`Dashboard_Superstore.pbix`](./Dashboard_Superstore.pbix)

**Skills:** Data modeling, DAX, interactive visualization, dashboard design, business reporting.

---

### Analisis Data Netflix (Python)

**Role:** Data Analyst (Portfolio Project)

**Tools:** Python (Pandas, Matplotlib, Seaborn), Google Colab

**Goal:** Menggali insight dari katalog konten Netflix, meliputi komposisi tipe konten, tren pertumbuhan konten, distribusi negara produksi, rating, genre, dan durasi film, sebagai dasar rekomendasi strategi konten.

**Description:** Analisis ini menggunakan dataset Netflix Movies and TV Shows yang berisi 8.807 judul dengan berbagai atribut seperti tipe, sutradara, pemeran, negara, tanggal ditambahkan, rating, durasi, dan genre. Proses analisis meliputi Data Cleaning (penanganan missing value pada kolom director/cast/country, konversi tipe data tanggal, serta pemisahan kolom durasi untuk Movie dan TV Show), Exploratory Data Analysis (EDA), hingga visualisasi data menggunakan Matplotlib dan Seaborn.

**Skills:** Data cleaning dengan Python, exploratory data analysis, data visualization, business insight generation.

**Key Findings:**
- Movie mendominasi katalog Netflix dibandingkan TV Show.
- Jumlah konten yang ditambahkan meningkat pesat menjelang periode 2019–2020.
- Amerika Serikat merupakan kontributor konten terbesar, diikuti oleh India dan Inggris.
- **TV-MA** adalah rating paling umum, menunjukkan Netflix banyak menyasar audiens dewasa.
- Drama Internasional dan Komedi menjadi genre yang paling sering muncul.
- Rata-rata durasi film menunjukkan tren **menurun** sejak tahun 2000-an, dari sekitar 120 menit menjadi sekitar 95 menit pada 2021, mengindikasikan pergeseran preferensi ke format film yang lebih ringkas.

**Business Impact:** Insight dari analisis ini dapat digunakan untuk memahami preferensi konten audiens Netflix, mengevaluasi strategi produksi berdasarkan negara dan genre, serta memberikan gambaran arah tren durasi konten yang relevan dengan kebiasaan menonton digital saat ini.

**Repository:** [`netflix-data-analysis`](./netflix-data-analysis)

**File:** [`netflix_data_analysis.ipynb`](./netflix-data-analysis/netflix_data_analysis.ipynb)

---

## Tools & Skills
- **Microsoft Excel:** Data Cleaning, Pivot Table, Pivot Chart, Interactive Dashboard, Slicer
- **Power BI:** Data Modeling, DAX, Interactive Dashboard
- **Python:** Pandas, Matplotlib, Seaborn, Google Colab
- **Analytical Skills:** Exploratory Data Analysis (EDA), KPI reporting, business insight generation, data-driven recommendation

## Contact
- LinkedIn: [@shofiyatulfajriyah](https://www.linkedin.com/in/shofiyatulfajriyah/)
- Email: fajriyah144@gmail.com
