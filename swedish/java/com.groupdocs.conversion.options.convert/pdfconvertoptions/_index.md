---
title: "PdfConvertOptions"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Alternativ för konvertering till Pdf-filtyp."
type: docs
weight: 25
url: /sv/java/com.groupdocs.conversion.options.convert/pdfconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IPageMarginConvertOptions](../../com.groupdocs.conversion.options.convert/ipagemarginconvertoptions), [com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions)
```
public class PdfConvertOptions extends CommonConvertOptions<PdfFileType> implements Serializable, IPageMarginConvertOptions, IPageSizeConvertOptions, IPageOrientationConvertOptions
```

Alternativ för konvertering till Pdf-filtyp.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [PdfConvertOptions()](#PdfConvertOptions--) | Initierar en ny instans av klassen [PdfConvertOptions](../../com.groupdocs.conversion.options.convert/pdfconvertoptions). |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getDpi()](#getDpi--) | Önskad DPI för sidan efter konvertering. |
|
|  | [setDpi(int value)](#setDpi-int-) | Önskad DPI för sidan efter konvertering. |
|
|  | [getPassword()](#getPassword--) | Ange den här egenskapen om du vill skydda det konverterade dokumentet med ett lösenord. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Ange den här egenskapen om du vill skydda det konverterade dokumentet med ett lösenord. |
|
|  | [getMarginTop()](#getMarginTop--) | Önskad övre marginal för sidan i punkter efter konvertering. |
|
|  | [setMarginTop(float value)](#setMarginTop-float-) | Önskad övre marginal för sidan i punkter efter konvertering. |
|
|  | [getMarginBottom()](#getMarginBottom--) | Önskad nedre marginal för sidan i punkter efter konvertering. |
|
|  | [setMarginBottom(float value)](#setMarginBottom-float-) | Önskad nedre marginal för sidan i punkter efter konvertering. |
|
|  | [getMarginLeft()](#getMarginLeft--) | Önskad vänster marginal för sidan i punkter efter konvertering. |
|
|  | [setMarginLeft(float value)](#setMarginLeft-float-) | Önskad vänster marginal för sidan i punkter efter konvertering. |
|
|  | [getMarginRight()](#getMarginRight--) | Önskad höger marginal för sidan i punkter efter konvertering. |
|
|  | [setMarginRight(float value)](#setMarginRight-float-) | Önskad höger marginal för sidan i punkter efter konvertering. |
|
|  | [getPdfOptions()](#getPdfOptions--) | Pdf-specifika konverteringsalternativ |
|
|  | [setPdfOptions(PdfOptions value)](#setPdfOptions-com.groupdocs.conversion.options.convert.PdfOptions-) | Pdf-specifika konverteringsalternativ |
|
|  | [getRotate()](#getRotate--) | Sidrotation |
|
|  | [setRotate(Rotation value)](#setRotate-com.groupdocs.conversion.options.convert.Rotation-) | Sidrotation |
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


Initierar en ny instans av klassen [PdfConvertOptions](../../com.groupdocs.conversion.options.convert/pdfconvertoptions).


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
| värde | int |  |

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
| värde | java.lang.String |  |

### getMarginTop() {#getMarginTop--}
```
public final float getMarginTop()
```


Önskad övre marginal för sidan i punkter efter konvertering.


**Returns:**
float
### setMarginTop(float value) {#setMarginTop-float-}
```
public final void setMarginTop(float value)
```


Önskad övre marginal för sidan i punkter efter konvertering.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getMarginBottom() {#getMarginBottom--}
```
public final float getMarginBottom()
```


Önskad nedre marginal för sidan i punkter efter konvertering.


**Returns:**
float
### setMarginBottom(float value) {#setMarginBottom-float-}
```
public final void setMarginBottom(float value)
```


Önskad nedre marginal för sidan i punkter efter konvertering.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```


Önskad vänster marginal för sidan i punkter efter konvertering.


**Returns:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```


Önskad vänster marginal för sidan i punkter efter konvertering.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```


Önskad höger marginal för sidan i punkter efter konvertering.


**Returns:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```


Önskad höger marginal för sidan i punkter efter konvertering.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


Pdf-specifika konverteringsalternativ


**Returns:**
[PdfOptions](../../com.groupdocs.conversion.options.convert/pdfoptions)
### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.conversion.options.convert.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


Pdf-specifika konverteringsalternativ


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PdfOptions](../../com.groupdocs.conversion.options.convert/pdfoptions) |  |

### getRotate() {#getRotate--}
```
public final Rotation getRotate()
```


Sidrotation


**Returns:**
[Rotation](../../com.groupdocs.conversion.options.convert/rotation)
### setRotate(Rotation value) {#setRotate-com.groupdocs.conversion.options.convert.Rotation-}
```
public final void setRotate(Rotation value)
```


Sidrotation


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rotation](../../com.groupdocs.conversion.options.convert/rotation) |  |

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


Angiven sidbredd i punkter om den är satt till PageSize.Custom


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


Angiven sidhöjd i punkter om den är satt till PageSize.Custom


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

