# Koin Cepat — Android

Game arcade sederhana native Android, dibuat dengan Kotlin tanpa layanan login atau Firebase.

## Identitas aplikasi
- Nama: Koin Cepat
- Application ID: `com.zalil.koincepat`
- Versi awal: 1.0 (versionCode 1)
- Minimum Android: 6.0 (API 23)
- Target SDK: 35

## Build dari HP melalui GitHub
1. Buat repository GitHub baru bernama `koin-cepat-android`.
2. Upload seluruh isi folder proyek ini ke root repository (bukan folder ZIP-nya).
3. Pastikan branch utama bernama `main`.
4. Buka tab **Actions**. Workflow akan berjalan otomatis setelah file di-push.
5. Setelah selesai, buka hasil run workflow dan unduh artifact `koin-cepat-android`.
6. Di dalam artifact ada APK debug untuk tes di HP dan AAB release.

## Catatan Google Play
AAB release dari workflow awal ini belum ditandatangani dengan kunci rilis milik pengembang. Untuk mengunggah ke Play Console, buat upload keystore sendiri dan pasang signing config/secrets sebelum rilis. Jangan membagikan file keystore atau password kepada siapa pun. Ganti application ID sebelum publikasi bila nama paket ini sudah digunakan.

## Kontrol game
- Ketuk koin untuk menambah skor.
- Ketuk bom untuk kehilangan nyawa.
- Koin yang lolos dari bawah layar juga mengurangi nyawa.
- Rekor tertinggi disimpan di perangkat.
