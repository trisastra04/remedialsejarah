# Absensi Salat Online Siswa

Aplikasi ini digunakan untuk mencatat absensi salat siswa secara online.
Guru tinggal scan QR Code siswa, data akan otomatis tersimpan ke Google Spreadsheet.

## Struktur Spreadsheet
- **Sheet1**: Absensi
  ```
  Timestamp | ID Siswa | Nama | Salat | Waktu | Tanggal
  ```
- **Sheet2**: Data Siswa
  ```
  ID Siswa | Nama
  ```

## Cara Deploy
1. Buat Google Spreadsheet dengan 2 sheet seperti di atas.
2. Buka `Extensions -> Apps Script` dan paste kode GAS yang sudah disiapkan.
3. Deploy sebagai **Web App** dan salin URL-nya.
4. Ganti URL di `index.html` bagian `scriptURL` dengan URL Web App Anda.
5. Upload `index.html` ini ke repository GitHub.
6. Aktifkan GitHub Pages di repository tersebut.
