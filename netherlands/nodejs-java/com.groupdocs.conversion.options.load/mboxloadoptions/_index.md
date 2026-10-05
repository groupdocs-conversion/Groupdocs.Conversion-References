---
title: "MboxLoadOptions"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Opties voor het laden van Mbox-documenten"
type: docs
weight: 26
url: /nl/nodejs-java/com.groupdocs.conversion.options.load/mboxloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class MboxLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Opties voor het laden van Mbox-documenten
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [MboxLoadOptions()](#MboxLoadOptions--) | Initialiseert een nieuw exemplaar van de class. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [isConvertOwner()](#isConvertOwner--) | De eigenaar wordt niet geconverteerd |
| [isConvertOwned()](#isConvertOwned--) | \{@inheritDoc\} |
| [getDepth()](#getDepth--) | \{@inheritDoc\} Default: 3 |
| [setDepth(int depth)](#setDepth-int-) | \{@inheritDoc\} |
| [getEqualityComponents()](#getEqualityComponents--) | \{@inheritDoc\} |
### MboxLoadOptions() {#MboxLoadOptions--}
```
public MboxLoadOptions()
```


Initialiseert een nieuw exemplaar van de class.

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


De eigenaar wordt niet geconverteerd

**Returns:**
boolean
### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Optie om te bepalen of de eigendomdocumenten in de documentcontainer moeten worden geconverteerd

**Returns:**
boolean
### getDepth() {#getDepth--}
```
public int getDepth()
```


Optie om te bepalen hoeveel niveaus diep de conversie moet worden uitgevoerd. Standaard: 3

**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| diepte | int |  |

### getEqualityComponents() {#getEqualityComponents--}
```
public List<Object> getEqualityComponents()
```




**Returns:**
java.util.List<java.lang.Object>
