---
title: "NsfLoadOptions"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Alternativ för att läsa in Nsf-dokument."
type: docs
weight: 25
url: /sv/java/com.groupdocs.conversion.options.load/nsfloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class NsfLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Alternativ för att läsa in Nsf-dokument.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [NsfLoadOptions()](#NsfLoadOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isConvertOwner()](#isConvertOwner--) |  |
|  | [isConvertOwned()](#isConvertOwned--) | {@inheritDoc} |
|
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
### NsfLoadOptions() {#NsfLoadOptions--}
```
public NsfLoadOptions()
```


### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Hämtar alternativ för att styra om dokumentbehållaren själv måste konverteras


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


Alternativ för att styra hur många nivåer i djupet konverteringen ska utföras


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| depth | int |  |

