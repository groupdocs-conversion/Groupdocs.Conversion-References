---
title: "WordProcessingConvertOptions"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Alternativ för konvertering till WordProcessing-filtyp."
type: docs
weight: 48
url: /sv/nodejs-java/com.groupdocs.conversion.options.convert/wordprocessingconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IPageMarginConvertOptions](../../com.groupdocs.conversion.options.convert/ipagemarginconvertoptions), [com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions), [com.groupdocs.conversion.options.convert.IPdfRecognitionModeOptions](../../com.groupdocs.conversion.options.convert/ipdfrecognitionmodeoptions)
```
public class WordProcessingConvertOptions extends CommonConvertOptions<WordProcessingFileType> implements Serializable, IPageMarginConvertOptions, IPageSizeConvertOptions, IPageOrientationConvertOptions, IPdfRecognitionModeOptions
```

Alternativ för konvertering till WordProcessing-filtyp.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WordProcessingConvertOptions()](#WordProcessingConvertOptions--) | Initierar en ny instans av klassen [WordProcessingConvertOptions](../../com.groupdocs.conversion.options.convert/wordprocessingconvertoptions). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDpi()](#getDpi--) | Önskad DPI för sidan efter konvertering. |
| [setDpi(int value)](#setDpi-int-) | Önskad DPI för sidan efter konvertering. |
| [getPassword()](#getPassword--) | Ange den här egenskapen om du vill skydda det konverterade dokumentet med ett lösenord. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Ange den här egenskapen om du vill skydda det konverterade dokumentet med ett lösenord. |
| [getRtfOptions()](#getRtfOptions--) | RTF-specifika konverteringsalternativ |
| [setRtfOptions(RtfOptions value)](#setRtfOptions-com.groupdocs.conversion.options.convert.RtfOptions-) | RTF-specifika konverteringsalternativ |
| [getZoom()](#getZoom--) | Anger zoomnivån i procent. |
| [setZoom(int value)](#setZoom-int-) | Anger zoomnivån i procent. |
| [getMarginTop()](#getMarginTop--) | Önskad övre marginal för sidan i pixlar efter konvertering. |
| [setMarginTop(int value)](#setMarginTop-int-) | Önskad övre marginal för sidan i pixlar efter konvertering. |
| [getMarginBottom()](#getMarginBottom--) | Önskad nedre marginal för sidan i pixlar efter konvertering. |
| [setMarginBottom(int value)](#setMarginBottom-int-) | Önskad nedre marginal för sidan i pixlar efter konvertering. |
| [getMarginLeft()](#getMarginLeft--) | Önskad vänster marginal för sidan i pixlar efter konvertering. |
| [setMarginLeft(int value)](#setMarginLeft-int-) | Önskad vänster marginal för sidan i pixlar efter konvertering. |
| [getMarginRight()](#getMarginRight--) | Önskad högermarginal för sidan i pixlar efter konvertering. |
| [setMarginRight(int value)](#setMarginRight-int-) | Önskad högermarginal för sidan i pixlar efter konvertering. |
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


Initierar en ny instans av klassen [WordProcessingConvertOptions](../../com.groupdocs.conversion.options.convert/wordprocessingconvertoptions).

### getDpi() {#getDpi--}
```
public final int getDpi()
```


Önskad DPI för sidan efter konvertering. Standardupplösningen är: 96 dpi.

**Returns:**
int
### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```


Önskad DPI för sidan efter konvertering. Standardupplösningen är: 96 dpi.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Ange den här egenskapen om du vill skydda det konverterade dokumentet med ett lösenord.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Ange den här egenskapen om du vill skydda det konverterade dokumentet med ett lösenord.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getRtfOptions() {#getRtfOptions--}
```
public final RtfOptions getRtfOptions()
```


RTF-specifika konverteringsalternativ

**Returns:**
[RtfOptions](../../com.groupdocs.conversion.options.convert/rtfoptions)
### setRtfOptions(RtfOptions value) {#setRtfOptions-com.groupdocs.conversion.options.convert.RtfOptions-}
```
public final void setRtfOptions(RtfOptions value)
```


RTF-specifika konverteringsalternativ

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RtfOptions](../../com.groupdocs.conversion.options.convert/rtfoptions) |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Anger zoomnivån i procent. Standard är 100. Standardzoom stöds fram till Microsoft Word 2010. Från och med Microsoft Word 2013 sätts standardzoom inte längre till dokumentet, utan det verkar använda zoomfaktorn från det senast öppnade dokumentet.

**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Anger zoomnivån i procent. Standard är 100. Standardzoom stöds fram till Microsoft Word 2010. Från och med Microsoft Word 2013 sätts standardzoom inte längre till dokumentet, utan det verkar använda zoomfaktorn från det senast öppnade dokumentet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getMarginTop() {#getMarginTop--}
```
public final int getMarginTop()
```


Önskad övre marginal för sidan i pixlar efter konvertering.

**Returns:**
int
### setMarginTop(int value) {#setMarginTop-int-}
```
public final void setMarginTop(int value)
```


Önskad övre marginal för sidan i pixlar efter konvertering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getMarginBottom() {#getMarginBottom--}
```
public final int getMarginBottom()
```


Önskad nedre marginal för sidan i pixlar efter konvertering.

**Returns:**
int
### setMarginBottom(int value) {#setMarginBottom-int-}
```
public final void setMarginBottom(int value)
```


Önskad nedre marginal för sidan i pixlar efter konvertering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getMarginLeft() {#getMarginLeft--}
```
public final int getMarginLeft()
```


Önskad vänster marginal för sidan i pixlar efter konvertering.

**Returns:**
int
### setMarginLeft(int value) {#setMarginLeft-int-}
```
public final void setMarginLeft(int value)
```


Önskad vänster marginal för sidan i pixlar efter konvertering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getMarginRight() {#getMarginRight--}
```
public final int getMarginRight()
```


Önskad högermarginal för sidan i pixlar efter konvertering.

**Returns:**
int
### setMarginRight(int value) {#setMarginRight-int-}
```
public final void setMarginRight(int value)
```


Önskad högermarginal för sidan i pixlar efter konvertering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getPageOrientation() {#getPageOrientation--}
```
public PageOrientation getPageOrientation()
```


Hämtar sidorientering efter konvertering

**Returns:**
[PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation)
### setPageOrientation(PageOrientation pageOrientation) {#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-}
```
public void setPageOrientation(PageOrientation pageOrientation)
```


Ställer in önskad sidorientering efter konvertering

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageOrientation | [PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation) |  |

### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


Hämtar önskad sidstorlek efter konvertering

**Returns:**
[PageSize](../../com.groupdocs.conversion.options.convert/pagesize)
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.conversion.options.convert.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


Ställ in önskad sidstorlek efter konvertering

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


Angiven sidbredd i punkter om  är inställd på PageSize.Custom

**Returns:**
float
### setPageWidth(float pageWidth) {#setPageWidth-float-}
```
public void setPageWidth(float pageWidth)
```


Ställ in önskad sidbredd

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageWidth | float |  |

### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


Angiven sidhöjd i punkter om  är inställd på PageSize.Custom

**Returns:**
float
### setPageHeight(float pageHeight) {#setPageHeight-float-}
```
public void setPageHeight(float pageHeight)
```


Ställ in önskad sidhöjd

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageHeight | float |  |

### getPdfRecognitionMode() {#getPdfRecognitionMode--}
```
public PdfRecognitionMode getPdfRecognitionMode()
```


Hämtar igenkänningsläge vid konvertering från pdf

**Returns:**
[PdfRecognitionMode](../../com.groupdocs.conversion.options.convert/pdfrecognitionmode)
### setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode) {#setPdfRecognitionMode-com.groupdocs.conversion.options.convert.PdfRecognitionMode-}
```
public void setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode)
```


Ställer in igenkänningsläge vid konvertering från pdf

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pdfRecognitionMode | [PdfRecognitionMode](../../com.groupdocs.conversion.options.convert/pdfrecognitionmode) |  |

