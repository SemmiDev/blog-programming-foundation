+++
author = "assistant lecture"
title = "Tugas 3 📝 Perulangan"
date = "2021-09-28"
description = "Tugas 3 📝 Perulangan"
tags = [
    "assignments",
    "java",
]
+++

{{< notice warning >}}
**Deadine** ⏳ \
**SI = Kamis, 07 Oktober 2021 Pukul 23:00 wib** \
**MI = Kamis, 07 Oktober 2021 Pukul 23:00 wib**
{{< /notice >}}

# Daftar isi
**Klik** untuk bernavigasi

- [`Penilaian`](https://programming-concept.netlify.app/posts/tugas-3/#penilaian)
- [`Petunjuk pengerjaan soal`](https://programming-concept.netlify.app/posts/tugas-3/#petunjuk)
- [`Peraturan`](https://programming-concept.netlify.app/posts/tugas-3/#peraturan)
- [`Template program`](https://programming-concept.netlify.app/posts/tugas-3/#template-program)
- [`Soal`](https://programming-concept.netlify.app/posts/tugas-3/#soal)
    - [`Soal no 1 (contoh & tips)`](https://programming-concept.netlify.app/posts/tugas-3/#soal-no-1)
    - [`Output soal no 1`](https://programming-concept.netlify.app/posts/tugas-3/#output-soal-no-1)
    - [`Soal no 2 (contoh & tips)`](https://programming-concept.netlify.app/posts/tugas-3/#soal-no-2)
    - [`Output soal no 2`](https://programming-concept.netlify.app/posts/tugas-3/#output-soal-no-2)

---

# Penilaian
**Tugas 3** ini terdiri dari **2 soal**\
Masing-masing soal memiliki **sebuah test** di Codepost\
Jika kedua test **passed** maka **total point** = **1** \
Jika salah satu test **passed** maka **total point** = **0.5** + baca `note`\
Jika tidak ada test yang **passed** maka **total point** = **0** + baca `note`\
Tidak mengumpulkan tugas **total point** = **0**

`note` *walaupun test-nya **failed** (tapi jawaban hampir benar), tetap akan **diberi poin** yeee* 🎉🎉

---
# Petunjuk
{{< notice info >}}
Sebelum **GAS** ngerjain tugas ini, `wajib` **[TONTON VIDIO INI](https://www.youtube.com/watch?v=duP3DwdSAC4)** terlebih dahulu ya (**2m 53s**) 😊 vidio-nya berisi guide/panduan untuk ngerjain tugas 3 ini
{{< /notice >}}

---
# Peraturan
Nama **file program java** yang akan di submit di **Codepost** harus `Perulangan.java`

---
# Template Program
Silahkan **copas** template program dibawah ini kedalam file `Perulangan.java` yg udah kalian bikin

```java
public class Perulangan {
    public static void main(String[] args) {
        soalNo();
    }

    public static void soalNo1() {

    }

    public static void soalNo2() {
        
    }
}
```

---
# Soal
### Soal no 1
Hitunglah **hasil penjumlahan bilangan asli kelipatan `3 atau 5`** yang dimulai dari angka **10 sampai dengan 700**, kemudian tampilkan **hasil penjumlahannya**

{{< notice example >}}
`Contoh soal`

Hasil penjumlahan **bilangan asli kelipatan `3 atau 5` kurang dari 10** adalah?

**Jawab**

Bilangan asli **kelipatan 3 atau 5** kurang dari 10 = `3` `5` `6` `9`\
Kemudian jumlahkan = `3` + `5` + `6` + `9`\
Hasil = `23`
{{< /notice >}}

{{< notice tip >}}

- Gunakan **for** (looping)
- Gunakan **if** (conditional)
- Gunakan variable **total** untuk menampung hasil penjumlahan 
- Gunakan operasi **|| (or)** atau boleh juga tidak menggunakannya
- Gunakan keyword **continue** jika dirasa perlu

`gak tau operasi OR itu apa?` **[Googling](https://www.google.com)**
{{< /notice >}}

### Output Soal no 1
Di bawah ini, **hasil/output** program untuk soal no 1

`total = 114895`

---
### Soal no 2
Buatlah sebuah **matriks identitas** ber ordo `11 x 11` (11 baris 11 kolom). Kemudian, tepat di **pertengahan** matriks identitas tersebut, cetak tanda **#** (kress)

{{< notice info >}}
**Matriks Identitas** adalah matriks persegi yang elemen-elemen pada diagonal utamanya bernilai **1** dan elemen-elemen diluar diagonal utama bernilai **0**
{{< /notice >}}

{{< notice example >}}
**Matriks identitas ber ordo `5 x 5`** (5 baris 5 kolom). Kemudian, tepat di **pertengahan** matriks identitas tersebut, cetak tanda **#** (kress)

>**1** 0 0 0 0\
0 **1** 0 0 0\
0 0 **#** 0 0\
0 0 0 **1** 0\
0 0 0 0 **1**

**Matriks identitas ber ordo `7 x 7`** (7 baris 7 kolom). Kemudian, tepat di **pertengahan** matriks identitas tersebut, cetak tanda **#** (kress)

>**1** 0 0 0 0 0 0\
0 **1** 0 0 0 0 0\
0 0 **1** 0 0 0 0\
0 0 0 **#** 0 0 0\
0 0 0 0 **1** 0 0\
0 0 0 0 0 **1** 0\
0 0 0 0 0 0 **1**

{{< /notice >}}

{{< notice tip >}}
- Gunakan **nested loop** / **loop bersarang**
- Contoh penggunaan **nested loop / loop bersarang** ada di **slide ppt**
- Gunakan **if**
- Contoh penggunaan **if** ada di **slide ppt** pertemuan minggu lalu
- Gunakan keyword **continue** jika dirasa perlu

`belum paham cara pake loop bersarang?` **[Googling](https://www.google.com)**
{{< /notice >}}

### Output Soal no 2

>**1** 0 0 0 0 0 0 0 0 0 0\
0 **1** 0 0 0 0 0 0 0 0 0\
0 0 **1** 0 0 0 0 0 0 0 0\
0 0 0 **1** 0 0 0 0 0 0 0\
0 0 0 0 **1** 0 0 0 0 0 0\
0 0 0 0 0 **#** 0 0 0 0 0\
0 0 0 0 0 0 **1** 0 0 0 0\
0 0 0 0 0 0 0 **1** 0 0 0\
0 0 0 0 0 0 0 0 **1** 0 0\
0 0 0 0 0 0 0 0 0 **1** 0\
0 0 0 0 0 0 0 0 0 0 **1**

---
>Selamat Mengerjakan