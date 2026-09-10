# Laporan Praktikum Modul 02: Declarative UI & Responsive Layout

- **Nama**: [fasaufa fiaunila]
- **NIM**: [362558302042]
- **Kelas / Prodi**: 2C / Sarjana Terapan TRPL
- **Mata Kuliah**: Pemrograman Perangkat Bergerak (Semester 3)

---

## 1. Ringkasan Implementasi
[Saya merancang dashboard responsif menggunakan LayoutBuilder untuk menyesuaikan tampilan berdasarkan lebar layar]

## 2. Bukti Tangkapan Layar (Running App)
| Mode Portrait (Light) | Mode Dark Theme | Mode Landscape / Tablet (2 Kolom) |
|---|---|---|
| ![Portrait](./screenshots/Cuplikan%20layar%202026-09-08%20185309.png) | ![Dark](./screenshots/Screenshot%20(77).png) | ![Wide](./screenshots/Screenshot%20(76).png) |

## 3. Kendala Layout yang Dihadapi & Solusinya
- **Kendala**: [terjadi overflow pada bagian header ketika ukuran layar itu kecil dibagian informasi semester dan ikon notifikasi itu terlalu lebar kalau pake row]
- **Solusi**: [mengganti row jadi wrap]

## 4. Jawaban Pertanyaan Refleksi
1. **Efisiensi Single-pass BoxConstraints**: [BoxConstraints membuat widget mengetahui batas ukuran yg tersedia hingga dapat menentukan ukuran dan posisi tepat dalam satu layout]
2. **Kriteria Modularisasi Widget**: [widget dipisahkan jika memiliki fungsi atau tampilan yang berbeda]
3. **Manfaat M3 ThemeData Terpusat**: [membuat tema dan warna lebih terpusat]