---
title: "PdfLoadOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Opsi untuk memuat dokumen Pdf."
type: docs
weight: 2740
url: /id/net/groupdocs.conversion.options.load/pdfloadoptions/
---
## PdfLoadOptions class

Opsi untuk memuat dokumen Pdf.

```csharp
public sealed class PdfLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IFontTransformationLoadOptions, IMetadataLoadOptions, 
    IPageNumberingLoadOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfLoadOptions](pdfloadoptions)() | Menginisialisasi instance baru dari kelas [`PdfLoadOptions`](../pdfloadoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/pdfloadoptions/clearbuiltindocumentproperties) { get; set; } | Menghapus properti metadata bawaan dari dokumen. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/pdfloadoptions/clearcustomdocumentproperties) { get; set; } | Menghapus properti metadata kustom dari dokumen. |
| [ConvertOwned](../../groupdocs.conversion.options.load/pdfloadoptions/convertowned) { get; set; } | Menerapkan [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) Default adalah false |
| [ConvertOwner](../../groupdocs.conversion.options.load/pdfloadoptions/convertowner) { get; set; } | Menerapkan [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) Default adalah true |
| [DefaultFont](../../groupdocs.conversion.options.load/pdfloadoptions/defaultfont) { get; set; } | Font default untuk dokumen Pdf. Font berikut akan digunakan jika sebuah font tidak ada. |
| [Depth](../../groupdocs.conversion.options.load/pdfloadoptions/depth) { get; set; } | Menerapkan [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Default: 1 |
| [FlattenAllFields](../../groupdocs.conversion.options.load/pdfloadoptions/flattenallfields) { get; set; } | Ratakan semua bidang pada formulir PDF. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/pdfloadoptions/fontsubstitutes) { get; set; } | Ganti font tertentu saat mengonversi dokumen Pdf. |
| [FontTransformations](../../groupdocs.conversion.options.load/pdfloadoptions/fonttransformations) { get; set; } | Mengubah font yang ada setelah pemuatan dokumen dan substitusi font selesai. Transformasi font dapat memodifikasi semua font dalam dokumen, termasuk font yang berhasil dimuat. |
| [Format](../../groupdocs.conversion.options.load/pdfloadoptions/format) { get; } | Tipe berkas dokumen input. Nilainya `null` sampai format ditetapkan, jadi periksa apakah `null` daripada membandingkannya dengan [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), yang tidak pernah sama. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipe berkas dokumen input. |
| [HidePdfAnnotations](../../groupdocs.conversion.options.load/pdfloadoptions/hidepdfannotations) { get; set; } | Sembunyikan anotasi dalam dokumen Pdf. |
| [PageNumbering](../../groupdocs.conversion.options.load/pdfloadoptions/pagenumbering) { get; set; } | Aktifkan atau nonaktifkan pembuatan penomoran halaman dalam dokumen yang dikonversi. Default: false |
| [Password](../../groupdocs.conversion.options.load/pdfloadoptions/password) { get; set; } | Atur kata sandi untuk membuka proteksi dokumen yang dilindungi. |
| [RemoveEmbeddedFiles](../../groupdocs.conversion.options.load/pdfloadoptions/removeembeddedfiles) { get; set; } | Hapus file tersemat. |
| [RemoveJavascript](../../groupdocs.conversion.options.load/pdfloadoptions/removejavascript) { get; set; } | Hapus javascript. |
| [ResetFontFolders](../../groupdocs.conversion.options.load/pdfloadoptions/resetfontfolders) { get; set; } | Atur ulang folder font sebelum memuat dokumen |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat Juga

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IFontTransformationLoadOptions](../ifonttransformationloadoptions)
* interface [IMetadataLoadOptions](../imetadataloadoptions)
* interface [IPageNumberingLoadOptions](../ipagenumberingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
