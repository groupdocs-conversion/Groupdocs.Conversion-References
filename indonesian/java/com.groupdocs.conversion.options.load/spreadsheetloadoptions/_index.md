---
title: "SpreadsheetLoadOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Opsi untuk memuat dokumen Spreadsheet."
type: docs
weight: 31
url: /id/java/com.groupdocs.conversion.options.load/spreadsheetloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable, [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class SpreadsheetLoadOptions extends LoadOptions implements Cloneable, Serializable, IDocumentsContainerLoadOptions
```

Opsi untuk memuat dokumen Spreadsheet.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [SpreadsheetLoadOptions()](#SpreadsheetLoadOptions--) | Menginisialisasi instance baru dari kelas [SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions). |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getSheets()](#getSheets--) | Dapatkan nama lembar untuk dikonversi |
|
|  | [setSheets(List<String> sheets)](#setSheets-java.util.List-java.lang.String--) | Atur nama lembar untuk dikonversi |
|
|  | [getCultureInfo()](#getCultureInfo--) | Dapatkan informasi budaya sistem pada saat file dimuat |
|
|  | [setCultureInfo(System.Globalization.CultureInfo cultureInfo)](#setCultureInfo-com.aspose.ms.System.Globalization.CultureInfo-) | Atur informasi budaya sistem pada saat file dimuat |
|
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Font default untuk dokumen spreadsheet. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Font default untuk dokumen spreadsheet. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Ganti font tertentu saat mengonversi dokumen spreadsheet. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Ganti font tertentu saat mengonversi dokumen spreadsheet. |
|
|  | [getShowGridLines()](#getShowGridLines--) | Tampilkan garis kisi saat mengonversi file Excel. |
|
|  | [setShowGridLines(boolean value)](#setShowGridLines-boolean-) | Tampilkan garis kisi saat mengonversi file Excel. |
|
|  | [getShowHiddenSheets()](#getShowHiddenSheets--) | Tampilkan lembar tersembunyi saat mengonversi file Excel. |
|
|  | [setShowHiddenSheets(boolean value)](#setShowHiddenSheets-boolean-) | Tampilkan lembar tersembunyi saat mengonversi file Excel. |
|
|  | [getOnePagePerSheet()](#getOnePagePerSheet--) | Jika OnePagePerSheet bernilai true, konten lembar akan dikonversi menjadi satu halaman dalam dokumen PDF. |
|
|  | [setOnePagePerSheet(boolean value)](#setOnePagePerSheet-boolean-) | Jika OnePagePerSheet bernilai true, konten lembar akan dikonversi menjadi satu halaman dalam dokumen PDF. |
|
|  | [getAllColumnsInOnePagePerSheet()](#getAllColumnsInOnePagePerSheet--) | Mendapatkan properti AllColumnsInOnePagePerSheet |
|
|  | [setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet)](#setAllColumnsInOnePagePerSheet-boolean-) | Mengatur properti AllColumnsInOnePagePerSheet |
|
|  | [getOptimizePdfSize()](#getOptimizePdfSize--) | Jika True dan mengonversi ke PDF, konversi dioptimalkan untuk ukuran file yang lebih baik daripada kualitas cetak. |
|
|  | [setOptimizePdfSize(boolean value)](#setOptimizePdfSize-boolean-) | Jika True dan mengonversi ke PDF, konversi dioptimalkan untuk ukuran file yang lebih baik daripada kualitas cetak. |
|
|  | [getConvertRange()](#getConvertRange--) | Konversi rentang tertentu saat mengonversi ke format selain spreadsheet. |
|
|  | [setConvertRange(String value)](#setConvertRange-java.lang.String-) | Konversi rentang tertentu saat mengonversi ke format selain spreadsheet. |
|
|  | [getSkipEmptyRowsAndColumns()](#getSkipEmptyRowsAndColumns--) | Lewati baris dan kolom kosong saat mengonversi. |
|
|  | [setSkipEmptyRowsAndColumns(boolean value)](#setSkipEmptyRowsAndColumns-boolean-) | Lewati baris dan kolom kosong saat mengonversi. |
|
|  | [getPassword()](#getPassword--) | Atur kata sandi untuk membuka proteksi dokumen yang dilindungi. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Atur kata sandi untuk membuka proteksi dokumen yang dilindungi. |
|
|  | [getHideComments()](#getHideComments--) | Sembunyikan komentar. |
|
|  | [setHideComments(boolean value)](#setHideComments-boolean-) | Sembunyikan komentar. |
|
|  | [isCheckExcelRestriction()](#isCheckExcelRestriction--) | Apakah memeriksa pembatasan file Excel ketika pengguna memodifikasi objek terkait sel. |
|
| [setCheckExcelRestriction(boolean checkExcelRestriction)](#setCheckExcelRestriction-boolean-) |  |
|  | [getSheetIndexes()](#getSheetIndexes--) | Mendapatkan Daftar indeks lembar untuk dikonversi. |
|
|  | [setSheetIndexes(List<Integer> sheetIndexes)](#setSheetIndexes-java.util.List-java.lang.Integer--) | Mengatur Daftar indeks lembar untuk dikonversi. |
|
|  | [isAutoFitRows()](#isAutoFitRows--) | Sesuaikan otomatis semua baris saat mengonversi |
|
| [setAutoFitRows(boolean autoFitRows)](#setAutoFitRows-boolean-) |  |
|  | [getResetFontFolders()](#getResetFontFolders--) | Reset folder font sebelum memuat dokumen |
|
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
|  | [deepClone()](#deepClone--) | Menggandakan instance saat ini. |
|
|  | [getRowsPerPage()](#getRowsPerPage--) | Bagi lembar kerja menjadi halaman berdasarkan baris. |
|
|  | [setRowsPerPage(int rowsPerPage)](#setRowsPerPage-int-) | Bagi lembar kerja menjadi halaman berdasarkan baris. |
|
|  | [getColumnsPerPage()](#getColumnsPerPage--) | Bagi lembar kerja menjadi halaman berdasarkan kolom. |
|
|  | [setColumnsPerPage(int columnsPerPage)](#setColumnsPerPage-int-) | Bagi lembar kerja menjadi halaman berdasarkan kolom. |
|
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
### SpreadsheetLoadOptions() {#SpreadsheetLoadOptions--}
```
public SpreadsheetLoadOptions()
```


Menginisialisasi instance baru dari kelas [SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions).


### getSheets() {#getSheets--}
```
public List<String> getSheets()
```


Dapatkan nama lembar untuk dikonversi


**Returns:**
java.util.List<java.lang.String>
### setSheets(List<String> sheets) {#setSheets-java.util.List-java.lang.String--}
```
public void setSheets(List<String> sheets)
```


Atur nama lembar untuk dikonversi


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lembar | java.util.List<java.lang.String> |  |

### getCultureInfo() {#getCultureInfo--}
```
public System.Globalization.CultureInfo getCultureInfo()
```


Dapatkan informasi budaya sistem pada saat file dimuat


**Returns:**
com.aspose.ms.System.Globalization.CultureInfo
### setCultureInfo(System.Globalization.CultureInfo cultureInfo) {#setCultureInfo-com.aspose.ms.System.Globalization.CultureInfo-}
```
public void setCultureInfo(System.Globalization.CultureInfo cultureInfo)
```


Atur informasi budaya sistem pada saat file dimuat


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cultureInfo | com.aspose.ms.System.Globalization.CultureInfo |  |

### getFormat() {#getFormat--}
```
public final SpreadsheetFileType getFormat()
```


Jenis berkas dokumen input


**Returns:**
[SpreadsheetFileType](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Font default untuk dokumen spreadsheet. Font berikut akan digunakan jika sebuah font tidak ada.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Font default untuk dokumen spreadsheet. Font berikut akan digunakan jika sebuah font tidak ada.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Ganti font tertentu saat mengonversi dokumen spreadsheet.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Ganti font tertentu saat mengonversi dokumen spreadsheet.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getShowGridLines() {#getShowGridLines--}
```
public final boolean getShowGridLines()
```


Tampilkan garis kisi saat mengonversi file Excel.


**Returns:**
boolean
### setShowGridLines(boolean value) {#setShowGridLines-boolean-}
```
public final void setShowGridLines(boolean value)
```


Tampilkan garis kisi saat mengonversi file Excel.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getShowHiddenSheets() {#getShowHiddenSheets--}
```
public final boolean getShowHiddenSheets()
```


Tampilkan lembar tersembunyi saat mengonversi file Excel.


**Returns:**
boolean
### setShowHiddenSheets(boolean value) {#setShowHiddenSheets-boolean-}
```
public final void setShowHiddenSheets(boolean value)
```


Tampilkan lembar tersembunyi saat mengonversi file Excel.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getOnePagePerSheet() {#getOnePagePerSheet--}
```
public final boolean getOnePagePerSheet()
```


Jika OnePagePerSheet bernilai true, konten lembar akan dikonversi menjadi satu halaman dalam dokumen PDF. Nilai default adalah false.


**Returns:**
boolean
### setOnePagePerSheet(boolean value) {#setOnePagePerSheet-boolean-}
```
public final void setOnePagePerSheet(boolean value)
```


Jika OnePagePerSheet bernilai true, konten lembar akan dikonversi menjadi satu halaman dalam dokumen PDF. Nilai default adalah false.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getAllColumnsInOnePagePerSheet() {#getAllColumnsInOnePagePerSheet--}
```
public boolean getAllColumnsInOnePagePerSheet()
```


Mendapatkan properti AllColumnsInOnePagePerSheet


**Returns:**
boolean - true jika menyesuaikan semua kolom ke satu halaman

### setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet) {#setAllColumnsInOnePagePerSheet-boolean-}
```
public void setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet)
```


Mengatur properti AllColumnsInOnePagePerSheet


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | allColumnsInOnePagePerSheet | boolean | Properti AllColumnsInOnePagePerSheet |
|

### getOptimizePdfSize() {#getOptimizePdfSize--}
```
public final boolean getOptimizePdfSize()
```


Jika True dan mengonversi ke PDF, konversi dioptimalkan untuk ukuran file yang lebih baik daripada kualitas cetak.


**Returns:**
boolean
### setOptimizePdfSize(boolean value) {#setOptimizePdfSize-boolean-}
```
public final void setOptimizePdfSize(boolean value)
```


Jika True dan mengonversi ke PDF, konversi dioptimalkan untuk ukuran file yang lebih baik daripada kualitas cetak.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getConvertRange() {#getConvertRange--}
```
public final String getConvertRange()
```


Konversi rentang tertentu saat mengonversi ke format selain spreadsheet. Contoh: "D1:F8".


**Returns:**
java.lang.String
### setConvertRange(String value) {#setConvertRange-java.lang.String-}
```
public final void setConvertRange(String value)
```


Konversi rentang tertentu saat mengonversi ke format selain spreadsheet. Contoh: "D1:F8".


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getSkipEmptyRowsAndColumns() {#getSkipEmptyRowsAndColumns--}
```
public final boolean getSkipEmptyRowsAndColumns()
```


Lewati baris dan kolom kosong saat mengonversi. Default adalah True.


**Returns:**
boolean
### setSkipEmptyRowsAndColumns(boolean value) {#setSkipEmptyRowsAndColumns-boolean-}
```
public final void setSkipEmptyRowsAndColumns(boolean value)
```


Lewati baris dan kolom kosong saat mengonversi. Default adalah True.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Atur kata sandi untuk membuka proteksi dokumen yang dilindungi.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Atur kata sandi untuk membuka proteksi dokumen yang dilindungi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getHideComments() {#getHideComments--}
```
public final boolean getHideComments()
```


Sembunyikan komentar.


**Returns:**
boolean
### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


Sembunyikan komentar.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### isCheckExcelRestriction() {#isCheckExcelRestriction--}
```
public boolean isCheckExcelRestriction()
```


Apakah memeriksa pembatasan file Excel ketika pengguna memodifikasi objek terkait sel. Misalnya, Excel tidak mengizinkan memasukkan nilai string yang lebih panjang dari 32K. Ketika Anda memasukkan nilai yang lebih panjang dari 32K, jika properti ini bernilai true, Anda akan mendapatkan Exception. Jika properti ini bernilai false, kami akan menerima nilai string yang Anda masukkan sebagai nilai sel sehingga nanti Anda dapat mengeluarkan nilai string lengkap untuk format file lain seperti CSV. Namun, jika Anda telah menetapkan nilai semacam itu yang tidak valid untuk format file Excel, Anda tidak boleh menyimpan workbook sebagai format file Excel nanti. Jika tidak, mungkin terjadi kesalahan tak terduga pada file Excel yang dihasilkan.


**Returns:**
boolean - flag pemeriksaan pembatasan

### setCheckExcelRestriction(boolean checkExcelRestriction) {#setCheckExcelRestriction-boolean-}
```
public void setCheckExcelRestriction(boolean checkExcelRestriction)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| checkExcelRestriction | boolean |  |

