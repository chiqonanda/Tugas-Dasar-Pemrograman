<a name="top"></a>

<div align="center">

<img src="documentation/readme-screenshots/00-readme-banner.png" alt="Banner README Desa Wisata Budaya Pampang" width="1100">

</div>

<p align="center">
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap 5" />
  <img src="https://img.shields.io/badge/Vue-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" alt="Vue" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
</p>

<h1 id="judul-utama">Desa Wisata Budaya Pampang — Situs Web Profil Wisata</h1>

Repositori ini memuat dokumentasi resmi pengembangan situs web profil wisata **Desa Wisata Budaya Pampang** di Samarinda untuk kebutuhan Proyek Akhir PBW. Implementasi disusun dengan pendekatan PHP native berbasis MVC (custom framework), MySQL sebagai basis data, Bootstrap 5 untuk antarmuka responsif, serta Vue dan JavaScript pada komponen interaktif tertentu.

---

## Daftar Isi

- [Daftar Isi](#daftar-isi)
- [Deskripsi Situs Web](#deskripsi-situs-web)
- [Kunjungi Website Pampang](#kunjungi-website-pampang)
- [Profil Mitra](#profil-mitra)
- [Profil Kelompok](#profil-kelompok)
- [Peta Laman Dan Arsitektur Informasi](#peta-laman-dan-arsitektur-informasi)
- [Fitur Utama Situs](#fitur-utama-situs)
- [Struktur Proyek](#struktur-proyek)
- [Cuplikan Antarmuka Situs](#cuplikan-antarmuka-situs)
- [Verifikasi Kesesuaian Instruksi Proyek Akhir](#verifikasi-kesesuaian-instruksi-proyek-akhir)

---

## Deskripsi Situs Web

Situs web ini dirancang sebagai media informasi publik Desa Wisata Budaya Pampang, mencakup profil desa, agenda kegiatan budaya, publikasi dan berita, dokumentasi visual, serta informasi lokasi dan kontak pengelola. Struktur penyajian diprioritaskan agar ringkas, mudah dipindai, dan tetap informatif pada perangkat desktop maupun seluler.

Dalam konteks instruksi proyek PBW, komponen *detail wisata* direalisasikan melalui pemetaan multi-laman, yaitu **Tentang**, **Publikasi**, serta **Kontak**. Seluruh konten dikelola melalui panel admin dengan CRUD penuh untuk postingan, agenda, galeri, dan informasi kontak. Pendekatan ini dipilih agar setiap kelompok informasi memiliki ruang penjelasan yang lebih jelas dan tidak menumpuk pada satu halaman panjang.

---

## Kunjungi Website Pampang

Jika Anda ingin melihat pengalaman lengkapnya secara langsung, kunjungi website resmi Desa Wisata Budaya Pampang di:

<p align="center">
  <a href="http://desawisatabudayapampang">
    <img src="https://img.shields.io/badge/Kunjungi%20Website-desawisatabudayapampang-2e7d32?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Kunjungi website Desa Wisata Budaya Pampang" />
  </a>
</p>

Website ini dirancang agar pengunjung dapat memahami kekayaan budaya Desa Pampang dengan cepat melalui alur yang ringkas: mulai dari pengenalan profil desa, agenda pertunjukan budaya, publikasi dan galeri, hingga informasi kontak dan lokasi. Untuk pembaca repositori, kunjungan langsung ke situs akan memberi gambaran paling jelas tentang kualitas implementasi antarmuka, struktur informasi, dan pengalaman pengguna yang dibangun dalam proyek ini.

---

## Profil Mitra

**Desa Wisata Budaya Pampang** merupakan mitra studi kasus pada proyek ini. Desa Pampang dikenal sebagai salah satu destinasi wisata budaya unggulan di Samarinda yang merepresentasikan kehidupan dan kebudayaan suku Dayak Kenyah secara autentik.

Desa Pampang berlokasi di Samarinda, Kalimantan Timur. Dalam operasionalnya, desa wisata ini menyelenggarakan pertunjukan tarian tradisional, pameran kerajinan tangan, dan kegiatan budaya lainnya secara rutin. Situs web ini disusun untuk menjawab kebutuhan informasi publik yang paling sering dicari pengunjung: profil dan konteks wisata, jadwal agenda kegiatan, dokumentasi visual, publikasi berita, serta kanal komunikasi resmi pengelola.

---

## Profil Kelompok

| NIM | Nama | Kelas |
|:---:|:---:|:---:|
| 2409116045 | Muhammad Rizky Febrianto | Sistem Informasi B 2024 |
| 2409116046 | Chiqo Nanda Rial Pratama | Sistem Informasi B 2024 |
| 2409116069 | Daffa Syahrani Husain | Sistem Informasi B 2024 |
| 2409116072 | Marcela | Sistem Informasi B 2024 |

---

## Peta Laman Dan Arsitektur Informasi

| Kelompok Laman | URL | Peran Informasi |
|---|---|---|
| Publik | `/` | Ringkasan awal situs, agenda terkini, galeri, dan postingan unggulan |
| Publik | `/tentang` | Profil desa, latar sejarah, dan narasi wisata budaya |
| Publik | `/publikasi` | Galeri dokumentasi visual dan artikel/berita kegiatan desa |
| Publik | `/kontak` | Peta, alamat, jam operasional, serta kanal komunikasi pengelola |
| Admin | `/login` | Titik masuk autentikasi admin |
| Admin | `/admin` | Dashboard pengelolaan ringkasan data |
| Admin | `/admin/postingan` | Manajemen artikel dan berita (CRUD) |
| Admin | `/admin/agenda` | Manajemen jadwal kegiatan budaya (CRUD) |
| Admin | `/admin/galeri` | Manajemen foto dokumentasi (CRUD + upload) |
| Admin | `/admin/kontak` | Pengelolaan informasi kontak dan operasional |
| Admin | `/admin/password` | Pengaturan keamanan akun admin |

---

## Fitur Utama Situs

| Fitur | Uraian |
|---|---|
| Profil Desa Wisata | Menyajikan identitas Desa Pampang, latar budaya, dan konteks informasi publik |
| Agenda Kegiatan | Menampilkan jadwal pertunjukan budaya dan acara desa secara terstruktur |
| Publikasi & Galeri | Menyediakan artikel berita dan dokumentasi visual kegiatan desa |
| Informasi Kontak | Menyediakan alamat, jam operasional, harga tiket, dan jalur komunikasi pengelola |
| Manajemen Konten Admin | CRUD penuh untuk postingan, agenda, galeri (file/URL), dan data kontak |
| Upload Gambar | Mendukung unggahan file gambar (JPG/PNG/WEBP/GIF, maks. 5MB) dan input URL eksternal |
| Autentikasi Admin | Login berbasis session dengan regenerasi ID session dan proteksi session fixation |
| Ganti Password Admin | Fitur ubah password dengan validasi password lama dan konfirmasi password baru |
| Arsitektur MVC | Custom framework PHP native dengan pemisahan Controller, Model, View, dan Router |
| Error Handling | Halaman error khusus (404, 500, dll.) dengan pesan berbahasa Indonesia |

---

## Struktur Proyek

<details>
<summary><b>Struktur Folder Inti (Ringkas)</b></summary>

```text
desa-wisata-pampang/
├── app/
│   ├── core/                  # Komponen inti framework
│   │   ├── bootstrap.php      # Entry point, autoloader, dan inisialisasi routing
│   │   ├── Controller.php     # Base controller (view, redirect, session, JSON)
│   │   ├── Database.php       # Singleton database dengan konfigurasi ENV
│   │   └── Router.php         # Router berbasis array dengan error handling
│   ├── controllers/           # Pengendali alur request per modul
│   │   ├── AdminController.php
│   │   ├── AgendaController.php
│   │   ├── AuthController.php
│   │   ├── GaleriController.php
│   │   ├── KontakController.php
│   │   ├── PasswordController.php
│   │   ├── PostinganController.php
│   │   └── PublicController.php
│   ├── models/                # Akses dan logika data
│   │   ├── AgendaModel.php
│   │   ├── GaleriModel.php
│   │   ├── KontakModel.php
│   │   ├── PostinganModel.php
│   │   └── UserModel.php
│   └── views/                 # Template tampilan (publik, admin, error)
│       ├── public/
│       │   ├── beranda/
│       │   ├── tentang/
│       │   ├── publikasi/
│       │   └── kontak/
│       ├── admin/
│       │   ├── agenda/
│       │   ├── galeri/
│       │   ├── postingan/
│       │   ├── kontak/
│       │   ├── dashboard.php
│       │   ├── login.php
│       │   └── password.php
│       └── errors/            # Halaman error (404, 500, generic)
├── public/                    # Web root (entry point & aset publik)
│   ├── index.php              # Entry point aplikasi
│   ├── .htaccess              # URL rewriting Apache
│   ├── assets/                # CSS, JS, gambar statis
│   └── uploads/               # File upload pengguna
│       ├── galeri/
│       └── postingan/
├── sql/                       # Skema dan data awal basis data
├── documentation/
│   └── readme-screenshots/    # Cuplikan antarmuka untuk README
└── README.md                  # Dokumentasi utama proyek
```

</details>

---

## Cuplikan Antarmuka Situs

<h3 id="cuplikan-01">1. Beranda</h3>

<div align="center">

<img src="documentation/readme-screenshots/01-beranda.png" alt="Screenshot laman Beranda Desa Wisata Budaya Pampang" width="920">

</div>

*Laman Beranda menampilkan hero, navigasi utama, agenda terkini, galeri pilihan, dan postingan unggulan.*

<h3 id="cuplikan-02">2. Tentang</h3>

<div align="center">

<img src="documentation/readme-screenshots/02-tentang.png" alt="Screenshot laman Tentang Desa Wisata Budaya Pampang" width="920">

</div>

*Laman Tentang menampilkan profil desa, latar sejarah, dan narasi kekayaan budaya Desa Pampang.*

<h3 id="cuplikan-03">3. Publikasi</h3>

<div align="center">

<img src="documentation/readme-screenshots/03-publikasi.png" alt="Screenshot laman Publikasi Desa Wisata Budaya Pampang" width="920">

</div>

*Laman Publikasi menampilkan galeri dokumentasi visual dan artikel berita kegiatan desa.*

<h3 id="cuplikan-04">4. Kontak</h3>

<div align="center">

<img src="documentation/readme-screenshots/04-kontak.png" alt="Screenshot laman Kontak Desa Wisata Budaya Pampang" width="920">

</div>

*Laman Kontak menampilkan agenda kegiatan, alamat, jam operasional, harga, dan kanal komunikasi resmi.*

<h3 id="cuplikan-05">5. Login Admin</h3>

<div align="center">

<img src="documentation/readme-screenshots/05-login-admin.png" alt="Screenshot laman Login Admin Desa Wisata Budaya Pampang" width="920">

</div>

*Laman Login Admin menampilkan formulir autentikasi untuk membatasi akses panel administrasi.*

<h3 id="cuplikan-06">6. Dashboard Admin</h3>

<div align="center">

<img src="documentation/readme-screenshots/06-admin-dashboard.png" alt="Screenshot laman Dashboard Admin Desa Wisata Budaya Pampang" width="920">

</div>

*Laman Dashboard Admin menampilkan ringkasan data postingan, agenda, dan galeri yang terkelola.*

<h3 id="cuplikan-07">7. Manajemen Postingan</h3>

<div align="center">

<img src="documentation/readme-screenshots/07-admin-postingan.png" alt="Screenshot laman Manajemen Postingan Admin" width="920">

</div>

*Laman Manajemen Postingan menyediakan antarmuka tambah, edit, dan hapus artikel berita desa.*

<h3 id="cuplikan-08">8. Manajemen Agenda</h3>

<div align="center">

<img src="documentation/readme-screenshots/08-admin-agenda.png" alt="Screenshot laman Manajemen Agenda Admin" width="920">

</div>

*Laman Manajemen Agenda menyediakan antarmuka pengelolaan jadwal kegiatan dan pertunjukan budaya.*

<h3 id="cuplikan-09">9. Manajemen Galeri</h3>

<div align="center">

<img src="documentation/readme-screenshots/09-admin-galeri.png" alt="Screenshot laman Manajemen Galeri Admin" width="920">

</div>

*Laman Manajemen Galeri menyediakan antarmuka upload foto (file/URL) dan pengelolaan dokumentasi visual.*

<h3 id="cuplikan-10">10. Manajemen Kontak</h3>

<div align="center">

<img src="documentation/readme-screenshots/10-admin-kontak.png" alt="Screenshot laman Manajemen Kontak Admin" width="920">

</div>

*Laman Manajemen Kontak menyediakan antarmuka pengelolaan alamat, jam operasional, harga, dan kontak resmi.*

---

## Verifikasi Kesesuaian Instruksi Proyek Akhir

| Poin Instruksi PA | Implementasi pada Repo/Situs |
|---|---|
| Berfokus pada objek pariwisata Samarinda | Studi kasus mitra: Desa Wisata Budaya Pampang (Samarinda) |
| Memuat beranda | Tersedia laman publik `/` dengan ringkasan konten utama |
| Memuat detail wisata | Dipetakan ke `/tentang`, `/publikasi`, dan `/kontak` |
| Memuat CRUD sederhana | CRUD penuh tersedia untuk postingan, agenda, galeri, dan kontak melalui panel admin |
| Menggunakan PHP dan MySQL | Basis implementasi backend dan data pada proyek ini |
| Menggunakan koneksi terpisah (`Database.php`) | Kelas Database Singleton dipisahkan di `app/core/Database.php` dengan konfigurasi ENV |
| Menggunakan session dan autentikasi admin | Akses admin melalui `/login` dengan session regeneration dan panel `/admin` |
| Responsif dengan Bootstrap 5 dan interaktif dengan Vue & JS | Digunakan pada antarmuka publik untuk konsistensi tampilan dan interaksi dinamis |
| Nilai tambah MVC | Struktur kode diorganisasi dengan custom framework MVC di folder `app/` |

---

<div align="center">

<img src="documentation/readme-screenshots/11-readme-footer.png" alt="Footer visual README Desa Wisata Budaya Pampang" width="1100">

</div>

> [!NOTE]
> Dokumen ini disusun sebagai ringkasan teknis dan bukti implementasi Proyek Akhir PBW untuk penilai, mitra, dan pembaca repositori.

<p align="center"><a href="#top">Kembali ke atas</a></p>
