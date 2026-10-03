---
title: "ConvertOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Kelas opsi konversi umum."
type: docs
weight: 12
url: /id/java/com.groupdocs.conversion.options.convert/convertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions), java.lang.Cloneable
```
public abstract class ConvertOptions<TFileType> extends ValueObject implements Serializable, IConvertOptions, Cloneable
```

Kelas opsi konversi umum.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getFormat()](#getFormat--) | {@inheritDoc} |
|
|  | [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) | Tipe file yang diinginkan untuk dokumen input yang akan dikonversi. |
|
|  | [deepClone()](#deepClone--) | Menggandakan instance opsi saat ini. |
|
|  | [getFormat_ConvertOptions_New()](#getFormat-ConvertOptions-New--) | Tipe file yang diinginkan untuk dokumen input yang akan dikonversi. |
|
|  | [setFormat_ConvertOptions_New(TFileType value)](#setFormat-ConvertOptions-New-TFileType-) | Tipe file yang diinginkan untuk dokumen input yang akan dikonversi. |
|
### getFormat() {#getFormat--}
```
public FileType getFormat()
```


Mendapatkan tipe file yang diinginkan untuk mengonversi dokumen masukan.


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


Tipe file yang diinginkan untuk dokumen input yang akan dikonversi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Menggandakan instance opsi saat ini.


**Returns:**
java.lang.Object -
### getFormat_ConvertOptions_New() {#getFormat-ConvertOptions-New--}
```
public final TFileType getFormat_ConvertOptions_New()
```


Tipe file yang diinginkan untuk dokumen input yang akan dikonversi.


**Returns:**
TFileType
### setFormat_ConvertOptions_New(TFileType value) {#setFormat-ConvertOptions-New-TFileType-}
```
public final void setFormat_ConvertOptions_New(TFileType value)
```


Tipe file yang diinginkan untuk dokumen input yang akan dikonversi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | TFileType |  |

