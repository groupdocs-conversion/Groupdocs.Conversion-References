---
title: "LoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Clase abstracta de opciones de carga de documentos."
type: docs
weight: 25
url: /es/nodejs-java/com.groupdocs.conversion.options.load/loadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public abstract class LoadOptions extends ValueObject implements Serializable
```

Clase abstracta de opciones de carga de documentos.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [LoadOptions()](#LoadOptions--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFormat()](#getFormat--) | Tipo de archivo del documento de entrada |
| [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) | Tipo de archivo del documento de entrada |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


### getFormat() {#getFormat--}
```
public FileType getFormat()
```


Tipo de archivo del documento de entrada

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


Tipo de archivo del documento de entrada

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

