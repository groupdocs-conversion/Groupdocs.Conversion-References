---
title: "XmlLoadOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Opsi untuk memuat dokumen XML."
type: docs
weight: 2960
url: /id/net/groupdocs.conversion.options.load/xmlloadoptions/
---
## XmlLoadOptions class

Opsi untuk memuat dokumen XML.

```csharp
public sealed class XmlLoadOptions : WebLoadOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [XmlLoadOptions](xmlloadoptions)() | Menginisialisasi instance baru dari kelas [`XmlLoadOptions`](../xmlloadoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BasePath](../../groupdocs.conversion.options.load/webloadoptions/basepath) { get; set; } | Jalur/url dasar untuk html |
| [ConfigureHeaders](../../groupdocs.conversion.options.load/webloadoptions/configureheaders) { get; set; } | Aksi untuk konfigurasi header permintaan. Parameter pertama dari aksi adalah Uri. |
| [CredentialsProvider](../../groupdocs.conversion.options.load/webloadoptions/credentialsprovider) { get; set; } | Penyedia kredensial untuk Uri. |
| [CustomCssStyle](../../groupdocs.conversion.options.load/webloadoptions/customcssstyle) { get; set; } | Mengimplementasikan [`CustomCssStyle`](../icustomcssstyleoptions/customcssstyle) |
| [Encoding](../../groupdocs.conversion.options.load/webloadoptions/encoding) { get; set; } | Mendapatkan atau mengatur pengkodean yang akan digunakan saat memuat dokumen web. Jika properti bernilai null, pengkodean akan ditentukan dari atribut set karakter dokumen. |
| [Format](../../groupdocs.conversion.options.load/xmlloadoptions/format) { get; } | Tipe berkas dokumen input. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipe berkas dokumen input. |
| [HtmlRenderingMode](../../groupdocs.conversion.options.load/webloadoptions/htmlrenderingmode) { get; set; } | Mengontrol cara konten HTML dirender. Default: AbsolutePositioning |
| [MarginSettings](../../groupdocs.conversion.options.load/webloadoptions/marginsettings) { get; set; } | Pengaturan margin halaman |
| [OrientationSettings](../../groupdocs.conversion.options.load/webloadoptions/orientationsettings) { get; set; } | Pengaturan orientasi halaman |
| [PageLayoutOptions](../../groupdocs.conversion.options.load/webloadoptions/pagelayoutoptions) { get; set; } | Menentukan opsi tata letak halaman saat memuat dokumen web. |
| [PageNumbering](../../groupdocs.conversion.options.load/webloadoptions/pagenumbering) { get; set; } | Aktifkan atau nonaktifkan pembuatan penomoran halaman dalam dokumen yang dikonversi. Default: false |
| [ResourceLoadingTimeout](../../groupdocs.conversion.options.load/webloadoptions/resourceloadingtimeout) { get; set; } | Batas waktu untuk memuat sumber daya eksternal |
| [SizeSettings](../../groupdocs.conversion.options.load/webloadoptions/sizesettings) { get; set; } | Pengaturan ukuran halaman |
| [SkipExternalResources](../../groupdocs.conversion.options.load/webloadoptions/skipexternalresources) { get; set; } | Menerapkan [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [UseAsDataSource](../../groupdocs.conversion.options.load/xmlloadoptions/useasdatasource) { get; set; } | Gunakan dokumen Xml sebagai sumber data |
| [UsePdf](../../groupdocs.conversion.options.load/webloadoptions/usepdf) { get; set; } | Gunakan pdf untuk konversi. Default: false |
| [WhitelistedResources](../../groupdocs.conversion.options.load/webloadoptions/whitelistedresources) { get; set; } | Menerapkan [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |
| [XslFoFactory](../../groupdocs.conversion.options.load/xmlloadoptions/xslfofactory) { get; set; } | Aliran dokumen XSL-FO untuk mengonversi XML menggunakan file markup XSL-FO. |
| [XsltFactory](../../groupdocs.conversion.options.load/xmlloadoptions/xsltfactory) { get; set; } | Aliran dokumen XSLT untuk mengonversi XML dengan melakukan transformasi XSL ke HTML. |
| [Zoom](../../groupdocs.conversion.options.load/webloadoptions/zoom) { get; set; } | Menentukan tingkat zoom sebagai persentase. Tingkat zoom diterapkan pada tag &lt;body&gt; dokumen sebelum konversi, mengubah skala tampilan visual dokumen. Nilai 100% mewakili ukuran asli. Nilai default adalah 100. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat Juga

* class [WebLoadOptions](../webloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
