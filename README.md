# Profil LPM Gema Alpas Universitas Pancasila

## Penulis

Dibuat oleh **Satria Mahardika**, mahasiswa Teknik Informatika Universitas Pancasila.

**NPM:** 4525210068

## Deskripsi Singkat

Proyek ini merupakan halaman web profil organisasi kampus yang dibuat menggunakan HTML untuk memperkenalkan **Lembaga Pers Mahasiswa (LPM) Gema Alpas Universitas Pancasila**. 

Halaman web ini menyajikan informasi lengkap mulai dari profil lembaga, galeri foto, rubrik redaksi, alur pendaftaran, hingga kontak resmi redaksi.

## Struktur Halaman

### 1. Header

Bagian header berada di paling atas halaman yang memuat judul utama lembaga, deskripsi singkat, serta menu navigasi cepat.

Kode yang digunakan:

```html
<header id="atas">
    <h1>LPM Gema Alpas</h1>
    <p>Lembaga Pers Mahasiswa Gerakan Mahasiswa Almamater Pancasila Universitas Pancasila.</p>
    <nav>
        <a href="#tentang">Tentang</a> | 
        <a href="#kegiatan">Redaksi</a> | 
        <a href="#alur">Pendaftaran</a> | 
        <a href="#kontak">Kontak</a> | 
        <a href="https://lpmgemaalpas.com" target="_blank">Website Resmi</a>
    </nav>
</header>
```

### 2. Profil Lembaga

Bagian ini berisi penjelasan sejarah singkat serta bidang fokus dari LPM Gema Alpas menggunakan tag ``<section>``, ``<h2>``, ``<h3>``, ``<p>``, dan ``<ul>``.

```html
<section id="tentang">
    <h2>Profil Lembaga</h2>
    <p>Gema Alpas adalah Lembaga Pers Mahasiswa di Universitas Pancasila yang berdiri sejak tahun 1982 dan bergerak di bidang jurnalistik.</p>
    <p>Kami berkomitmen menyajikan informasi yang <strong>objektif</strong> &amp; <em>kritis</em>.<br>Setiap karya tulis melalui proses kurasi ketat demi menjaga kualitas pemberitaan kampus.</p>
    
    <h3>Bidang Fokus</h3>
    <ul>
        <li>Jurnalistik dan Penulisan Berita</li>
        <li>Peliputan Isu Nasional &amp; Kampus</li>
        <li>Media Kreatif dan Publikasi</li>
    </ul>
</section>
```

### 3. Foto Dokumentasi

Bagian ini menampilkan dokumentasi visual berupa foto gedung rektorat dan logo lembaga menggunakan tag <img> yang dilengkapi atribut alt

```html
<section id="kegiatan">
    <h2>Foto gedung &amp; Logo LPM Gema Alpas</h2>
    <p>Gedung rektorat dan juga Logo LPM Gema Alpas.</p>
    <p>Dokumentasi visual ini merepresentasikan tempat berprosesnya para awak redaksi dalam mengembangkan bakat jurnalistik mereka.</p>
    <img src="https://cdn.antaranews.com/cache/1200x800/2024/02/04/Universitas-Pancasila1.jpg" alt="Gedung Rektorat" width="350">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQO31A6yGYsNLkZWxvUku7xv0zWSQdcxutiWzCThaNwnI6pMQdJFfrDePty&s=10" alt="Logo LPM Gema Alpas" width="350">
</section>
```

### 4. Rubrik Utama Redaksi

Bagian ini menampilkan rubrik-rubrik yang dikelola oleh redaksi menggunakan description list ``<dl>``, ``<dt>``, ``<dd>``.Isu Nasional: Kajian dan peliputan seputar isu-isu aktual di Indonesia.Opini: Wadah tulisan kritis dan pandangan mahasiswa.Kampus: Informasi dan berita kegiatan akademik Universitas Pancasila.

