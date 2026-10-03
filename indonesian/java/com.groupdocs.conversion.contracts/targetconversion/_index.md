---
title: "TargetConversion"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Mewakili konversi target yang mungkin dan sebuah flag apakah itu utama atau sekunder"
type: docs
weight: 14
url: /id/java/com.groupdocs.conversion.contracts/targetconversion/
---
**Inheritance:**
java.lang.Object
```
public final class TargetConversion
```

Mewakili konversi target yang mungkin dan sebuah flag apakah itu utama atau sekunder

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getFormat()](#getFormat--) | format dokumen target |
|
|  | [isPrimary()](#isPrimary--) | Apakah konversi utama |
|
|  | [getConvertOptions()](#getConvertOptions--) | Opsi konversi yang telah ditentukan yang dapat digunakan untuk mengonversi ke tipe saat ini |
|
### getFormat() {#getFormat--}
```
public FileType getFormat()
```


format dokumen target


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - Target document format

### isPrimary() {#isPrimary--}
```
public boolean isPrimary()
```


Apakah konversi utama


**Returns:**
boolean - `true` jika utama

### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Opsi konversi yang telah ditentukan yang dapat digunakan untuk mengonversi ke tipe saat ini


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions) - convert options

