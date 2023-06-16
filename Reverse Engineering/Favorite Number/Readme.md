# Favorite Number - Reverse Engineering

## Attached
![fn1](https://github.com/Bayupangestu18/WRITE-UP_TCP1P/assets/119099396/081e880d-0a70-4d13-8dce-81d6d24c38e6)

Di soal ini kita di beri sebuah excutable linux, kita di suruh untuk mencari flag dengan menebak nomor dari sebuah programnya.

## Sollutions

![fn2](https://github.com/Bayupangestu18/WRITE-UP_TCP1P/assets/119099396/29c54b27-c30c-49a9-9f97-1fbbf3a2bdd0)

Untuk menjalankan file executable nya kita perlu menambahkan permission execute ke dalam file nya agar bisa di jalankan, lalu saat kita jalankan kita di minta untuk memasukkan nomor favorite dari sebuah program tersebut. 

Untuk melihat isi dari sebuah file executable nya kita bisa menggunakan software `IDA Freeware` saat kita buka kita langsung pilih menu main 

![fn3](https://github.com/Bayupangestu18/WRITE-UP_TCP1P/assets/119099396/466212ad-ce38-49d1-a758-ea8fb8c1e355)

lalu kita perlu klik F5 untuk debugging untuk melihat fungsi dari kode main tersebut dan nomor nya ketemu yaitu 69.

![fn4](https://github.com/Bayupangestu18/WRITE-UP_TCP1P/assets/119099396/02151842-36d7-4b62-863e-846bddc61687)

Lalu kita masukkan nomor nya tadi dan boom kita menemukan flagnya

![fn5](https://github.com/Bayupangestu18/WRITE-UP_TCP1P/assets/119099396/1ac5392e-4aad-4f9e-b254-5d1b5553eb0c)

<div align="center">
  <h2> Flag : TCP1P{G00d_w4y_T0_St4rT_R3v3rs1nG} </h2>
  </div>
