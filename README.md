# **0. GENERAL DATA INFORMATION**

Student Name: Salsabila Tantri Ayu.
Berikut adalah high level dari apa yang telah kerjakan Pada Chapstone Project II - Data Analysis. Pembahasan saya mulai dari : 
* Pembahasan General mengenai database
* SQL
* Data Manipulation
* Data Insight (Statistics & Data Visualization)

Untuk detail setiap bagiannya dapat melihat informasi dibawah ini. 

Bila ada masukan megenai project ini atau hal hal yang sekiranya ingin disampaikan dapat menghubungi saya di email sebagai berikut: salsabila.ta@outlook.com

Terima kasih

# **1. GENERAL DATA INFORMATION**

## **1.1 CONTEXT**

Database ini menjelaskan mengenai perusahaan fiktif bernama "Northwind Traders". Perusahaan ini bergerak di bidang export dan import "speciality food" dari seluruh dunia. Perusahaan ingin mengetahui gambaran umum tentang bisnis yang sedang mereka jalankan. Apakah ada hal hal yang bisa diimprove dari data yang tersedia? Dari insight yang dihasilkan diharapkan bisa membantu perusahaan dalam menentukan langkah strategis untuk mengembangkan perusahaan dan lain sebagainya.
<br>

**Fokus Analisis : Suppliers**

## **1.2 DATABASE INFORMATION**

Pada bagian ini saya memberikan penjelasan mengenai data data setiap tabel pada database Northwind


# **2. SQL - Database**
**THE OBJECTIVES**
* SQL TO PYTHON CONNECTION
* USING CTE OR OTHER WINDOW FUNCTION (IF NEEDED)
* BUILT – IN FUNCTION AS NEEDED

## **2.1 CONNECTING TO DATABASE**
Membuat koneksi dari SQL ke Python agar bisa melakukan query di Jupyter Notebook
<br>

## **2.2 Data Detail**
Saya menjabarkan isi dari tabel tabel yang akan saya gunakan, dan saya memilih beberapa kolom dari tabel tersebut.
<br>

## **2.3 TABLE CREATION - Tabel 1**
Gambaran tabel tabel yang akan saya gabungkan untuk saya jadikan sebuah dataframe. Pada bagian ini saya memanfaatkan fitur built in SQL seperti LEFT JOIN.

## **2.4 TABLE CREATION - Tabel 2**
Disini saya menggunakan built in feature dari SQL yaitu group, having, order dan left join untuk melihat kategori produk, dan asal negara supplier beserta total supplier di negara tersebut dan juga harga rata rata per produknya.

## **2.5 TABLE CREATION - Tabel 3**
Disini saya menggunakan built in feature dari SQL yaitu group, order dan left join untuk melihat negara dengan supplier terbanyak.



# **3. DATA MANIPULATION**
**THE OBJECTIVES**
* ANY ANOMALIES ? (MISSING VALUE, OUTLIER, DATA FORMATTING, DOUBLE DATA? 
* HOW TO DEAL WITH THE ANOMALIES? 
* IF THERE’S NO ANOMALIES, PROVE IT 
<br>

## **3.1 GENERAL INFORMATION FOR DATA**
Mengetahui informasi umum data dengan .info
<br>

## **3.2 CHANGING DATA TYPE, MISSING VALUE & ANOMALY**
* Mengubah tipe data menjadi tipe data yang sesuai dengan datanya. 
* Mengecek missing value
<br>

## **3.3 ADD NEW FEATURE & DIVE IN EACH FEATURES**
Dibantu dengan 2 buah features```quantity``` dan ```unitinstock```. Saya menambahkan feature baru yang menunjukan jumlah yang harus segera diorder.

Di bagian ini juga saya mengecek banyaknya data outliers.

## **3.4 BUILT-IN FUNCTION PANDAS TO GET INSIGHT**
Disini saya menampilkan beberapa dataframe menggunakan built-in function pandas untuk mendapatkan gambaran, dan mengambil insight.

<br>

# **4. DATA INSIGHT (DATA VISUALIZATION, STATISTICS)**
**THE OBJECTIVES**
<br>
DATA VISUALIZATION
* DATA VISUALIZATION USING PYTHON & TABLEAU
* INSIGHT / STORY / ANY INFORMATION TO EXPLAIN THE GRAPH TO SOLVE THE PROBLEM



## 4.1 **Negara Penyumbang Supplier**
##  **Analysis 1: Negara Asal Supplier**
<br>
##  **Analysis 2: Kuantitas Barang Yang Diorder Per Negara Per Kategori**
<br>
##  **Analysis 3: Rata-Rata Harga Satuan Per Negara Per Kategori**
<br>

## 4.2 **Produk Yang Harus Reorder**
## **Analysis 1: List Produk Yang Harus Seger Reorder**
<br>

## 4.3 Total Sales Per Kategori
<br>
## **Analysis 1: Total Sales Per Kategori**
<br>
## **Analysis 2: Total Sales Perkategori & Dibandingkan Dengan Harga Satuan Serta Tingkat Reorder**
<br>
## **Analysis 3: Korelasi Antara Harga Satuan Dengan Reorderlevel**

## 4.4 **Jumlah Order Sepanjang Waktu**


STATISTICS
* COMPARING VALUE / PROPORTION WITH SUITABLE METHOD
* RELATIONSHIP BETWEEN VARIABELS 
* INSIGHT FROM DESCRIPTIVE STATISTIC TEST & INFERENTIAL STATISTIC TO SOLVE THE PROBLEM
<br>

## **4.5 Uji Perbandingan Nilai Rata Rata Orderan Tiap Kategori**
## **Analysis 1: Normality Asessment**
## **Analysis 2: Kolmogorov Smirnov**
## **Analysis 3: Kruskal-Wall Test**
