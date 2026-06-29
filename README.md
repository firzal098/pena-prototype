# ✒️ Pena - Wireframe-Exact Mobile Prototype

Direktori ini berisi prototipe visual interaktif berbasis **HTML/CSS/JS** yang dirancang untuk mensimulasikan antarmuka dan alur navigasi aplikasi **Pena** persis sesuai dengan **desain wireframe (mobile dark mode)** dari perancangan Tahap 4.

## 📱 Desain UI yang Selaras Persis dengan Wireframe:
* **Chassis Bingkai Smartphone**: Berada di tengah halaman web desktop dengan *speaker notch* dan kamera di bagian atas.
* **Status Bar Real-Time Mockup**: Menampilkan jam (waktu) real-time yang tersinkronisasi, bar sinyal seluler, dan ikon persentase baterai.
* **Skema Warna Dark Mode Premium**: Menggunakan palet token persis sesuai spesifikasi wireframe (`#0f111a` latar belakang utama, `#161824` latar belakang kartu, `#2e3248` garis tepi kartu, dsb.).
* **Bottom Navigation Bar Terintegrasi**: Memungkinkan perpindahan antar-layar (Home, Tracker, Keuangan, Laporan, Setel/Leaderboard) dengan satu sentuhan.

---

## 🛠️ Cara Menjalankan Aplikasi
Karena prototipe ini dibuat sepenuhnya menggunakan teknologi web standar tanpa dependensi server, Anda **tidak memerlukan instalasi Python, pip, Node.js, npm, atau kompilasi build**.

### Langkah Cepat:
1. Navigasikan penjelajah berkas (File Explorer) Anda ke direktori:  
   `4. Luaran/B - Working Prototype/html_prototype/`
2. Klik dua kali (Double-click) berkas **`index.html`** untuk langsung membukanya di peramban web (Google Chrome, Microsoft Edge, Safari, Firefox).
3. Anda juga dapat menggunakan ekstensi *Live Server* di VS Code jika ingin menjalankannya secara lokal.

---

## 💎 Fitur Utama yang Disimulasikan:
1. **Pintu Gerbang Autentikasi (Auth Gate)**: Form Masuk (Login) dan Daftar Baru yang interaktif dengan validasi data. Tersedia tombol pintas instan untuk masuk menggunakan akun simulasi `firzal@pena.com` (password `123`).
2. **Dashboard Utama (Beranda)**: Kartu status performa pengguna (Level & Bar Kemajuan EXP kuning, Streak kebiasaan, Sisa limit anggaran bulanan), notifikasi pengingat dinamis, checkbox tugas harian, dan lencana militer terkunci/terbuka.
3. **Tracker Harian**: Checklist tugas hari ini dengan penambahan kegiatan secara instan, pemilih kategori chip, penambahan kategori kustom interaktif dengan *color picker*, serta deteksi naik level dan selebrasi balon/salju confetti.
4. **Manajemen Keuangan (Budgeting)**: Segmentasi form masukan Gain/Sink dengan kalkulator nominal, kategori dropdown, keterangan, deteksi limit overbudget dinamis dengan alarm merah visual, dan histori riwayat log.
5. **Grafik & Laporan**: Gambar grafik tren konsistensi 7 hari terakhir yang digambar secara dinamis melalui objek SVG, berdampingan dengan grafik alokasi belanja bulanan berjalan.
6. **Podium Peringkat Global (Leaderboard)**: Struktur visual podium juara 3 besar (Rank 1 center emas tinggi, Rank 2 perak, Rank 3 perunggu), list peringkat umum lainnya, serta galeri pencapaian milestone.
7. **Pengaturan & Akun**: Setelan konfigurasi profil, toggles reminder notifikasi beserta waktu, reset database lokal, dan deskripsi tugas mahasiswa.
8. **Penyimpanan Lokal (localStorage)**: Semua data, profil baru, kegiatan baru, dan pengeluaran tersimpan secara persisten di penyimpanan peramban Anda. Anda dapat me-refresh halaman dan data tidak akan hilang!
