# Aplikasi sewa motor
##  Aplikasi ini merupakan aplikasi perhitungan yang menggunakan penjumlahan di dalamnya 

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)




## Fitur aplikasi sewa motor

- Penjumlahan


## Tech

Aplikasi ini dikerjakan menggunakan:

- Aplikasi sewa motor ini dikerjakan menggunakan intelej idea 

## Requirement
- aplikasi intelej idea 

## Class 
- SewaMotor
## method



```sh
private static final int HARGA_*
→ Konstant harga sewa per hari untuk tiap jenis motor.

main(String[] args)
→ Titik masuk program. Mengambil input pengguna (nama, lama, jenis), menentukan harga, menghitung total, lalu menampilkan nota.

getStringInput(Scanner, String)
→ Membaca input teks (nama).

getIntInput(Scanner, String)
→ Membaca input angka (lama sewa, jenis). Catatan: saat ini memakai Integer.parseInt(input.nextLine()) — jika pengguna memasukkan teks yang bukan angka, program akan crash (NumberFormatException).

tentukanHarga(int jenis)
→ Mengembalikan harga per hari sesuai kode jenis (1/2/3). Mengembalikan 0 untuk jenis tidak valid.

getNamaMotor(int jenis)
→ Mengubah kode jenis jadi nama motor (Beat/Vario/NMAX).

hitungTotal(int harga, int lama)
→ Mengalikan harga per hari dengan lama sewa (hari).

tampilkanNota(...)
→ Mencetak nota akhir ke console.


 


