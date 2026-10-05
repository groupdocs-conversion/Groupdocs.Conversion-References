---
title: "WordProcessingConvertOptions"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Opties voor conversie naar WordProcessing-bestandstype."
type: docs
weight: 48
url: /nl/nodejs-java/com.groupdocs.conversion.options.convert/wordprocessingconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IPageMarginConvertOptions](../../com.groupdocs.conversion.options.convert/ipagemarginconvertoptions), [com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions), [com.groupdocs.conversion.options.convert.IPdfRecognitionModeOptions](../../com.groupdocs.conversion.options.convert/ipdfrecognitionmodeoptions)
```
public class WordProcessingConvertOptions extends CommonConvertOptions<WordProcessingFileType> implements Serializable, IPageMarginConvertOptions, IPageSizeConvertOptions, IPageOrientationConvertOptions, IPdfRecognitionModeOptions
```

Opties voor conversie naar WordProcessing-bestandstype.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [WordProcessingConvertOptions()](#WordProcessingConvertOptions--) | Initialiseert een nieuw exemplaar van de [WordProcessingConvertOptions](../../com.groupdocs.conversion.options.convert/wordprocessingconvertoptions) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getDpi()](#getDpi--) | Gewenste pagina-DPI na conversie. |
| [setDpi(int value)](#setDpi-int-) | Gewenste pagina-DPI na conversie. |
| [getPassword()](#getPassword--) | Stel deze eigenschap in als u het geconverteerde document met een wachtwoord wilt beveiligen. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Stel deze eigenschap in als u het geconverteerde document met een wachtwoord wilt beveiligen. |
| [getRtfOptions()](#getRtfOptions--) | RTF-specifieke conversie-opties |
| [setRtfOptions(RtfOptions value)](#setRtfOptions-com.groupdocs.conversion.options.convert.RtfOptions-) | RTF-specifieke conversie-opties |
| [getZoom()](#getZoom--) | Specificeert het zoomniveau in procent. |
| [setZoom(int value)](#setZoom-int-) | Specificeert het zoomniveau in procent. |
| [getMarginTop()](#getMarginTop--) | Gewenste bovenmarge van de pagina in pixels na conversie. |
| [setMarginTop(int value)](#setMarginTop-int-) | Gewenste bovenmarge van de pagina in pixels na conversie. |
| [getMarginBottom()](#getMarginBottom--) | Gewenste ondermarge van de pagina in pixels na conversie. |
| [setMarginBottom(int value)](#setMarginBottom-int-) | Gewenste ondermarge van de pagina in pixels na conversie. |
| [getMarginLeft()](#getMarginLeft--) | Gewenste linkermarge van de pagina in pixels na conversie. |
| [setMarginLeft(int value)](#setMarginLeft-int-) | Gewenste linkermarge van de pagina in pixels na conversie. |
| [getMarginRight()](#getMarginRight--) | Gewenste rechtermarge van de pagina in pixels na conversie. |
| [setMarginRight(int value)](#setMarginRight-int-) | Gewenste rechtermarge van de pagina in pixels na conversie. |
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


Initialiseert een nieuw exemplaar van de [WordProcessingConvertOptions](../../com.groupdocs.conversion.options.convert/wordprocessingconvertoptions) klasse.

### getDpi() {#getDpi--}
```
public final int getDpi()
```


Gewenste pagina-DPI na conversie. De standaardresolutie is: 96 dpi.

**Returns:**
int
### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```


Gewenste pagina-DPI na conversie. De standaardresolutie is: 96 dpi.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

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
| value | java.lang.String |  |

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


Specificeert het zoomniveau in procenten. Standaard is 100. Standaardzoom wordt ondersteund tot Microsoft Word 2010. Vanaf Microsoft Word 2013 wordt de standaardzoom niet langer op het document ingesteld, maar lijkt deze de zoomfactor van het laatst geopende document te gebruiken.

**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Specificeert het zoomniveau in procenten. Standaard is 100. Standaardzoom wordt ondersteund tot Microsoft Word 2010. Vanaf Microsoft Word 2013 wordt de standaardzoom niet langer op het document ingesteld, maar lijkt deze de zoomfactor van het laatst geopende document te gebruiken.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getMarginTop() {#getMarginTop--}
```
public final int getMarginTop()
```


Gewenste bovenmarge van de pagina in pixels na conversie.

**Returns:**
int
### setMarginTop(int value) {#setMarginTop-int-}
```
public final void setMarginTop(int value)
```


Gewenste bovenmarge van de pagina in pixels na conversie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getMarginBottom() {#getMarginBottom--}
```
public final int getMarginBottom()
```


Gewenste ondermarge van de pagina in pixels na conversie.

**Returns:**
int
### setMarginBottom(int value) {#setMarginBottom-int-}
```
public final void setMarginBottom(int value)
```


Gewenste ondermarge van de pagina in pixels na conversie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getMarginLeft() {#getMarginLeft--}
```
public final int getMarginLeft()
```


Gewenste linkermarge van de pagina in pixels na conversie.

**Returns:**
int
### setMarginLeft(int value) {#setMarginLeft-int-}
```
public final void setMarginLeft(int value)
```


Gewenste linkermarge van de pagina in pixels na conversie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getMarginRight() {#getMarginRight--}
```
public final int getMarginRight()
```


Gewenste rechtermarge van de pagina in pixels na conversie.

**Returns:**
int
### setMarginRight(int value) {#setMarginRight-int-}
```
public final void setMarginRight(int value)
```


Gewenste rechtermarge van de pagina in pixels na conversie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getPageOrientation() {#getPageOrientation--}
```
public PageOrientation getPageOrientation()
```


Haalt paginarichting op na conversie

**Returns:**
[PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation)
### setPageOrientation(PageOrientation pageOrientation) {#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-}
```
public void setPageOrientation(PageOrientation pageOrientation)
```


Stelt gewenste paginarichting in na conversie

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


Gespecificeerde paginabreedte in punten als  is ingesteld op PageSize.Custom

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


Gespecificeerde paginahoogte in punten als  is ingesteld op PageSize.Custom

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


Haalt herkenningsmodus op bij het converteren van pdf

**Returns:**
[PdfRecognitionMode](../../com.groupdocs.conversion.options.convert/pdfrecognitionmode)
### setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode) {#setPdfRecognitionMode-com.groupdocs.conversion.options.convert.PdfRecognitionMode-}
```
public void setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode)
```


Stelt herkenningsmodus in bij het converteren van pdf

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pdfRecognitionMode | [PdfRecognitionMode](../../com.groupdocs.conversion.options.convert/pdfrecognitionmode) |  |

