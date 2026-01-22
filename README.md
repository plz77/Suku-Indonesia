# Kenali-Suku-Indonesia
A simple Android application that utilizes Python for processing; a project showcase for my class.


# Aplikasi Pencari Informasi Suku Indonesia 🇮🇩
Aplikasi Android berbasis MIT App Inventor yang terintegrasi dengan server Python (Flask) untuk mencari informasi detail mengenai suku-suku di Indonesia secara otomatis.


## 📖 Latar Belakang
Proyek ini dikembangkan khusus sebagai **bahan display atau alat bantu ajar** di dalam kelas. Tujuannya adalah untuk memberikan visualisasi yang interaktif kepada siswa mengenai keragaman etnis di Indonesia melalui teknologi digital.


## 🌟 Alasan Pembuatan Aplikasi
Didasari oleh semangat untuk **melestarikan budaya Indonesia**. Dengan aplikasi ini, diharapkan generasi muda dapat lebih mudah mengakses informasi mengenai deskripsi suku, pakaian adat, hingga rumah adat, sehingga rasa cinta terhadap tanah air tetap terjaga.


## 🛠️ Teknologi yang Digunakan
- **Frontend:** MIT App Inventor (Blok Programming).
- **Backend:** Python 3 dengan Framework Flask.
- **Data Teks:** Scraping otomatis dari Wikipedia Indonesia melalui library `wikipedia`.
- **Data Gambar:** Google Search Image API via [Serper.dev](https://serper.dev/).
- **Tunneling:** Ngrok (untuk menghubungkan server lokal ke internet).


## 🚀 Langkah Penggunaan Simpel
1. **Jalankan Server:** Buka file Python di Google Colab, masukkan API Key Serper Anda, dan jalankan semua sel.
2. **Konfigurasi URL:** Salin link `ngrok-free.app/translate` yang muncul di log Colab.
3. **Update App:** Tempelkan link tersebut ke komponen `Web1.Url` di proyek MIT App Inventor Anda.
4. **Gunakan Aplikasi:** Buka aplikasi di HP, ketik nama suku (contoh: "Baduy" atau "Bali"), lalu tekan tombol cari.
5. **Hasil:** Informasi deskripsi dan gambar akan muncul secara otomatis di layar kedua.
