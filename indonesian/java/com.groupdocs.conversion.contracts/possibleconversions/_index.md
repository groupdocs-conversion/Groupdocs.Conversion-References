---
title: "PossibleConversions"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Mewakili pemetaan pasangan konversi yang didukung untuk format file sumber tertentu"
type: docs
weight: 13
url: /id/java/com.groupdocs.conversion.contracts/possibleconversions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public final class PossibleConversions extends ValueObject
```

Mewakili pemetaan pasangan konversi yang didukung untuk format file sumber tertentu

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [PossibleConversions(FileType source)](#PossibleConversions-com.groupdocs.conversion.filetypes.FileType-) | Membuat daftar konversi yang mungkin untuk format file sumber yang ditentukan |
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [NULL](#NULL) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getLoadOptions()](#getLoadOptions--) | Opsi muat yang telah ditentukan sebelumnya yang dapat digunakan untuk mengonversi dari tipe saat ini |
|
|  | [getAll()](#getAll--) | Semua tipe file target dan flag utama/sekunder |
|
|  | [getTargetConversion(FileType target)](#getTargetConversion-com.groupdocs.conversion.filetypes.FileType-) | Mengembalikan konversi target untuk tipe file target yang ditentukan |
|
| [getTargetConversion(String extension)](#getTargetConversion-java.lang.String-) |  |
|  | [getPrimary()](#getPrimary--) | Tipe file target utama |
|
|  | [getSecondary()](#getSecondary--) | Tipe file target sekunder |
|
|  | [add(ConversionPair pair)](#add-com.groupdocs.conversion.contracts.ConversionPair-) | Tambahkan pasangan konversi |
|
|  | [forTarget(FileType target)](#forTarget-com.groupdocs.conversion.filetypes.FileType-) | Temukan pasangan konversi dalam daftar saat ini untuk tipe file target |
|
|  | [getSource()](#getSource--) | Format file sumber |
|
### PossibleConversions(FileType source) {#PossibleConversions-com.groupdocs.conversion.filetypes.FileType-}
```
public PossibleConversions(FileType source)
```


Membuat daftar konversi yang mungkin untuk format file sumber yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | tipe file sumber |
|

### NULL {#NULL}
```
public static final PossibleConversions NULL
```


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Opsi muat yang telah ditentukan sebelumnya yang dapat digunakan untuk mengonversi dari tipe saat ini


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions) - load options

### getAll() {#getAll--}
```
public Iterable<TargetConversion> getAll()
```


Semua tipe file target dan flag utama/sekunder


**Returns:**
java.lang.Iterable<com.groupdocs.conversion.contracts.TargetConversion> - Iterabel dari [TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion)

### getTargetConversion(FileType target) {#getTargetConversion-com.groupdocs.conversion.filetypes.FileType-}
```
public TargetConversion getTargetConversion(FileType target)
```


Mengembalikan konversi target untuk tipe file target yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | tipe file target |
|

**Returns:**
[TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion) - conversions

### getTargetConversion(String extension) {#getTargetConversion-java.lang.String-}
```
public TargetConversion getTargetConversion(String extension)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ekstensi | java.lang.String |  |

**Returns:**
[TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion)
### getPrimary() {#getPrimary--}
```
public Iterable<FileType> getPrimary()
```


Tipe file target utama


**Returns:**
java.lang.Iterable<com.groupdocs.conversion.filetypes.FileType> - tipe file target utama

### getSecondary() {#getSecondary--}
```
public Iterable<FileType> getSecondary()
```


Tipe file target sekunder


**Returns:**
java.lang.Iterable<com.groupdocs.conversion.filetypes.FileType> - tipe file target sekunder

### add(ConversionPair pair) {#add-com.groupdocs.conversion.contracts.ConversionPair-}
```
public void add(ConversionPair pair)
```


Tambahkan pasangan konversi


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | pair | [ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) | pasangan konversi |
|

### forTarget(FileType target) {#forTarget-com.groupdocs.conversion.filetypes.FileType-}
```
public ConversionPair forTarget(FileType target)
```


Temukan pasangan konversi dalam daftar saat ini untuk tipe file target


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | tipe file target |
|

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - conversion pair

### getSource() {#getSource--}
```
public FileType getSource()
```


Format file sumber


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - file formats

