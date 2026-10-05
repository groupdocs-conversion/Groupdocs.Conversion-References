---
title: "PossibleConversions"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Belirli kaynak dosya formatı için hangi dönüştürme çiftlerinin desteklendiğini gösteren bir eşlemeyi temsil eder"
type: docs
weight: 13
url: /tr/nodejs-java/com.groupdocs.conversion.contracts/possibleconversions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public final class PossibleConversions extends ValueObject
```

Belirli kaynak dosya formatı için hangi dönüştürme çiftlerinin desteklendiğini gösteren bir eşlemeyi temsil eder
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PossibleConversions(FileType source)](#PossibleConversions-com.groupdocs.conversion.filetypes.FileType-) | Belirtilen kaynak dosya biçimi için olası dönüşüm listesini oluşturur |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [NULL](#NULL) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) | Mevcut türden dönüştürmek için kullanılabilecek önceden tanımlanmış yükleme seçenekleri |
| [getAll()](#getAll--) | Tüm hedef dosya türleri ve birincil/ikincil bayrağı |
| [getTargetConversion(FileType target)](#getTargetConversion-com.groupdocs.conversion.filetypes.FileType-) | Belirtilen hedef dosya türü için hedef dönüşümü döndürür |
| [getTargetConversion(String extension)](#getTargetConversion-java.lang.String-) |  |
| [getPrimary()](#getPrimary--) | Birincil hedef dosya türleri |
| [getSecondary()](#getSecondary--) | İkincil hedef dosya türleri |
| [add(ConversionPair pair)](#add-com.groupdocs.conversion.contracts.ConversionPair-) | Dönüşüm çifti ekle |
| [forTarget(FileType target)](#forTarget-com.groupdocs.conversion.filetypes.FileType-) | Hedef dosya türü için mevcut listede dönüşüm çiftini bul |
| [getSource()](#getSource--) | Kaynak dosya biçimleri |
### PossibleConversions(FileType source) {#PossibleConversions-com.groupdocs.conversion.filetypes.FileType-}
```
public PossibleConversions(FileType source)
```


Belirtilen kaynak dosya biçimi için olası dönüşüm listesini oluşturur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | kaynak dosya türü |

### NULL {#NULL}
```
public static final PossibleConversions NULL
```


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Mevcut türden dönüştürmek için kullanılabilecek önceden tanımlanmış yükleme seçenekleri

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions) - load options
### getAll() {#getAll--}
```
public Iterable<TargetConversion> getAll()
```


Tüm hedef dosya türleri ve birincil/ikincil bayrağı

**Returns:**
java.lang.Iterable<com.groupdocs.conversion.contracts.TargetConversion> - [TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion) öğesinin Iterable'ı
### getTargetConversion(FileType target) {#getTargetConversion-com.groupdocs.conversion.filetypes.FileType-}
```
public TargetConversion getTargetConversion(FileType target)
```


Belirtilen hedef dosya türü için hedef dönüşümü döndürür

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | hedef dosya türü |

**Returns:**
[TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion) - conversions
### getTargetConversion(String extension) {#getTargetConversion-java.lang.String-}
```
public TargetConversion getTargetConversion(String extension)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uzantı | java.lang.String |  |

**Returns:**
[TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion)
### getPrimary() {#getPrimary--}
```
public Iterable<FileType> getPrimary()
```


Birincil hedef dosya türleri

**Returns:**
java.lang.Iterable<com.groupdocs.conversion.filetypes.FileType> - birincil hedef dosya türleri
### getSecondary() {#getSecondary--}
```
public Iterable<FileType> getSecondary()
```


İkincil hedef dosya türleri

**Returns:**
java.lang.Iterable<com.groupdocs.conversion.filetypes.FileType> - ikincil hedef dosya türleri
### add(ConversionPair pair) {#add-com.groupdocs.conversion.contracts.ConversionPair-}
```
public void add(ConversionPair pair)
```


Dönüşüm çifti ekle

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pair | [ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) | dönüşüm çifti |

### forTarget(FileType target) {#forTarget-com.groupdocs.conversion.filetypes.FileType-}
```
public ConversionPair forTarget(FileType target)
```


Hedef dosya türü için mevcut listede dönüşüm çiftini bul

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | hedef dosya türü |

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - conversion pair
### getSource() {#getSource--}
```
public FileType getSource()
```


Kaynak dosya biçimleri

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - file formats
