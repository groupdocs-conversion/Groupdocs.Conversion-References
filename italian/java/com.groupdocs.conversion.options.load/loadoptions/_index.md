---
title: "LoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Classe astratta di opzioni di caricamento del documento."
type: docs
weight: 22
url: /it/java/com.groupdocs.conversion.options.load/loadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public abstract class LoadOptions extends ValueObject implements Serializable
```

Classe astratta di opzioni di caricamento del documento.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [LoadOptions()](#LoadOptions--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getFormat()](#getFormat--) | Tipo di file del documento di input |
|
|  | [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) | Tipo di file del documento di input |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


### getFormat() {#getFormat--}
```
public FileType getFormat()
```


Tipo di file del documento di input


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


Tipo di file del documento di input


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

