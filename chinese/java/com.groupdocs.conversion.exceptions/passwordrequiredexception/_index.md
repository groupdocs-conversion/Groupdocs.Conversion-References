---
title: "PasswordRequiredException"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "当文件受密码保护且未提供密码时抛出的 GroupDocs 异常"
type: docs
weight: 18
url: /zh/java/com.groupdocs.conversion.exceptions/passwordrequiredexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.groupdocs.conversion.exceptions.GroupDocsConversionException](../../com.groupdocs.conversion.exceptions/groupdocsconversionexception)
```
public final class PasswordRequiredException extends GroupDocsConversionException
```

当文件受密码保护且未提供密码时抛出的 GroupDocs 异常

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PasswordRequiredException()](#PasswordRequiredException--) | 默认构造函数 |
|
|  | [PasswordRequiredException(FileType fileType)](#PasswordRequiredException-com.groupdocs.conversion.filetypes.FileType-) | 创建带有文件类型的异常实例 |
|
|  | [PasswordRequiredException(String message)](#PasswordRequiredException-java.lang.String-) | 创建带有消息的异常实例 |
|
### PasswordRequiredException() {#PasswordRequiredException--}
```
public PasswordRequiredException()
```


默认构造函数


### PasswordRequiredException(FileType fileType) {#PasswordRequiredException-com.groupdocs.conversion.filetypes.FileType-}
```
public PasswordRequiredException(FileType fileType)
```


创建带有文件类型的异常实例


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | 文件类型 |
|

### PasswordRequiredException(String message) {#PasswordRequiredException-java.lang.String-}
```
public PasswordRequiredException(String message)
```


创建带有消息的异常实例


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 消息 | java.lang.String | 消息 |
|

