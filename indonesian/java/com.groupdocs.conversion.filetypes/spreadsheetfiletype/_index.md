---
title: "SpreadsheetFileType"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Mendefinisikan dokumen Spreadsheet."
type: docs
weight: 25
url: /id/java/com.groupdocs.conversion.filetypes/spreadsheetfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class SpreadsheetFileType extends FileType implements Serializable
```

Mendefinisikan dokumen Spreadsheet. Menyertakan tipe file berikut:
[Csv](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Csv),
[Fods](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Fods),
[Ods](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Ods),
[Ots](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Ots),
[Tsv](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Tsv),
[Xlam](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlam),
[Xls](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xls),
[Xlsb](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlsb),
[Xlsm](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlsm),
[Xlsx](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlsx),
[Xlt](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlt),
[Xltm](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xltm),
[Xltx](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xltx).
Pelajari lebih lanjut tentang format Spreadsheet [di sini](../https://wiki.fileformat.com/spreadsheet).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [SpreadsheetFileType()](#SpreadsheetFileType--) | Konstruktor serialisasi |
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Xls](#Xls) | XLS mewakili Format File Biner Excel. |
|
|  | [Xlsx](#Xlsx) | XLSX adalah format yang terkenal untuk dokumen Microsoft Excel yang diperkenalkan oleh Microsoft dengan rilis Microsoft Office 2007. |
|
|  | [Xlsm](#Xlsm) | XLSM adalah jenis file Spreadsheet yang mendukung makro. |
|
|  | [Xlsb](#Xlsb) | Format file XLSB menentukan Format File Biner Excel, yang merupakan kumpulan catatan dan struktur yang menentukan konten buku kerja Excel. |
|
|  | [Ods](#Ods) | File dengan ekstensi ODS merupakan format Dokumen Spreadsheet OpenDocument yang dapat diedit oleh pengguna. |
|
|  | [Ots](#Ots) | File dengan ekstensi .ots adalah file Template Spreadsheet OpenDocument yang dibuat dengan perangkat lunak aplikasi Calc yang termasuk dalam Apache OpenOffice. |
|
|  | [Xltx](#Xltx) | File XLTX mewakili Template Microsoft Excel yang berbasis pada spesifikasi format file Office OpenXML. |
|
|  | [Xlt](#Xlt) | File dengan ekstensi .XLT adalah file template yang dibuat dengan Microsoft Excel, yang merupakan aplikasi spreadsheet yang termasuk dalam paket Microsoft Office. |
|
|  | [Xltm](#Xltm) | Ekstensi file XLTM mewakili file yang dihasilkan oleh Microsoft Excel sebagai file template yang mendukung makro. |
|
|  | [Tsv](#Tsv) | Format file Tab-Separated Values (TSV) mewakili data yang dipisahkan dengan tab dalam format teks biasa. |
|
|  | [Xlam](#Xlam) | XLAM adalah file Add-In yang mendukung Makro yang digunakan untuk menambahkan fungsi baru ke spreadsheet. |
|
|  | [Csv](#Csv) | File dengan ekstensi CSV (Comma Separated Values) mewakili file teks biasa yang berisi catatan data dengan nilai yang dipisahkan koma. |
|
|  | [Fods](#Fods) | File dengan ekstensi .fods adalah jenis format dokumen Spreadsheet OpenDocument yang menyimpan data dalam baris dan kolom. |
|
|  | [Dif](#Dif) | DIF merupakan singkatan dari Data Interchange Format yang digunakan untuk mengimpor/mengekspor data spreadsheet antara berbagai aplikasi. |
|
|  | [Sxc](#Sxc) | Format file SXC (Sun XML Calc) termasuk dalam suite perkantoran yang disebut OpenOffice.org. |
|
|  | [Numbers](#Numbers) | File dengan ekstensi .numbers diklasifikasikan sebagai tipe file spreadsheet, itulah mengapa mereka mirip dengan file .xlsx; tetapi file Numbers dibuat dengan menggunakan perangkat lunak spreadsheet Apple iWork Numbers. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### SpreadsheetFileType() {#SpreadsheetFileType--}
```
public SpreadsheetFileType()
```


Konstruktor serialisasi


### Xls {#Xls}
```
public static final SpreadsheetFileType Xls
```


XLS mewakili Excel Binary File Format. File semacam itu dapat dibuat oleh Microsoft Excel serta program spreadsheet serupa lainnya seperti OpenOffice Calc atau Apple Numbers.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/spreadsheet/xls).


### Xlsx {#Xlsx}
```
public static final SpreadsheetFileType Xlsx
```


XLSX adalah format yang terkenal untuk dokumen Microsoft Excel yang diperkenalkan oleh Microsoft dengan rilis Microsoft Office 2007.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/spreadsheet/xlsx).


### Xlsm {#Xlsm}
```
public static final SpreadsheetFileType Xlsm
```


XLSM adalah jenis file Spreadsheet yang mendukung makro.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/spreadsheet/xlsm).


### Xlsb {#Xlsb}
```
public static final SpreadsheetFileType Xlsb
```


Format file XLSB menentukan Format File Biner Excel, yang merupakan kumpulan catatan dan struktur yang menentukan konten buku kerja Excel.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/spreadsheet/xlsb).


### Ods {#Ods}
```
public static final SpreadsheetFileType Ods
```


File dengan ekstensi ODS merupakan format OpenDocument Spreadsheet Document yang dapat diedit oleh pengguna. Data disimpan dalam file ODF dalam baris dan kolom.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/spreadsheet/ods).


### Ots {#Ots}
```
public static final SpreadsheetFileType Ots
```


File dengan ekstensi .ots adalah file OpenDocument Spreadsheet Template yang dibuat dengan perangkat lunak aplikasi Calc yang termasuk dalam Apache OpenOffice. Perangkat lunak aplikasi Calc serupa dengan Excel yang tersedia di Microsoft Office.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/spreadsheet/ots).


### Xltx {#Xltx}
```
public static final SpreadsheetFileType Xltx
```


File XLTX mewakili Microsoft Excel Template yang berbasis pada spesifikasi format file Office OpenXML. File ini digunakan untuk membuat file template standar yang dapat digunakan untuk menghasilkan file XLSX yang memiliki pengaturan yang sama seperti yang ditentukan dalam file XLTX.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/spreadsheet/xltx).


### Xlt {#Xlt}
```
public static final SpreadsheetFileType Xlt
```


File dengan ekstensi .XLT adalah file template yang dibuat dengan Microsoft Excel, sebuah aplikasi spreadsheet yang merupakan bagian dari suite Microsoft Office. Microsoft Office 97-2003 mendukung pembuatan file XLT baru serta membuka file tersebut.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/spreadsheet/xlt).


### Xltm {#Xltm}
```
public static final SpreadsheetFileType Xltm
```


Ekstensi file XLTM mewakili file yang dihasilkan oleh Microsoft Excel sebagai file template yang mendukung makro. File XLTM mirip dengan XLTX dalam struktur, kecuali bahwa yang terakhir tidak mendukung pembuatan file template dengan makro.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/spreadsheet/xltm).


### Tsv {#Tsv}
```
public static final SpreadsheetFileType Tsv
```


Format file Tab-Separated Values (TSV) mewakili data yang dipisahkan dengan tab dalam format teks biasa.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/spreadsheet/tsv).


### Xlam {#Xlam}
```
public static final SpreadsheetFileType Xlam
```


XLAM adalah file Add-In yang mendukung makro yang digunakan untuk menambahkan fungsi baru ke spreadsheet. Add-In adalah program tambahan yang menjalankan kode tambahan dan menyediakan fungsionalitas tambahan untuk spreadsheet.
Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/spreadsheet/xlam/)


### Csv {#Csv}
```
public static final SpreadsheetFileType Csv
```


File dengan ekstensi CSV (Comma Separated Values) mewakili file teks biasa yang berisi catatan data dengan nilai yang dipisahkan koma.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/spreadsheet/csv).


### Fods {#Fods}
```
public static final SpreadsheetFileType Fods
```


File dengan ekstensi .fods adalah jenis format dokumen OpenDocument Spreadsheet yang menyimpan data dalam baris dan kolom. Format ini ditentukan sebagai bagian dari spesifikasi ODF 1.2 yang dipublikasikan dan dipelihara oleh OASIS. Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/spreadsheet/fods).


### Dif {#Dif}
```
public static final SpreadsheetFileType Dif
```


DIF merupakan singkatan dari Data Interchange Format yang digunakan untuk mengimpor/mengekspor data spreadsheet antara berbagai aplikasi. Ini termasuk Microsoft Excel, OpenOffice Calc, StarCalc, dan banyak lainnya. Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/spreadsheet/dif).


### Sxc {#Sxc}
```
public static final SpreadsheetFileType Sxc
```


Format file SXC (Sun XML Calc) merupakan bagian dari suite perkantoran yang disebut OpenOffice.org. Format ini umumnya memenuhi kebutuhan spreadsheet pengguna karena merupakan format file spreadsheet berbasis XML. Format SXC mendukung rumus, fungsi, makro, dan diagram bersama DataPilot. Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/spreadsheet/sxc).


### Numbers {#Numbers}
```
public static final SpreadsheetFileType Numbers
```


File dengan ekstensi .numbers diklasifikasikan sebagai tipe file spreadsheet, itulah mengapa mereka mirip dengan file .xlsx; namun file Numbers dibuat dengan menggunakan perangkat lunak spreadsheet Apple iWork Numbers. Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/spreadsheet/numbers).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Menyiapkan opsi muat default untuk tipe file sumber


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Menyiapkan opsi konversi default untuk tipe file


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static final FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
