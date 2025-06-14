# 🗺️ Dataset Sandtara

Repositori ini berisi kumpulan dataset yang digunakan untuk membangun sistem rekomendasi wisata, hotel, dan prediksi cuaca. Dataset ini dikembangkan dalam rangka mendukung pengambilan keputusan berbasis data untuk wisatawan.

## 📂 Daftar Dataset

Berikut adalah file yang tersedia di repositori ini:

1. **Dataset-DestinasiWisata.xlsx**  
   Berisi informasi mengenai berbagai destinasi wisata (nama, lokasi, deskripsi, kategori, dan fitur pendukung).

2. **Dataset-Hotel-ByRating&UlasanUser.csv**  
   Berisi data hotel, rating pengguna, dan ulasan. Sangat cocok untuk model rekomendasi berbasis konten atau collaborative filtering.

3. **Dataset-PrediksiCuaca-Hari-OpenMeteor.csv**  
   Data prakiraan cuaca harian dari Open-Meteo (parameter: suhu, kelembapan, hujan, dll).

4. **Dataset-PrediksiCuaca-Jam-OpenMeteor.csv**  
   Data prakiraan cuaca per jam dari Open-Meteo. Cocok untuk prediksi jangka pendek dan integrasi real-time.

---

## 🎯 Tujuan

Dataset ini disusun untuk mendukung:

- Rekomendasi tempat wisata berdasarkan preferensi dan kondisi cuaca.
- Rekomendasi hotel berdasarkan rating dan ulasan.
- Integrasi data cuaca untuk meningkatkan pengalaman perjalanan.

---

## ▶️ Cara Menggunakan Dataset

### 1. Unduh Dataset

Klik tombol `Code > Download ZIP` atau clone repositori ini:

```bash
git clone https://github.com/mrikihidayat/Dataset-Sandtana.git
cd Dataset-Sandtana
```

### 2. Baca Dataset dengan Menggunakan Python
```bash
import pandas as pd

# Membaca dataset wisata
df_wisata = pd.read_excel("Dataset-DestinasiWisata.xlsx")

# Membaca dataset hotel
df_hotel = pd.read_csv("Dataset-Hotel-ByRating&UlasanUser.csv")

# Membaca dataset cuaca harian
df_cuaca_hari = pd.read_csv("Dataset-PrediksiCuaca-Hari-OpenMeteor.csv")

# Membaca dataset cuaca jam-jaman
df_cuaca_jam = pd.read_csv("Dataset-PrediksiCuaca-Jam-OpenMeteor.csv")

# Contoh: menampilkan 5 data pertama
print(df_hotel.head())
```
