# Sentiment Analysis Review Produk menggunakan Machine Learning dengan TensorFlow

Ini adalah project Sentiment Analysis sederhana menggunakan Machine Learning dengan TensorFlow. Tujuan dari project ini adalah untuk mengklasifikasikan sentimen positif atau negatif dari teks yang diberikan.

## Deskripsi

Project ini menggunakan model Machine Learning yang telah dilatih untuk menganalisis sentimen dari teks. Model ini dibangun dengan menggunakan dataset yang terdiri dari berbagai review teks positif dan negatif.

## Cara Kerja

1. **Pra-pemrosesan Data**:
    - Tokenisasi teks: Mengubah teks menjadi urutan token.
    - Padding: Menyesuaikan panjang setiap kalimat menjadi sama.

2. **Pembuatan Model**:
    - Sequential Model dengan beberapa layer Dense.
    - Layer Embedding untuk mengubah teks menjadi vektor.
    - Layer Bidirectional LSTM untuk memahami konteks sekuensial dalam teks secara maju dan mundur.
    - Layer Dense dengan fungsi aktivasi sigmoid untuk output binary (positif/negatif).

3. **Pelatihan Model**:
    - Menggunakan metode Adam untuk optimasi.
    - Menggunakan binary crossentropy sebagai loss function.
    - Melacak metrik akurasi selama pelatihan.

4. **Evaluasi Model**:
    - Memplotting metrik akurasi dan loss pada saat training.
    - Mengukur akurasi pada data validasi.
    - Melihat metrik loss untuk mengevaluasi performa model.
    - Menginput teks baru untuk melihat output prediksi dari model yang telah ditraining.

## Dataset

Dataset yang digunakan dalam project ini adalah dataset mengenai review produk dari suatu e-commerce, untuk datasetnya sudah disediakan direpository ini dalam bentuk zip
