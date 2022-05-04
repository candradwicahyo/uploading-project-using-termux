# uploading file using termux

install terlebih dahulu sebuah **git** di aplikasi **termux** milik kalian.

```bash
pkg install git
```

lakukan config terlebih dahulu sebelum mengeksekusi

```bash
git config --global user.name "username github kalian"
git config --global user.mail email github kalian
```

setelah pemasangan selesai. lakukan perintah dibawah ini

```bash
git init
git add nama-file (untuk mengupload 1 file)
git add . (untuk mengupload semua file)
git commut -m "isi sesuka kalian"
git branch -M branch-github-kalian (default: master atau main)
git remote add origin https://github.com/candradwicahyo/project-kalian.git (bila menggunakan metode http / https)
git push -u origin branch-github-kalian (default: master atau main)
```

setelah itu, kalian akan disuruh memasukkan sebuah username github dan password github milik kalian.

isi username dengan username github kalian dan isi password dengan memasukkan **personal access token**

bagaimana cara membuat **personal access token**?

masuk ke **Settings** ~> **Developer Settings** ~> **Personal Access Tokens**

ketika ada input checkbox dengan tulisan berupa **repo**, silahkan centang input tersebut. lalu sesuaikan waktu **expired** dari token milik kalian sendiri.

- [X] repo


lalu tempel / paste di termux kalian. selesai

> ditulis oleh **candra dwi cahyo**
