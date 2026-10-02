---
title: "ConvertOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "通用转换选项类。"
type: docs
weight: 12
url: /zh/java/com.groupdocs.conversion.options.convert/convertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions), java.lang.Cloneable
```
public abstract class ConvertOptions<TFileType> extends ValueObject implements Serializable, IConvertOptions, Cloneable
```

通用转换选项类。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getFormat()](#getFormat--) | {@inheritDoc} |
|
|  | [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) | 所需的文件类型，输入文档应转换为该类型。 |
|
|  | [deepClone()](#deepClone--) | 克隆当前选项实例。 |
|
|  | [getFormat_ConvertOptions_New()](#getFormat-ConvertOptions-New--) | 所需的文件类型，输入文档应转换为该类型。 |
|
|  | [setFormat_ConvertOptions_New(TFileType value)](#setFormat-ConvertOptions-New-TFileType-) | 所需的文件类型，输入文档应转换为该类型。 |
|
### getFormat() {#getFormat--}
```
public FileType getFormat()
```


获取输入文档应转换为的目标文件类型。


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


所需的文件类型，输入文档应转换为该类型。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


克隆当前选项实例。


**Returns:**
java.lang.Object -
### getFormat_ConvertOptions_New() {#getFormat-ConvertOptions-New--}
```
public final TFileType getFormat_ConvertOptions_New()
```


所需的文件类型，输入文档应转换为该类型。


**Returns:**
TFileType
### setFormat_ConvertOptions_New(TFileType value) {#setFormat-ConvertOptions-New-TFileType-}
```
public final void setFormat_ConvertOptions_New(TFileType value)
```


所需的文件类型，输入文档应转换为该类型。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | TFileType |  |

