# TAMA — Neo Camera

TAMA adalah proyek web mobile berisi halaman jam, alarm, dan kamera AR berbasis browser. Antarmuka diperbarui dengan tema gelap premium, panel glass, aksen cyan-violet, serta tata letak yang menyesuaikan layar ponsel.

## Halaman

- `index.html` — halaman utama TAMA.
- `alarm.html` — halaman alarm.
- `kamera.html` — kamera AR dengan deteksi tangan dan wajah.
- `manifest.json` — metadata instalasi web app.
- `icon.jpg` — ikon aplikasi.

## Fitur kamera

- **Portal** — efek visual yang mengikuti pose tangan.
- **Api** — efek api di area telapak tangan dengan pilihan warna dan ukuran.
- **Glow** — partikel visual dengan beberapa tema warna.
- **Gambar** — menggambar di udara menggunakan gerakan telunjuk.
- **Sensor** — overlay privasi bergaya biometrik yang mengikuti wajah.
- **Foto** — menyimpan gabungan gambar kamera dan lapisan efek.
- **Video** — merekam gabungan kamera dan lapisan efek jika browser mendukung MediaRecorder dan captureStream.

## Menjalankan

Kamera membutuhkan izin pengguna dan secure context (HTTPS atau localhost). Untuk GitHub Pages, buka:

- Beranda: https://tamayana.github.io/clock/
- Kamera: https://tamayana.github.io/clock/kamera.html
- Alarm: https://tamayana.github.io/clock/alarm.html

Buka melalui Safari atau Chrome, bukan browser dalam aplikasi pesan. Saat diminta, izinkan akses kamera. Ketersediaan perekaman video dan mode layar penuh bergantung pada dukungan browser/perangkat.

## Teknologi

- HTML, CSS, dan JavaScript
- MediaPipe Hands dan Face Mesh
- GitHub Pages

## Pengembang

- GitHub: https://github.com/tamayana
