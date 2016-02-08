#Instalasi

##Download
NodeJS bisa berjalan di sistem operasi GNU/Linux, Mac OS X, maupun Windows. Untuk mendapatkan software NodeJS bisa menuju alamat [web NodeJS](https://nodejs.org/en/).

##Instalasi di GNU/Linux Debian Jessie

```
wget -b https://nodejs.org/dist/v4.2.6/node-v4.2.6-linux-x64.tar.xz
tar -xJv -f node-v4.2.6-linux-x64.tar.xz
ln -s node-v4.2.6-linux-x64 .node
echo 'export PATH=$PATH:~/.node/bin' >> ~/.bashrc
```

Jika tidak ada kendala maka kita bisa menjalankan perintah di bawah, untuk menguji mesin Node JS sudah terinstall dengan benar.
```
salman@electron:~$ node -v
v4.2.6
```

##Test Instalasi
Untuk menguji instalasi buat skrip kecil --hello.js-- seperti ini,
```
/* Hello, World! program in node.js */
console.log("Hello, World!")
```

Kemudian jalankan dengan perintah,
```
node hello.js
```

