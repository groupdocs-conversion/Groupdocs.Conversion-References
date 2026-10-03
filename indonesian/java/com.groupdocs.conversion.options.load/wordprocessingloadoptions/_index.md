---
title: "WordProcessingLoadOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Opsi untuk memuat dokumen WordProcessing."
type: docs
weight: 40
url: /id/java/com.groupdocs.conversion.options.load/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IResourceLoadingOptions](../../com.groupdocs.conversion.options.load/iresourceloadingoptions), [com.groupdocs.conversion.options.load.IPageNumberingLoadOptions](../../com.groupdocs.conversion.options.load/ipagenumberingloadoptions), [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class WordProcessingLoadOptions extends LoadOptions implements Serializable, IResourceLoadingOptions, IPageNumberingLoadOptions, IDocumentsContainerLoadOptions
```

Opsi untuk memuat dokumen WordProcessing.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) | Menginisialisasi instance baru dari kelas [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions). |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Font default untuk dokumen Words. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Font default untuk dokumen Words. |
|
|  | [getAutoFontSubstitution()](#getAutoFontSubstitution--) | Jika AutoFontSubstitution dinonaktifkan, GroupDocs.Conversion menggunakan DefaultFont untuk substitusi font yang hilang. |
|
|  | [setAutoFontSubstitution(boolean value)](#setAutoFontSubstitution-boolean-) | Jika AutoFontSubstitution dinonaktifkan, GroupDocs.Conversion menggunakan DefaultFont untuk substitusi font yang hilang. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Substitusi font tertentu saat mengonversi dokumen Words. |
|
|  | [isEmbedTrueTypeFonts()](#isEmbedTrueTypeFonts--) | Jika EmbedTrueTypeFonts bernilai true, GroupDocs.Conversion menyematkan font TrueType dalam dokumen output. |
|
| [setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)](#setEmbedTrueTypeFonts-boolean-) |  |
|  | [isUpdatePageLayout()](#isUpdatePageLayout--) | Perbarui tata letak halaman setelah memuat. |
|
| [setUpdatePageLayout(boolean updatePageLayout)](#setUpdatePageLayout-boolean-) |  |
|  | [isUpdateFields()](#isUpdateFields--) | Perbarui bidang setelah memuat. |
|
| [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) |  |
|  | [isKeepDateFieldOriginalValue()](#isKeepDateFieldOriginalValue--) | Pertahankan nilai asli bidang tanggal. |
|
|  | [setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)](#setKeepDateFieldOriginalValue-boolean-) | Mengatur agar mempertahankan nilai asli bidang tanggal. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Substitusi font tertentu saat mengonversi dokumen Words. |
|
|  | [getPassword()](#getPassword--) | Atur kata sandi untuk membuka proteksi dokumen yang dilindungi. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Atur kata sandi untuk membuka proteksi dokumen yang dilindungi. |
|
|  | [getHideWordTrackedChanges()](#getHideWordTrackedChanges--) | Sembunyikan markup dan pelacakan perubahan untuk dokumen Word. |
|
|  | [setHideWordTrackedChanges(boolean value)](#setHideWordTrackedChanges-boolean-) | Sembunyikan markup dan pelacakan perubahan untuk dokumen Word. |
|
|  | [setHideComments(boolean value)](#setHideComments-boolean-) | Sembunyikan komentar. |
|
|  | [getBookmarkOptions()](#getBookmarkOptions--) | Opsi bookmark |
|
|  | [setBookmarkOptions(WordProcessingBookmarksOptions value)](#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-) | Opsi bookmark |
|
|  | [isPreserveFontFields()](#isPreserveFontFields--) | Menentukan apakah akan mempertahankan bidang formulir Microsoft Word sebagai bidang formulir dalam PDF atau mengonversinya menjadi teks. |
|
|  | [setPreserveFontFields(boolean preserveFontFields)](#setPreserveFontFields-boolean-) | Mengatur flag preserveFontFields |
|
|  | [isUseTextShaper()](#isUseTextShaper--) | Menentukan apakah akan menggunakan text shaper untuk tampilan kerning yang lebih baik. |
|
|  | [setUseTextShaper(boolean isUseTextShaper)](#setUseTextShaper-boolean-) | Menentukan apakah akan menggunakan text shaper untuk tampilan kerning yang lebih baik. |
|
|  | [isPreserveDocumentStructure()](#isPreserveDocumentStructure--) | Menentukan apakah struktur dokumen harus dipertahankan saat mengonversi ke PDF (default adalah false). |
|
| [setPreserveDocumentStructure(boolean preserveDocumentStructure)](#setPreserveDocumentStructure-boolean-) |  |
|  | [getSkipExternalResources()](#getSkipExternalResources--) | {@inheritDoc} |
|
|  | [setSkipExternalResources(boolean skip)](#setSkipExternalResources-boolean-) | {@inheritDoc} |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | {@inheritDoc} |
|
|  | [setWhitelistedResources(List<String> whiteList)](#setWhitelistedResources-java.util.List-java.lang.String--) | {@inheritDoc} |
|
|  | [getCommentDisplayMode()](#getCommentDisplayMode--) | Menentukan bagaimana komentar harus ditampilkan dalam dokumen output. |
|
| [setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode)](#setCommentDisplayMode-com.groupdocs.conversion.options.load.WordProcessingCommentDisplay-) |  |
|  | [getShowFullCommenterName()](#getShowFullCommenterName--) | Tampilkan nama lengkap pemberi komentar dalam komentar. |
|
| [setShowFullCommenterName(boolean showFullCommenterName)](#setShowFullCommenterName-boolean-) |  |
|  | [isPageNumbering()](#isPageNumbering--) | Aktifkan atau nonaktifkan pembuatan penomoran halaman dalam dokumen yang dikonversi. |
|
| [setPageNumbering(boolean isPageNumbering)](#setPageNumbering-boolean-) |  |
|  | [getHyphenationOptions()](#getHyphenationOptions--) | Mendapatkan opsi hyphenation untuk dokumen WordProcessing. |
|
|  | [setHyphenationOptions(HyphenationOptions hyphenationOptions)](#setHyphenationOptions-com.groupdocs.conversion.options.load.HyphenationOptions-) | Mengatur opsi hyphenation untuk dokumen WordProcessing. |
|
|  | [isInterruptThreadIfImageExceptionThrown()](#isInterruptThreadIfImageExceptionThrown--) | Mendapatkan flag InterruptThreadIfImageExceptionThrown Default: false Jika true maka menghentikan thread konversi utama jika terjadi pengecualian pada thread pemrosesan gambar. |
|
|  | [setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown)](#setInterruptThreadIfImageExceptionThrown-boolean-) | Mengatur flag InterruptThreadIfImageExceptionThrown |
|
|  | [isAutoDetectRtlDirection()](#isAutoDetectRtlDirection--) | Ketika diaktifkan (default), paragraf dan run yang teksnya dominan kanan-ke-kiri (RTL) akan memiliki flag bidi diperbaiki sebelum konversi. |
|
|  | [setAutoDetectRtlDirection(boolean autoDetectRtlDirection)](#setAutoDetectRtlDirection-boolean-) | Mengatur autoDetectRtlDirection |
|
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
### WordProcessingLoadOptions() {#WordProcessingLoadOptions--}
```
public WordProcessingLoadOptions()
```


Menginisialisasi instance baru dari kelas [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions).


### getFormat() {#getFormat--}
```
public final WordProcessingFileType getFormat()
```


Jenis berkas dokumen input


**Returns:**
[WordProcessingFileType](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Font default untuk dokumen Words. Font berikut akan digunakan jika font tidak ada.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Font default untuk dokumen Words. Font berikut akan digunakan jika font tidak ada.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getAutoFontSubstitution() {#getAutoFontSubstitution--}
```
public final boolean getAutoFontSubstitution()
```


Jika AutoFontSubstitution dinonaktifkan, GroupDocs.Conversion menggunakan DefaultFont untuk substitusi font yang hilang. Jika AutoFontSubstitution diaktifkan,
GroupDocs.Conversion mengevaluasi semua bidang terkait dalam FontInfo (Panose, Sig, dll) untuk font yang hilang dan menemukan kecocokan terdekat di antara sumber font yang tersedia.
Catatan bahwa mekanisme substitusi font akan menggantikan DefaultFont dalam kasus ketika FontInfo untuk font yang hilang tersedia dalam dokumen. Nilai default adalah True.


**Returns:**
boolean
### setAutoFontSubstitution(boolean value) {#setAutoFontSubstitution-boolean-}
```
public final void setAutoFontSubstitution(boolean value)
```


Jika AutoFontSubstitution dinonaktifkan, GroupDocs.Conversion menggunakan DefaultFont untuk substitusi font yang hilang. Jika AutoFontSubstitution diaktifkan,
GroupDocs.Conversion mengevaluasi semua bidang terkait dalam FontInfo (Panose, Sig, dll) untuk font yang hilang dan menemukan kecocokan terdekat di antara sumber font yang tersedia.
Catatan bahwa mekanisme substitusi font akan menggantikan DefaultFont dalam kasus ketika FontInfo untuk font yang hilang tersedia dalam dokumen. Nilai default adalah True.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Substitusi font tertentu saat mengonversi dokumen Words.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### isEmbedTrueTypeFonts() {#isEmbedTrueTypeFonts--}
```
public boolean isEmbedTrueTypeFonts()
```


Jika EmbedTrueTypeFonts true, GroupDocs.Conversion menyematkan font true type dalam dokumen output. Default: false


**Returns:**
boolean
### setEmbedTrueTypeFonts(boolean embedTrueTypeFonts) {#setEmbedTrueTypeFonts-boolean-}
```
public void setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| embedTrueTypeFonts | boolean |  |

### isUpdatePageLayout() {#isUpdatePageLayout--}
```
public boolean isUpdatePageLayout()
```


Perbarui tata letak halaman setelah memuat. Default: false


**Returns:**
boolean
### setUpdatePageLayout(boolean updatePageLayout) {#setUpdatePageLayout-boolean-}
```
public void setUpdatePageLayout(boolean updatePageLayout)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| updatePageLayout | boolean |  |

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


Perbarui bidang setelah memuat. Default: false


**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| updateFields | boolean |  |

### isKeepDateFieldOriginalValue() {#isKeepDateFieldOriginalValue--}
```
public boolean isKeepDateFieldOriginalValue()
```


Pertahankan nilai asli bidang tanggal. Default: false


**Returns:**
boolean
### setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue) {#setKeepDateFieldOriginalValue-boolean-}
```
public void setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)
```


Mengatur agar mempertahankan nilai asli bidang tanggal.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| keepDateFieldOriginalValue | boolean |  |

### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Substitusi font tertentu saat mengonversi dokumen Words.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

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

### getHideWordTrackedChanges() {#getHideWordTrackedChanges--}
```
public final boolean getHideWordTrackedChanges()
```


Sembunyikan markup dan pelacakan perubahan untuk dokumen Word.


**Returns:**
boolean
### setHideWordTrackedChanges(boolean value) {#setHideWordTrackedChanges-boolean-}
```
public final void setHideWordTrackedChanges(boolean value)
```


Sembunyikan markup dan pelacakan perubahan untuk dokumen Word.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


Sembunyikan komentar.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getBookmarkOptions() {#getBookmarkOptions--}
```
public final WordProcessingBookmarksOptions getBookmarkOptions()
```


Opsi bookmark


**Returns:**
[WordProcessingBookmarksOptions](../../com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions)
### setBookmarkOptions(WordProcessingBookmarksOptions value) {#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-}
```
public final void setBookmarkOptions(WordProcessingBookmarksOptions value)
```


Opsi bookmark


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [WordProcessingBookmarksOptions](../../com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions) |  |

### isPreserveFontFields() {#isPreserveFontFields--}
```
public boolean isPreserveFontFields()
```


Menentukan apakah akan mempertahankan bidang formulir Microsoft Word sebagai bidang formulir dalam PDF atau mengonversinya menjadi teks. Default adalah false.


**Returns:**
boolean - flag preserveFontFields

### setPreserveFontFields(boolean preserveFontFields) {#setPreserveFontFields-boolean-}
```
public void setPreserveFontFields(boolean preserveFontFields)
```


Mengatur flag preserveFontFields


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | preserveFontFields | boolean | pertahankan bidang formulir Microsoft Word sebagai bidang formulir dalam PDF atau konversi menjadi teks |
|

### isUseTextShaper() {#isUseTextShaper--}
```
public boolean isUseTextShaper()
```


Menentukan apakah akan menggunakan text shaper untuk tampilan kerning yang lebih baik. Default adalah false.


**Returns:**
boolean
### setUseTextShaper(boolean isUseTextShaper) {#setUseTextShaper-boolean-}
```
public void setUseTextShaper(boolean isUseTextShaper)
```


Menentukan apakah akan menggunakan text shaper untuk tampilan kerning yang lebih baik. Default adalah false.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | isUseTextShaper | boolean | bendera isUseTextShaper |
|

### isPreserveDocumentStructure() {#isPreserveDocumentStructure--}
```
public boolean isPreserveDocumentStructure()
```


Menentukan apakah struktur dokumen harus dipertahankan saat mengonversi ke PDF (default adalah false). Perhatikan bahwa mengekspor struktur dokumen secara signifikan meningkatkan konsumsi memori, terutama untuk dokumen besar.


**Returns:**
boolean
### setPreserveDocumentStructure(boolean preserveDocumentStructure) {#setPreserveDocumentStructure-boolean-}
```
public void setPreserveDocumentStructure(boolean preserveDocumentStructure)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| preserveDocumentStructure | boolean |  |

