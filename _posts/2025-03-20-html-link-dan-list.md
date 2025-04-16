---
layout: post
title: "HTML: Link dan Daftar"
date: 2025-03-20
---

Materi dasar mengenai penggunaan tautan dan daftar dalam HTML.

# 🔗 Memahami Link & Daftar dalam HTML

## 🤔 Apa Itu Link dalam HTML?

**Link** (tautan) adalah elemen yang digunakan untuk menghubungkan satu halaman ke halaman lainnya, baik dalam situs web yang sama ataupun menuju situs web eksternal.

### 📌 Tag yang Digunakan:
- `<a>`: Tag anchor yang digunakan untuk membuat hyperlink

### ✅ Contoh Penggunaan Link

- **Link ke halaman lain**:
  ```html
  <a href="about.html">Tentang Kami</a>

<!-- Link ke situs luar -->
<a href="https://www.google.com" target="_blank">Cari di Google</a>

<!-- Link ke bagian tertentu dalam halaman -->
<a href="#kontak">Lompat ke Bagian Kontak</a>

<!-- Elemen target -->
<h2 id="kontak">Kontak Kami</h2>

---

## 🧾 Apa Itu List dalam HTML?

**List** (daftar) adalah elemen HTML yang digunakan untuk menampilkan item dalam urutan tertentu atau tanpa urutan.

### 📌 Jenis-Jenis List di HTML:

| Jenis List        | Tag          | Deskripsi                                 |
|-------------------|--------------|-------------------------------------------|
| **Ordered List**  | `<ol>`       | Daftar dengan urutan (nomor)             |
| **Unordered List**| `<ul>`       | Daftar tanpa urutan (bullet points)       |
| **Description List**| `<dl>`     | Daftar definisi atau keterangan           |

---

### ✅ Contoh Ordered List (Daftar Terurut)

```html
<ol>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ol>


### ✅ Contoh Unordered List


<ul>
  <li>Blog</li>
  <li>Galeri</li>
  <li>Kontak</li>
</ul>


### ✅ Contoh Description List


<dl>
  <dt>HTML</dt>
  <dd>Bahasa markup untuk web</dd>

  <dt>CSS</dt>
  <dd>Bahasa untuk desain tampilan</dd>
</dl>


---

## 🎯 Tips Penggunaan Link & List

- Gunakan `target="_blank"` untuk membuka link di tab baru.
- Tambahkan `title` pada tag `<a>` untuk memberi informasi tambahan saat hover.
- Gunakan list untuk menyusun menu navigasi.
- Nesting list di dalam list untuk membuat submenu atau daftar berjenjang.

---

## ✅ Kesimpulan

- **Link (`<a>`)** penting untuk menghubungkan halaman dan membuat situs web mudah dinavigasi.
- **List (`<ul>`, `<ol>`, `<dl>`)** membantu menampilkan informasi dalam bentuk yang rapi dan terstruktur.
- Keduanya merupakan elemen HTML dasar yang sering digunakan dalam berbagai layout dan konten situs.

> 💡 Kuasai tag `<a>`, `<ul>`, `<ol>`, dan `<li>` agar kamu bisa membangun struktur navigasi dan konten yang baik dalam halaman web!