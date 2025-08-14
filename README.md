#🎁 Kado Online Interactive Animation

Proyek ini adalah animasi interaktif bertema **"Kado Online"** yang dibuat dengan **HTML, CSS, dan JavaScript murni**.  
Ketika kotak kado diklik tiga kali, animasi pembukaan akan berjalan, menampilkan pesan ucapan, transisi antar scene, efek partikel, dan musik latar.  
Cocok untuk mengirim ucapan selamat atau kejutan spesial secara online.

---

##✨ Fitur Utama

- **🎁 Animasi Kotak Kado**
  - Kotak dapat diklik untuk "diguncang".
  - Terbuka setelah 3 klik, memperlihatkan pesan ucapan.

- **🎬 Transisi Multi Scene**
  1. **Gift Scene** (kotak kado tertutup)
  2. **Final Scene** (ucapan & foto spesial)
  3. **Bonus Scene** (ucapan tambahan)
  4. **Congratulations Scene** (hujan emoji kucing)

- **💥 Efek Partikel**
  - Partikel bulat kuning
  - Animasi bunga
  - Hujan emoji kucing 🐱

- **🎵 Musik Latar**
  - Memutar `song.mp4` secara loop setelah kado terbuka.
  - Audio diaktifkan setelah interaksi pertama untuk menghindari pembatasan autoplay browser.

- **📱 Desain Responsif**
  - Mendukung tampilan di desktop dan mobile.

- **🔄 Replay Otomatis**
  - Setelah animasi selesai, otomatis kembali ke tampilan awal.


##📂 Struktur Proyek

.
├── index.html          # File utama berisi HTML, CSS, dan JavaScript
├── song.mp4            # Musik latar (looping)
└── README.md           # Dokumentasi proyek

## 🚀 Cara Kerja

1. **Klik kotak kado** → kotak akan berguncang.
2. Setelah **3 klik**:
   - Tutup kotak terbuka.
   - Muncul partikel & bunga.
   - Musik latar mulai diputar.
3. **Scene berganti otomatis**:
   - Gift Scene → Final Scene → Bonus Scene → Congratulations Scene.
4. **Congratulations Scene** → hujan emoji kucing selama 2,5 detik.
5. **Replay otomatis** → kembali ke Gift Scene.

---

##🛠 Teknologi yang Digunakan

- **HTML5** → Struktur halaman & elemen audio.
- **CSS3** → Desain, transisi, dan animasi.
- **Vanilla JavaScript (ES6)** → Interaksi klik, kontrol scene, efek partikel.

## 🔧 Cara Menggunakan

1. **Download atau clone repositori ini**:
   ```bash
   git clone https://github.com/username/kado-online.git
   cd kado-online
2. **Pastikan file audio** `song.mp4` berada di direktori yang sama dengan `index.html`.
3. **Buka file** `index.html` di browser.
4. **Klik kotak kado** untuk memulai animasi.


## 🎨 Kustomisasi

* **Teks Ucapan**

  * Edit langsung di `index.html`:

    ```html
    <h1 id="initial-message">Selamat Semhas Bangg!</h1>
    ```
* **Gambar**

  * Ganti URL `img src` di bagian Final Scene dan Bonus Scene.
* **Warna**

  * Ubah variabel CSS di bagian `:root`:

    ```css
    :root {
        --bg-color: #f0f4f8;
        --primary-gift-color: #d63031;
        --secondary-gift-color: #e17055;
        --ribbon-color: #fdcb6e;
        --text-color: #2d3436;
    }
    ```
* **Musik**

  * Ganti file `song.mp4` dengan lagu favorit kamu.

---

## 📸 Preview

**Gift Scene → Final Scene → Bonus Scene → Congratulations Scene**

![Preview Image](https://i.pinimg.com/736x/d1/97/77/d1977749e95f9448b58cd0c5c630ec2e.jpg)

---

## ⚠️ Catatan Penting

* **Autoplay musik** dibatasi oleh browser, sehingga musik hanya akan mulai setelah ada interaksi klik.
* File `song.mp4` tidak disediakan di repositori ini (gunakan musik kamu sendiri).

---

## 📜 Lisensi

Proyek ini bebas digunakan dan dimodifikasi untuk keperluan pribadi atau edukasi.
Tidak diperkenankan menggunakan untuk tujuan komersial tanpa izin pembuat.

---

