---
title: "EBookFileType 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "定义电子书文档。"
type: docs
url: /zh/python-net/groupdocs.conversion.filetypes/ebookfiletype/
is_root: false
weight: 60
---


## EBookFileType class

定义电子书文档。包括以下文件类型：[`EBookFileType.epub`](/conversion/python-net/groupdocs.conversion.filetypes/ebookfiletype/epub/), [`EBookFileType.mobi`](/conversion/python-net/groupdocs.conversion.filetypes/ebookfiletype/mobi/), [`EBookFileType.azw3`](/conversion/python-net/groupdocs.conversion.filetypes/ebookfiletype/azw3/)。

EBookFileType 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/ebookfiletype/__init__/) | 初始化一个新的 [`EBookFileType`](/conversion/python-net/groupdocs.conversion.filetypes/ebookfiletype/) 实例用于序列化。 |

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
| [EPUB](/conversion/python-net/groupdocs.conversion.filetypes/ebookfiletype/epub/) | EPUB 扩展是一种电子书文件格式，为出版商和消费者提供标准的数字出版格式。该格式已非常普及，受到众多电子阅读器和软件应用的支持。了解更多关于此文件格式的信息。 |
| [MOBI](/conversion/python-net/groupdocs.conversion.filetypes/ebookfiletype/mobi/) | MOBI 文件格式是最广泛使用的电子书文件格式之一。该格式是对旧的 OEB（Open Ebook Format）格式的增强，并曾作为 Mobipocket Reader 的专有格式使用。了解更多关于此文件格式的信息。 |
| [AZW3](/conversion/python-net/groupdocs.conversion.filetypes/ebookfiletype/azw3/) | AZW3，也称为 Kindle Format 8（KF8），是为亚马逊 Kindle 设备开发的 AZW 电子书数字文件格式的改进版。该格式是对旧 AZW 文件的增强，仅在 Kindle Fire 设备上使用，并向后兼容其祖先文件格式，即 MOBI 和 AZW。了解更多关于此文件格式的信息。 |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | 未知文件类型（继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |

### 另见
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
