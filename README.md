# Wrangling and Viz: E-Commerce Data
---
Repository ini berisi file-file yang merupakan bagian dari proses data wrangling, visualisasi, dan analisis suatu dataset E-Commerce.


## Objektif Analisis
Beberapa tujuan yang ingin dicapai dari terkait proses dan analisis antara lain:

1. Bagaimana popularitas kategori produk yang dipesan?
2. Bagaimana potensi kehilangan pendapatan (revenue loss) dari produk yang dipesan?
3. Bagaimana trend pendapatan (revenue) tiap kategori produk selama satu tahun terakhir?
4. Bagaimana trend jumlah produk yang berhasil dikirim ke customer selama setahun terakhir?
5. Bagaimana trend total pendapatan (revenue) perusahaan selama setahun terakhir?

## Data
Data yang digunakan adalah database "olist" yang berisi sembilan tabel data. Pada proses analisis ini hanya digunakan empat tabel data yang relevan untuk menjawab objektif, yaitu tabel data order, order items, products, dan product category name translation.

## Hasil Analisis
### 1. Bagaimana popularitas kategori produk yang dipesan?
Hasil analisis terkait objektif pertama menunjukkan bahwa lima kategori produk yang paling banyak dipesan yaitu produk kategori bed_bath_table, health_beauty, sport_leisure, computers_accessories, dan furniture_decor. Selain itu, adapun lima kategori produk yang paling sedikit dipesan yaitu produk kategori security_and_services, fashion_childrens_clothes, pc_gamer, cds_dvds_musicals, dan  la_cuisine.

Strategi atau keputusan bisnis yang dapat diambil berdasarkan hasil analisis tersebut yaitu:

- Mengadakan campaign-campaign bertema atau berkaitan dengan produk-produk paling banyak dipesan hingga terbentuk branding yang kuat sebagai perusahaan e-commerce  yang paling dapat diandalkan dan dipercaya jika customer ingin membeli kategori-kategori produk populer tersebut.
- Membuat program promosi berupa bundling produk yang sering dipesan dengan produk yang jarang dipesan

### 2. Bagaimana potensi kehilangan pendapatan (revenue loss) tiap produk yang dipesan?
Pada objektif kedua, analisis difokuskan pada data pemesanan (order) yang berstatus batal (cancel) dan tidak tersedia (unavailable) karena kedua status order menandakan bahwa transaksi pemesanan tidak terjadi dan perusahaan menjadi kehilangan potensi pendapatan. Hasil analisis terkait objektif kedua menunjukkan bahwa lima kategori produk yang paling banyak membuat perusahaan kehilangan potensi pendapatan yaitu produk kategori cool_stuff, sport_leisure, computers_accessories, watches_gifts, dan auto.

Strategi atau keputusan bisnis yang dapat diambil berdasarkan hasil analisis tersebut yaitu:

- Perusahaan mengadakan survey ke customer yang pernah membatalkan pesanan untuk mendapatkan informasi lebih banyak terkait alasan atau *pain points* customer hingga mengambil keputusan untuk membatalkan pesanan

### 3. Bagaimana trend total pendapatan (revenue) tiap kategori produk selama satu tahun terakhir?
Pada objektif ketiga, analisis difokuskan pada pendapatan (revenue) perusahaan dari pemesanan yang sudah berhasil diterima customer atau berstatus "delivered". Pendapatan dihitung berdasarkan hasil penjumlahan antara harga (price) dan biaya pengiriman (freight_value) tiap produk.

Hasil analisis menunjukkan bahwa lima kategori produk yang menghasilkan pendapatan terbanyak untuk perusahaan selama satu tahun terakhir yaitu kategori produk health_beauty, watches_gifts, bed_bath_table, sport_leisure, dan computers_accessories. Adapun trend total pendapatan dari kelima kategori tersebut selama setahun terakhir termasuk naik-turun setiap bulannya. Grafik trend menunjukan bahwa total pendapatan tiap kategori produk kompak mengalami penutunan yang signifikan pada periode bulan Desember 2017. Adapun kategori produk yang paling konsisten trend peningkatan total pendapatannya selama setahun terakhir adalah kategori health_beauty.

Strategi atau keputusan bisnis yang dapat diambil berdasarkan hasil analisis tersebut yaitu:

- Perusahaan melakukan investigasi lebih komprehensif untuk mendapatkan informasi lebih banyak terkait penyebab penurunan total pendapatan kelima kategori produk tersebut pada periode bulan Desember 2017.
- Memberi perhatian dan treatment khusus terhadap kelima kategori produk tersebut pada campaign bulan selanjutnya agar total pendapatan dari kelima kategori produk tersebut naik, terutama produk health_beauty yang trendnya cenderung selalu naik

### 4. Bagaimana trend jumlah produk yang berhasil dikirim ke customer selama setahun terakhir?
Pada objektif keempat, analisis berfokus pada jumlah produk yang berhasil dikirim ke customer selama setahun terakhir. Hasil analisis menunjukkan bahwa terdapat kenaikan signfikan jumlah produk yang berhasil dikirim pada periode bulan November 2017 namun kembali turun cukup signifikan pada periode bulan selanjutnya yaitu Desember 2017. Perusahaan dapat melakukan investigasi lebih komprehensif untuk mendapatkan penyebab kondisi tersebut.

### 5. Bagaimana trend total pendapatan (revenue) perusahaan selama setahun terakhir?
Pada objektif kelima, analisis berfokus pada total pendapatan (revenue) perusahaan yang diperoleh dari produk yang berhasil dikirim ke customer selama setahun terakhir. Mirip hasil analisis keempat sebelumnya, ada kenaikan signifikan total pendapatan pada periode bulan November 2017 namun kembali turun cukup signifikan pada periode bulan selanjutnya yaitu Desember 2017. Perusahaan dapat melakukan investigasi lebih komprehensif untuk mendapatkan penyebab kondisi tersebut.

Terdapat gambaran yang menarik ketika hasil analisis objektif keempat dan kelima dibandingkan satu sama lain, yaitu banyaknya produk yang berhasil dikirim pada bulan September 2017 mengalami penurunan dibandingkan bulan sebelumnya dan hal yang sama juga terjadi pada bulan April 2018, namun total pendapatan dari produk yang berhasil dikirim pada bulan September 2017 dan April 2018 justru mengalami kenaikan dibandingkan total pendapatan bulan sebelumnya. Hal itu kemungkinan terjadi karena pada bulan September 2017 dan April 2018 customer melakukan pembelian produk-produk bernilai revenue lebih besar walaupun secara jumlah produk yang dibeli lebih sedikit dibandingkan bulan sebelumnya.
