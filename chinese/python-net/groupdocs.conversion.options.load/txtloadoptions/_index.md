---
title: "TxtLoadOptions 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "加载 Txt 文档的选项。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.load/txtloadoptions/
is_root: false
weight: 500
---


## TxtLoadOptions class

加载 Txt 文档的选项。

纯文本的字体配置：

由于 TXT 文件不包含字体信息，请使用 DefaultTextFont 指定在转换期间渲染纯文本内容的字体。

TxtLoadOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/__init__/) | 初始化一个新的 [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/) 实例。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | 确定两个对象实例是否相等。 (继承自 [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (继承自 [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (继承自 [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | 用作默认的哈希函数。 (继承自 [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### 属性
| 属性 | 描述 |
| :- | :- |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/default_font/) | 在转换期间渲染纯文本内容时使用的字体。默认：Arial 10pt。 |
| [detect_numbering_with_whitespaces](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/detect_numbering_with_whitespaces/) | 该属性指定在转换纯文本文档时如何识别编号列表项。默认值为 True。 |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/encoding/) | 加载 Txt 文档时使用的编码。可以为 None。默认是 None。 |
| [format](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/format/) | 输入文档的文件类型。 |
| [leading_spaces_options](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/leading_spaces_options/) | 处理前导空格的首选选项。 |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/margin_settings/) | 边距设置，定义于 [`IPageMarginOptions`](/conversion/python-net/groupdocs.conversion.options/ipagemarginoptions/)。 |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/size_settings/) | 加载 TXT 文档的页面尺寸选项。 |
| [trailing_spaces_options](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/trailing_spaces_options/) | 处理尾随空格的首选选项。默认值为 [`TxtTrailingSpacesOptions.trim`](/conversion/python-net/groupdocs.conversion.options.load/txttrailingspacesoptions/)。 |

### 另见
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
