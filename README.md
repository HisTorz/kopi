# 🍵 Warung Kopi Santai - Website

Website responsif untuk "Warung Kopi Santai" dengan tema hangat dan estetik yang dirancang untuk memberikan pengalaman pengguna yang nyaman dan menarik.

## ✨ Fitur Utama

### 🎨 Desain & Tema
- **Tema Hangat**: Menggunakan kombinasi warna coklat tua (#4B2E2B), cream (#F5E1C0), dan hijau daun (#6B8E23)
- **Typography**: Font Poppins untuk teks utama, Merriweather untuk bagian cerita/sejarah
- **Responsif**: Desain yang optimal untuk desktop, tablet, dan mobile
- **Animasi**: Efek hover, scroll animations, dan transisi yang halus

### 📱 Navigasi & UX
- **Sticky Navigation**: Menu navigasi yang tetap di atas saat scroll
- **Mobile Menu**: Hamburger menu untuk perangkat mobile
- **Smooth Scrolling**: Navigasi antar section yang halus
- **Interactive Elements**: Efek hover pada menu, tombol, dan card

### 🍽️ Menu & Konten
- **Menu Lengkap**: 10 makanan dan 10 minuman dengan foto dan harga
- **Fasilitas**: 9 fasilitas dengan ikon dan deskripsi
- **Sejarah**: Cerita lengkap tentang Kopi Santai sejak 2015
- **Testimoni**: 4 testimoni pelanggan dengan rating bintang
- **Galeri**: Grid foto suasana indoor dan outdoor

### 📞 Kontak & Reservasi
- **Form Reservasi**: Form lengkap untuk booking ruang meeting
- **Informasi Kontak**: WhatsApp, Instagram, TikTok, dan alamat
- **Google Maps**: Placeholder untuk embed peta lokasi
- **Social Media**: Link ke platform sosial media

## 🚀 Cara Menjalankan

### Prerequisites
- Web browser modern (Chrome, Firefox, Safari, Edge)
- Local server (opsional, untuk development)

### Setup
1. **Clone atau download** semua file ke folder lokal
2. **Buka file** `index.html` di browser
3. **Atau jalankan local server**:
   ```bash
   # Menggunakan Python
   python -m http.server 8000
   
   # Menggunakan Node.js
   npx serve .
   
   # Menggunakan PHP
   php -S localhost:8000
   ```

### Struktur File
```
kopi/
├── index.html          # File HTML utama
├── style.css           # Stylesheet CSS
├── script.js           # JavaScript untuk interaktivitas
├── images/             # Folder untuk gambar (buat manual)
└── README.md           # Dokumentasi ini
```

## 🎯 Fitur Interaktif

### JavaScript Features
- **Mobile Navigation**: Toggle menu mobile
- **Form Validation**: Validasi form reservasi
- **Notifications**: Sistem notifikasi untuk feedback user
- **Scroll Animations**: Animasi elemen saat scroll
- **Hover Effects**: Efek interaktif pada elemen
- **Touch Support**: Gesture support untuk mobile
- **Performance**: Debounced scroll events untuk optimasi

### CSS Features
- **CSS Grid & Flexbox**: Layout modern dan responsif
- **CSS Variables**: Penggunaan warna yang konsisten
- **Media Queries**: Breakpoint untuk berbagai ukuran layar
- **Transitions**: Animasi CSS yang halus
- **Backdrop Filter**: Efek blur pada navbar

## 📱 Responsive Breakpoints

- **Desktop**: > 768px
- **Tablet**: 768px - 480px
- **Mobile**: < 480px

## 🎨 Customization

### Warna Utama
```css
--primary-color: #4B2E2B;    /* Coklat Tua */
--secondary-color: #F5E1C0;  /* Cream */
--accent-color: #6B8E23;     /* Hijau Daun */
```

### Font
```css
--main-font: 'Poppins', sans-serif;
--heading-font: 'Merriweather', serif;
```

### Mengganti Gambar
1. **Buat folder** `images/` di root project
2. **Tambahkan gambar** sesuai kebutuhan:
   - `hero-bg.jpg` - Background hero section
   - `menu-food-1.jpg` sampai `menu-food-10.jpg` - Foto makanan
   - `menu-drink-1.jpg` sampai `menu-drink-10.jpg` - Foto minuman
   - `gallery-1.jpg` sampai `gallery-6.jpg` - Foto galeri
   - `testimonial-1.jpg` sampai `testimonial-4.jpg` - Foto profil testimoni

3. **Update HTML** untuk menggunakan gambar asli:
   ```html
   <!-- Ganti placeholder dengan gambar asli -->
   <img src="images/hero-bg.jpg" alt="Suasana Warung Kopi">
   ```

## 🔧 Development

### Menambah Section Baru
1. **HTML**: Tambahkan section dengan ID unik
2. **CSS**: Buat styles untuk section baru
3. **JavaScript**: Tambahkan animasi jika diperlukan

### Menambah Menu Item
1. **HTML**: Copy struktur menu-item yang ada
2. **Update**: Nama, harga, dan deskripsi
3. **Gambar**: Tambahkan foto menu di folder images

### Menambah Fasilitas
1. **HTML**: Copy struktur facility-item
2. **Icon**: Pilih icon dari Font Awesome
3. **Update**: Nama dan deskripsi fasilitas

## 🌐 Deployment

### Static Hosting
- **Netlify**: Drag & drop folder ke Netlify
- **Vercel**: Connect repository GitHub
- **GitHub Pages**: Push ke branch gh-pages
- **Firebase Hosting**: Deploy menggunakan Firebase CLI

### Web Server
- **Apache**: Upload ke folder htdocs
- **Nginx**: Configure server block
- **IIS**: Setup website di IIS Manager

## 📊 Performance

### Optimizations
- **Lazy Loading**: Gambar dimuat saat diperlukan
- **Debounced Events**: Scroll events di-optimize
- **CSS Transitions**: Animasi menggunakan CSS
- **Minified Assets**: File CSS/JS di-minify untuk production

### Best Practices
- **Semantic HTML**: Struktur HTML yang bermakna
- **Accessibility**: Support keyboard navigation
- **SEO**: Meta tags dan struktur yang optimal
- **Mobile First**: Design dimulai dari mobile

## 🐛 Troubleshooting

### Common Issues
1. **Font tidak muncul**: Pastikan koneksi internet untuk Google Fonts
2. **Icon tidak muncul**: Pastikan CDN Font Awesome dapat diakses
3. **Menu mobile tidak berfungsi**: Check console untuk error JavaScript
4. **Form tidak submit**: Pastikan semua field required terisi

### Debug Mode
- **Console Logs**: Buka Developer Tools untuk melihat logs
- **Error Handling**: JavaScript memiliki error handling yang baik
- **Validation**: Form validation memberikan feedback yang jelas

## 📝 Changelog

### v1.0.0 (Current)
- ✅ Website responsif lengkap
- ✅ Semua section yang diminta
- ✅ Mobile navigation
- ✅ Form reservasi
- ✅ Animasi dan interaktivitas
- ✅ Tema hangat dan estetik

## 🤝 Contributing

Untuk berkontribusi pada project ini:
1. Fork repository
2. Buat feature branch
3. Commit changes
4. Push ke branch
5. Buat Pull Request

## 📄 License

Project ini dibuat untuk Warung Kopi Santai. Semua hak cipta dilindungi.

## 📞 Support

Untuk pertanyaan atau dukungan:
- **Email**: support@kopisantai.com
- **WhatsApp**: 0877623623663
- **Instagram**: @kopisantai

---

**Dibuat dengan ❤️ untuk Warung Kopi Santai**

*"Dari secangkir kopi, kami ingin menciptakan jutaan kenangan."*
