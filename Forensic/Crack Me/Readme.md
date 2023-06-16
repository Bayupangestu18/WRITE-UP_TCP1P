# Crack Me - Forensic

## Attached
![cr11](https://github.com/Bayupangestu18/WRITE-UP_TCP1P/assets/119099396/b2da43ca-f020-4567-b69f-66f8bada248a)

Untuk soal crack me ini kita di beri file zip dan file nya di password dan kita di suruh mencari passwordnya.

## Solutions

Di dalam file zip itu ada file flag.txt tetapi saat kita buka tidak bisa karena di password jadi kita harus mencari password nya, untuk mencari passwordnya kita bisa bruteforce menggunakan tools john the ripper untuk crack atau brute force password zip.

Pertama kita ubah dulu zip nya menjadi file txt dengan zip2john seperti gambar di bawah ini !!

![cr1](https://github.com/Bayupangestu18/WRITE-UP_TCP1P/assets/119099396/af6ceb43-1636-4611-a144-096939bb2ef0)

Setelah menjadi txt selanjutnya kita bisa crack passwordnya dengan john the ripper, saat kita menggunakan john the ripper tanpa menyertakan lokasi wordlist atau tanpa menyertakan pssword nya maka john the ripper itu otomatis memakai wordlist nya sendiri yaitu `john.lst`

![cr4](https://github.com/Bayupangestu18/WRITE-UP_TCP1P/assets/119099396/ac48e36f-7be0-40e1-939f-a9897a1a3416)

Nah passsword nya udh ketemu seperti gambar di atas, lalu kita tinggal extract memasukkan password nya.

![cr2](https://github.com/Bayupangestu18/WRITE-UP_TCP1P/assets/119099396/2f6c1ff4-bb83-4128-914a-8f5ae2399c97)

nah akhirnya ketemu flagnya 

![cr5](https://github.com/Bayupangestu18/WRITE-UP_TCP1P/assets/119099396/28ef220a-769a-42e7-b8db-ac0b87de0ca0)

<div align="center">
  <h2> Flag : TCP1P{cR4ck_Z1p_With_joHn_Th3_riPp3r} </h2>
  </div>
