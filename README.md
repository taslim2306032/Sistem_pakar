# Sistem Pakar Diagnosa Penyakit Ringan
TASLIM_NURALIM 2306032


Sistem ini merupakan contoh **sistem pakar sederhana** yang dibuat menggunakan bahasa pemrograman **Python** dan pustaka **experta**. Sistem ini digunakan untuk mendiagnosa penyakit berdasarkan gejala yang dimasukkan oleh pengguna.

## Fitur

- Mendeteksi beberapa penyakit ringan berdasarkan kombinasi gejala:
  - Flu
  - Pneumonia
  - Pilek Biasa
  - Infeksi Tenggorokan
  - Alergi
  - COVID-19
  - Infeksi Sinus
  - Bronkitis
  - Kondisi Sehat

- Input gejala dilakukan melalui pertanyaan interaktif (ya/tidak).
- Menggunakan _rule-based inference engine_ dari `experta`.

## Instalasi

1. Pastikan Python sudah terpasang (disarankan versi 3.8 ke atas).
2. Clone repositori ini:

   ```bash
   git clone https://github.com/taslim2306032/Sistem_pakar.git
   cd Sistem_pakar
   ```

3. Install pustaka yang dibutuhkan:

   ```bash
   pip install experta
   ```

## Menjalankan Program

Jalankan file utama dengan:

```bash
python main.py
```

Kemudian jawab pertanyaan gejala yang muncul di terminal dengan `ya` atau `tidak`.

Contoh:

```
Apakah kamu batuk? (ya/tidak): ya
Apakah kamu demam? (ya/tidak): tidak
Apakah kamu merasa lelah? (ya/tidak): ya
...
Diagnosa: Kamu mungkin mengalami Bronkitis.
```

## Struktur File

```
Sistem_pakar/
├── main.py         # Program utama sistem pakar
└── README.md       # Dokumentasi ini
```
