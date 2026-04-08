# WorkEdu Platform 🚀

## 📌 Deskripsi

WorkEdu adalah landing page platform belajar dan bekerja dari rumah yang dirancang menggunakan HTML5 dan CSS3. Project ini dibuat untuk memenuhi Tugas 2 Pemrograman Web (Frontend CSS) sekaligus sebagai fondasi untuk pengembangan ke backend di masa depan.

---

## 🎯 Fitur Utama

- ✅ Navbar interaktif dengan hover effect
- ✅ Hero section dengan background image + overlay
- ✅ Section fitur & kursus
- ✅ Testimonial (social proof)
- ✅ Pricing plan (model bisnis)
- ✅ Form registrasi
- ✅ Responsive design (mobile friendly)
- ✅ Animasi hover & transition modern
- ✅ Glassmorphism UI

---

## 📸 Screenshot

### Tampilan Landing Page

![Screenshot](assets/image1.png)
![Screenshot](assets/image2.png)
![Screenshot](assets/image3.png)
![Screenshot](assets/image4.png)
![Screenshot](assets/image5.png)
![Screenshot](assets/image6.png)
![Screenshot](assets/image7.png)

---

## 📈 Pengembangan Selanjutnya (Roadmap)

- 🔐 Sistem login & register (backend)
- 📊 Dashboard user
- 💳 Integrasi payment (subscription)
- 🗂️ Database kursus

---

## 👤 Identitas

Nama : Muhammad Akbar  
NIM : F1D02410075  
Kelas : Pemrograman Web C 2026

---

## ⭐ Catatan

Project ini dirancang tidak hanya untuk tugas, tetapi sebagai dasar pengembangan aplikasi web fullstack di masa depan.

## 🧠 Penjelasan Implementasi

Secara garis besar, website WorkEdu ini dibangun menggunakan pendekatan **Pure HTML5 + CSS3 (tanpa framework)** dengan fokus pada clean structure, modern UI, dan scalability untuk pengembangan backend di masa depan.

---

### 🏗️ Struktur Layout (HTML5 Semantic)

Website ini menggunakan struktur HTML5 semantic untuk meningkatkan keterbacaan kode dan SEO:

- `<header>` → bagian navigasi utama (Navbar)
- `<section>` → membagi konten (Hero, Features, Courses, dll)
- `<footer>` → bagian penutup

Setiap section memiliki `id` agar bisa diakses melalui navigasi (anchor link).

---

### 🎨 Styling & Visual Design (CSS3)

Seluruh tampilan dikontrol menggunakan **External CSS (`style.css`)** untuk menjaga konsistensi dan kemudahan maintenance.

#### 1. Box Model

Digunakan untuk mengatur jarak dan ukuran elemen:

- `padding` → jarak dalam elemen
- `margin` → jarak antar elemen
- `border` → garis pembatas

Contoh implementasi:

- Card menggunakan padding besar untuk ruang konten
- Section menggunakan margin/padding agar tidak terlalu padat

---

#### 2. Flexbox Layout (Core Layout System)

Flexbox digunakan sebagai sistem layout utama untuk menyusun elemen secara horizontal dan responsif:

- Navbar → untuk sejajarkan logo dan menu
- Card Container → untuk menampilkan card dalam baris

Properti penting:

- `display: flex`
- `justify-content: center`
- `flex-wrap: wrap`

---

#### 3. Glassmorphism UI

Desain modern diterapkan menggunakan efek **glassmorphism**:

- `background: rgba(...)`
- `backdrop-filter: blur(...)`

Efek ini memberikan kesan transparan dan futuristik seperti aplikasi startup modern.

---

### 🎯 Interaksi & Animasi (User Experience)

Untuk meningkatkan UX, digunakan efek interaktif berbasis CSS:

#### 1. Hover Effect

Digunakan pada:

- Card
- Button
- Navbar link

Efek yang digunakan:

- `transform: scale()` → memperbesar elemen
- `translateY()` → efek melayang
- `box-shadow` → efek kedalaman

👉 Memberikan feedback visual bahwa elemen bisa diklik.

---

#### 2. Transition

Semua interaksi dibuat smooth menggunakan:

```css
transition: 0.3s;
```

👉 Menghindari perubahan mendadak (lebih natural)

3. Animation (Fade In Up)

Card menggunakan animasi:

opacity
transform

Saat halaman dibuka, elemen muncul perlahan dari bawah (fade + slide).

👉 Memberikan kesan dinamis dan modern

📱 Responsive Design

Website dibuat responsive menggunakan media query:
@media (max-width: 768px)

Perubahan:

Navbar menjadi vertikal
Card menyesuaikan lebar layar
Font size diperkecil

👉 Agar nyaman di mobile

🧩 Struktur Komponen (Scalable Design)

Website dibangun dengan konsep modular:
.navbar
.hero
.card
.btn
.content

👉 Memudahkan pengembangan ke tahap berikutnya (backend / framework)

🚀 Kesimpulan

Project ini tidak hanya memenuhi kebutuhan tugas, tetapi juga dirancang sebagai fondasi aplikasi web modern yang siap dikembangkan menjadi:

Sistem login
Dashboard user
Platform pembelajaran online
Pendekatan ini memastikan bahwa project dapat berkembang tanpa perlu redesign besar di masa depan.
