---
title: "PersonalStorageLoadOptions"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Opties voor het laden van personal storage-documenten."
type: docs
weight: 32
url: /nl/nodejs-java/com.groupdocs.conversion.options.load/personalstorageloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class PersonalStorageLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Opties voor het laden van personal storage-documenten.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PersonalStorageLoadOptions()](#PersonalStorageLoadOptions--) | Initialiseert een nieuw exemplaar van de class. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFolder()](#getFolder--) | Map die verwerkt moet worden Standaard is Inbox |
| [setFolder(String folder)](#setFolder-java.lang.String-) | Stel map in die verwerkt moet worden |
| [isConvertOwner()](#isConvertOwner--) | \{@inheritDoc\} De eigenaar wordt niet geconverteerd |
| [isConvertOwned()](#isConvertOwned--) | \{@inheritDoc\} |
| [getDepth()](#getDepth--) | \{@inheritDoc\} |
| [setDepth(int depth)](#setDepth-int-) | \{@inheritDoc\} |
### PersonalStorageLoadOptions() {#PersonalStorageLoadOptions--}
```
public PersonalStorageLoadOptions()
```


Initialiseert een nieuw exemplaar van de class.

### getFolder() {#getFolder--}
```
public String getFolder()
```


Map die verwerkt moet worden Standaard is Inbox

**Returns:**
java.lang.String - Map die verwerkt moet worden
### setFolder(String folder) {#setFolder-java.lang.String-}
```
public void setFolder(String folder)
```


Stel map in die verwerkt moet worden

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| map | java.lang.String | map |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Haalt optie op om te bepalen of de documentencontainer zelf moet worden geconverteerd De eigenaar wordt niet geconverteerd

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


Optie om te bepalen hoeveel niveaus diep de conversie moet worden uitgevoerd

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

