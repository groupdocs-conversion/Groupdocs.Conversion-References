---
title: "PdfConvertOptions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Options pour la conversion vers le type de fichier Pdf."
type: docs
weight: 25
url: /fr/java/com.groupdocs.conversion.options.convert/pdfconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IPageMarginConvertOptions](../../com.groupdocs.conversion.options.convert/ipagemarginconvertoptions), [com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions)
```
public class PdfConvertOptions extends CommonConvertOptions<PdfFileType> implements Serializable, IPageMarginConvertOptions, IPageSizeConvertOptions, IPageOrientationConvertOptions
```

Options pour la conversion vers le type de fichier Pdf.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [PdfConvertOptions()](#PdfConvertOptions--) | Initialise une nouvelle instance de la classe [PdfConvertOptions](../../com.groupdocs.conversion.options.convert/pdfconvertoptions). |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getDpi()](#getDpi--) | DPI de page souhaité après conversion. |
|
|  | [setDpi(int value)](#setDpi-int-) | DPI de page souhaité après conversion. |
|
|  | [getPassword()](#getPassword--) | Définissez cette propriété si vous souhaitez protéger le document converti avec un mot de passe. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Définissez cette propriété si vous souhaitez protéger le document converti avec un mot de passe. |
|
|  | [getMarginTop()](#getMarginTop--) | Marge supérieure de page souhaitée en points après conversion. |
|
|  | [setMarginTop(float value)](#setMarginTop-float-) | Marge supérieure de page souhaitée en points après conversion. |
|
|  | [getMarginBottom()](#getMarginBottom--) | Marge inférieure de page souhaitée en points après conversion. |
|
|  | [setMarginBottom(float value)](#setMarginBottom-float-) | Marge inférieure de page souhaitée en points après conversion. |
|
|  | [getMarginLeft()](#getMarginLeft--) | Marge gauche de page souhaitée en points après conversion. |
|
|  | [setMarginLeft(float value)](#setMarginLeft-float-) | Marge gauche de page souhaitée en points après conversion. |
|
|  | [getMarginRight()](#getMarginRight--) | Marge droite de la page souhaitée en points après conversion. |
|
|  | [setMarginRight(float value)](#setMarginRight-float-) | Marge droite de la page souhaitée en points après conversion. |
|
|  | [getPdfOptions()](#getPdfOptions--) | Options de conversion spécifiques au PDF |
|
|  | [setPdfOptions(PdfOptions value)](#setPdfOptions-com.groupdocs.conversion.options.convert.PdfOptions-) | Options de conversion spécifiques au PDF |
|
|  | [getRotate()](#getRotate--) | Rotation de page |
|
|  | [setRotate(Rotation value)](#setRotate-com.groupdocs.conversion.options.convert.Rotation-) | Rotation de page |
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


Initialise une nouvelle instance de la classe [PdfConvertOptions](../../com.groupdocs.conversion.options.convert/pdfconvertoptions).


### getDpi() {#getDpi--}
```
public final int getDpi()
```


Résolution DPI de la page souhaitée après conversion. La résolution par défaut est : 96 dpi.


**Returns:**
int
### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```


Résolution DPI de la page souhaitée après conversion. La résolution par défaut est : 96 dpi.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Définissez cette propriété si vous souhaitez protéger le document converti avec un mot de passe.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Définissez cette propriété si vous souhaitez protéger le document converti avec un mot de passe.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getMarginTop() {#getMarginTop--}
```
public final float getMarginTop()
```


Marge supérieure de page souhaitée en points après conversion.


**Returns:**
float
### setMarginTop(float value) {#setMarginTop-float-}
```
public final void setMarginTop(float value)
```


Marge supérieure de page souhaitée en points après conversion.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getMarginBottom() {#getMarginBottom--}
```
public final float getMarginBottom()
```


Marge inférieure de page souhaitée en points après conversion.


**Returns:**
float
### setMarginBottom(float value) {#setMarginBottom-float-}
```
public final void setMarginBottom(float value)
```


Marge inférieure de page souhaitée en points après conversion.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```


Marge gauche de page souhaitée en points après conversion.


**Returns:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```


Marge gauche de page souhaitée en points après conversion.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```


Marge droite de la page souhaitée en points après conversion.


**Returns:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```


Marge droite de la page souhaitée en points après conversion.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


Options de conversion spécifiques au PDF


**Returns:**
[PdfOptions](../../com.groupdocs.conversion.options.convert/pdfoptions)
### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.conversion.options.convert.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


Options de conversion spécifiques au PDF


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PdfOptions](../../com.groupdocs.conversion.options.convert/pdfoptions) |  |

### getRotate() {#getRotate--}
```
public final Rotation getRotate()
```


Rotation de page


**Returns:**
[Rotation](../../com.groupdocs.conversion.options.convert/rotation)
### setRotate(Rotation value) {#setRotate-com.groupdocs.conversion.options.convert.Rotation-}
```
public final void setRotate(Rotation value)
```


Rotation de page


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rotation](../../com.groupdocs.conversion.options.convert/rotation) |  |

### getPageOrientation() {#getPageOrientation--}
```
public PageOrientation getPageOrientation()
```


Obtient l'orientation de la page après conversion


**Returns:**
[PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation)
### setPageOrientation(PageOrientation pageOrientation) {#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-}
```
public void setPageOrientation(PageOrientation pageOrientation)
```


Définit l'orientation de la page souhaitée après conversion


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageOrientation | [PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation) |  |

### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


Obtient la taille de page souhaitée après conversion


**Returns:**
[PageSize](../../com.groupdocs.conversion.options.convert/pagesize)
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.conversion.options.convert.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


Définit la taille de page souhaitée après conversion


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


Largeur de page spécifiée en points si elle est définie sur PageSize.Custom


**Returns:**
float
### setPageWidth(float pageWidth) {#setPageWidth-float-}
```
public void setPageWidth(float pageWidth)
```


Définit la largeur de page souhaitée


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageWidth | float |  |

### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


Hauteur de page spécifiée en points si elle est définie sur PageSize.Custom


**Returns:**
float
### setPageHeight(float pageHeight) {#setPageHeight-float-}
```
public void setPageHeight(float pageHeight)
```


Définit la hauteur de page souhaitée


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageHeight | float |  |

