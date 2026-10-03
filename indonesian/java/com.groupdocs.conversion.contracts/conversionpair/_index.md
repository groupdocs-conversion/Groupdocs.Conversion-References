---
title: "ConversionPair"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Mewakili pasangan konversi"
type: docs
weight: 10
url: /id/java/com.groupdocs.conversion.contracts/conversionpair/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class ConversionPair extends ValueObject
```

Mewakili pasangan konversi

## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [NULL](#NULL) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [createPrimary(FileType source, FileType target)](#createPrimary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | Membuat pasangan konversi utama |
|
|  | [createPrimary(List<? extends FileType> sources, List<? extends FileType> targets)](#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--) | Membuat pasangan konversi utama |
|
| [createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs)](#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--com.groupdocs.conversion.contracts.Pair-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType----) |  |
|  | [createSecondary(FileType source, FileType target)](#createSecondary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | Membuat pasangan konversi sekunder |
|
|  | [createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets)](#createSecondary-java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--) | Membuat pasangan konversi sekunder |
|
|  | [getEqualityComponents()](#getEqualityComponents--) | Komponen kesetaraan |
|
|  | [toString()](#toString--) | Representasi string pasangan konversi |
|
|  | [getSource()](#getSource--) | Format file sumber |
|
|  | [getTarget()](#getTarget--) | Format file target |
|
|  | [isPrimary()](#isPrimary--) | Pasangan konversi utama atau tidak |
|
### NULL {#NULL}
```
public static final ConversionPair NULL
```


### createPrimary(FileType source, FileType target) {#createPrimary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public static ConversionPair createPrimary(FileType source, FileType target)
```


Membuat pasangan konversi utama


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | sumber |
|
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | target |
|

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - ConversionPair

### createPrimary(List<? extends FileType> sources, List<? extends FileType> targets) {#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--}
```
public static List<ConversionPair> createPrimary(List<? extends FileType> sources, List<? extends FileType> targets)
```


Membuat pasangan konversi utama


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | sumber | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> | tipe file sumber |
|
|  | target | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> | tipe file target |
|

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair> - pasangan konversi utama

### createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs) {#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--com.groupdocs.conversion.contracts.Pair-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType----}
```
public static List<ConversionPair> createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sumber | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> |  |
| target | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> |  |
| excludedPairs | com.groupdocs.conversion.contracts.Pair<com.groupdocs.conversion.filetypes.FileType,com.groupdocs.conversion.filetypes.FileType>[] |  |

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair>
### createSecondary(FileType source, FileType target) {#createSecondary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public static ConversionPair createSecondary(FileType source, FileType target)
```


Membuat pasangan konversi sekunder


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | tipe file sumber |
|
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | tipe file target |
|

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - secondary conversion pair

### createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets) {#createSecondary-java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--}
```
public static List<ConversionPair> createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets)
```


Membuat pasangan konversi sekunder


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | sumber | java.lang.Iterable<? extends com.groupdocs.conversion.filetypes.FileType> | tipe file sumber |
|
|  | target | java.lang.Iterable<? extends com.groupdocs.conversion.filetypes.FileType> | tipe file target |
|

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair> - pasangan konversi sekunder

### getEqualityComponents() {#getEqualityComponents--}
```
public System.Collections.Generic.IGenericEnumerable getEqualityComponents()
```


Komponen kesetaraan


**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable - komponen kesetaraan

### toString() {#toString--}
```
public String toString()
```


Representasi string pasangan konversi


**Returns:**
java.lang.String - string

### getSource() {#getSource--}
```
public FileType getSource()
```


Format file sumber


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - source file format

### getTarget() {#getTarget--}
```
public FileType getTarget()
```


Format file target


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - target file format

### isPrimary() {#isPrimary--}
```
public boolean isPrimary()
```


Pasangan konversi utama atau tidak


**Returns:**
boolean - benar jika utama, jika tidak

