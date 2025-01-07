# 📚 Studi Kasus: Spotify Song Analysis Project

## 👥 Anggota Kelompok
1. Muhammad Ferdo Bahril Rizky (202110370311470)

---

## 📖 Pendahuluan

### 🔍 1. Pernyataan Masalah
Dengan jutaan lagu yang tersedia di Spotify, penting untuk memahami karakteristik yang memengaruhi popularitas lagu. Proyek ini bertujuan untuk menjawab pertanyaan seperti:
1. Faktor audio apa yang paling berpengaruh terhadap popularitas lagu?
2. Bagaimana genre dan subgenre memengaruhi tren popularitas?
3. Apakah tempo, energi, atau sifat akustik memainkan peran penting?

### 📊 2. Data yang Digunakan
- **URL Dataset** dapat diakses melalui tautan berikut:
  - 🔗 [Download Dataset](https://www.dropbox.com/sh/qj0ueimxot3ltbf/AACzMOHv7sZCJsj3ErjtOG7ya?dl=1)
- **Dataset** mencakup atribut seperti:
  - 'track_id'
  - 'track_name'
  - 'track_artist'
  - 'track_popularity'
  - 'playlist_genre'
  - 'danceability'
  - 'energy'
  - 'tempo'
  - dll.
- **Metodologi:**
  - 🔄 Pembersihan data untuk mengatasi nilai kosong dan memastikan format data yang konsisten.
  - 📈 Analisis eksploratif (EDA) untuk mengeksplorasi distribusi popularitas dan fitur audio.
  - 🔗 Analisis korelasi untuk mengukur hubungan antara fitur audio dan popularitas.

### 🔬 3. Pendekatan/Teknik Analisis
- **Eksplorasi Data:**
  - Mengelompokkan data berdasarkan genre dan menghitung rata-rata popularitas.
  - Menampilkan distribusi popularitas menggunakan histogram dan boxplot.
- **Analisis Korelasi:**
  - Mengukur korelasi antara track_popularity dengan fitur audio seperti danceability, energy, dan tempo.
  - Menggunakan heatmap untuk visualisasi korelasi fitur.

### 🎯 4. Analisis Membantu Konsumen & Industri Musik Manfaat bagi Produser dan Pemasar:
- **Manfaat bagi Pengelola Produser:**
  - Memahami fitur audio yang berkontribusi pada popularitas dapat mengarahkan strategi produksi.
  - Membantu memilih genre dan fitur audio yang relevan untuk target aud.
- **Manfaat bagi Pemasar:**
  - Menemukan pola lagu populer dapat meningkatkan pengalaman mendengarkan.

---

## 📦 Package yang Diperlukan

### 🗂️ Deskripsi Dataset
- track_name, track_artist, track_popularity, dan fitur audio seperti danceability, energy, acousticness, dll.

---

## 🛠️ Langkah-Langkah Pembersihan Data
1. 🚿 Menghapus nilai kosong pada kolom penting.(`country`, `agent`, `company`).
2. 🛠️ Memastikan format waktu pada track_album_release_date.
3. 📊 Menyesuaikan tipe data untuk analisis korelasi dan visualisasi.

---

## 📊 Hasil Analisis Data

### 🔍 Popularitas rata-rata dihitung berdasarkan genre.
- 
- ![Gambar1](https://github.com/iniferdooo/UAS_BIGDATA/blob/main/Gambar/Average%20Daily%20Rate%20(ADR)%20.jpg)
- #### Rata-rata ADR Berdasarkan genre

|Popularitas| Rata-rata ADR |
|------------|---------------|
| POP        | 75.32         |
| ROCK       | 68.45         |
| R&B        | 70.45         |
| JAZZ       | 62.14         |
| RAP        | 73.50         |
| LATIN      | 66.40         | 
















### 🌍 Korelasi Fitur Audio dengan Popularitas:
| Fitur Audio  | Korelasi |
|--------------|----------|
| Danceability | 0.42     | 
| Energy       | 0.35     |
| Tempo        | -0.15    |


---

## 🚀 Kesimpulan
- **Untuk Produser:**
  - Data memberikan panduan memilih fitur audio yang berhubungan dengan popularitas tinggi.
  - Strategi ini dapat meningkatkan keberhasilan rilis lagu baru
- **Untuk Pemasar:**
  - Mengetahui fitur umum dari lagu populer dapat meningkatkan pengalaman mendengarkan.

---
