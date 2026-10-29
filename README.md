# EZI Inventory — unduhan

EZI adalah sistem inventaris kantor kecil yang berjalan di satu PC Windows di jaringan lokal. PC dan HP lain di kantor membukanya lewat browser. EZI mencatat barang, stok masuk dan keluar, peminjaman, permintaan pembelian, dan pengeluaran, lengkap dengan laporan, export Excel, dan backup database. Ada dua peran: Admin dan Staff. Tampilan dalam Bahasa Indonesia (bisa diganti ke English).

Repo ini hanya berisi installer dan panduan. Kode sumber disimpan di repo terpisah.

## Unduh

Buka **[Releases](https://github.com/freiyu/Easy-Inventory-Releases/releases/latest)**, lalu unduh `EZI-Setup-x.y.z.exe` dan `SHA256SUMS.txt`. Tidak perlu akun GitHub.

Kebutuhan: Windows 10 atau 11 (64-bit) dan hak Administrator untuk memasang. Node.js, database, dan lainnya sudah ada di dalam installer.

## Panduan

1. [Instalasi](docs/INSTALLATION.md): unduh, cek keaslian file, pasang, Admin pertama.
2. [Akses pengguna](docs/USER-ACCESS.md): membuka EZI dari PC dan HP lain.
3. [Panduan Admin](docs/ADMIN-GUIDE.md): backup, restore, pindah PC, update.
4. [Mengatasi masalah](docs/TROUBLESHOOTING.md)

## Lisensi

EZI dirilis dengan [MIT License](LICENSE). Software pihak ketiga di dalam installer (Node.js, MariaDB, WinSW) memakai lisensinya sendiri: lihat [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md).
