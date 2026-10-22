SIMATEL — paket prototipe online
=================================

Isi:
- index.html : prototipe SIMATEL, data simulasi saja.

Cara menerbitkan melalui Vercel:
1. Buat repositori GitHub BARU bernama simatel-demo.
2. Unggah index.html ke root repositori.
3. Buka https://vercel.com/ lalu masuk dengan akun Anda.
4. Pilih Add New > Project, lalu impor repositori simatel-demo.
5. Untuk prototipe statis ini, biarkan pengaturan build default/kosong jika Vercel mengenalinya sebagai static site, lalu klik Deploy.
6. Setelah deployment selesai, Vercel akan memberikan URL *.vercel.app.

Penting:
- Ini hanya prototipe frontend, bukan aplikasi produksi.
- Tidak ada autentikasi sungguhan atau database terpusat.
- Jangan masukkan data inventaris nyata, dokumen sensitif, username/password perangkat, atau informasi operasi.
- Sebelum penggunaan instansi, siapkan login, kontrol akses, Supabase RLS, storage privat, audit log, dan persetujuan keamanan TI.
