---
title: "DocumentInfo 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "用于检索多态文档信息的基础实现。"
type: docs
url: /zh/python-net/groupdocs.conversion.contracts/documentinfo/
is_root: false
weight: 120
---


## DocumentInfo class

用于检索多态文档信息的基础实现。

实例由 `Converter.get_document_info()` 返回，并公开诸如格式、页数、创建日期、大小以及特定格式属性等元数据。

DocumentInfo 类型公开以下成员：

### 方法
| 方法 | 描述 |
| :- | :- |
| [get](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get/) |  |
| [get_file](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get_file/) |  |
| [get_string](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get_string/) |  |

### 属性
| 属性 | 描述 |
| :- | :- |
| [creation_date](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/creation_date/) | 文档的创建日期。 |
| [format](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/format/) | 文档的格式。 |
| [pages_count](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/pages_count/) | 文档的总页数。 |
| [property_names](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/property_names/) | 该属性实现了 [`IDocumentInfo.property_names`](/conversion/python-net/groupdocs.conversion.contracts/idocumentinfo/property_names/)。 |
| [size](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/size/) | 文档的字节大小。 |

### 示例

```python
from groupdocs.conversion import Converter

def show_document_info(path):
    with Converter(path) as converter:
        info = converter.get_document_info()
        print("Format:", info.format)
        print("Pages count:", info.pages_count)
        print("Creation date:", info.creation_date)
        print("Size (bytes):", info.size)

# 示例用法
show_document_info("./lorem-ipsum.txt")
```

### 另见
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
