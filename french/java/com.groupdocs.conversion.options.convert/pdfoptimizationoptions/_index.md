---
title: "PdfOptimizationOptions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Définit les options d'optimisation Pdf."
type: docs
weight: 29
url: /fr/java/com.groupdocs.conversion.options.convert/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfOptimizationOptions extends ValueObject implements Serializable
```

Définit les options d'optimisation Pdf.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [PdfOptimizationOptions()](#PdfOptimizationOptions--) | Initialise une nouvelle instance de la classe [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions). |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getLinkDuplicateStreams()](#getLinkDuplicateStreams--) | Lier les flux dupliqués |
|
|  | [setLinkDuplicateStreams(boolean value)](#setLinkDuplicateStreams-boolean-) | Lier les flux dupliqués |
|
|  | [getRemoveUnusedObjects()](#getRemoveUnusedObjects--) | Supprimer les objets inutilisés |
|
|  | [setRemoveUnusedObjects(boolean value)](#setRemoveUnusedObjects-boolean-) | Supprimer les objets inutilisés |
|
|  | [getRemoveUnusedStreams()](#getRemoveUnusedStreams--) | Supprimer les flux inutilisés |
|
|  | [setRemoveUnusedStreams(boolean value)](#setRemoveUnusedStreams-boolean-) | Supprimer les flux inutilisés |
|
|  | [getCompressImages()](#getCompressImages--) | Si CompressImages est défini sur |
true
, toutes les images du document sont recompressées.
|
|  | [setCompressImages(boolean value)](#setCompressImages-boolean-) | Si CompressImages est défini sur |
true
, toutes les images du document sont recompressées.
|
|  | [getImageQuality()](#getImageQuality--) | Valeur en pourcentage où 100 % correspond à une qualité et une taille d'image inchangées. |
|
|  | [setImageQuality(int value)](#setImageQuality-int-) | Valeur en pourcentage où 100 % correspond à une qualité et une taille d'image inchangées. |
|
|  | [getUnembedFonts()](#getUnembedFonts--) | Ne pas incorporer les polices si défini sur true |
|
|  | [setUnembedFonts(boolean value)](#setUnembedFonts-boolean-) | Ne pas incorporer les polices si défini sur true |
|
| [getFontSubsetStrategy()](#getFontSubsetStrategy--) |  |
|  | [setFontSubsetStrategy(PdfFontSubsetStrategy fontSubsetStrategy)](#setFontSubsetStrategy-com.groupdocs.conversion.options.convert.PdfFontSubsetStrategy-) | Définir la stratégie de sous-ensemble de polices |
|
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


Initialise une nouvelle instance de la classe [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions).


### getLinkDuplicateStreams() {#getLinkDuplicateStreams--}
```
public final boolean getLinkDuplicateStreams()
```


Lier les flux dupliqués


**Returns:**
booléen
### setLinkDuplicateStreams(boolean value) {#setLinkDuplicateStreams-boolean-}
```
public final void setLinkDuplicateStreams(boolean value)
```


Lier les flux dupliqués


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getRemoveUnusedObjects() {#getRemoveUnusedObjects--}
```
public final boolean getRemoveUnusedObjects()
```


Supprimer les objets inutilisés


**Returns:**
booléen
### setRemoveUnusedObjects(boolean value) {#setRemoveUnusedObjects-boolean-}
```
public final void setRemoveUnusedObjects(boolean value)
```


Supprimer les objets inutilisés


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getRemoveUnusedStreams() {#getRemoveUnusedStreams--}
```
public final boolean getRemoveUnusedStreams()
```


Supprimer les flux inutilisés


**Returns:**
booléen
### setRemoveUnusedStreams(boolean value) {#setRemoveUnusedStreams-boolean-}
```
public final void setRemoveUnusedStreams(boolean value)
```


Supprimer les flux inutilisés


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getCompressImages() {#getCompressImages--}
```
public final boolean getCompressImages()
```


Si CompressImages est défini sur
true
, toutes les images du document sont recompressées. La compression est définie par la propriété ImageQuality.


**Returns:**
booléen
### setCompressImages(boolean value) {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```


Si CompressImages est défini sur
true
, toutes les images du document sont recompressées. La compression est définie par la propriété ImageQuality.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getImageQuality() {#getImageQuality--}
```
public final int getImageQuality()
```


Valeur en pourcentage où 100 % correspond à une qualité et une taille d'image inchangées. Pour réduire la taille de l'image, définissez cette propriété à moins de 100.


**Returns:**
int
### setImageQuality(int value) {#setImageQuality-int-}
```
public final void setImageQuality(int value)
```


Valeur en pourcentage où 100 % correspond à une qualité et une taille d'image inchangées. Pour réduire la taille de l'image, définissez cette propriété à moins de 100.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getUnembedFonts() {#getUnembedFonts--}
```
public final boolean getUnembedFonts()
```


Ne pas incorporer les polices si défini sur true


**Returns:**
booléen
### setUnembedFonts(boolean value) {#setUnembedFonts-boolean-}
```
public final void setUnembedFonts(boolean value)
```


Ne pas incorporer les polices si défini sur true


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

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


Définir la stratégie de sous-ensemble de polices


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontSubsetStrategy | [PdfFontSubsetStrategy](../../com.groupdocs.conversion.options.convert/pdffontsubsetstrategy) |  |

