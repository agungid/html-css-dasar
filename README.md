# Git Command Documentation

Berikut adalah beberapa perintah Git yang umum digunakan untuk kontrol versi.

## 1. `git init`

Perintah `git init` digunakan untuk membuat repositori Git baru. Ini menginisialisasi repositori kosong di direktori saat ini.

## 2. `git clone`

Perintah `git clone` digunakan untuk membuat salinan lokal dari repositori remote. Ini mengunduh seluruh repositori, termasuk semua cabang dan riwayat commit.

## 3. `git add`

Perintah `git add` digunakan untuk menambahkan file ke area staging. Ini mempersiapkan file untuk commit selanjutnya.

## 4. `git commit`

Perintah `git commit` digunakan untuk membuat commit baru dengan perubahan yang ada di area staging. Ini memungkinkan Anda untuk memberikan pesan commit untuk menjelaskan perubahan yang dilakukan.

## 5. `git push`

Perintah `git push` digunakan untuk mengunggah commit lokal ke repositori remote. Ini memperbarui repositori remote dengan perubahan lokal Anda.

## 6. `git pull`

Perintah `git pull` digunakan untuk mengambil dan menggabungkan perubahan dari repositori remote. Ini memperbarui repositori lokal Anda dengan perubahan terbaru dari repositori remote.

## 7. `git branch`

Perintah `git branch` digunakan untuk menampilkan, membuat, atau menghapus cabang di repositori. Ini memungkinkan Anda untuk bekerja pada cabang yang berbeda untuk fitur atau perbaikan bug yang berbeda.

## 8. `git checkout`

Perintah `git checkout` digunakan untuk beralih antara cabang atau mengembalikan file dari commit tertentu. Ini memungkinkan Anda untuk menjelajahi versi kode yang berbeda.

## 9. `git merge`

Perintah `git merge` digunakan untuk menggabungkan perubahan dari cabang yang berbeda. Ini mengintegrasikan perubahan dari satu cabang ke cabang lainnya.

## 10. `git status`

Perintah `git status` digunakan untuk menampilkan status terkini dari repositori. Ini menunjukkan file mana yang dimodifikasi, di-staging, atau tidak terlacak.

# Menganti nama branch di lokal dan repository

## 11. `git branch -m`

Perintah `git branch -m` digunakan untuk mengganti nama branch di lokal. Anda dapat menggunakan perintah ini dengan menentukan nama branch lama dan nama branch baru yang diinginkan.

Contoh penggunaan:
```bash
git branch -m nama-branch-lama nama-branch-baru
```

## 12. `git push origin :nama-branch-lama nama-branch-baru`

Perintah `git push origin :nama-branch-lama nama-branch-baru` digunakan untuk mengganti nama branch di repositori remote. Anda dapat menggunakan perintah ini untuk menghapus branch lama dan mengunggah branch baru dengan nama yang diinginkan.

Contoh penggunaan:
```bash
git push origin :nama-branch-lama nama-branch-baru
```


