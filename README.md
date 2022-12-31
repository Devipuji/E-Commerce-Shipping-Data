# E-Commerce Shipping Data

Data source : https://www.kaggle.com/prachi13/customer-analytics

## Kelompok 3 : "Asklepios"
#### Anggota : 
- Awalsyah Rinanto Putra
- Fathah Oscar
- M Rizky Septiansyah
- Hermawan Febrianto
- Devi Puji Ayuningsih
- Anggita Citanegara Lubis
    

## **Project Overview** 
• Mencari insight dari dataset dengan Exploratory Data Analysis (EDA) <br>
• Melakukan data cleansing, data processing, data engineering untuk menyiapkan data sebelum modeling (Pre-Processing) <br>
• Dari beberapa feature yang ada, mencoba untuk membuat model prediksi apakah shipping deliveries akan diterima telat atau tepat waktu pada customers <br>
• Memberikan analisis rekomendasi/solusi dan keuntungan apa saja yang bisa diperoleh jika performa model yang kita bangun memuaskan. 


## Business Background
Asklepios sebagai perusahaan data science consultant independen, di-hire untuk mengolah suatu dataset shipment. Kami diminta untuk mencari solusi bagaimana cara mengatasi permasalahan yang mereka punya melalui dataset tersebut.


## Problem Statement
E-Commerce Shipping Dataset menunjukan bahwa dari 10.999 sampel transaksi pembelian online, 59.74% transaksi diantaranya masih mengalami keterlambatan waktu pengiriman barang. Sementara, ketepatan waktu pengiriman berpengaruh sebesar 50.1% terhadap customer satisfaction. Customer akan mendapatkan experience yang kurang baik dalam menggunakan layanan E-Commerce dari company tersebut. Selain itu, keterlambatan ini juga menyebabkan company mengalami potential revenue loss dari sisi finansial dan operasional project. Pada sisi finansial, keterlambatan ini menimbulkan lead time pada saat penagihan invoice. Sedangkan pada sisi operasional project, keterlambatan membuat project tidak berjalan lancar dan memperlambat waktu proses sehingga menimbulkan biaya sewa gudang yang lebih besar. (Siburian dan Kartika, 2021)


## Descriptive Statistics
A. Tidak ada data yang memiliki duplicated value <br>
B. Tidak ada kolom yang memiliki missing value <br>
C. Terdapat 10 feature yang merupakan 5 feature numericals dan 5 feature categoricals


## Univariate Analysis
![kde 1](https://user-images.githubusercontent.com/116422996/210133577-f0da2fb1-da6e-454d-bfd6-93d5002fb1a4.jpg)
![barplot 1](https://user-images.githubusercontent.com/116422996/210133579-2e25b7c8-0f9b-413a-9d08-d7d3e661c336.jpg)


## Multivariate Analysis
![heatmap](https://user-images.githubusercontent.com/116422996/198685212-05e9cebb-2b61-4105-99de-bff76598b4cf.jpg)


## Data Pre-Processing
![image](https://user-images.githubusercontent.com/116422996/210133044-359c2c23-8895-4767-a384-0cbc285c840c.png)


## Business Insight and Recommendation
![Screenshot (33)](https://user-images.githubusercontent.com/116422996/210133628-d1dd783f-4eaf-4c9b-b292-ff76d04dc3c7.png)

- Untuk pembelian produk dengan discount diatas 10% banyak mengalami keterlambatan pengiriman. <br>
Dalam hal ini pihak e-commerce perlu memberikan notifikasi keterlambatan pengiriman kepada customer ketika melakukan pembelian dengan menggunakan discount yang besar yang memungkinkan produk yang dipesan tidak terkirim tepat waktu.
- Barang dengan berat 2-4 Kg terkonfirmasi mengalami keterlambatan pengiriman. <br>
Dalam hal ini, pihak e-commerce perlu memberikan notifikasi keterlambatan pengiriman kepada customer yang membeli produk di rentang berat produk 2-4 kg sebelum customer melakukan transaksi.
