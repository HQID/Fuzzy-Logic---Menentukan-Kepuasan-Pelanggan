# Sistem Logika Fuzzy untuk Kepuasan Pelanggan

Repository ini berisi Sistem Logika Fuzzy untuk mengevaluasi kepuasan pelanggan berdasarkan kualitas produk dan kualitas layanan menggunakan metode Mamdani.

## Daftar Isi

- [Pendahuluan](#pendahuluan)
- [Fitur](#fitur)
- [Instalasi](#instalasi)
- [Penggunaan](#penggunaan)
- [Berkontribusi](#berkontribusi)

## Pendahuluan

Proyek ini mengimplementasikan sistem logika fuzzy untuk menentukan kepuasan pelanggan berdasarkan dua input:
- Kualitas Produk
- Kualitas Layanan

Sistem menggunakan metode Mamdani untuk inferensi fuzzy dan mencakup sembilan aturan fuzzy untuk menentukan output (kepuasan pelanggan).

## Fitur

- **Fuzzifikasi**: Mengubah nilai input tegas menjadi nilai fuzzy.
- **Mesin Inferensi**: Mengaplikasikan aturan fuzzy untuk mendapatkan nilai fuzzy output.
- **Aggregasi**: Menggabungkan hasil dari semua aturan fuzzy.
- **Defuzzifikasi**: Mengubah keluaran fuzzy yang teragregasi menjadi nilai tegas.

## Instalasi

1. **Klon repository:**

   ```sh
   git clone https://github.com/yourusername/fuzzy-customer-satisfaction.git
   cd fuzzy-customer-satisfaction

2. **Instal dependensi:**

   Pastikan Anda telah menginstal Python. Kemudian, instal paket Python yang diperlukan menggunakan pip:

   ```sh
   pip install numpy scikit-fuzzy matplotlib
   ```

## Berkontribusi

Kontribusi Anda sangat kami harapkan! Jika Anda ingin berkontribusi pada proyek ini, silakan ikuti langkah-langkah berikut:

1. Fork repository.
2. Buat branch baru (`git checkout -b feature-branch`).
3. Commit perubahan Anda (`git commit -m 'Tambah fitur baru'`).
4. Push ke branch (`git push origin feature-branch`).
5. Buat pull request.
