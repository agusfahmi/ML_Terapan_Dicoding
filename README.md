




# Laporan Proyek Machine Learning - Agus Fahmi Aji Pramana

## Domain Proyek
Di era digital saat ini, transformasi pasar tradisional telah menjadi semakin terlihat dengan penjual yang beralih ke platform digital untuk menjual produk mereka. Dalam lingkungan digital yang penuh dengan berbagai pilihan produk dan layanan, menjadi sangat penting bagi penjual untuk menarik perhatian pelanggan potensial mereka. Dalam hal ini, fitur rekomendasi memegang peranan yang krusial.

Ketersediaan produk dalam jumlah yang melimpah di platform digital seringkali membuat konsumen merasa kewalahan. Mereka mencari cara untuk menemukan produk yang sesuai dengan kebutuhan dan preferensi mereka tanpa harus menyisihkan banyak waktu untuk pencarian manual. Inilah tempat dimana sistem rekomendasi menjadi sangat berharga.

Sistem rekomendasi pada platform digital berfungsi untuk menganalisis perilaku pembeli, seperti riwayat pembelian sebelumnya, preferensi produk, dan interaksi lainnya dengan platform. Berdasarkan data ini, sistem rekomendasi dapat memberikan rekomendasi produk yang relevan kepada pengguna. Dengan cara ini, penjual dapat memanfaatkan data yang ada untuk secara efektif mempromosikan produk mereka kepada pelanggan yang mungkin berminat, meningkatkan peluang penjualan, dan memperluas basis pelanggan mereka.

Fitur rekomendasi juga membantu menciptakan pengalaman berbelanja yang lebih personal dan efisien bagi konsumen. Ketika pengguna melihat rekomendasi produk yang sesuai dengan preferensi mereka, mereka cenderung lebih puas dengan pengalaman berbelanja dan lebih mungkin untuk melakukan pembelian. Ini membantu menciptakan hubungan yang lebih kuat antara penjual dan pelanggan, yang pada gilirannya dapat meningkatkan loyalitas pelanggan dan pertumbuhan bisnis.

Dalam dunia digital yang kompetitif, penjual yang mampu menyediakan fitur rekomendasi yang efektif memiliki keunggulan yang signifikan. Dengan memanfaatkan teknologi ini, mereka dapat mengoptimalkan penjualan mereka, meningkatkan pengalaman pelanggan, dan tetap relevan di pasar yang terus berubah. Oleh karena itu, fitur rekomendasi adalah salah satu alat penting yang harus dimiliki oleh penjual dalam upaya mereka untuk sukses di pasar digital saat ini.
 - Jelaskan mengapa dan bagaimana masalah tersebut harus diselesaikan : 
