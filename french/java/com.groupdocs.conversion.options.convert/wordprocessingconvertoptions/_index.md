---
title: "WordProcessingConvertOptions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Options de conversion vers le type de fichier WordProcessing."
type: docs
weight: 48
url: /fr/java/com.groupdocs.conversion.options.convert/wordprocessingconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IPageMarginConvertOptions](../../com.groupdocs.conversion.options.convert/ipagemarginconvertoptions), [com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions), [com.groupdocs.conversion.options.convert.IPdfRecognitionModeOptions](../../com.groupdocs.conversion.options.convert/ipdfrecognitionmodeoptions)
```
public class WordProcessingConvertOptions extends CommonConvertOptions<WordProcessingFileType> implements Serializable, IPageMarginConvertOptions, IPageSizeConvertOptions, IPageOrientationConvertOptions, IPdfRecognitionModeOptions
```

Options de conversion vers le type de fichier WordProcessing.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [WordProcessingConvertOptions()](#WordProcessingConvertOptions--) | Initialise une nouvelle instance de la classe [WordProcessingConvertOptions](../../com.groupdocs.conversion.options.convert/wordprocessingconvertoptions). |
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
|  | [getRtfOptions()](#getRtfOptions--) | Options de conversion spécifiques à RTF |
|
|  | [setRtfOptions(RtfOptions value)](#setRtfOptions-com.groupdocs.conversion.options.convert.RtfOptions-) | Options de conversion spécifiques à RTF |
|
|  | [getZoom()](#getZoom--) | Spécifie le niveau de zoom en pourcentage. |
|
|  | [setZoom(int value)](#setZoom-int-) | Spécifie le niveau de zoom en pourcentage. |
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
|  | [getMarkdownOptions()](#getMarkdownOptions--) | Obtient |
|
|  | [setMarkdownOptions(MarkdownOptions markdownOptions)](#setMarkdownOptions-com.groupdocs.conversion.options.convert.MarkdownOptions-) | Définit |
|
### WordProcessingConvertOptions() {#WordProcessingConvertOptions--}
```
public WordProcessingConvertOptions()
```


Initialise une nouvelle instance de la classe [WordProcessingConvertOptions](../../com.groupdocs.conversion.options.convert/wordprocessingconvertoptions).


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

### getRtfOptions() {#getRtfOptions--}
```
public final RtfOptions getRtfOptions()
```


Options de conversion spécifiques à RTF


**Returns:**
[RtfOptions](../../com.groupdocs.conversion.options.convert/rtfoptions)
### setRtfOptions(RtfOptions value) {#setRtfOptions-com.groupdocs.conversion.options.convert.RtfOptions-}
```
public final void setRtfOptions(RtfOptions value)
```


Options de conversion spécifiques à RTF


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RtfOptions](../../com.groupdocs.conversion.options.convert/rtfoptions) |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Spécifie le niveau de zoom en pourcentage. La valeur par défaut est 100.
Le zoom par défaut est pris en charge jusqu'à Microsoft Word 2010. À partir de Microsoft Word 2013, le zoom par défaut n'est plus appliqué au document, il semble plutôt utiliser le facteur de zoom du dernier document ouvert.


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Spécifie le niveau de zoom en pourcentage. La valeur par défaut est 100.
Le zoom par défaut est pris en charge jusqu'à Microsoft Word 2010. À partir de Microsoft Word 2013, le zoom par défaut n'est plus appliqué au document, il semble plutôt utiliser le facteur de zoom du dernier document ouvert.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

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

### getPdfRecognitionMode() {#getPdfRecognitionMode--}
```
public PdfRecognitionMode getPdfRecognitionMode()
```


Obtient le mode de reconnaissance lors de la conversion depuis le PDF


**Returns:**
[PdfRecognitionMode](../../com.groupdocs.conversion.options.convert/pdfrecognitionmode)
### setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode) {#setPdfRecognitionMode-com.groupdocs.conversion.options.convert.PdfRecognitionMode-}
```
public void setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode)
```


Définit le mode de reconnaissance lors de la conversion depuis le PDF


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pdfRecognitionMode | [PdfRecognitionMode](../../com.groupdocs.conversion.options.convert/pdfrecognitionmode) |  |

### getMarkdownOptions() {#getMarkdownOptions--}
```
public MarkdownOptions getMarkdownOptions()
```


Obtient


**Returns:**
[MarkdownOptions](../../com.groupdocs.conversion.options.convert/markdownoptions)
### setMarkdownOptions(MarkdownOptions markdownOptions) {#setMarkdownOptions-com.groupdocs.conversion.options.convert.MarkdownOptions-}
```
public void setMarkdownOptions(MarkdownOptions markdownOptions)
```


Définit


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| markdownOptions | [MarkdownOptions](../../com.groupdocs.conversion.options.convert/markdownoptions) |  |

