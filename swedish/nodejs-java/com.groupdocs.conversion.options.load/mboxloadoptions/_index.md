---
title: "MboxLoadOptions"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Alternativ för inläsning av Mbox-dokument"
type: docs
weight: 26
url: /sv/nodejs-java/com.groupdocs.conversion.options.load/mboxloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class MboxLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Alternativ för inläsning av Mbox-dokument
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MboxLoadOptions()](#MboxLoadOptions--) | Initierar en ny instans av  klassen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isConvertOwner()](#isConvertOwner--) | Ägaren kommer inte att konverteras |
| [isConvertOwned()](#isConvertOwned--) | \\{@inheritDoc\\} |
| [getDepth()](#getDepth--) | \{@inheritDoc\} Default: 3 |
| [setDepth(int depth)](#setDepth-int-) | \\{@inheritDoc\\} |
| [getEqualityComponents()](#getEqualityComponents--) | \\{@inheritDoc\\} |
### MboxLoadOptions() {#MboxLoadOptions--}
```
public MboxLoadOptions()
```


Initierar en ny instans av  klassen.

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Ägaren kommer inte att konverteras

**Returns:**
boolean
### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Alternativ för att styra om de ägda dokumenten i dokumentbehållaren måste konverteras

**Returns:**
boolean
### getDepth() {#getDepth--}
```
public int getDepth()
```


Alternativ för att styra hur många nivåer i djupet konverteringen ska utföras. Standard: 3

**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| djup | int |  |

### getEqualityComponents() {#getEqualityComponents--}
```
public List<Object> getEqualityComponents()
```




**Returns:**
java.util.List<java.lang.Object>
