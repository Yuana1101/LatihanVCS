# LatihanVCS
Nama: Yuana eka putra yuha<br>
Nim: 312210703<br>
Kelas: TI.22.C.9<br>

# Cara mendownload Git pada git-scm

- Pertama anda harus mendownload Aplikasi  Git, buka website resminya Git  di **git-scm.com** .

![Capture](https://user-images.githubusercontent.com/47426095/196143840-b4702fcf-402a-4231-9057-16b03768fe0f.JPG)
Download lah sesuai dengan bit (32 bit atau 64 bit)laptop anda agar support. Setelah selesai download klik instal

- Lalu klik next simpan file lokasi instal di C:\ProgramFiles\Git(sesuai keinginan anda) , lalu di next saja semua sampai ke step install, TUNGGU SAMPAI SELESAI.

  ![image](https://user-images.githubusercontent.com/56957725/67549597-d8d67380-f72e-11e9-9387-456db6ca1fb8.png)
  
- Setelah melakukan penginstalan, buka cmd untuk mengetahui apakah sudah bisa melakukan proses atau belum. Untuk mengetahui versinya ketikan perintah **git --version.**  Saya memakai versi 2.39.1.windows.1

![3](https://user-images.githubusercontent.com/123886012/215353855-389ff9de-168e-4e00-b4d0-8570ba498b50.jpg)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Cara membuat akun git
- Disini anda harus membuat akun git terlebih dahulu  untuk membuat repository server bukalah link tersebut *http://github.com*

![196099586-9031f90c-b7e7-49bc-9bae-a7f7614994e7](https://user-images.githubusercontent.com/123886012/215354075-d02014a7-232e-488f-aad8-f11c37c36602.png)

### _Membuat repositori baru_

- Nanti anda akan dialihkan ke tab baru untuk membuat repositori baru, isi susuai inspirasi anda setelah selesai klik buat repositori.

![2](https://user-images.githubusercontent.com/123886012/215354290-80e85fbc-b1fc-44eb-81f4-1eff825a7bd6.jpg)

- Lalu nanti di tab baru ada url, url ini akan digunakan untuk remote GitHub.

![4](https://user-images.githubusercontent.com/123886012/215354255-2746de01-fe15-4bc6-b828-f8cd9efe53ee.jpg)

- Klik kanan lalu buka git bash pada folder, kemudian inisiasi folder dengan git init,lalu buat file Readme.md pakai user name dan user email yang tadi sudah dibuat, dengan perintah : 	
      **$ git config --global user.email “nama_user”**
      **$ git config --global user.name “nama_user”**

![5](https://user-images.githubusercontent.com/123886012/215354519-55d7b1f7-7a7a-4ece-b3dd-5272be33d0b2.jpg)

- Lalu jalankan perintah *git init* untuk membuat membuat file kosong berformat GIT. File ini fungsinya untuk menyimpan semua perubahan pada working directory dan file ini terbentuknya hidden.

![5](https://user-images.githubusercontent.com/123886012/215355393-7333fe50-ac4a-4ec7-b0c8-9bfadd851b70.jpg)

- Lalu buat 1 file baru bernama README.md, dengan memasukan perintah _echo “#latihan1” >> README.md.

![5](https://user-images.githubusercontent.com/123886012/215355470-0c5337a6-d5ac-4d97-90ee-fc2f2e5aa2d1.jpg)

- Untuk menyimpan perubahan yang ada kedalam database gunakan perintah git commit -m “komentar"

![5](https://user-images.githubusercontent.com/123886012/215355983-5a591b33-0df1-4df5-b951-e62926e9cedc.jpg)


- Kalau ingin melihat infonya ketik perintah git status. Lalu lakukan git push, jika tidak bisa, lakukan git push --set-upstream origin master untuk autentikasi device

![5](https://user-images.githubusercontent.com/123886012/215356067-ea30f0ba-072c-4632-9b51-8444a78cf084.jpg)

Sekian Dan Terima Kasih



