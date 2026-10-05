---
title: "TsvLoadOptions 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "表示加载 TSV 文档的选项。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.load/tsvloadoptions/
is_root: false
weight: 480
---


## TsvLoadOptions class

表示加载 TSV 文档的选项。

TsvLoadOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/__init__/) | 初始化一个新的 [`TsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/) 实例。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [clone](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clone/) | 克隆当前实例。（继承自 [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)） |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | 确定两个对象实例是否相等。 (继承自 [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (继承自 [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (继承自 [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | 用作默认的哈希函数。 (继承自 [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### 属性
| 属性 | 描述 |
| :- | :- |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/clear_built_in_document_properties/) | 此属性从文档中移除内置的元数据属性。 |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/clear_custom_document_properties/) | 此属性从文档中移除自定义的元数据属性。 |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/convert_owned/) | 此选项控制是否必须转换文档容器中的拥有文档。 |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/convert_owner/) | 此选项控制是否必须转换文档的容器本身；如果为 true，容器将成为第一个被转换的文档。 |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/default_font/) | 缺少字体时使用的字体。 |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/depth/) | 此选项控制执行转换的深度层级数。 |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/font_substitutes/) | 字体替代。 |
| [format](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/format/) | 输入文档的文件类型。 |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/margin_settings/) | 页面边距设置。 |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/size_settings/) | 页面尺寸设置。 |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/skip_external_resources/) | 此属性决定是否加载外部资源；如果为 True，除 [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/) 列表中的资源外，所有外部资源都不会被加载。默认值：True。 |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/whitelisted_resources/) | 始终会被加载的外部资源。 |
| [all_columns_in_one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/all_columns_in_one_page_per_sheet/) | 此属性决定是否在结果中将工作表的所有列内容渲染在单页上。（继承自 [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)） |
| [auto_fit_rows](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/auto_fit_rows/) | 转换时行会自动适应。（继承自 [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)） |
| [check_excel_restriction](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/) | 此属性决定在修改单元格相关对象时是否检查 Excel 文件的限制。（继承自 [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)） |
| [columns_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/columns_per_page/) | 用于将工作表拆分为多页的每页列数；默认值为 0，表示禁用分页。（继承自 [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)） |
| [convert_range](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_range/) | 转换为非电子表格格式时要转换的范围，例如 "D1:F8"。（继承自 [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)） |
| [culture_info](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/culture_info/) | 加载文件时使用的系统区域性信息。（继承自 [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)） |
| [ignore_formula_calculation_errors](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/ignore_formula_calculation_errors/) | 该属性指示是否忽略公式计算错误。错误可能是不受支持的函数、外部链接等。默认值为 False。（继承自 [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)） |
| [one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/one_page_per_sheet/) | 该属性指示是否将每个工作表的内容转换为 PDF 文档中的单页。默认值为 True。（继承自 [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)） |
| [optimize_pdf_size](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/optimize_pdf_size/) | 在转换为 PDF 时，如果设置为 True，转换将优化为更小的文件大小而非打印质量。（继承自 [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)） |
| [password](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/password/) | 用于解除受保护文档的密码。（继承自 [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)） |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/preserve_document_structure/) | 指示在转换为 PDF 时是否应保留文档结构的标志（默认值为 False）。（继承自 [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)） |
| [print_comments](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/print_comments/) | 工作表的注释打印方式。默认值为 PrintNoComments。（继承自 [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)） |
| [reset_font_folders](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/reset_font_folders/) | 在加载文档之前会重置字体文件夹。（继承自 [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)） |
| [rows_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/rows_per_page/) | 用于将工作表拆分为页面的每页行数，默认值为 0 表示不分页。（继承自 [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)） |
| [sheet_indexes](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheet_indexes/) | 要转换的工作表索引列表。（继承自 [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)） |
| [sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheets/) | 要转换的工作表名称。（继承自 [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)） |
| [show_grid_lines](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_grid_lines/) | 转换 Excel 文件时显示网格线的选项。（继承自 [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)） |
| [show_hidden_sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_hidden_sheets/) | 转换 Excel 文件时显示隐藏工作表的选项。（继承自 [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)） |
| [skip_empty_rows_and_columns](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_empty_rows_and_columns/) | 转换时跳过空行和空列的设置。（继承自 [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)） |
| [skip_footers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_footers/) | 该属性决定在转换电子表格文档时是否跳过页脚。默认值：False。（继承自 [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)） |
| [skip_headers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_headers/) | 转换电子表格文档时跳过页眉的选项。默认值：False。（继承自 [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)） |

### 另见
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
