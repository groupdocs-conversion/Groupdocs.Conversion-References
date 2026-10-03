---
title: "ConvertOptions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "La classe générale d'options de conversion."
type: docs
weight: 12
url: /fr/java/com.groupdocs.conversion.options.convert/convertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions), java.lang.Cloneable
```
public abstract class ConvertOptions<TFileType> extends ValueObject implements Serializable, IConvertOptions, Cloneable
```

La classe générale d'options de conversion.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getFormat()](#getFormat--) | {@inheritDoc} |
|
|  | [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) | Le type de fichier souhaité vers lequel le document d'entrée doit être converti. |
|
|  | [deepClone()](#deepClone--) | Clone l'instance actuelle des options. |
|
|  | [getFormat_ConvertOptions_New()](#getFormat-ConvertOptions-New--) | Le type de fichier souhaité vers lequel le document d'entrée doit être converti. |
|
|  | [setFormat_ConvertOptions_New(TFileType value)](#setFormat-ConvertOptions-New-TFileType-) | Le type de fichier souhaité vers lequel le document d'entrée doit être converti. |
|
### getFormat() {#getFormat--}
```
public FileType getFormat()
```


Obtient le type de fichier souhaité vers lequel le document d'entrée doit être converti.


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


Le type de fichier souhaité vers lequel le document d'entrée doit être converti.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Clone l'instance actuelle des options.


**Returns:**
java.lang.Object -
### getFormat_ConvertOptions_New() {#getFormat-ConvertOptions-New--}
```
public final TFileType getFormat_ConvertOptions_New()
```


Le type de fichier souhaité vers lequel le document d'entrée doit être converti.


**Returns:**
TFileType
### setFormat_ConvertOptions_New(TFileType value) {#setFormat-ConvertOptions-New-TFileType-}
```
public final void setFormat_ConvertOptions_New(TFileType value)
```


Le type de fichier souhaité vers lequel le document d'entrée doit être converti.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | TFileType |  |