Masalah yang dijelaskan di atas, yaitu pentingnya fitur rekomendasi dalam transformasi pasar tradisional ke dalam lingkungan digital, harus diselesaikan karena memiliki dampak yang signifikan pada keberhasilan bisnis dan pengalaman pelanggan. Berikut adalah beberapa alasan mengapa masalah ini harus diselesaikan: Pertama, fitur rekomendasi membantu penjual meningkatkan keunggulan bersaing dengan memungkinkan pelanggan dengan mudah menemukan produk yang sesuai dengan kebutuhan mereka, yang kritis dalam pasar yang sangat kompetitif. 
Kedua, fitur ini dapat meningkatkan penghasilan dengan meningkatkan peluang penjualan dan memungkinkan pelanggan untuk melakukan pembelian tambahan atau berulang. Ketiga, fitur rekomendasi menciptakan pengalaman berbelanja yang lebih personal dan efisien bagi pelanggan, meningkatkan kepuasan mereka dan mendorong loyalitas terhadap merek atau platform. Keempat, dengan pemahaman yang lebih baik tentang preferensi pelanggan, penjual dapat mengoptimalkan inventaris mereka, mengurangi risiko kelebihan persediaan, dan mengelola operasi bisnis dengan lebih efisien. Terakhir, ini semua berkontribusi pada pertumbuhan bisnis yang signifikan, menjaga keberlanjutan, dan memungkinkan penjual untuk tetap bersaing di era bisnis yang semakin terhubung secara digital.
  
  **Artikel dan Jurnal Referensi**:

 -   [Recommender Systems For Business - A Gentle Introduction](https://www.width.ai/post/recommender-systems-recommendation-systems)

 - [5 Advantages Recommendation Engines can Offer to Businesses](https://towardsdatascience.com/5-advantages-recommendation-engines-can-offer-to-businesses-10b663977673)

## Business Understanding
Berikut tahapan pemecahan masalah terkait klasifikasi teks emosional dapat dibagi menjadi beberapa tahap :

1. **Penentuan Tujuan Penelitian/Pemecahan Masalah:**
Bagaimana cara merekomendasikan produk yang disukai pengguna lain dapat direkomendasikan kepada pengguna lainnya juga ?
2. **Pengumpulan Data:**
   Dataset diambil dari situs open source kaggle bernama  [ Groceries dataset for Market Basket Analysis(MBA)](https://www.kaggle.com/datasets/rashikrahmanpritom/groceries-dataset-for-market-basket-analysismba). 

4. **Pemrosesan Teks:**
  Meakukan pra-pemrosesan pada data penjualan, seperti membersihkan nilai null, mengubah ke dalam bahasa indonesia, menghapus data duplicate, replace kata yang ambigu dll

5. **Pengembangan Model:**
   Pengembangan model klasifikasi menggunakan Vector . Melatih model menggunakan dataset yang telah di pre-processing

6. **Validasi dan Evaluasi Model:**
Menggunakan data validasi untuk menguji kinerja model  dengan metrik seperti akurasi .

7. **Implementasi:**
Penerapan model pada aplikasi untuk mengembangkan bisnis

**Kendala Sumber Daya dan Batasan Waktu:**
- Tersedia sumber daya manusia yang terlatih untuk annotasi data.
- Akses terhadap komputasi yang memadai untuk melatih model (GPU jika diperlukan).
- Kemampuan untuk mengakses dan mengelola data teks yang relevan.
- Batasan waktu yang harus dipertimbangkan, termasuk tenggat waktu untuk penelitian, pengumpulan data, pelatihan model, dan implementasi.

**Estimasi Waktu/Milestone:**
- Pengumpulan dan anotasi data: 1-2 bulan.
- Pemrosesan dan persiapan data: 1 bulan.
- Pengembangan dan pelatihan model: 2-3 bulan.
- Validasi dan evaluasi model: 1 bulan.
- Implementasi dan integrasi: 1-2 bulan.
- Pemantauan dan pemeliharaan berkelanjutan: Ongoing.

### Problem Statements
-   Bagaimana mengembangkan sistem rekomendasi produk yang sesuai dengan preferensi, minat atau perilaku pengguna?
-   Bagaimana hasil dan evaluasi model dalam mengembangkan sistem rekomendasi produk yang sesuai dengan preferensi, minat atau perilaku pengguna?
### Goals

-   Mengetahui cara pengembangan sistem rekomendasi produk yang sesuai dengan preferensi, minat atau perilaku pengguna.
-   Mengetahui hasil dan evaluasi model dalam mengembangkan sistem rekomendasi produk yang sesuai dengan preferensi, minat atau perilaku pengguna.

### Solution Statement 

-   Melakukan data preprocessing dan exploratory data analysis (EDA) pada dataset yang dipakai dengan melihat keterkaitan antar feature pada data tersebut untuk mendapatkan insight dan knowledge.
    
-   Mengembangkan model machine lerning yang sesuai untuk membangun sistem rekomendasi dan melakukan evaluasi model dengan menggunakan evaluation matrix. Teknik yang akan diimplementasikan untuk membangun sistem ini adalah sebagai berikut:
    
    -   Content-Based Filtering, merekomendasikan beberapa item berdasarkan kemiripan antar item yang direkomendasikan dengan item yang dipilih.
-   Menampilkan hasil rekomendasi berdasarkan model yang telah dikembangkan.
-   Melakukan evaluasi berdasarkan metriks evaluasi dari model sistem rekomendasi yang telah dikembangkan.

## Data Understanding
Untuk membangun sebuah model diperlukan data. Maka data yang diambil dari situs kaggle dengan nama [Groceries dataset for Market Basket Analysis(MBA)](https://www.kaggle.com/datasets/rashikrahmanpritom/groceries-dataset-for-market-basket-analysismba).  Groceries dataset for Market Basket Analysis(MBA)  ini merupakan kumpulan data yang digunakan untuk melatih dan menguji model-model Recommender . Berikut ini adalah gambaran umum tentang dataset ini:

**Jumlah Data:** Dataset ini terdiri dari 3898 user unik atau entri. Artinya, terdapat 38765 data transaksi dari semua user.

**Tujuan Dataset:** Dataset ini digunakan untuk melatih model Sistem Rekomendasi berbasis konten. Dengan demikian, dataset ini dapat digunakan dalam berbagai proyek Recommender system 

### Variabel-variabel pada Emotion Classification NLP dataset adalah sebagai berikut:
- Member_id : merupakan id user yang telah bertransaksi
- Tanggal : merupakan tanggal transksi
- Deskripsi_barang : Merupakan barang yang dibeli oleh user
- Kategori : Merupakan kategori barang yang dibeli

## Data Preparation
Dilihat dari sudut pandang kerunutan proses dalam data preparation, saya melakukan data cleaning pada data  `Groceries data.csv`  . setelah dirasa sudah terlihat cukup baik, saya menjadikannya sebagai dataframe yang utuh untuk mengembangkan sistem rekomendasi. Berikut langkah-langkahnya:

 
**Data Cleaning**  `Groceries data.csv`
    
   Ada beberapa handling yang dilakukan pada dataframe  `Groceries Data`, diantaranya sebagai berikut.
    
   -   Handling Missing Values
        
        Data yang hilang, null, NaN atau tidak terbaca merupakan hal umum yang seringkali ditemui. Agar data yang missing tidak memengaruhi kinerja model yang akan dikembangkan, maka saya akan menghapusnya. Pada proyek ini, saya menemukan missing values pada beberapa feature, salah satunya adalah kategori dimana terdapat data yang tidak jelas namanya.
        
    -   Data Reduction
        
        Data yang terlalu banyak akan memperlambat kinerja proses machine learning. Pada proyek ini, saya memiliki asumsi kalau terdapat beberapa dataset yang ambigu sehingga membuat model kebingunan, maka dari itu perlu preprocessing data . Saya berfikir hal ini tidak akan menjadi masalah. Karena, selain jumlah data pada datasetnya memiliki jumlah yang cukup banyak, proses reduction dapat mempercepat runtime model dengan menghemat memory.
        
    -   Handling Duplicate Data
        
        Dataset yang berantakan dan terduplikasi dapat mempengaruhi hasil modeling dan analisis akhir. Pada proyek ini, terdapat banyak duplikasi data didalamnya berdasarkan Member_id  dan Deskripsi_barang. Menghapusnya merupakan langkah yang tepat untuk merapikan data.
  - Replace to Indonesia Language
  Setelah pemrosesan data selesai, data diterjemahkan kedalam bahasa indonesia menggunakan google sheets agar dapat mudah dipahami.
        
   -   Fixed data in Kategori features
        
        Pada features kategori, saya mendapati kategori  _**Sci-Fi**_. setelah saya pahami, ternyata  _**Sci-Fi**_  merupakan akronim dari kata  _**Science Fiction**_  yang menggambarkan transaksi yang dilakukan. kata  _**Sci-Fi**_  memiliki separator dash atau tanda pisah. Hal ini, perlu dihilangkan. apabila tidak dihilangkan maka pada tahap vektorisasi TF-IDF nantinya kata  _**Sci-Fi**_  akan diperlakukan sebagai 2 kata yang berbeda  _**Sci**_  dan  _**Fi**_. karena, pada tahap TF-IDF selain melakukan vektorisasi juga dilakukan tokenisasi.

## Modeling

-   **Content-Based Filtering**
    
    Konsep dasar dari content-based filtering adalah memberikan rekomendasi item dengan memperhatikan kemiripan dari item yang disukai oleh pengguna berdasarkan aktivitas pengguna tersebut di masa lalu. Ambil contoh, mawan menyukai sering bertransaksi ayam.Maka, sistem akan merekomendasikan produk dengan kategori yang mirip seperti Daging, Telur . Pada akhirnya, semakin banyak informasi yang didapatkan dari aktivitas pengguna, semakin baik pula akurasi dari sistem rekomendasi yang dihasilkan.
    
    [![content-based](https://github.com/nurmuhimawann/MLT2-Dicoding/raw/main/images/content-based.png?raw=true)](https://github.com/nurmuhimawann/MLT2-Dicoding/blob/main/images/content-based.png?raw=true)
    
    Nah, pada proyek kali ini, saya akan menerapkan pendekatan content-based filtering untuk mengembangkan model guna membangun sistem rekomendasi produk sesuai dengan goals dari proyek ini. Ada beberapa tahapan yang saya lakukan, diantaranya sebagai berikut.
    
    1.  Prepare data
        
        Menyiapkan dataframe yang telah dibersihkan dalam tahap data preparation sebelumnya.
        
    2.  TF-IDF Vectorizer
        
        Proses term frequency-inverse document frequency (TF-IDF) diperlukan untuk menemukan representasi kata yang penting dalam kolom kategori. Pada proyek ini, proses vectorizer dilakukan dengan memanfaatkan function  [tfidfvectorizer()](https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html)  yang telah tersedia pada library scikit-learn. berikut hasil tf-idf dalam bentuk matrix. yang mana pada matrix menunjukkan korelasi antara produk dengan kategori-nya.
        
        [![tfidf](https://github.com/nurmuhimawann/MLT2-Dicoding/raw/main/images/vectorizer.png?raw=true)](https://github.com/nurmuhimawann/MLT2-Dicoding/blob/main/images/vectorizer.png?raw=true)
        
    3.  Perhitungan Cosine Similarity
        
        cosine similarity digunakan untuk menghitung derajat kesamaan (similarity degree) antar produk . Pada proyek ini, kalkulasi similarity dilakukan dengan mengimplementasikan function  [cosine_similarity()](http://scikit-learn.org/stable/modules/generated/sklearn.metrics.pairwise.cosine_similarity.html)  yang telah tersedia pada library sklearn. Perhitungan similarity merupakan tahapan paling penting dalam pendekatan content-based filtering, karena pada dasarnya pendekatan ini menerapkan prinsip kesamaan antar item untuk mendapatkan hasil rekomendasi yang sesuai. Output dari cosine similarity akan menghasilkan suatu matrix kesamaan yang bisa dilihat pada konversi ke bentuk dataframe berikut.
        
![image](https://github.com/agusfahmi/ML_Terapan_Dicoding/assets/85145157/7ea452b7-8293-4f74-901d-2d548dfaeb3a)
        
    4.  Create Custom Functions
        
        Tahapan terakhir adalah membangun custom function untuk mendapatkan rekomendasi terhadap data input yang diinginkan. functions ini bekerja dengan mengambil similarity dari data produk yang ingin dicari, data yang similar akan dimasukkan ke dalam variabel closest. parameter K di define untuk menghasilkan top-K recommendation berdasarkan tingkat similarity tertinggi. produk yang dicari akan dihapus agar tidak muncul dalam daftar rekomendasi. Step terakhir, return digunakan untuk mengembalikan values dalam bentuk dataframe, dimana values yang di return merupakan rekomendasi dari judul produk berdasarkan tingkat similarity.
        
        [![functions](https://github.com/nurmuhimawann/MLT2-Dicoding/raw/main/images/recommendation-content-based.png?raw=true)](https://github.com/nurmuhimawann/MLT2-Dicoding/blob/main/images/recommendation-content-based.png?raw=true)
        
    5.  Recommendations
        
        [![harry](https://github.com/nurmuhimawann/MLT2-Dicoding/raw/main/images/harry-potter.png?raw=true)](https://github.com/nurmuhimawann/MLT2-Dicoding/blob/main/images/harry-potter.png?raw=true)
        
        Berikut ini merupakan Top 5 Recommendations berdasarkan kategori dari produk  'Harry Potter and the Prisioner of Azkaban'. Sistem telah berhasil merekomendasikan produk dengan sesuai, bisa dilihat pada hasil yang mendapatkan rekomendasi produk yang mirip dengan kategori Adventure dan Fantasy.
        
        [![output-cb](https://github.com/nurmuhimawann/MLT2-Dicoding/raw/main/images/output-content-based.png?raw=true)](https://github.com/nurmuhimawann/MLT2-Dicoding/blob/main/images/output-content-based.png?raw=true)
        
    
    Kelebihan Content-Based Filtering
    
    -   Mampu menjelaskan bagaimana hasil rekomendasi didapatkan
    -   Kemampuan untuk merekomendasikan item yang sifatnya baru bagi pengguna bahkan belum pernah di-rate oleh siapapun, karena prinsip kerjanya yaitu dengan melihat deskripsi item yang terdapat pada item yang pernah diberi nilai rating tinggi
    
    Kekurangan Content-Based Filtering
    
    -   Terbatasnya rekomendasi hanya pada item-item yang mirip (similar) sehingga tidak ada kesempatan untuk mendapatkan item yang tidak terduga (serendipity)
        
    -   Sistem tidak dapat memberikan rekomendasi kepada pengguna baru yang belum pernah melakukan aktivitas apapun dan tidak memiliki profil user yang cukup (Cold Start Problem)

## Evaluation
Evaluasi dilakukan untuk mengukur sejauh mana performance atau kinerja dari model sistem rekomendasi. Pada proyek ini, evaluasi diukur menggunakan metriks evaluasi sesuai dengan pendekatan yang dipakai dalam pengembangan sistem rekomendasi.

-   **Content-Based Filtering**
    
    Pada pendekatan Content-Based Filtering, performance model diukur menggunakan nilai metriks precisions dengan similarity. Cosinus Similarity merupakan ukuran yang mengkuantifikasi kesamaan antara dua atau lebih vektor.
    
    [![cosine-sim](https://github.com/nurmuhimawann/MLT2-Dicoding/raw/main/images/cosine-sim-formula.png?raw=true)](https://github.com/nurmuhimawann/MLT2-Dicoding/blob/main/images/cosine-sim-formula.png?raw=true)
    
    Nilai cosinus similarity memiliki rentang yang terbatas antara 0 dan 1. ukuran kemiripan ditentukan oleh ukuran cosinus sudut antara dua vektor tak nol. Semakin besar nilai cosinus similarity semakin mendekati 1, maka sudut antara kedua vektor juga semakin kecil. Bisa dilihat pada gambar di bawah ini.
    
    [![example-cosine-sim](https://github.com/nurmuhimawann/MLT2-Dicoding/raw/main/images/example-cos-sim.png?raw=true)](https://github.com/nurmuhimawann/MLT2-Dicoding/blob/main/images/example-cos-sim.png?raw=true)
    
    Precision merupakan tingkat ketepatan antara informasi yang diminta oleh pengguna dengan hasil yang diberikan oleh sistem. Precision sangat cocok diterapkan sebagai metriks evaluasi pada sistem rekomendasi yang mana pengukuran kualitas akan ditentukan melalui seberapa bergunakah sistem dapat melakukan prediksi.
    
    [![precision](https://github.com/nurmuhimawann/MLT2-Dicoding/raw/main/images/precision.png?raw=true)](https://github.com/nurmuhimawann/MLT2-Dicoding/blob/main/images/precision.png?raw=true)
    
    Keterangan:
    
    -   **True Postive (TP):**  prediksinya  **Positif**  dan hasil yang sebenarnya memang  **Positif.**
        
    -   **False Positive (FP)**: prediksinya  **Positif**, namun hasil yang sebenarnya adalah  **Negatif.**
        
    -   **True Negative (TN):**  prediksinya  **Negatif**  dan hasil yang sebenarnya memang  **Negatif.**
        
    -   **False Negative (FN)**: prediksinya  **Negatif**, namun hasil yang sebenarnya adalah  **Positif.**
        
    
    Formula diatas merupakan rumus precision. Namun, dalam sistem rekomendasi lebih sederhana menggunakan rumus seperti gambar dibawah ini. pada dasarnya sama saja, precisions membantu pengguna memilih item yang mirip di antara set item yang tersedia.
    
    [![precision-for-recommendations](https://github.com/nurmuhimawann/MLT2-Dicoding/raw/main/images/precision-recommendations.png?raw=true)](https://github.com/nurmuhimawann/MLT2-Dicoding/blob/main/images/precision-recommendations.png?raw=true)
    
    [![harry](https://github.com/nurmuhimawann/MLT2-Dicoding/raw/main/images/harry-potter.png?raw=true)](https://github.com/nurmuhimawann/MLT2-Dicoding/blob/main/images/harry-potter.png?raw=true)
    
    Pada pendekatan content-based filtering ini, saya memakai produk 'Harry Potter and the Prisioner of Azkaban' untuk mencari rekomendasi produk lain yang sesuai. dan mendapatkan hasil sebagai berikut.
    
    [![output-cb](https://github.com/nurmuhimawann/MLT2-Dicoding/raw/main/images/output-content-based.png?raw=true)](https://github.com/nurmuhimawann/MLT2-Dicoding/blob/main/images/output-content-based.png?raw=true)
    
    Dengan memakai metrics precision, maka dapat dihitung:
    
    -   'Harry Potter and the Prisioner of Azkaban'  pada kategori Adventure, Fantasy, IMAX.
    -   Dari 5 produk rekomendasi, terdapat 3 produk yang memiliki kategori yang sama dengan yang dicari yaitu, kategori Adventure, Fantasy, IMAX. produk terakhir, merekomendasikan produk lain dengan kategori drama dan thriller. Ini tidak sesuai dengan apa yang dicari.
    
    Maka, sesuai dengan formula,
    
    _precision = (# of our recommended that are relevan) / (# of items we recommended item)_
    
    _precision = 3 / 5_
    
    _precision = 0.6_
    
    _precision = 60%_
    
    Berdasarkan Top 5 rekomendasi produk yang diberikan didapatkan pricisions sebesar 60% dari model content-based filtering untuk sistem rekomendasi yang telah dikembangkan.
    


Referensi:

[1] J. Ni, T. Young, Vlad Pandelea, F. Xue, Vinay Adiga, and Z. Wang, "Recent advances in deep learning based dialogue systems: a systematic survey," Artificial Intelligence Review, vol. 56, no. 4, pp. 3055–3155, Aug. 2022, doi: [https://doi.org/10.1007/s10462-022-10248-8](https://doi.org/10.1007/s10462-022-10248-8).
[2] P. Nandwani and R. Verma, "A review on sentiment analysis and emotion detection from text," Social Network Analysis and Mining, vol. 11, no. 1, Aug. 2021, doi: [https://doi.org/10.1007/s13278-021-00776-6](https://doi.org/10.1007/s13278-021-00776-6).
[3] S. Akhtar, Deepanway Ghosal, Asif Ekbal, P. Bhattacharyya, and Sadao Kurohashi, "All-in-One: Emotion, Sentiment and Intensity Prediction Using a Multi-Task Ensemble Framework," IEEE Transactions on Affective Computing, vol. 13, no. 1, pp. 285–297, Jan. 2022, doi: [https://doi.org/10.1109/taffc.2019.2926724](https://doi.org/10.1109/taffc.2019.2926724).
[4] Priya Chakriswaran, Durai Raj Vincent, K. Srinivasan, V. Sharma, C.-Y. Chang, and D. G. Reina, "Emotion AI-Driven Sentiment Analysis: A Survey, Future Research Directions, and Open Issues," Applied Sciences, vol. 9, no. 24, pp. 5462–5462, Dec. 2019, doi: [https://doi.org/10.3390/app9245462](https://doi.org/10.3390/app9245462).
[5] M. S. Akhtar, D. S. Chauhan, D. Ghosal, S. Poria, A. Ekbal, and P. Bhattacharyya, "Multi-task Learning for Multi-modal Emotion Recognition and Sentiment Analysis," arXiv.org, 2019. [https://arxiv.org/abs/1905.05812](https://arxiv.org/abs/1905.05812) (accessed Sep. 09, 2023).

