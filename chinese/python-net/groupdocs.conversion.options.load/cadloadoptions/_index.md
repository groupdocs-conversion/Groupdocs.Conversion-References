---
title: "CadLoadOptions 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "提供加载 CAD 文档的选项。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.load/cadloadoptions/
is_root: false
weight: 60
---


## CadLoadOptions class

提供加载 CAD 文档的选项。

CadLoadOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/__init__/) | 初始化一个新的 [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/) 类实例。 |

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
| [background_color](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/background_color/) | 背景颜色。 |
| [ctb_sources](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/ctb_sources/) | CTB 源。 |
| [draw_color](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/draw_color/) | 前景颜色。 |
| [draw_type](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/draw_type/) | 绘图类型。 |
| [format](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/format/) | 输入文档的文件类型。 |
| [layout_names](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) | 要转换的布局名称。 |
| [layout_scope](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/) | 确定要转换的绘图空间的布局范围。默认是[`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/)，它不限制转换。当提供[`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/)时会被忽略，因为显式的布局名称始终优先。`None` 值将被视为[`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/)。 |

### 另见
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