### getSheetIndexes() {#getSheetIndexes--}
```
public List<Integer> getSheetIndexes()
```


Mendapatkan Daftar indeks lembar untuk dikonversi.


**Returns:**
java.util.List<java.lang.Integer>
### setSheetIndexes(List<Integer> sheetIndexes) {#setSheetIndexes-java.util.List-java.lang.Integer--}
```
public void setSheetIndexes(List<Integer> sheetIndexes)
```


Mengatur Daftar indeks lembar yang akan dikonversi. Indeks harus berbasis nol.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sheetIndexes | java.util.List<java.lang.Integer> |  |

### isAutoFitRows() {#isAutoFitRows--}
```
public boolean isAutoFitRows()
```


Sesuaikan otomatis semua baris saat mengonversi


**Returns:**
boolean
### setAutoFitRows(boolean autoFitRows) {#setAutoFitRows-boolean-}
```
public void setAutoFitRows(boolean autoFitRows)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| autoFitRows | boolean |  |

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


Reset folder font sebelum memuat dokumen


**Returns:**
boolean
### setResetFontFolders(boolean resetFontFolders) {#setResetFontFolders-boolean-}
```
public void setResetFontFolders(boolean resetFontFolders)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| resetFontFolders | boolean |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Menggandakan instance saat ini.


