# Karaoke Studio Lite — MVP 0.1

Starter project Android pribadi untuk menyiapkan bahan video karaoke.

## Sudah ada
- Memilih satu file audio MP3.
- Membaca durasi audio jika formatnya didukung Android.
- Memilih file lirik TXT.
- Memilih banyak gambar.
- Membuat preview timeline awal dengan membagi durasi lagu rata ke semua gambar.

## Belum ada
- Auto Sync lirik ke vokal.
- Timeline editor yang bisa digeser/diedit.
- Efek partikel, zoom, transisi, atau audio visualizer pada video final.
- Rendering dan ekspor MP4.
- Server Auto Sync.

Jadi versi ini adalah kerangka awal yang jujur, bukan APK produksi lengkap.

## Build
1. Instal Android Studio versi stabil dan Android SDK Platform 35.
2. Buka folder `KaraokeStudioLite` di Android Studio.
3. Pastikan JDK 17 digunakan.
4. Sinkronkan Gradle. Proyek ini belum menyertakan Gradle Wrapper; jika Android Studio meminta wrapper, buat wrapper Gradle 8.9 untuk proyek ini.
5. Hubungkan HP dengan USB debugging atau gunakan emulator, lalu tekan Run.

## Target teknis berikutnya
1. Tambahkan penyimpanan izin URI dan penyimpanan proyek.
2. Integrasikan layanan server untuk forced alignment yang diuji khusus pada vokal lagu.
3. Tambahkan editor timeline dan preset efek.
4. Implementasikan rendering lokal 720p H.264/AAC dan uji pada iQOO Z7x.
