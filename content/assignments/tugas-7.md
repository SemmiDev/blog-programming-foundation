+++
author = "assistant lecture"
title = "Tugas 7 📖 String"
date = "2021-10-24"
description = "Tugas 7 📖 String"
tags = [
    "assignments",
    "java",
]
+++


yee... mingdep kita libur nugas dlu yee`1 November 2021`

<!-- {{< notice info >}}
`Deadine`\
**SI** Rabu, 03 November 2021 Pukul 10:00 wib\
**MI** Jumat, 05 Oktober 2021 Pukul 10:00 wib

`Peraturan`\
Nama file program **NIMExtractor.java**
{{< /notice >}}
 
## ▶ Nomor Induk Mahasiswa (NIM)

`Deskripsi`

Mail yang berkuliah di **Universitas Ebisidi** ingin mengetahui makna dari NIM yang diberikan univ tersebut kepadanya. **Universitas Ebisidi** tersebut memiliki aturan & pemaknaan dari NIM yang diberikan kepada para mahasiswanya.

Berikut beberapa aturan dan pemaknaannya:\
**Aturan**
- NIM berjumlah 10 karakter
- NIM Tidak boleh mengandung spasi

**Makna**

![nim](/assets/nim.png "NIM" )
- Dua karakter pertama, menandakan tahun **A**ngkatan
	- **20** untuk angkatan 2020
	- **21** untuk angkatan 2021
- Dua karakter berikutnya, menandakan kode **F**akultas
	- **01** untuk FK 
	- **02** untuk FT
	- **03** untuk FMIPA
- Dua karakter berikutnya, menandakan **J**alur masuk
	- **11** Jalur SBMPTN
	- **12** Jalur SNMPTN
	- **13** Jalur PBUD
- Empat karakter terakhir, menandakan **N**omor mahasiswa

---

Buatlah program untuk meng ekstrak NIM yang diberikan univ tersebut
 
`Template Program`

	public class NIMExtractor {
		public static void main(String[] args) {

		}
		public static void extract(String nim) {
			// tulis programnya disini
		}
	}

`Lakukan validasi di method extract`
- Jika nim *mengandung* spasi, maka cetak **Tidak Boleh Ada Spasi**, kemudian **hentikan program**
- Jika panjang karakter nim tidak sama dengan 10, maka cetak **NIM tidak valid**, kemudian **hentikan program**\
`note` : untuk menghentikan program, gunakan **System.exit(1)**

`Contoh Masukan`\
	2003113948

`Contoh Keluaran`\
	NIM: 2003113948\
	Angkatan: 2020\
	Fakultas: FMIPA\
	Jalur: SBMPTN\
	No Mahasiswa: 3948

---

`Contoh Masukan`\
	2103123950

`Contoh Keluaran`\
	NIM: 2103123950\
	Angkatan: 2021\
	Fakultas: FMIPA\
	Jalur: SNMPTN\
	No Mahasiswa: 3950

---


`Contoh Masukan`\
	2101123952

`Contoh Keluaran`\
	NIM: 2101123952\
	Angkatan: 2021\
	Fakultas: FK\
	Jalur: SNMPTN\
	No Mahasiswa: 3952

---

`Contoh Masukan`\
21011239522173682173813

`Contoh Keluaran`\
NIM Tidak valid

---


`Contoh Masukan`\
20031139 48

`Contoh Keluaran`\
	Tidak Boleh Ada Spasi

---

`Bahan bacaan/Referensi`
- [javatpoint](https://www.javatpoint.com/java-string)
- [Download](/assets/String.pdf) Handbook -->
