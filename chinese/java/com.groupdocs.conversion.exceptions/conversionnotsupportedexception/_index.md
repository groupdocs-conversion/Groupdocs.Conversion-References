---
title: "ConversionNotSupportedException"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "当不支持将源文件转换为目标文件类型时抛出的 GroupDocs 异常"
type: docs
weight: 10
url: /zh/java/com.groupdocs.conversion.exceptions/conversionnotsupportedexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.groupdocs.conversion.exceptions.GroupDocsConversionException](../../com.groupdocs.conversion.exceptions/groupdocsconversionexception)
```
public final class ConversionNotSupportedException extends GroupDocsConversionException
```

当不支持将源文件转换为目标文件类型时抛出的 GroupDocs 异常

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [ConversionNotSupportedException()](#ConversionNotSupportedException--) | 默认构造函数 |
|
|  | [ConversionNotSupportedException(FileType source, FileType target)](#ConversionNotSupportedException-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | 创建一个异常实例，包含源文件类型和目标文件类型 |
|
|  | [ConversionNotSupportedException(String message)](#ConversionNotSupportedException-java.lang.String-) | 创建带有消息的异常实例 |
|
### ConversionNotSupportedException() {#ConversionNotSupportedException--}
```
public ConversionNotSupportedException()
```


默认构造函数


### ConversionNotSupportedException(FileType source, FileType target) {#ConversionNotSupportedException-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public ConversionNotSupportedException(FileType source, FileType target)
```


创建一个异常实例，包含源文件类型和目标文件类型


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | 源文件类型 |
|
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | 目标文件类型 |
|

### ConversionNotSupportedException(String message) {#ConversionNotSupportedException-java.lang.String-}
```
public ConversionNotSupportedException(String message)
```


创建带有消息的异常实例


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 消息 | java.lang.String | 消息 |
|

