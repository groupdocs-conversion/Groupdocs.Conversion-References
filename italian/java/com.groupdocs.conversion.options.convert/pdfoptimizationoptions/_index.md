---
title: "PdfOptimizationOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Definisce le opzioni di ottimizzazione Pdf."
type: docs
weight: 29
url: /it/java/com.groupdocs.conversion.options.convert/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfOptimizationOptions extends ValueObject implements Serializable
```

Definisce le opzioni di ottimizzazione Pdf.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [PdfOptimizationOptions()](#PdfOptimizationOptions--) | Inizializza una nuova istanza della classe [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions). |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getLinkDuplicateStreams()](#getLinkDuplicateStreams--) | Collega flussi duplicati |
|
|  | [setLinkDuplicateStreams(boolean value)](#setLinkDuplicateStreams-boolean-) | Collega flussi duplicati |
|
|  | [getRemoveUnusedObjects()](#getRemoveUnusedObjects--) | Rimuovi oggetti inutilizzati |
|
|  | [setRemoveUnusedObjects(boolean value)](#setRemoveUnusedObjects-boolean-) | Rimuovi oggetti inutilizzati |
|
|  | [getRemoveUnusedStreams()](#getRemoveUnusedStreams--) | Rimuovi flussi inutilizzati |
|
|  | [setRemoveUnusedStreams(boolean value)](#setRemoveUnusedStreams-boolean-) | Rimuovi flussi inutilizzati |
|
|  | [getCompressImages()](#getCompressImages--) | Se CompressImages è impostato su |
true
, tutte le immagini nel documento vengono ricomprese.
|
|  | [setCompressImages(boolean value)](#setCompressImages-boolean-) | Se CompressImages è impostato su |
true
, tutte le immagini nel documento vengono ricomprese.
|
|  | [getImageQuality()](#getImageQuality--) | Valore in percentuale dove 100% corrisponde a qualità e dimensione dell'immagine invariati. |
|
|  | [setImageQuality(int value)](#setImageQuality-int-) | Valore in percentuale dove 100% corrisponde a qualità e dimensione dell'immagine invariati. |
|
|  | [getUnembedFonts()](#getUnembedFonts--) | Imposta i caratteri non incorporati se impostato su true |
|
|  | [setUnembedFonts(boolean value)](#setUnembedFonts-boolean-) | Imposta i caratteri non incorporati se impostato su true |
|
| [getFontSubsetStrategy()](#getFontSubsetStrategy--) |  |
|  | [setFontSubsetStrategy(PdfFontSubsetStrategy fontSubsetStrategy)](#setFontSubsetStrategy-com.groupdocs.conversion.options.convert.PdfFontSubsetStrategy-) | Imposta la strategia di sottoinsieme dei caratteri |
|
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


Inizializza una nuova istanza della classe [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions).


### getLinkDuplicateStreams() {#getLinkDuplicateStreams--}
```
public final boolean getLinkDuplicateStreams()
```


Collega flussi duplicati


**Returns:**
booleano
### setLinkDuplicateStreams(boolean value) {#setLinkDuplicateStreams-boolean-}
```
public final void setLinkDuplicateStreams(boolean value)
```


Collega flussi duplicati


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getRemoveUnusedObjects() {#getRemoveUnusedObjects--}
```
public final boolean getRemoveUnusedObjects()
```


Rimuovi oggetti inutilizzati


**Returns:**
booleano
### setRemoveUnusedObjects(boolean value) {#setRemoveUnusedObjects-boolean-}
```
public final void setRemoveUnusedObjects(boolean value)
```


Rimuovi oggetti inutilizzati


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getRemoveUnusedStreams() {#getRemoveUnusedStreams--}
```
public final boolean getRemoveUnusedStreams()
```


Rimuovi flussi inutilizzati


**Returns:**
booleano
### setRemoveUnusedStreams(boolean value) {#setRemoveUnusedStreams-boolean-}
```
public final void setRemoveUnusedStreams(boolean value)
```


Rimuovi flussi inutilizzati


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getCompressImages() {#getCompressImages--}
```
public final boolean getCompressImages()
```


Se CompressImages è impostato su
true
, tutte le immagini nel documento vengono ricomprese. La compressione è definita dalla proprietà ImageQuality.


**Returns:**
booleano
### setCompressImages(boolean value) {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```


Se CompressImages è impostato su
true
, tutte le immagini nel documento vengono ricomprese. La compressione è definita dalla proprietà ImageQuality.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getImageQuality() {#getImageQuality--}
```
public final int getImageQuality()
```


Valore in percentuale dove 100% corrisponde a qualità e dimensione dell'immagine invariati. Per ridurre la dimensione dell'immagine, impostare questa proprietà a meno di 100.


**Returns:**
int
### setImageQuality(int value) {#setImageQuality-int-}
```
public final void setImageQuality(int value)
```


Valore in percentuale dove 100% corrisponde a qualità e dimensione dell'immagine invariati. Per ridurre la dimensione dell'immagine, impostare questa proprietà a meno di 100.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getUnembedFonts() {#getUnembedFonts--}
```
public final boolean getUnembedFonts()
```


Imposta i caratteri non incorporati se impostato su true


**Returns:**
booleano
### setUnembedFonts(boolean value) {#setUnembedFonts-boolean-}
```
public final void setUnembedFonts(boolean value)
```


Imposta i caratteri non incorporati se impostato su true


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getFontSubsetStrategy() {#getFontSubsetStrategy--}
```
public PdfFontSubsetStrategy getFontSubsetStrategy()
```




**Returns:**
[PdfFontSubsetStrategy](../../com.groupdocs.conversion.options.convert/pdffontsubsetstrategy)
### setFontSubsetStrategy(PdfFontSubsetStrategy fontSubsetStrategy) {#setFontSubsetStrategy-com.groupdocs.conversion.options.convert.PdfFontSubsetStrategy-}
```
public void setFontSubsetStrategy(PdfFontSubsetStrategy fontSubsetStrategy)
```


Imposta la strategia di sottoinsieme dei caratteri


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontSubsetStrategy | [PdfFontSubsetStrategy](../../com.groupdocs.conversion.options.convert/pdffontsubsetstrategy) |  |

