# 🧩 Praktikum DevOps Pertemuan 5

Proyek ini digunakan untuk **latihan kolaborasi menggunakan GitHub** dalam mata kuliah *Development and Operations (DevOps)*.

## 🎯 Tujuan
Mahasiswa dapat memahami konsep **Continuous Integration (CI)** dengan praktik langsung berkolaborasi di satu proyek bersama.

---

## 📘 Langkah Praktikum

1. **Fork** repository ini ke akun GitHub Anda.  
2. **Clone** ke laptop/HP (via Termux atau aplikasi GitHub).  
3. Buat **branch baru** dengan nama Anda:
   ```bash
   git checkout -b nama-anda
   ```
4. Edit file `index.html`:  
   Tambahkan kartu nama Anda di bagian `<div class="cards">`, contohnya:
   ```html
   <div class="card">
     <h3>Nama Anda</h3>
     <p>Mahasiswa Pertiba</p>
   </div>
   ```
5. **Commit dan push** perubahan Anda:
   ```bash
   git add .
   git commit -m "Menambahkan nama [Nama Anda]"
   git push origin nama-anda
   ```
6. Di GitHub, buat **Pull Request (PR)** ke branch `main` milik dosen.  
7. Setelah PR diterima → halaman otomatis terupdate di GitHub Pages 🎉  

---

## 💡 Tips
- Gunakan browser mode desktop atau aplikasi GitHub untuk kemudahan edit.  
- Jika muncul konflik, diskusikan bareng di Zoom — ini bagian penting dari DevOps!
