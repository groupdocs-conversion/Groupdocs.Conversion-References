---
title: "LoadOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Kelas abstrak opsi pemuatan dokumen."
type: docs
weight: 22
url: /id/java/com.groupdocs.conversion.options.load/loadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public abstract class LoadOptions extends ValueObject implements Serializable
```

Kelas abstrak opsi pemuatan dokumen.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [LoadOptions()](#LoadOptions--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getFormat()](#getFormat--) | Jenis berkas dokumen input |
|
|  | [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) | Jenis berkas dokumen input |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


### getFormat() {#getFormat--}
```
public FileType getFormat()
```


Jenis berkas dokumen input


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


Jenis berkas dokumen input


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

