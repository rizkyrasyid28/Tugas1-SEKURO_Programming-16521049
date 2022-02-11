# Rangkuman GIT & GITHUB

Source : [Playlist GIT & GITHUB Web Programming UNPAS](https://www.youtube.com/watch?v=lTMZxWMjXQU&list=PLFIM0718LjIVknj6sgsSceMqlq242-jNf)

### Rizky Abdillah Rasyid - 16521049
<p>&nbsp;</p>

## [#1 APA ITU GIT & GITHUB?](https://youtu.be/lTMZxWMjXQU)
GIT adalah version control system. Version control system (Revision control system/source code management) adalah system yang mengelola perubahan dari sebuah dokumen, program computer, website dan kumpulan informasi lain. 

Alasan menggunakan version control system karena kesulitan dalam membuat versi dalam program/file, untuk melakukan kolaborasi dengan orang lain dalam membuat program, untuk share  atau show off project. 

GIT adalah Sebuah system yang menyimpan rekaman/snapshot perubahan pada source code. Maanfaat GIT adalah Memungkinkan bekerja berkolaborasi dengan baik, Mengetahui siapa yang melakukan dan kapan perubahan terjadi , Memungkinkan kita untuk Kembali ke keadaan sebelum perubahan (checkout). 

Aplikasi serupa dengan GIT adalah SVN, Mercurial, dan CVS. 

GIT adalah sebuah software/VCS terdistribusi untuk mengelola perubahan file di dalam folder. 

Foldernya disebut repository/repo GIT akan menyimpan history perubahan file melalui commit, seletah commit akan merekam 1 snapshot. Setiap commit ditandai oleh hash. Branch adalah dalam satu repo terdapat cabang biasanya untuk membuat fitur lain. 

Merge adalah menyatukan semua fitur dari beberapa branch Kalian bisa melakukan secara local tetapi harus terinstall software GIT GITHUB adalah layanan cloud untuk menyimpan dan mengelola project/repo GIT. 

Pada GITHUB bisa melakukan fungsi GIT melalui Cloud.GIT dan GITHUB ketika digabungkan dan membuat menjadi remote (repo di clone ke local) dapat menegerjakan suatu project dengan fleksibel dan kolaboratif dengan push dan pull commit.

## [#2 BEKERJA DENGAN GITHUB](https://youtu.be/Q3Id0DgcrXY)
Cara sign up Github
-	username
-	Email address
-	Password
-	Verify account
-	Pilih versi github (Free/Pro)
-	Isi Kuesioner Github
-	Verifikasi email

Untuk membuat Repository, klik start new project atau klik new repository.
Untuk membuar repository,
-	Nama Repository
-	Deskripsi Repo
-	Akses Repo (Public/Private)
-	Instalasi README.md atau Tidak 

Setelah klik create repository, maka punya sebuah Repo dengan URL yang terdapat judul Reponya. Setelah itu bisa membuat file baru atau upload file. Saat Create new file bisa mengedit file di Github langsung. Setelah edit harus tulis commit, tulis pesan commit, deskripsi, dan memilih apakah mau direct commit atau new brach. Untuk perubahan dapat ditrack dengan klik history.

## [#3 GITHUB : BRANCH](https://youtu.be/k1QXd-8VbPY)
Branching adalah membuat git branch yaitu membuat snapshot tanpa menggangu jalur utama (master branch) yang dilakukan untuk membuat firut yang eksperimental atau terdapat 2 orang yang mengerjakan repo yang sama. Cara membuat branch adalah mengedit file yang sudah ada lalu commit dan pilih create new branch. Atau klik branch di halaman repo lalu create branch baru. Merge atau untuk mengembalikan branch ke master branch klik pull request, masuk ke open a pull request, git mengcek apakah kedua branch ini bisa dimerge otomatis jika tidak terdapat perbedaan (conflict). Pull request adalah branch meminta pemilik master untuk menarik perubahan dari branch. Master branch harus meng-confirm merge. Untuk menghapus branch masuk ke menu branches dan klik delete branch. Jika terdapat 2 branch yang ingin dimerge maka perlu melakukan pull request satu-persatu. Conflict harus diselesaikan secara manual

## [#4 GITHUB : FORK](https://youtu.be/8rry2ncZmfg)
Fork atau Forking adalah membuat copy/duplikat dari repo orang lain (beserta history commit). Dapat disebut jembatan antara repo original dan duplikatnya sehingga bisa memodifikasi repo original dan bisa berkontribusi pada repo orang lain.  Fork dan clone berbeda, tetapi fungsinya hampir mirip yaitu menduplikat repo. Fork adalah menduplikat repo orang lain untuk masuk ke github kita, sedangkan Clone menduplikat repo yang ada di github/remote ke local/computer kita. Caranya dengan klik edit pada file di repository orang lain dan akan otomatis fork file tersebut. Atau klik tombol fork di kanan atas halaman repo. Untuk membuat pull request caranya klik new pull request lalu klik create pull request dan bisa ditambahkan pesan setelah itu tunggu apakah diterima(merge) atau tidak repo forknya oleh pemilik repo asli.

## [#5 BEKERJA DENGAN GIT](https://youtu.be/e-6OkXRqWaE)
Cara install git
-	Buka https://git-scm.com/
-	Download GIT sesuai versi dan OS
-	Install seperti biasa
-	Pilih text editor
-	Install Selesai

Ketika install git, sudah include git bash yang mirip seperti cmd prompt.
Git Command (local)
1. Inisialisasi repo
```
$ git init 
```
2. Menambahkan File
```
$ git add <file(s)>
```
3. Mengetahui Status dari Repository
```
$ git status
```
4. Commit Perubahan
```
$ git commit
```
5. Memasukkan Konfigurasi ke dalam GIT
```
$ git config
```
6. Membuat Branch
```
$ git branch
```
7. Menampilkan Sebuah Command
```
$ git help
```
3 area repo 
-	Working tree = folder tempat bekerja
-	Staging area = memberi tahu git bahwa sudah melakukan perubahan
-	History = berubahan sudah di-commit

Staging area dan history akan tersimpan kedalam semua file ke dalam folder .git yang tersembunyi. ketika sudah membuat folder dan sudah diinialisasi menjadi repo maka git akan memantau folder tersebut. Jika ada perubahan bisa disimpan pada staging area dengan command  git add, jika sudah oke maka disimpan ke dalam history git commit.

## [#6 GIT BRANCH & MERGE](https://youtu.be/EGl7KxVOyNs)