---
title: "WordProcessingConvertOptions"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "WordProcessing dosya türüne dönüştürme seçenekleri."
type: docs
weight: 48
url: /tr/nodejs-java/com.groupdocs.conversion.options.convert/wordprocessingconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IPageMarginConvertOptions](../../com.groupdocs.conversion.options.convert/ipagemarginconvertoptions), [com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions), [com.groupdocs.conversion.options.convert.IPdfRecognitionModeOptions](../../com.groupdocs.conversion.options.convert/ipdfrecognitionmodeoptions)
```
public class WordProcessingConvertOptions extends CommonConvertOptions<WordProcessingFileType> implements Serializable, IPageMarginConvertOptions, IPageSizeConvertOptions, IPageOrientationConvertOptions, IPdfRecognitionModeOptions
```

WordProcessing dosya türüne dönüştürme seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WordProcessingConvertOptions()](#WordProcessingConvertOptions--) | Yeni bir [WordProcessingConvertOptions](../../com.groupdocs.conversion.options.convert/wordprocessingconvertoptions) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDpi()](#getDpi--) | Dönüştürmeden sonraki istenen sayfa DPI'sı. |
| [setDpi(int value)](#setDpi-int-) | Dönüştürmeden sonraki istenen sayfa DPI'sı. |
| [getPassword()](#getPassword--) | Bu özelliği, dönüştürülen belgeyi bir şifreyle korumak istiyorsanız ayarlayın. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Bu özelliği, dönüştürülen belgeyi bir şifreyle korumak istiyorsanız ayarlayın. |
| [getRtfOptions()](#getRtfOptions--) | RTF'ye özgü dönüştürme seçenekleri |
| [setRtfOptions(RtfOptions value)](#setRtfOptions-com.groupdocs.conversion.options.convert.RtfOptions-) | RTF'ye özgü dönüştürme seçenekleri |
| [getZoom()](#getZoom--) | Yakınlaştırma seviyesini yüzde olarak belirtir. |
| [setZoom(int value)](#setZoom-int-) | Yakınlaştırma seviyesini yüzde olarak belirtir. |
| [getMarginTop()](#getMarginTop--) | Dönüştürmeden sonraki istenen sayfa üst kenar boşluğu (piksel). |
| [setMarginTop(int value)](#setMarginTop-int-) | Dönüştürmeden sonraki istenen sayfa üst kenar boşluğu (piksel). |
| [getMarginBottom()](#getMarginBottom--) | Dönüştürmeden sonraki istenen sayfa alt kenar boşluğu (piksel). |
| [setMarginBottom(int value)](#setMarginBottom-int-) | Dönüştürmeden sonraki istenen sayfa alt kenar boşluğu (piksel). |
| [getMarginLeft()](#getMarginLeft--) | Dönüştürmeden sonraki istenen sayfa sol kenar boşluğu (piksel). |
| [setMarginLeft(int value)](#setMarginLeft-int-) | Dönüştürmeden sonraki istenen sayfa sol kenar boşluğu (piksel). |
| [getMarginRight()](#getMarginRight--) | Dönüştürmeden sonraki istenen sayfa sağ kenar boşluğu (piksel). |
| [setMarginRight(int value)](#setMarginRight-int-) | Dönüştürmeden sonraki istenen sayfa sağ kenar boşluğu (piksel). |
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
### WordProcessingConvertOptions() {#WordProcessingConvertOptions--}
```
public WordProcessingConvertOptions()
```


Yeni bir [WordProcessingConvertOptions](../../com.groupdocs.conversion.options.convert/wordprocessingconvertoptions) sınıfı örneği başlatır.

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

### getRtfOptions() {#getRtfOptions--}
```
public final RtfOptions getRtfOptions()
```


RTF'ye özgü dönüştürme seçenekleri

**Returns:**
[RtfOptions](../../com.groupdocs.conversion.options.convert/rtfoptions)
### setRtfOptions(RtfOptions value) {#setRtfOptions-com.groupdocs.conversion.options.convert.RtfOptions-}
```
public final void setRtfOptions(RtfOptions value)
```


RTF'ye özgü dönüştürme seçenekleri

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RtfOptions](../../com.groupdocs.conversion.options.convert/rtfoptions) |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Yakınlaştırma seviyesini yüzde olarak belirtir. Varsayılan değer 100'dür. Varsayılan yakınlaştırma Microsoft Word 2010'a kadar desteklenir. Microsoft Word 2013'ten itibaren varsayılan yakınlaştırma belgeye artık ayarlanmamaktadır; bunun yerine açılan son belgenin yakınlaştırma faktörü kullanılıyor gibi görünür.

**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Yakınlaştırma seviyesini yüzde olarak belirtir. Varsayılan değer 100'dür. Varsayılan yakınlaştırma Microsoft Word 2010'a kadar desteklenir. Microsoft Word 2013'ten itibaren varsayılan yakınlaştırma belgeye artık ayarlanmamaktadır; bunun yerine açılan son belgenin yakınlaştırma faktörü kullanılıyor gibi görünür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

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

### getPdfRecognitionMode() {#getPdfRecognitionMode--}
```
public PdfRecognitionMode getPdfRecognitionMode()
```


PDF'den dönüştürürken tanıma modunu alır

**Returns:**
[PdfRecognitionMode](../../com.groupdocs.conversion.options.convert/pdfrecognitionmode)
### setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode) {#setPdfRecognitionMode-com.groupdocs.conversion.options.convert.PdfRecognitionMode-}
```
public void setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode)
```


PDF'den dönüştürürken tanıma modunu ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pdfRecognitionMode | [PdfRecognitionMode](../../com.groupdocs.conversion.options.convert/pdfrecognitionmode) |  |

