---
title: "WordProcessingConvertOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Optionen für die Konvertierung zum WordProcessing-Dateityp."
type: docs
weight: 48
url: /de/java/com.groupdocs.conversion.options.convert/wordprocessingconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IPageMarginConvertOptions](../../com.groupdocs.conversion.options.convert/ipagemarginconvertoptions), [com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions), [com.groupdocs.conversion.options.convert.IPdfRecognitionModeOptions](../../com.groupdocs.conversion.options.convert/ipdfrecognitionmodeoptions)
```
public class WordProcessingConvertOptions extends CommonConvertOptions<WordProcessingFileType> implements Serializable, IPageMarginConvertOptions, IPageSizeConvertOptions, IPageOrientationConvertOptions, IPdfRecognitionModeOptions
```

Optionen für die Konvertierung zum WordProcessing-Dateityp.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [WordProcessingConvertOptions()](#WordProcessingConvertOptions--) | Initialisiert eine neue Instanz der Klasse [WordProcessingConvertOptions](../../com.groupdocs.conversion.options.convert/wordprocessingconvertoptions). |
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
|  | [getRtfOptions()](#getRtfOptions--) | RTF-spezifische Konvertierungsoptionen |
|
|  | [setRtfOptions(RtfOptions value)](#setRtfOptions-com.groupdocs.conversion.options.convert.RtfOptions-) | RTF-spezifische Konvertierungsoptionen |
|
|  | [getZoom()](#getZoom--) | Gibt den Zoom‑Wert in Prozent an. |
|
|  | [setZoom(int value)](#setZoom-int-) | Gibt den Zoom‑Wert in Prozent an. |
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
|  | [getMarkdownOptions()](#getMarkdownOptions--) | Liest |
|
|  | [setMarkdownOptions(MarkdownOptions markdownOptions)](#setMarkdownOptions-com.groupdocs.conversion.options.convert.MarkdownOptions-) | Setzt |
|
### WordProcessingConvertOptions() {#WordProcessingConvertOptions--}
```
public WordProcessingConvertOptions()
```


Initialisiert eine neue Instanz der Klasse [WordProcessingConvertOptions](../../com.groupdocs.conversion.options.convert/wordprocessingconvertoptions).


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

### getRtfOptions() {#getRtfOptions--}
```
public final RtfOptions getRtfOptions()
```


RTF-spezifische Konvertierungsoptionen


**Returns:**
[RtfOptions](../../com.groupdocs.conversion.options.convert/rtfoptions)
### setRtfOptions(RtfOptions value) {#setRtfOptions-com.groupdocs.conversion.options.convert.RtfOptions-}
```
public final void setRtfOptions(RtfOptions value)
```


RTF-spezifische Konvertierungsoptionen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RtfOptions](../../com.groupdocs.conversion.options.convert/rtfoptions) |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Gibt den Zoom‑Wert in Prozent an. Standard ist 100.
Standardzoom wird bis Microsoft Word 2010 unterstützt. Ab Microsoft Word 2013 wird der Standardzoom nicht mehr auf das Dokument gesetzt, stattdessen scheint der Zoomfaktor des zuletzt geöffneten Dokuments verwendet zu werden.


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Gibt den Zoom‑Wert in Prozent an. Standard ist 100.
Standardzoom wird bis Microsoft Word 2010 unterstützt. Ab Microsoft Word 2013 wird der Standardzoom nicht mehr auf das Dokument gesetzt, stattdessen scheint der Zoomfaktor des zuletzt geöffneten Dokuments verwendet zu werden.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

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

### getPdfRecognitionMode() {#getPdfRecognitionMode--}
```
public PdfRecognitionMode getPdfRecognitionMode()
```


Ermittelt den Erkennungsmodus beim Konvertieren von PDF.


**Returns:**
[PdfRecognitionMode](../../com.groupdocs.conversion.options.convert/pdfrecognitionmode)
### setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode) {#setPdfRecognitionMode-com.groupdocs.conversion.options.convert.PdfRecognitionMode-}
```
public void setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode)
```


Setzt den Erkennungsmodus beim Konvertieren von PDF.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pdfRecognitionMode | [PdfRecognitionMode](../../com.groupdocs.conversion.options.convert/pdfrecognitionmode) |  |

### getMarkdownOptions() {#getMarkdownOptions--}
```
public MarkdownOptions getMarkdownOptions()
```


Liest


**Returns:**
[MarkdownOptions](../../com.groupdocs.conversion.options.convert/markdownoptions)
### setMarkdownOptions(MarkdownOptions markdownOptions) {#setMarkdownOptions-com.groupdocs.conversion.options.convert.MarkdownOptions-}
```
public void setMarkdownOptions(MarkdownOptions markdownOptions)
```


Setzt


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| markdownOptions | [MarkdownOptions](../../com.groupdocs.conversion.options.convert/markdownoptions) |  |

