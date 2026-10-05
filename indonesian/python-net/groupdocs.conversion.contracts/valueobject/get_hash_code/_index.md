---
title: "metode get_hash_code"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Berfungsi sebagai fungsi hash default."
type: docs
url: /id/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/
is_root: false
weight: 1040
---


## get_hash_code

Berfungsi sebagai fungsi hash default.

Komponen array, list, dan dictionary di-hash berdasarkan isinya, sesuai dengan cara kesetaraan membandingkannya, sehingga dua objek yang dibandingkan setara juga memiliki hash yang sama dan dapat digunakan sebagai kunci dictionary atau anggota set.

Ini TIDAK berlaku untuk komponen yang merupakan `System.Collections.IEnumerable` lain: komponen semacam itu di-hash berdasarkan referensi, dan yang diekspos sebagai iterator malas menghasilkan nilai yang berbeda pada setiap akses, sehingga objek yang membawanya tidak dapat digunakan sebagai kunci sama sekali. Koleksi bersarang juga dibandingkan dan di-hash berdasarkan referensi bukan secara rekursif.

Konsekuensi lainnya adalah bahwa memodifikasi koleksi yang diungkapkan oleh objek nilai — menambahkan ke daftar halaman, atau menulis ke array nama-tata letak — mengubah hash objek tersebut, sehingga instance yang sudah disimpan dalam kontainer hash menjadi tidak dapat dijangkau. Perlakukan objek nilai sebagai beku setelah digunakan sebagai kunci.

```python
def get_hash_code(self):
    ...
```

**Returns:** A hash code for the current object.

### Lihat Juga
* class [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)
