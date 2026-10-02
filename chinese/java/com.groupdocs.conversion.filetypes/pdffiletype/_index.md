---
title: "PdfFileType"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "定义 PDF 文档。"
type: docs
weight: 21
url: /zh/java/com.groupdocs.conversion.filetypes/pdffiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfFileType extends FileType implements Serializable
```

定义 Pdf 文档。包括以下文件类型：
[Pdf](../../com.groupdocs.conversion.filetypes/pdffiletype#Pdf),

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PdfFileType()](#PdfFileType--) | 序列化构造函数 |
|
## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Pdf](#Pdf) | 便携式文档格式（PDF）是一种由 Adobe 在 1990 年代创建的文档类型。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PdfFileType() {#PdfFileType--}
```
public PdfFileType()
```


序列化构造函数


### Pdf {#Pdf}
```
public static final PdfFileType Pdf
```


便携式文档格式（PDF）是一种由 Adobe 在 1990 年代创建的文档类型。该文件格式的目的是引入一种标准，用于以独立于应用软件、硬件以及操作系统的格式表示文档和其他参考资料。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/view/pdf)。


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
public static final FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
