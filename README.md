# latihan-vcs

Instalasi Git • Download Git, buka website resminya Git (git-scm.com). • Kemudian unduh Git sesuai dengan arsitektur komputer. • Selamat, Git sudah terinstal di Windows.
img
Menambahkan Global Config • Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi user.name dan user.email • konfigurasi ini bisa dilakukan untuk global repostiry atau individual repository. • apabila belum dilakukan konfigurasi, akan mengakibatkan terjadi kegagalan saat menjalankan perintah git commit
img
Perintah Dasar Git • git init, perintah untuk membuat repository local • git add, perintah untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit. • git commit, perintah untuk menyimpan perubahan kedalam database git. • git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository. • git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever. • git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory) • git pull, perintah untuk mengambil/mendownload perubahan terbaru dari server repository ke local repository Membuat Reposiory Local • Buka direktory aktif, (buka menggunakan Windows Explorer) • klik kanan pada direktory aktif tersebut, dan pilih menu Git Bash, sehingga muncul git bash commad • Buat direktory project praktikum pertama
img
Membuat Reposiory Local • Jalankan perintah git init, untuk membuat repository local. • Repository baru berhasil di inisialisasi, dengan terbentuknya satu direktori hidden dengan nama .git • Pada direktori tersebut, semua perubahan pada working directory akan disimpan. Menambahkan File baru pada repository • Untuk membuat file dapat menggunakan text editor, lalu menyimpan filenya pada direktori aktif (repository) • disini kita akan coba buat satu file bernama README.md Menambahkan File baru pada repository • Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add. Menambahkan Remote Repository • Remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository, sehingga dapat diakses oleh banyak user. • Untuk menambahkan remote repository server, gunakan perintah git remote add origin Clone Repository • Clone repository, pada dasarnya adalah meng-copy repository server dan secara otomatis membuat satu direktory sesuai dengan nama repositorynya.

