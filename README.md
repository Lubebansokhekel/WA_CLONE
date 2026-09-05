# CHAT_APP 24.0

Aplikasi chat modern berbasis WebView yang ringan, bersih, dan nyaman digunakan.

> Package: `com.chatapp`  
> Versi: 24.0 (Modified)

---

## Tentang Aplikasi

**CHAT_APP** adalah forum chat berbasis web yang dibungkus dalam aplikasi Android agar pengalaman pengguna lebih optimal.  
Semua fitur chat berjalan di server web, sementara aplikasi Android berfungsi sebagai jendela fullscreen yang stabil dan nyaman.

Aplikasi ini cocok untuk komunitas yang ingin memiliki ruang chat sendiri dengan tampilan yang rapi dan notifikasi yang aktif.

---

## Fitur Utama

### Pengalaman Pengguna
- **Tampilan Fullscreen Immersive**  
  Status bar dan navigation bar disembunyikan secara otomatis. Fokus sepenuhnya ke percakapan.
- **Anti Accidental Refresh**  
  Gestur tarik ke bawah untuk refresh dinonaktifkan, sehingga chat tidak mudah ter-reset secara tidak sengaja.
- **Stabil di berbagai orientasi**  
  Aplikasi tetap berjalan lancar saat layar diputar atau ukuran berubah.

### Fitur Chat
- Chat privat & grup secara real-time
- Dukungan media (foto & file)
- Notifikasi push yang informatif (menampilkan nama pengirim, cuplikan pesan, dan foto profil)
- Integrasi untuk pengiriman notifikasi yang andal

### Hiburan di dalam Chat
- Mini-game yang bisa dimainkan langsung di dalam aplikasi (contoh: permainan ular tangga digital yang bisa buat Mabar bareng temen dan game lainnya)
- Sistem game modular, mudah dikembangkan lebih lanjut

---

## Keamanan & Privasi (Ringkasan)

- Komunikasi berjalan melalui protokol HTTPS
- Notifikasi push menggunakan layanan yang sudah umum dipakai banyak aplikasi
- Aplikasi tidak menyimpan data chat secara lokal di perangkat (semua data dikelola di sisi server)
- Permission yang diminta sebatas kebutuhan fitur (storage, notifikasi, dan background yang wajar)

Kami berusaha menjaga agar aplikasi tetap ringan dan tidak meminta izin yang berlebihan.

---

## Permission yang Digunakan

Aplikasi meminta beberapa izin standar untuk mendukung fitur:

| Permission | Kegunaan |
|-----------|----------|
| Storage / Media | Mengirim & menyimpan foto/file |
| Notifikasi | Menerima pemberitahuan chat baru |
| Battery Optimization | Agar notifikasi tetap diterima dengan baik |
| Background terkait | Menjaga notifikasi dan layanan chat tetap responsif |

> **Catatan untuk pengguna Xiaomi, Oppo, Vivo, Realme, dan Huawei**  
> Agar notifikasi dan fitur background berjalan optimal, silakan aktifkan **Autostart** dan izinkan aktivitas latar belakang melalui pengaturan aplikasi di HP Anda.

---

## Cara Install

1. Uninstall versi lama terlebih dahulu (jika ada).
2. Izinkan instalasi dari sumber tidak dikenal.
3. Install file APK yang disediakan.
4. Berikan izin yang diminta saat pertama kali dijalankan.

---

## File yang Tersedia

| File | Keterangan |
|------|------------|
| `CHAT_APP_24.0` | Versi Android siap pakai (fullscreen + permission lengkap) |

---

## Update di Versi Ini

- Tampilan dibuat fullscreen immersive sticky
- Fitur pull-to-refresh dinonaktifkan agar lebih stabil
- Layout dioptimalkan agar konten chat memenuhi seluruh layar
- Permission modern ditambahkan (storage media, notifikasi, battery, dll)
- URL sumber chat tetap utuh dan tidak diubah

---

## Catatan Teknis

- Min SDK: 16  
- Target SDK: 29  
- Dibangun sebagai WebView wrapper yang ringan  
- Notifikasi yang sudah didukung  

---

## Disclaimer

Aplikasi ini merupakan hasil pengembangan dan penyesuaian dari proyek chat berbasis web.  
Gunakan secara bijak sesuai keperluan komunitas.  
Pengembang tidak bertanggung jawab atas penggunaan di luar tujuan yang dimaksud.

---

Terima kasih telah menggunakan **CHAT_APP**.  
Semoga bermanfaat dan menyenangkan untuk komunitas Anda.
