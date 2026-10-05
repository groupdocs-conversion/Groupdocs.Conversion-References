---
title: "DiagramLoadOptions"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Opties voor het laden van Diagram-documenten."
type: docs
weight: 16
url: /nl/nodejs-java/com.groupdocs.conversion.options.load/diagramloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DiagramLoadOptions extends LoadOptions implements Serializable
```

Opties voor het laden van Diagram-documenten.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [DiagramLoadOptions()](#DiagramLoadOptions--) | Initialiseert een nieuw exemplaar van de klasse [DiagramLoadOptions](../../com.groupdocs.conversion.options.load/diagramloadoptions). |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getDefaultFont()](#getDefaultFont--) | Standaardlettertype voor Diagram-document. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Standaardlettertype voor Diagram-document. |
### DiagramLoadOptions() {#DiagramLoadOptions--}
```
public DiagramLoadOptions()
```


Initialiseert een nieuw exemplaar van de klasse [DiagramLoadOptions](../../com.groupdocs.conversion.options.load/diagramloadoptions).

### getFormat() {#getFormat--}
```
public final DiagramFileType getFormat()
```


Bestandstype van invoerdocument

**Returns:**
[DiagramFileType](../../com.groupdocs.conversion.filetypes/diagramfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Standaardlettertype voor Diagram-document. Het volgende lettertype wordt gebruikt als een lettertype ontbreekt.

**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Standaardlettertype voor Diagram-document. Het volgende lettertype wordt gebruikt als een lettertype ontbreekt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

