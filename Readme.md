# Submission 1: Proyek Pengembangan Machine Learning Pipeline
Nama                : Zakaria Rafi
E-mail              : zakariarafifahmi@gmail.com
Username dicoding   :zakaria_rafi

| | Deskripsi |
| ----------- | ----------- |
| Dataset | [World Happiness Report](https://www.kaggle.com/datasets/unsdsn/world-happiness) |
| Masalah | Analisis faktor-faktor yang mempengaruhi tingkat kebahagiaan di berbagai negara dan prediksi skor kebahagiaan berdasarkan faktor-faktor tersebut. Tujuan adalah untuk memahami dinamika kebahagiaan dan faktor-faktor yang berkontribusi terhadapnya untuk membantu pembuat kebijakan dalam membuat keputusan yang informasinya.|
| Solusi machine learning | Mengembangkan model machine learning yang dapat memprediksi skor kebahagiaan berdasarkan faktor-faktor seperti GDP per kapita, dukungan sosial, harapan hidup, kebebasan, absensi korupsi, dan kemurahan hati. Model ini akan dilatih menggunakan data historis dari World Happiness Report dan akan dievaluasi berdasarkan metrik seperti Mean Absolute Error (MAE), Mean Squared Error (MSE), atau R-squared. |
| Metode pengolahan | Metode pengolahan data melibatkan beberapa langkah kritis untuk memastikan keakuratan dan efisiensi dalam analisis. Proses ini dimulai dengan pembersihan data, di mana data yang hilang atau tidak konsisten ditangani dan outlier dieliminasi jika perlu untuk memastikan keandalan data. Eksplorasi data mengikuti, melibatkan analisis deskriptif dan visualisasi untuk mendapatkan pemahaman yang lebih mendalam tentang distribusi dan korelasi antar variabel. Pada tahap feature engineering, fitur disesuaikan dan ditransformasi untuk meningkatkan performa model. Proses normalisasi data menyusul, di mana fitur disekalakan agar memiliki rentang nilai yang serupa, yang pada gilirannya membantu meningkatkan konvergensi model.  |
| Arsitektur model | Model Random Forest dipilih karena Random Forest dapat menghandle non-linearitas dalam data, model ini memiliki mekanisme untuk menangani overfitting, seperti bagging dan model ini dapat memberikan informasi tentang pentingnya fitur, yang bisa berguna untuk interpretasi dan analisis lebih lanjut. |
| Metrik evaluasi | Evaluasi model menggunakan Mean Absolute Error (MAE), yang mengukur rata-rata selisih absolut antara prediksi dan nilai sebenarnya,serta karena MAE memberikan informasi yang jelas dan mudah diinterpretasikan tentang rata-rata kesalahan dalam unit skor kebahagiaan dan MAE tidak sensitive terhadap outlier sebagaimana Mean Squared Error (MSE), sehingga memberikan evaluasi yang lebih robust. |
| Performa model | Performa model akan dievaluasi menggunakan metrik di atas pada set validasi dan test. Optimisasi hyperparameter dan teknik validasi silang dapat digunakan untuk memastikan bahwa model memiliki performa yang baik dan tidak overfitting atau underfitting. Model harus mampu memprediksi skor kebahagiaan dengan akurasi yang memadai dan eror yang minimal. |