+++
author = "assistant lecture"
title = "Tugas 5 📖 Array"
date = "2021-10-18"
description = "Tugas 5 📖 Array"
tags = [
    "assignments",
    "java",
]
+++

{{< notice info >}}
`Deadine`\
**SI** Rabu, 20 Oktober 2021 Pukul 09:30 wib\
**MI** Jumat, 22 Oktober 2021 Pukul 09:30 wib

`Peraturan`\
Nama file program **Array.java**
{{< /notice >}}
 
## ▶ Java 🤍 Statistika

**Deskripsi**

Buatlah sebuah array (nama variable array-nya bebas) yang berisi data sebagai berikut `15, 15, 15, 15, 16, 16, 17, 17, 20, 21, 23, 23, 28, 30, 32, 35, 37, 38, 40, 41, 41, 43, 45, 45, 49, 50, 53, 54, 55, 55, 59, 59, 60, 63, 65, 65, 67, 70, 71, 72, 72, 75, 75, 78, 80, 82, 83, 84, 85, 85, 85, 88, 89, 89, 90, 92, 93, 94, 95, 95, 96, 96, 97, 97, 98, 98, 98, 99, 99, 99, 99, 99, 99, 99, 99`

**Tentukanlah** 
- `Total`
- `Rata-Rata`
- `Kuartil 1`
- `Kuartil 2 (median)`
- `Kuartil 3`

**Tips**

- Gunakan perulangan & beberapa operasi matematika
- Untuk rata-rata gunakan tipe data **double**
- Dibawah ini merupakan rumus kuartil untuk **n+1** habis dibagi 4\
`n = banyaknya data`


![rumus-quartile](/assets/quartile.png "rumus-quartile untu k n + 1 % 4 == 0")

**Ket**
- **x** pada soal mengindikasikan *letak*
- misalnya, jika didapat **x** nya = 3, maka hasil quartil terletak pada posisi ke 3 pada kumpulan data (yg sudah di urutkan)
- ingat, **indeks array** dimulai dari **0**

**Output**

Total = 4816\
Rata-rata = 64.0\
Letak q1: x19 = 40\
Letak q2: x38 = 70\
Letak q3: x57 = 93