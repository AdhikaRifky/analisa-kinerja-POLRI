Analisa Kinerja Kepolisian Republik Indonesia Berbasis Teks dengan Metode RNN

Deskripsi Proyek

Proyek ini bertujuan untuk menganalisis kinerja Kepolisian Republik Indonesia berdasarkan data teks menggunakan metode Recurrent Neural Network (RNN). Model yang dikembangkan menggunakan pendekatan TF-IDF sebagai fitur input untuk meningkatkan efisiensi analisis.

struktur
skripsi-analisa-kinerja-polri/
├── data/              # Dataset yang digunakan (tidak diunggah jika bersifat rahasia)
├── notebooks/         # Jupyter Notebook untuk eksplorasi data, training, dan evaluasi model
├── README.md          # Dokumentasi proyek ini
├── requirements.txt   # Daftar library yang digunakan dalam proyek
└── .gitignore         # File untuk mengecualikan data besar/sensitif

Teknologi & Library yang Digunakan

Python

TensorFlow/Keras untuk membangun dan melatih model RNN

Scikit-learn untuk preprocessing data dan evaluasi model

Pandas & NumPy untuk manipulasi data

Matplotlib & Seaborn untuk visualisasi data

Dataset

Dataset yang digunakan dalam penelitian ini bersumber dari hasil Scrapping mandiri. Jika dataset tidak diunggah ke GitHub, silakan menghubungi saya untuk informasi lebih lanjut.

Cara Menjalankan Proyek

1. Clone Repository

git clone https://github.com/username/skripsi-analisa-kinerja-polri.git
cd skripsi-analisa-kinerja-polri


2. Buat Virtual Environment (Opsional tapi Disarankan)

python -m venv venv
source venv/bin/activate  # Mac/Linux
venv\Scripts\activate     # Windows


3. Install Dependensi

pip install -r requirements.txt


4. Jalankan Jupyter Notebook

jupyter notebook

Lalu buka notebook dalam folder notebooks/ untuk melihat analisis dan hasil model.

Hasil & Evaluasi

Model RNN yang dibangun berhasil mencapai akurasi 77%, dengan evaluasi menggunakan confusion matrix, precision, recall, dan F1-score.

