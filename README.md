# Aplikasi Absensi Siswa Berbasis Mobile (SMK Negeri 1 Talaud)

Proyek Akhir Pemrograman Perangkat Bergerak - Kelompok 4

Aplikasi absensi siswa berbasis mobile yang dibangun dengan Flutter dan Firebase. Siswa melakukan absensi dengan foto selfie sebagai bukti kehadiran, tanpa memerlukan GPS.

## Fitur Utama

- Login dan autentikasi pengguna
- Absensi dengan foto selfie sebagai validasi kehadiran
- Riwayat kehadiran siswa
- Penyimpanan data dan foto secara cloud (Firestore & Storage)

## Anggota Kelompok & Peran

- Gratia Joy Prawoto (Project Management & UI/UX)
- Putu Astika Suci Mahayani (Project Management & Flutter Developer)
- Eka Mantiri (UI/UX Designer)
- Maria Jelita Bonte (Flutter Developer & QA)
- Gratia Christie Chaeli Menggasa (Quality Assurance)

## Teknologi yang Digunakan

- Framework: Flutter (Dart)
- Backend/BaaS: Firebase (Authentication, Firestore, Storage)
- State Management: Provider

## Cara Menjalankan Proyek

1. Clone repository ini:
   ```bash
   git clone https://github.com/psuci27/app-absensi-siswa.git
   ```
2. Masuk ke direktori proyek:
   ```bash
   cd app-absensi-siswa
   ```
3. Unduh dependencies:
   ```bash
   flutter pub get
   ```
4. Hubungkan dengan Firebase: unduh `google-services.json` dari Firebase Console, lalu letakkan di `android/app/`.
5. Jalankan aplikasi:
   ```bash
   flutter run
   ```

## Struktur Folder

```
lib/
├── models/      # Model data
├── providers/   # State management (Provider)
├── screens/     # Halaman aplikasi
├── services/    # Layanan Firebase
└── main.dart
```

## Catatan

Proyek ini dibuat untuk keperluan pembelajaran pada mata kuliah Pemrograman Perangkat Bergerak, [nama kampus/program studi], [semester/tahun].
