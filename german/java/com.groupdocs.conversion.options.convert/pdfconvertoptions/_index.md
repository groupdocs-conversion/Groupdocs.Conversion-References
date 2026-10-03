---
title: "PdfConvertOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Optionen für die Konvertierung zum Pdf-Dateityp."
type: docs
weight: 25
url: /de/java/com.groupdocs.conversion.options.convert/pdfconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IPageMarginConvertOptions](../../com.groupdocs.conversion.options.convert/ipagemarginconvertoptions), [com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions)
```
public class PdfConvertOptions extends CommonConvertOptions<PdfFileType> implements Serializable, IPageMarginConvertOptions, IPageSizeConvertOptions, IPageOrientationConvertOptions
```

Optionen für die Konvertierung zum Pdf-Dateityp.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PdfConvertOptions()](#PdfConvertOptions--) | Initialisiert eine neue Instanz der Klasse [PdfConvertOptions](../../com.groupdocs.conversion.options.convert/pdfconvertoptions). |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getDpi()](#getDpi--) | Gewünschte Seiten-DPI nach der Konvertierung. |
|
|  | [setDpi(int value)](#setDpi-int-) | Gewünschte Seiten-DPI nach der Konvertierung. |
|
|  | [getPassword()](#getPassword--) | Setzen Sie diese Eigenschaft, wenn Sie das konvertierte Dokument mit einem Passwort schützen möchten. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Setzen Sie diese Eigenschaft, wenn Sie das konvertierte Dokument mit einem Passwort schützen möchten. |
|
|  | [getMarginTop()](#getMarginTop--) | Gewünschter oberer Seitenrand in Punkten nach der Konvertierung. |
|
|  | [setMarginTop(float value)](#setMarginTop-float-) | Gewünschter oberer Seitenrand in Punkten nach der Konvertierung. |
|
|  | [getMarginBottom()](#getMarginBottom--) | Gewünschter unterer Seitenrand in Punkten nach der Konvertierung. |
|
|  | [setMarginBottom(float value)](#setMarginBottom-float-) | Gewünschter unterer Seitenrand in Punkten nach der Konvertierung. |
|
|  | [getMarginLeft()](#getMarginLeft--) | Gewünschter linker Seitenrand in Punkten nach der Konvertierung. |
|
|  | [setMarginLeft(float value)](#setMarginLeft-float-) | Gewünschter linker Seitenrand in Punkten nach der Konvertierung. |
|
|  | [getMarginRight()](#getMarginRight--) | Gewünschter rechter Seitenrand in Punkten nach der Konvertierung. |
|
|  | [setMarginRight(float value)](#setMarginRight-float-) | Gewünschter rechter Seitenrand in Punkten nach der Konvertierung. |
|
|  | [getPdfOptions()](#getPdfOptions--) | PDF-spezifische Konvertierungsoptionen |
|
|  | [setPdfOptions(PdfOptions value)](#setPdfOptions-com.groupdocs.conversion.options.convert.PdfOptions-) | PDF-spezifische Konvertierungsoptionen |
|
|  | [getRotate()](#getRotate--) | Seitendrehung |
|
|  | [setRotate(Rotation value)](#setRotate-com.groupdocs.conversion.options.convert.Rotation-) | Seitendrehung |
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


Initialisiert eine neue Instanz der Klasse [PdfConvertOptions](../../com.groupdocs.conversion.options.convert/pdfconvertoptions).


### getDpi() {#getDpi--}
```
public final int getDpi()
```


Gewünschte Seiten-DPI nach der Konvertierung. Die Standardauflösung beträgt: 96 dpi.


**Returns:**
int
### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```


Gewünschte Seiten-DPI nach der Konvertierung. Die Standardauflösung beträgt: 96 dpi.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Setzen Sie diese Eigenschaft, wenn Sie das konvertierte Dokument mit einem Passwort schützen möchten.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Setzen Sie diese Eigenschaft, wenn Sie das konvertierte Dokument mit einem Passwort schützen möchten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getMarginTop() {#getMarginTop--}
```
public final float getMarginTop()
```


Gewünschter oberer Seitenrand in Punkten nach der Konvertierung.


**Returns:**
float
### setMarginTop(float value) {#setMarginTop-float-}
```
public final void setMarginTop(float value)
```


Gewünschter oberer Seitenrand in Punkten nach der Konvertierung.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getMarginBottom() {#getMarginBottom--}
```
public final float getMarginBottom()
```


Gewünschter unterer Seitenrand in Punkten nach der Konvertierung.


**Returns:**
float
### setMarginBottom(float value) {#setMarginBottom-float-}
```
public final void setMarginBottom(float value)
```


Gewünschter unterer Seitenrand in Punkten nach der Konvertierung.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```


Gewünschter linker Seitenrand in Punkten nach der Konvertierung.


**Returns:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```


Gewünschter linker Seitenrand in Punkten nach der Konvertierung.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```


Gewünschter rechter Seitenrand in Punkten nach der Konvertierung.


**Returns:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```


Gewünschter rechter Seitenrand in Punkten nach der Konvertierung.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


PDF-spezifische Konvertierungsoptionen


**Returns:**
[PdfOptions](../../com.groupdocs.conversion.options.convert/pdfoptions)
### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.conversion.options.convert.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


PDF-spezifische Konvertierungsoptionen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PdfOptions](../../com.groupdocs.conversion.options.convert/pdfoptions) |  |

### getRotate() {#getRotate--}
```
public final Rotation getRotate()
```


Seitendrehung


**Returns:**
[Rotation](../../com.groupdocs.conversion.options.convert/rotation)
### setRotate(Rotation value) {#setRotate-com.groupdocs.conversion.options.convert.Rotation-}
```
public final void setRotate(Rotation value)
```


Seitendrehung


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rotation](../../com.groupdocs.conversion.options.convert/rotation) |  |

### getPageOrientation() {#getPageOrientation--}
```
public PageOrientation getPageOrientation()
```


Liest die Seitenorientierung nach der Konvertierung


**Returns:**
[PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation)
### setPageOrientation(PageOrientation pageOrientation) {#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-}
```
public void setPageOrientation(PageOrientation pageOrientation)
```


Setzt die gewünschte Seitenorientierung nach der Konvertierung


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageOrientation | [PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation) |  |

### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


Liest die gewünschte Seitengröße nach der Konvertierung


**Returns:**
[PageSize](../../com.groupdocs.conversion.options.convert/pagesize)
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.conversion.options.convert.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


Setzt die gewünschte Seitengröße nach der Konvertierung


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


Angegebene Seitenbreite in Punkten, wenn sie auf PageSize.Custom gesetzt ist


**Returns:**
float
### setPageWidth(float pageWidth) {#setPageWidth-float-}
```
public void setPageWidth(float pageWidth)
```


Setzt die gewünschte Seitenbreite


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageWidth | float |  |

### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


Angegebene Seitenhöhe in Punkten, wenn sie auf PageSize.Custom gesetzt ist


**Returns:**
float
### setPageHeight(float pageHeight) {#setPageHeight-float-}
```
public void setPageHeight(float pageHeight)
```


Setzt die gewünschte Seitenhöhe


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageHeight | float |  |

