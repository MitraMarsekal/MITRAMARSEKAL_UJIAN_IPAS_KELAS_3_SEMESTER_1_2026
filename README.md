# Simulasi Ujian IPAS Kelas 3 Semester 1 (2026)

Aplikasi **Computer-Based Test (CBT)** berbasis web menggunakan HTML, CSS, dan JavaScript yang terhubung ke **Google Sheets** dan **Google Apps Script** sebagai penyedia soal serta penyimpan rekap hasil ujian.

## Struktur Proyek
- `index.html` — Antarmuka login/token peserta, timer hitung mundur, tampilan soal, dan hasil ujian.
- `README.md` — Dokumentasi proyek.

## Alur Singkat Penggunaan
1. Siapkan tab `Soal` dan `Hasil` pada **Google Sheets**, lalu *deploy* kode **Google Apps Script** sebagai *Web app*.
2. Masukkan URL *Web app* ke variabel `API_URL` di dalam `index.html`.
3. Unggah `index.html` ke repositori ini dan aktifkan **GitHub Pages** pada menu **Settings -> Pages** (lihat juga [GitHub Docs](https://docs.github.com/en)).