### getSkipExternalResources() {#getSkipExternalResources--}
```
public boolean getSkipExternalResources()
```


Jika true semua sumber eksternal tidak akan dimuat kecuali sumber daya di dalam


**Returns:**
boolean
### setSkipExternalResources(boolean skip) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skip)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lewati | boolean |  |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


Sumber daya eksternal yang akan selalu dimuat


**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whiteList) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whiteList)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| whiteList | java.util.List<java.lang.String> |  |

### getCommentDisplayMode() {#getCommentDisplayMode--}
```
public WordProcessingCommentDisplay getCommentDisplayMode()
```


Menentukan bagaimana komentar harus ditampilkan dalam dokumen output. Default adalah ShowInBalloons.


**Returns:**
[WordProcessingCommentDisplay](../../com.groupdocs.conversion.options.load/wordprocessingcommentdisplay)
### setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode) {#setCommentDisplayMode-com.groupdocs.conversion.options.load.WordProcessingCommentDisplay-}
```
public void setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| commentDisplayMode | [WordProcessingCommentDisplay](../../com.groupdocs.conversion.options.load/wordprocessingcommentdisplay) |  |

### getShowFullCommenterName() {#getShowFullCommenterName--}
```
public boolean getShowFullCommenterName()
```


Tampilkan nama lengkap pemberi komentar dalam komentar. Default adalah false.


**Returns:**
boolean
### setShowFullCommenterName(boolean showFullCommenterName) {#setShowFullCommenterName-boolean-}
```
public void setShowFullCommenterName(boolean showFullCommenterName)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| showFullCommenterName | boolean |  |

