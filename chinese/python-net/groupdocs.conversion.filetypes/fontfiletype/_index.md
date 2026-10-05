---
title: "FontFileType 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "表示字体文档类型。"
type: docs
url: /zh/python-net/groupdocs.conversion.filetypes/fontfiletype/
is_root: false
weight: 100
---


## FontFileType class

表示字体文档类型。

包括以下类型：
- [`FontFileType.ttf`](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/ttf/)
- [`FontFileType.eot`](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/eot/)
- [`FontFileType.otf`](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/otf/)
- [`FontFileType.cff`](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/cff/)
- [`FontFileType.type1`](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/type1/)
- [`FontFileType.woff`](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/woff/)
- [`FontFileType.woff2`](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/woff2/)

了解更多关于字体格式 https://docs.fileformat.com/font/。

FontFileType 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/__init__/) | 初始化一个用于序列化的 FontFileType。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [compare_to](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to/) | 比较当前对象与其他对象。（继承自 [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)） |
| [compare_to_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to_object/) | （继承自 [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)） |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals/) | 实现由 [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals/) 定义的相等比较。（继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |
| [equals_enumeration](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals_enumeration/) | （继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals_object/) | （继承自 [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)） |
| [from_display_name](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_display_name/) | （继承自 [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)） |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_extension/) | 获取提供的文件扩展名对应的 FileType。（继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_filename/) | 返回指定 file_name 的 FileType。（继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_stream/) | 返回提供的文档流的 FileType。（继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |
| [from_value](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_value/) | （继承自 [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)） |
| [get_all](/conversion/python-net/groupdocs.conversion.filetypes/filetype/get_all/) | （继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/enumeration/get_hash_code/) | 提供默认的哈希函数。（继承自 [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)） |
| [to_string](/conversion/python-net/groupdocs.conversion.filetypes/filetype/to_string/) | 文件类型的字符串表示。（继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |

### 属性
| 属性 | 描述 |
| :- | :- |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/filetype/description/) | 文件类型描述。（继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/extension/) | 文件扩展名。（继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/filetype/family/) | 文件族。（继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/filetype/file_format/) | 文件格式。（继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |

### 字段
| 字段 | 描述 |
| :- | :- |
| [TTF](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/ttf/) | .ttf 扩展名的文件表示基于 TrueType 规范的字体文件。它最初由 Apple Computer, Inc 为 Mac OS 设计并发布，随后被 Microsoft 采用于 Windows OS。了解更多关于此文件格式的信息，请访问此处。 |
| [EOT](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/eot/) | .eot 扩展名的文件是嵌入文档的 OpenType 字体。它们主要用于网页等 Web 文件。该字体由 Microsoft 创建，并被包括 PowerPoint 演示文稿 .pps 文件在内的 Microsoft 产品支持。了解更多关于此文件格式的信息，请访问此处。 |
| [OTF](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/otf/) | .otf 扩展名的文件指的是 OpenType 字体格式。OTF 字体格式更具可伸缩性，并扩展了 TTF 格式在数字排版中的现有特性。该格式由 Microsoft 和 Adobe 开发，OTF 结合了 PostScript 和 TrueType 字体格式的特性。了解更多关于此文件格式的信息，请访问此处。 |
| [CFF](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/cff/) | .cff 扩展名的文件是紧凑字体格式（Compact Font Format），也称为 PostScript Type 1 或 CIDFont。CFF 充当容器，将多个字体一起存储在称为 FontSet 的单元中。了解更多关于此文件格式的信息，请访问此处。 |
| [TYPE1](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/type1/) | Type 1 字体是一种已废弃的 Adobe 技术，曾广泛用于基于桌面的出版软件和能够使用 PostScript 的打印机。虽然许多现代平台、网页浏览器和移动操作系统不再支持 Type 1 字体，但某些操作系统仍然支持。了解更多关于此文件格式的信息，请访问此处。 |
| [WOFF](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/woff/) | .woff 扩展名的文件是基于 Web Open Font Format（WOFF）的网络字体文件。它使用基于 TrueType（.TTF）或 OpenType（.OTT）字体类型的特定格式压缩容器。了解更多关于此文件格式的信息，请访问此处。 |
| [WOFF2](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/woff2/) | .woff 扩展名的文件是基于 Web Open Font Format（WOFF）的网络字体文件。它使用基于 TrueType（.TTF）或 OpenType（.OTT）字体类型的特定格式压缩容器。了解更多关于此文件格式的信息，请访问此处。 |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | 未知文件类型（继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |

### 另见
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
