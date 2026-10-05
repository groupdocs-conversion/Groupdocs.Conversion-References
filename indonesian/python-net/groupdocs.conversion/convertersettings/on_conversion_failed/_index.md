---
title: "properti on_conversion_failed"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Penangan peristiwa yang dipanggil ketika konversi gagal."
type: docs
url: /id/python-net/groupdocs.conversion/convertersettings/on_conversion_failed/
is_root: false
weight: 2070
---


## on_conversion_failed property

Penangan peristiwa yang dipanggil ketika konversi gagal.

Dihormati untuk kompatibilitas mundur: nilai digabungkan ke dalam kantong peristiwa internal saat konstruksi [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) (memetakan ke [`ConversionEvents.on_document_failed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_failed/)) dan ditimpa jika penangan yang sama juga disetel pada parameter konstruktor `events`.

### Definition:
```python
@property
def on_conversion_failed(self):
    ...
@on_conversion_failed.setter
def on_conversion_failed(self, value):
    ...
```

### Lihat Juga
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
