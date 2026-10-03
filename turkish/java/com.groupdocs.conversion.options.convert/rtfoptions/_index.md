---
title: "RtfOptions"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "RTF dosya türüne dönüştürme seçenekleri."
type: docs
weight: 39
url: /tr/java/com.groupdocs.conversion.options.convert/rtfoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class RtfOptions extends ValueObject implements Serializable
```

RTF dosya türüne dönüştürme seçenekleri.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [RtfOptions()](#RtfOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getExportImagesForOldReaders()](#getExportImagesForOldReaders--) | Eski okuyucular için anahtar kelimelerin RTF'ye yazılıp yazılmayacağını belirtir. |
|
|  | [setExportImagesForOldReaders(boolean value)](#setExportImagesForOldReaders-boolean-) | Eski okuyucular için anahtar kelimelerin RTF'ye yazılıp yazılmayacağını belirtir. |
|
### RtfOptions() {#RtfOptions--}
```
public RtfOptions()
```


### getExportImagesForOldReaders() {#getExportImagesForOldReaders--}
```
public final boolean getExportImagesForOldReaders()
```


Eski okuyucular için anahtar kelimelerin RTF'ye yazılıp yazılmayacağını belirtir.
Bu, RTF belgesinin boyutunu önemli ölçüde etkileyebilir. Varsayılan değer False'tur.


**Returns:**
boolean
### setExportImagesForOldReaders(boolean value) {#setExportImagesForOldReaders-boolean-}
```
public final void setExportImagesForOldReaders(boolean value)
```


Eski okuyucular için anahtar kelimelerin RTF'ye yazılıp yazılmayacağını belirtir.
Bu, RTF belgesinin boyutunu önemli ölçüde etkileyebilir. Varsayılan değer False'tur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