### isPageNumbering() {#isPageNumbering--}
```
public boolean isPageNumbering()
```


Aktifkan atau nonaktifkan pembuatan penomoran halaman dalam dokumen yang dikonversi. Default: false


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

### getHyphenationOptions() {#getHyphenationOptions--}
```
public HyphenationOptions getHyphenationOptions()
```


Mendapatkan opsi hyphenation untuk dokumen WordProcessing.


**Returns:**
[HyphenationOptions](../../com.groupdocs.conversion.options.load/hyphenationoptions)
### setHyphenationOptions(HyphenationOptions hyphenationOptions) {#setHyphenationOptions-com.groupdocs.conversion.options.load.HyphenationOptions-}
```
public void setHyphenationOptions(HyphenationOptions hyphenationOptions)
```


Mengatur opsi hyphenation untuk dokumen WordProcessing.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hyphenationOptions | [HyphenationOptions](../../com.groupdocs.conversion.options.load/hyphenationoptions) |  |

### isInterruptThreadIfImageExceptionThrown() {#isInterruptThreadIfImageExceptionThrown--}
```
public boolean isInterruptThreadIfImageExceptionThrown()
```


Mendapatkan flag InterruptThreadIfImageExceptionThrown Default: false Jika true maka menghentikan thread konversi utama jika terjadi pengecualian pada thread pemrosesan gambar.


