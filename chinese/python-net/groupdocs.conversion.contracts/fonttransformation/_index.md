---
title: "FontTransformation 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "描述字体转换配置，包括字体属性，在文档加载和字体替代后应用。"
type: docs
url: /zh/python-net/groupdocs.conversion.contracts/fonttransformation/
is_root: false
weight: 200
---


## FontTransformation class

描述字体转换配置，包括字体属性，在文档加载和字体替代后应用。

FontTransformation 类型公开以下成员：

### 方法
| 方法 | 描述 |
| :- | :- |
| [create](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create/#original_font-replacement_font) | 创建一个字体转换，使用完全匹配的字体（大小和样式必须匹配）。 |
| [create_by_name](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create_by_name/#original_font_name-replacement_font_name) | 仅通过名称创建字体转换，匹配任何大小和样式，且替换字体保留原始字体的大小和样式。 |
| [create_flexible](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create_flexible/#original_font-replacement_font-match_any_size-match_any_style) | 创建一个具有灵活匹配选项的字体转换。 |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | 确定两个对象实例是否相等。 (继承自 [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (继承自 [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (继承自 [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | 用作默认的哈希函数。 (继承自 [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### 属性
| 属性 | 描述 |
| :- | :- |
| [match_any_size](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/match_any_size/) | 该属性指示是否匹配原始字体名称的任何字体大小（true），或仅匹配 `OriginalFont` 中指定的确切字体大小（false）。 |
| [match_any_style](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/match_any_style/) | 该属性决定是否匹配原始字体的任何字体样式（粗体、斜体、下划线）（True），或需要 `OriginalFont` 中指定的确切字体样式（False）。 |
| [original_font](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/original_font/) | 要匹配和替换的原始字体规范。 |
| [replacement_font](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/replacement_font/) | 替换字体规范。 |

### 另见
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
