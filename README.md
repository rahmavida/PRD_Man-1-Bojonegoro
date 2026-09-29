# PRD_Man-1-Bojonegoro

# PRODUCT REQUIREMENTS DOCUMENT (PRD)
## Website Profil MAN 1 Bojonegoro

---

## 1. Informasi Produk

| Item | Detail |
|---|---|
| Nama Produk | Website Profil Madrasah MAN 1 Bojonegoro |
| Jenis Produk | Website Informasi & Profil Institusi |
| Target Pengguna | Calon siswa, orang tua, siswa, guru/staf, alumni, masyarakat umum |
| Platform | Web Responsive |
| Tujuan | Menyediakan informasi resmi madrasah secara terstruktur, menarik, dan mudah diakses, termasuk alur pendaftaran murid baru |

---

## 2. Latar Belakang

Website ini dibuat sebagai media informasi digital untuk memperkenalkan MAN 1 Bojonegoro, **Madrasah Tahfidz, Riset dan Literasi**, kepada pengunjung

Informasi yang disediakan mencakup sejarah madrasah, sambutan kepala madrasah, visi dan misi, sarana dan prasarana, kurikulum dan peminatan, jumlah siswa, organisasi dan ekstrakurikuler, berita dan pengumuman, galeri kegiatan, alur pendaftaran murid baru (SPMB), serta informasi kontak

Website dirancang dengan satu navigasi utama yang konsisten agar pengunjung dapat mengakses seluruh informasi melalui delapan halaman: Beranda, Profil, Akademik, Kesiswaan, Berita, Galeri, SPMB, dan Kontak

---

## 3. Tujuan Produk

