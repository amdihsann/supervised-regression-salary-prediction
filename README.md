# Supervised_Regression_SalaryPrediction
## Project Portfolio Exploratory Data Analysis
Exploratory Data Analysis (EDA) adalah langkah awal yang krusial dalam setiap proyek analisis data. EDA dapat membantu dalam menggali lebih dalam tentang dataset, menemukan pola-pola tersembunyi, dan memahami karakteristik data secara menyeluruh. Exploratory Data Analysis (EDA) menjadi langkah awal dalam proyek prediksi gaji ini. Proyek ini akan menyajikan hasil EDA yang meliputi visualisasi data dan analisis data berserta report insight. Proyek ini bertujuan untuk memprediksi gaji seseorang menggunakan teknik supervised learning berbasis regresi. Analisis dilakukan dengan menerapkan beberapa model regresi pada dataset salary_data.csv.

Goals:
  1. Melakukan analisis eksplorasi data (EDA) untuk memahami pola data.
  2. Melakukan preprocessing data seperti menangani data duplikat, nilai yang hilang, dan encoding variabel kategorikal (dataset ini tidak memiliki kolom kategorikal).
  3. Membangun beberapa model regresi untuk memprediksi gaji, antara lain model Linear Regression, Decision Tree, dan Random Forest.
  4. Mengevaluasi performa model berdasarkan data training dan testing untuk memahami potensi underfitting atau overfitting.
  5. Memberikan hasil berupa kesimpulan singkat terkait model data yang sudah dianalisis.

Insights:
  1. Exploratory Data Analysis (EDA)
     Tidak ditemukan nilai yang hilang atau duplikat dalam dataset dan sudah dilakukan Data preprocessing sehingga dataset siap digunakan untuk pelatihan model.

  2. Model Linear Regression
     Model sederhana ini menunjukkan tanda underfitting karena tidak mampu menjelaskan variasi data dengan baik. Namun, model ini memiliki kemampuan generalisasi yang cukup baik terhadap data baru.

  3. Model Decision Tree
     Model ini memiliki performa yang sangat baik pada data training, tetapi gagal pada data testing. Ini menunjukkan adanya masalah overfitting.

  4. Model Random Forest
     Meskipun model ini juga menunjukkan sedikit overfitting, performanya lebih stabil dibandingkan Decision Tree. Model ini cukup baik dalam menjelaskan variasi data pada data training maupun testing.

Advices:
  1. Pilih Model yang Sesuai Kebutuhan
     Gunakan Linear Regression jika Anda membutuhkan model yang sederhana dan cepat untuk digunakan dalam produksi, meskipun prediksinya mungkin kurang akurat. Jika fokus pada akurasi lebih tinggi, pilih Random Forest dengan pengaturan parameter yang dioptimalkan.

  2. Tingkatkan Generalisasi Model
     Untuk menghindari masalah overfitting pada Decision Tree dan Random Forest, lakukan hyperparameter tuning, seperti mengatur kedalaman maksimum pohon atau mengurangi jumlah pohon (n_estimators).

  3. Evaluasi Model Secara Berkala
     Lakukan evaluasi model secara berkala dengan data baru untuk memastikan bahwa model tetap relevan dan dapat menangkap pola terbaru dari data.

  4. Tambahkan Variabel atau Fitur Baru
     Pertimbangkan menambahkan variabel seperti pengalaman kerja, tingkat pendidikan, atau lokasi pekerjaan. Ini dapat meningkatkan akurasi prediksi gaji dengan menambahkan dimensi penting dalam dataset.

  5. Gunakan Data Tambahan untuk Pelatihan
     Jika memungkinkan, tambahkan lebih banyak data untuk melatih model agar dapat menghasilkan prediksi yang lebih akurat dan stabil.

Should you have any suggestions or feedback, feel free to reach out to me via direct message on LinkedIn or email
email: ahmadihsan506@gmail.com
linkedIn: https://www.linkedin.com/in/ahmadihsan-/ 
