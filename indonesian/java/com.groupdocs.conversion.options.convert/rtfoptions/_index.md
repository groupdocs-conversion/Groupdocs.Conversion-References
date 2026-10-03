---
title: "RtfOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Opsi untuk konversi ke tipe file RTF."
type: docs
weight: 39
url: /id/java/com.groupdocs.conversion.options.convert/rtfoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class RtfOptions extends ValueObject implements Serializable
```

Opsi untuk konversi ke tipe file RTF.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [RtfOptions()](#RtfOptions--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getExportImagesForOldReaders()](#getExportImagesForOldReaders--) | Menentukan apakah kata kunci untuk "pembaca lama" ditulis ke RTF atau tidak. |
|
|  | [setExportImagesForOldReaders(boolean value)](#setExportImagesForOldReaders-boolean-) | Menentukan apakah kata kunci untuk "pembaca lama" ditulis ke RTF atau tidak. |
|
### RtfOptions() {#RtfOptions--}
```
public RtfOptions()
```


### getExportImagesForOldReaders() {#getExportImagesForOldReaders--}
```
public final boolean getExportImagesForOldReaders()
```


Menentukan apakah kata kunci untuk "pembaca lama" ditulis ke RTF atau tidak.
Ini dapat secara signifikan memengaruhi ukuran dokumen RTF. Nilai default adalah False.


**Returns:**
boolean
### setExportImagesForOldReaders(boolean value) {#setExportImagesForOldReaders-boolean-}
```
public final void setExportImagesForOldReaders(boolean value)
```


Menentukan apakah kata kunci untuk "pembaca lama" ditulis ke RTF atau tidak.
Ini dapat secara signifikan memengaruhi ukuran dokumen RTF. Nilai default adalah False.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

