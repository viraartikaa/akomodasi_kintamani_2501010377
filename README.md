# Akuisisi Data Akomodasi Kecamatan Kintamani

## Identitas
- Nama: Ni Putu Vira Artika Dewi
- NIM: 2501010377
- Mata Kuliah: BIFP-243 Akuisisi dan Manajemen Data
- Wilayah: Kecamatan Kintamani, Kabupaten Bangli, Bali

## Deskripsi
Proyek ini bertujuan mengakuisisi dan mengelola
data akomodasi menggunakan OpenStreetMap melalui
Overpass API.

## Sumber Data
1. OpenStreetMap melalui Overpass API.
2. BPS Kabupaten Bangli.
3. Satu Data Bali sebagai sumber pendukung.

## Kategori
- hotel
- guest_house
- hostel
- motel
- apartment
- chalet

## Metodologi
1. Pemeriksaan batas administratif.
2. Akuisisi melalui Overpass API.
3. Penyimpanan raw JSON.
4. Transformasi JSON menjadi DataFrame.
5. Cleaning dan validasi koordinat.
6. Analisis distribusi dan kelengkapan.
7. Perbandingan dengan BPS.
8. Verifikasi sampel.
9. Pembuatan dokumentasi dan laporan.

## Struktur Dataset
Dataset memiliki 11 kolom:
osm_type, osm_id, nama, jenis, lat, lon,
desa, bintang, jumlah_kamar, website, url_osm.

## Etika Data
- Tidak mengambil kontak pribadi.
- Tidak melakukan scraping OTA.
- Tidak menggunakan Google Maps.
- Mematuhi penggunaan Overpass API.
- Menjaga data raw.
- Mencantumkan atribusi dan lisensi.

## Atribusi
© OpenStreetMap contributors.

Data tersedia di bawah lisensi ODbL.

https://www.openstreetmap.org/copyright

## Hasil Pengolahan
- Total data raw: 32
- Total data bersih: 32
- Duplikat: 0
- Tanpa nama: 1
- Di luar wilayah: 0
- Status verifikasi BPS: Belum diverifikasi

## Menjalankan Notebook
Buka notebooks/akuisisi_akomodasi.ipynb
dan jalankan seluruh cell secara berurutan.

## Keterbatasan
OpenStreetMap merupakan data crowdsourced
sehingga tidak dapat dianggap sebagai daftar
resmi dan lengkap seluruh usaha akomodasi.