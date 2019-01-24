# latihan1

TUTORIAL CARA MENGGUNAKAN GIT

Git adalah pengontrol versi yang bertugas mencatat setiap perubahan pada file proyek yang dikerjakan oleh banyak orang maupun sendiri. Git dikenal juga dengan distributed revision control (VCS terdistribusi), artinya penyimpanan database Git tidak hanya berada dalam satu tempat saja.

Langkah-langkah Install GIT di berbagai jenis sistem

Install GIT di Windows

Menginstall GIT di Windows sangat mudah, cukup dengan mendownload dan menjalankan instalasinya. Ikuti langkah berikut ini untuk meng-install GIT di Windows:

1. Buka website ini dan download installer GIT untuk Windows.
2. Setelah download, buka file tersebut untuk menjalankan proses instalasi. Ikuti semua instruksi, klik Next dan Finish hingga semua  proses instalasi selesai.

PERINTAH DASAR GIT

1. git init, perintah untuk membuat repository local
2. git add, perintah untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit.
3. git commit, perintah untuk menyimpan perubahan kedalam database git.
4. git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository.
5. git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever.
6. git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory).

Langkah-Langkah Menggunakan Git

1. Klik kanan pada monotir 
2. Klik " Git Bash Here"
3. Maka akan ada tampilan commond pront seperti dibawah ini
4. Buka Drive yang ingin dipakai semisal Drive D dengan perintah cd /d 
5. Buat directory dengan printah "mkdir" sebagai contoh directory Pemograman1 
6. Buka directory Pemograman1 dengan perintah cd Pemograman1
7. Buat directory latihan1 dan buka directory latihan1
8. Menambahkan file baru pada repository dengan perintah echo "#latihan1" >> README.md
9. Jalankan perintah git init untuk menjalankan repository local
10. Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add README.md
11. Untuk menyimpan perubahaan yang ada kedalam database repository local, gunakan perintah git commit -m "File pertama saya"
12. Buat repository server, isi nama repositorynya semisal : latihan1 
    lalu klik tombol Creat repository
13. Menambahkan remote repository. remote repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan  sehingga dapat diakses oleh banyak user
14. Mengirim perubahan ke server dengan perintah git push -u origin master 
15. Melihat hasil pada repository, buka laman github.com arahkan pada repositorynya. Maka perubahan akan terlihat pada laman tersebut 
