---
title: "SpreadsheetFileType"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Menentukan dokumen Spreadsheet. Menyertakan jenis file berikut Csv./spreadsheetfiletype/csv Fods./spreadsheetfiletype/fods Ods./spreadsheetfiletype/ods Ots./spreadsheetfiletype/ots Tsv./spreadsheetfiletype/tsv Xlam./spreadsheetfiletype/xlam Xls./spreadsheetfiletype/xls Xlsb./spreadsheetfiletype/xlsb Xlsm./spreadsheetfiletype/xlsm Xlsx./spreadsheetfiletype/xlsx Xlt./spreadsheetfiletype/xlt Xltm./spreadsheetfiletype/xltm Xltx./spreadsheetfiletype/xltx. Pelajari lebih lanjut tentang format Spreadsheet di sini https//wiki.fileformat.com/spreadsheet."
type: docs
weight: 1240
url: /id/net/groupdocs.conversion.filetypes/spreadsheetfiletype/
---
## SpreadsheetFileType class

Menentukan dokumen Spreadsheet. Menyertakan jenis file berikut: [`Csv`](./csv), [`Fods`](./fods), [`Ods`](./ods), [`Ots`](./ots), [`Tsv`](./tsv), [`Xlam`](./xlam), [`Xls`](./xls), [`Xlsb`](./xlsb), [`Xlsm`](./xlsm), [`Xlsx`](./xlsx), [`Xlt`](./xlt), [`Xltm`](./xltm), [`Xltx`](./xltx). Pelajari lebih lanjut tentang format Spreadsheet [di sini](https://wiki.fileformat.com/spreadsheet).

```csharp
public sealed class SpreadsheetFileType : FileType
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SpreadsheetFileType](spreadsheetfiletype)() | Konstruktor Serialisasi |

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
| static readonly [Csv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/csv) | File dengan ekstensi CSV (Comma Separated Values) mewakili file teks biasa yang berisi catatan data dengan nilai yang dipisahkan koma. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/spreadsheet/csv). |
| static readonly [Dif](../../groupdocs.conversion.filetypes/spreadsheetfiletype/dif) | DIF merupakan singkatan dari Data Interchange Format yang digunakan untuk mengimpor/mengekspor data spreadsheet antar aplikasi yang berbeda. Ini termasuk Microsoft Excel, OpenOffice Calc, StarCalc, dan banyak lainnya. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/spreadsheet/dif). |
| static readonly [FlatOpc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/flatopc) | Flat OPC Excel adalah Office Open XML SpreadsheetML yang disimpan dalam file XML datar alih-alih paket ZIP. |
| static readonly [Fods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/fods) | File dengan ekstensi .fods adalah jenis format dokumen OpenDocument Spreadsheet yang menyimpan data dalam baris dan kolom. Format ini ditentukan sebagai bagian dari spesifikasi ODF 1.2 yang dipublikasikan dan dipelihara oleh OASIS. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/spreadsheet/fods). |
| static readonly [Numbers](../../groupdocs.conversion.filetypes/spreadsheetfiletype/numbers) | File dengan ekstensi .numbers diklasifikasikan sebagai tipe file spreadsheet, itulah mengapa mereka mirip dengan file .xlsx; tetapi file Numbers dibuat dengan menggunakan perangkat lunak spreadsheet Apple iWork Numbers. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/spreadsheet/numbers). |
| static readonly [Ods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ods) | File dengan ekstensi ODS merupakan format OpenDocument Spreadsheet Document yang dapat diedit oleh pengguna. Data disimpan di dalam file ODF dalam baris dan kolom. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/spreadsheet/ods). |
| static readonly [Ots](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ots) | File dengan ekstensi .ots adalah file Template OpenDocument Spreadsheet yang dibuat dengan perangkat lunak aplikasi Calc yang termasuk dalam Apache OpenOffice. Perangkat lunak aplikasi Calc serupa dengan Excel yang tersedia di Microsoft Office. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/spreadsheet/ots). |
| static readonly [Sxc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/sxc) | Format file SXC (Sun XML Calc) termasuk dalam suite perkantoran yang disebut OpenOffice.org. Format ini umumnya menangani kebutuhan spreadsheet pengguna karena merupakan format file spreadsheet berbasis XML. Format SXC mendukung rumus, fungsi, makro, dan diagram bersama DataPilot. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/spreadsheet/sxc). |
| static readonly [Tsv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/tsv) | Format file Tab-Separated Values (TSV) mewakili data yang dipisahkan dengan tab dalam format teks biasa. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/spreadsheet/tsv). |
| static readonly [Xlam](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlam) | XLAM adalah file Macro-Enabled Add-In yang digunakan untuk menambahkan fungsi baru ke spreadsheet. Add-In adalah program tambahan yang menjalankan kode tambahan dan menyediakan fungsionalitas tambahan untuk spreadsheet. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/spreadsheet/xlam/). |
| static readonly [Xls](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xls) | XLS mewakili Excel Binary File Format. File semacam itu dapat dibuat oleh Microsoft Excel serta program spreadsheet serupa lainnya seperti OpenOffice Calc atau Apple Numbers. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/spreadsheet/xls). |
| static readonly [Xlsb](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsb) | Format file XLSB menentukan Excel Binary File Format, yang merupakan kumpulan catatan dan struktur yang menentukan konten buku kerja Excel. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/spreadsheet/xlsb). |
| static readonly [Xlsm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsm) | XLSM adalah jenis file Spreadsheet yang mendukung makro. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/spreadsheet/xlsm). |
| static readonly [Xlsx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsx) | XLSX adalah format terkenal untuk dokumen Microsoft Excel yang diperkenalkan oleh Microsoft dengan rilis Microsoft Office 2007. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/spreadsheet/xlsx). |
| static readonly [Xlt](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlt) | File dengan ekstensi .XLT adalah file templat yang dibuat dengan Microsoft Excel, yaitu aplikasi spreadsheet yang merupakan bagian dari paket Microsoft Office. Microsoft Office 97-2003 mendukung pembuatan file XLT baru serta membuka file tersebut. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/spreadsheet/xlt). |
| static readonly [Xltm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltm) | Ekstensi file XLTM mewakili file yang dihasilkan oleh Microsoft Excel sebagai file templat yang mendukung makro. File XLTM mirip dengan XLTX dalam struktur kecuali yang terakhir tidak mendukung pembuatan file templat dengan makro. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/spreadsheet/xltm). |
| static readonly [Xltx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltx) | File XLTX mewakili Microsoft Excel Template yang berbasis pada spesifikasi format file Office OpenXML. File ini digunakan untuk membuat file templat standar yang dapat digunakan untuk menghasilkan file XLSX yang memiliki pengaturan yang sama seperti yang ditentukan dalam file XLTX. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/spreadsheet/xltx). |

### Lihat Juga

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
