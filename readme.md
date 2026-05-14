# Animasi 3D Lebah - Landing Page

Proyek ini adalah halaman web interaktif yang menampilkan animasi lebah 3D menggunakan **Three.js** dan **GSAP**. Karena menggunakan aset eksternal (.glb), proyek ini **harus dijalankan melalui server** agar model 3D dapat muncul.

## Cara Menjalankan Menggunakan VS Code Live Server

Ikuti langkah-langkah berikut untuk menjalankan proyek ini di komputer Anda:

### 1. Instal Ekstensi Live Server
Jika Anda belum memilikinya, instal ekstensi **Live Server** oleh Ritwick Dey di VS Code:
1. Buka **VS Code**.
2. Klik ikon **Extensions** di sidebar kiri (atau tekan `Ctrl+Shift+X`).
3. Cari "**Live Server**".
4. Klik **Install**.

### 2. Jalankan Proyek
Setelah ekstensi terpasang:
1. Pastikan folder proyek `Animasi 3D Lebah` sudah terbuka di VS Code.
2. Buka file `index.html`.
3. Klik kanan pada area editor `index.html`.
4. Pilih **"Open with Live Server"**.
5. Browser Anda akan otomatis terbuka di alamat `http://127.0.0.1:5500/index.html` (atau port serupa).

### 3. Alternatif (Tanpa Ekstensi)
Jika Anda lebih suka menggunakan terminal, Anda bisa menggunakan:
- **Node.js**: `npx serve .`
- **Python**: `python -m http.server 8000`

---

## Mengapa Harus Pakai Server?
Browser memiliki fitur keamanan bernama **CORS (Cross-Origin Resource Sharing)**. Jika Anda membuka file `index.html` langsung dengan klik dua kali (protokol `file://`), browser akan memblokir proses loading file model 3D (`.glb`) karena dianggap tidak aman. Menjalankannya melalui server lokal (`http://`) menyelesaikan masalah ini.

## Teknologi yang Digunakan
- **Three.js**: Untuk render 3D.
- **GSAP**: Untuk animasi transisi antar section.
- **CSS Vanilla**: Untuk styling premium.
