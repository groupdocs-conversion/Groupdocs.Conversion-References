---
title: "FontFileType"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "定义字体文档。"
type: docs
weight: 17
url: /zh/java/com.groupdocs.conversion.filetypes/fontfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class FontFileType extends FileType implements Serializable
```

定义字体文档。
包括以下类型：
[Ttf](../../com.groupdocs.conversion.filetypes/fontfiletype#Ttf),
[Eot](../../com.groupdocs.conversion.filetypes/fontfiletype#Eot),
[Otf](../../com.groupdocs.conversion.filetypes/fontfiletype#Otf),
[Cff](../../com.groupdocs.conversion.filetypes/fontfiletype#Cff),
[Type1](../../com.groupdocs.conversion.filetypes/fontfiletype#Type1),
[Woff](../../com.groupdocs.conversion.filetypes/fontfiletype#Woff),
[Woff2](../../com.groupdocs.conversion.filetypes/fontfiletype#Woff2),
了解更多关于字体格式的信息 [here](../https://wiki.fileformat.com/font)。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [FontFileType()](#FontFileType--) | 序列化构造函数 |
|
## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Ttf](#Ttf) | 带有 .ttf 扩展名的文件表示基于 TrueType 规范的字体技术的字体文件。 |
|
|  | [Eot](#Eot) | 带有 .eot 扩展名的文件是嵌入文档中的 OpenType 字体。 |
|
|  | [Otf](#Otf) | 带有 .otf 扩展名的文件指的是 OpenType 字体格式。 |
|
|  | [Cff](#Cff) | 带有 .cff 扩展名的文件是紧凑字体格式，也称为 PostScript Type 1 或 CIDFont。 |
|
|  | [Type1](#Type1) | Type 1 字体是一种已弃用的 Adobe 技术，曾广泛用于基于桌面的出版软件和能够使用 PostScript 的打印机。 |
|
|  | [Woff](#Woff) | 带有 .woff 扩展名的文件是基于 Web Open Font Format (WOFF) 的网络字体文件。 |
|
|  | [Woff2](#Woff2) | 带有 .woff 扩展名的文件是基于 Web Open Font Format (WOFF) 的网络字体文件。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### FontFileType() {#FontFileType--}
```
public FontFileType()
```


序列化构造函数


### Ttf {#Ttf}
```
public static final FontFileType Ttf
```


带有 .ttf 扩展名的文件表示基于 TrueType 规范的字体技术的字体文件。它最初由 Apple Computer, Inc 为 Mac OS 设计并发布，随后被 Microsoft 采用于 Windows OS。了解更多关于此文件格式的信息 [here](../https://docs.fileformat.com/font/ttf/)。


### Eot {#Eot}
```
public static final FontFileType Eot
```


带有 .eot 扩展名的文件是嵌入文档中的 OpenType 字体。这些字体主要用于网页等网络文件。它由 Microsoft 创建，并受到包括 PowerPoint 演示文稿 .pps 文件在内的 Microsoft 产品的支持。了解更多关于此文件格式的信息 [here](../https://docs.fileformat.com/font/eot/)。


### Otf {#Otf}
```
public static final FontFileType Otf
```


带有 .otf 扩展名的文件指的是 OpenType 字体格式。OTF 字体格式更具可伸缩性，并扩展了 TTF 格式在数字排版中的现有功能。该格式由 Microsoft 和 Adobe 开发，OTF 结合了 PostScript 和 TrueType 字体格式的特性。了解更多关于此文件格式的信息 [here](../https://docs.fileformat.com/font/otf/)。


### Cff {#Cff}
```
public static final FontFileType Cff
```


带有 .cff 扩展名的文件是紧凑字体格式，也称为 PostScript Type 1 或 CIDFont。CFF 充当容器，可将多个字体存储在称为 FontSet 的单一单元中。了解更多关于此文件格式的信息 [here](../https://docs.fileformat.com/font/cff/)。


### Type1 {#Type1}
```
public static final FontFileType Type1
```


Type 1 字体是一种已弃用的 Adobe 技术，曾广泛用于基于桌面的出版软件和能够使用 PostScript 的打印机。虽然许多现代平台、网页浏览器和移动操作系统不再支持 Type 1 字体，但某些操作系统仍然支持。了解更多关于此文件格式的信息 [here](../https://docs.fileformat.com/font/type1/)。


### Woff {#Woff}
```
public static final FontFileType Woff
```


带有 .woff 扩展名的文件是基于 Web Open Font Format (WOFF) 的网络字体文件。它具有基于 TrueType (.TTF) 或 OpenType (.OTT) 字体类型的特定格式压缩容器。了解更多关于此文件格式的信息 [here](../https://docs.fileformat.com/font/woff/)。


### Woff2 {#Woff2}
```
public static final FontFileType Woff2
```


带有 .woff 扩展名的文件是基于 Web Open Font Format (WOFF) 的网络字体文件。它具有基于 TrueType (.TTF) 或 OpenType (.OTT) 字体类型的特定格式压缩容器。了解更多关于此文件格式的信息 [here](../https://docs.fileformat.com/font/woff/)。


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
