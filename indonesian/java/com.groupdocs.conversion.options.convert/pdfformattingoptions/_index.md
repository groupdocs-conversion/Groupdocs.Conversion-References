---
title: "PdfFormattingOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Mendefinisikan opsi pemformatan Pdf."
type: docs
weight: 28
url: /id/java/com.groupdocs.conversion.options.convert/pdfformattingoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfFormattingOptions extends ValueObject implements Serializable
```

Mendefinisikan opsi pemformatan Pdf.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfFormattingOptions()](#PdfFormattingOptions--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getCenterWindow()](#getCenterWindow--) | Menentukan apakah posisi jendela dokumen akan dipusatkan di layar. |
|
|  | [setCenterWindow(boolean value)](#setCenterWindow-boolean-) | Menentukan apakah posisi jendela dokumen akan dipusatkan di layar. |
|
|  | [getDirection()](#getDirection--) | Mengatur urutan baca teks: L2R (kiri ke kanan) atau R2L (kanan ke kiri). |
|
|  | [setDirection(PdfDirection value)](#setDirection-com.groupdocs.conversion.options.convert.PdfDirection-) | Mengatur urutan baca teks: L2R (kiri ke kanan) atau R2L (kanan ke kiri). |
|
|  | [getDisplayDocTitle()](#getDisplayDocTitle--) | Menentukan apakah bilah judul jendela dokumen harus menampilkan judul dokumen. |
|
|  | [setDisplayDocTitle(boolean value)](#setDisplayDocTitle-boolean-) | Menentukan apakah bilah judul jendela dokumen harus menampilkan judul dokumen. |
|
|  | [getFitWindow()](#getFitWindow--) | Menentukan apakah jendela dokumen harus diubah ukurannya agar sesuai dengan halaman pertama yang ditampilkan. |
|
|  | [setFitWindow(boolean value)](#setFitWindow-boolean-) | Menentukan apakah jendela dokumen harus diubah ukurannya agar sesuai dengan halaman pertama yang ditampilkan. |
|
|  | [getHideMenuBar()](#getHideMenuBar--) | Menentukan apakah bilah menu harus disembunyikan ketika dokumen aktif. |
|
|  | [setHideMenuBar(boolean value)](#setHideMenuBar-boolean-) | Menentukan apakah bilah menu harus disembunyikan ketika dokumen aktif. |
|
|  | [getHideToolBar()](#getHideToolBar--) | Menentukan apakah bilah alat harus disembunyikan ketika dokumen aktif. |
|
|  | [setHideToolBar(boolean value)](#setHideToolBar-boolean-) | Menentukan apakah bilah alat harus disembunyikan ketika dokumen aktif. |
|
|  | [getHideWindowUI()](#getHideWindowUI--) | Menentukan apakah elemen antarmuka pengguna harus disembunyikan ketika dokumen aktif. |
|
|  | [setHideWindowUI(boolean value)](#setHideWindowUI-boolean-) | Menentukan apakah elemen antarmuka pengguna harus disembunyikan ketika dokumen aktif. |
|
|  | [getNonFullScreenPageMode()](#getNonFullScreenPageMode--) | Mengatur mode halaman, menentukan cara menampilkan dokumen saat keluar dari mode layar penuh. |
|
|  | [setNonFullScreenPageMode(PdfPageMode value)](#setNonFullScreenPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-) | Mengatur mode halaman, menentukan cara menampilkan dokumen saat keluar dari mode layar penuh. |
|
|  | [getPageLayout()](#getPageLayout--) | Mengatur tata letak halaman yang akan digunakan saat dokumen dibuka. |
|
|  | [setPageLayout(PdfPageLayout value)](#setPageLayout-com.groupdocs.conversion.options.convert.PdfPageLayout-) | Mengatur tata letak halaman yang akan digunakan saat dokumen dibuka. |
|
|  | [getPageMode()](#getPageMode--) | Mengatur mode halaman, menentukan cara dokumen ditampilkan saat dibuka. |
|
|  | [setPageMode(PdfPageMode value)](#setPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-) | Mengatur mode halaman, menentukan cara dokumen ditampilkan saat dibuka. |
|
### PdfFormattingOptions() {#PdfFormattingOptions--}
```
public PdfFormattingOptions()
```


### getCenterWindow() {#getCenterWindow--}
```
public final boolean getCenterWindow()
```


Menentukan apakah posisi jendela dokumen akan dipusatkan di layar. Default: false.


**Returns:**
boolean
### setCenterWindow(boolean value) {#setCenterWindow-boolean-}
```
public final void setCenterWindow(boolean value)
```


Menentukan apakah posisi jendela dokumen akan dipusatkan di layar. Default: false.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getDirection() {#getDirection--}
```
public final PdfDirection getDirection()
```


Mengatur urutan baca teks: L2R (kiri ke kanan) atau R2L (kanan ke kiri). Default: L2R.


**Returns:**
[PdfDirection](../../com.groupdocs.conversion.options.convert/pdfdirection)
### setDirection(PdfDirection value) {#setDirection-com.groupdocs.conversion.options.convert.PdfDirection-}
```
public final void setDirection(PdfDirection value)
```


Mengatur urutan baca teks: L2R (kiri ke kanan) atau R2L (kanan ke kiri). Default: L2R.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PdfDirection](../../com.groupdocs.conversion.options.convert/pdfdirection) |  |

### getDisplayDocTitle() {#getDisplayDocTitle--}
```
public final boolean getDisplayDocTitle()
```


Menentukan apakah bilah judul jendela dokumen harus menampilkan judul dokumen. Default: false.


**Returns:**
boolean
### setDisplayDocTitle(boolean value) {#setDisplayDocTitle-boolean-}
```
public final void setDisplayDocTitle(boolean value)
```


Menentukan apakah bilah judul jendela dokumen harus menampilkan judul dokumen. Default: false.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getFitWindow() {#getFitWindow--}
```
public final boolean getFitWindow()
```


Menentukan apakah jendela dokumen harus diubah ukurannya agar sesuai dengan halaman pertama yang ditampilkan. Default: false.


**Returns:**
boolean
### setFitWindow(boolean value) {#setFitWindow-boolean-}
```
public final void setFitWindow(boolean value)
```


Menentukan apakah jendela dokumen harus diubah ukurannya agar sesuai dengan halaman pertama yang ditampilkan. Default: false.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getHideMenuBar() {#getHideMenuBar--}
```
public final boolean getHideMenuBar()
```


Menentukan apakah bilah menu harus disembunyikan ketika dokumen aktif. Default: false.


**Returns:**
boolean
### setHideMenuBar(boolean value) {#setHideMenuBar-boolean-}
```
public final void setHideMenuBar(boolean value)
```


Menentukan apakah bilah menu harus disembunyikan ketika dokumen aktif. Default: false.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getHideToolBar() {#getHideToolBar--}
```
public final boolean getHideToolBar()
```


Menentukan apakah bilah alat harus disembunyikan ketika dokumen aktif. Default: false.


**Returns:**
boolean
### setHideToolBar(boolean value) {#setHideToolBar-boolean-}
```
public final void setHideToolBar(boolean value)
```


Menentukan apakah bilah alat harus disembunyikan ketika dokumen aktif. Default: false.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getHideWindowUI() {#getHideWindowUI--}
```
public final boolean getHideWindowUI()
```


Menentukan apakah elemen antarmuka pengguna harus disembunyikan ketika dokumen aktif. Default: false.


**Returns:**
boolean
### setHideWindowUI(boolean value) {#setHideWindowUI-boolean-}
```
public final void setHideWindowUI(boolean value)
```


Menentukan apakah elemen antarmuka pengguna harus disembunyikan ketika dokumen aktif. Default: false.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getNonFullScreenPageMode() {#getNonFullScreenPageMode--}
```
public final PdfPageMode getNonFullScreenPageMode()
```


Mengatur mode halaman, menentukan cara menampilkan dokumen saat keluar dari mode layar penuh.


**Returns:**
[PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode)
### setNonFullScreenPageMode(PdfPageMode value) {#setNonFullScreenPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-}
```
public final void setNonFullScreenPageMode(PdfPageMode value)
```


Mengatur mode halaman, menentukan cara menampilkan dokumen saat keluar dari mode layar penuh.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode) |  |

### getPageLayout() {#getPageLayout--}
```
public final PdfPageLayout getPageLayout()
```


Mengatur tata letak halaman yang akan digunakan saat dokumen dibuka.


**Returns:**
[PdfPageLayout](../../com.groupdocs.conversion.options.convert/pdfpagelayout)
### setPageLayout(PdfPageLayout value) {#setPageLayout-com.groupdocs.conversion.options.convert.PdfPageLayout-}
```
public final void setPageLayout(PdfPageLayout value)
```


Mengatur tata letak halaman yang akan digunakan saat dokumen dibuka.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PdfPageLayout](../../com.groupdocs.conversion.options.convert/pdfpagelayout) |  |

### getPageMode() {#getPageMode--}
```
public final PdfPageMode getPageMode()
```


Mengatur mode halaman, menentukan cara dokumen ditampilkan saat dibuka.


**Returns:**
[PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode)
### setPageMode(PdfPageMode value) {#setPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-}
```
public final void setPageMode(PdfPageMode value)
```


Mengatur mode halaman, menentukan cara dokumen ditampilkan saat dibuka.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode) |  |