### 5. Alur Pendaftaran Anggota Baru

Berisi tahapan seleksi atau pendaftaran bagi mahasiswa yang ingin bergabung ke dalam awak redaksi, dibuat menggunakan ordered list ``<ol>`` dan ``<li>``.Mengakses tautan pendaftaran terbuka pers mahasiswa.Mengikuti peliputan uji coba atau diklat jurnalistik dasar.Wawancara kompetensi dasar menulis dan peliputan.Pengukuhan dan bergabung di awak redaksi Gema Alpas.

### 6. Kontak & Media Sosial

Bagian ini menyediakan akses komunikasi langsung dengan redaksi melalui email (mailto:) dan tautan eksternal Instagram.

```html
<section id="kontak">
    <h2>Kontak &amp; Media Sosial</h2>
    <p>Hubungi redaksi kami melalui tautan di bawah ini:</p>
    <ul>
        <li>Email Redaksi: <a href="mailto:lpmgemaalpas1982@gmail.com">lpmgemaalpas1982@gmail.com</a></li>
        <li>Instagram: <a href="[https://instagram.com/gemaalpas](https://instagram.com/gemaalpas)" target="_blank">@gemaalpas</a></li>
    </ul>
</section>
```

### 7. Footer

Bagian paling bawah halaman yang berisi hak cipta dan tombol pintasan kembali ke bagian atas halaman (#atas).

```html
<footer>
    <hr>
    <p>&copy; 2026 LPM Gema Alpas Universitas Pancasila</p>
    <p><a href="#atas">Kembali ke atas</a></p>
</footer>
```

Tag HTML yang Digunakan

| Tag HTML | Fungsi |
| :--- | :--- |
| `<!DOCTYPE html>` | Menentukan dokumen menggunakan standar HTML5 |
| `<html>` | Elemen akar utama dokumen |
| `<head>` | Menyimpan metadata dan judul halaman |
| `<title>` | Judul yang tampil pada tab browser |
| `<body>` | Konten utama yang ditampilkan pada web |
| `<header>` & `<footer>` | Bagian kepala dan kaki halaman |
| `<nav>` | Memuat tautan navigasi menu |
| `<section>` | Mengelompokkan bagian konten |
| `<h1>` - `<h3>` | Tingkatan judul teks (*heading*) |
| `<p>` | Membuat paragraf teks |
| `<a>` | Membuat tautan (*hyperlink, anchor, mailto*) |
| `<img>` | Menyisipkan gambar ke dalam web |
| `<ul>` & `<ol>` | Membuat daftar tidak berurutan dan berurutan |
| `<li>` | Item di dalam list |
| `<dl>`, `<dt>`, `<dd>` | Membuat daftar deskripsi istilah |
| `<strong>` & `<em>` | Menebalkan dan memiringkan teks |
| `<br>` | Menambahkan baris baru (*line break*) |

### Cara Menjalankan Proyek

1. Unduh atau clone repositori proyek ini ke komputer Anda.
2. Buka folder proyek menggunakan aplikasi Visual Studio Code.
3. Pastikan file utama HTML tersimpan dengan benar.
4. Klik dua kali pada file HTML atau jalankan menggunakan ekstensi Live Server di VS Code.
5. Halaman web profil LPM Gema Alpas akan terbuka di browser Anda.

### Tampilan HTML
<img width="566" height="820" alt="image" src="https://github.com/user-attachments/assets/85be0f3b-0bc5-4861-b816-943f441dc03e" />


### Kesimpulan

Proyek ini dirancang untuk menerapkan dasar-dasar pengembangan web menggunakan HTML murni. Seluruh komponen tugas seperti struktur dokumen, penggunaan minimal dua gambar dengan atribut alt, empat jenis link (anchor internal, eksternal, dan mailto), serta tiga tipe list (``<ul>``, ``<ol>``, dan ``<dl>``) telah diterapkan secara optimal.
