---
title: "目标转换"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "表示可能的目标转换以及它是主要还是次要的标志"
type: docs
weight: 14
url: /zh/java/com.groupdocs.conversion.contracts/targetconversion/
---
**Inheritance:**
java.lang.Object
```
public final class TargetConversion
```

表示可能的目标转换以及它是主要还是次要的标志

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getFormat()](#getFormat--) | 目标文档格式 |
|
|  | [isPrimary()](#isPrimary--) | 转换是否为主要 |
|
|  | [getConvertOptions()](#getConvertOptions--) | 可用于转换为当前类型的预定义转换选项 |
|
### getFormat() {#getFormat--}
```
public FileType getFormat()
```


目标文档格式


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - Target document format

### isPrimary() {#isPrimary--}
```
public boolean isPrimary()
```


转换是否为主要


**Returns:**
布尔型 - `true` 表示主要

### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


可用于转换为当前类型的预定义转换选项


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions) - convert options

