---
title: "PersonalStorageLoadOptions"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Alternativ för att ladda personliga lagringsdokument."
type: docs
weight: 32
url: /sv/nodejs-java/com.groupdocs.conversion.options.load/personalstorageloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class PersonalStorageLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Alternativ för att ladda personliga lagringsdokument.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PersonalStorageLoadOptions()](#PersonalStorageLoadOptions--) | Initierar en ny instans av  klassen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFolder()](#getFolder--) | Mapp som ska bearbetas Standard är Inkorg |
| [setFolder(String folder)](#setFolder-java.lang.String-) | Ange mapp som ska bearbetas |
| [isConvertOwner()](#isConvertOwner--) | \{@inheritDoc\} Ägaren kommer inte att konverteras |
| [isConvertOwned()](#isConvertOwned--) | \\{@inheritDoc\\} |
| [getDepth()](#getDepth--) | \\{@inheritDoc\\} |
| [setDepth(int depth)](#setDepth-int-) | \\{@inheritDoc\\} |
### PersonalStorageLoadOptions() {#PersonalStorageLoadOptions--}
```
public PersonalStorageLoadOptions()
```


Initierar en ny instans av  klassen.

### getFolder() {#getFolder--}
```
public String getFolder()
```


Mapp som ska bearbetas Standard är Inkorg

**Returns:**
java.lang.String - Mapp som ska bearbetas
### setFolder(String folder) {#setFolder-java.lang.String-}
```
public void setFolder(String folder)
```


Ange mapp som ska bearbetas

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mapp | java.lang.String | mapp |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Hämtar alternativ för att styra om dokumentbehållaren själv måste konverteras. Ägaren kommer inte att konverteras

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
| djup | int |  |

