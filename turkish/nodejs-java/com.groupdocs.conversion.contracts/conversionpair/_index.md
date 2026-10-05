---
title: "ConversionPair"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Dönüştürme çiftini temsil eder"
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.conversion.contracts/conversionpair/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class ConversionPair extends ValueObject
```

Dönüştürme çiftini temsil eder
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [NULL](#NULL) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createPrimary(FileType source, FileType target)](#createPrimary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | Birincil dönüşüm çiftini oluşturur |
| [createPrimary(List<? extends FileType> sources, List<? extends FileType> targets)](#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--) | Birincil dönüşüm çiftlerini oluşturur |
| [createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs)](#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--com.groupdocs.conversion.contracts.Pair-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType----) |  |
| [createSecondary(FileType source, FileType target)](#createSecondary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | İkincil dönüşüm çiftini oluşturur |
| [createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets)](#createSecondary-java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--) | İkincil dönüşüm çiftlerini oluşturur |
| [getEqualityComponents()](#getEqualityComponents--) | Eşitlik bileşenleri |
| [toString()](#toString--) | Dönüşüm çifti dize temsili |
| [getSource()](#getSource--) | Kaynak dosya formatı |
| [getTarget()](#getTarget--) | Hedef dosya formatı |
| [isPrimary()](#isPrimary--) | Birincil dönüşüm çifti mi değil mi |
### NULL {#NULL}
```
public static final ConversionPair NULL
```


### createPrimary(FileType source, FileType target) {#createPrimary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public static ConversionPair createPrimary(FileType source, FileType target)
```


Birincil dönüşüm çiftini oluşturur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | kaynak |
| target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | hedef |

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - ConversionPair
### createPrimary(List<? extends FileType> sources, List<? extends FileType> targets) {#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--}
```
public static List<ConversionPair> createPrimary(List<? extends FileType> sources, List<? extends FileType> targets)
```


Birincil dönüşüm çiftlerini oluşturur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| kaynaklar | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> | kaynak dosya türü |
| hedefler | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> | hedef dosya türü |

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair> - birincil dönüşüm çiftleri
### createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs) {#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--com.groupdocs.conversion.contracts.Pair-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType----}
```
public static List<ConversionPair> createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| kaynaklar | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> |  |
| hedefler | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> |  |
| excludedPairs | com.groupdocs.conversion.contracts.Pair<com.groupdocs.conversion.filetypes.FileType,com.groupdocs.conversion.filetypes.FileType>[] |  |

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair>
### createSecondary(FileType source, FileType target) {#createSecondary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public static ConversionPair createSecondary(FileType source, FileType target)
```


İkincil dönüşüm çiftini oluşturur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | kaynak dosya türü |
| target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | hedef dosya türü |

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - secondary conversion pair
### createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets) {#createSecondary-java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--}
```
public static List<ConversionPair> createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets)
```


İkincil dönüşüm çiftlerini oluşturur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| kaynaklar | java.lang.Iterable<? extends com.groupdocs.conversion.filetypes.FileType> | kaynak dosya türü |
| hedefler | java.lang.Iterable<? extends com.groupdocs.conversion.filetypes.FileType> | hedef dosya türü |

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair> - ikincil dönüşüm çiftleri
### getEqualityComponents() {#getEqualityComponents--}
```
public System.Collections.Generic.IGenericEnumerable getEqualityComponents()
```


Eşitlik bileşenleri

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable - eşitlik bileşenleri
### toString() {#toString--}
```
public String toString()
```


Dönüşüm çifti dize temsili

**Returns:**
java.lang.String - dize
### getSource() {#getSource--}
```
public FileType getSource()
```


Kaynak dosya formatı

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - source file format
### getTarget() {#getTarget--}
```
public FileType getTarget()
```


Hedef dosya formatı

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - target file format
### isPrimary() {#isPrimary--}
```
public boolean isPrimary()
```


Birincil dönüşüm çifti mi değil mi

**Returns:**
boolean - birincil ise true, değilse
