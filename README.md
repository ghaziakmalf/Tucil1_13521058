# 24 Game Solver dengan Algoritma Brute Force
## Deskripsi Program
Program ini merupakan program yang dapat menyelesaikan permainan kartu 24 dengan menggunakan algoritma _brute force_. Permainan kartu 24 adalah permainan kartu aritmatika dengan tujuan mencari cara untuk mengubah 4 buah angka random sehingga mendapatkan hasil akhir sejumlah 24. Pada awal permainan moderator atau salah satu pemain mengambil 4 kartu dari dek yang sudah dikocok secara random. Permainan berakhir ketika pemain berhasil menemukan solusi untuk membuat kumpulan nilainya menjadi 24. Pengubahan nilai tersebut dapat dilakukan menggunakan operasi dasar matematika penjumlahan (+), pengurangan (-), perkalian (×), divisi (/) dan tanda kurung ( () ). Tiap kartu harus digunakan tepat sekali dan urutan penggunaannya bebas.

Program menerima input pilihan masukan kartu, yaitu dengan input secara manual ataupun secara acak. Apabila input secara manual, program akan meminta 4 kartu dari user berupa A, 2, 3, 4, 5, 6, 7, 8, 9, 10, J, Q, K. As bernilai 1, Jack bernilai 11, Queen bernilai 12, King bernilai 13, sedangkan kartu bilangan memiliki nilai dari bilangan itu sendiri. Apabila input secara acak, program akan menjalankan algoritma random untuk mengambil kartu secara acak tanpa adanya input dari user. Program akan mencari solusi dari 4 kartu tersebut dengan menggunakan algoritma _brute force_ dan akan menampilkan solusi yang ditemukan. Setelah itu, user dapat memilih untuk menyimpan solusi ke dalam file.

## Requirement
- GNU g++ compiler

## Cara Menggunakan Program
Program dapat di-_compile_ dengan cara:
```bash
g++ src/24GameSolver.cpp -o bin/24GameSolver
```
Program dapat dijalankan dengan cara:
```bash
bin/24GameSolver.exe

atau

Jalankan program langsung dengan double klik file '24GameSolver' dalam folder 'bin'
```

## Author
Program ini dibuat oleh:
- 13521058 - Ghazi Akmal Fauzan
