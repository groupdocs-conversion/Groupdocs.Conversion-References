---
title: "DiagramLoadOptions"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Alternativ för inläsning av Diagram-dokument."
type: docs
weight: 16
url: /sv/nodejs-java/com.groupdocs.conversion.options.load/diagramloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DiagramLoadOptions extends LoadOptions implements Serializable
```

Alternativ för inläsning av Diagram-dokument.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [DiagramLoadOptions()](#DiagramLoadOptions--) | Initierar en ny instans av klassen [DiagramLoadOptions](../../com.groupdocs.conversion.options.load/diagramloadoptions). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getDefaultFont()](#getDefaultFont--) | Standardteckensnitt för Diagram-dokument. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Standardteckensnitt för Diagram-dokument. |
### DiagramLoadOptions() {#DiagramLoadOptions--}
```
public DiagramLoadOptions()
```


Initierar en ny instans av klassen [DiagramLoadOptions](../../com.groupdocs.conversion.options.load/diagramloadoptions).

### getFormat() {#getFormat--}
```
public final DiagramFileType getFormat()
```


Inmatningsdokumentets filtyp

**Returns:**
[DiagramFileType](../../com.groupdocs.conversion.filetypes/diagramfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Standardteckensnitt för Diagram-dokument. Följande teckensnitt kommer att användas om ett teckensnitt saknas.

**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Standardteckensnitt för Diagram-dokument. Följande teckensnitt kommer att användas om ett teckensnitt saknas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

