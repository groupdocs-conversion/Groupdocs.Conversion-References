---
title: "SpreadsheetLoadOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Opsi untuk memuat dokumen Spreadsheet."
type: docs
weight: 2810
url: /id/net/groupdocs.conversion.options.load/spreadsheetloadoptions/
---
## SpreadsheetLoadOptions class

Opsi untuk memuat dokumen Spreadsheet.

```csharp
public class SpreadsheetLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IMetadataLoadOptions, IPageMarginOptions, IPageSizeOptions, 
    IResourceLoadingOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SpreadsheetLoadOptions](spreadsheetloadoptions)() | Menginisialisasi instance baru dari kelas [`SpreadsheetLoadOptions`](../spreadsheetloadoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AllColumnsInOnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/allcolumnsinonepagepersheet) { get; set; } | Jika AllColumnsInOnePagePerSheet bernilai true, semua konten kolom dari satu lembar akan dikeluarkan ke satu halaman saja dalam hasil. Lebar ukuran kertas pada pagesetup akan menjadi tidak valid, namun pengaturan lain pada pagesetup tetap berlaku. |
| [AutoFitRows](../../groupdocs.conversion.options.load/spreadsheetloadoptions/autofitrows) { get; set; } | Menyesuaikan otomatis semua baris saat mengonversi |
| [CheckExcelRestriction](../../groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction) { get; set; } | Apakah memeriksa pembatasan file excel ketika pengguna memodifikasi objek terkait sel. Misalnya, excel tidak mengizinkan memasukkan nilai string yang lebih panjang dari 32K. Ketika Anda memasukkan nilai yang lebih panjang dari 32K, jika properti ini bernilai true, Anda akan mendapatkan Exception. Jika properti ini bernilai false, kami akan menerima nilai string yang Anda masukkan sebagai nilai sel sehingga nanti Anda dapat mengeluarkan nilai string lengkap untuk format file lain seperti CSV. Namun, jika Anda telah menetapkan nilai semacam itu yang tidak valid untuk format file excel, Anda tidak boleh menyimpan workbook sebagai format file excel nanti. Jika tidak, mungkin terjadi kesalahan tak terduga pada file excel yang dihasilkan. |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clearbuiltindocumentproperties) { get; set; } | Menghapus properti metadata bawaan dari dokumen. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clearcustomdocumentproperties) { get; set; } | Menghapus properti metadata kustom dari dokumen. |
| [ColumnsPerPage](../../groupdocs.conversion.options.load/spreadsheetloadoptions/columnsperpage) { get; set; } | Membagi lembar kerja menjadi halaman berdasarkan kolom. Nilai default adalah 0, tanpa paginasi. |
| [ConvertOwned](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertowned) { get; set; } | Menerapkan [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) Default adalah false |
| [ConvertOwner](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertowner) { get; set; } | Menerapkan [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) Default adalah true |
| [ConvertRange](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertrange) { get; set; } | Mengonversi rentang tertentu saat mengonversi ke format selain spreadsheet. Contoh: "D1:F8". |
| [CultureInfo](../../groupdocs.conversion.options.load/spreadsheetloadoptions/cultureinfo) { get; set; } | Mendapatkan atau mengatur informasi budaya sistem pada saat file dimuat |
| [DefaultFont](../../groupdocs.conversion.options.load/spreadsheetloadoptions/defaultfont) { get; set; } | Font default untuk dokumen spreadsheet. Font berikut akan digunakan jika sebuah font tidak tersedia. |
| [Depth](../../groupdocs.conversion.options.load/spreadsheetloadoptions/depth) { get; set; } | Menerapkan [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Default: 1 |
| [FontSubstitutes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/fontsubstitutes) { get; set; } | Mengganti font tertentu saat mengonversi dokumen spreadsheet. |
| [Format](../../groupdocs.conversion.options.load/spreadsheetloadoptions/format) { get; set; } | Tipe berkas dokumen input. Nilainya `null` sampai format ditetapkan, jadi periksa apakah `null` daripada membandingkannya dengan [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), yang tidak pernah sama. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipe berkas dokumen input. |
| [IgnoreFormulaCalculationErrors](../../groupdocs.conversion.options.load/spreadsheetloadoptions/ignoreformulacalculationerrors) { get; set; } | Menunjukkan apakah akan mengabaikan kesalahan perhitungan formula. Kesalahan dapat berupa fungsi yang tidak didukung, tautan eksternal, dll. Nilai default adalah false. |
| [MarginSettings](../../groupdocs.conversion.options.load/spreadsheetloadoptions/marginsettings) { get; set; } | Pengaturan margin halaman |
| [OnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/onepagepersheet) { get; set; } | Jika OnePagePerSheet bernilai true, konten lembar akan dikonversi menjadi satu halaman dalam dokumen PDF. Nilai default adalah true. |
| [OptimizePdfSize](../../groupdocs.conversion.options.load/spreadsheetloadoptions/optimizepdfsize) { get; set; } | Jika True dan mengonversi ke PDF, konversi dioptimalkan untuk ukuran file yang lebih baik dibandingkan kualitas cetak. |
| [Password](../../groupdocs.conversion.options.load/spreadsheetloadoptions/password) { get; set; } | Atur kata sandi untuk membuka proteksi dokumen yang dilindungi. |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/spreadsheetloadoptions/preservedocumentstructure) { get; set; } | Menentukan apakah struktur dokumen harus dipertahankan saat mengonversi ke PDF (default adalah false). |
| [PrintComments](../../groupdocs.conversion.options.load/spreadsheetloadoptions/printcomments) { get; set; } | Mewakili cara komentar dicetak bersama lembar. Nilai default adalah PrintNoComments. |
| [ResetFontFolders](../../groupdocs.conversion.options.load/spreadsheetloadoptions/resetfontfolders) { get; set; } | Atur ulang folder font sebelum memuat dokumen |
| [RowsPerPage](../../groupdocs.conversion.options.load/spreadsheetloadoptions/rowsperpage) { get; set; } | Membagi lembar kerja menjadi halaman berdasarkan baris. Nilai default adalah 0, tanpa paginasi. |
| [SheetIndexes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheetindexes) { get; set; } | Daftar indeks lembar yang akan dikonversi. Indeks harus berbasis nol |
| [Sheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheets) { get; set; } | Nama lembar yang akan dikonversi |
| [ShowGridLines](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showgridlines) { get; set; } | Tampilkan garis kisi saat mengonversi file Excel. |
| [ShowHiddenSheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showhiddensheets) { get; set; } | Tampilkan lembar tersembunyi saat mengonversi file Excel. |
| [SizeSettings](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sizesettings) { get; set; } | Pengaturan ukuran halaman |
| [SkipEmptyRowsAndColumns](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipemptyrowsandcolumns) { get; set; } | Lewati baris dan kolom kosong saat mengonversi. Nilai default adalah True. |
| [SkipExternalResources](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipexternalresources) { get; set; } | Menerapkan [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [SkipFooters](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipfooters) { get; set; } | Lewati footer saat mengonversi dokumen spreadsheet. Nilai default: false. |
| [SkipHeaders](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipheaders) { get; set; } | Lewati header saat mengonversi dokumen spreadsheet. Nilai default: false. |
| [WhitelistedResources](../../groupdocs.conversion.options.load/spreadsheetloadoptions/whitelistedresources) { get; set; } | Menerapkan [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clone)() | Mengkloning instance saat ini. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat Juga

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IMetadataLoadOptions](../imetadataloadoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
