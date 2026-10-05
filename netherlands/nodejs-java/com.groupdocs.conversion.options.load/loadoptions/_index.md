---
title: "LoadOptions"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Abstracte klasse voor documentlaadopties"
type: docs
weight: 25
url: /nl/nodejs-java/com.groupdocs.conversion.options.load/loadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public abstract class LoadOptions extends ValueObject implements Serializable
```

Abstracte klasse voor documentlaadopties
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [LoadOptions()](#LoadOptions--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFormat()](#getFormat--) | Bestandstype van invoerdocument |
| [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) | Bestandstype van invoerdocument |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


### getFormat() {#getFormat--}
```
public FileType getFormat()
```


Bestandstype van invoerdocument

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


Bestandstype van invoerdocument

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

