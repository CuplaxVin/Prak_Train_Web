# Review & Penjelasan Kode HTML -- Tabel Mahasiswa

Dokumen ini berisi **penjelasan dan koreksi deskriptif** dari kode HTML
yang dibuat secara mandiri.\
Tidak ada perubahan penulisan kode yang dilakukan, hanya analisis
struktur dan konsep.

---

# 1. Struktur HTML Utama

Struktur dokumen sudah mengikuti standar HTML5:

- `<!doctype html>`
- `<html>`
- `<head>`
- `<body>`

`<!doctype html>` memberi tahu browser bahwa dokumen menggunakan
**HTML5**.

---

# 2. Bagian Head

Di dalam `<head>` terdapat:

- `meta charset`
- `meta viewport`
- `title`
- `style`

**meta charset** Digunakan agar browser membaca karakter sebagai
**UTF‑8**.

**meta viewport** Digunakan agar halaman dapat tampil **responsif pada
perangkat mobile**.

**title** Menentukan judul halaman yang muncul di **tab browser**.

**style** Saat ini masih kosong, sehingga belum ada styling yang
diterapkan.

---

# 3. Struktur Semantik HTML

Elemen semantik yang digunakan:

- `header`
- `main`
- `section`
- `footer`

Ini merupakan praktik yang baik karena:

- membuat struktur halaman lebih jelas
- membantu SEO
- membantu screen reader memahami halaman

---

# 4. Header Halaman

Di dalam `header` terdapat elemen `h1` yang berfungsi sebagai **judul
utama halaman** yaitu _Tabel Mahasiswa_.

Setiap halaman idealnya memiliki satu `h1`, sehingga penggunaan ini
sudah tepat.

---

# 5. Deskripsi Awal Tabel

Sebelum tabel terdapat paragraf yang menjelaskan isi tabel.

Ini merupakan praktik yang baik karena memberikan **konteks kepada
pembaca sebelum melihat data tabel**.

Urutan konten sudah logis:

1.  Judul
2.  Penjelasan
3.  Tabel

---

# 6. Struktur Tabel Mahasiswa

Komponen tabel yang digunakan:

- `table`
- `thead`
- `tbody`
- `tr`
- `th`
- `td`

Penjelasan:

**thead** Menampung bagian header tabel.

**tr** Membuat baris tabel.

**th** Digunakan sebagai judul kolom.

**tbody** Menampung isi data tabel.

**td** Digunakan untuk data pada tabel.

Struktur ini sudah benar untuk tabel HTML.

---

# 7. Isi Data Mahasiswa

Data tabel berisi:

- Nama
- NIM
- Mata Kuliah
- Nilai
- Status

Setiap mahasiswa dibuat dalam satu baris `tr` dengan beberapa `td`.

Ini menunjukkan pemahaman tentang **struktur data tabular**.

---

# 8. Logika Status Kelulusan

Terdapat aturan dalam deskripsi:

> Nilai 60 ke atas dianggap lulus.

Ini menunjukkan pemikiran tentang **logika data**, walaupun masih
ditulis secara manual dalam HTML.

---

# 9. Section Deskripsi Tabel

Terdapat section khusus yang menjelaskan isi tabel.

Hal ini baik karena memisahkan:

- data
- penjelasan

Class pada section juga menunjukkan persiapan untuk **penggunaan CSS**
di masa depan.

---

# 10. Tabel Perhitungan

Di bagian akhir terdapat tabel kedua yang berisi:

- Total Mahasiswa
- Total Lulus
- Total Tidak Lulus

Ini menunjukkan pemahaman konsep **ringkasan data (summary)**.

Namun secara struktur, tabel ini tidak menggunakan:

- `thead`
- `tbody`

Walaupun tidak salah secara teknis, struktur tabel bisa dibuat lebih
konsisten.

---

# 11. Konsistensi Struktur Tabel

Tabel pertama memiliki struktur lengkap (`thead` dan `tbody`).

Tabel kedua langsung menggunakan `tr` tanpa struktur tambahan.

Browser tetap dapat menampilkan tabel dengan benar, tetapi dari sisi
**konsistensi struktur HTML** masih dapat ditingkatkan.

---

# 12. Footer

Bagian `footer` berisi teks:

_Tabel Mahasiswa 2026_

Ini berfungsi sebagai penutup halaman dan sudah sesuai dengan struktur
layout HTML modern.

---

# 13. Komentar dalam Kode

Kode juga memiliki komentar seperti:

- table header
- table content
- describe table

Komentar membantu:

- memahami struktur kode
- memudahkan pembacaan kode
- mempermudah debugging

---

# 14. Penilaian Keseluruhan

Kelebihan:

- Struktur HTML sudah benar
- Menggunakan elemen semantik
- Struktur tabel jelas
- Data tertata rapi
- Ada deskripsi tabel
- Ada ringkasan perhitungan
- Ada komentar kode

Hal yang bisa ditingkatkan:

- konsistensi struktur tabel
- pemanfaatan CSS
- pemisahan CSS jika proyek mulai berkembang

---

# 15. Kesimpulan

Kode yang dibuat sudah menunjukkan pemahaman tentang:

- struktur dasar HTML
- penggunaan tabel
- penyusunan data
- struktur halaman yang logis

Untuk latihan mandiri tanpa bantuan AI, hasil ini sudah **baik untuk
level frontend beginner**.
