---
title: "PdfConvertOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Opzioni per la conversione al tipo di file Pdf."
type: docs
weight: 25
url: /it/java/com.groupdocs.conversion.options.convert/pdfconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IPageMarginConvertOptions](../../com.groupdocs.conversion.options.convert/ipagemarginconvertoptions), [com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions)
```
public class PdfConvertOptions extends CommonConvertOptions<PdfFileType> implements Serializable, IPageMarginConvertOptions, IPageSizeConvertOptions, IPageOrientationConvertOptions
```

Opzioni per la conversione al tipo di file Pdf.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [PdfConvertOptions()](#PdfConvertOptions--) | Inizializza una nuova istanza della classe [PdfConvertOptions](../../com.groupdocs.conversion.options.convert/pdfconvertoptions). |
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
|  | [getPdfOptions()](#getPdfOptions--) | Opzioni di conversione specifiche per PDF |
|
|  | [setPdfOptions(PdfOptions value)](#setPdfOptions-com.groupdocs.conversion.options.convert.PdfOptions-) | Opzioni di conversione specifiche per PDF |
|
|  | [getRotate()](#getRotate--) | Rotazione della pagina |
|
|  | [setRotate(Rotation value)](#setRotate-com.groupdocs.conversion.options.convert.Rotation-) | Rotazione della pagina |
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


Inizializza una nuova istanza della classe [PdfConvertOptions](../../com.groupdocs.conversion.options.convert/pdfconvertoptions).


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

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


Opzioni di conversione specifiche per PDF


**Returns:**
[PdfOptions](../../com.groupdocs.conversion.options.convert/pdfoptions)
### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.conversion.options.convert.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


Opzioni di conversione specifiche per PDF


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PdfOptions](../../com.groupdocs.conversion.options.convert/pdfoptions) |  |

### getRotate() {#getRotate--}
```
public final Rotation getRotate()
```


Rotazione della pagina


**Returns:**
[Rotation](../../com.groupdocs.conversion.options.convert/rotation)
### setRotate(Rotation value) {#setRotate-com.groupdocs.conversion.options.convert.Rotation-}
```
public final void setRotate(Rotation value)
```


Rotazione della pagina


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rotation](../../com.groupdocs.conversion.options.convert/rotation) |  |

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

