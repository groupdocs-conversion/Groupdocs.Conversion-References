---
title: "CadLoadOptions"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Opties voor het laden van CAD-documenten."
type: docs
weight: 12
url: /nl/nodejs-java/com.groupdocs.conversion.options.load/cadloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CadLoadOptions extends LoadOptions implements Serializable
```

Opties voor het laden van CAD-documenten.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [CadLoadOptions()](#CadLoadOptions--) | Initialiseert een nieuw exemplaar van de klasse [CadLoadOptions](../../com.groupdocs.conversion.options.load/cadloadoptions). |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getWidth()](#getWidth--) | Stelt de gewenste paginabreedte in voor het converteren van een CAD-document. |
| [setWidth(int value)](#setWidth-int-) | Stelt de gewenste paginabreedte in voor het converteren van een CAD-document. |
| [getHeight()](#getHeight--) | Stelt de gewenste paginahoogte in voor het converteren van een CAD-document. |
| [setHeight(int value)](#setHeight-int-) | Stelt de gewenste paginahoogte in voor het converteren van een CAD-document. |
| [getLayoutNames()](#getLayoutNames--) | Specificeert welke CAD-indelingen moeten worden geconverteerd. |
| [setLayoutNames(String[] value)](#setLayoutNames-java.lang.String---) | Specificeert welke CAD-indelingen moeten worden geconverteerd. |
| [getDrawType()](#getDrawType--) | Haalt het type tekening op. |
| [setDrawType(CadDrawTypeMode drawType)](#setDrawType-com.groupdocs.conversion.options.load.CadDrawTypeMode-) | Stelt het type tekening in. |
| [getBackgroundColor()](#getBackgroundColor--) | Haalt een achtergrondkleur op. |
| [setBackgroundColor(System.Drawing.Color backgroundColor)](#setBackgroundColor-com.aspose.ms.System.Drawing.Color-) | Stelt een achtergrondkleur in. |
| [getFontDirectories()](#getFontDirectories--) |  |
| [setFontDirectories(List<String> fontDirectories)](#setFontDirectories-java.util.List-java.lang.String--) |  |
### CadLoadOptions() {#CadLoadOptions--}
```
public CadLoadOptions()
```


Initialiseert een nieuw exemplaar van de klasse [CadLoadOptions](../../com.groupdocs.conversion.options.load/cadloadoptions).

### getFormat() {#getFormat--}
```
public CadFileType getFormat()
```


Bestandstype van invoerdocument

**Returns:**
[CadFileType](../../com.groupdocs.conversion.filetypes/cadfiletype)
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Stelt de gewenste paginabreedte in voor het converteren van een CAD-document.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Stelt de gewenste paginabreedte in voor het converteren van een CAD-document.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Stelt de gewenste paginahoogte in voor het converteren van een CAD-document.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Stelt de gewenste paginahoogte in voor het converteren van een CAD-document.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getLayoutNames() {#getLayoutNames--}
```
public final String[] getLayoutNames()
```


Specificeert welke CAD-indelingen moeten worden geconverteerd.

**Returns:**
java.lang.String[]
### setLayoutNames(String[] value) {#setLayoutNames-java.lang.String---}
```
public final void setLayoutNames(String[] value)
```


Specificeert welke CAD-indelingen moeten worden geconverteerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getDrawType() {#getDrawType--}
```
public CadDrawTypeMode getDrawType()
```


Haalt het type tekening op.

**Returns:**
[CadDrawTypeMode](../../com.groupdocs.conversion.options.load/caddrawtypemode)
### setDrawType(CadDrawTypeMode drawType) {#setDrawType-com.groupdocs.conversion.options.load.CadDrawTypeMode-}
```
public void setDrawType(CadDrawTypeMode drawType)
```


Stelt het type tekening in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| drawType | [CadDrawTypeMode](../../com.groupdocs.conversion.options.load/caddrawtypemode) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public System.Drawing.Color getBackgroundColor()
```


Haalt een achtergrondkleur op.

**Returns:**
com.aspose.ms.System.Drawing.Color
### setBackgroundColor(System.Drawing.Color backgroundColor) {#setBackgroundColor-com.aspose.ms.System.Drawing.Color-}
```
public void setBackgroundColor(System.Drawing.Color backgroundColor)
```


Stelt een achtergrondkleur in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| backgroundColor | com.aspose.ms.System.Drawing.Color |  |

### getFontDirectories() {#getFontDirectories--}
```
public List<String> getFontDirectories()
```




**Returns:**
java.util.List<java.lang.String>
### setFontDirectories(List<String> fontDirectories) {#setFontDirectories-java.util.List-java.lang.String--}
```
public void setFontDirectories(List<String> fontDirectories)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontDirectories | java.util.List<java.lang.String> |  |

