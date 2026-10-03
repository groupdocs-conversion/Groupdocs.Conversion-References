---
title: "PdfConvertOptions"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Opties voor conversie naar Pdf-bestandstype."
type: docs
weight: 25
url: /nl/java/com.groupdocs.conversion.options.convert/pdfconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IPageMarginConvertOptions](../../com.groupdocs.conversion.options.convert/ipagemarginconvertoptions), [com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions)
```
public class PdfConvertOptions extends CommonConvertOptions<PdfFileType> implements Serializable, IPageMarginConvertOptions, IPageSizeConvertOptions, IPageOrientationConvertOptions
```

Opties voor conversie naar Pdf-bestandstype.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [PdfConvertOptions()](#PdfConvertOptions--) | Initialiseert een nieuw exemplaar van de klasse [PdfConvertOptions](../../com.groupdocs.conversion.options.convert/pdfconvertoptions). |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getDpi()](#getDpi--) | Gewenste pagina-DPI na conversie. |
|
|  | [setDpi(int value)](#setDpi-int-) | Gewenste pagina-DPI na conversie. |
|
|  | [getPassword()](#getPassword--) | Stel deze eigenschap in als u het geconverteerde document met een wachtwoord wilt beveiligen. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Stel deze eigenschap in als u het geconverteerde document met een wachtwoord wilt beveiligen. |
|
|  | [getMarginTop()](#getMarginTop--) | Gewenste bovenmarge van de pagina in punten na conversie. |
|
|  | [setMarginTop(float value)](#setMarginTop-float-) | Gewenste bovenmarge van de pagina in punten na conversie. |
|
|  | [getMarginBottom()](#getMarginBottom--) | Gewenste ondermarge van de pagina in punten na conversie. |
|
|  | [setMarginBottom(float value)](#setMarginBottom-float-) | Gewenste ondermarge van de pagina in punten na conversie. |
|
|  | [getMarginLeft()](#getMarginLeft--) | Gewenste linkermarge van de pagina in punten na conversie. |
|
|  | [setMarginLeft(float value)](#setMarginLeft-float-) | Gewenste linkermarge van de pagina in punten na conversie. |
|
|  | [getMarginRight()](#getMarginRight--) | Gewenste rechter paginamarge in punten na conversie. |
|
|  | [setMarginRight(float value)](#setMarginRight-float-) | Gewenste rechter paginamarge in punten na conversie. |
|
|  | [getPdfOptions()](#getPdfOptions--) | Pdf-specifieke conversie-opties |
|
|  | [setPdfOptions(PdfOptions value)](#setPdfOptions-com.groupdocs.conversion.options.convert.PdfOptions-) | Pdf-specifieke conversie-opties |
|
|  | [getRotate()](#getRotate--) | Paginarotatie |
|
|  | [setRotate(Rotation value)](#setRotate-com.groupdocs.conversion.options.convert.Rotation-) | Paginarotatie |
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


Initialiseert een nieuw exemplaar van de klasse [PdfConvertOptions](../../com.groupdocs.conversion.options.convert/pdfconvertoptions).


### getDpi() {#getDpi--}
```
public final int getDpi()
```


Gewenste DPI van de pagina na conversie. De standaardresolutie is: 96 dpi.


**Returns:**
int
### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```


Gewenste DPI van de pagina na conversie. De standaardresolutie is: 96 dpi.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Stel deze eigenschap in als u het geconverteerde document met een wachtwoord wilt beveiligen.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Stel deze eigenschap in als u het geconverteerde document met een wachtwoord wilt beveiligen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getMarginTop() {#getMarginTop--}
```
public final float getMarginTop()
```


Gewenste bovenmarge van de pagina in punten na conversie.


**Returns:**
float
### setMarginTop(float value) {#setMarginTop-float-}
```
public final void setMarginTop(float value)
```


Gewenste bovenmarge van de pagina in punten na conversie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### getMarginBottom() {#getMarginBottom--}
```
public final float getMarginBottom()
```


Gewenste ondermarge van de pagina in punten na conversie.


**Returns:**
float
### setMarginBottom(float value) {#setMarginBottom-float-}
```
public final void setMarginBottom(float value)
```


Gewenste ondermarge van de pagina in punten na conversie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```


Gewenste linkermarge van de pagina in punten na conversie.


**Returns:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```


Gewenste linkermarge van de pagina in punten na conversie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```


Gewenste rechter paginamarge in punten na conversie.


**Returns:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```


Gewenste rechter paginamarge in punten na conversie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


Pdf-specifieke conversie-opties


**Returns:**
[PdfOptions](../../com.groupdocs.conversion.options.convert/pdfoptions)
### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.conversion.options.convert.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


Pdf-specifieke conversie-opties


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PdfOptions](../../com.groupdocs.conversion.options.convert/pdfoptions) |  |

### getRotate() {#getRotate--}
```
public final Rotation getRotate()
```


Paginarotatie


**Returns:**
[Rotation](../../com.groupdocs.conversion.options.convert/rotation)
### setRotate(Rotation value) {#setRotate-com.groupdocs.conversion.options.convert.Rotation-}
```
public final void setRotate(Rotation value)
```


Paginarotatie


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Rotation](../../com.groupdocs.conversion.options.convert/rotation) |  |

### getPageOrientation() {#getPageOrientation--}
```
public PageOrientation getPageOrientation()
```


Haalt paginaoriëntatie op na conversie


**Returns:**
[PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation)
### setPageOrientation(PageOrientation pageOrientation) {#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-}
```
public void setPageOrientation(PageOrientation pageOrientation)
```


Stelt gewenste paginaoriëntatie in na conversie


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pageOrientation | [PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation) |  |

### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


Haalt gewenste paginagrootte op na conversie


**Returns:**
[PageSize](../../com.groupdocs.conversion.options.convert/pagesize)
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.conversion.options.convert.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


Stel gewenste paginagrootte in na conversie


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


Gespecificeerde paginabreedte in punten als deze is ingesteld op PageSize.Custom


**Returns:**
float
### setPageWidth(float pageWidth) {#setPageWidth-float-}
```
public void setPageWidth(float pageWidth)
```


Stel gewenste paginabreedte in


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pageWidth | float |  |

### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


Gespecificeerde paginahoogte in punten als deze is ingesteld op PageSize.Custom


**Returns:**
float
### setPageHeight(float pageHeight) {#setPageHeight-float-}
```
public void setPageHeight(float pageHeight)
```


Stel gewenste paginahoogte in


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pageHeight | float |  |