**Returns:**
boolean
### setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown) {#setInterruptThreadIfImageExceptionThrown-boolean-}
```
public void setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown)
```


Mengatur flag InterruptThreadIfImageExceptionThrown


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| interruptThreadIfImageExceptionThrown | boolean |  |

### isAutoDetectRtlDirection() {#isAutoDetectRtlDirection--}
```
public boolean isAutoDetectRtlDirection()
```


Ketika diaktifkan (default), paragraf dan run yang teksnya dominan kanan-ke-kiri (RTL) akan memiliki flag bidi diperbaiki sebelum konversi.


Ini cocok dengan heuristik yang diterapkan oleh Microsoft Word dan LibreOffice dan
memperbaiki rendering dokumen Arab/Ibrani yang dihasilkan oleh pembuat
(khususnya Google Docs) yang menghasilkan OOXML tanpa


dan dengan

pada run yang hanya berisi skrip RTL.


Atur ke
false
untuk mempertahankan interpretasi OOXML yang ketat dari
markup sumber.


**Returns:**
boolean
### setAutoDetectRtlDirection(boolean autoDetectRtlDirection) {#setAutoDetectRtlDirection-boolean-}
```
public void setAutoDetectRtlDirection(boolean autoDetectRtlDirection)
```


Mengatur autoDetectRtlDirection


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | autoDetectRtlDirection | boolean | autoDetectRtlDirection |
|

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

