---
title: "MarkdownOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Opsi untuk konversi ke tipe file markdown."
type: docs
weight: 2010
url: /id/net/groupdocs.conversion.options.convert/markdownoptions/
---
## MarkdownOptions class

Opsi untuk konversi ke tipe file markdown.

```csharp
public sealed class MarkdownOptions : ValueObject
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [MarkdownOptions](markdownoptions)() | Menginisialisasi instance baru dari kelas [`MarkdownOptions`](../markdownoptions) class. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ExportImagesAsBase64](../../groupdocs.conversion.options.convert/markdownoptions/exportimagesasbase64) { get; set; } | Ekspor gambar sebagai base64. Defaultnya true. Diabaikan ketika [`ImageSavingCallback`](./imagesavingcallback) diatur. |
| [ImageSavingCallback](../../groupdocs.conversion.options.convert/markdownoptions/imagesavingcallback) { get; set; } | Callback dipanggil sekali per gambar saat menyimpan Markdown. Memungkinkan pemanggil menyimpan gambar secara eksternal dan mengganti URI yang disematkan dalam dokumen. Memiliki prioritas lebih tinggi daripada [`ExportImagesAsBase64`](./exportimagesasbase64) bila tidak null. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat Juga

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
