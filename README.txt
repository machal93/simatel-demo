SIMATEL — Tahap 1 pemisahan lapisan tampilan

Isi:
- index.html: salinan aplikasi yang diunggah, dengan link CSS terpisah ditambahkan.
- desktop.css: lapisan CSS desktop terpisah.
- mobile.css: lapisan CSS smartphone terpisah.
- Logika JavaScript, autentikasi, fitur, dan konfigurasi Supabase di index.html tidak dipindahkan atau diubah.

Penting:
- Ini adalah tahap awal yang konservatif, bukan pemisahan penuh seluruh HTML menjadi dua aplikasi.
- Letakkan ketiga file di folder/deployment yang sama agar file CSS ditemukan.
- Sebelum mengganti situs aktif, uji salinan di staging dan pastikan URL publik tetap HTTPS.
- Tidak ada migrasi atau perubahan database.
