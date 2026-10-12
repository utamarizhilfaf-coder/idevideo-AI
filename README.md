# IdeVideo AI

Website statis untuk menghasilkan prompt video dan storyboard sederhana. Dibuat dengan HTML, CSS, dan JavaScript tanpa framework dan tanpa API key.

## Fitur
- Responsif untuk HP dan komputer
- Input ide, gaya visual, durasi, rasio layar, gerakan kamera, audio
- Pembagian storyboard per scene
- Instruksi konsistensi karakter dan lokasi
- Negative guidance opsional
- Salin prompt, unduh sebagai `.txt`
- Simpan dan muat riwayat prompt menggunakan `localStorage`
- Template cepat untuk ASMR, promosi produk, cerita pendek, dan vlog
- Tidak mengirim data ke server; riwayat tersimpan di browser perangkat yang digunakan

## Menjalankan secara lokal
1. Ekstrak ZIP.
2. Buka folder `idevideo-ai`.
3. Buka `index.html` menggunakan browser modern.
4. Untuk pengalaman lebih baik, jalankan lewat server lokal sederhana atau hosting statis.

## Deploy gratis ke GitHub Pages
1. Buat akun GitHub jika belum punya.
2. Buat repository baru, misalnya `idevideo-ai`.
3. Unggah `index.html` dan `README.md` ke root repository.
4. Buka **Settings → Pages**.
5. Di bagian build/deployment, pilih **Deploy from a branch**.
6. Pilih branch `main` dan folder `/ (root)`, lalu simpan.
7. Tunggu proses publikasi selesai. GitHub akan menampilkan URL website pada halaman Pages.

Nama menu dapat berubah sewaktu-waktu. Periksa panduan resmi GitHub Pages jika tampilan berbeda.

## Alternatif: Netlify
1. Masuk ke Netlify dan buat akun.
2. Pilih opsi untuk menambahkan situs baru melalui deploy manual.
3. Seret folder proyek atau unggah file situs sesuai petunjuk Netlify yang berlaku.
4. Gunakan URL gratis yang disediakan untuk pengujian.

## Batasan prototipe
- Generator menggunakan template JavaScript, bukan model AI generatif.
- Hasil storyboard adalah kerangka awal; pengguna sebaiknya menyunting detail adegan.
- Riwayat `localStorage` hanya tersedia di browser/perangkat yang sama dan dapat hilang jika data browser dihapus.
- Belum ada akun pengguna, database cloud, pembayaran, atau integrasi langsung dengan Dola AI.
- Jangan menaruh API key rahasia dalam file HTML/JavaScript publik. Jika kelak memakai API AI, buat backend untuk menyimpan kunci secara aman.
- IdeVideo AI adalah nama proyek sementara dan bukan produk resmi atau afiliasi Dola AI.

## Struktur proyek
```text
idevideo-ai/
├── index.html
└── README.md
```
