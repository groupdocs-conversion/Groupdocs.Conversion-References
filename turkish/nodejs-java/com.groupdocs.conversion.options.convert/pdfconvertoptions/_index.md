---
title: "PdfConvertOptions"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Pdf dosya türüne dönüştürme seçenekleri."
type: docs
weight: 25
url: /tr/nodejs-java/com.groupdocs.conversion.options.convert/pdfconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IPageMarginConvertOptions](../../com.groupdocs.conversion.options.convert/ipagemarginconvertoptions), [com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions)
```
public class PdfConvertOptions extends CommonConvertOptions<PdfFileType> implements Serializable, IPageMarginConvertOptions, IPageSizeConvertOptions, IPageOrientationConvertOptions
```

Pdf dosya türüne dönüştürme seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfConvertOptions()](#PdfConvertOptions--) | Yeni bir [PdfConvertOptions](../../com.groupdocs.conversion.options.convert/pdfconvertoptions) sınıfının örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDpi()](#getDpi--) | Dönüştürmeden sonraki istenen sayfa DPI'sı. |
| [setDpi(int value)](#setDpi-int-) | Dönüştürmeden sonraki istenen sayfa DPI'sı. |
| [getPassword()](#getPassword--) | Bu özelliği, dönüştürülen belgeyi bir şifreyle korumak istiyorsanız ayarlayın. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Bu özelliği, dönüştürülen belgeyi bir şifreyle korumak istiyorsanız ayarlayın. |
| [getMarginTop()](#getMarginTop--) | Dönüştürmeden sonraki istenen sayfa üst kenar boşluğu (piksel). |
| [setMarginTop(int value)](#setMarginTop-int-) | Dönüştürmeden sonraki istenen sayfa üst kenar boşluğu (piksel). |
| [getMarginBottom()](#getMarginBottom--) | Dönüştürmeden sonraki istenen sayfa alt kenar boşluğu (piksel). |
| [setMarginBottom(int value)](#setMarginBottom-int-) | Dönüştürmeden sonraki istenen sayfa alt kenar boşluğu (piksel). |
| [getMarginLeft()](#getMarginLeft--) | Dönüştürmeden sonraki istenen sayfa sol kenar boşluğu (piksel). |
| [setMarginLeft(int value)](#setMarginLeft-int-) | Dönüştürmeden sonraki istenen sayfa sol kenar boşluğu (piksel). |
| [getMarginRight()](#getMarginRight--) | Dönüştürmeden sonraki istenen sayfa sağ kenar boşluğu (piksel). |
| [setMarginRight(int value)](#setMarginRight-int-) | Dönüştürmeden sonraki istenen sayfa sağ kenar boşluğu (piksel). |
| [getPdfOptions()](#getPdfOptions--) | Pdf'ye özgü dönüştürme seçenekleri |
| [setPdfOptions(PdfOptions value)](#setPdfOptions-com.groupdocs.conversion.options.convert.PdfOptions-) | Pdf'ye özgü dönüştürme seçenekleri |
| [getRotate()](#getRotate--) | Sayfa döndürme |
| [setRotate(Rotation value)](#setRotate-com.groupdocs.conversion.options.convert.Rotation-) | Sayfa döndürme |
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


Yeni bir [PdfConvertOptions](../../com.groupdocs.conversion.options.convert/pdfconvertoptions) sınıfının örneğini başlatır.

### getDpi() {#getDpi--}
```
public final int getDpi()
```


Dönüştürmeden sonraki istenen sayfa DPI'sı. Varsayılan çözünürlük: 96 dpi.

**Returns:**
int
### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```


Dönüştürmeden sonraki istenen sayfa DPI'sı. Varsayılan çözünürlük: 96 dpi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Bu özelliği, dönüştürülen belgeyi bir şifreyle korumak istiyorsanız ayarlayın.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Bu özelliği, dönüştürülen belgeyi bir şifreyle korumak istiyorsanız ayarlayın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getMarginTop() {#getMarginTop--}
```
public final int getMarginTop()
```


Dönüştürmeden sonraki istenen sayfa üst kenar boşluğu (piksel).

**Returns:**
int
### setMarginTop(int value) {#setMarginTop-int-}
```
public final void setMarginTop(int value)
```


Dönüştürmeden sonraki istenen sayfa üst kenar boşluğu (piksel).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getMarginBottom() {#getMarginBottom--}
```
public final int getMarginBottom()
```


Dönüştürmeden sonraki istenen sayfa alt kenar boşluğu (piksel).

**Returns:**
int
### setMarginBottom(int value) {#setMarginBottom-int-}
```
public final void setMarginBottom(int value)
```


Dönüştürmeden sonraki istenen sayfa alt kenar boşluğu (piksel).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getMarginLeft() {#getMarginLeft--}
```
public final int getMarginLeft()
```


Dönüştürmeden sonraki istenen sayfa sol kenar boşluğu (piksel).

**Returns:**
int
### setMarginLeft(int value) {#setMarginLeft-int-}
```
public final void setMarginLeft(int value)
```


Dönüştürmeden sonraki istenen sayfa sol kenar boşluğu (piksel).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getMarginRight() {#getMarginRight--}
```
public final int getMarginRight()
```


Dönüştürmeden sonraki istenen sayfa sağ kenar boşluğu (piksel).

**Returns:**
int
### setMarginRight(int value) {#setMarginRight-int-}
```
public final void setMarginRight(int value)
```


Dönüştürmeden sonraki istenen sayfa sağ kenar boşluğu (piksel).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


Pdf'ye özgü dönüştürme seçenekleri

**Returns:**
[PdfOptions](../../com.groupdocs.conversion.options.convert/pdfoptions)
### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.conversion.options.convert.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


Pdf'ye özgü dönüştürme seçenekleri

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PdfOptions](../../com.groupdocs.conversion.options.convert/pdfoptions) |  |

### getRotate() {#getRotate--}
```
public final Rotation getRotate()
```


Sayfa döndürme

**Returns:**
[Rotation](../../com.groupdocs.conversion.options.convert/rotation)
### setRotate(Rotation value) {#setRotate-com.groupdocs.conversion.options.convert.Rotation-}
```
public final void setRotate(Rotation value)
```


Sayfa döndürme

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rotation](../../com.groupdocs.conversion.options.convert/rotation) |  |

### getPageOrientation() {#getPageOrientation--}
```
public PageOrientation getPageOrientation()
```


Dönüştürmeden sonraki sayfa yönelimini alır

**Returns:**
[PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation)
### setPageOrientation(PageOrientation pageOrientation) {#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-}
```
public void setPageOrientation(PageOrientation pageOrientation)
```


Dönüştürmeden sonraki istenen sayfa yönelimini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageOrientation | [PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation) |  |

### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


Dönüştürmeden sonraki istenen sayfa boyutunu alır

**Returns:**
[PageSize](../../com.groupdocs.conversion.options.convert/pagesize)
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.conversion.options.convert.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


Dönüştürmeden sonra istenen sayfa boyutunu ayarla

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


Sayfa genişliği, eğer  PageSize.Custom olarak ayarlanmışsa nokta cinsinden belirtilir

**Returns:**
float
### setPageWidth(float pageWidth) {#setPageWidth-float-}
```
public void setPageWidth(float pageWidth)
```


İstenen sayfa genişliğini ayarla

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageWidth | float |  |

### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


Sayfa yüksekliği, eğer  PageSize.Custom olarak ayarlanmışsa nokta cinsinden belirtilir

**Returns:**
float
### setPageHeight(float pageHeight) {#setPageHeight-float-}
```
public void setPageHeight(float pageHeight)
```


İstenen sayfa yüksekliğini ayarla

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageHeight | float |  |

