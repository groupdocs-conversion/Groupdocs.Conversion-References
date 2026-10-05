---
title: "OlmLoadOptions"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Opties voor het laden van Olm-documenten."
type: docs
weight: 29
url: /nl/nodejs-java/com.groupdocs.conversion.options.load/olmloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions), java.lang.Cloneable, java.io.Serializable
```
public final class OlmLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions, Cloneable, Serializable
```

Opties voor het laden van Olm-documenten.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [OlmLoadOptions()](#OlmLoadOptions--) | Initialiseert een nieuwe instantie van de [OlmLoadOptions](../../com.groupdocs.conversion.options.load/olmloadoptions) klasse. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [folder](#folder) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [memberwiseClone()](#memberwiseClone--) |  |
| [isConvertOwner()](#isConvertOwner--) | De eigenaar wordt niet geconverteerd |
| [isConvertOwned()](#isConvertOwned--) | \{@inheritDoc\} |
| [getFolder()](#getFolder--) | Map die verwerkt moet worden Standaard is Inbox |
| [setFolder(String folder)](#setFolder-java.lang.String-) |  |
| [getDepth()](#getDepth--) | \{@inheritDoc\} Default: 3 |
| [setDepth(int depth)](#setDepth-int-) |  |
| [deepClone()](#deepClone--) | Kloont huidige instantie. |
### OlmLoadOptions() {#OlmLoadOptions--}
```
public OlmLoadOptions()
```


Initialiseert een nieuwe instantie van de [OlmLoadOptions](../../com.groupdocs.conversion.options.load/olmloadoptions) klasse.

### folder {#folder}
```
public String folder
```


### memberwiseClone() {#memberwiseClone--}
```
public Object memberwiseClone()
```




**Returns:**
java.lang.Object
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
### getFolder() {#getFolder--}
```
public String getFolder()
```


Map die verwerkt moet worden Standaard is Inbox

**Returns:**
java.lang.String
### setFolder(String folder) {#setFolder-java.lang.String-}
```
public void setFolder(String folder)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| map | java.lang.String |  |

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

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Kloont huidige instantie.

**Returns:**
java.lang.Object
