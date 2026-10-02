---
title: "WordProcessingFileType"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "定义文字处理文件，包含以纯文本或富文本格式的用户信息。"
type: docs
weight: 28
url: /zh/java/com.groupdocs.conversion.filetypes/wordprocessingfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class WordProcessingFileType extends FileType implements Serializable
```

定义了包含用户信息的纯文本或富文本格式的文字处理文件。纯文本文件格式仅包含未格式化的文本，无法应用字体或页面设置等。而富文本文件格式则允许设置字体类型、样式（粗体、斜体、下划线等）、页面边距、标题、项目符号和编号以及其他多种格式化功能。
包括以下文件类型：
[Doc](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Doc),
[Docm](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Docm),
[Docx](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Docx),
[Dot](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Dot),
[Dotm](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Dotm),
[Dotx](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Dotx),
[Odt](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Odt),
[Ott](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Ott),
[Rtf](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Rtf),
[Txt](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Txt),
[Md](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Md),
了解更多关于文字处理格式的信息，请点击[此处](../https://wiki.fileformat.com/word-processing)。


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [WordProcessingFileType()](#WordProcessingFileType--) | 序列化构造函数 |
|
## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Doc](#Doc) | 带有 .doc 扩展名的文件表示由 Microsoft Word 或其他文字处理软件以二进制文件格式生成的文档。 |
|
|  | [Docm](#Docm) | DOCM 文件是由 Microsoft Word 2007 及以上版本生成的、具备运行宏功能的文档。 |
|
|  | [Docx](#Docx) | DOCX 是一种广为人知的 Microsoft Word 文档格式。 |
|
|  | [Dot](#Dot) | 带有 .DOT 扩展名的文件是 Microsoft Word 创建的模板文件，具有预设格式，用于生成后续的 DOC 或 DOCX 文件。 |
|
|  | [Dotm](#Dotm) | 带有 DOTM 扩展名的文件表示由 Microsoft Word 2007 及以上版本创建的模板文件。 |
|
|  | [Dotx](#Dotx) | 带有 DOTX 扩展名的文件是由 Microsoft Word 创建的模板文件，用于预设设置以生成后续的 DOCX 文件。 |
|
|  | [Rtf](#Rtf) | 由 Microsoft 引入并记录的富文本格式（RTF）是一种用于在应用程序中编码格式化文本和图形的方法。 |
|
|  | [Odt](#Odt) | ODT 文件是一种基于 OpenDocument 文本文档格式的文字处理应用程序创建的文档类型。 |
|
|  | [Ott](#Ott) | 带有 OTT 扩展名的文件是符合 OASIS OpenDocument 标准格式的应用程序生成的模板文档。 |
|
|  | [Txt](#Txt) | 带有 .TXT 扩展名的文件是包含以行形式呈现的纯文本的文本文档。 |
|
|  | [Md](#Md) | 使用 Markdown 语言方言创建的文本文件保存为 .MD 或 .MARKDOWN 扩展名。 |
|
|  | [Ml](#Ml) | Ml 文件 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### WordProcessingFileType() {#WordProcessingFileType--}
```
public WordProcessingFileType()
```


序列化构造函数


### Doc {#Doc}
```
public static final WordProcessingFileType Doc
```


带有 .doc 扩展名的文件表示由 Microsoft Word 或其他文字处理软件以二进制文件格式生成的文档。
了解更多关于此文件格式的信息，请访问[here](../https://wiki.fileformat.com/word-processing/doc)。


### Docm {#Docm}
```
public static final WordProcessingFileType Docm
```


DOCM 文件是由 Microsoft Word 2007 及以上版本生成的、具备运行宏功能的文档。
了解更多关于此文件格式的信息，请访问[here](../https://wiki.fileformat.com/word-processing/docm)。


### Docx {#Docx}
```
public static final WordProcessingFileType Docx
```


DOCX 是 Microsoft Word 文档的知名格式。自 2007 年 Microsoft Office 2007 发布起，引入了该格式，其文档结构从纯二进制改为 XML 与二进制文件的组合。
了解更多关于此文件格式的信息，请访问[here](../https://wiki.fileformat.com/word-processing/docx)。


### Dot {#Dot}
```
public static final WordProcessingFileType Dot
```


带有 .DOT 扩展名的文件是 Microsoft Word 创建的模板文件，具有预设格式，用于生成后续的 DOC 或 DOCX 文件。
了解更多关于此文件格式的信息，请访问[here](../https://wiki.fileformat.com/word-processing/dot)。


### Dotm {#Dotm}
```
public static final WordProcessingFileType Dotm
```


带有 DOTM 扩展名的文件表示由 Microsoft Word 2007 及以上版本创建的模板文件。
了解更多关于此文件格式的信息，请访问[here](../https://wiki.fileformat.com/word-processing/dotm)。


### Dotx {#Dotx}
```
public static final WordProcessingFileType Dotx
```


带有 DOTX 扩展名的文件是由 Microsoft Word 创建的模板文件，用于预设设置以生成后续的 DOCX 文件。
了解更多关于此文件格式的信息，请访问[here](../https://wiki.fileformat.com/word-processing/dotx)。


### Rtf {#Rtf}
```
public static final WordProcessingFileType Rtf
```


由 Microsoft 引入并记录的富文本格式（RTF）是一种用于在应用程序中编码格式化文本和图形的方法。
了解更多关于此文件格式的信息，请访问[here](../https://wiki.fileformat.com/word-processing/rtf)。


### Odt {#Odt}
```
public static final WordProcessingFileType Odt
```


ODT 文件是一种基于 OpenDocument 文本文档格式的文字处理应用程序创建的文档类型。
了解更多关于此文件格式的信息，请访问[here](../https://wiki.fileformat.com/word-processing/odt)。


### Ott {#Ott}
```
public static final WordProcessingFileType Ott
```


带有 OTT 扩展名的文件是符合 OASIS OpenDocument 标准格式的应用程序生成的模板文档。
了解更多关于此文件格式的信息，请访问[here](../https://wiki.fileformat.com/word-processing/ott)。


### Txt {#Txt}
```
public static final WordProcessingFileType Txt
```


带有 .TXT 扩展名的文件是包含以行形式呈现的纯文本的文本文档。
了解更多关于此文件格式的信息，请访问[here](../https://wiki.fileformat.com/word-processing/txt)。


### Md {#Md}
```
public static final WordProcessingFileType Md
```


使用 Markdown 语言方言创建的文本文件保存为 .MD 或 .MARKDOWN 扩展名。MD 文件以纯文本格式保存，使用 Markdown 语言，其中还包括内联文本符号，定义文本的格式方式，如缩进、表格格式、字体和标题。了解更多关于此文件格式的信息，请访问[here](../https://wiki.fileformat.com/word-processing/md)。


### Ml {#Ml}
```
public static final WordProcessingFileType Ml
```


Ml 文件


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


为源文件类型准备了默认加载选项


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions<WordProcessingFileType> getConvertOptions()
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
