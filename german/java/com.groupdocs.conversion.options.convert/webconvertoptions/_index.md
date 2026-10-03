---
title: "WebConvertOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Optionen für die Konvertierung zum Web-Dateityp."
type: docs
weight: 46
url: /de/java/com.groupdocs.conversion.options.convert/webconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions
```
public class WebConvertOptions extends CommonConvertOptions<WebFileType>
```

Optionen für die Konvertierung zum Web-Dateityp.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [WebConvertOptions()](#WebConvertOptions--) | Initialisiert eine neue Instanz der Klasse. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isUsePdf()](#isUsePdf--) |  |
| [setUsePdf(boolean usePdf)](#setUsePdf-boolean-) |  |
| [isFixedLayout()](#isFixedLayout--) |  |
| [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) |  |
| [isFixedLayoutShowBorders()](#isFixedLayoutShowBorders--) |  |
| [setFixedLayoutShowBorders(boolean fixedLayoutShowBorders)](#setFixedLayoutShowBorders-boolean-) |  |
| [getZoom()](#getZoom--) |  |
| [setZoom(int zoom)](#setZoom-int-) |  |
|  | [isEmbedFontResources()](#isEmbedFontResources--) | Gibt an, ob Schriftartressourcen in das Haupt‑HTML eingebettet werden sollen. |
|
|  | [setEmbedFontResources(boolean embedFontResources)](#setEmbedFontResources-boolean-) | Gibt an, ob Schriftartressourcen in das Haupt‑HTML eingebettet werden sollen. |
|
### WebConvertOptions() {#WebConvertOptions--}
```
public WebConvertOptions()
```


Initialisiert eine neue Instanz der Klasse.


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
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| zoom | int |  |

### isEmbedFontResources() {#isEmbedFontResources--}
```
public boolean isEmbedFontResources()
```


Gibt an, ob Schriftartressourcen in das Haupt‑HTML eingebettet werden sollen. Standard ist false. Hinweis: Wenn FixedLayout auf true gesetzt ist, werden Schriftartressourcen immer eingebettet.


**Returns:**
boolean
### setEmbedFontResources(boolean embedFontResources) {#setEmbedFontResources-boolean-}
```
public void setEmbedFontResources(boolean embedFontResources)
```


Gibt an, ob Schriftartressourcen in das Haupt‑HTML eingebettet werden sollen. Standard ist false. Hinweis: Wenn FixedLayout auf true gesetzt ist, werden Schriftartressourcen immer eingebettet.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| embedFontResources | boolean |  |

