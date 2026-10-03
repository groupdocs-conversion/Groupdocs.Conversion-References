---
title: "PersonalStorageLoadOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Optionen zum Laden von Personal Storage-Dokumenten."
type: docs
weight: 28
url: /de/java/com.groupdocs.conversion.options.load/personalstorageloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class PersonalStorageLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Optionen zum Laden von Personal Storage-Dokumenten.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PersonalStorageLoadOptions()](#PersonalStorageLoadOptions--) | Initialisiert eine neue Instanz der Klasse. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getFolder()](#getFolder--) | Ordner, der verarbeitet werden soll. Standard ist Posteingang. |
|
|  | [setFolder(String folder)](#setFolder-java.lang.String-) | Ordner festlegen, der verarbeitet werden soll |
|
|  | [isConvertOwner()](#isConvertOwner--) | {@inheritDoc} Der Besitzer wird nicht konvertiert |
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


Initialisiert eine neue Instanz der Klasse.


### getFolder() {#getFolder--}
```
public String getFolder()
```


Ordner, der verarbeitet werden soll. Standard ist Posteingang.


**Returns:**
java.lang.String - Ordner, der verarbeitet werden soll

### setFolder(String folder) {#setFolder-java.lang.String-}
```
public void setFolder(String folder)
```


Ordner festlegen, der verarbeitet werden soll


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Ordner | java.lang.String | Ordner |
|

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Liest die Option, um zu steuern, ob der Dokumentencontainer selbst konvertiert werden muss. Der Besitzer wird nicht konvertiert


**Returns:**
boolean
### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Option, um zu steuern, ob die im Dokumentcontainer enthaltenen Dokumente konvertiert werden müssen


**Returns:**
boolean
### getDepth() {#getDepth--}
```
public int getDepth()
```


Option, um zu steuern, wie viele Ebenen tief die Konvertierung durchgeführt werden soll


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Tiefe | int |  |