**Returns:**
java.lang.Object -
### getRowsPerPage() {#getRowsPerPage--}
```
public int getRowsPerPage()
```


Membagi lembar kerja menjadi halaman per baris. Default adalah 0, tanpa paginasi.


**Returns:**
int
### setRowsPerPage(int rowsPerPage) {#setRowsPerPage-int-}
```
public void setRowsPerPage(int rowsPerPage)
```


Membagi lembar kerja menjadi halaman per baris. Default adalah 0, tanpa paginasi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rowsPerPage | int |  |

### getColumnsPerPage() {#getColumnsPerPage--}
```
public int getColumnsPerPage()
```


Membagi lembar kerja menjadi halaman per kolom. Default adalah 0, tanpa paginasi.


**Returns:**
int
### setColumnsPerPage(int columnsPerPage) {#setColumnsPerPage-int-}
```
public void setColumnsPerPage(int columnsPerPage)
```


Membagi lembar kerja menjadi halaman per kolom. Default adalah 0, tanpa paginasi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| columnsPerPage | int |  |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Mendapatkan opsi untuk mengontrol apakah kontainer dokumen itu sendiri harus dikonversi


**Returns:**
boolean
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| convertOwner | boolean |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Opsi untuk mengontrol apakah dokumen yang dimiliki dalam kontainer dokumen harus dikonversi


**Returns:**
boolean
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| convertOwned | boolean |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Opsi untuk mengontrol berapa banyak tingkat kedalaman untuk melakukan konversi


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| depth | int |  |

