## Basic Git Concepts

Git adalah tools untuk mengelola perubahan kode (version control system).
Git menggunakan sistem distributed revision control, artinya setiap developer punya salinan lengkap repository di komputernya (tidak bergantung pada satu server saja).

4 konsep di sini:
- **Repository (Repo)** → tempat penyimpanan project  
- **Commit** → menyimpan perubahan kode (seperti “save point”)  
- **Branch** → cabang untuk mengerjakan fitur tanpa mengganggu kode utama  
- **Merge** → menggabungkan perubahan dari branch ke branch lain  

---

## Git Workflow (Simple)

Biasanya urutannya seperti ini:

```bash
git init          # buat repository
git add .         # pilih file yang mau disimpan
git commit -m "pesan"   # simpan perubahan
git push          # kirim ke server (misalnya GitHub)
