📚 Studi Kasus: Spotify Song Analysis Project
👥 Anggota Kelompok
Muhammad Ferdo Bahril Rizky (202110370311470)
📖 Pendahuluan
1. Pernyataan Masalah
Dengan jutaan lagu yang tersedia di Spotify, penting untuk memahami karakteristik yang memengaruhi popularitas lagu. Proyek ini bertujuan untuk menjawab pertanyaan seperti:

Faktor audio apa yang paling berpengaruh terhadap popularitas lagu?

Bagaimana genre dan subgenre memengaruhi tren popularitas?

Apakah tempo, energi, atau sifat akustik memainkan peran penting?

Masalah ini relevan karena memberikan wawasan berharga bagi musisi, produser, dan pemasar untuk meningkatkan strategi perilisan dan promosi lagu.

📊 2. Data yang Digunakan
Dataset yang digunakan mencakup 32.833 entri dan 23 atribut, yang meliputi:

track_id, track_name, track_artist, track_popularity, playlist_genre, danceability, energy, tempo, dan lain-lain.

🔗 Download Dataset

Metodologi:
🔄 Pembersihan data untuk mengatasi nilai kosong dan memastikan format data yang konsisten.
📈 Analisis eksploratif (EDA) untuk mengeksplorasi distribusi popularitas dan fitur audio.
🔗 Analisis korelasi untuk mengukur hubungan antara fitur audio dan popularitas.

🔬 3. Pendekatan/Teknik Analisis
Eksplorasi Data:

Mengelompokkan data berdasarkan genre dan menghitung rata-rata popularitas.

Menampilkan distribusi popularitas menggunakan histogram dan boxplot.

Analisis Korelasi:

Mengukur korelasi antara track_popularity dengan fitur audio seperti danceability, energy, dan tempo.

Menggunakan heatmap untuk visualisasi korelasi fitur.

🎯 4. Analisis Membantu Konsumen & Industri Musik
Manfaat bagi Produser dan Pemasar:

Memahami fitur audio yang berkontribusi pada popularitas dapat mengarahkan strategi produksi.

Membantu memilih genre dan fitur audio yang relevan untuk target audiens.

Manfaat bagi Konsumen:

Menemukan pola lagu populer dapat meningkatkan pengalaman mendengarkan.

📦 5. Package yang Diperlukan

pandas

matplotlib

seaborn

numpy

🗂️ 6. Deskripsi Dataset
Dataset ini berasal dari sumber Spotify dan mencakup informasi seperti:

track_name, track_artist, track_popularity, dan fitur audio seperti danceability, energy, acousticness, dll.

🛠️ 7. Langkah-Langkah Pembersihan Data
🚿 Menghapus nilai kosong pada kolom penting.
🛠️ Memastikan format waktu pada track_album_release_date.
📊 Menyesuaikan tipe data untuk analisis korelasi dan visualisasi.

📊 8. Hasil Analisis Data
Distribusi Popularitas Berdasarkan Genre:

Popularitas rata-rata dihitung berdasarkan genre.

Contoh:

Genre

Popularitas Rata-rata

Pop

75.32

Rock

68.45

Jazz

62.14

Korelasi Fitur Audio dengan Popularitas:

Fitur Audio

Korelasi

Danceability

0.42

Energy

0.35

Tempo

-0.15

🚀 9. Kesimpulan
Untuk Produser dan Pemasar:

Data memberikan panduan memilih fitur audio yang berhubungan dengan popularitas tinggi.

Strategi ini dapat meningkatkan keberhasilan rilis lagu baru.

Untuk Konsumen:

Mengetahui fitur umum dari lagu populer dapat meningkatkan pengalaman mendengarkan.

Proyek ini memberikan wawasan yang relevan dan dapat dikembangkan lebih jauh dengan analisis prediktif untuk memodelkan popularitas lagu berdasarkan fitur audio.

