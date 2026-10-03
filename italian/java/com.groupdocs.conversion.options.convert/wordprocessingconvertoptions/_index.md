---
title: "WordProcessingConvertOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Opzioni per la conversione al tipo di file WordProcessing."
type: docs
weight: 48
url: /it/java/com.groupdocs.conversion.options.convert/wordprocessingconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IPageMarginConvertOptions](../../com.groupdocs.conversion.options.convert/ipagemarginconvertoptions), [com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions), [com.groupdocs.conversion.options.convert.IPdfRecognitionModeOptions](../../com.groupdocs.conversion.options.convert/ipdfrecognitionmodeoptions)
```
public class WordProcessingConvertOptions extends CommonConvertOptions<WordProcessingFileType> implements Serializable, IPageMarginConvertOptions, IPageSizeConvertOptions, IPageOrientationConvertOptions, IPdfRecognitionModeOptions
```

Opzioni per la conversione al tipo di file WordProcessing.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [WordProcessingConvertOptions()](#WordProcessingConvertOptions--) | Inizializza una nuova istanza della classe [WordProcessingConvertOptions](../../com.groupdocs.conversion.options.convert/wordprocessingconvertoptions). |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getDpi()](#getDpi--) | DPI della pagina desiderato dopo la conversione. |
|
|  | [setDpi(int value)](#setDpi-int-) | DPI della pagina desiderato dopo la conversione. |
|
|  | [getPassword()](#getPassword--) | Imposta questa proprietà se desideri proteggere il documento convertito con una password. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Imposta questa proprietà se desideri proteggere il documento convertito con una password. |
|
|  | [getRtfOptions()](#getRtfOptions--) | Opzioni di conversione specifiche per RTF |
|
|  | [setRtfOptions(RtfOptions value)](#setRtfOptions-com.groupdocs.conversion.options.convert.RtfOptions-) | Opzioni di conversione specifiche per RTF |
|
|  | [getZoom()](#getZoom--) | Specifica il livello di zoom in percentuale. |
|
|  | [setZoom(int value)](#setZoom-int-) | Specifica il livello di zoom in percentuale. |
|
|  | [getMarginTop()](#getMarginTop--) | Margine superiore della pagina desiderato in punti dopo la conversione. |
|
|  | [setMarginTop(float value)](#setMarginTop-float-) | Margine superiore della pagina desiderato in punti dopo la conversione. |
|
|  | [getMarginBottom()](#getMarginBottom--) | Margine inferiore della pagina desiderato in punti dopo la conversione. |
|
|  | [setMarginBottom(float value)](#setMarginBottom-float-) | Margine inferiore della pagina desiderato in punti dopo la conversione. |
|
|  | [getMarginLeft()](#getMarginLeft--) | Margine sinistro della pagina desiderato in punti dopo la conversione. |
|
|  | [setMarginLeft(float value)](#setMarginLeft-float-) | Margine sinistro della pagina desiderato in punti dopo la conversione. |
|
|  | [getMarginRight()](#getMarginRight--) | Margine destro della pagina desiderato in punti dopo la conversione. |
|
|  | [setMarginRight(float value)](#setMarginRight-float-) | Margine destro della pagina desiderato in punti dopo la conversione. |
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
|  | [getMarkdownOptions()](#getMarkdownOptions--) | Ottiene |
|
|  | [setMarkdownOptions(MarkdownOptions markdownOptions)](#setMarkdownOptions-com.groupdocs.conversion.options.convert.MarkdownOptions-) | Imposta |
|
### WordProcessingConvertOptions() {#WordProcessingConvertOptions--}
```
public WordProcessingConvertOptions()
```


Inizializza una nuova istanza della classe [WordProcessingConvertOptions](../../com.groupdocs.conversion.options.convert/wordprocessingconvertoptions).


### getDpi() {#getDpi--}
```
public final int getDpi()
```


DPI della pagina desiderato dopo la conversione. La risoluzione predefinita è: 96 dpi.


**Returns:**
int
### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```


DPI della pagina desiderato dopo la conversione. La risoluzione predefinita è: 96 dpi.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Imposta questa proprietà se desideri proteggere il documento convertito con una password.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Imposta questa proprietà se desideri proteggere il documento convertito con una password.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getRtfOptions() {#getRtfOptions--}
```
public final RtfOptions getRtfOptions()
```


Opzioni di conversione specifiche per RTF


**Returns:**
[RtfOptions](../../com.groupdocs.conversion.options.convert/rtfoptions)
### setRtfOptions(RtfOptions value) {#setRtfOptions-com.groupdocs.conversion.options.convert.RtfOptions-}
```
public final void setRtfOptions(RtfOptions value)
```


Opzioni di conversione specifiche per RTF


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RtfOptions](../../com.groupdocs.conversion.options.convert/rtfoptions) |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Specifica il livello di zoom in percentuale. Il valore predefinito è 100.
Lo zoom predefinito è supportato fino a Microsoft Word 2010. A partire da Microsoft Word 2013 lo zoom predefinito non è più impostato sul documento, ma sembra utilizzare il fattore di zoom dell'ultimo documento aperto.


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Specifica il livello di zoom in percentuale. Il valore predefinito è 100.
Lo zoom predefinito è supportato fino a Microsoft Word 2010. A partire da Microsoft Word 2013 lo zoom predefinito non è più impostato sul documento, ma sembra utilizzare il fattore di zoom dell'ultimo documento aperto.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getMarginTop() {#getMarginTop--}
```
public final float getMarginTop()
```


Margine superiore della pagina desiderato in punti dopo la conversione.


**Returns:**
float
### setMarginTop(float value) {#setMarginTop-float-}
```
public final void setMarginTop(float value)
```


Margine superiore della pagina desiderato in punti dopo la conversione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getMarginBottom() {#getMarginBottom--}
```
public final float getMarginBottom()
```


Margine inferiore della pagina desiderato in punti dopo la conversione.


**Returns:**
float
### setMarginBottom(float value) {#setMarginBottom-float-}
```
public final void setMarginBottom(float value)
```


Margine inferiore della pagina desiderato in punti dopo la conversione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```


Margine sinistro della pagina desiderato in punti dopo la conversione.


**Returns:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```


Margine sinistro della pagina desiderato in punti dopo la conversione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```


Margine destro della pagina desiderato in punti dopo la conversione.


**Returns:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```


Margine destro della pagina desiderato in punti dopo la conversione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getPageOrientation() {#getPageOrientation--}
```
public PageOrientation getPageOrientation()
```


Ottiene l'orientamento della pagina dopo la conversione


**Returns:**
[PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation)
### setPageOrientation(PageOrientation pageOrientation) {#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-}
```
public void setPageOrientation(PageOrientation pageOrientation)
```


Imposta l'orientamento della pagina desiderato dopo la conversione


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageOrientation | [PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation) |  |

### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


Ottiene le dimensioni della pagina desiderate dopo la conversione


**Returns:**
[PageSize](../../com.groupdocs.conversion.options.convert/pagesize)
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.conversion.options.convert.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


Imposta le dimensioni della pagina desiderate dopo la conversione


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


Larghezza della pagina specificata in punti se impostata su PageSize.Custom


**Returns:**
float
### setPageWidth(float pageWidth) {#setPageWidth-float-}
```
public void setPageWidth(float pageWidth)
```


Imposta la larghezza della pagina desiderata


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageWidth | float |  |

### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


Altezza della pagina specificata in punti se impostata su PageSize.Custom


**Returns:**
float
### setPageHeight(float pageHeight) {#setPageHeight-float-}
```
public void setPageHeight(float pageHeight)
```


Imposta l'altezza della pagina desiderata


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageHeight | float |  |

### getPdfRecognitionMode() {#getPdfRecognitionMode--}
```
public PdfRecognitionMode getPdfRecognitionMode()
```


Ottiene la modalità di riconoscimento durante la conversione da pdf


**Returns:**
[PdfRecognitionMode](../../com.groupdocs.conversion.options.convert/pdfrecognitionmode)
### setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode) {#setPdfRecognitionMode-com.groupdocs.conversion.options.convert.PdfRecognitionMode-}
```
public void setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode)
```


Imposta la modalità di riconoscimento durante la conversione da pdf


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pdfRecognitionMode | [PdfRecognitionMode](../../com.groupdocs.conversion.options.convert/pdfrecognitionmode) |  |

### getMarkdownOptions() {#getMarkdownOptions--}
```
public MarkdownOptions getMarkdownOptions()
```


Ottiene


**Returns:**
[MarkdownOptions](../../com.groupdocs.conversion.options.convert/markdownoptions)
### setMarkdownOptions(MarkdownOptions markdownOptions) {#setMarkdownOptions-com.groupdocs.conversion.options.convert.MarkdownOptions-}
```
public void setMarkdownOptions(MarkdownOptions markdownOptions)
```


Imposta


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| markdownOptions | [MarkdownOptions](../../com.groupdocs.conversion.options.convert/markdownoptions) |  |

