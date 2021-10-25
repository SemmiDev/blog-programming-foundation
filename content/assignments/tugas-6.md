+++
author = "assistant lecture"
title = "Tugas 6 📖 Class & Object"
date = "2021-10-24"
description = "Tugas 6 📖 Class & Object"
tags = [
    "assignments",
    "java",
]
+++

{{< notice info >}}
`Deadine`\
**SI** Rabu, 27 Oktober 2021 Pukul 10:00 wib\
**MI** Jumat, 29 Oktober 2021 Pukul 10:00 wib

`Peraturan`\
Nama file program **Student.java**
{{< /notice >}}
 
## ▶ Akses Attribute

`Deskripsi`

Diberikan template program dibawah ini, silahkan coba akses attribut dari object **mail**.\
Attribut yang akan di akses adalah **id**, **name**, dan **nim**
Kemudian tampilkan attribut yang di dapat.

`Template Program`
```java
import java.util.*;

public class Main {
	public static void main(String[] args) {
		Student mail = new Student(1, "mail", "2003113999");

		// coba akses attribut id, kemudian tampilkan
		// coba akses attribut name, kemudian tampilkan
		// coba akses attribut nim, kemudian tampilkan
	}
}

class Student {
	private int id;
	private String name;
	private String nim;

	public Student(int id, String name, String nim) {
		this.id = id;
		this.name = name;
		this.nim = nim;
	}

	public int getId() {
		return id;
	}
	public String getName() {
		return name;
	}
	public String getNim() {
		return nim;
	}
	public void setName(String inputName) {
		name = inputName;
	}
	public void setNim(String inputNim) {
		nim = inputNim;
	}
}
```

`Output`\
1\
mail\
2003113999
