# 🚀 Belajar GitHub: Panduan Asik 🚀

GitHub itu seru banget buat kamu yang mau ngoding bareng-bareng atau mau nge-track perubahan kodingan dengan rapi. Ini semacam social media-nya developer! Di sini kamu bisa bareng-bareng bikin project, bagi-bagi kode, atau bahkan gabung buat kontribusi ke project open-source.

> **Info** Tugas dan kerjaan akan di infoin di bagian [Kerjaan Modul](#-kerjaan-modul).

## 🔥 Dasar-Dasar GitHub yang Perlu Kamu Tahu

1. **Repo (Repository)**: Tempat kita simpen semua kode + sejarah perubahannya. Anggap aja ini kayak folder project kamu tapi bisa diakses online.
2. **Branch**: Mirip jalan bercabang, kamu bisa coba fitur baru atau ngefix bug di branch ini tanpa ganggu branch utama (biasanya namanya `main` atau `master`).
3. **Commit**: Simpen perubahan kode kamu di repo, dan kasih pesan singkat buat cerita perubahan apa aja yang dilakukan.
4. **Pull Request (PR)**: Permintaan buat gabungin branch-mu ke branch lain (biasanya ke branch utama). Ini semacam approval, jadi orang lain bisa cek dulu sebelum kodenya masuk.
5. **Fork**: Copy-an repo orang lain ke akunmu, biar kamu bisa modif sesuka hati tanpa ganggu project aslinya.
6. **Issues**: Tempat curhat masalah atau ide-ide buat project. Biasanya dipake buat catet bug, ide fitur baru, atau checklist to-do biar rapi.

---

## 💻 Langkah-Langkah Bikin Project di GitHub

### 1. **Buat Akun GitHub**

   Daftar dulu di [GitHub.com](https://github.com). Cuma butuh email dan beberapa langkah, dan akun GitHub kamu langsung jadi!

### 2. **Bikin Repository Baru**

   - Di halaman depan GitHub, klik **New** buat bikin repo.
   - Masukin nama repo + deskripsi singkat.
   - Pilih mau repo-nya **public** (buat dilihat semua orang) atau **private** (buat kamu sendiri atau tim kecil).
   - Terakhir, klik **Create repository**.

### 3. **Sambungin Repo Lokal ke GitHub**

   Misal kamu udah punya project di laptop, tinggal buka terminal atau cmd dan ketik:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/username/repositoryname.git
   git push -u origin main
  ```
(Jangan lupa ganti username dan repositoryname sama username dan nama repo kamu ya!)

### 4. **Bikin Branch Buat Fitur Baru**
  Setiap fitur baru bisa kamu bikin di branch terpisah biar nggak ganggu branch utama:

  ```bash
Copy code
git checkout -b nama_branch
Ini bikin kamu bisa ngembangin fitur atau ngefix bug lebih bebas.
```
### 5. **Commit dan Push Perubahan**
  Setiap kali ada update di kode, jangan lupa commit dan push ke GitHub:

```bash
Copy code
git add .
git commit -m "Pesan commit"
git push origin nama_branch
```
### 6. **Pull Request dan Merge**
  Di halaman repo GitHub, buka Pull Requests buat bikin PR baru.
  Minta review kalau perlu, dan kalau udah fix tinggal merge biar kode masuk ke branch utama.
  
### 7. **Otomasi dengan GitHub Actions**
  Pake fitur GitHub Actions buat otomatisin berbagai tugas, kayak testing kode, build, sampai deployment. Bisa kamu setup dengan bikin file .yml di dalam folder .github/workflows.
  
---

## ⚡️ Tips Jagoan Pake GitHub
Gunakan Pesan Commit yang Bikin Orang Ngerti: Jangan cuma “update” doang, kasih penjelasan biar orang tau perubahan apa yang terjadi.
Manfaatin Branch untuk Eksperimen Fitur Baru: Setiap fitur baru, coba di branch sendiri biar kode utama tetep bersih.
Pakai Pull Request Buat Review Kode: Biar orang lain bisa ngecek dan kasih saran sebelum gabungin kode ke main.
Gunakan Issues Buat Track Progress: Bisa buat checklist, ide, atau buat diskusi hal-hal penting.

---

## 🌟 Manfaat Pake GitHub
Bisa Kolaborasi Bareng-Bareng: Ngoding bareng tim atau kontribusi ke project orang lain jadi lebih gampang.
Sistem Versi yang Teratur: Semua perubahan bisa dilacak, jadi nggak takut kode hilang atau keliru.
Otomatisasi dengan GitHub Actions: Dari testing sampai deploy bisa otomatis, tinggal setup aja!
Dukungan Open Source: Buat kamu yang mau share project ke dunia atau kontribusi di project keren lainnya.
Nah, itu dia dasar-dasar GitHub yang wajib kamu tau! Semoga bisa langsung dipraktekin buat project seru kamu! 🎉

---

## 📝 Kerjaan Modul
*Kerjaan dan tugas bakal dikasih disini ya... Tungguin aja...*


---
