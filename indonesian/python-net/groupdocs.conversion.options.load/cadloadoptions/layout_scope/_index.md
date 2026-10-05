---
title: "properti layout_scope"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Ruang lingkup tata letak yang menentukan ruang gambar mana yang dikonversi."
type: docs
url: /id/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/
is_root: false
weight: 2070
---


## layout_scope property

Ruang lingkup tata letak yang menentukan ruang gambar mana yang dikonversi. Defaultnya adalah [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/), yang tidak membatasi konversi. Diabaikan ketika [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) disediakan, karena nama tata letak eksplisit selalu menang. Nilai `None` diperlakukan sebagai [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/).

Jika ruang lingkup tidak memilih salah satu lembar yang ditawarkan oleh gambar, konversi gagal dengan `InvalidLoadOptionsException`, yang menyebutkan ruang lingkup dan lembar yang tersedia alih-alih merender ruang yang dikecualikan. Gambar yang tidak menawarkan lembar sama sekali tidak terpengaruh dan tetap dikonversi sebagai satu unit. Tidak dihormati saat mengonversi ke PDF/UA-1, karena alasan yang diberikan pada [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/).

### Definition:
```python
@property
def layout_scope(self):
    ...
@layout_scope.setter
def layout_scope(self, value):
    ...
```

### Lihat Juga
* class [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/)
