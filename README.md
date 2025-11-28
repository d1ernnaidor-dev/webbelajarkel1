# Web Pembelajarankl1

Selamat datang di repositori **webpembelajarankl1** — sebuah proyek halaman web sederhana.

## Deskripsi

Proyek ini berisi sebuah berkas `index.html` untuk menampilkan materi/halaman web pembelajaran.

## Fitur
- Halaman statis sederhana (`index.html`)

## Cara Menjalankan (Local)

1. Buka folder proyek
2. Jalankan file `index.html` di browser dengan meng-klik file, atau gunakan Live Server (VS Code):

   - Jika menggunakan Live Server di VS Code: klik kanan pada `index.html` → `Open with Live Server`.
   - Atau buka file secara langsung di browser (double-click) untuk versi lokal.

## Menambahkan README ke GitHub (Commit & Push)

Jika Anda belum meng-commit file README ke repo GitHub, lakukan langkah berikut di PowerShell (Windows):

```powershell
# Pastikan berada di root project
cd "C:\Users\HP\OneDrive\Desktop\webpembela"

# Inisialisasi git jika belum
git init

# Tambah file README
git add README.md

# Commit perubahan
git commit -m "Add README.md"

# Tambah remote origin (jika belum ada) - ganti URL dengan repositorimu
git remote add origin https://github.com/<USERNAME>/<REPO>.git

# Push ke branch utama (main)
git push -u origin main
```

Catatan: Jika repository Anda sudah ada di GitHub dan terhubung, Anda hanya perlu `git add`, `git commit`, dan `git push`.

## Verifikasi di GitHub

Setelah mem-push, buka halaman GitHub repositori Anda — GitHub akan menampilkan isi README.md di bawah daftar file secara otomatis.

## Kontribusi

Jika Anda ingin menambahkan fitur atau memperbaiki halaman, silahkan membuat Pull Request, atau menghubungi melalui Issues.

## Lisensi

Lisensi default: MIT — ubah sesuai kebutuhan.

---
Jika Anda ingin, saya dapat menambahkan badge (misal: license, build, atau live) dan contoh screenshot untuk mempercantik README.
