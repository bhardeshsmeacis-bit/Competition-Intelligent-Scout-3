# Competition Intelligent Scout 3

**Competition Intelligent Scout 3 (CIS 3)** adalah halaman informasi dan pusat tautan perlombaan Pramuka yang diselenggarakan oleh **Ambalan Bhatara Rama & Dewi Shinta**, Gugus Depan Ciamis **01-139 & 01-140**.

Halaman utama menampilkan formulir pendaftaran, unduhan formulir, petunjuk perlombaan, Instagram, dan kontak WhatsApp panitia.

> “mengukir prestasi berasama praja”

## Fitur halaman

- Identitas CIS 3, ambalan, dan gugus depan
- Unduhan **Formulir Pendaftaran CIS III** dalam format DOCX
- Tautan Google Forms untuk:
  - Lomba Paskat
  - Lomba Mini Pionering
  - Lomba Dance Semaphore
- Tautan **Juklak & Juknis Perlombaan**
- Tautan Instagram `@intelligentscout_3`
- Dialog **Hubungi Panitia** dengan dua tautan WhatsApp:
  - Panitia Utama — informasi perlombaan
  - Wakil Panitia Utama — pendaftaran dan bantuan
- Layar pemuatan selama dua detik dan dekorasi ikon Pramuka bergerak
- Tampilan responsif, indikator fokus keyboard, dan dukungan sebagian untuk `prefers-reduced-motion`

## Teknologi

- HTML5 untuk struktur halaman
- CSS internal pada `index.html` untuk tampilan dan animasi
- JavaScript vanilla untuk layar pemuatan, dekorasi, dan dialog WhatsApp
- SVG inline untuk ikon WhatsApp dan Instagram

Tidak ada framework, dependensi, atau proses build yang diperlukan.

## Struktur project

```text
Competition-Intelligent-Scout-3/
├── index.html
├── cis.png
├── FORM PENDAFTARAN CIS III.docx
├── WhatsApp Image 2026-08-19 at 20.01.42.jpeg
└── README.md
```

`cis.png` digunakan sebagai logo yang tampil di halaman. Berkas JPEG saat ini tidak dirujuk oleh `index.html`.

## Menjalankan website

Website ini statis. Buka `index.html` langsung di browser, atau jalankan folder project menggunakan ekstensi **Live Server** di VS Code. Pastikan `cis.png` dan berkas DOCX tetap berada di folder yang sama dengan `index.html`.

**Catatan:** tautan **Juklak & Juknis Perlombaan** pada halaman mengarah ke `juknis.html`, tetapi berkas tersebut belum tersedia di project. Tautan itu baru dapat digunakan setelah `juknis.html` ditambahkan.

## Kontak panitia

- **Panitia Utama:** +62 819-1079-3125
- **Wakil Panitia Utama:** +62 821-1855-0966

## Lisensi

Project ini dibuat untuk mendukung kegiatan **Competition Intelligent Scout 3**.

© 2026 Competition Intelligent Scout 3

Kreativitas • Inovasi • Solidaritas
