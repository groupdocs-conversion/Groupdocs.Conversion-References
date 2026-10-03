---
title: "WordProcessingConvertOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Opsi untuk konversi ke tipe file WordProcessing."
type: docs
weight: 48
url: /id/java/com.groupdocs.conversion.options.convert/wordprocessingconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IPageMarginConvertOptions](../../com.groupdocs.conversion.options.convert/ipagemarginconvertoptions), [com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions), [com.groupdocs.conversion.options.convert.IPdfRecognitionModeOptions](../../com.groupdocs.conversion.options.convert/ipdfrecognitionmodeoptions)
```
public class WordProcessingConvertOptions extends CommonConvertOptions<WordProcessingFileType> implements Serializable, IPageMarginConvertOptions, IPageSizeConvertOptions, IPageOrientationConvertOptions, IPdfRecognitionModeOptions
```

Opsi untuk konversi ke tipe file WordProcessing.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [WordProcessingConvertOptions()](#WordProcessingConvertOptions--) | Menginisialisasi instance baru dari kelas [WordProcessingConvertOptions](../../com.groupdocs.conversion.options.convert/wordprocessingconvertoptions). |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getDpi()](#getDpi--) | DPI halaman yang diinginkan setelah konversi. |
|
|  | [setDpi(int value)](#setDpi-int-) | DPI halaman yang diinginkan setelah konversi. |
|
|  | [getPassword()](#getPassword--) | Setel properti ini jika Anda ingin melindungi dokumen yang dikonversi dengan kata sandi. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Setel properti ini jika Anda ingin melindungi dokumen yang dikonversi dengan kata sandi. |
|
|  | [getRtfOptions()](#getRtfOptions--) | Opsi konversi khusus RTF |
|
|  | [setRtfOptions(RtfOptions value)](#setRtfOptions-com.groupdocs.conversion.options.convert.RtfOptions-) | Opsi konversi khusus RTF |
|
|  | [getZoom()](#getZoom--) | Menentukan tingkat zoom dalam persentase. |
|
|  | [setZoom(int value)](#setZoom-int-) | Menentukan tingkat zoom dalam persentase. |
|
|  | [getMarginTop()](#getMarginTop--) | Margin atas halaman yang diinginkan dalam poin setelah konversi. |
|
|  | [setMarginTop(float value)](#setMarginTop-float-) | Margin atas halaman yang diinginkan dalam poin setelah konversi. |
|
|  | [getMarginBottom()](#getMarginBottom--) | Margin bawah halaman yang diinginkan dalam poin setelah konversi. |
|
|  | [setMarginBottom(float value)](#setMarginBottom-float-) | Margin bawah halaman yang diinginkan dalam poin setelah konversi. |
|
|  | [getMarginLeft()](#getMarginLeft--) | Margin kiri halaman yang diinginkan dalam poin setelah konversi. |
|
|  | [setMarginLeft(float value)](#setMarginLeft-float-) | Margin kiri halaman yang diinginkan dalam poin setelah konversi. |
|
|  | [getMarginRight()](#getMarginRight--) | Margin kanan halaman yang diinginkan dalam poin setelah konversi. |
|
|  | [setMarginRight(float value)](#setMarginRight-float-) | Margin kanan halaman yang diinginkan dalam poin setelah konversi. |
|
| [getPageOrientation()](#getPageOrientation--) |  |
| [setPageOrientation(PageOrientation pageOrientation)](#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-) |  |
| [getPageSize()](#getPageSize--) |  |
| [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) |  |
| [getPageWidth()](#getPageWidth--) |  |
| [setPageWidth(float pageWidth)](#setPageWidth-float-) |  |
| [getPageHeight()](#getPageHeight--) |  |
| [setPageHeight(float pageHeight)](#setPageHeight-float-) |  |
| [getPdfRecognitionMode()](#getPdfRecognitionMode--) |  |
| [setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode)](#setPdfRecognitionMode-com.groupdocs.conversion.options.convert.PdfRecognitionMode-) |  |
|  | [getMarkdownOptions()](#getMarkdownOptions--) | Mendapatkan |
|
|  | [setMarkdownOptions(MarkdownOptions markdownOptions)](#setMarkdownOptions-com.groupdocs.conversion.options.convert.MarkdownOptions-) | Mengatur |
|
### WordProcessingConvertOptions() {#WordProcessingConvertOptions--}
```
public WordProcessingConvertOptions()
```


Menginisialisasi instance baru dari kelas [WordProcessingConvertOptions](../../com.groupdocs.conversion.options.convert/wordprocessingconvertoptions).


### getDpi() {#getDpi--}
```
public final int getDpi()
```


DPI halaman yang diinginkan setelah konversi. Resolusi default adalah: 96 dpi.


**Returns:**
int
### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```


DPI halaman yang diinginkan setelah konversi. Resolusi default adalah: 96 dpi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Setel properti ini jika Anda ingin melindungi dokumen yang dikonversi dengan kata sandi.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Setel properti ini jika Anda ingin melindungi dokumen yang dikonversi dengan kata sandi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getRtfOptions() {#getRtfOptions--}
```
public final RtfOptions getRtfOptions()
```


Opsi konversi khusus RTF


**Returns:**
[RtfOptions](../../com.groupdocs.conversion.options.convert/rtfoptions)
### setRtfOptions(RtfOptions value) {#setRtfOptions-com.groupdocs.conversion.options.convert.RtfOptions-}
```
public final void setRtfOptions(RtfOptions value)
```


Opsi konversi khusus RTF


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [RtfOptions](../../com.groupdocs.conversion.options.convert/rtfoptions) |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Menentukan tingkat zoom dalam persentase. Defaultnya adalah 100.
Zoom default didukung hingga Microsoft Word 2010. Mulai dari Microsoft Word 2013, zoom default tidak lagi diatur ke dokumen, melainkan tampaknya menggunakan faktor zoom dari dokumen terakhir yang dibuka.


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Menentukan tingkat zoom dalam persentase. Defaultnya adalah 100.
Zoom default didukung hingga Microsoft Word 2010. Mulai dari Microsoft Word 2013, zoom default tidak lagi diatur ke dokumen, melainkan tampaknya menggunakan faktor zoom dari dokumen terakhir yang dibuka.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getMarginTop() {#getMarginTop--}
```
public final float getMarginTop()
```


Margin atas halaman yang diinginkan dalam poin setelah konversi.


**Returns:**
float
### setMarginTop(float value) {#setMarginTop-float-}
```
public final void setMarginTop(float value)
```


Margin atas halaman yang diinginkan dalam poin setelah konversi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float |  |

### getMarginBottom() {#getMarginBottom--}
```
public final float getMarginBottom()
```


Margin bawah halaman yang diinginkan dalam poin setelah konversi.


**Returns:**
float
### setMarginBottom(float value) {#setMarginBottom-float-}
```
public final void setMarginBottom(float value)
```


Margin bawah halaman yang diinginkan dalam poin setelah konversi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```


Margin kiri halaman yang diinginkan dalam poin setelah konversi.


**Returns:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```


Margin kiri halaman yang diinginkan dalam poin setelah konversi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```


Margin kanan halaman yang diinginkan dalam poin setelah konversi.


**Returns:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```


Margin kanan halaman yang diinginkan dalam poin setelah konversi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float |  |

### getPageOrientation() {#getPageOrientation--}
```
public PageOrientation getPageOrientation()
```


Mendapatkan orientasi halaman setelah konversi


**Returns:**
[PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation)
### setPageOrientation(PageOrientation pageOrientation) {#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-}
```
public void setPageOrientation(PageOrientation pageOrientation)
```


Mengatur orientasi halaman yang diinginkan setelah konversi


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageOrientation | [PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation) |  |

### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


Mendapatkan ukuran halaman yang diinginkan setelah konversi


**Returns:**
[PageSize](../../com.groupdocs.conversion.options.convert/pagesize)
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.conversion.options.convert.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


Mengatur ukuran halaman yang diinginkan setelah konversi


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


Lebar halaman yang ditentukan dalam poin jika diatur ke PageSize.Custom


**Returns:**
float
### setPageWidth(float pageWidth) {#setPageWidth-float-}
```
public void setPageWidth(float pageWidth)
```


Mengatur lebar halaman yang diinginkan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageWidth | float |  |

### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


Tinggi halaman yang ditentukan dalam poin jika diatur ke PageSize.Custom


**Returns:**
float
### setPageHeight(float pageHeight) {#setPageHeight-float-}
```
public void setPageHeight(float pageHeight)
```


Mengatur tinggi halaman yang diinginkan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageHeight | float |  |

### getPdfRecognitionMode() {#getPdfRecognitionMode--}
```
public PdfRecognitionMode getPdfRecognitionMode()
```


Mendapatkan mode pengenalan saat mengonversi dari pdf


**Returns:**
[PdfRecognitionMode](../../com.groupdocs.conversion.options.convert/pdfrecognitionmode)
### setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode) {#setPdfRecognitionMode-com.groupdocs.conversion.options.convert.PdfRecognitionMode-}
```
public void setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode)
```


Mengatur mode pengenalan saat mengonversi dari pdf


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pdfRecognitionMode | [PdfRecognitionMode](../../com.groupdocs.conversion.options.convert/pdfrecognitionmode) |  |

### getMarkdownOptions() {#getMarkdownOptions--}
```
public MarkdownOptions getMarkdownOptions()
```


Mendapatkan


**Returns:**
[MarkdownOptions](../../com.groupdocs.conversion.options.convert/markdownoptions)
### setMarkdownOptions(MarkdownOptions markdownOptions) {#setMarkdownOptions-com.groupdocs.conversion.options.convert.MarkdownOptions-}
```
public void setMarkdownOptions(MarkdownOptions markdownOptions)
```


Mengatur


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| markdownOptions | [MarkdownOptions](../../com.groupdocs.conversion.options.convert/markdownoptions) |  |

