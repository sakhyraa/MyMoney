# MyMoney Tracker

Website pengelola keuangan pribadi dengan HTML, CSS, dan JavaScript murni. Tidak memerlukan PHP, MySQL, Node.js, atau backend.

## Menjalankan secara lokal
1. Ekstrak ZIP.
2. Buka folder `mymoney-tracker` di VS Code.
3. Jalankan `index.html` dengan ekstensi Live Server, atau buka langsung di browser.
4. Tambahkan sumber dana terlebih dahulu, lalu catat transaksi dan target tabungan.

## Hosting GitHub Pages
1. Buat repository baru di GitHub.
2. Upload seluruh isi folder ini ke root repository (pastikan `index.html` ada di root).
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/(root)`, lalu klik **Save**.
6. Tunggu proses publikasi dan buka URL GitHub Pages yang diberikan.

## Fitur
- Dashboard saldo, pemasukan, pengeluaran, dan target tabungan.
- Transaksi pemasukan/pengeluaran dengan kategori, tanggal, sumber dana, catatan.
- Kelola rekening, e-wallet, uang tunai, dan saldo awal.
- Target tabungan, setoran dan penarikan sebagai transfer internal.
- Laporan bulanan, grafik arus kas dan pengeluaran per kategori.
- Ekspor CSV, backup/restore JSON, reset data.
- Layout responsif untuk desktop dan HP.

## Penting tentang data
Data disimpan dengan `localStorage` pada browser. Data tidak otomatis tersinkronisasi antarperangkat dan tidak dikirim ke server. Jika browser/site data dibersihkan, data lokal dapat hilang. Gunakan menu **Pengaturan & Backup** untuk mengunduh backup JSON secara berkala. Jangan mengunggah file backup yang berisi data keuangan pribadi ke repository publik.

## Catatan versi awal
Ini merupakan prototipe pencatatan manual, bukan aplikasi perbankan dan tidak terhubung ke rekening bank. Nilai saldo dihitung berdasarkan saldo awal, transaksi, dan pergerakan tabungan yang dimasukkan pengguna.
