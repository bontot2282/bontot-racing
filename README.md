
# Service Motor Panggilan

Website pemesanan layanan servis dan penanganan darurat sepeda motor panggilan berbasis web. Dirancang untuk memudahkan pengendara memesan mekanik ke lokasi tanpa harus mengantre di bengkel.

## Fitur Utama
- **Katalog Paket Servis:** Daftar layanan servis ringan, servis besar, ganti oli, dan perbaikan darurat (mogok) lengkap dengan estimasi harga.
- **Form Booking & Integrasi WhatsApp:** Formulir pemesanan cepat yang otomatis memformat data pelanggan (nama, jenis motor, keluhan, dan titik lokasi) ke pesan WhatsApp admin.
- **Cek Area Jangkauan:** Informasi wilayah operasional dan estimasi waktu kedatangan mekanik.
- **Tombol Panggilan Darurat:** Akses cepat satu klik untuk kondisi motor mogok di jalan.

## Teknologi yang Digunakan
- **Frontend:** HTML5, CSS3, JavaScript *(sesuaikan jika memakai Tailwind CSS, React, atau Next.js)*
- **Integrasi:** WhatsApp Click-to-Chat API / Google Maps Embed

## Struktur Folder
```text
service-motor-panggilan/
├── assets/
│   ├── images/      # Foto dokumentasi mekanik & ilustrasi layanan
│   └── icons/       # Ikon paket servis
├── css/
│   └── style.css    # Styling utama website
├── js/
│   └── booking.js   # Logika validasi form & redirect WhatsApp
├── index.html       # Halaman utama
└── README.md
```

## Cara Menjalankan di Komputer Lokal
1. **Clone repositori ini:**
   ```bash
   git clone [https://github.com/username-anda/service-motor-panggilan.git](https://github.com/username-anda/service-motor-panggilan.git)
   ```
2. **Masuk ke direktori proyek:**
   ```bash
   cd service-motor-panggilan
   ```
3. **Jalankan website:**
   - Jika menggunakan HTML/CSS/JS murni, buka file `index.html` langsung di browser atau gunakan ekstensi **Live Server** di VS Code.
   - Jika menggunakan framework berbasis Node.js, jalankan `npm install` lalu `npm run dev`.

## Status Pengembangan
- [x] Inisialisasi struktur repositori
- [ ] Desain halaman utama & katalog harga
- [ ] Integrasi form pemesanan ke WhatsApp
- [ ] Deploy ke hosting
