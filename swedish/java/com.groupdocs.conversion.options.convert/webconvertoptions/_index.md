---
title: "WebConvertOptions"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Alternativ för konvertering till Web-filtyp."
type: docs
weight: 46
url: /sv/java/com.groupdocs.conversion.options.convert/webconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions
```
public class WebConvertOptions extends CommonConvertOptions<WebFileType>
```

Alternativ för konvertering till Web-filtyp.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [WebConvertOptions()](#WebConvertOptions--) | Initierar en ny instans av klassen. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isUsePdf()](#isUsePdf--) |  |
| [setUsePdf(boolean usePdf)](#setUsePdf-boolean-) |  |
| [isFixedLayout()](#isFixedLayout--) |  |
| [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) |  |
| [isFixedLayoutShowBorders()](#isFixedLayoutShowBorders--) |  |
| [setFixedLayoutShowBorders(boolean fixedLayoutShowBorders)](#setFixedLayoutShowBorders-boolean-) |  |
| [getZoom()](#getZoom--) |  |
| [setZoom(int zoom)](#setZoom-int-) |  |
|  | [isEmbedFontResources()](#isEmbedFontResources--) | Anger om teckensnittresurser ska bäddas in i huvud‑HTML. |
|
|  | [setEmbedFontResources(boolean embedFontResources)](#setEmbedFontResources-boolean-) | Anger om teckensnittresurser ska bäddas in i huvud‑HTML. |
|
### WebConvertOptions() {#WebConvertOptions--}
```
public WebConvertOptions()
```


Initierar en ny instans av klassen.


### isUsePdf() {#isUsePdf--}
```
public boolean isUsePdf()
```




**Returns:**
boolean
### setUsePdf(boolean usePdf) {#setUsePdf-boolean-}
```
public void setUsePdf(boolean usePdf)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| usePdf | boolean |  |

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```




**Returns:**
boolean
### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fixedLayout | boolean |  |

### isFixedLayoutShowBorders() {#isFixedLayoutShowBorders--}
```
public boolean isFixedLayoutShowBorders()
```




**Returns:**
boolean
### setFixedLayoutShowBorders(boolean fixedLayoutShowBorders) {#setFixedLayoutShowBorders-boolean-}
```
public void setFixedLayoutShowBorders(boolean fixedLayoutShowBorders)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fixedLayoutShowBorders | boolean |  |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| zoom | int |  |

### isEmbedFontResources() {#isEmbedFontResources--}
```
public boolean isEmbedFontResources()
```


Anger om teckensnittresurser ska bäddas in i huvud‑HTML. Standard är falskt. Obs: Om FixedLayout är satt till true kommer teckensnittresurser alltid att bäddas in.


**Returns:**
boolean
### setEmbedFontResources(boolean embedFontResources) {#setEmbedFontResources-boolean-}
```
public void setEmbedFontResources(boolean embedFontResources)
```


Anger om teckensnittresurser ska bäddas in i huvud‑HTML. Standard är falskt. Obs: Om FixedLayout är satt till true kommer teckensnittresurser alltid att bäddas in.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| embedFontResources | boolean |  |

