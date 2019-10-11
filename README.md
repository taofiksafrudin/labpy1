#latihan 1
#latihan 1 >> README.md


Latihan 1 #cara menggunakan git
•	Pertama kita harus mendownload aplikasi git, dengan membuka website resminya (git-scm.com)  
![Capture](https://user-images.githubusercontent.com/56193251/66633731-b3793e00-ec35-11e9-8d7e-dee39d3d3060.PNG)

Kita install terlebih dahulu
•	Setelah terinsltall, kita lakukan configurasi user.name dan user.emai. perintah yang harus ditulis ialah : (git config –global user.name “name_user”)
                          (git config –global user.emai “email_user)
                          
 ![2](https://user-images.githubusercontent.com/56193251/66634947-5d59ca00-ec38-11e9-9da7-8c3d0efe622f.PNG)
 
•	Membuat repository local
•	Buka directory aktif misalnya : c:/labs_pemograman1 (buka menggunakan Windows explore)
•	Klik kanan pada directory aktif tersebut, dan pilih menu git bash, sehingga muncul git bash commad
![3](https://user-images.githubusercontent.com/56193251/66635160-c6414200-ec38-11e9-92d4-898a1148755a.PNG)
 
•	Lalu ketikan perintah (mkdir latihan1)
                                       (cd latihan1)
•	Directory aktif menjadi C:/Labs_pemograman1/latihan1
 ![4](https://user-images.githubusercontent.com/56193251/66635286-128c8200-ec39-11e9-8e29-305dfff43747.PNG)

 
•	Lalu jalankan perintah git ini, untuk membuat repositorynlocal
                      (git ini)
•	Menambahkan  File baru pada Repository
•	Kita akan mencoba membuat satu file README.md (text file) dengan menuliskan perintah (echo “#lathan 1 >> README.md)
•	Untuk menambahkan file tersebut kita kita gunakan perintah (git add README.md)
 
•	Commit (menyimpan pe
•	rubahan ke database)
•	Untuk menyimpan perubahan tersebut kita ketikan perintah (git commit –m “komentar commit”)
•	Perubhan berasil tersimpan
 
8.	Membuat repository server
•	Pertama kita akan membuka website https://github.com
•	kita harus membuat akun terlebih dahulu di github
•	pada halaman github, klik tombol star a project, atau klik new Repository pada icon (+)
 
•	isi name repostorynya :labpy2
•	lalu klik create repository
 
9.	Menambahkan Remote Repository 
•	Untuk menambahkan remote repository server, kita ketik perintah (git remote add origin [url]) 
Git  remote add origin https://github.com/taofiksafrudin/labpy2.git
10.	Push (mengirim perubahan ke server)
•	Untuk melakukan perubahan kita perlu menggunakan perintah (git push –u origin master)   
•	Perintah ini akan menyuruh kita memasukan username dan password pad akun github
 
11.	Melihat hasil pada server repository
•	Buka halaman github.com, arahkan pada repositorynya
•	Maka perubahan akan terlihat pada halamn tersebut
 
12.	Clone repository
•	Untuk melakukan cloning, gunakan printah (git clone [url
•	(git clone htpps://github.com/taofiksafrudin/labpy2.git

