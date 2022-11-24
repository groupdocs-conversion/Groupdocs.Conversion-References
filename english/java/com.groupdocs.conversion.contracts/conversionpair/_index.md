---
title: ConversionPair
second_title: GroupDocs.Conversion for Java API Reference
description: Represents conversion pair
type: docs
weight: 10
url: /java/com.groupdocs.conversion.contracts/conversionpair/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class ConversionPair extends ValueObject
```

Represents conversion pair
## Fields

| Field | Description |
| --- | --- |
| [NULL](#NULL) |  |
## Methods

| Method | Description |
| --- | --- |
| [createPrimary(FileType source, FileType target)](#createPrimary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | Creates primary conversion pair |
| [createPrimary(List<? extends FileType> sources, List<? extends FileType> targets)](#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--) | Creates primary conversion pairs |
| [createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs)](#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--com.groupdocs.conversion.contracts.Pair-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType----) |  |
| [createSecondary(FileType source, FileType target)](#createSecondary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | Creates secondary conversion pair |
| [createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets)](#createSecondary-java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--) | Creates secondary conversion pairs |
| [getEqualityComponents()](#getEqualityComponents--) | Equality components |
| [toString()](#toString--) | Conversion pair string representation |
| [getSource()](#getSource--) | Source file format |
| [getTarget()](#getTarget--) | Target file format |
| [isPrimary()](#isPrimary--) | Primary conversion pair or not |
### NULL {#NULL}
```
public static final ConversionPair NULL
```


### createPrimary(FileType source, FileType target) {#createPrimary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public static ConversionPair createPrimary(FileType source, FileType target)
```


Creates primary conversion pair

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | source |
| target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | target |

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - ConversionPair
### createPrimary(List<? extends FileType> sources, List<? extends FileType> targets) {#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--}
```
public static List<ConversionPair> createPrimary(List<? extends FileType> sources, List<? extends FileType> targets)
```


Creates primary conversion pairs

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sources | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> | sources file type |
| targets | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> | targets file type |

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair> - primary conversion pairs
### createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs) {#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--com.groupdocs.conversion.contracts.Pair-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType----}
```
public static List<ConversionPair> createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sources | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> |  |
| targets | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> |  |
| excludedPairs | com.groupdocs.conversion.contracts.Pair<com.groupdocs.conversion.filetypes.FileType,com.groupdocs.conversion.filetypes.FileType>[] |  |

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair>
### createSecondary(FileType source, FileType target) {#createSecondary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public static ConversionPair createSecondary(FileType source, FileType target)
```


Creates secondary conversion pair

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | source file type |
| target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | target file type |

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - secondary conversion pair
### createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets) {#createSecondary-java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--}
```
public static List<ConversionPair> createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets)
```


Creates secondary conversion pairs

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sources | java.lang.Iterable<? extends com.groupdocs.conversion.filetypes.FileType> | sources file type |
| targets | java.lang.Iterable<? extends com.groupdocs.conversion.filetypes.FileType> | targets file type |

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair> - secondary conversion pairs
### getEqualityComponents() {#getEqualityComponents--}
```
public System.Collections.Generic.IGenericEnumerable getEqualityComponents()
```


Equality components

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable - equality components
### toString() {#toString--}
```
public String toString()
```


Conversion pair string representation

**Returns:**
java.lang.String - string
### getSource() {#getSource--}
```
public FileType getSource()
```


Source file format

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - source file format
### getTarget() {#getTarget--}
```
public FileType getTarget()
```


Target file format

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - target file format
### isPrimary() {#isPrimary--}
```
public boolean isPrimary()
```


Primary conversion pair or not

**Returns:**
boolean - true if primary, else if not
