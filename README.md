# Submission 1: Fake News Detection
Nama: Febrian Chrisna Ardianto

Username dicoding: chrisnaa

| | Deskripsi |
| ----------- | ----------- |
| Dataset | [Fake News Detection Dataset](https://www.kaggle.com/datasets/abdelilahelfedg/fake-news-detection-dataset) |
| Masalah |Di era digital saat ini, penyebaran berita palsu (hoaks) melalui media sosial dan situs berita memiliki dampak signifikan terhadap masyarakat, terutama dalam mempengaruhi opini publik dan keputusan penting. Proyek ini bertujuan untuk mendeteksi dan mengklasifikasikan berita sebagai berita palsu atau berita asli dengan menggunakan model machine learning, untuk membantu mengurangi dampak negatif dari penyebaran berita palsu.|
| Solusi machine learning | Solusi machine learning yang akan dibangun adalah model yang mampu mengklasifikasikan artikel berita menjadi dua kategori: berita palsu dan berita asli. Model ini akan dilatih menggunakan dataset yang mengandung berita dari dua sumber berbeda (The New York Times untuk berita asli dan AFP Fact Check untuk berita palsu).|
| Metode pengolahan | Data diproses menggunakan teknik seperti pembersihan teks (case folding), tokenisasi, dan konversi teks menjadi representasi numerik dengan teknik seperti TF-IDF atau word embeddings. Dataset dibagi menjadi data pelatihan dan evaluasi, kemudian diproses menggunakan TensorFlow Transform untuk mempersiapkan data sebelum digunakan dalam pelatihan model.|
| Arsitektur model | Model yang digunakan adalah model berbasis deep learning menggunakan LSTM (Long Short-Term Memory) yang dipadukan dengan Bidirectional LSTM dan Dense layers untuk mengklasifikasikan teks. Proses tuning dilakukan menggunakan Hyperband untuk mencari kombinasi hiperparameter terbaik seperti jumlah unit LSTM, unit Dense, dan tingkat dropout.|
| Metrik evaluasi | Metrik yang digunakan untuk mengevaluasi performa model meliputi Binary Accuracy, AUC (Area Under Curve), False Positives, True Positives, False Negatives, dan True Negatives. Metrik utama yang digunakan untuk evaluasi adalah akurasi klasifikasi.|
| Performa model | Model yang dibangun menunjukkan performa yang sangat baik dengan binary accuracy sebesar 97.15%, yang menunjukkan kemampuan model dalam mengklasifikasikan berita asli dan palsu dengan akurat.|
