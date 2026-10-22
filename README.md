# Pembuktian Citra Digital sebagai Susunan Angka

**Mata Kuliah:** Pengolahan Citra Digital  
**Nama:** [YAZID HUSAINI]  
**NIM:** [24260048]  
**Bahasa Pemrograman:** Python

## 1. Deskripsi

Project ini dibuat untuk membuktikan bahwa citra digital merupakan representasi data numerik yang dapat dibaca dan diolah menggunakan pemrograman komputer.

Eksperimen dilakukan menggunakan Python, NumPy, Pillow, dan Matplotlib melalui Jupyter Notebook.

## 2. Tujuan

- Mengetahui representasi numerik citra digital.
- Mengamati matriks dan nilai piksel RGB.
- Mengonversi citra RGB menjadi grayscale.
- Menganalisis distribusi intensitas menggunakan histogram.
- Membuktikan pengaruh manipulasi nilai piksel terhadap tampilan gambar.
- Merekonstruksi citra dari array numerik.

## 3. Dasar Teori

Citra digital tersusun atas elemen yang disebut piksel (*picture element*). Setiap piksel menyimpan nilai numerik yang merepresentasikan intensitas atau warna.

Pada citra RGB 8-bit, setiap piksel memiliki tiga kanal warna: Red, Green, dan Blue. Masing-masing kanal memiliki rentang nilai 0–255.

Jika citra memiliki lebar W dan tinggi H, jumlah pikselnya adalah:

N = W × H

Untuk citra RGB dengan tiga kanal, jumlah nilai kanal warnanya adalah:

Jumlah nilai = W × H × 3

## 4. Metode Eksperimen

1. Membaca gambar menggunakan Pillow.
2. Mengubah gambar menjadi array NumPy.
3. Mengamati dimensi, jumlah piksel, dan nilai RGB.
4. Mengonversi citra menjadi grayscale.
5. Memanipulasi intensitas piksel.
6. Menganalisis histogram dan statistik intensitas.
7. Merekonstruksi gambar dan membandingkan nilai piksel.

## 5. Struktur Repository

- `pembuktian_citra.ipynb`: kode, penjelasan, dan hasil eksperimen.
- `images/`: gambar asli yang digunakan.
- `results/`: gambar hasil pengolahan.
- `requirements.txt`: daftar library Python.
- `TODO.md`: daftar pekerjaan dan progres project.

## 6. Cara Menjalankan

1. Pastikan Python sudah terpasang.
2. Buat dan aktifkan virtual environment.
3. Instal library:

   `pip install -r requirements.txt`

4. Buka `pembuktian_citra.ipynb` menggunakan VS Code.
5. Pilih kernel Python dari virtual environment.
6. Jalankan notebook dari awal hingga akhir.

## 7. Hasil dan Kesimpulan

Hasil eksperimen dan visualisasi tersedia di notebook serta folder `results/`.

Kesimpulan akhir akan didasarkan pada hasil pengujian, termasuk representasi matriks piksel, manipulasi intensitas, analisis histogram, dan verifikasi rekonstruksi citra.
