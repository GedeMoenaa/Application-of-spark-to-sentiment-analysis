# **Penerapan Spark dengan Menggunakan Metode Naive Bayes Pada Analisis Sentimen Tingkat Kepuasan Pengguna Aplikasi Go-jek Berdasarkan Rating dan Review yang diberikan pengguna Pada Google Play Store**

### **Mengapa Menggunakan Spark Pada Proses Pengolahan Data?**
Pada dasarnya Apache Spark merupakan sebuah framework atau environtment yang dapat digunakan untuk mengakses data dari berbagai sumber berbeda, kemudian mengolah data tersebut, kemudian menyimpannya kedalam penyimpanan data untuk dianalisis, biasanya spark digunakan untuk melakukan analisis data berskala besar (Big Data).Apache Spark melakukan pemrosesan data melalui in-memory, sehingga waktu pemrosesan lebih cepat daripada framework sejenis seperti MapReduce dan lainnya.

### **Model Pemrosesan Data yang Digunakan**
Pada Project ini Menerapkan Batch Processing Data, dimana proses Batch merupakan sebuah metode untuk melakukan pengumpulan data dalam jumlah besar dan memprosesnya dalam satu waktu. Dimana pada Project Ini data dikumpulkan dengan melakukan web scraper dengan menggunakan modul 
```python
pip install google-play-scraper
```
yang tersedia pada jupyter notebook/python kemudian data yang didapatkan akan dikumpulkan terlebih dahulu dan dibagi menjadi beberapa batch, kemudian dilakukan pemrosesan secara bersamaan

### **Preprocessing Data**

Sebelum melakukan prosessing dari batch-batch data yang dikumpulkan, langkah pertama adalah melakukan preprocessing data pada tiap-tiap batch, dimana preprocessing data pada tiap-tiap batch meliputi:
- pengahpusan nilai kosong/Missing value
- penghapusan duplikasi data
- serta melakukan transformasi/filtering data.

### **Processing Data**

- Labelling 
- Case Folding
- Tokenizer
- Stop word removal
- Count vectorizer
- Pipeline dan transformser
- TF-IDF

### **Modelling with Naive Bayes**
- Split Data
- fit model pipeline pada data train
- menghitung akurasi model
- menampilkan confusion matriks akurasi

### **Validasi Model with K-fold cross Validation**
- Menantukan k untuk validasi silang pada model latih model
- tampilkan confunsion matriks

### **Visualisasi Sentimen Positif dan Negatif dengan menggunakan Wordcloud**




