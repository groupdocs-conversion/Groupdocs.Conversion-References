---
title: "CadLoadOptions"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Alternativ för inläsning av CAD-dokument."
type: docs
weight: 12
url: /sv/java/com.groupdocs.conversion.options.load/cadloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CadLoadOptions extends LoadOptions implements Serializable
```

Alternativ för inläsning av CAD-dokument.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [CadLoadOptions()](#CadLoadOptions--) | Initierar en ny instans av klassen [CadLoadOptions](../../com.groupdocs.conversion.options.load/cadloadoptions). |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getLayoutNames()](#getLayoutNames--) | Anger vilka CAD-layouter som ska konverteras |
|
|  | [setLayoutNames(String[] value)](#setLayoutNames-java.lang.String---) | Anger vilka CAD-layouter som ska konverteras |
|
|  | [getDrawType()](#getDrawType--) | Hämtar typ av ritning. |
|
|  | [setDrawType(CadDrawTypeMode drawType)](#setDrawType-com.groupdocs.conversion.options.load.CadDrawTypeMode-) | Ställer in typ av ritning. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Hämtar en bakgrundsfärg. |
|
|  | [setBackgroundColor(System.Drawing.Color backgroundColor)](#setBackgroundColor-com.aspose.ms.System.Drawing.Color-) | Ställer in en bakgrundsfärg. |
|
| [getFontDirectories()](#getFontDirectories--) |  |
| [setFontDirectories(List<String> fontDirectories)](#setFontDirectories-java.util.List-java.lang.String--) |  |
|  | [getCtbSources()](#getCtbSources--) | Hämtar CTB-källorna. |
|
|  | [setCtbSources(Map<String,InputStream> ctbSources)](#setCtbSources-java.util.Map-java.lang.String-java.io.InputStream--) | Ställer in CTB-källorna. |
|
|  | [getDrawColor()](#getDrawColor--) | Hämtar förgrundsfärg. |
|
|  | [setDrawColor(System.Drawing.Color drawColor)](#setDrawColor-com.aspose.ms.System.Drawing.Color-) | Ställer in förgrundsfärg. |
|
### CadLoadOptions() {#CadLoadOptions--}
```
public CadLoadOptions()
```


Initierar en ny instans av klassen [CadLoadOptions](../../com.groupdocs.conversion.options.load/cadloadoptions).


### getFormat() {#getFormat--}
```
public CadFileType getFormat()
```


Dokumentfiltyp för inmatning


**Returns:**
[CadFileType](../../com.groupdocs.conversion.filetypes/cadfiletype)
### getLayoutNames() {#getLayoutNames--}
```
public final String[] getLayoutNames()
```


Anger vilka CAD-layouter som ska konverteras


**Returns:**
java.lang.String[]
### setLayoutNames(String[] value) {#setLayoutNames-java.lang.String---}
```
public final void setLayoutNames(String[] value)
```


Anger vilka CAD-layouter som ska konverteras


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String[] |  |

### getDrawType() {#getDrawType--}
```
public CadDrawTypeMode getDrawType()
```


Hämtar typ av ritning.


**Returns:**
[CadDrawTypeMode](../../com.groupdocs.conversion.options.load/caddrawtypemode)
### setDrawType(CadDrawTypeMode drawType) {#setDrawType-com.groupdocs.conversion.options.load.CadDrawTypeMode-}
```
public void setDrawType(CadDrawTypeMode drawType)
```


Ställer in typ av ritning.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| drawType | [CadDrawTypeMode](../../com.groupdocs.conversion.options.load/caddrawtypemode) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public System.Drawing.Color getBackgroundColor()
```


Hämtar en bakgrundsfärg.


**Returns:**
com.aspose.ms.System.Drawing.Color
### setBackgroundColor(System.Drawing.Color backgroundColor) {#setBackgroundColor-com.aspose.ms.System.Drawing.Color-}
```
public void setBackgroundColor(System.Drawing.Color backgroundColor)
```


Ställer in en bakgrundsfärg.


**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontDirectories | java.util.List<java.lang.String> |  |

### getCtbSources() {#getCtbSources--}
```
public Map<String,InputStream> getCtbSources()
```


Hämtar CTB-källorna.


**Returns:**
java.util.Map<java.lang.String,java.io.InputStream>
### setCtbSources(Map<String,InputStream> ctbSources) {#setCtbSources-java.util.Map-java.lang.String-java.io.InputStream--}
```
public void setCtbSources(Map<String,InputStream> ctbSources)
```


Ställer in CTB-källorna.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ctbSources | java.util.Map<java.lang.String,java.io.InputStream> |  |

### getDrawColor() {#getDrawColor--}
```
public System.Drawing.Color getDrawColor()
```


Hämtar förgrundsfärg.


**Returns:**
com.aspose.ms.System.Drawing.Color
### setDrawColor(System.Drawing.Color drawColor) {#setDrawColor-com.aspose.ms.System.Drawing.Color-}
```
public void setDrawColor(System.Drawing.Color drawColor)
```


Ställer in förgrundsfärg.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| drawColor | com.aspose.ms.System.Drawing.Color |  |

