---
title: "ConversionPair"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "表示转换对"
type: docs
weight: 10
url: /zh/java/com.groupdocs.conversion.contracts/conversionpair/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class ConversionPair extends ValueObject
```

表示转换对

## 字段

| 字段 | 描述 |
| --- | --- |
| [NULL](#NULL) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [createPrimary(FileType source, FileType target)](#createPrimary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | 创建主要转换对 |
|
|  | [createPrimary(List<? extends FileType> sources, List<? extends FileType> targets)](#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--) | 创建主要转换对 |
|
| [createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs)](#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--com.groupdocs.conversion.contracts.Pair-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType----) |  |
|  | [createSecondary(FileType source, FileType target)](#createSecondary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | 创建次要转换对 |
|
|  | [createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets)](#createSecondary-java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--) | 创建次要转换对 |
|
|  | [getEqualityComponents()](#getEqualityComponents--) | 相等组件 |
|
|  | [toString()](#toString--) | 转换对字符串表示 |
|
|  | [getSource()](#getSource--) | 源文件格式 |
|
|  | [getTarget()](#getTarget--) | 目标文件格式 |
|
|  | [isPrimary()](#isPrimary--) | 是否为主要转换对 |
|
### NULL {#NULL}
```
public static final ConversionPair NULL
```


### createPrimary(FileType source, FileType target) {#createPrimary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public static ConversionPair createPrimary(FileType source, FileType target)
```


创建主要转换对


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | 源 |
|
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | 目标 |
|

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - ConversionPair

### createPrimary(List<? extends FileType> sources, List<? extends FileType> targets) {#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--}
```
public static List<ConversionPair> createPrimary(List<? extends FileType> sources, List<? extends FileType> targets)
```


创建主要转换对


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 源 | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> | 源文件类型 |
|
|  | 目标 | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> | 目标文件类型 |
|

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair> - 主要转换对

### createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs) {#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--com.groupdocs.conversion.contracts.Pair-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType----}
```
public static List<ConversionPair> createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 源 | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> |  |
| 目标 | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> |  |
| excludedPairs | com.groupdocs.conversion.contracts.Pair<com.groupdocs.conversion.filetypes.FileType,com.groupdocs.conversion.filetypes.FileType>[] |  |

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair>
### createSecondary(FileType source, FileType target) {#createSecondary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public static ConversionPair createSecondary(FileType source, FileType target)
```


创建次要转换对


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | 源文件类型 |
|
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | 目标文件类型 |
|

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - secondary conversion pair

### createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets) {#createSecondary-java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--}
```
public static List<ConversionPair> createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets)
```


创建次要转换对


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 源 | java.lang.Iterable<? extends com.groupdocs.conversion.filetypes.FileType> | 源文件类型 |
|
|  | 目标 | java.lang.Iterable<? extends com.groupdocs.conversion.filetypes.FileType> | 目标文件类型 |
|

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair> - 次要转换对

### getEqualityComponents() {#getEqualityComponents--}
```
public System.Collections.Generic.IGenericEnumerable getEqualityComponents()
```


相等组件


**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable - 相等组件

### toString() {#toString--}
```
public String toString()
```


转换对字符串表示


**Returns:**
java.lang.String - 字符串

### getSource() {#getSource--}
```
public FileType getSource()
```


源文件格式


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - source file format

### getTarget() {#getTarget--}
```
public FileType getTarget()
```


目标文件格式


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - target file format

### isPrimary() {#isPrimary--}
```
public boolean isPrimary()
```


是否为主要转换对


**Returns:**
boolean - 如果为主则为 true，否则为 false

