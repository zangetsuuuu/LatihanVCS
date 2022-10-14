# Latihan VCS

Nama: Rafif Isdarufa Athallah

NIM: 312210299

Kelas: TI.22.A3

Cara pengunaan Git:

1. Download [Git](https://git-scm.com), kemudian install.
2. Lakukan konfigurasi awal *user.name* dan *user.email* dengan command `git config --global user.name "username"` dan `git config --global user.email "email"`

![Screenshot 2022-10-14 104711](https://user-images.githubusercontent.com/115514467/195761346-1157ba9f-ae23-4454-9d77-663a91d5f9a2.jpg)

3. Buka direktori aktif, lalu klik kanan pada direktori aktif tersebut dan pilih menu Git Bash Here.
4. Kemudian buat direktori baru dengan nama latihan1 dengan command `mkdir latihan1`, selanjutnya masuk ke dalam direktori baru tersebut dengan command `cd latihan1`. 

![Screenshot 2022-10-14 110232](https://user-images.githubusercontent.com/115514467/195762064-fb27f44b-a15d-4b98-a80a-fd9b5a7f9796.jpg)

5. Untuk membuat repositori lokal, gunakan command `git init`.

![Screenshot 2022-10-14 110318](https://user-images.githubusercontent.com/115514467/195763030-b35189ec-ae11-4aa0-92bb-28aaa8056e2b.jpg)

6. Buat satu file bernama README.md dengan command `echo "Latihan 1: Penggunaan GIT" >> README.md`.

![Screenshot 2022-10-14 110340](https://user-images.githubusercontent.com/115514467/195763404-fbe0e634-6e10-4896-85af-c226758012a6.jpg)

7. Untuk menambahkan file yang baru saja dibuat tersebut, gunakan command `git add README.md`.

![Screenshot 2022-10-14 110438](https://user-images.githubusercontent.com/115514467/195764092-4c9d4da1-a6b0-49b4-ba02-61f7363b1186.jpg)

8. Untuk menyimpan perubahan yang ada ke dalam database repositori lokal, gunakan command `git commit -m "File pertama saya"`

![Screenshot 2022-10-14 110545](https://user-images.githubusercontent.com/115514467/195764352-c0a2a9a8-8d46-42a0-98b4-a460f95b4311.jpg)
