---
title: "DetectNumberingWithWhitespaces"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Memungkinkan untuk menentukan bagaimana item daftar bernomor dikenali saat dokumen teks biasa dikonversi. Nilai default adalah true."
type: docs
weight: 30
url: /id/net/groupdocs.conversion.options.load/txtloadoptions/detectnumberingwithwhitespaces/
---
## TxtLoadOptions.DetectNumberingWithWhitespaces property

Memungkinkan untuk menentukan bagaimana item daftar bernomor dikenali saat dokumen teks biasa dikonversi. Nilai default adalah true.

```csharp
public bool DetectNumberingWithWhitespaces { get; set; }
```

### Catatan

Jika opsi ini diatur ke false, algoritma pengenalan daftar mendeteksi paragraf daftar, ketika nomor daftar diakhiri dengan titik, kurung kanan, atau simbol bullet (seperti "•", "*", "-" atau "o").

Jika opsi ini diatur ke true, spasi juga digunakan sebagai pemisah nomor daftar: algoritma pengenalan daftar untuk penomoran gaya Arab (1., 1.1.2.) menggunakan spasi dan simbol titik (".") sekaligus.

### Lihat Juga

* class [TxtLoadOptions](../../txtloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
