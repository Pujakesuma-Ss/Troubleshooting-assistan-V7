# PC3000E-6 Troubleshooting Assistant — V7

## Isi build
- Database pencarian berisi 42 kelompok Message yang terdeteksi dalam ekstraksi Shop Manual yang tersedia. Ini bukan klaim bahwa semua revisi manual/serial number tercakup.
- Pencarian nomor message, kata trouble, komponen, dan isi halaman yang diekstrak.
- Halaman teks sumber per message beserta nomor halaman cetak dan indeks halaman PDF.
- Alur interaktif Message -18; cabang pompa grease Step 7 telah diarahkan ke Step 8 sesuai tabel pada halaman cetak 116.
- Referensi diagram dan catatan pemeriksaan; laporan dapat disalin, diunduh sebagai TXT, atau dibagikan melalui WhatsApp.

## Batasan penting
- Diagram asli belum disematkan sebagai gambar. Buka PDF Shop Manual asli untuk membaca diagram Z27802 dan gambar lokasi komponen.
- Alur interaktif lengkap belum dibuat untuk 41 kelompok lainnya. Aplikasi menampilkan teks prosedur yang diekstrak, bukan membuat langkah diagnosis baru.
- Sebelum digunakan untuk perbaikan, cocokkan revisi manual, serial number unit, diagram, nilai ukur, dan prosedur Service Manual. Jangan menggunakan nomor terminal atau nilai yang tidak tercantum pada sumber.

## Publikasi GitHub Pages lewat Android
1. Ekstrak ZIP ini.
2. Buka repositori GitHub dan pilih Add file → Upload files.
3. Unggah isi folder ini (index.html, style.css, app.js, trouble_codes.json, README_ID.md) ke root repositori.
4. Pilih commit changes. Jika diminta, setujui penggantian file lama.
5. Buka URL GitHub Pages dan refresh.

## Struktur
- `index.html` — tampilan aplikasi
- `style.css` — gaya responsif
- `app.js` — pencarian, tampilan manual, alur Message -18, laporan
- `trouble_codes.json` — teks yang diekstrak dari Shop Manual
