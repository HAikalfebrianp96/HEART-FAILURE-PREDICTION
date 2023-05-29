# HEART FAILURE PREDICTION 
# Introduction
Penelitian ini bertujuan untuk memprediksi gagal jantung menggunakan berbagai algoritma pembelajaran mesin dan teknik fusi hibrida. Makalah ini fokus pada penggunaan algoritma mayoritas yang menggunakan 3 model pembelajaran mesin dengan kinerja terbaik dari total 10 model yang dipilih, antara lain Logistic Regression, Decision Tree, Random Forest, Bagging Classifier, Gradient Boosting Classifier, Extreme Gradient Boosting Classifier, Extra Trees Classifier, CatBoost Classifier, dan lainnya.

Tiga pengklasifikasi teratas dipilih berdasarkan akurasi, skor f1, dan waktu pelatihan yang diperlukan. Minimum akurasi dan ambang batas skor F1 ditetapkan pada 90% untuk mencapai kinerja yang lebih baik dalam situasi dunia nyata dengan tingkat akurasi yang lebih tinggi dan kompleksitas waktu yang rendah.

Model yang diusulkan menggabungkan ketiga model terbaik menggunakan metode Gradient Boosting Classifier dengan akurasi sebesar 0.7949.

# Purpose of the Project
Seiring dengan dataset yang besar, algoritma pembelajaran mesin terbukti jauh lebih efektif dan akurat dalam menentukan berbagai prediksi mengenai rekam medis tertentu. Ini membantu dalam memberikan lebih banyak informasi untuk mendidik pasien tentang penyakit mereka. Model berbasis klasifikasi sangat berguna dalam kondisi ini di mana penyakit harus dideteksi berdasarkan beberapa parameter medis. Ini berkaitan dengan masalah klasifikasi biner untuk memprediksi kemungkinan pasien meninggal karena gagal jantung dengan mempertimbangkan berbagai parameter sesuai kumpulan data.

# About the dataset
penyakit kardiovaskular (CVDs) adalah penyebab kematian nomor 1 secara global, merenggut sekitar 17,9 juta nyawa setiap tahun, yang merupakan 31% dari semua kematian di seluruh dunia. Gagal jantung adalah kejadian umum yang disebabkan oleh CVD dan kumpulan data ini berisi 12 fitur yang dapat digunakan untuk memprediksi kematian akibat gagal jantung.

Sebagian besar penyakit kardiovaskular dapat dicegah dengan mengatasi faktor risiko perilaku seperti penggunaan tembakau, pola makan yang tidak sehat dan obesitas, kurangnya aktivitas fisik, dan penggunaan alkohol yang berbahaya dengan menggunakan strategi populasi luas.

Orang dengan penyakit kardiovaskular atau yang memiliki risiko kardiovaskular tinggi (karena adanya satu atau lebih faktor risiko seperti hipertensi, diabetes, hiperlipidemia, atau penyakit yang sudah ada) memerlukan deteksi dan penanganan dini di mana model pembelajaran mesin dapat sangat membantu.
link data https://www.kaggle.com/datasets/andrewmvd/heart-failure-clinical-data
