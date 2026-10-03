---
title: "NsfLoadOptions"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Opties voor het laden van Nsf‑documenten."
type: docs
weight: 25
url: /nl/java/com.groupdocs.conversion.options.load/nsfloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class NsfLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Opties voor het laden van Nsf‑documenten.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [NsfLoadOptions()](#NsfLoadOptions--) |  |
## Methoden

| Methode | Beschrijving |
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


Krijgt optie om te bepalen of de container van het document zelf moet worden geconverteerd


**Returns:**
boolean
### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Optie om te bepalen of de eigendom documenten in de documentencontainer moeten worden geconverteerd


**Returns:**
boolean
### getDepth() {#getDepth--}
```
public int getDepth()
```


Optie om te bepalen hoeveel niveaus in diepte de conversie moet uitvoeren


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| depth | int |  |

