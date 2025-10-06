# Portfolio Website Modern

Website portfolio modern dengan desain responsif dan animasi menarik.

## 🚀 Fitur

- ✅ **Design Modern** - Interface yang clean dan profesional
- ✅ **Responsive** - Optimal di semua device (desktop, tablet, mobile)
- ✅ **Dark/Light Mode** - Toggle tema gelap/terang
- ✅ **Smooth Animations** - Animasi scroll, hover, dan transitions
- ✅ **Particle Background** - Background dengan efek partikel interaktif
- ✅ **Navigation Smooth** - Smooth scrolling dan fixed navbar
- ✅ **Portfolio Filter** - Filter project berdasarkan kategori
- ✅ **Contact Form** - Form kontak dengan validasi
- ✅ **Loading Screen** - Splash screen dengan animasi loading
- ✅ **Mobile Menu** - Hamburger menu untuk mobile devices

## 📁 Struktur File

```
modern-portfolio/
├── index.html          # File utama website
├── css/
│   └── style.css       # Stylesheet dengan semua styling
├── js/
│   └── script.js       # JavaScript untuk interaktivitas
└── assets/
    ├── images/         # Folder untuk gambar
    │   └── placeholder.txt
    ├── icons/          # Folder untuk ikon
    └── video/          # Folder untuk video background
```

## 🛠️ Cara Menjalankan

### 1. Menggunakan Live Server (Recommended)
```bash
# Jika menggunakan VS Code, install extension "Live Server"
# Klik kanan pada index.html -> "Open with Live Server"

# Atau menggunakan Python
cd modern-portfolio
python -m http.server 8000
# Buka http://localhost:8000
```

### 2. Menggunakan PHP Server
```bash
cd modern-portfolio
php -S localhost:8000
# Buka http://localhost:8000
```

### 3. Menggunakan XAMPP/WAMP
- Copy folder `modern-portfolio` ke `htdocs` (XAMPP) atau `www` (WAMP)
- Jalankan Apache service
- Buka `http://localhost/modern-portfolio`

## 🎨 Customization

### Mengubah Warna Theme
Edit variabel CSS di `css/style.css`:
```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    --accent-color: #06b6d4;
    /* ... lainnya */
}
```

### Mengubah Konten
Edit file `index.html` untuk:
- Nama dan informasi pribadi
- Skills dan persentase
- Project portfolio
- Informasi kontak

### Menambahkan Gambar
1. **Foto Profil**: Simpan sebagai `assets/images/profile.jpg`
2. **Project Images**: Simpan sebagai `assets/images/project1.jpg`, `project2.jpg`, etc.
3. **Video Background**: Simpan sebagai `assets/video/background.mp4`

## 📱 Responsive Breakpoints
- **Desktop**: > 1024px
- **Tablet**: 768px - 1024px  
- **Mobile**: < 768px

## 🌟 Browser Support
- Chrome (recommended)
- Firefox
- Safari
- Edge

## 📝 Catatan
- Pastikan semua gambar dan video ditempatkan di folder yang benar
- Untuk performa optimal, kompres gambar sebelum digunakan
- Video background sebaiknya dalam format MP4 dengan durasi pendek

## 🔧 Troubleshooting

### Gambar Tidak Muncul
Pastikan file gambar ada di folder `assets/images/` dengan nama yang sesuai

### Animasi Tidak Bekerja
Pastikan JavaScript dienable di browser

### Responsive Issues
Test di berbagai device dan browser

---

Dibuat dengan ❤️ menggunakan HTML, CSS, dan JavaScript vanilla.
