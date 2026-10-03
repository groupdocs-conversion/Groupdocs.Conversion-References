---
title: "ConvertOptions"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Genel dönüştürme seçenekleri sınıfı."
type: docs
weight: 12
url: /tr/java/com.groupdocs.conversion.options.convert/convertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions), java.lang.Cloneable
```
public abstract class ConvertOptions<TFileType> extends ValueObject implements Serializable, IConvertOptions, Cloneable
```

Genel dönüştürme seçenekleri sınıfı.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getFormat()](#getFormat--) | {@inheritDoc} |
|
|  | [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) | Girdi belgesinin dönüştürülmesi gereken istenen dosya türü. |
|
|  | [deepClone()](#deepClone--) | Mevcut seçenek örneğini kopyalar. |
|
|  | [getFormat_ConvertOptions_New()](#getFormat-ConvertOptions-New--) | Girdi belgesinin dönüştürülmesi gereken istenen dosya türü. |
|
|  | [setFormat_ConvertOptions_New(TFileType value)](#setFormat-ConvertOptions-New-TFileType-) | Girdi belgesinin dönüştürülmesi gereken istenen dosya türü. |
|
### getFormat() {#getFormat--}
```
public FileType getFormat()
```


Giriş belgesinin dönüştürülmesi gereken istenen dosya türünü alır.


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


Girdi belgesinin dönüştürülmesi gereken istenen dosya türü.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Mevcut seçenek örneğini kopyalar.


**Returns:**
java.lang.Object -
### getFormat_ConvertOptions_New() {#getFormat-ConvertOptions-New--}
```
public final TFileType getFormat_ConvertOptions_New()
```


Girdi belgesinin dönüştürülmesi gereken istenen dosya türü.


**Returns:**
TFileType
### setFormat_ConvertOptions_New(TFileType value) {#setFormat-ConvertOptions-New-TFileType-}
```
public final void setFormat_ConvertOptions_New(TFileType value)
```


Girdi belgesinin dönüştürülmesi gereken istenen dosya türü.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | TFileType |  |

