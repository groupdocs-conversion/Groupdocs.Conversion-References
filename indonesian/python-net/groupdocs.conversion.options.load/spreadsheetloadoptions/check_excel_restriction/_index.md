---
title: "properti check_excel_restriction"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Properti ini menentukan apakah pembatasan file Excel diperiksa saat memodifikasi objek terkait sel."
type: docs
url: /id/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/
is_root: false
weight: 2030
---


## check_excel_restriction property

Properti ini menentukan apakah pembatasan file Excel diperiksa saat memodifikasi objek terkait sel.

Jika true, mencoba memasukkan string yang lebih panjang dari 32 K akan memunculkan pengecualian. Jika false, string input diterima, memungkinkan nilai penuh dikeluarkan ke format lain seperti CSV. Namun, menyimpan workbook kembali ke format Excel dengan nilai tidak valid tersebut dapat menyebabkan kesalahan yang tidak terduga.

### Definition:
```python
@property
def check_excel_restriction(self):
    ...
@check_excel_restriction.setter
def check_excel_restriction(self, value):
    ...
```

### Lihat Juga
* class [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)
