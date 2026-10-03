---
title: "PdfOptions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Options pour la conversion vers le type de fichier Pdf."
type: docs
weight: 30
url: /fr/java/com.groupdocs.conversion.options.convert/pdfoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfOptions extends ValueObject implements Serializable
```

Options pour la conversion vers le type de fichier Pdf.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [PdfOptions()](#PdfOptions--) | ctor |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getPdfFormat()](#getPdfFormat--) | Définit le format PDF du document converti. |
|
|  | [setPdfFormat(PdfFormats value)](#setPdfFormat-com.groupdocs.conversion.options.convert.PdfFormats-) | Définit le format PDF du document converti. |
|
|  | [getRemovePdfACompliance()](#getRemovePdfACompliance--) | Supprime la conformité PDF/A |
|
|  | [setRemovePdfACompliance(boolean value)](#setRemovePdfACompliance-boolean-) | Supprime la conformité PDF/A |
|
|  | [getZoom()](#getZoom--) | Spécifie le niveau de zoom en pourcentage. |
|
|  | [setZoom(int value)](#setZoom-int-) | Spécifie le niveau de zoom en pourcentage. |
|
|  | [getLinearize()](#getLinearize--) | Linéarise le document PDF pour le Web |
|
|  | [setLinearize(boolean value)](#setLinearize-boolean-) | Linéarise le document PDF pour le Web |
|
|  | [getOptimizationOptions()](#getOptimizationOptions--) | Options d'optimisation PDF |
|
|  | [setOptimizationOptions(PdfOptimizationOptions value)](#setOptimizationOptions-com.groupdocs.conversion.options.convert.PdfOptimizationOptions-) | Options d'optimisation PDF |
|
|  | [getGrayscale()](#getGrayscale--) | Convertit un PDF de l'espace colorimétrique RVB en niveaux de gris |
|
|  | [setGrayscale(boolean value)](#setGrayscale-boolean-) | Convertit un PDF de l'espace colorimétrique RVB en niveaux de gris |
|
|  | [getFormattingOptions()](#getFormattingOptions--) | Options de formatage PDF |
|
|  | [setFormattingOptions(PdfFormattingOptions value)](#setFormattingOptions-com.groupdocs.conversion.options.convert.PdfFormattingOptions-) | Options de formatage PDF |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | Métadonnées du document PDF. |
|
| [setDocumentInfo(PdfDocumentInfo documentInfo)](#setDocumentInfo-com.groupdocs.conversion.options.convert.PdfDocumentInfo-) |  |
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


ctor


### getPdfFormat() {#getPdfFormat--}
```
public final PdfFormats getPdfFormat()
```


Définit le format PDF du document converti.


**Returns:**
[PdfFormats](../../com.groupdocs.conversion.options.convert/pdfformats)
### setPdfFormat(PdfFormats value) {#setPdfFormat-com.groupdocs.conversion.options.convert.PdfFormats-}
```
public final void setPdfFormat(PdfFormats value)
```


Définit le format PDF du document converti.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PdfFormats](../../com.groupdocs.conversion.options.convert/pdfformats) |  |

### getRemovePdfACompliance() {#getRemovePdfACompliance--}
```
public final boolean getRemovePdfACompliance()
```


Supprime la conformité PDF/A


**Returns:**
booléen
### setRemovePdfACompliance(boolean value) {#setRemovePdfACompliance-boolean-}
```
public final void setRemovePdfACompliance(boolean value)
```


Supprime la conformité PDF/A


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Spécifie le niveau de zoom en pourcentage. La valeur par défaut est 100.


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Spécifie le niveau de zoom en pourcentage. La valeur par défaut est 100.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getLinearize() {#getLinearize--}
```
public final boolean getLinearize()
```


Linéarise le document PDF pour le Web


**Returns:**
booléen
### setLinearize(boolean value) {#setLinearize-boolean-}
```
public final void setLinearize(boolean value)
```


Linéarise le document PDF pour le Web


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getOptimizationOptions() {#getOptimizationOptions--}
```
public final PdfOptimizationOptions getOptimizationOptions()
```


Options d'optimisation PDF


**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions)
### setOptimizationOptions(PdfOptimizationOptions value) {#setOptimizationOptions-com.groupdocs.conversion.options.convert.PdfOptimizationOptions-}
```
public final void setOptimizationOptions(PdfOptimizationOptions value)
```


Options d'optimisation PDF


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions) |  |

### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


Convertit un PDF de l'espace colorimétrique RVB en niveaux de gris


**Returns:**
booléen
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


Convertit un PDF de l'espace colorimétrique RVB en niveaux de gris


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getFormattingOptions() {#getFormattingOptions--}
```
public final PdfFormattingOptions getFormattingOptions()
```


Options de formatage PDF


**Returns:**
[PdfFormattingOptions](../../com.groupdocs.conversion.options.convert/pdfformattingoptions)
### setFormattingOptions(PdfFormattingOptions value) {#setFormattingOptions-com.groupdocs.conversion.options.convert.PdfFormattingOptions-}
```
public final void setFormattingOptions(PdfFormattingOptions value)
```


Options de formatage PDF


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PdfFormattingOptions](../../com.groupdocs.conversion.options.convert/pdfformattingoptions) |  |

### getDocumentInfo() {#getDocumentInfo--}
```
public PdfDocumentInfo getDocumentInfo()
```


Métadonnées du document PDF.


**Returns:**
[PdfDocumentInfo](../../com.groupdocs.conversion.options.convert/pdfdocumentinfo)
### setDocumentInfo(PdfDocumentInfo documentInfo) {#setDocumentInfo-com.groupdocs.conversion.options.convert.PdfDocumentInfo-}
```
public void setDocumentInfo(PdfDocumentInfo documentInfo)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| documentInfo | [PdfDocumentInfo](../../com.groupdocs.conversion.options.convert/pdfdocumentinfo) |  |

