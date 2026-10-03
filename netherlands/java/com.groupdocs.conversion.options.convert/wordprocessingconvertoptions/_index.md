---
title: "WordProcessingConvertOptions"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Opties voor conversie naar WordProcessing‑bestandstype."
type: docs
weight: 48
url: /nl/java/com.groupdocs.conversion.options.convert/wordprocessingconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IPageMarginConvertOptions](../../com.groupdocs.conversion.options.convert/ipagemarginconvertoptions), [com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions), [com.groupdocs.conversion.options.convert.IPdfRecognitionModeOptions](../../com.groupdocs.conversion.options.convert/ipdfrecognitionmodeoptions)
```
public class WordProcessingConvertOptions extends CommonConvertOptions<WordProcessingFileType> implements Serializable, IPageMarginConvertOptions, IPageSizeConvertOptions, IPageOrientationConvertOptions, IPdfRecognitionModeOptions
```

Opties voor conversie naar WordProcessing‑bestandstype.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [WordProcessingConvertOptions()](#WordProcessingConvertOptions--) | Initialiseert een nieuw exemplaar van de klasse [WordProcessingConvertOptions](../../com.groupdocs.conversion.options.convert/wordprocessingconvertoptions). |
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
|  | [getRtfOptions()](#getRtfOptions--) | RTF-specifieke conversie-opties |
|
|  | [setRtfOptions(RtfOptions value)](#setRtfOptions-com.groupdocs.conversion.options.convert.RtfOptions-) | RTF-specifieke conversie-opties |
|
|  | [getZoom()](#getZoom--) | Specificeert het zoomniveau in procenten. |
|
|  | [setZoom(int value)](#setZoom-int-) | Specificeert het zoomniveau in procenten. |
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
|  | [getMarkdownOptions()](#getMarkdownOptions--) | Haalt op |
|
|  | [setMarkdownOptions(MarkdownOptions markdownOptions)](#setMarkdownOptions-com.groupdocs.conversion.options.convert.MarkdownOptions-) | Stelt in |
|
### WordProcessingConvertOptions() {#WordProcessingConvertOptions--}
```
public WordProcessingConvertOptions()
```


Initialiseert een nieuw exemplaar van de klasse [WordProcessingConvertOptions](../../com.groupdocs.conversion.options.convert/wordprocessingconvertoptions).


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

### getRtfOptions() {#getRtfOptions--}
```
public final RtfOptions getRtfOptions()
```


RTF-specifieke conversie-opties


**Returns:**
[RtfOptions](../../com.groupdocs.conversion.options.convert/rtfoptions)
### setRtfOptions(RtfOptions value) {#setRtfOptions-com.groupdocs.conversion.options.convert.RtfOptions-}
```
public final void setRtfOptions(RtfOptions value)
```


RTF-specifieke conversie-opties


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [RtfOptions](../../com.groupdocs.conversion.options.convert/rtfoptions) |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Specificeert het zoomniveau in procenten. Standaard is 100.
Standaardzoom wordt ondersteund tot Microsoft Word 2010. Vanaf Microsoft Word 2013 wordt de standaardzoom niet langer op het document ingesteld; in plaats daarvan lijkt deze de zoomfactor van het laatst geopende document te gebruiken.


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Specificeert het zoomniveau in procenten. Standaard is 100.
Standaardzoom wordt ondersteund tot Microsoft Word 2010. Vanaf Microsoft Word 2013 wordt de standaardzoom niet langer op het document ingesteld; in plaats daarvan lijkt deze de zoomfactor van het laatst geopende document te gebruiken.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

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

### getPdfRecognitionMode() {#getPdfRecognitionMode--}
```
public PdfRecognitionMode getPdfRecognitionMode()
```


Haalt de herkenningsmodus op bij het converteren van pdf


**Returns:**
[PdfRecognitionMode](../../com.groupdocs.conversion.options.convert/pdfrecognitionmode)
### setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode) {#setPdfRecognitionMode-com.groupdocs.conversion.options.convert.PdfRecognitionMode-}
```
public void setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode)
```


Stelt de herkenningsmodus in bij het converteren van pdf


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pdfRecognitionMode | [PdfRecognitionMode](../../com.groupdocs.conversion.options.convert/pdfrecognitionmode) |  |

### getMarkdownOptions() {#getMarkdownOptions--}
```
public MarkdownOptions getMarkdownOptions()
```


Haalt op


**Returns:**
[MarkdownOptions](../../com.groupdocs.conversion.options.convert/markdownoptions)
### setMarkdownOptions(MarkdownOptions markdownOptions) {#setMarkdownOptions-com.groupdocs.conversion.options.convert.MarkdownOptions-}
```
public void setMarkdownOptions(MarkdownOptions markdownOptions)
```


Stelt in


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| markdownOptions | [MarkdownOptions](../../com.groupdocs.conversion.options.convert/markdownoptions) |  |

