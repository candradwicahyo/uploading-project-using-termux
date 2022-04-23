# uploading-project-using-termux
tutorial uploading files using termux

langkah pertama yang harus dilakukan adalah menjalankan aplikasi termux terlebih dahulu
  * The first step to do is run the termux application first

ketika sudah didalam aplikasi termux, langkah selanjutnya adalah menginstall git lebih dahulu
  * when it is in the termux application, the next step is to install git first

```bash
pkg install git
```

ketika sudah menginstall git, langkah selanjutnya adalah menuju lokasi file yang ingin diupload
  * when you have installed git, the next step is to go to the location of the file you want to upload

```bash
cd lokasi-files
```

ketika sudah berada didalam folder tujuan, lakukan langkah dibawah ini
  * when it is in the destination folder, do the steps below

```bash 
git init
```

jika kalian ingin mengupload 1 file saja, maka lakukan cara dibawah ini
  * if you want to upload only 1 file, then do the method below

```bash
git add nama-file
```

jika kalian ingin mengupload semua file yang ada didalam folder tersebut, lakukan cara dibawah ini
  * if you want to upload all the files in the folder, do the following:

```bash
git add .
```

setelah itu, lakukan commit seperti dibawah ini
  * after that, do the commit as below

```bash
git commit -m "isi sesuka kalian"
```

setelah itu, lakukan git branch dengan nama branch default milik github kalian
  * after that, do a git branch with your github default branch name

```bash
git branch -M nama-branch-kalian
```

default branch github adalah : **master**
  * default branch github is : **master**

lalu, lakukan remote dengan url repo project kalian
  * then, do remote with your project repo url

```bash
git remote add origin https://github.com/username-github-kalian/nama-repository-project-kalian.git
```

lalu, push file kalian
  * then, push your files

```bash
git push -u origin nama-branch-repo-kalian
```

setelah itu, kalian akan disuruh memasukkan sebuah username github kalian. 
kalian tinggal isi dengan username github kalian.
  * after that, you will be asked to enter your github username. you just fill it with your github username

setelah itu, kalian akan disuruh memasukkan sebuah password github kalian.
  * after that, you will be asked to enter your github password.

### catatan
  * ### Note

ketika kalian disuruh untuk memasukkan sebuah password github kalian, kalian harus memasukkan code **personal access token** github milik kalian.
  * when you are prompted to enter your github password, you must enter your personal github access token code.

jika kalian belum punya sebuah **personal access token** github milik kalian sendiri. kalian bisa membuatnya terlebih dahulu di bagian
  * if you don't have a personal access token github of your own. you can make it first in the section

**Settings** -> **Developer settings** -> **Personal access tokens** -> lalu buat access token.
  * **Settings** -> **Developer settings** -> **Personal access tokens** -> then, create access tokens

kalian akan disuruh menulis note / judul access token milik kalian sesuai keinginan kalian
  * you will be asked to write a note / title of your access token according to your wishes

jika kalian menemukan checkbox bertuliskan **repo**, kalian bisa centang checkbox tersebut dan kalian bisa menentukan waktu / expired token milik kalian.
   * if you find a checkbox that says repo, you can check the checkbox and you can determine the time / expiration of your token.

setelah semua itu selesai, kalian akan mendapatkan **personal access token** milik kalian sendiri dan disarankan dari pihak **github** untuk menyalin token tersebut. karena, kalian hanya bisa melihat token itu satu kali di **github**.
  * after all that is done, you will get your own personal access token and it is recommended from github to copy the token. because, you can only see the token once on github.

kalian bisa menyimpan token tersebut ke aplikasi catatan dengan diberikan sebuah password yang aman sebelum menggunakan atau melihat token itu lagi.

tinggal kalian **paste** token tersebut di aplikasi termux. setelah itu files kalian akan sukses terupload

semoga kalian paham dengan penjelasan saya ini. jika kalian masih kebingungan dengan penjelasan saya, silahkan kirimkan keluhan anda ke platform saya di bawah ini
  * You can save the token to the notes application by providing a secure password before using or viewing the token again. all you have to do is paste the token in the termux application. after that your files will be uploaded successfully I hope you understand my explanation. if you are still confused with my explanation, please send your complaint to my platform below

* intagram : **candradwicahyo18**
* email : **candradwicahyo18@gmail.com**

> ditulis oleh **candra dwi cahyo**
> * translate by **Google Translate**
