# 📖 Penjelasan Perintah Git Dasar

Git adalah **Version Control System (VCS)** yang digunakan untuk mencatat perubahan pada file, melacak riwayat kerja, dan mempermudah kolaborasi dalam tim.  
Beberapa perintah dasar Git yang sangat penting dipahami adalah **`git status`**, **`git diff`**, dan **`git log`**.  

---

## 🔹 1. git status
**Pengertian:**  
`git status` adalah perintah Git untuk **menampilkan status repository**.  

**Penjelasan:**  
Dengan perintah ini, kita dapat mengetahui:  
- ✅ Branch yang sedang aktif.  
- 📂 File yang sudah masuk ke staging area (siap commit).  
- ✏️ File yang dimodifikasi tetapi belum di-*stage*.  
- 🆕 File baru yang belum dilacak oleh Git (*untracked files*).  

👉 Singkatnya, `git status` membantu memastikan kondisi repo sebelum melakukan commit.  

**Contoh:**
```bash
git status

🔹 2. git diff

Pengertian:
git diff adalah perintah Git untuk menampilkan perbedaan isi file antara versi terakhir dengan perubahan terbaru.

Penjelasan:

➕ Menunjukkan baris kode yang ditambahkan (+).

➖ Menunjukkan baris kode yang dihapus (-).

🔍 Bisa digunakan untuk membandingkan working directory, staging area, atau antar commit tertentu.

👉 Dengan git diff, kita bisa mengecek detail perubahan agar yakin sebelum commit.
Contoh

git diff
git diff --cached

🔹 3. git log

Pengertian:
git log adalah perintah Git untuk melihat riwayat commit dalam repository.

Penjelasan:
Informasi yang ditampilkan meliputi:

🔑 Hash commit (ID unik setiap commit).

👤 Author (siapa yang melakukan commit).

🗓️ Tanggal commit.

📝 Pesan commit yang menjelaskan perubahan.

👉 Dengan git log, kita dapat melacak siapa yang mengubah apa, kapan perubahan dilakukan, dan untuk tujuan apa.

Contoh:

git log
git log --oneline
git log --oneline --graph --all

🙋‍♂️ Kontribusi Saya

Dalam proyek ini, saya berkontribusi di bagian penjelasan perintah Git, khususnya:

Git Status → menjelaskan fungsi untuk melihat kondisi repository.

Git Diff → menjelaskan cara melihat perbedaan isi file.

Git Log → menjelaskan penggunaan untuk melihat riwayat commit.

Dengan kontribusi ini, diharapkan pembaca dapat memahami dasar penggunaan Git dan lebih mudah dalam mengelola project menggunakan version control.


