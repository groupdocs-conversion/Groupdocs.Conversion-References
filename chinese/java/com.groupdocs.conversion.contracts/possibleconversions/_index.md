---
title: "PossibleConversions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "表示针对特定源文件格式支持的转换对映射"
type: docs
weight: 13
url: /zh/java/com.groupdocs.conversion.contracts/possibleconversions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public final class PossibleConversions extends ValueObject
```

表示针对特定源文件格式支持的转换对映射

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PossibleConversions(FileType source)](#PossibleConversions-com.groupdocs.conversion.filetypes.FileType-) | 为指定的源文件格式创建可能的转换列表 |
|
## 字段

| 字段 | 描述 |
| --- | --- |
| [NULL](#NULL) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getLoadOptions()](#getLoadOptions--) | 可用于从当前类型转换的预定义加载选项 |
|
|  | [getAll()](#getAll--) | 所有目标文件类型及主/次标志 |
|
|  | [getTargetConversion(FileType target)](#getTargetConversion-com.groupdocs.conversion.filetypes.FileType-) | 返回指定目标文件类型的目标转换 |
|
| [getTargetConversion(String extension)](#getTargetConversion-java.lang.String-) |  |
|  | [getPrimary()](#getPrimary--) | 主要目标文件类型 |
|
|  | [getSecondary()](#getSecondary--) | 次要目标文件类型 |
|
|  | [add(ConversionPair pair)](#add-com.groupdocs.conversion.contracts.ConversionPair-) | 添加转换对 |
|
|  | [forTarget(FileType target)](#forTarget-com.groupdocs.conversion.filetypes.FileType-) | 在当前列表中查找目标文件类型的转换对 |
|
|  | [getSource()](#getSource--) | 源文件格式 |
|
### PossibleConversions(FileType source) {#PossibleConversions-com.groupdocs.conversion.filetypes.FileType-}
```
public PossibleConversions(FileType source)
```


为指定的源文件格式创建可能的转换列表


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | 源文件类型 |
|

### NULL {#NULL}
```
public static final PossibleConversions NULL
```


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


可用于从当前类型转换的预定义加载选项


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions) - load options

### getAll() {#getAll--}
```
public Iterable<TargetConversion> getAll()
```


所有目标文件类型及主/次标志


**Returns:**
java.lang.Iterable<com.groupdocs.conversion.contracts.TargetConversion> - [TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion) 的可迭代集合

### getTargetConversion(FileType target) {#getTargetConversion-com.groupdocs.conversion.filetypes.FileType-}
```
public TargetConversion getTargetConversion(FileType target)
```


返回指定目标文件类型的目标转换


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | 目标文件类型 |
|

**Returns:**
[TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion) - conversions

### getTargetConversion(String extension) {#getTargetConversion-java.lang.String-}
```
public TargetConversion getTargetConversion(String extension)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 扩展名 | java.lang.String |  |

**Returns:**
[TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion)
### getPrimary() {#getPrimary--}
```
public Iterable<FileType> getPrimary()
```


主要目标文件类型


**Returns:**
java.lang.Iterable<com.groupdocs.conversion.filetypes.FileType> - 主要目标文件类型

### getSecondary() {#getSecondary--}
```
public Iterable<FileType> getSecondary()
```


次要目标文件类型


**Returns:**
java.lang.Iterable<com.groupdocs.conversion.filetypes.FileType> - 次要目标文件类型

### add(ConversionPair pair) {#add-com.groupdocs.conversion.contracts.ConversionPair-}
```
public void add(ConversionPair pair)
```


添加转换对


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | pair | [ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) | 转换对 |
|

### forTarget(FileType target) {#forTarget-com.groupdocs.conversion.filetypes.FileType-}
```
public ConversionPair forTarget(FileType target)
```


在当前列表中查找目标文件类型的转换对


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | 目标文件类型 |
|

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - conversion pair

### getSource() {#getSource--}
```
public FileType getSource()
```


源文件格式


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - file formats

