---
title: "properti attachment_content_handler"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Delegasi yang digunakan untuk menangani pemrosesan khusus lampiran email."
type: docs
url: /id/python-net/groupdocs.conversion.options.convert/emailconvertoptions/attachment_content_handler/
is_root: false
weight: 2010
---


## attachment_content_handler property

Delegasi yang digunakan untuk menangani pemrosesan khusus lampiran email.

Delegasi menerima nama lampiran (`str`), tipe konten (`str`), dan aliran lampiran asli (`io.RawIOBase`), dan harus mengembalikan aliran lampiran yang dimodifikasi (`io.RawIOBase`).

### Definition:
```python
@property
def attachment_content_handler(self):
    ...
@attachment_content_handler.setter
def attachment_content_handler(self, value):
    ...
```

### Lihat Juga
* class [`EmailConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/emailconvertoptions/)
