---
title: "EBookFileType"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "定义用于 3D 图形文件格式的 CAD（Computer Aided Design）文档，可能包含 2D 或 3D 设计。"
type: docs
weight: 14
url: /zh/java/com.groupdocs.conversion.filetypes/ebookfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class EBookFileType extends FileType implements Serializable
```

定义 CAD 文档（计算机辅助设计），用于 3D 图形文件格式，可能包含 2D 或 3D 设计。
包括以下类型：
[Epub](../../com.groupdocs.conversion.filetypes/ebookfiletype#Epub),
[Mobi](../../com.groupdocs.conversion.filetypes/ebookfiletype#Mobi),
[Azw3](../../com.groupdocs.conversion.filetypes/ebookfiletype#Azw3),
了解更多关于 CAD 格式的信息，请点击[此处](../https://wiki.fileformat.com/cad)。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [EBookFileType()](#EBookFileType--) | 序列化构造函数 |
|
## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Epub](#Epub) | EPUB 扩展名是一种电子书文件格式，为出版商和消费者提供标准的数字出版格式。 |
|
|  | [Mobi](#Mobi) | MOBI 文件格式是最广泛使用的电子书文件格式之一。 |
|
|  | [Azw3](#Azw3) | AZW3，也称为 Kindle Format 8（KF8），是为 Amazon Kindle 设备开发的 AZW 电子书数字文件格式的改进版本。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### EBookFileType() {#EBookFileType--}
```
public EBookFileType()
```


序列化构造函数


### Epub {#Epub}
```
public static final EBookFileType Epub
```


EPUB 扩展名是一种电子书文件格式，为出版商和消费者提供标准的数字出版格式。该格式现已非常普及，受到众多电子阅读器和软件应用的支持。了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/ebook/epub)。


### Mobi {#Mobi}
```
public static final EBookFileType Mobi
```


MOBI 文件格式是最广泛使用的电子书文件格式之一。该格式是对旧的 OEB（Open Ebook Format）格式的改进，并曾作为 Mobipocket Reader 的专有格式。了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/ebook/mobi)。


### Azw3 {#Azw3}
```
public static final EBookFileType Azw3
```


AZW3，也称为 Kindle Format 8（KF8），是为 Amazon Kindle 设备开发的 AZW 电子书数字文件格式的改进版本。该格式是对旧 AZW 文件的升级，仅在 Kindle Fire 设备上使用，并向后兼容其前身文件格式，即 MOBI 和 AZW。了解更多关于此文件格式的信息，请点击[此处](../https://docs.fileformat.com/ebook/azw3/)。


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
