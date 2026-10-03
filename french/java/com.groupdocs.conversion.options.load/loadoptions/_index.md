---
title: "LoadOptions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Classe abstraite d'options de chargement de document."
type: docs
weight: 22
url: /fr/java/com.groupdocs.conversion.options.load/loadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public abstract class LoadOptions extends ValueObject implements Serializable
```

Classe abstraite d'options de chargement de document.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [LoadOptions()](#LoadOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getFormat()](#getFormat--) | Type de fichier du document d’entrée. |
|
|  | [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) | Type de fichier du document d’entrée. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


### getFormat() {#getFormat--}
```
public FileType getFormat()
```


Type de fichier du document d’entrée.


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


Type de fichier du document d’entrée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

