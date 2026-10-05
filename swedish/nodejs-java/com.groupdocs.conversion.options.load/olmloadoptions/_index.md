---
title: "OlmLoadOptions"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Alternativ för att ladda Olm-dokument."
type: docs
weight: 29
url: /sv/nodejs-java/com.groupdocs.conversion.options.load/olmloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions), java.lang.Cloneable, java.io.Serializable
```
public final class OlmLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions, Cloneable, Serializable
```

Alternativ för att ladda Olm-dokument.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [OlmLoadOptions()](#OlmLoadOptions--) | Initierar en ny instans av klassen [OlmLoadOptions](../../com.groupdocs.conversion.options.load/olmloadoptions). |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [folder](#folder) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [memberwiseClone()](#memberwiseClone--) |  |
| [isConvertOwner()](#isConvertOwner--) | Ägaren kommer inte att konverteras |
| [isConvertOwned()](#isConvertOwned--) | \\{@inheritDoc\\} |
| [getFolder()](#getFolder--) | Mapp som ska bearbetas Standard är Inkorg |
| [setFolder(String folder)](#setFolder-java.lang.String-) |  |
| [getDepth()](#getDepth--) | \{@inheritDoc\} Default: 3 |
| [setDepth(int depth)](#setDepth-int-) |  |
| [deepClone()](#deepClone--) | Klonar aktuell instans. |
### OlmLoadOptions() {#OlmLoadOptions--}
```
public OlmLoadOptions()
```


Initierar en ny instans av klassen [OlmLoadOptions](../../com.groupdocs.conversion.options.load/olmloadoptions).

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
### getFolder() {#getFolder--}
```
public String getFolder()
```


Mapp som ska bearbetas Standard är Inkorg

**Returns:**
java.lang.String
### setFolder(String folder) {#setFolder-java.lang.String-}
```
public void setFolder(String folder)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mapp | java.lang.String |  |

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

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Klonar aktuell instans.

**Returns:**
java.lang.Object
