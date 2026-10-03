---
title: "PdfConvertOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Opsi untuk konversi ke tipe file Pdf."
type: docs
weight: 25
url: /id/java/com.groupdocs.conversion.options.convert/pdfconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IPageMarginConvertOptions](../../com.groupdocs.conversion.options.convert/ipagemarginconvertoptions), [com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions)
```
public class PdfConvertOptions extends CommonConvertOptions<PdfFileType> implements Serializable, IPageMarginConvertOptions, IPageSizeConvertOptions, IPageOrientationConvertOptions
```

Opsi untuk konversi ke tipe file Pdf.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [PdfConvertOptions()](#PdfConvertOptions--) | Menginisialisasi instance baru dari kelas [PdfConvertOptions](../../com.groupdocs.conversion.options.convert/pdfconvertoptions). |
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
|  | [getPdfOptions()](#getPdfOptions--) | Opsi konversi khusus Pdf |
|
|  | [setPdfOptions(PdfOptions value)](#setPdfOptions-com.groupdocs.conversion.options.convert.PdfOptions-) | Opsi konversi khusus Pdf |
|
|  | [getRotate()](#getRotate--) | Rotasi halaman |
|
|  | [setRotate(Rotation value)](#setRotate-com.groupdocs.conversion.options.convert.Rotation-) | Rotasi halaman |
|
| [getPageOrientation()](#getPageOrientation--) |  |
| [setPageOrientation(PageOrientation pageOrientation)](#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-) |  |
| [getPageSize()](#getPageSize--) |  |
| [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) |  |
| [getPageWidth()](#getPageWidth--) |  |
| [setPageWidth(float pageWidth)](#setPageWidth-float-) |  |
| [getPageHeight()](#getPageHeight--) |  |
| [setPageHeight(float pageHeight)](#setPageHeight-float-) |  |
### PdfConvertOptions() {#PdfConvertOptions--}
```
public PdfConvertOptions()
```


Menginisialisasi instance baru dari kelas [PdfConvertOptions](../../com.groupdocs.conversion.options.convert/pdfconvertoptions).


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

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


Opsi konversi khusus Pdf


**Returns:**
[PdfOptions](../../com.groupdocs.conversion.options.convert/pdfoptions)
### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.conversion.options.convert.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


Opsi konversi khusus Pdf


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PdfOptions](../../com.groupdocs.conversion.options.convert/pdfoptions) |  |

### getRotate() {#getRotate--}
```
public final Rotation getRotate()
```


Rotasi halaman


**Returns:**
[Rotation](../../com.groupdocs.conversion.options.convert/rotation)
### setRotate(Rotation value) {#setRotate-com.groupdocs.conversion.options.convert.Rotation-}
```
public final void setRotate(Rotation value)
```


Rotasi halaman


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Rotation](../../com.groupdocs.conversion.options.convert/rotation) |  |

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

