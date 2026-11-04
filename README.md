# Sakuku - Catatan Hutang & Piutang

Aplikasi web modern untuk mencatat hutang dan piutang secara praktis, responsif, dan tersinkronisasi *real-time* ke **Google Cloud Firestore** (100% Gratis pada Firebase Spark Plan).

---

## 🌟 Fitur Unggulan

- **Realtime Cloud Sync**: Data otomatis tersinkronisasi langsung ke Google Cloud Firestore.
- **Dukungan Offline (PWA)**: Tetap dapat digunakan mencatat dan melihat data walau sedang tidak ada internet.
- **Kompresi Bukti Pembayaran**: Bukti screenshot transfer atau chat dikompres otomatis (~30-50KB) dan disimpan langsung ke cloud tanpa biaya tambahan.
- **Desain 100% Responsif**:
  - **Desktop**: Tampilan tabel interaktif, statistik lengkap, dan sidebar intuitif.
  - **Mobile**: Navigasi bawah (*Bottom Nav*), tombol melayang *Action Button*, dan tampilan kartu yang ramah sentuhan.
- **Pengingat WhatsApp Otomatis**: Sekali klik untuk mengirimkan rincian tagihan terformat rapi ke WhatsApp peminjam.
- **Cadangkan & Pulihkan**: Ekspor data lengkap ke `.json` atau rekapitulasi ke `.csv` (Excel).

---

## 🚀 Cara Menjalankan & Deploy

Aplikasi ini bersifat *client-side* murni (*zero-build*).

### Deploy via GitHub Pages:
1. Setelah repositori ini di-push ke GitHub, buka tab **Settings** di repositori GitHub Anda.
2. Pilih menu **Pages** di sebelah kiri.
3. Pada bagian **Build and deployment** > **Branch**, pilih `main` (atau `master`) dan folder `/ (root)`.
4. Klik **Save**. Web Anda akan langsung aktif secara publik dalam 1-2 menit!
