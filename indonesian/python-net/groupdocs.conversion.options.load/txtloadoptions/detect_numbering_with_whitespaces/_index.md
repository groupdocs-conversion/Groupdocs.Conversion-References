---
title: "properti detect_numbering_with_whitespaces"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Properti ini menentukan bagaimana item daftar bernomor dikenali saat dokumen teks biasa dikonversi."
type: docs
url: /id/python-net/groupdocs.conversion.options.load/txtloadoptions/detect_numbering_with_whitespaces/
is_root: false
weight: 2020
---


## detect_numbering_with_whitespaces property

Properti ini menentukan bagaimana item daftar bernomor dikenali saat dokumen teks biasa dikonversi. Nilai default adalah True.

Jika opsi ini diatur ke False, algoritma pengenalan daftar mendeteksi paragraf daftar ketika nomor daftar diakhiri dengan titik, kurung kanan, atau simbol bullet (seperti "•", "*", "-" atau "o").

Jika opsi ini diatur ke True, spasi juga digunakan sebagai pemisah nomor daftar: algoritma pengenalan daftar untuk penomoran gaya Arab (mis., 1., 1.1.2.) menggunakan spasi dan simbol titik (".") sekaligus.

### Definition:
```python
@property
def detect_numbering_with_whitespaces(self):
    ...
@detect_numbering_with_whitespaces.setter
def detect_numbering_with_whitespaces(self, value):
    ...
```

### Lihat Juga
* class [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/)
