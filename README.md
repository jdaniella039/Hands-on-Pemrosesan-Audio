# Hands-on Pemrosesan Audio

Repository ini berisi solusi untuk tugas mata kuliah IF4021 - Multimedia Information Processing tentang Pemrosesan Audio. Tugas ini meliputi rekaman suara, analisis, filtering, pitch shifting, normalisasi, dan remix audio menggunakan Python.

## Struktur Repository
## Hands-on-Pemrosesan-Audio/
Hands-on-Pemrosesan-Audio/

## Deskripsi Tugas

### Tugas 1: Rekaman dan Analisis Suara Multi-Level
- **Tujuan:** Rekam suara selama 25 detik dengan variasi tingkat suara yang berbeda dan visualisasikan waveform serta spektrogram.
- **Proses:** 
  - 5 detik pertama: suara sangat pelan dan berbisik
  - 5 detik kedua: suara normal
  - 5 detik ketiga: suara keras
  - 5 detik keempat: suara cempreng
  - 5 detik terakhir: suara berteriak
- **Hasil:** Visualisasi waveform dan spektrogram serta perbandingan kualitas dan durasi setelah resampling.

### Tugas 2: Pengurangan Noise dengan Filtering
- **Tujuan:** Rekam suara di lingkungan berisik dan terapkan filter untuk mengurangi noise (high-pass, low-pass, band-pass).
- **Proses:**
  - Eksperimen dengan berbagai nilai frekuensi cutoff (500 Hz, 1000 Hz, 2000 Hz).
- **Hasil:** Perbandingan spektrogram untuk masing-masing filter dan analisis jenis noise serta efektivitas filter.

### Tugas 3: Pitch Shifting dan Manipulasi Audio
- **Tujuan:** Terapkan pitch shifting pada rekaman suara untuk menciptakan efek suara chipmunk.
- **Proses:** 
  - Pitch shift dengan +7 dan +12 semitone.
- **Hasil:** Visualisasi waveform dan spektrogram sebelum dan sesudah pitch shifting, serta penjelasan pengaruh pitch terhadap kejelasan suara.

### Tugas 4: Rangkaian Pemrosesan Audio
- **Tujuan:** Lakukan rangkaian pemrosesan audio pada rekaman yang telah dipitch shift.
- **Proses:**
  - Terapkan Equalizer, Gain/Fade, Normalisasi, Kompresi, Noise Gate, dan Silence Trimming.
  - Set target loudness ke -16 LUFS.
- **Hasil:** Visualisasi waveform dan spektrogram sebelum dan sesudah pemrosesan, serta analisis perubahan dinamika suara dan perbedaan antara normalisasi peak dan LUFS.

### Tugas 5: Analisis Musik dan Remix
- **Tujuan:** Pilih dua lagu dengan nuansa yang berbeda dan lakukan analisis tempo (BPM) serta kunci lagu.
- **Proses:**
  - Samakan tempo dan kunci kedua lagu menggunakan time-stretching dan pitch-shifting.
  - Gabungkan lagu dengan efek crossfading dan filter kreatif.
- **Hasil:** Hasil remix kedua lagu dengan visualisasi waveform dan spektrogram, serta penjelasan proses dan parameter yang digunakan.

## Cara Menjalankan Kode

1. **Clone repositori**:

   ```bash
   git clone https://github.com/username/Hands-on-Pemrosesan-Audio.git
   cd Hands-on-Pemrosesan-Audio
