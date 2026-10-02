---
title: "Web文件类型"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "定义网页文档。"
type: docs
weight: 27
url: /zh/java/com.groupdocs.conversion.filetypes/webfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class WebFileType extends FileType implements Serializable
```

定义网页文档。
包括以下类型：
[Xml](../../com.groupdocs.conversion.filetypes/webfiletype#Xml),
[Json](../../com.groupdocs.conversion.filetypes/webfiletype#Json),
[Html](../../com.groupdocs.conversion.filetypes/webfiletype#Html),
[Htm](../../com.groupdocs.conversion.filetypes/webfiletype#Htm),
[Mht](../../com.groupdocs.conversion.filetypes/webfiletype#Mht),
[Mhtml](../../com.groupdocs.conversion.filetypes/webfiletype#Mhtml),
[Chm](../../com.groupdocs.conversion.filetypes/webfiletype#Chm),
了解更多关于网络格式的信息，请点击[此处](../https://wiki.fileformat.com/web)。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [WebFileType()](#WebFileType--) | 序列化构造函数 |
|
## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Xml](#Xml) | XML 代表可扩展标记语言，它类似于 HTML，但在使用标签定义对象方面有所不同。 |
|
|  | [Json](#Json) | JSON（JavaScript 对象表示法）是一种开放标准文件格式，用于共享数据，使用人类可读的文本来存储和传输数据。 |
|
|  | [Html](#Html) | HTML（超文本标记语言）是用于在浏览器中显示的网页的扩展名。 |
|
|  | [Htm](#Htm) | HTM（超文本标记语言）是用于在浏览器中显示的网页的扩展名。 |
|
|  | [Mht](#Mht) | 扩展名为 MHTML 的文件表示一种网页存档格式，可由多种不同的应用程序创建。 |
|
|  | [Mhtml](#Mhtml) | 扩展名为 MHTML 的文件表示一种网页存档格式，可由多种不同的应用程序创建。 |
|
|  | [Chm](#Chm) | CHM 文件格式代表 Microsoft HTML 帮助文件，由一系列 HTML 页面组成。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### WebFileType() {#WebFileType--}
```
public WebFileType()
```


序列化构造函数


### Xml {#Xml}
```
public static final WebFileType Xml
```


XML 代表可扩展标记语言，它类似于 HTML，但在使用标签定义对象方面有所不同。了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/web/xml)。


### Json {#Json}
```
public static final WebFileType Json
```


JSON（JavaScript 对象表示法）是一种开放标准文件格式，用于共享数据，使用人类可读的文本来存储和传输数据。了解更多关于此文件格式的信息，请点击[此处](../https://docs.fileformat.com/web/json)。


### Html {#Html}
```
public static final WebFileType Html
```


HTML（超文本标记语言）是用于在浏览器中显示的网页的扩展名。了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/web/html)。


### Htm {#Htm}
```
public static final WebFileType Htm
```


HTM（超文本标记语言）是用于在浏览器中显示的网页的扩展名。了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/web/html)。


### Mht {#Mht}
```
public static final WebFileType Mht
```


扩展名为 MHTML 的文件表示一种网页存档格式，可由多种不同的应用程序创建。该格式被称为存档格式，因为它将网页 HTML 代码及相关资源保存到单个文件中。了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/web/mhtml)。


### Mhtml {#Mhtml}
```
public static final WebFileType Mhtml
```


扩展名为 MHTML 的文件表示一种网页存档格式，可由多种不同的应用程序创建。该格式被称为存档格式，因为它将网页 HTML 代码及相关资源保存到单个文件中。了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/web/mhtml)。


### Chm {#Chm}
```
public static final WebFileType Chm
```


CHM 文件格式代表 Microsoft HTML 帮助文件，由一系列 HTML 页面组成。它提供索引，以便快速访问主题并导航到帮助文档的不同部分。了解更多关于此文件格式的信息，请点击[此处](../https://docs.fileformat.com/web/chm)。


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


为源文件类型准备了默认加载选项


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


为文件类型准备了默认转换选项


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
