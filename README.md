# UAS-TI4C-Pemograman-Seluler

Proyek ini menggunakan Firebase sebagai server API dan Firestore sebagai basis data. Berikut adalah langkah-langkah untuk konfigurasi, instalasi, cara menjalankan proyek ini, serta cara melakukan backup database.

## Konfigurasi Firebase

1. **Buat Proyek di Firebase Console**:
   - Masuk ke [Firebase Console](https://console.firebase.google.com/).
   - Buat proyek baru atau pilih proyek yang sudah ada.

2. **Tambahkan Aplikasi ke Firebase**:
   - Untuk aplikasi web, pilih ikon web (`</>`), masukkan nama aplikasi, dan klik "Register app".
   - Ikuti petunjuk untuk mengonfigurasi Firebase SDK. Salin konfigurasi Firebase yang diberikan.

3. **Instal Firebase CLI**:
   ```bash
   npm install -g firebase-tools
