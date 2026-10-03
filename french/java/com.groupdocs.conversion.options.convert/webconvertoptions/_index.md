---
title: "WebConvertOptions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Options de conversion vers le type de fichier Web."
type: docs
weight: 46
url: /fr/java/com.groupdocs.conversion.options.convert/webconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions
```
public class WebConvertOptions extends CommonConvertOptions<WebFileType>
```

Options de conversion vers le type de fichier Web.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [WebConvertOptions()](#WebConvertOptions--) | Initialise une nouvelle instance de la classe. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [isUsePdf()](#isUsePdf--) |  |
| [setUsePdf(boolean usePdf)](#setUsePdf-boolean-) |  |
| [isFixedLayout()](#isFixedLayout--) |  |
| [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) |  |
| [isFixedLayoutShowBorders()](#isFixedLayoutShowBorders--) |  |
| [setFixedLayoutShowBorders(boolean fixedLayoutShowBorders)](#setFixedLayoutShowBorders-boolean-) |  |
| [getZoom()](#getZoom--) |  |
| [setZoom(int zoom)](#setZoom-int-) |  |
|  | [isEmbedFontResources()](#isEmbedFontResources--) | Spécifie si les ressources de police doivent être intégrées dans le HTML principal. |
|
|  | [setEmbedFontResources(boolean embedFontResources)](#setEmbedFontResources-boolean-) | Spécifie si les ressources de police doivent être intégrées dans le HTML principal. |
|
### WebConvertOptions() {#WebConvertOptions--}
```
public WebConvertOptions()
```


Initialise une nouvelle instance de la classe.


### isUsePdf() {#isUsePdf--}
```
public boolean isUsePdf()
```




**Returns:**
booléen
### setUsePdf(boolean usePdf) {#setUsePdf-boolean-}
```
public void setUsePdf(boolean usePdf)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| usePdf | booléen |  |

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```




**Returns:**
booléen
### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fixedLayout | booléen |  |

### isFixedLayoutShowBorders() {#isFixedLayoutShowBorders--}
```
public boolean isFixedLayoutShowBorders()
```




**Returns:**
booléen
### setFixedLayoutShowBorders(boolean fixedLayoutShowBorders) {#setFixedLayoutShowBorders-boolean-}
```
public void setFixedLayoutShowBorders(boolean fixedLayoutShowBorders)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fixedLayoutShowBorders | booléen |  |

### getZoom() {#getZoom--}
```
public int getZoom()
```




**Returns:**
int
### setZoom(int zoom) {#setZoom-int-}
```
public void setZoom(int zoom)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| zoom | int |  |

### isEmbedFontResources() {#isEmbedFontResources--}
```
public boolean isEmbedFontResources()
```


Spécifie si les ressources de police doivent être intégrées dans le HTML principal. La valeur par défaut est false. Remarque : si FixedLayout est défini sur true, les ressources de police seront toujours intégrées.


**Returns:**
booléen
### setEmbedFontResources(boolean embedFontResources) {#setEmbedFontResources-boolean-}
```
public void setEmbedFontResources(boolean embedFontResources)
```


Spécifie si les ressources de police doivent être intégrées dans le HTML principal. La valeur par défaut est false. Remarque : si FixedLayout est défini sur true, les ressources de police seront toujours intégrées.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| embedFontResources | booléen |  |

