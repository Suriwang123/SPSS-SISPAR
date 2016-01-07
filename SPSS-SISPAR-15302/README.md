# SPSS-Parallel

Program ini saya buat untuk memenuhi tugas dari Sistem Parallel, yang di ampu oleh Bapak Lukman Heryawan.
Nama  : Budi Triwibowo Yuli W
NIM   : 13/347556/PA/15302


SPSS-Paralel adalah sebuah aplikasi desktop yang digunakan untuk melakukan fungsi fungsi sederhana pada operasi matematis statistik, berikut adalah beberapa fungsi yang terdapat pada SPSS-Paralel, antara lain :

a. Modus
b. Median
c. Mean
d. Range
e. Regresi Linier
f. Standar Deviasi
g. Variansi

Yang membedakan aplikasi yang buatan kami dengan aplikasi SPSS pada umumnya adalah aplikasi ini menggunakan komputasi parallel untuk menghitung fungsi fungsi statistik tersebut. Kami menggunakan cara parallel pada bagian penjumlahan serta perkalian. Dengan menggunakan konsep Single Instruction Multiple Data, operasi penjumlahan dan perkalian dilakukan. Operasi ini dilakukan oleh GPU NVidia, dimana setiap thradnya membutuhkan setengah data, dan setiap thread akan dimasukkan sebuah instruksi yang sama.

System Requirement untuk membuat aplikasi ini antara lain :

1. Software
   - Windows 10 x64 bit
   - Visual Studio 2015
   - [CUDA Toolkit v7.5](https://developer.nvidia.com/cuda-downloads)
2. Hardware
   - Nvidia Graphic Card
3. Package
   - Reogrid - .Net Spreadsheet Component v0.9.1.0
   - Json.Net v7.0.1
   - CUDAfy.Net v1.29

Catatan :

1. Aplikasi dibangun menggunakan bahasa pemrograman c#
2. Package Reogrid dan Json.Net akan secara otomatis terinstall jika kita mem-build ulang Source Code di atas.
3. apabila terdapat permasalah pada Package CUDAfy.Net dan CUDA Toolkit buka link [Codeplex ini](https://cudafy.codeplex.com/) untuk keterangan lebih lanjut.

Sebagai catatan, tugas ini tidak orisinal buatan saya, saya banyak menulis ulang codingan dari Mas Anggara Jatmika Aji, karena secara jujur, saya masih kesulitan dalam melakukan coding secara mandiri.
Mohon dimaklumi, Terimakasih Banyak

Budi Triwibowo Yuli W
13/347556/PA/15302
