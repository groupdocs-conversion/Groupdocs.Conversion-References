---
title: "LoadOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "抽象文档加载选项类。"
type: docs
weight: 22
url: /zh/java/com.groupdocs.conversion.options.load/loadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public abstract class LoadOptions extends ValueObject implements Serializable
```

抽象文档加载选项类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [LoadOptions()](#LoadOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getFormat()](#getFormat--) | 输入文档文件类型 |
|
|  | [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) | 输入文档文件类型 |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


### getFormat() {#getFormat--}
```
public FileType getFormat()
```


输入文档文件类型


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


输入文档文件类型


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

