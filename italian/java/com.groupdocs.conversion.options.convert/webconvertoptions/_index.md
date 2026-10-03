---
title: "WebConvertOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Opzioni per la conversione al tipo di file Web."
type: docs
weight: 46
url: /it/java/com.groupdocs.conversion.options.convert/webconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions
```
public class WebConvertOptions extends CommonConvertOptions<WebFileType>
```

Opzioni per la conversione al tipo di file Web.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [WebConvertOptions()](#WebConvertOptions--) | Inizializza una nuova istanza della classe. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isUsePdf()](#isUsePdf--) |  |
| [setUsePdf(boolean usePdf)](#setUsePdf-boolean-) |  |
| [isFixedLayout()](#isFixedLayout--) |  |
| [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) |  |
| [isFixedLayoutShowBorders()](#isFixedLayoutShowBorders--) |  |
| [setFixedLayoutShowBorders(boolean fixedLayoutShowBorders)](#setFixedLayoutShowBorders-boolean-) |  |
| [getZoom()](#getZoom--) |  |
| [setZoom(int zoom)](#setZoom-int-) |  |
|  | [isEmbedFontResources()](#isEmbedFontResources--) | Specifica se incorporare le risorse dei font all'interno dell'HTML principale. |
|
|  | [setEmbedFontResources(boolean embedFontResources)](#setEmbedFontResources-boolean-) | Specifica se incorporare le risorse dei font all'interno dell'HTML principale. |
|
### WebConvertOptions() {#WebConvertOptions--}
```
public WebConvertOptions()
```


Inizializza una nuova istanza della classe.


### isUsePdf() {#isUsePdf--}
```
public boolean isUsePdf()
```




**Returns:**
booleano
### setUsePdf(boolean usePdf) {#setUsePdf-boolean-}
```
public void setUsePdf(boolean usePdf)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| usePdf | booleano |  |

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```




**Returns:**
booleano
### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fixedLayout | booleano |  |

### isFixedLayoutShowBorders() {#isFixedLayoutShowBorders--}
```
public boolean isFixedLayoutShowBorders()
```




**Returns:**
booleano
### setFixedLayoutShowBorders(boolean fixedLayoutShowBorders) {#setFixedLayoutShowBorders-boolean-}
```
public void setFixedLayoutShowBorders(boolean fixedLayoutShowBorders)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fixedLayoutShowBorders | booleano |  |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| zoom | int |  |

### isEmbedFontResources() {#isEmbedFontResources--}
```
public boolean isEmbedFontResources()
```


Specifica se incorporare le risorse dei font all'interno dell'HTML principale. Il valore predefinito è false. Nota: se FixedLayout è impostato su true, le risorse dei font saranno sempre incorporate.


**Returns:**
booleano
### setEmbedFontResources(boolean embedFontResources) {#setEmbedFontResources-boolean-}
```
public void setEmbedFontResources(boolean embedFontResources)
```


Specifica se incorporare le risorse dei font all'interno dell'HTML principale. Il valore predefinito è false. Nota: se FixedLayout è impostato su true, le risorse dei font saranno sempre incorporate.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| embedFontResources | booleano |  |

