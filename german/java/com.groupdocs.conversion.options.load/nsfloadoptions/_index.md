---
title: "NsfLoadOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Optionen zum Laden von Nsf-Dokumenten."
type: docs
weight: 25
url: /de/java/com.groupdocs.conversion.options.load/nsfloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class NsfLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Optionen zum Laden von Nsf-Dokumenten.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [NsfLoadOptions()](#NsfLoadOptions--) |  |
## Methoden

| Methode | Beschreibung |
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


Ruft die Option ab, um zu steuern, ob der Dokumentcontainer selbst konvertiert werden muss


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

