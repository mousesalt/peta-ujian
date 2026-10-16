# Peta Ujian — Pemetaan Sesi Semester

Aplikasi web statis untuk membantu sekolah membagi siswa ke jadwal ujian berdasarkan rombel, hari, sesi, dan jumlah komputer.

## Fitur

- Pengaturan jumlah komputer (default 10 komputer).
- Enam rombel awal: Busana X, XI, XII dan DKV X, XI, XII.
- Total awal 119 siswa, dengan jumlah sementara 20, 20, 20, 20, 20, dan 19. Silakan sesuaikan jika data asli berbeda.
- Jadwal Senin–Minggu dengan Jumat otomatis nonaktif.
- Tiga sesi per hari: 08.00–09.40, 09.40–11.20, dan 11.20–13.00.
- Pembagian otomatis, dengan batas peserta tiap sesi mengikuti jumlah komputer.
- Daftar nama siswa dapat ditempel, satu nama per baris. Jika nama belum dimasukkan, aplikasi menggunakan label sementara seperti `Siswa 01`.
- Peta komputer 01–10, ekspor CSV, dan cetak / simpan ke PDF melalui dialog cetak browser.
- Pengaturan tersimpan di `localStorage` pada browser yang digunakan.

## Deploy ke GitHub Pages

1. Buat repository baru di GitHub, misalnya `peta-ujian`.
2. Unggah `index.html` ke folder utama repository. `README.md` boleh ikut diunggah.
3. Buka **Settings → Pages** pada repository.
4. Di **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/(root)`, lalu klik **Save**.
6. Tunggu sampai alamat GitHub Pages muncul pada halaman tersebut.

Aplikasi tidak membutuhkan build, framework, server, atau API key.

## Catatan penting

Data nama, jumlah siswa, dan pengaturan disimpan secara lokal di browser/perangkat tempat aplikasi dibuka. Data tidak tersinkron otomatis antarkomputer atau antarperangkat. Unduh CSV untuk menyimpan salinan jadwal. File CSV dapat dibuka di Excel atau Google Sheets.
