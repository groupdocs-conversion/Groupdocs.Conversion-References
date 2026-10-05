---
title: "CadDocumentInfo 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "包含 Cad 文档元数据。"
type: docs
url: /zh/python-net/groupdocs.conversion.contracts/caddocumentinfo/
is_root: false
weight: 50
---


## CadDocumentInfo class

包含 Cad 文档元数据。

[`DocumentInfo.pages_count`](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/pages_count/) counts the sheets the drawing offers under the load options it was read with.

如果没有显式[`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) 这些工作表是模型空间，模型空间始终可绘制，因此始终是工作表，加上每个纸张空间布局，其存储的页面设置具有正的宽度和高度，并通过[`CadLoadOptions.layout_scope`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/) 进行限制。显式布局名称则直接获胜：工作表随后成为绘图所携带的提供的名称，按顺序匹配，既不受范围也不受页面设置的筛选。

对于 DWF，会报告已发布的页面集合。当请求的范围未匹配到任何提供页面的图纸工作表时，计数为零，即小于一的计数为零；此时元数据仍然描述该图纸，而零表示范围未选择任何内容，而不是让请求图纸内容的调用者失败。在相同的加载选项下，转换会失败。

因此计数并不是[`CadDocumentInfo.layouts`](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layouts/) 的大小，该属性列出绘图携带的每个绘图配置，包括那些无法发布为工作表的配置，并且它并不预测特定转换会输出多少页。

CadDocumentInfo 类型公开以下成员：

### 方法
| 方法 | 描述 |
| :- | :- |
| [get](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get/) |  |
| [get_file](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get_file/) |  |
| [get_string](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get_string/) |  |

### 属性
| 属性 | 描述 |
| :- | :- |
| [creation_date](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/creation_date/) | 文档创建日期。 |
| [format](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/format/) | 文档格式。 |
| [height](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/height/) | CAD 文档的高度。 |
| [layers](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layers/) | 文档中的图层。 |
| [layouts](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layouts/) | 文档中的布局。 |
| [pages_count](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/pages_count/) | 文档页数。 |
| [property_names](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/property_names/) | 当前文档信息可检索的所有属性的可枚举集合。 |
| [size](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/size/) | 文档大小（字节）。 |
| [width](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/width/) | CAD 文档的宽度。 |

### 另见
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
