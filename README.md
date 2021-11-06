# Membuat repository baru

````
langkah-langkahnya sbb:
- server yang digunakan adalah http://github.com
- buatlah akun terlebih dahulu setelah itu login
- buka laman github,cari icon(+)klil new repository
- seperti gambar di bawah ini
````
![img](https://raw.githubusercontent.com/RAIS14/labpy1/master/repository_baru.png)
````
- isi nama repositorynya,misal : **labpy1**
- lalu klik tombol create repository
- seperti gambar dibawah ini
````
![img](https://raw.githubusercontent.com/RAIS14/labpy1/master/nama_repository.png)
````
- lalu untuk menambahkan file baru(README.md) pada repository
- tuliskan perintah dasar git seperti contoh gambar dibawah ini dengan memakai Git yang sudah diinstal di pc 
````
![img](https://raw.githubusercontent.com/RAIS14/labpy1/master/perintah_dasar_git.png)
````
perintah dasar git :

- git init = untuk membuat repository local
- git add = untuk menambahkan file baru,atau perubahan pada file pada staging sebelum proses commit
- git commit = untuk menyimpan perubahan kedalam database git
- git push -u origin master = untuk mengirim perubahan pada repository local menuju server repository
- git clone [url] = untuk membuat working directory yang diambil dari repository server
- git remote add origin [url] = untuk menambahkan remote server/repository server pada local repository
````

## Mencari nilai terbesar dari 3 bilangan
````
** berikut ini program python nya**
````
````
a=int (input ('bilangan a : '))
b=int (input ('bilangan b : '))
c=int (input ('bilangan c : '))

if a>b :
	if a>c :
		print(a)
	else :
		print (c)
elif b>c :
	print(b)
else :
	print (c)
````
### hasil program :

![img](https://raw.githubusercontent.com/RAIS14/labpy1/master/hasil_program.png		)

#### Penjelasan program

````
input bilangan a=5
input bilangan b=7
input bilangan c=11

jadi nilai terbesar adalah : 11

````
