# tugas4

## tutorial git vcs

### kita membuat repositories

1.kita buat folder di pc kita<br>
2.kita ketik $mkdir latihan_buat untuk menambahkan folder<br>
3.kita pindah directory yg barusan kita buat dengan cara $cd latihan_buat <br>
![gambar 1](foto/ss2.png) <br>
4.kita akan inisilasisasi folder git dengan cara $git init <br>
![gambar2](foto/ss3.png)<br>
5.kita menambahkan file baru pada repositori kita dengan cara $echo “# latihan buat repository” >> README.md. dan file README.md telah berhasil kita buat <br>
![gambar3](foto/ss8.png) <br>
6.menambhkan file baru repository dengan cara $git add README.md <br>
![gambar4](foto/ss9.png) <br>
7.selamat kita berhasil menambahkan file baru repository <br>
8.sekarang kita commit atau yang biasa kita kenal menyimpan perubahan ke database dengan cara $git commit -m "file pertama kita" <br>
![gambar5](foto/ss10.png) <br>
9.setelah itu kita membuat respository ke server <br>
10.server repository yang kita buat menggunakan github.com <br>
11.anda harus membuat akun github dulu <br>
![gambar6](foto/ss11.png) <br>
12.setelah anda berhasil membuat akun github anda pada halamam beranda klik start a project lalu buat new repository
![gambar7](foto/ss12.png)<br>
13.membuat repository server
14.menambhakan remote repository dengan cara git remote add orign url
15.mengirim perubahan ke server dengan cara $git push -u orign master (biasa nya ada perintah untuk masukin akun github kita untuk konekin ke server)
16.buka akun github anda dan lihat pada repository nya maka perubahan akan terlihat di situh
