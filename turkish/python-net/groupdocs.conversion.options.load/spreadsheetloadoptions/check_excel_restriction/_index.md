---
title: "check_excel_restriction özelliği"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Bu özellik, hücreyle ilgili nesneler değiştirilirken Excel dosyası kısıtlamalarının kontrol edilip edilmediğini belirler."
type: docs
url: /tr/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/
is_root: false
weight: 2030
---


## check_excel_restriction property

Bu özellik, hücreyle ilgili nesneler değiştirilirken Excel dosyası kısıtlamalarının kontrol edilip edilmediğini belirler.

Doğru ise, 32 K'dan uzun bir dize girmeye çalışmak bir istisna oluşturur. Yanlış ise, giriş dizesi kabul edilir ve tam değer CSV gibi diğer formatlara çıktılanabilir. Ancak, çalışma kitabını bu geçersiz değerlerle Excel formatına kaydetmek beklenmedik hatalara yol açabilir.

### Definition:
```python
@property
def check_excel_restriction(self):
    ...
@check_excel_restriction.setter
def check_excel_restriction(self, value):
    ...
```

### Ayrıca Bakınız
* class [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)
