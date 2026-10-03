---
title: "WordProcessingConvertOptions"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "WordProcessing dosya türüne dönüştürme seçenekleri."
type: docs
weight: 48
url: /tr/java/com.groupdocs.conversion.options.convert/wordprocessingconvertoptions/
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
|  | [WordProcessingConvertOptions()](#WordProcessingConvertOptions--) | Yeni bir [WordProcessingConvertOptions](../../com.groupdocs.conversion.options.convert/wordprocessingconvertoptions) sınıfı örneği başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getDpi()](#getDpi--) | Dönüştürme sonrası istenen sayfa DPI'sı. |
|
|  | [setDpi(int value)](#setDpi-int-) | Dönüştürme sonrası istenen sayfa DPI'sı. |
|
|  | [getPassword()](#getPassword--) | Dönüştürülen belgeyi bir şifre ile korumak istiyorsanız bu özelliği ayarlayın. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Dönüştürülen belgeyi bir şifre ile korumak istiyorsanız bu özelliği ayarlayın. |
|
|  | [getRtfOptions()](#getRtfOptions--) | RTF'ye özgü dönüştürme seçenekleri |
|
|  | [setRtfOptions(RtfOptions value)](#setRtfOptions-com.groupdocs.conversion.options.convert.RtfOptions-) | RTF'ye özgü dönüştürme seçenekleri |
|
|  | [getZoom()](#getZoom--) | Yakınlaştırma seviyesini yüzde olarak belirtir. |
|
|  | [setZoom(int value)](#setZoom-int-) | Yakınlaştırma seviyesini yüzde olarak belirtir. |
|
|  | [getMarginTop()](#getMarginTop--) | Dönüştürme sonrası istenen sayfa üst kenar boşluğu (puan olarak). |
|
|  | [setMarginTop(float value)](#setMarginTop-float-) | Dönüştürme sonrası istenen sayfa üst kenar boşluğu (puan olarak). |
|
|  | [getMarginBottom()](#getMarginBottom--) | Dönüştürme sonrası istenen sayfa alt kenar boşluğu (puan olarak). |
|
|  | [setMarginBottom(float value)](#setMarginBottom-float-) | Dönüştürme sonrası istenen sayfa alt kenar boşluğu (puan olarak). |
|
|  | [getMarginLeft()](#getMarginLeft--) | Dönüştürme sonrası istenen sayfa sol kenar boşluğu (puan olarak). |
|
|  | [setMarginLeft(float value)](#setMarginLeft-float-) | Dönüştürme sonrası istenen sayfa sol kenar boşluğu (puan olarak). |
|
|  | [getMarginRight()](#getMarginRight--) | Dönüştürmeden sonra istenen sayfa sağ kenar boşluğu puan cinsinden. |
|
|  | [setMarginRight(float value)](#setMarginRight-float-) | Dönüştürmeden sonra istenen sayfa sağ kenar boşluğu puan cinsinden. |
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
|  | [getMarkdownOptions()](#getMarkdownOptions--) | Alır |
|
|  | [setMarkdownOptions(MarkdownOptions markdownOptions)](#setMarkdownOptions-com.groupdocs.conversion.options.convert.MarkdownOptions-) | Ayarlar |
|
### WordProcessingConvertOptions() {#WordProcessingConvertOptions--}
```
public WordProcessingConvertOptions()
```


Yeni bir [WordProcessingConvertOptions](../../com.groupdocs.conversion.options.convert/wordprocessingconvertoptions) sınıfı örneği başlatır.


### getDpi() {#getDpi--}
```
public final int getDpi()
```


Dönüştürmeden sonra istenen sayfa DPI'sı. Varsayılan çözünürlük: 96 dpi.


**Returns:**
int
### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```


Dönüştürmeden sonra istenen sayfa DPI'sı. Varsayılan çözünürlük: 96 dpi.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Dönüştürülen belgeyi bir şifre ile korumak istiyorsanız bu özelliği ayarlayın.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Dönüştürülen belgeyi bir şifre ile korumak istiyorsanız bu özelliği ayarlayın.


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


Yakınlaştırma seviyesini yüzde olarak belirtir. Varsayılan değer 100.
Varsayılan yakınlaştırma Microsoft Word 2010'a kadar desteklenir. Microsoft Word 2013'ten itibaren varsayılan yakınlaştırma belgeye daha fazla ayarlanmıyor, bunun yerine açılan son belgenin yakınlaştırma faktörünü kullandığı görülüyor.


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Yakınlaştırma seviyesini yüzde olarak belirtir. Varsayılan değer 100.
Varsayılan yakınlaştırma Microsoft Word 2010'a kadar desteklenir. Microsoft Word 2013'ten itibaren varsayılan yakınlaştırma belgeye daha fazla ayarlanmıyor, bunun yerine açılan son belgenin yakınlaştırma faktörünü kullandığı görülüyor.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getMarginTop() {#getMarginTop--}
```
public final float getMarginTop()
```


Dönüştürme sonrası istenen sayfa üst kenar boşluğu (puan olarak).


**Returns:**
float
### setMarginTop(float value) {#setMarginTop-float-}
```
public final void setMarginTop(float value)
```


Dönüştürme sonrası istenen sayfa üst kenar boşluğu (puan olarak).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getMarginBottom() {#getMarginBottom--}
```
public final float getMarginBottom()
```


Dönüştürme sonrası istenen sayfa alt kenar boşluğu (puan olarak).


**Returns:**
float
### setMarginBottom(float value) {#setMarginBottom-float-}
```
public final void setMarginBottom(float value)
```


Dönüştürme sonrası istenen sayfa alt kenar boşluğu (puan olarak).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```


Dönüştürme sonrası istenen sayfa sol kenar boşluğu (puan olarak).


**Returns:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```


Dönüştürme sonrası istenen sayfa sol kenar boşluğu (puan olarak).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```


Dönüştürmeden sonra istenen sayfa sağ kenar boşluğu puan cinsinden.


**Returns:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```


Dönüştürmeden sonra istenen sayfa sağ kenar boşluğu puan cinsinden.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getPageOrientation() {#getPageOrientation--}
```
public PageOrientation getPageOrientation()
```


Dönüştürmeden sonra sayfa yönelimini alır


**Returns:**
[PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation)
### setPageOrientation(PageOrientation pageOrientation) {#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-}
```
public void setPageOrientation(PageOrientation pageOrientation)
```


Dönüştürmeden sonra istenen sayfa yönelimini ayarlar


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageOrientation | [PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation) |  |

### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


Dönüştürmeden sonra istenen sayfa boyutunu alır


**Returns:**
[PageSize](../../com.groupdocs.conversion.options.convert/pagesize)
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.conversion.options.convert.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


Dönüştürmeden sonra istenen sayfa boyutunu ayarlar


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


PageSize.Custom olarak ayarlanmışsa belirtilen sayfa genişliği puan cinsinden


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


PageSize.Custom olarak ayarlanmışsa belirtilen sayfa yüksekliği puan cinsinden


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

### getMarkdownOptions() {#getMarkdownOptions--}
```
public MarkdownOptions getMarkdownOptions()
```


Alır


**Returns:**
[MarkdownOptions](../../com.groupdocs.conversion.options.convert/markdownoptions)
### setMarkdownOptions(MarkdownOptions markdownOptions) {#setMarkdownOptions-com.groupdocs.conversion.options.convert.MarkdownOptions-}
```
public void setMarkdownOptions(MarkdownOptions markdownOptions)
```


Ayarlar


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| markdownOptions | [MarkdownOptions](../../com.groupdocs.conversion.options.convert/markdownoptions) |  |

