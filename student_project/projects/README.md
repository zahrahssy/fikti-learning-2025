# 📁 Project Akhir

## 🔄 Sync Fork Terlebih Dahulu
1. Masuk ke GitHub dan buka repository hasil *fork* kamu.
2. Klik tombol **Sync fork** → **Update branch**.
3. Pastikan muncul tulisan **“This branch is up to date with ...”**.
4. Setelah itu, buka terminal di folder lokal kamu:
   ```bash
   git pull
   ```

## 📂 Struktur Project
Di dalam repo ini sudah ada contoh struktur project di folder [`sample_project/`](sample_project/). Silakan ikuti struktur tersebut.

### 📁 Langkah Buat Folder Project
1. Masuk ke dalam folder utama project.
2. Masuk ke dalam folder sesuai dengan nama kelompok `/group<number>`

Di dalam folder tersebut, wajib ada 3 komponen sesuai dengan folder [`sample_project/`](sample_project/) berikut:

- 📁 dataset/ → berisi file dataset yang kamu gunakan (.csv)
- 📁 notebooks/ → file export colab notebook (.ipynb) berisi proses analisis kamu
- 📝 README.md → dokumentasi project kamu

## ✅ Commit dan Pull Request
1. Tambahkan, commit, dan push perubahan kamu:
    ```bash
    git add .
    git commit -m "nim - nama - group<number> - perubahan"
    git push origin main 
    ```
2. Masuk ke GitHub, klik Pull Request → New Pull Request, Pastikan:
    - Kiri (base repository): repo utama
    - Kanan (compare): repo kamu
3. Isi judul Pull Request (PR) dengan format:
    ```
    nim - nama - group<number> - perubahan
    ```
4. Klik Create Pull Request.

---

Jika sudah muncul di halaman Pull Request repo utama dan ada nama kamu, artinya sudah berhasil masuk. Saya akan review dan approve. 