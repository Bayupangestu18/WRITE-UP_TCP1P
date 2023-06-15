# Hidden in One - Forensic

## Attached
![hd1](https://github.com/Bayupangestu18/WRITE-UP_CTF-TKJ/assets/119099396/2c11cfbb-7958-4eb0-af69-197f80e1ace6)

Di soal ini kita di berikan sebuah zip dan kita di suruh untuk mencari flag dari dalam zip tersebut saat kita ekstrak secara biasa flag nya keluar tetapi itu fake flag.

## Solutions
Jadi untuk menemukan flag nya kita perlu melihat lebih dalam lagi ke zip nya kita bisa menggunakan binwalk, saat kita lihat dengan binwalk ada file png lagi seperti gambar di bawah ini 

![hd2](https://github.com/Bayupangestu18/WRITE-UP_CTF-TKJ/assets/119099396/b38994cd-886e-4f11-ae87-822c9f48350b)

Tetapi saat kita ekstrak menggunakan binwalk foto nya tidak keluar 

![hd3](https://github.com/Bayupangestu18/WRITE-UP_CTF-TKJ/assets/119099396/f7fcf577-a3ef-4b14-86a8-c9af0afbde8b)

Jadi saya menggunakan foremost untuk mengambil file png yang tersembunyi seperti gambar di bawah ini !!

![hd4](https://github.com/Bayupangestu18/WRITE-UP_CTF-TKJ/assets/119099396/85ec785f-c044-4815-973b-46f953ff5353)

dan akhir nya foto nya dapat kita ambil dan boom flag nya ketemu ternyata flagnya berada dalam foto tersebut.

![00000000](https://github.com/Bayupangestu18/WRITE-UP_CTF-TKJ/assets/119099396/ba1be57f-0147-4e65-b6e6-8ecaa1d96f51)

<div align="center">
  <h2> Flag : TCP1P{H1dd3N_1n_Pl41n_S1gHt} </h2>
  </div>

