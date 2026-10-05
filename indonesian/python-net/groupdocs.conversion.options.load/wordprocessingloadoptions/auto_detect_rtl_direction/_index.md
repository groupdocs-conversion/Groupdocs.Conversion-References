---
title: "properti auto_detect_rtl_direction"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Properti autodetectrtldirection menentukan apakah paragraf dan run dengan teks yang sebagian besar kanan-ke-kiri memiliki flag bidi yang diperbaiki sebelum konversi."
type: docs
url: /id/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/auto_detect_rtl_direction/
is_root: false
weight: 2010
---


## auto_detect_rtl_direction property

Properti auto_detect_rtl_direction menentukan apakah paragraf dan run dengan teks yang sebagian besar dari kanan ke kiri memiliki flag bidi yang diperbaiki sebelum konversi.

Ketika disetel ke True (default), properti ini menerapkan heuristik yang digunakan oleh Microsoft Word dan LibreOffice, memperbaiki rendering dokumen Arab/Ibrani yang dihasilkan oleh alat seperti Google Docs yang menghasilkan OOXML tanpa `<w:bidi/>` dan dengan `<w:rtl w:val=\"0\"/>` pada run yang hanya berisi skrip RTL. Atur ke False untuk mempertahankan interpretasi OOXML yang ketat dari markup sumber.

### Definition:
```python
@property
def auto_detect_rtl_direction(self):
    ...
@auto_detect_rtl_direction.setter
def auto_detect_rtl_direction(self, value):
    ...
```

### Lihat Juga
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
