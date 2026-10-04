---
title: "FinanceFileType"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Mendefinisikan dokumen Keuangan. Menyertakan jenis-jenis berikut Xbrl./financefiletype/xbrlIXbrl./financefiletype/ixbrlOfx./financefiletype/ofx. Pelajari lebih lanjut tentang format Keuangan di sinihttps//docs.fileformat.com/finance/."
type: docs
weight: 1140
url: /id/net/groupdocs.conversion.filetypes/financefiletype/
---
## FinanceFileType class

Mendefinisikan dokumen Keuangan. Menyertakan jenis-jenis berikut: [`Xbrl`](./xbrl)[`IXbrl`](./ixbrl)[`Ofx`](./ofx) Pelajari lebih lanjut tentang format Keuangan [di sini](https://docs.fileformat.com/finance/).

```csharp
public sealed class FinanceFileType : FileType
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [FinanceFileType](financefiletype)() | Konstruktor Serialisasi |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Deskripsi tipe file |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Ekstensi file |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Keluarga file |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Format file |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Membandingkan objek saat ini dengan objek lain. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Mengimplementasikan [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Berfungsi sebagai fungsi hash default. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Representasi string |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| static readonly [IXbrl](../../groupdocs.conversion.filetypes/financefiletype/ixbrl) | Di dalam iXBRL, konten XBRL dibungkus dalam format file xHTML yang menggunakan tag XML. Seperti XBRL, merupakan elemen akar dari file iXBRL. Format XHTML merepresentasikan isinya sebagai kumpulan berbagai jenis dokumen dan modul. Semua file dalam XHTML didasarkan pada format file XML dan mematuhi standar dokumen XML. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/finance/ixbrl/). |
| static readonly [Ofx](../../groupdocs.conversion.filetypes/financefiletype/ofx) | Open Financial Exchange (OFX) adalah format aliran data untuk pertukaran informasi keuangan yang berkembang dari Open Financial Connectivity (OFC) milik Microsoft dan format file Open Exchange milik Intuit. Pelajari lebih lanjut tentang format file ini [di sini](https://en.wikipedia.org/wiki/Open_Financial_Exchange). |
| static readonly [Xbrl](../../groupdocs.conversion.filetypes/financefiletype/xbrl) | XBRL adalah standar internasional terbuka untuk pelaporan bisnis digital yang banyak digunakan secara global. Ini adalah bahasa berbasis XML yang menggunakan elemen XBRL, yang dikenal sebagai tag, untuk menggambarkan setiap item data bisnis guna menyusun data untuk penyortiran dan analisis laporan. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/finance/xbrl/). |

### Lihat Juga

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
