---
title: "layout_names properti"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Nama tata letak yang akan dikonversi."
type: docs
url: /id/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/
is_root: false
weight: 2060
---


## layout_names property

Nama tata letak yang akan dikonversi.

Tidak dihormati saat mengonversi ke PDF/UA-1. Target tersebut merender gambar sebagai satu halaman bertag, yang tidak dapat memuat satu lembar per tata letak yang dipilih, sehingga seluruh gambar dikonversi sebagai gantinya dan tidak ada yang berlaku di sini.

Setiap target lain, termasuk PDF, menghormati pilihan. Pada target tersebut, nama dicocokkan secara tepat dengan tata letak yang dibawa gambar, sehingga nama yang hanya berbeda huruf besar/kecil dianggap nama yang berbeda. Nama yang tidak cocok dengan apa pun akan diabaikan dan hanya membebani pemanggil satu lembar; daftar yang tidak ada yang cocok menyebabkan konversi gagal dengan `InvalidLoadOptionsException` yang menyebutkan nama‑nama yang tidak ditemukan dan tata letak yang memang dimiliki gambar, alih‑alih merender lembar yang tidak diminta pemanggil. Gambar yang tidak memiliki tata letak sama sekali dikecualikan: tidak ada yang dapat dicocokkan, sehingga tidak ada yang ditolak.

### Definition:
```python
@property
def layout_names(self):
    ...
@layout_names.setter
def layout_names(self, value):
    ...
```

### Lihat Juga
* class [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/)
