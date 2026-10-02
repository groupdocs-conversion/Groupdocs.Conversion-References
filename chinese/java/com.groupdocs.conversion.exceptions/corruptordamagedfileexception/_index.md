---
title: "CorruptOrDamagedFileException"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "当文件损坏或受损时抛出的 GroupDocs 异常"
type: docs
weight: 11
url: /zh/java/com.groupdocs.conversion.exceptions/corruptordamagedfileexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.groupdocs.conversion.exceptions.GroupDocsConversionException](../../com.groupdocs.conversion.exceptions/groupdocsconversionexception)
```
public final class CorruptOrDamagedFileException extends GroupDocsConversionException
```

当文件损坏或受损时抛出的 GroupDocs 异常

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [CorruptOrDamagedFileException()](#CorruptOrDamagedFileException--) | 默认构造函数 |
|
|  | [CorruptOrDamagedFileException(FileType fileType)](#CorruptOrDamagedFileException-com.groupdocs.conversion.filetypes.FileType-) | 创建带有文件类型的异常实例 |
|
|  | [CorruptOrDamagedFileException(String message)](#CorruptOrDamagedFileException-java.lang.String-) | 创建带有消息的异常实例 |
|
|  | [CorruptOrDamagedFileException(String message, RuntimeException exception)](#CorruptOrDamagedFileException-java.lang.String-java.lang.RuntimeException-) | 创建一个带有消息的异常实例并传播内部异常 |
|
### CorruptOrDamagedFileException() {#CorruptOrDamagedFileException--}
```
public CorruptOrDamagedFileException()
```


默认构造函数


### CorruptOrDamagedFileException(FileType fileType) {#CorruptOrDamagedFileException-com.groupdocs.conversion.filetypes.FileType-}
```
public CorruptOrDamagedFileException(FileType fileType)
```


创建带有文件类型的异常实例


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | 文件类型 |
|

### CorruptOrDamagedFileException(String message) {#CorruptOrDamagedFileException-java.lang.String-}
```
public CorruptOrDamagedFileException(String message)
```


创建带有消息的异常实例


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 消息 | java.lang.String | 消息 |
|

### CorruptOrDamagedFileException(String message, RuntimeException exception) {#CorruptOrDamagedFileException-java.lang.String-java.lang.RuntimeException-}
```
public CorruptOrDamagedFileException(String message, RuntimeException exception)
```


创建一个带有消息的异常实例并传播内部异常


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 消息 | java.lang.String | 消息 |
|
|  | 异常 | java.lang.RuntimeException | 内部异常 |
|

