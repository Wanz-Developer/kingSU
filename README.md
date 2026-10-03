# KingSU Utility

Aplikasi utilitas dasbor kustom yang ringan dan modern untuk perangkat Android yang memiliki akses root. Aplikasi ini dirancang khusus untuk mempermudah manajemen perintah sistem esensial secara aman.

## ✨ Fitur Utama

*   **Periksa Akses Root:** Deteksi otomatis status biner `su` pada sistem secara aman tanpa risiko *force close* (kompatibel dengan KernelSU, KernelSU Next, Magisk, dan APatch).
*   **Reboot ke Recovery:** Akses cepat satu klik untuk memulai ulang perangkat langsung masuk ke mode Custom Recovery (seperti crDroid Recovery, TWRP, atau OrangeFox).
*   **Reboot ke Bootloader:** Pintasan instan untuk masuk ke mode Fastboot / Bootloader tanpa perlu kombinasi tombol fisik.

## 📱 Keamanan Distribusi Umum

Aplikasi ini dibangun menggunakan framework **Jetpack Compose** dan **Kotlin** modern dengan sistem isolasi eror (*try-catch protection*). Jika aplikasi ini dijalankan pada perangkat unrooted, aplikasi tetap dapat terbuka dengan aman dan menampilkan indikator status tanpa menyebabkan kegagalan sistem atau gangguan pada file internal perangkat.

## 🚀 Cara Pemasangan

1. Unduh berkas APK versi terbaru pada menu **Releases** di repositori ini.
2. Pasang file `kingSU_v1.0.0.apk` tersebut di perangkat Android Anda.
3. Buka aplikasi, dan berikan izin *Superuser* jika manajer root Anda memicu jendela permintaan izin akses.

## 🛠️ Pengembangan & Spesifikasi Proyek

*   **Bahasa Pemrograman:** Kotlin
*   **UI Framework:** Jetpack Compose (Material Design 3)
*   **Minimum Android API:** API 29 (Android 10.0)

---
*Dikembangkan secara independen oleh Wanz-Developer.*
