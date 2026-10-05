---
title: "FontSubstitutionContext 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "描述在加载或渲染源文档时发生的单个字体替代。"
type: docs
url: /zh/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/
is_root: false
weight: 190
---


## FontSubstitutionContext class

描述在加载或渲染源文档时发生的单个字体替代。

实例被传递给 [`ConversionEvents.on_font_substituted`](/conversion/python-net/groupdocs.conversion/conversionevents/on_font_substituted/)。

FontSubstitutionContext 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/__init__/#source_file_name-original_font_name-substitute_font_name-reason) | 初始化一个新的 FontSubstitutionContext。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [original_font_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/original_font_name/) | 源文档引用的字体名称，但在转换管道中不可用。 |
| [reason](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/) | 替换消息完全按照转换管道报告的原样呈现，未解析。 |
| [source_file_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/source_file_name/) | 正在转换的源文档的文件名。当源以非 `io.RawIOBase` 的流形式提供时，此处包含生成的标识符，而非真实的文件名。 |
| [substitute_font_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/substitute_font_name/) | 用于替代的字体名称。对于引擎仅以描述性文本报告替代的文档，可能为 None——在这种情况下请阅读 [`FontSubstitutionContext.reason`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/)。 |

### 另见
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
