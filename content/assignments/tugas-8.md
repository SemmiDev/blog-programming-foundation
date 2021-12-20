+++
author = "assistant lecture"
title = "Tugas 8 📖 Error Handling"
date = "2021-12-08"
description = "Tugas 8 📖 Error Handling"
tags = [
    "assignments",
    "java",
]
+++

{{< notice info >}}
`Deadline`\
**SI** Rabu, 17 November 2021 Pukul 09:30 WIB\
**MI** Jumat, 19 November 2021 Pukul 09:30 WIB

`Peraturan`\
Nama file program **ErrorHandling.java**
{{< /notice >}}

## ▶ Soal 1
Method **bagiDonk()** berfungsi untuk membagi bilangan **x** dengan bilangan **y**. Silahkan handle **Exception**/**Error** yang akan terjadi pada method tersebut ketika nilai **pembagi**/**y** nya bernilai **0** dengan menggunakan mekanisme **try, catch & finally**.

Jika **Exception** terjadi maka tampikan `Upsss: pembagi tidak boleh 0 yee`
Kemudian di block **finally** tampilkan `Hehehehehe`

Jika tidak terjadi **Exception** maka tampilkan hasil pembagiannya, Kemudian di block **finally** juga menampilkan `Hehehehehe`

## ▶ Soal 2
Method **bacaIsiArray()** berfungsi untuk menampilkan isi array **students[]** berdasarkan nilai **index**. Silahkan handle **Exception**/**Error** yang akan terjadi pada method tersebut ketika nilai **index** nya lebih dari **panjang array-1** dengan menggunakan mekanisme **try, catch & finally**.

Jika **Exception** terjadi maka tampikan `Upsss: index melebihi panjang array-1`
Kemudian di block **finally** tampilkan `Hehehehehe`

Jika tidak terjadi **Exception** maka tampilkan isi array berdasarkan **index** 
Kemudian di block **finally** juga menampilkan `Hehehehehe`

## ▶ Template
```Java
public class ErrorHandling {
    public static void main(String[] args) {

    }

    public static void bagiDonk(int x, int y) {
        // tulis program untuk soal no 1 disini
    }

    public static void bacaIsiArray(int index) {
        String[] students = {"sam","faren","adit","chiko","ghaza","iwan","fadhil","zaky"};
        // tulis program untuk soal no 2 disini
    }
}

```
