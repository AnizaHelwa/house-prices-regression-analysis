# house-prices-regression-analysis

📌 **Overview**

Proyek ini bertujuan untuk memprediksi harga jual rumah menggunakan berbagai fitur properti seperti luas tanah, kualitas bangunan, lokasi, dan fasilitas lainnya. Dataset ini berasal dari kompetisi populer di Kaggle yang menuntut teknik preprocessing data yang teliti karena banyaknya variabel kategorikal dan nilai yang hilang.

🛠️ **Tech Stack**

- Language: Python
- Data Analysis: Pandas, NumPy
- Visualization: Matplotlib, Seaborn
- Machine Learning: Scikit-Learn (Random Forest Regressor)

🚀 **Key Workflow & Features**

- Exploratory Data Analysis (EDA): Menganalisis korelasi antar fitur dan distribusi variabel target (SalePrice).
- Data Cleaning:
    - Menangani missing values secara sistematis pada fitur numerik dan kategorikal.
    - Melakukan Outlier removal untuk menjaga integritas model.

- Feature Engineering:
    - Log Transformation: Menerapkan transformasi log pada variabel target untuk menangani skewness agar distribusi data lebih normal.
    - Encoding: Mengubah data kategorikal menjadi format numerik yang dapat diproses model.

- Modeling: Menggunakan Random Forest Regressor untuk menangkap hubungan non-linear antar fitur.
- Evaluation: Model dievaluasi menggunakan metrik RMSE (Root Mean Squared Error) pada data yang sudah di-log transform, yang mencerminkan persentase error terhadap harga asli.

📊 **Results**

Model berhasil memberikan prediksi yang mendekati harga asli (seperti yang terlihat pada tabel perbandingan di akhir notebook), menunjukkan bahwa fitur seperti kualitas material dan luas area memiliki pengaruh signifikan terhadap harga rumah.
