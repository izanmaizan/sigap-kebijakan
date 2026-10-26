# Kebijakan Privasi — SIGAP RSUD M. Natsir

**Berlaku sejak:** 26 Oktober 2026

**SIGAP** (Sistem Informasi Gerakan Aktivitas Pegawai) adalah aplikasi kepegawaian internal **RSUD Mohammad Natsir Solok** untuk absensi, jadwal shift, apel, laporan kinerja harian (LKH), izin/cuti, dan penilaian kinerja (KPI). Aplikasi hanya untuk pegawai RSUD. Akun dibuat oleh admin RS, bukan oleh pengguna sendiri.

## Pengelola data
RSUD Mohammad Natsir Solok, Sumatera Barat. Kontak: izanmaizan@gmail.com

## Data yang dikumpulkan dan tujuannya

| Data | Kapan | Tujuan |
|---|---|---|
| Nama, NIP/username, jabatan, unit kerja, status kepegawaian | Akun dibuat admin | Identitas dan hak akses |
| Kata sandi (disimpan sebagai hash) | Login / ganti sandi | Autentikasi |
| **Lokasi tepat (GPS)** | Hanya saat Anda menekan absen masuk/pulang atau mengajukan absensi luar | Memastikan absen dilakukan di area kerja yang ditentukan RS |
| **Foto/kamera** | Saat apel, validasi atribut seragam, atau absensi luar | Bukti kehadiran dan kelengkapan atribut |
| Waktu absen, jadwal shift, LKH, izin/cuti, banding, nilai KPI | Saat Anda mengisi | Fungsi inti aplikasi dan penilaian kinerja |
| Token notifikasi (Firebase Cloud Messaging) | Setelah Anda mengizinkan notifikasi | Mengirim pengingat absen dan pemberitahuan |
| Alamat IP dan log aktivitas (login, perubahan data) | Otomatis | Keamanan dan audit |

Aplikasi **tidak** mengumpulkan lokasi di latar belakang, tidak memuat iklan, dan tidak menjual atau membagikan data ke pihak ketiga untuk tujuan komersial.

## Pihak ketiga
- **Google Firebase Cloud Messaging**: mengantar notifikasi (menerima token perangkat).
- **Google Play**: distribusi aplikasi.

Data lain disimpan di server milik RSUD M. Natsir dan hanya dapat diakses pegawai berwenang (atasan langsung, admin kepegawaian, manajemen) sesuai peran.

## Keamanan
Akses memakai login dan token berotorisasi. Kata sandi disimpan dalam bentuk hash. Perlu diketahui: sambungan aplikasi ke server RS saat ini belum memakai HTTPS penuh, sehingga data dikirim tanpa enkripsi transport. RS berencana migrasi ke HTTPS.

## Penyimpanan dan penghapusan
Data kepegawaian disimpan selama masa kerja dan sesuai kebutuhan arsip kepegawaian/kinerja RS. Pegawai dapat meminta koreksi atau penghapusan data (termasuk akun) melalui admin kepegawaian RSUD M. Natsir atau email di atas. Data yang wajib diarsipkan oleh aturan kepegawaian tidak dapat dihapus lebih awal.

## Izin yang diminta aplikasi
Kamera, lokasi (saat aplikasi digunakan), notifikasi, alarm terjadwal (pengingat absen), dan getar. Semua dapat dicabut di pengaturan perangkat; fitur terkait (absen, apel) tidak akan berfungsi tanpa izin lokasi/kamera.

## Anak-anak
Aplikasi hanya untuk pegawai dewasa dan tidak ditujukan bagi anak di bawah 18 tahun.

## Perubahan kebijakan
Perubahan diumumkan di halaman ini dengan tanggal baru.
