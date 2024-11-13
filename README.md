# Aplikasi Konversi Suhu 

Aplikasi KonversiSuhu adalah aplikasi desktop berbasis Java yang dapat mengonversi suhu antar skala:
Celcius, Fahrenheit, Reamur, dan Kelvin.
Dibuat dengan antarmuka grafis Java Swing, aplikasi ini mendukung konversi dua arah antar skala suhu.

## Identitas
- Nama  : Addin Husnan Nadhari
- Npm   : 2210010037
- Kelas : 5B Nonreg Banjarmasin

## Fitur
- Mengonversi suhu antar skala (Celcius, Fahrenheit, Reamur, dan Kelvin).
- Validasi input suhu (hanya angka desimal yang diterima).
- Tombol untuk menghapus dan keluar.

## Struktur Antarmuka
- Input Suhu: Kotak teks untuk memasukkan nilai suhu yang akan dikonversi.
- Pilihan Skala Awal: Dropdown untuk memilih skala suhu awal.
- Pilihan Skala Tujuan: Radio button untuk memilih skala suhu tujuan.
- Hasil Konversi: Label yang menampilkan hasil konversi.
- Tombol:
    - Konversi: Mengonversi suhu sesuai pilihan.
    - Hapus: Menghapus input suhu dan hasil konversi.
    - Keluar: Menutup aplikasi.

## Instalasi
1. Clone repositori:
    `git clone https://github.com/username/KonversiSuhu.git`
2. Buka proyek di IDE Java (NetBeans atau IntelliJ IDEA).
3. Pastikan JDK 8 atau lebih baru sudah terpasang.
4. Jalankan `KonversiSuhu.java` untuk memulai aplikasi.

## Cara Menggunakan
1. Masukkan suhu awal di kotak teks.
2. Pilih skala awal di dropdown.
3. Pilih skala tujuan di radio button.
4. Klik tombol "Konversi" untuk melihat hasil.
5. Gunakan "Hapus" untuk mengatur ulang input, atau "Keluar" untuk menutup aplikasi.

## Struktur Kode
- `KonversiSuhu.java`: Kelas utama yang mengelola antarmuka pengguna dan logika konversi.
  - Metode utama:
    - `toCelcius`, `toFahrenheit`, `toReamur`, `toKelvin` - Metode untuk mengonversi suhu.
    - `konversiSuhu()` - Mengonversi suhu sesuai input pengguna.

