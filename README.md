# Akuisisi Data Akomodasi di Kecamatan Kintamani

**Mata Kuliah:** BIFP-243 Akuisisi dan Manajemen Data
**Pengambil Data:** Ni Putu Vira Artika Dewi (NIM: 2501010377)
**Tanggal Akses:** 2026-11-11

## 1. Deskripsi Proyek
Proyek ini bertujuan untuk mengumpulkan, meratakan, dan mendokumentasikan data akomodasi di Kecamatan Kintamani, Kabupaten Bangli, Bali secara etis.

## 2. Sumber Data & Atribusi
* **OpenStreetMap API (Overpass API)** - Data spasial dan atribut akomodasi.
* Data ini berlisensi Open Data Commons Open Database License (ODbL).
* **Atribusi Mandatory:** Data memuat informasi dari OpenStreetMap yang tersedia di bawah lisensi ODbL. **© OpenStreetMap contributors**.

## 3. Batasan Etika
* Mematuhi rate limit Overpass API tanpa request berulang berlebihan.
* Melakukan **minimisasi data** dengan sengaja tidak mengumpulkan nomor telepon, email, dan akun media sosial pemilik.
* Bebas dari scraping platform OTA terlarang (Airbnb, Booking.com, Agoda, dll.).

## 4. Cara Menjalankan Ulang Kode
1. Buka Notebook di Google Colab.
2. Jalankan seluruh sel dari atas ke bawah.
3. Respons mentah tersimpan di `data/raw/` dan dataset interim bersih di `data/interim/akomodasi_kintamani.csv`.

## 5. Struktur Repositori
- `data/` : Menyimpan data raw dan interim
- `docs/` : Menyimpan dokumen analisis dan metadata