1. Memperkenalkan MAN 1 Bojonegoro beserta program unggulannya (Tahfidz Al-Qur'an, Riset & Literasi, Sistem Kredit Semester, Taruna Brawijaya)
2. Menampilkan sejarah, sambutan kepala madrasah, serta visi dan misi
3. Menyampaikan informasi kurikulum, program peminatan, dan jumlah siswa
4. Menampilkan kegiatan kesiswaan, yaitu OSIS dan ekstrakurikuler
5. Menyajikan berita, pengumuman, dan galeri kegiatan terbaru
6. Menjelaskan alur pendaftaran murid baru (SPMB) secara online
7. Menyediakan informasi kontak, peta lokasi, tautan media sosial, dan formulir pesan

---

## 4. Target Pengguna

**Calon Siswa**
Melihat profil madrasah, program peminatan, ekstrakurikuler, fasilitas, dan alur SPMB

**Orang Tua**
Memperoleh informasi dasar madrasah, program unggulan, alur pendaftaran, dan kontak yang dapat dihubungi

**Siswa**
Mengakses berita, pengumuman, galeri, serta informasi OSIS dan ekstrakurikuler

**Guru / Staf**
Menggunakan website sebagai media informasi identitas dan program madrasah

**Pengunjung Umum**
Memperoleh gambaran umum madrasah, lokasi, dan kabar terbaru

---

## 5. Struktur Website

Website memiliki delapan halaman utama:

```
Website Profil MAN 1 Bojonegoro
│
├── Beranda (index.html)
│   ├── Hero / Welcome
│   ├── Keunggulan Kami
│   ├── Berita Terbaru
│   ├── Pengumuman
│   └── Lokasi Kami
│
├── Profil (profil.html)
│   ├── Sejarah Sekolah
│   ├── Sambutan Kepala Sekolah
│   ├── Visi & Misi
│   ├── Sarana & Prasarana
│   └── Lokasi
│
├── Akademik (jurusan.html)
│   ├── Kurikulum
│   ├── Daftar Jurusan / Peminatan
│   ├── Program Unggulan
│   ├── Prestasi Akademik
│   └── Jumlah Siswa per Tingkatan Kelas
│
├── Kesiswaan (kesiswaan.html)
│   ├── OSIS
│   └── Ekstrakurikuler
│
├── Berita (berita.html)
│   ├── Berita
│   └── Pengumuman
│
├── Galeri (galeri.html)
│   └── Semua Foto
│
├── SPMB (ppdb.html)
│   ├── Alur Pendaftaran
│   ├── Dokumen Pendaftaran
│   ├── FAQ
│   └── Ajakan Daftar Online
│
└── Kontak (kontak.html)
    ├── Informasi Kontak
    ├── Media Sosial
    ├── Formulir Kirim Pesan
    └── Peta Lokasi
```

---

## 6. Functional Requirements

### FR-01: Navigasi dan Layout Global

Semua halaman memiliki komponen yang sama:

- **Header** berisi logo, nama madrasah, dan tagline "Madrasah Tahfidz, Riset dan Literasi". Header bersifat sticky sehingga tetap terlihat saat halaman digulir.
- **Navigasi utama** dengan delapan menu: Beranda, Profil, Akademik, Kesiswaan, Berita, Galeri, SPMB, Kontak.
- Halaman yang sedang dibuka ditandai dengan class `active` pada menu, ditampilkan dengan warna emas dan garis bawah.
- **Footer** berisi tiga kolom: identitas madrasah, tautan cepat, dan kontak singkat (alamat, telepon, email), ditambah hak cipta.

### FR-02: Halaman Beranda

**Hero Section**

Menampilkan judul "Selamat Datang di MAN 1 Bojonegoro", deskripsi singkat madrasah beserta dasar pendiriannya (SK Menteri Agama Nomor 56 Tahun 1978, 11 April 1978), foto latar madrasah, dan dua tombol aksi: **Profil Sekolah** dan **Info SPMB**.

**Keunggulan Kami**

Empat kartu program unggulan:

1. Tahfidz Al-Qur'an
2. Riset & Literasi
3. Sistem Kredit Semester
4. Taruna Brawijaya

**Berita Terbaru**

Tiga kartu berita terbaru (gambar, tanggal, judul, ringkasan, tautan "Baca selengkapnya") dan tautan menuju halaman Berita.

**Pengumuman**

Daftar lima pengumuman terbaru lengkap dengan tanggal dan tautan.

**Lokasi Kami**

Alamat singkat, tautan ke halaman Kontak, dan peta Google Maps tertanam.

### FR-03: Halaman Profil

**Sejarah Sekolah**

Ditampilkan dalam bentuk timeline:

| Tahun | Peristiwa |
|---|---|
| 1968 | Lahir berdasarkan SK Menteri Agama No. 17/1968 dengan nama SP IAIN, bertempat di Masjid Agung Darussalam Bojonegoro |
| 1978 | Didirikan berdasarkan SK Menteri Agama Nomor 56 Tahun 1978 tanggal 11 April 1978 |
| 1979/1980 | Berubah status menjadi Madrasah Aliyah Negeri, bertempat di Jalan Monginsidi 160 |
| 1998 | Ditetapkan sebagai Madrasah Aliyah Model (SK Menteri Agama RI No. IV/PP.06/KEP/174/1998) |
| 2026 | Dikenal sebagai Madrasah Tahfidz, Riset dan Literasi |

**Sambutan Kepala Sekolah**

Berisi teks sambutan mengenai pemanfaatan media sosial dan website sebagai sarana informasi dan publikasi. Kepala madrasah yang ditampilkan:

> **EKO SUPRIYANTO, M.Pd.**
> Kepala MAN 1 Bojonegoro

**Visi**

"Terwujudnya Insan Akademis Yang Unggul, Kompetitif, dan Islami."

**Misi**

Sembilan poin misi, antara lain membina anak didik dalam aqidah, syariah, dan akhlak, mengembangkan IPTEK dan seni budaya bernafaskan Islam, serta meningkatkan kualitas administrasi pendidikan, proses belajar mengajar, dan partisipasi stakeholder.

**Sarana & Prasarana**

Enam kartu fasilitas: Ruang Kelas, Laboratorium, Perpustakaan, Masjid/Mushola, Fitness & Kantin, dan Asrama.

**Lokasi**

Alamat dan peta Google Maps tertanam.

### FR-04: Halaman Akademik

**Kurikulum**

Menjelaskan penerapan Kurikulum Merdeka yang dipadukan dengan kurikulum madrasah Kementerian Agama, dengan empat komponen: mata pelajaran umum, mata pelajaran keagamaan, muatan lokal dan pengembangan diri, serta projek dan kokurikuler. Juga menjelaskan Sistem Kredit Semester (SKS) yang memungkinkan masa studi 6 semester (2 tahun).

**Program Peminatan**

Tiga peminatan:

1. **MIPA** (Matematika & Ilmu Pengetahuan Alam)
2. **IPS** (Ilmu Pengetahuan Sosial)
3. **Keagamaan**

**Program Unggulan**

1. Program SKS (Sistem Kredit Semester) dengan konsep *Personalized Learning Journey*
2. Madrasah Rintisan Taruna Brawijaya
3. Tahfidz, Riset & Literasi

**Prestasi Akademik**

184 siswa lolos PTN tanpa tes (2026).

**Jumlah Siswa**

Tabel jumlah siswa per tingkatan kelas, tahun ajaran 2026/2027:

| No | Kelas | Jumlah Siswa |
|---|---|---|
| 1 | 10 | 382 |
| 2 | 11 | 349 |
| 3 | 12 | 391 |
| | **Total** | **1122** |

### FR-05: Halaman Kesiswaan

**OSIS**

Penjelasan OSIS sebagai wadah organisasi siswa, peran OSIS (jembatan aspirasi, perencana kegiatan, pembentuk kepemimpinan dan akhlak karimah, pengembang minat dan bakat), serta mekanisme pemilihan pengurus oleh siswa.

**Ekstrakurikuler**

Dua puluh tiga ekstrakurikuler ditampilkan dalam bentuk kartu ikon:

Atletik, Basket, Bulutangkis, Cipta Baca Puisi, Desain Grafis, E-Sport, Fahmil Qur'an, Futsal, Group Studi Islam (GSI), Jurnalistik, Karate, Tahfidz Qur'an, MTQ, Musik, Paskibra, Pencak Silat, Pidato Bahasa Indonesia, Pidato Bahasa Inggris, PMR, Pramuka, Robotika, Tari, dan Tenis Meja.

### FR-06: Halaman Berita

- **Berita**: tujuh kartu berita berisi gambar, tanggal, judul, ringkasan, dan tautan "Baca selengkapnya" ke portal resmi madrasah (mansaro.sch.id). Tautan dibuka di tab baru.
- **Pengumuman**: daftar lima pengumuman terbaru dengan tanggal dan tautan.

### FR-07: Halaman Galeri

Menampilkan delapan foto dokumentasi dalam grid seragam (rasio 4:3) dengan efek zoom saat kursor diarahkan ke foto. Teks kategori (Kegiatan, Prestasi, Fasilitas, Ekstrakurikuler, Upacara, Laboratorium) ditampilkan sebagai keterangan saja dan belum berfungsi sebagai filter.

### FR-08: Halaman SPMB

**Alur Pendaftaran**

Lima langkah sesuai panduan SPMB Online MAN 1 Bojonegoro:

1. **Melakukan Pendaftaran**: registrasi di spmb.mansaro.sch.id dengan email dan password.
2. **Mengisi & Mencetak Formulir**: mengisi formulir pendaftaran, lalu mendownload formulir dan surat pernyataan untuk dicetak.
3. **Melakukan Validasi**: mengupload foto formulir dan surat pernyataan di situs SPMB.
4. **Mengikuti Ujian**: mengikuti ujian sesuai jadwal.
5. **Penyelesaian Administrasi**: dilakukan setelah dinyatakan lulus.

**Dokumen Pendaftaran**

Formulir pendaftaran dan surat pernyataan.

**FAQ**

Empat pertanyaan umum: tempat mendaftar, dokumen yang dicetak, cara validasi, dan waktu penyelesaian administrasi.

**Ajakan Daftar Online**

Tombol **Daftar Online** yang mengarah ke `https://spmb.mansaro.sch.id/` (dibuka di tab baru).

### FR-09: Halaman Kontak

**Informasi Kontak**

- Alamat: Jl. Monginsidi No. 160, Bojonegoro, Jawa Timur 62114
- Telepon: 0813-2563-9431
- Email: ptsp.man1bojonegoro@gmail.com

**Media Sosial**

Tautan ke Instagram, YouTube, dan TikTok resmi madrasah.

**Formulir Kirim Pesan**

Input yang tersedia:

- Nama Lengkap (wajib)
- Email (wajib)
- Subjek (opsional)
- Pesan (wajib)
- Tombol **Kirim Pesan**

> **Catatan implementasi:** formulir belum terhubung dengan backend atau sistem penyimpanan pesan. Form menggunakan `action="#"` dan `method="post"`, sehingga PRD ini tidak mengklaim bahwa pesan sudah benar-benar dikirim atau disimpan.

**Peta Lokasi**

Peta Google Maps tertanam.

---

## 7. Admin / Content Management

Belum tersedia untuk versi saat ini. Seluruh konten (berita, pengumuman, jumlah siswa, galeri) ditulis langsung di file HTML dan diperbarui secara manual.

---

## 8. User Flow

### Pengunjung Umum

```
Beranda
   │
   ├── Membaca keunggulan madrasah
   ├── Melihat berita terbaru & pengumuman
   │
   ▼
Profil / Akademik / Kesiswaan / Berita / Galeri
   │
   ▼
Kontak
```

### Calon Siswa & Orang Tua

```
Beranda
 │
 ├── Melihat keunggulan & profil sekolah
 │
 ▼
Profil ── sejarah, visi misi, fasilitas
 │
 ▼
Akademik ── kurikulum, peminatan, jumlah siswa
 │
 ▼
Kesiswaan ── OSIS & ekstrakurikuler
 │
 ▼
SPMB ── alur pendaftaran, dokumen, FAQ
 │
 ▼
Klik "Daftar Online" ── situs spmb.mansaro.sch.id
 │
 ▼
Kontak ── informasi kontak / formulir pesan
```

---

## 9. Non-Functional Requirements

### 9.1 Responsive Design

Website harus menyesuaikan tampilan dengan ukuran layar. Grid kartu (keunggulan, jurusan, berita, galeri, langkah SPMB) menggunakan `auto-fit` sehingga jumlah kolom menyesuaikan lebar layar otomatis.

Pada layar dengan lebar maksimal 700px:

- Header berubah menjadi susunan vertikal dan menu navigasi diratakan ke tengah.
- Layout halaman Kontak berubah menjadi satu kolom.
- Padding section dan hero dikurangi.
- Ukuran judul hero mengecil menjadi 28px.
- Dekorasi bar pada hero disembunyikan.

### 9.2 Accessibility

Website menggunakan:

- `alt` text pada gambar.
- Semantic HTML seperti `header`, `nav`, `section`, `footer`, `form`, dan `table`.
- `label` pada setiap field formulir.
- `caption` pada tabel jumlah siswa.
- Atribut `title` pada iframe peta.
- Atribut `lang="id"` pada seluruh halaman.

### 9.3 Visual Design

- Warna utama navy blue (`#0b2545`).
- Warna aksen gold (`#f4c542`).
- Background abu-abu muda (`#f4f6fa`) dan kartu putih.
- Font `Segoe UI` dengan cadangan `Arial` dan `sans-serif`.
- Layout berbasis container dengan lebar maksimum 1100px.
- Kartu dengan sudut membulat dan bayangan ringan.

---

## 10. Teknologi

| Teknologi | Penggunaan |
|---|---|
| HTML5 | Struktur halaman dan konten |
| CSS3 | Styling, layout (Flexbox & Grid), dan responsive design |
| Google Maps Embed | Peta lokasi madrasah |

Setiap halaman terhubung ke satu stylesheet bersama, `style.css`. Tidak ada JavaScript pada versi saat ini.

---

## 11. Prioritas Fitur

### MVP / Current Implementation

- Delapan halaman informasi (Beranda, Profil, Akademik, Kesiswaan, Berita, Galeri, SPMB, Kontak)
- Navigasi konsisten dan sticky header
- Responsive design
- Alur SPMB dan tautan ke situs pendaftaran
- Peta lokasi dan tautan media sosial

### Pengembangan Berikutnya

- Backend formulir kontak
- Filter kategori pada galeri
- Jadwal dan persyaratan SPMB resmi
- Database dan admin dashboard / CMS untuk berita dan pengumuman
- Peningkatan aksesibilitas (elemen `main`, `alt` text galeri yang deskriptif)

---

## 12. Struktur Project

Struktur berdasarkan file yang digunakan:

```
MAN-1-Bojonegoro
│
├── index.html
├── profil.html
├── jurusan.html
├── kesiswaan.html
├── berita.html
├── galeri.html
├── ppdb.html
├── kontak.html
├── style.css
│
├── man_1.jpeg            (latar hero)
├── gelar_karya.jpg       (berita)
├── demokrasi.jpg         (berita)
├── kualitas_guru.jpg     (berita)
├── sekolah_man.webp      (berita)
├── silaturahmi.jpg       (berita)
├── prestasi.jpg          (berita)
├── penutur.jpg           (berita & galeri)
└── galeri1.jpg – galeri7.jpg
```

Logo header dimuat dari URL eksternal (`mansaro.sch.id`), bukan dari file lokal.
