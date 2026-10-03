---
title: "PdfLoadOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Opsi untuk memuat dokumen Pdf."
type: docs
weight: 27
url: /id/java/com.groupdocs.conversion.options.load/pdfloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IPageNumberingLoadOptions](../../com.groupdocs.conversion.options.load/ipagenumberingloadoptions), [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public final class PdfLoadOptions extends LoadOptions implements Serializable, IPageNumberingLoadOptions, IDocumentsContainerLoadOptions
```

Opsi untuk memuat dokumen Pdf.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [PdfLoadOptions()](#PdfLoadOptions--) | Menginisialisasi instance baru dari kelas [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions). |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getRemoveEmbeddedFiles()](#getRemoveEmbeddedFiles--) | Hapus file tersemat. |
|
|  | [setRemoveEmbeddedFiles(boolean value)](#setRemoveEmbeddedFiles-boolean-) | Hapus file tersemat. |
|
|  | [getPassword()](#getPassword--) | Atur kata sandi untuk membuka proteksi dokumen yang dilindungi. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Atur kata sandi untuk membuka proteksi dokumen yang dilindungi. |
|
|  | [getDefaultFont()](#getDefaultFont--) | Font default untuk dokumen Pdf. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Font default untuk dokumen Pdf. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Ganti font tertentu saat mengonversi dokumen Pdf. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Ganti font tertentu saat mengonversi dokumen Pdf. |
|
|  | [getHidePdfAnnotations()](#getHidePdfAnnotations--) | Sembunyikan anotasi dalam dokumen Pdf. |
|
|  | [setHidePdfAnnotations(boolean value)](#setHidePdfAnnotations-boolean-) | Sembunyikan anotasi dalam dokumen Pdf. |
|
|  | [getFlattenAllFields()](#getFlattenAllFields--) | Ratakan semua bidang formulir PDF. |
|
|  | [setFlattenAllFields(boolean value)](#setFlattenAllFields-boolean-) | Ratakan semua bidang formulir PDF. |
|
|  | [getResetFontFolders()](#getResetFontFolders--) | Setel ulang folder font sebelum memuat dokumen. |
|
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
|  | [isPageNumbering()](#isPageNumbering--) | Aktifkan atau nonaktifkan pembuatan penomoran halaman dalam dokumen yang dikonversi. |
|
| [setPageNumbering(boolean isPageNumbering)](#setPageNumbering-boolean-) |  |
|  | [isRemoveJavascript()](#isRemoveJavascript--) | Mendapatkan flag Remove JavaScript. |
|
|  | [setRemoveJavascript(boolean removeJavascript)](#setRemoveJavascript-boolean-) | Mengatur flag Remove JavaScript. |
|
|  | [isConvertOwner()](#isConvertOwner--) | Menentukan apakah dokumen pemilik harus dikonversi. |
|
|  | [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) | Menentukan apakah dokumen pemilik harus dikonversi. |
|
|  | [isConvertOwned()](#isConvertOwned--) | Menentukan apakah dokumen yang dimiliki harus dikonversi. |
|
|  | [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) | Menentukan apakah dokumen yang dimiliki harus dikonversi. |
|
|  | [getDepth()](#getDepth--) | Kedalaman maksimum untuk memproses dokumen yang dimiliki. |
|
|  | [setDepth(int depth)](#setDepth-int-) | Kedalaman maksimum untuk memproses dokumen yang dimiliki. |
|
### PdfLoadOptions() {#PdfLoadOptions--}
```
public PdfLoadOptions()
```


Menginisialisasi instance baru dari kelas [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions).


### getFormat() {#getFormat--}
```
public final PdfFileType getFormat()
```


Jenis berkas dokumen input


**Returns:**
[PdfFileType](../../com.groupdocs.conversion.filetypes/pdffiletype)
### getRemoveEmbeddedFiles() {#getRemoveEmbeddedFiles--}
```
public final boolean getRemoveEmbeddedFiles()
```


Hapus file tersemat.


**Returns:**
boolean
### setRemoveEmbeddedFiles(boolean value) {#setRemoveEmbeddedFiles-boolean-}
```
public final void setRemoveEmbeddedFiles(boolean value)
```


Hapus file tersemat.


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

### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Font default untuk dokumen Pdf.
Font berikut akan digunakan jika font tidak ditemukan.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Font default untuk dokumen Pdf.
Font berikut akan digunakan jika font tidak ditemukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Ganti font tertentu saat mengonversi dokumen Pdf.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Ganti font tertentu saat mengonversi dokumen Pdf.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getHidePdfAnnotations() {#getHidePdfAnnotations--}
```
public final boolean getHidePdfAnnotations()
```


Sembunyikan anotasi dalam dokumen Pdf.


**Returns:**
boolean
### setHidePdfAnnotations(boolean value) {#setHidePdfAnnotations-boolean-}
```
public final void setHidePdfAnnotations(boolean value)
```


Sembunyikan anotasi dalam dokumen Pdf.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getFlattenAllFields() {#getFlattenAllFields--}
```
public final boolean getFlattenAllFields()
```


Ratakan semua bidang formulir PDF.


**Returns:**
boolean
### setFlattenAllFields(boolean value) {#setFlattenAllFields-boolean-}
```
public final void setFlattenAllFields(boolean value)
```


Ratakan semua bidang formulir PDF.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


Setel ulang folder font sebelum memuat dokumen.


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

### isPageNumbering() {#isPageNumbering--}
```
public boolean isPageNumbering()
```


Aktifkan atau nonaktifkan pembuatan penomoran halaman dalam dokumen yang dikonversi. Default: false.


**Returns:**
boolean
### setPageNumbering(boolean isPageNumbering) {#setPageNumbering-boolean-}
```
public void setPageNumbering(boolean isPageNumbering)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| isPageNumbering | boolean |  |

### isRemoveJavascript() {#isRemoveJavascript--}
```
public boolean isRemoveJavascript()
```


Mendapatkan flag Remove JavaScript.


**Returns:**
boolean
### setRemoveJavascript(boolean removeJavascript) {#setRemoveJavascript-boolean-}
```
public void setRemoveJavascript(boolean removeJavascript)
```


Mengatur flag Remove JavaScript.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| removeJavascript | boolean |  |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Menentukan apakah dokumen pemilik harus dikonversi.

Default adalah
true
.


**Returns:**
boolean
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```


Menentukan apakah dokumen pemilik harus dikonversi.

Default adalah
true
.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| convertOwner | boolean |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Menentukan apakah dokumen yang dimiliki harus dikonversi.

Default adalah
false
.


**Returns:**
boolean
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```


Menentukan apakah dokumen yang dimiliki harus dikonversi.

Default adalah
false
.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| convertOwned | boolean |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Kedalaman maksimum untuk memproses dokumen yang dimiliki.

Default adalah
2
.


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```


Kedalaman maksimum untuk memproses dokumen yang dimiliki.

Default adalah
2
.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| depth | int |  |

