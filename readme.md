# MeerAI Chatbot - WordPress Plugin

Plugin WordPress untuk menampilkan chatbot AI MeerAI di website Anda.

## 📋 Fitur

- ✅ Mudah diinstall di WordPress
- ✅ Panel admin yang user-friendly
- ✅ Pilihan menampilkan chatbot di:
  - Semua halaman
  - Halaman tertentu (bisa lebih dari satu)
  - Nonaktif
- ✅ Tidak perlu coding
- ✅ Widget floating button otomatis

## 📦 Cara Install

### Metode 1: Upload Plugin (Recommended)

1. **Download** file `meeraid-chatbot.zip`
2. Login ke **WordPress Admin**
3. Buka **Plugins → Add New**
4. Klik **Upload Plugin**
5. Pilih file `meeraid-chatbot.zip`
6. Klik **Install Now**
7. Klik **Activate Plugin**

### Metode 2: Upload Manual via FTP

1. Upload folder `meeraid-chatbot` ke `/wp-content/plugins/`
2. Login ke WordPress Admin
3. Buka **Plugins**
4. Aktifkan **MeerAI Chatbot**

## ⚙️ Cara Menggunakan

### 1. Dapatkan User ID Anda

1. Login ke [Dashboard MeerAI](https://meeraid.vercel.app/dashboard.html)
2. Buka tab **"Embed"**
3. Copy **User ID** Anda (ID unik dalam format string panjang)

### 2. Konfigurasi Plugin

1. Di WordPress Admin, buka **MeerAI Chatbot** di menu sidebar
2. Paste **User ID** Anda
3. Pilih dimana chatbot akan tampil:
   - **Semua Halaman**: Chatbot muncul di seluruh website
   - **Halaman Tertentu**: Pilih halaman mana saja (bisa lebih dari satu)
   - **Nonaktif**: Matikan sementara
4. Klik **Simpan Pengaturan**

### 3. Selesai! 🎉

Chatbot akan otomatis muncul di halaman yang Anda pilih sebagai floating button di pojok kanan bawah.

## 🎨 Customisasi

Untuk mengatur tampilan dan perilaku chatbot (warna, posisi, pesan welcome, dll):

1. Login ke [Dashboard MeerAI](https://meeraid.vercel.app/dashboard.html)
2. Buka tab **"Pengaturan"**
3. Sesuaikan:
   - Nama AI
   - Logo
   - Warna widget
   - Posisi (kanan bawah, kiri bawah, dll)
   - Pesan sambutan
   - Model AI
   - Dan lainnya

Perubahan akan otomatis tersinkronisasi ke website Anda.

## 📝 Contoh Penggunaan

### Tampilkan di Semua Halaman
1. Pilih radio button **"Semua Halaman"**
2. Klik **Simpan Pengaturan**
3. Chatbot akan muncul di seluruh website

### Tampilkan di Halaman Tertentu
1. Pilih radio button **"Halaman Tertentu"**
2. Centang halaman yang diinginkan (bisa lebih dari satu):
   - ☑️ Home
   - ☑️ About Us
   - ☑️ Contact
3. Klik **Simpan Pengaturan**
4. Chatbot hanya muncul di halaman yang dipilih

### Menonaktifkan Sementara
1. Pilih radio button **"Nonaktif"**
2. Klik **Simpan Pengaturan**
3. Chatbot tidak akan muncul di website (settings tetap tersimpan)

## 🔧 Troubleshooting

### Chatbot tidak muncul?
- Pastikan **User ID** sudah benar
- Pastikan tidak memilih **"Nonaktif"**
- Pastikan sudah **Simpan Pengaturan**
- Coba buka halaman dalam mode **Incognito/Private** (untuk bypass cache)
- Clear cache browser/plugin cache WordPress

### User ID salah?
- Login ke [Dashboard MeerAI](https://meeraid.vercel.app/dashboard.html)
- Tab **Embed** → Copy lagi User ID yang benar
- Paste di plugin settings

### Chatbot muncul di halaman yang tidak diinginkan?
- Cek pengaturan **"Tampilkan Chatbot di:"**
- Jika pilih **"Halaman Tertentu"**, pastikan hanya centang halaman yang diinginkan

## 💡 Tips

- Gunakan **"Semua Halaman"** untuk website yang ingin customer support di semua area
- Gunakan **"Halaman Tertentu"** untuk website yang hanya ingin chatbot di area spesifik (misal: halaman produk, kontak)
- Anda bisa mengubah pengaturan kapan saja tanpa install ulang plugin

## 📞 Support

- Website: [https://meeraid.vercel.app](https://meeraid.vercel.app)
- Dashboard: [https://meeraid.vercel.app/dashboard.html](https://meeraid.vercel.app/dashboard.html)

## 📄 License

GPL v2 or later

## 🔄 Changelog

### Version 1.0.0
- Initial release
- Basic page selection
- Admin panel
- Widget injection
