# Studi Kasus: Perbaikan Navbar & Grid yang Tidak Responsif (Micro-Job Focus)

Proyek ini dibuat untuk mendemonstrasikan kemampuan dalam mengidentifikasi dan memperbaiki masalah *bug* dan *layout* yang sering terjadi di *front-end* website. Masalah ini disimulasikan untuk menargetkan segmen *micro-job* perbaikan cepat.

## 🔗 Tautan Proyek

| Deskripsi | Tautan |
| :--- | :--- |
| **Versi dengan Bug (Before)** | [Lihat Versi ERROR (Halaman Index)](https://yafigian3-hue.github.io/Studi-Kasus-Solusi-Perbaikan-Layout-Responsif-Navbar/) |
| **Versi Sudah Diperbaiki (After)** | [Lihat Versi FIXED (Halaman Solusi)](https://yafigian3-hue.github.io/Studi-Kasus-Solusi-Perbaikan-Layout-Responsif-Navbar/fixed.html) |

---

## 🛠️ Penjelasan Teknis Perbaikan

Masalah utama pada proyek ini adalah *layout overflow* pada *mobile* dan *grid* yang tidak *wrap* dengan benar.

* **Masalah Navbar:** Navbar dibuat tidak responsif dan menyebabkan *overflow* di layar kecil.
    * **Solusi:** Bug *navbar* diperbaiki dengan menerapkan `display: flex` yang benar dan `media queries` untuk *toggle* menu hamburger pada ukuran layar tertentu.
* **Masalah Grid:** Kolom *grid* dibuat dengan lebar paksa yang menyebabkan *layout* "meledak" di *mobile*.
    * **Solusi:** *Grid* diperbaiki dengan menambahkan *breakpoint* **`sm:grid-cols-1`** di TailwindCSS. Ini memastikan *grid* berubah menjadi kolom tunggal, sehingga tampil rapi di perangkat *mobile*.

## ⭐ Keunggulan yang Ditunjukkan

Proyek ini menyoroti kemampuan saya dalam:

1.  **Diagnosis Cepat:** Mampu mengidentifikasi sumber masalah (*bug*) secara spesifik (width paksa, kurangnya *wrap*).
2.  **Perbaikan Bersih:** Menggunakan TailwindCSS untuk menghasilkan kode perbaikan yang efisien dan rapi.
3.  **Fokus pada Responsif:** Memastikan tampilan sempurna di semua ukuran layar (desktop, tablet, *mobile*).
