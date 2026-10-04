---
title: "CheckExcelRestriction"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Apakah memeriksa pembatasan file Excel ketika pengguna memodifikasi objek terkait sel. Misalnya Excel tidak mengizinkan memasukkan nilai string yang lebih panjang dari 32K. Ketika Anda memasukkan nilai yang lebih panjang dari 32K dan properti ini bernilai true, Anda akan mendapatkan Exception. Jika properti ini bernilai false, kami akan menerima nilai string yang Anda masukkan sebagai nilai sel sehingga nanti Anda dapat menghasilkan nilai string lengkap untuk format file lain seperti CSV. Namun jika Anda telah menetapkan nilai semacam itu yang tidak valid untuk format file Excel, Anda tidak boleh menyimpan workbook sebagai format file Excel nanti. Jika tidak, mungkin terjadi kesalahan tak terduga pada file Excel yang dihasilkan."
type: docs
weight: 40
url: /id/net/groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction/
---
## SpreadsheetLoadOptions.CheckExcelRestriction property

Apakah memeriksa pembatasan file excel ketika pengguna memodifikasi objek terkait sel. Misalnya, excel tidak mengizinkan memasukkan nilai string yang lebih panjang dari 32K. Ketika Anda memasukkan nilai yang lebih panjang dari 32K, jika properti ini bernilai true, Anda akan mendapatkan Exception. Jika properti ini bernilai false, kami akan menerima nilai string yang Anda masukkan sebagai nilai sel sehingga nanti Anda dapat mengeluarkan nilai string lengkap untuk format file lain seperti CSV. Namun, jika Anda telah menetapkan nilai semacam itu yang tidak valid untuk format file excel, Anda tidak boleh menyimpan workbook sebagai format file excel nanti. Jika tidak, mungkin terjadi kesalahan tak terduga pada file excel yang dihasilkan.

```csharp
public bool CheckExcelRestriction { get; set; }
```

### Lihat Juga

* class [SpreadsheetLoadOptions](../../spreadsheetloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
