# Jiyy Chat APK

Pembungkus Android (Capacitor) untuk Jiyy Chat. Aplikasi memuat https://jiyy-chat.jiyydev.workers.dev, jadi update web otomatis ikut tanpa build ulang APK.

## Cara pakai
1. Buat repo GitHub baru, upload semua isi folder ini (termasuk folder `.github`).
2. Tab Actions > Build APK > Run workflow (atau push ke branch `main`).
3. Setelah hijau, buka tab Releases dan unduh `JiyyChat.apk` dari HP. Izinkan "pasang dari sumber ini" saat diminta.

## Ganti alamat
Ubah URL di `capacitor.config.json` dan `www/index.html` kalau domain Worker berubah. Ubah `dev.jiyy.chat` (appId) hanya sebelum rilis pertama.

## Catatan
APK ini ditandatangani kunci debug: bisa dipasang langsung, tapi tidak untuk Play Store. Untuk Play Store perlu keystore rilis.
