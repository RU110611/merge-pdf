# Merge PDF
Aplikasi web ringan untuk menggabungkan beberapa file PDF menjadi satu file cuma lewat browser.

**Live Demo:** https://ru110611.github.io/merge-pdf/

## Fitur Utama
- **Privat & Aman (*Client-Side*):** Seluruh proses pengolahan dilakukan secara lokal di browser. File PDF tidak dikirim atau disimpan ke server mana pun.
- **Drag & Drop:** Tarik file langsung ke area upload atau tambahkan beberapa file secara bertahap.
- **Pilih Halaman & Pratinjau Visual:** Tentukan halaman tertentu (misal `1-3, 5`), pilih cepat halaman ganjil/genap, serta lihat *thumbnail* dan *zoom* tiap halaman sebelum digabung.
- **Atur Urutan Fleksibel:** Geser (*drag*) daftar file untuk mengatur urutan, atau klik kotak nomor biru untuk langsung melompat ke posisi urutan tujuan.
- **Custom Nama & Ekspor ZIP:** Ubah nama dokumen hasil penggabungan dan pilih output langsung sebagai `.pdf` atau dibungkus ke dalam arsip `.zip`.
  
## Teknologi yang Digunakan
- HTML5, CSS3, & Vanilla JavaScript
- [pdf-lib](https://pdf-lib.js.org/) — Pemrosesan dan penggabungan halaman PDF
- [PDF.js](https://mozilla.github.io/pdf.js/) — Rendering pratinjau (*thumbnail* dan *zoom*) halaman PDF
- [SortableJS](https://sortablejs.github.io/Sortable/) — Pengaturan urutan *drag-and-drop* dengan *auto-scroll*
- [JSZip](https://stuk.github.io/jszip/) — Pengemasan file hasil ke format arsip `.zip`

## Cara Menjalankan di Lokal
1. Clone repository ini:
   ```bash
   git clone [https://github.com/RU110611/merge-pdf.git](https://github.com/RU110611/merge-pdf.git)
   ```
2. Buka file `index.html` langsung menggunakan browser (atau jalankan lewat server lokal seperti XAMPP/Live Server).
