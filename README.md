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


# Membuat SSH Key dan Menambahkannya ke GitHub

Untuk membuat SSH key dan menambahkannya ke akun GitHub Anda, ikuti langkah-langkah berikut:

1. Buka terminal atau command prompt Anda.

2. Generate SSH key baru dengan menjalankan perintah berikut:
    ```bash
    ssh-keygen -t rsa -b 4096 -C "email_anda@example.com"
    ```
    Ganti "email_anda@example.com" dengan alamat email Anda sendiri.

3. Anda akan diminta untuk memasukkan lokasi file untuk menyimpan key. Tekan Enter untuk menyimpannya di lokasi default.

4. Anda juga akan diminta untuk memasukkan passphrase. Disarankan untuk menggunakan passphrase yang kuat untuk keamanan tambahan. Tekan Enter jika Anda ingin melewati pengaturan passphrase.

5. Setelah key berhasil dibuat, Anda dapat menampilkan key dengan menjalankan perintah berikut:
    ```bash
    cat ~/.ssh/id_rsa.pub
    ```

6. Salin seluruh output dari perintah tersebut.

7. Buka pengaturan akun GitHub Anda dan navigasikan ke bagian "SSH and GPG keys".

8. Klik "New SSH key" atau "Add SSH key".

9. Beri judul pada SSH key Anda (misalnya, "SSH Key Saya").

10. Tempelkan key yang telah Anda salin ke kolom "Key".

11. Klik "Add SSH key" untuk menyimpannya.

Sekarang Anda telah berhasil membuat SSH key dan menambahkannya ke akun GitHub Anda. Anda sekarang dapat menggunakan SSH untuk berinteraksi dengan aman dengan repositori-repositori Anda di GitHub.


