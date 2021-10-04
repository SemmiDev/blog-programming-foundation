+++
author = "assistant lecture"
title = "Tugas 4 📜 Method"
date = "2021-10-04"
description = "Tugas 4 📜 Method"
tags = [
    "assignments",
    "java",
]
+++

{{< notice warning >}}
`Deadine` 🕙 \
`SI` Jumat, 08 Oktober 2021 Pukul 08:30 wib\
`MI` Jumat, 08 Oktober 2021 Pukul 08:30 wib
{{< /notice >}}

{{< notice info >}}
- Nama **file program** yang akan di submit di **Codepost** harus **Method.java**
- Tidak disediakan **template program**, kalian harus baca dan analisa apa yang diminta/requirement dari soal
- Inputan / **Test Cases** akan ditentukan oleh codepost, oleh karena itu kalian harus handle setiap data yang masuk ke method sesuai dengan requirement soal. agar semua test case nya sukses. 
- Hati-hati dalam penamaan **method**\
**Methoda** tidak sama dengan **methodA**, tidak sama juga dengan **MethodA**, ataupun **METHODA**\
Intinya, nama method bersifat **case sensitive** dan buatlah nama method yang sesuai dengan apa yang di perintahkan soal
{{< /notice >}}

{{< notice info >}}
**Test Case** atau juga bisa disebut dengan **uji kasus** adalah suatu rancangan atau rangkaian mengenai tindakan yang dilakukan oleh user (dalam hal ini adalah abang) untuk melakukan verifikasi terhadap fitur atau fungsi tertentu dari program/method yang udah kalian bikin. Pembuatan test case bertujuan untuk memastikan bahwa sistem/method yang kalian bikin dapat dijalankan dengan baik sesuai dengan **kebutuhan awal/requirement** serta mampu memberikan respon ketika terdapat suatu masukan yang **tidak valid**
{{< /notice >}}

---

> Daftar Isi

[Soal 1 (Sistem Login Sederhana)](https://programming-concept.netlify.app/assignments/tugas-4/#-sistem-login-sederhana)\
[Soal 2 (Bermain dengan Pola Angka)](https://programming-concept.netlify.app/assignments/tugas-4/#-bermain-dengan-pola-angka)\
[Soal 3 (Bilangan Agak Prima)](https://programming-concept.netlify.app/assignments/tugas-4/#-bilangan-agak-prima)

---

## ▶ Sistem Login sederhana
`A. Deskripsi`\
Pak Faren ingin memiliki sebuah **sistem login sederhana**.\
Karena angkatan 2021 dari prodi SI & MI mahasiswanya baik hati & tidak sombong, maka mereka dengan senang hati akan membuatkan sebuah sistem login sederhana untuk Pak Faren.

`B. Ketentuan`\
Program login sederhana ini wajib menggunakan sebuah **method** yang bernama **login**.\
Method tersebut akan menerima dua buah argument alias memiliki dua buah parameter, yaitu **username** & **password** yang keduanya bertipe data **String**.\
Method **login** tersebut akan **mengembalikan nilai** bertipe data **String**.


`C. Logika Program`\
• Jika **username** nya sama/equals dengan `sammi`, jika **true**
maka akan dicek lagi, apakah **password** yang dimasukkan sama/equals dengan `sammi123`, jika **true** maka akan mengembalikan pesan **sammi berhasil login**. Jika tidak, maka akan mengembalikan pesan **password sammi salah**\
• Jika **username** nya sama/equals dengan `faren`, jika **true** 
maka akan dicek lagi, apakah **password** yang dimasukkan sama/equals dengan `faren123`, jika **true** maka akan mengembalikan pesan **faren berhasil login**. Jika tidak, maka akan mengembalikan pesan **password faren salah**\
• Jika **username** nya tidak sama dengan `sammi` ataupun `faren` maka akan mengembalikan pesan **akun tidak ditemukan**

---

## ▶ Bermain dengan pola angka
`A. Deskripsi`\
Pak Sammi meminta Anda untuk **memperhatikan/menganalisa contoh masukan dan keluaran yang diberikan dibawah, menemukan polanya, lalu membuat program yang menghasilkan pola tersebut**.

`B. Ketentuan`\
Program pola angka ini dibuat dalam sebuah method **void** yang bernama **polaAngka** yang menerima sebuah argument bilangan bulat **N**

`Contoh Masukan`\
**N** = 5

`Contoh Keluaran`\
0\
12\
345\
6789\
01234

---

`Contoh Masukan`\
**N** = 7

`Contoh Keluaran`\
0\
12\
345\
6789\
01234\
567890\
1234567

{{< notice info >}}
`Petunjuk`\
Gunakan perulangan bersarang. Simpan nilai yang akan dicetak pada suatu variabel yang selalu ditambahkan satu pada perulangan bersarang.
{{< /notice >}}

---

## ▶ Bilangan Agak Prima
`A. Deskripsi`\
Suatu bilangan bulat positif disebut **agak prima** apabila bilangan tersebut hanya habis dibagi oleh 1, bilangan itu sendiri, dan sebanyak-banyaknya dua bilangan bulat positif lainnya.

Pak Amin memberikan Anda **N** buah bilangan bulat. Untuk setiap bilangan, tentukan apakah bilangan tersebut bilangan **agak prima** atau bukan.

`B. Ketentuan`\
Program **agak prima** ini dibuat dalam sebuah method yang bernama **agakPrima** yang menerima sebuah argument bilangan bulat **N**. Method ini mengembalikan nilai bertipe data **String**.


`Contoh Masukan`\
**N** = 4\
`Contoh Keluaran`\
**YA**

---

`Contoh Masukan`\
**N** = 17\
`Contoh Keluaran`\
**YA**

---

`Contoh Masukan`\
**N** = 51\
`Contoh Keluaran`\
**YA**

---

`Contoh Masukan`\
**N** = 52\
`Contoh Keluaran`\
**BUKAN**

`C. Penjelasan`\
**Faktor-faktor dari 51** adalah **1, 3, 17, dan 51**, sedangkan **faktor dari 52** adalah **1, 2, 4, 13, 26, 52**. Oleh karena itu, **51 agak prima** sedangkan **52** tidak **agak prima**. Sesuai definisi di atas, bilangan prima secara langsung adalah bilangan **agak prima** juga.

---

> Selamat mengerjakan