---
title: "PersonalStorageLoadOptions"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Opties voor het laden van persoonlijke‑opslag‑documenten."
type: docs
weight: 28
url: /nl/java/com.groupdocs.conversion.options.load/personalstorageloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class PersonalStorageLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Opties voor het laden van persoonlijke‑opslag‑documenten.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [PersonalStorageLoadOptions()](#PersonalStorageLoadOptions--) | Initialiseert een nieuwe instantie van de klasse. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getFolder()](#getFolder--) | Map die moet worden verwerkt Standaard is Inbox |
|
|  | [setFolder(String folder)](#setFolder-java.lang.String-) | Stel de map in die moet worden verwerkt |
|
|  | [isConvertOwner()](#isConvertOwner--) | {@inheritDoc} De eigenaar wordt niet geconverteerd |
|
|  | [isConvertOwned()](#isConvertOwned--) | {@inheritDoc} |
|
|  | [getDepth()](#getDepth--) | {@inheritDoc} |
|
|  | [setDepth(int depth)](#setDepth-int-) | {@inheritDoc} |
|
### PersonalStorageLoadOptions() {#PersonalStorageLoadOptions--}
```
public PersonalStorageLoadOptions()
```


Initialiseert een nieuwe instantie van de klasse.


### getFolder() {#getFolder--}
```
public String getFolder()
```


Map die moet worden verwerkt Standaard is Inbox


**Returns:**
java.lang.String - Map die moet worden verwerkt

### setFolder(String folder) {#setFolder-java.lang.String-}
```
public void setFolder(String folder)
```


Stel de map in die moet worden verwerkt


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | map | java.lang.String | map |
|

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

