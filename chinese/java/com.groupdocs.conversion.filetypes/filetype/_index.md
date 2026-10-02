---
title: "FileType"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "文件类型基类"
type: docs
weight: 16
url: /zh/java/com.groupdocs.conversion.filetypes/filetype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration)
```
public class FileType extends Enumeration
```

文件类型基类

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [FileType()](#FileType--) | 序列化构造函数 |
|
## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Unknown](#Unknown) | 未知文件类型 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | 文件格式 |
|
|  | [getExtension()](#getExtension--) | 文件扩展名 |
|
|  | [getFamily()](#getFamily--) | 文件族 |
|
|  | [getDescription()](#getDescription--) | 文件类型的描述 |
|
|  | [fromFilename(String fileName)](#fromFilename-java.lang.String-) | 返回指定 fileName 的 FileType |
|
|  | [fromExtension(String fileExtension)](#fromExtension-java.lang.String-) | 获取提供的 fileExtension 的 FileType |
|
|  | [fromStream(InputStream inputStream)](#fromStream-java.io.InputStream-) | 返回提供的文档流的 FileType |
|
|  | [<T>getAllTypes(Class<T> typeOfT)](#-T-getAllTypes-java.lang.Class-T--) | 返回所有枚举值。 |
|
| [<T>getAllTypes(Class<T> typeOfT, FileType[] excluded)](#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType---) |  |
| [<T>getAllTypes(Class<T> typeOfT, FileType[][] excluded)](#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType--...-) |  |
|  | [toString()](#toString--) | 字符串表示 |
|
|  | [getLoadOptions()](#getLoadOptions--) | 为源文件类型准备了默认加载选项 |
|
|  | [getConvertOptions()](#getConvertOptions--) | 为文件类型准备了默认转换选项 |
|
| [isObsolete()](#isObsolete--) |  |
| [equals(Enumeration other)](#equals-com.groupdocs.conversion.contracts.Enumeration-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
### FileType() {#FileType--}
```
public FileType()
```


序列化构造函数


### Unknown {#Unknown}
```
public static final FileType Unknown
```


未知文件类型


### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


文件格式


**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


文件扩展名


**Returns:**
java.lang.String
### getFamily() {#getFamily--}
```
public String getFamily()
```


文件族


**Returns:**
java.lang.String - 文件族

### getDescription() {#getDescription--}
```
public final String getDescription()
```


文件类型的描述


**Returns:**
java.lang.String - 描述

### fromFilename(String fileName) {#fromFilename-java.lang.String-}
```
public static FileType fromFilename(String fileName)
```


返回指定 fileName 的 FileType


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fileName | java.lang.String | 文件名 |
|

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - The file type of specified file name

### fromExtension(String fileExtension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String fileExtension)
```


获取提供的 fileExtension 的 FileType


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fileExtension | java.lang.String | 文件扩展名 |
|

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - file type

### fromStream(InputStream inputStream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream inputStream)
```


返回提供的文档流的 FileType


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | inputStream | java.io.InputStream | 将被探测的 TStream |
|

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - The file type of provided stream

### <T>getAllTypes(Class<T> typeOfT) {#-T-getAllTypes-java.lang.Class-T--}
```
public static List<FileType> <T>getAllTypes(Class<T> typeOfT)
```


返回所有枚举值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List<com.groupdocs.conversion.filetypes.FileType> - 可枚举的文件类型


T
: 枚举对象类型。

### <T>getAllTypes(Class<T> typeOfT, FileType[] excluded) {#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType---}
```
public static List<FileType> <T>getAllTypes(Class<T> typeOfT, FileType[] excluded)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
| excluded | [FileType\[\]](../../com.groupdocs.conversion.filetypes/filetype) |  |

**Returns:**
java.util.List<com.groupdocs.conversion.filetypes.FileType>
### <T>getAllTypes(Class<T> typeOfT, FileType[][] excluded) {#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType--...-}
```
public static List<FileType> <T>getAllTypes(Class<T> typeOfT, FileType[][] excluded)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
| excluded | [FileType\[\]](../../com.groupdocs.conversion.filetypes/filetype) |  |

**Returns:**
java.util.List<com.groupdocs.conversion.filetypes.FileType>
### toString() {#toString--}
```
public String toString()
```


字符串表示


**Returns:**
java.lang.String - 文件类型的字符串表示

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


为源文件类型准备了默认加载选项


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions) - NULL if there is not file type specific load options

### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


为文件类型准备了默认转换选项


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions) - NULL if the conversion to the type not supported

### isObsolete() {#isObsolete--}
```
public boolean isObsolete()
```




**Returns:**
布尔
### equals(Enumeration other) {#equals-com.groupdocs.conversion.contracts.Enumeration-}
```
public boolean equals(Enumeration other)
```


确定两个对象实例是否相等。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) |  |

**Returns:**
布尔
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定两个对象实例是否相等。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
布尔
### hashCode() {#hashCode--}
```
public int hashCode()
```


作为默认的哈希函数。


**Returns:**
int
