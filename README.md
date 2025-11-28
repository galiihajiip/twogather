# TWO-GATHER - Vietnam Fair Labor Youth Initiative Website

Website untuk Final Project AIESEC Future Leaders Winter Peak 2025 dengan tema Formula 1 dan aktivisme sosial tentang buruh Vietnam.

## 🏎️ Fitur Website

- **Single Page Design** dengan navigasi smooth scroll
- **F1 Racing Theme** dengan nuansa kuning dan hitam
- **Fully Responsive** untuk desktop, tablet, dan mobile
- **Animasi Modern** dengan fade-in dan hover effects
- **Instagram Links** yang langsung terhubung ke profil anggota tim

## 🎨 Color Palette

- Primary Yellow: `#FFC300`
- Accent Yellow: `#FFD60A`
- Pure Black: `#000000`
- Dark Grey: `#222222`
- Light Grey: `#F7F7F7`
- Accent Red: `#DA291C`

## 📁 Struktur File

```
twogather/
├── index.html          # Halaman utama website
├── styles.css          # Styling dengan tema F1
├── script.js           # JavaScript untuk interaksi
├── images/             # Folder untuk gambar
│   ├── vietnam-flag.svg
│   ├── sdg8.png        # Placeholder - ganti dengan logo asli
│   ├── sdg10.png       # Placeholder - ganti dengan logo asli
│   ├── sdg12.png       # Placeholder - ganti dengan logo asli
│   ├── sdg16.png       # Placeholder - ganti dengan logo asli
│   ├── team-photo.jpg  # Placeholder - ganti dengan foto tim asli
│   └── coach-mesya.jpg # Placeholder - ganti dengan foto coach asli
└── README.md           # File ini
```

## 🖼️ Cara Menambahkan Gambar

### 1. Logo SDG (Sustainable Development Goals)

Download logo SDG resmi dari website UN:

- **SDG 8**: https://www.un.org/sustainabledevelopment/wp-content/uploads/2019/08/E-Goal-08.png
- **SDG 10**: https://www.un.org/sustainabledevelopment/wp-content/uploads/2019/08/E-Goal-10.png
- **SDG 12**: https://www.un.org/sustainabledevelopment/wp-content/uploads/2019/08/E-Goal-12.png
- **SDG 16**: https://www.un.org/sustainabledevelopment/wp-content/uploads/2019/08/E-Goal-16.png

Simpan file-file tersebut ke folder `images/` dengan nama yang sesuai.

### 2. Foto Tim

- Ambil foto tim TWO-GATHER
- Rename menjadi `team-photo.jpg`
- Simpan di folder `images/`
- Rekomendasi ukuran: minimal 1200x800 pixels

### 3. Foto Coach Mesya

- Ambil foto coach
- Rename menjadi `coach-mesya.jpg`
- Simpan di folder `images/`
- Rekomendasi ukuran: 500x500 pixels (square/persegi)

## 🚀 Cara Menjalankan Website

### Opsi 1: Buka Langsung di Browser

1. Buka file `index.html` dengan double-click
2. Atau klik kanan → Open With → Browser pilihan Anda

### Opsi 2: Menggunakan Local Server (Recommended)

Jika Anda memiliki Python terinstall:

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

Kemudian buka browser dan akses: `http://localhost:8000`

### Opsi 3: Menggunakan Live Server (VS Code)

1. Install extension "Live Server" di VS Code
2. Klik kanan pada `index.html`
3. Pilih "Open with Live Server"

## 📱 Sections Website

1. **Header** - Navigasi tetap di atas
2. **Hero Section** - Judul utama dengan visual F1
3. **About Project** - Penjelasan VFLYI
4. **Problem Statement** - Masalah yang diangkat
5. **Stakeholders Analysis** - Pihak-pihak yang terlibat
6. **SDGs** - Target SDG 8, 10, 12, dan 16
7. **Program Highlight** - Fair Labor Youth Initiative (FLYi)
8. **Events** - 3 event utama (Seminar, Campaign, Escape Room)
9. **Timeline** - Jadwal pelaksanaan program
10. **Team** - Anggota tim TWO-GATHER
11. **Values & Culture** - Nilai, behaviour, dan budaya kerja
12. **Call to Action** - Ajakan mendukung fair labor
13. **Footer** - Informasi penutup

## 🔧 Customization

### Mengubah Warna

Edit file `styles.css` pada bagian `:root`:

```css
:root {
    --primary-yellow: #FFC300;
    --accent-yellow: #FFD60A;
    --pure-black: #000000;
    /* ... */
}
```

### Menambah Link Social Media di Footer

Edit file `index.html` pada section footer:

```html
<div class="footer-social">
    <a href="YOUR_INSTAGRAM_LINK" class="social-icon instagram-icon"></a>
    <!-- Tambahkan social media lain di sini -->
</div>
```

## 📝 Catatan Penting

- Semua konten teks sudah sesuai dengan dokumen original tanpa perubahan
- Instagram links sudah terhubung ke profil masing-masing anggota
- Website fully responsive untuk semua ukuran layar
- Animasi smooth dan tidak berlebihan untuk presentasi profesional

## 👥 Tim TWO-GATHER

- **Team Leader**: Fenantya Aulia Salsabila ([@fenantya_lia](https://instagram.com/fenantya_lia))
- **Program**: Galih Aji Pangestu ([@galiihajiip](https://instagram.com/galiihajiip))
- **Finance & Logistic**: Caraka Jingga Al Akhsani ([@carakaa._](https://instagram.com/carakaa._))
- **Marketing & Communication**: Anindya Wira Hidayati Ahyani ([@anindyawira](https://instagram.com/anindyawira))
- **Delegates & Service**: All Member
- **Coach**: Mesya

## 📄 License

© 2025 TWO-GATHER. All rights reserved.

---

**AIESEC Future Leaders Winter Peak 2025 - Vietnam Fair Labor Youth Initiative**
