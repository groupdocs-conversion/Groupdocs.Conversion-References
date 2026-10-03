---
title: "CadLoadOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Optionen zum Laden von CAD-Dokumenten."
type: docs
weight: 12
url: /de/java/com.groupdocs.conversion.options.load/cadloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CadLoadOptions extends LoadOptions implements Serializable
```

Optionen zum Laden von CAD-Dokumenten.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [CadLoadOptions()](#CadLoadOptions--) | Initialisiert eine neue Instanz der Klasse [CadLoadOptions](../../com.groupdocs.conversion.options.load/cadloadoptions). |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getLayoutNames()](#getLayoutNames--) | Gibt an, welche CAD‑Layouts konvertiert werden sollen |
|
|  | [setLayoutNames(String[] value)](#setLayoutNames-java.lang.String---) | Gibt an, welche CAD‑Layouts konvertiert werden sollen |
|
|  | [getDrawType()](#getDrawType--) | Ruft den Zeichnungstyp ab. |
|
|  | [setDrawType(CadDrawTypeMode drawType)](#setDrawType-com.groupdocs.conversion.options.load.CadDrawTypeMode-) | Setzt den Zeichnungstyp. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Ruft eine Hintergrundfarbe ab. |
|
|  | [setBackgroundColor(System.Drawing.Color backgroundColor)](#setBackgroundColor-com.aspose.ms.System.Drawing.Color-) | Setzt eine Hintergrundfarbe. |
|
| [getFontDirectories()](#getFontDirectories--) |  |
| [setFontDirectories(List<String> fontDirectories)](#setFontDirectories-java.util.List-java.lang.String--) |  |
|  | [getCtbSources()](#getCtbSources--) | Liest die CTB-Quellen. |
|
|  | [setCtbSources(Map<String,InputStream> ctbSources)](#setCtbSources-java.util.Map-java.lang.String-java.io.InputStream--) | Setzt die CTB-Quellen. |
|
|  | [getDrawColor()](#getDrawColor--) | Liest die Vordergrundfarbe. |
|
|  | [setDrawColor(System.Drawing.Color drawColor)](#setDrawColor-com.aspose.ms.System.Drawing.Color-) | Setzt die Vordergrundfarbe. |
|
### CadLoadOptions() {#CadLoadOptions--}
```
public CadLoadOptions()
```


Initialisiert eine neue Instanz der Klasse [CadLoadOptions](../../com.groupdocs.conversion.options.load/cadloadoptions).


### getFormat() {#getFormat--}
```
public CadFileType getFormat()
```


Eingabedokument-Dateityp


**Returns:**
[CadFileType](../../com.groupdocs.conversion.filetypes/cadfiletype)
### getLayoutNames() {#getLayoutNames--}
```
public final String[] getLayoutNames()
```


Gibt an, welche CAD‑Layouts konvertiert werden sollen


**Returns:**
java.lang.String[]
### setLayoutNames(String[] value) {#setLayoutNames-java.lang.String---}
```
public final void setLayoutNames(String[] value)
```


Gibt an, welche CAD‑Layouts konvertiert werden sollen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String[] |  |

### getDrawType() {#getDrawType--}
```
public CadDrawTypeMode getDrawType()
```


Ruft den Zeichnungstyp ab.


**Returns:**
[CadDrawTypeMode](../../com.groupdocs.conversion.options.load/caddrawtypemode)
### setDrawType(CadDrawTypeMode drawType) {#setDrawType-com.groupdocs.conversion.options.load.CadDrawTypeMode-}
```
public void setDrawType(CadDrawTypeMode drawType)
```


Setzt den Zeichnungstyp.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| drawType | [CadDrawTypeMode](../../com.groupdocs.conversion.options.load/caddrawtypemode) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public System.Drawing.Color getBackgroundColor()
```


Ruft eine Hintergrundfarbe ab.


**Returns:**
com.aspose.ms.System.Drawing.Color
### setBackgroundColor(System.Drawing.Color backgroundColor) {#setBackgroundColor-com.aspose.ms.System.Drawing.Color-}
```
public void setBackgroundColor(System.Drawing.Color backgroundColor)
```


Setzt eine Hintergrundfarbe.


**Parameters:**
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontDirectories | java.util.List<java.lang.String> |  |

### getCtbSources() {#getCtbSources--}
```
public Map<String,InputStream> getCtbSources()
```


Liest die CTB-Quellen.


**Returns:**
java.util.Map<java.lang.String,java.io.InputStream>
### setCtbSources(Map<String,InputStream> ctbSources) {#setCtbSources-java.util.Map-java.lang.String-java.io.InputStream--}
```
public void setCtbSources(Map<String,InputStream> ctbSources)
```


Setzt die CTB-Quellen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ctbSources | java.util.Map<java.lang.String,java.io.InputStream> |  |

### getDrawColor() {#getDrawColor--}
```
public System.Drawing.Color getDrawColor()
```


Liest die Vordergrundfarbe.


**Returns:**
com.aspose.ms.System.Drawing.Color
### setDrawColor(System.Drawing.Color drawColor) {#setDrawColor-com.aspose.ms.System.Drawing.Color-}
```
public void setDrawColor(System.Drawing.Color drawColor)
```


Setzt die Vordergrundfarbe.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| drawColor | com.aspose.ms.System.Drawing.Color |  |

