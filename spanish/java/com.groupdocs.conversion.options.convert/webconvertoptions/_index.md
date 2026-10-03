---
title: "WebConvertOptions"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Opciones para la conversión al tipo de archivo Web."
type: docs
weight: 46
url: /es/java/com.groupdocs.conversion.options.convert/webconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions
```
public class WebConvertOptions extends CommonConvertOptions<WebFileType>
```

Opciones para la conversión al tipo de archivo Web.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [WebConvertOptions()](#WebConvertOptions--) | Inicializa una nueva instancia de la clase. |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [isUsePdf()](#isUsePdf--) |  |
| [setUsePdf(boolean usePdf)](#setUsePdf-boolean-) |  |
| [isFixedLayout()](#isFixedLayout--) |  |
| [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) |  |
| [isFixedLayoutShowBorders()](#isFixedLayoutShowBorders--) |  |
| [setFixedLayoutShowBorders(boolean fixedLayoutShowBorders)](#setFixedLayoutShowBorders-boolean-) |  |
| [getZoom()](#getZoom--) |  |
| [setZoom(int zoom)](#setZoom-int-) |  |
|  | [isEmbedFontResources()](#isEmbedFontResources--) | Especifica si se deben incrustar los recursos de fuentes dentro del HTML principal. |
|
|  | [setEmbedFontResources(boolean embedFontResources)](#setEmbedFontResources-boolean-) | Especifica si se deben incrustar los recursos de fuentes dentro del HTML principal. |
|
### WebConvertOptions() {#WebConvertOptions--}
```
public WebConvertOptions()
```


Inicializa una nueva instancia de la clase.


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
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| zoom | int |  |

### isEmbedFontResources() {#isEmbedFontResources--}
```
public boolean isEmbedFontResources()
```


Especifica si se deben incrustar los recursos de fuentes dentro del HTML principal. El valor predeterminado es false. Nota: Si FixedLayout está configurado en true, los recursos de fuentes siempre se incrustarán.


**Returns:**
booleano
### setEmbedFontResources(boolean embedFontResources) {#setEmbedFontResources-boolean-}
```
public void setEmbedFontResources(boolean embedFontResources)
```


Especifica si se deben incrustar los recursos de fuentes dentro del HTML principal. El valor predeterminado es false. Nota: Si FixedLayout está configurado en true, los recursos de fuentes siempre se incrustarán.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| embedFontResources | booleano |  |

