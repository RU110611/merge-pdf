# Merge PDF
Aplikasi web ringan untuk menggabungkan beberapa file PDF menjadi satu file cuma lewat browser.

**Live Demo:** https://ru110611.github.io/merge-pdf/

## Fitur Utama
- **100% Aman & Privat:** Seluruh proses penggabungan dilakukan secara lokal di browser (*client-side*). File PDF tidak pernah dikirim atau disimpan ke server mana pun.
- **Drag & Drop:** Tarik file langsung ke area upload atau tambahkan file secara bertahap.
- **Atur Urutan Fleksibel:** Geser (*drag*) daftar file untuk mengatur urutan halaman, atau klik kotak nomor biru untuk langsung melompat ke urutan tujuan.
- **Custom Nama File:** Ubah nama dokumen hasil penggabungan sebelum di-download.

## Teknologi yang Digunakan
- HTML5, CSS3, & Vanilla JavaScript
- [pdf-lib](https://pdf-lib.js.org/) — Pemrosesan dan penggabungan file PDF
- [SortableJS](https://sortablejs.github.io/Sortable/) — Pengaturan urutan *drag-and-drop*

## Cara Menjalankan di Lokal
1. Clone repository ini:
   ```bash
   git clone [https://github.com/RU110611/merge-pdf.git](https://github.com/RU110611/merge-pdf.git)
   ```
2. Buka file `index.html` langsung menggunakan browser.
