---
title: "PublisherFileType"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "定义 Publisher 文档。"
type: docs
weight: 24
url: /zh/java/com.groupdocs.conversion.filetypes/publisherfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PublisherFileType extends FileType implements Serializable
```

定义 Publisher 文档。
包括以下类型：
[Pub](../../com.groupdocs.conversion.filetypes/publisherfiletype#Pub),
了解更多关于字体格式的信息，请点击[此处](../https://wiki.fileformat.com/publisher)。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PublisherFileType()](#PublisherFileType--) | 序列化构造函数 |
|
## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Pub](#Pub) | PUB 文件是 Microsoft Publisher 文档文件格式。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PublisherFileType() {#PublisherFileType--}
```
public PublisherFileType()
```


序列化构造函数


### Pub {#Pub}
```
public static final PublisherFileType Pub
```


PUB 文件是 Microsoft Publisher 文档文件格式。它用于创建多种设计布局文档，例如时事通讯、传单、手册、明信片等。PUB 文件可以包含文本、光栅和矢量图像。了解更多关于此文件格式的信息，请点击[此处](../https://docs.fileformat.com/publisher/pub/)。


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


为源文件类型准备了默认加载选项


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
