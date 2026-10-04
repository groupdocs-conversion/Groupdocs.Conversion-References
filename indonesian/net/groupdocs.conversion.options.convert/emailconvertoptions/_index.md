---
title: "EmailConvertOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Opsi untuk konversi ke tipe file Email."
type: docs
weight: 1800
url: /id/net/groupdocs.conversion.options.convert/emailconvertoptions/
---
## EmailConvertOptions class

Opsi untuk konversi ke tipe file Email.

```csharp
public class EmailConvertOptions : ConvertOptions<EmailFileType>
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [EmailConvertOptions](emailconvertoptions)() | Menginisialisasi instance baru dari kelas [`EmailConvertOptions`](../emailconvertoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AttachmentContentHandler](../../groupdocs.conversion.options.convert/emailconvertoptions/attachmentcontenthandler) { get; set; } | Delegasi untuk menangani pemrosesan khusus lampiran email. Delegasi menerima nama lampiran, tipe konten, dan aliran lampiran asli sebagai parameter serta mengembalikan aliran lampiran yang telah dimodifikasi. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Tipe file yang diinginkan untuk mengonversi dokumen input. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Mengimplementasikan [`Format`](../iconvertoptions/format) |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Menggandakan instance opsi saat ini. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat Juga

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* class [EmailFileType](../../groupdocs.conversion.filetypes/emailfiletype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
