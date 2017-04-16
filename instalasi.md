#Instalasi

##Download
NodeJS bisa berjalan di sistem operasi GNU/Linux, Mac OS X, maupun Windows. Untuk mendapatkan software NodeJS bisa menuju alamat [web NodeJS](https://nodejs.org/en/).

##Instalasi di GNU/Linux Debian Jessie

```
wget -b --no-check-certificate https://nodejs.org/dist/v6.10.2/node-v6.10.2-linux-x64.tar.xz
tar -xJ -f node-v6.10.2-linux-x64.tar.xz
ln -s node-v6.10.2-linux-x64 .node
echo 'export PATH=$PATH:~/.node/bin' >> ~/.bashrc
```

Jika tidak ada kendala maka kita bisa menjalankan perintah di bawah, untuk menguji mesin Node JS sudah terinstall dengan benar.
```
salman@seruni:~$ node -v
v6.10.2
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
Hello, World!
```

