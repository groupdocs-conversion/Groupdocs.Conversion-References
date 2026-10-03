---
title: "DiagramLoadOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Optionen zum Laden von Diagrammdokumenten."
type: docs
weight: 15
url: /de/java/com.groupdocs.conversion.options.load/diagramloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DiagramLoadOptions extends LoadOptions implements Serializable
```

Optionen zum Laden von Diagrammdokumenten.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [DiagramLoadOptions()](#DiagramLoadOptions--) | Initialisiert eine neue Instanz der Klasse [DiagramLoadOptions](../../com.groupdocs.conversion.options.load/diagramloadoptions). |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Standard‑Schriftart für Diagrammdokument. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Standard‑Schriftart für Diagrammdokument. |
|
### DiagramLoadOptions() {#DiagramLoadOptions--}
```
public DiagramLoadOptions()
```


Initialisiert eine neue Instanz der Klasse [DiagramLoadOptions](../../com.groupdocs.conversion.options.load/diagramloadoptions).


### getFormat() {#getFormat--}
```
public final DiagramFileType getFormat()
```


Eingabedokument-Dateityp


**Returns:**
[DiagramFileType](../../com.groupdocs.conversion.filetypes/diagramfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Standard‑Schriftart für Diagrammdokument. Die folgende Schriftart wird verwendet, wenn eine Schriftart fehlt.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Standard‑Schriftart für Diagrammdokument. Die folgende Schriftart wird verwendet, wenn eine Schriftart fehlt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

