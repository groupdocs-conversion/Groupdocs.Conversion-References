---
title: CsvLoadOptions
second_title: GroupDocs.Konversi untuk Referensi .NET API
description: Opsi untuk memuat dokumen Csv.
type: docs
weight: 2050
url: /id/net/groupdocs.conversion.options.load/csvloadoptions/
---
## CsvLoadOptions class

Opsi untuk memuat dokumen Csv.

```csharp
public sealed class CsvLoadOptions : SpreadsheetLoadOptions
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [CsvLoadOptions](csvloadoptions)() | Menginisialisasi instance baru[`CsvLoadOptions`](../csvloadoptions) kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [CheckExcelRestriction](../../groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction) { get; set; } | Apakah memeriksa pembatasan file excel saat pengguna memodifikasi objek terkait sel. Misalnya, excel tidak mengizinkan memasukkan nilai string lebih dari 32K. Saat Anda memasukkan nilai lebih dari 32K, jika properti ini benar, Anda akan mendapatkan Pengecualian. Jika properti ini salah, kami akan menerima nilai string input Anda sebagai nilai sel sehingga nantinya Anda dapat menampilkan nilai string lengkap untuk format file lain seperti CSV. Namun, jika Anda telah menetapkan nilai yang tidak valid untuk format file excel, Anda sebaiknya tidak menyimpan buku kerja sebagai format file excel nanti. Kalau tidak, mungkin ada kesalahan tak terduga untuk file excel yang dihasilkan. |
| [ConvertDateTimeData](../../groupdocs.conversion.options.load/csvloadoptions/convertdatetimedata) { get; set; } | Menunjukkan apakah string dalam file dikonversi ke tanggal. Standarnya adalah Benar. |
| [ConvertNumericData](../../groupdocs.conversion.options.load/csvloadoptions/convertnumericdata) { get; set; } | Menunjukkan apakah string dalam file diubah menjadi numerik. Standarnya adalah Benar. |
| [ConvertRange](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertrange) { get; set; } | Mengonversi rentang tertentu saat mengonversi ke selain format spreadsheet. Contoh: "D1:F8". |
| [CultureInfo](../../groupdocs.conversion.options.load/spreadsheetloadoptions/cultureinfo) { get; set; } | Dapatkan atau setel info kultur sistem saat file dimuat |
| [DefaultFont](../../groupdocs.conversion.options.load/spreadsheetloadoptions/defaultfont) { get; set; } | Font default untuk dokumen spreadsheet. Font berikut akan digunakan jika font hilang. |
| [Encoding](../../groupdocs.conversion.options.load/csvloadoptions/encoding) { get; set; } | Pengkodean. Standarnya adalah Penyandian.Default. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/fontsubstitutes) { get; set; } | Mengganti font tertentu saat mengonversi dokumen spreadsheet. |
| [Format](../../groupdocs.conversion.options.load/spreadsheetloadoptions/format) { get; set; } | Jenis file dokumen masukan. |
| [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Jenis file dokumen masukan. |
| [HasFormula](../../groupdocs.conversion.options.load/csvloadoptions/hasformula) { get; set; } | Menunjukkan apakah teks adalah rumus jika dimulai dengan "=". |
| [HideComments](../../groupdocs.conversion.options.load/spreadsheetloadoptions/hidecomments) { get; set; } | Sembunyikan komentar. |
| [IsMultiEncoded](../../groupdocs.conversion.options.load/csvloadoptions/ismultiencoded) { get; set; } | True berarti file berisi beberapa penyandian. |
| [OnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/onepagepersheet) { get; set; } | Jika OnePagePerSheet benar, konten lembar akan dikonversi menjadi satu halaman dalam dokumen PDF. Nilai default adalah true. |
| [OptimizePdfSize](../../groupdocs.conversion.options.load/spreadsheetloadoptions/optimizepdfsize) { get; set; } | Jika True dan mengonversi ke Pdf, konversi dioptimalkan untuk ukuran file yang lebih baik daripada kualitas cetak. |
| [Password](../../groupdocs.conversion.options.load/spreadsheetloadoptions/password) { get; set; } | Tetapkan kata sandi untuk membuka proteksi dokumen yang dilindungi. |
| [Separator](../../groupdocs.conversion.options.load/csvloadoptions/separator) { get; set; } | Pembatas file Csv. |
| [SheetIndexes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheetindexes) { get; set; } | Daftar indeks sheet yang akan dikonversi. Indeks harus berbasis nol |
| [Sheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheets) { get; set; } | Nama sheet yang akan dikonversi |
| [ShowGridLines](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showgridlines) { get; set; } | Tampilkan garis kisi saat mengonversi file Excel. |
| [ShowHiddenSheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showhiddensheets) { get; set; } | Tampilkan lembar tersembunyi saat mengonversi file Excel. |
| [SkipEmptyRowsAndColumns](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipemptyrowsandcolumns) { get; set; } | Melewati baris dan kolom kosong saat mengonversi. Standarnya adalah Benar. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clone)() | Mengkloning instance saat ini. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat juga

* class [SpreadsheetLoadOptions](../spreadsheetloadoptions)
* ruang nama [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* perakitan [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
