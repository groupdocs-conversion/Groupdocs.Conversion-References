---
title: "SpreadsheetLoadOptions 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "提供加载 Spreadsheet 文档的选项。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/
is_root: false
weight: 440
---


## SpreadsheetLoadOptions class

提供加载 Spreadsheet 文档的选项。

SpreadsheetLoadOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/__init__/) | 初始化一个新的 [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/) 实例。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [clone](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clone/) | 克隆当前实例。 |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | 确定两个对象实例是否相等。 (继承自 [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (继承自 [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (继承自 [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | 用作默认的哈希函数。 (继承自 [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### 属性
| 属性 | 描述 |
| :- | :- |
| [all_columns_in_one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/all_columns_in_one_page_per_sheet/) | 该属性决定是否将工作表的所有列内容渲染在结果的单页上。 |
| [auto_fit_rows](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/auto_fit_rows/) | 转换时行会自动适配。 |
| [check_excel_restriction](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/) | 该属性决定在修改单元格相关对象时是否检查 Excel 文件限制。 |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clear_built_in_document_properties/) | ClearBuiltInDocumentProperties 属性决定在加载电子表格时是否清除内置文档属性。 |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clear_custom_document_properties/) | ClearCustomDocumentProperties 属性。 |
| [columns_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/columns_per_page/) | 每页列数用于将工作表拆分为多页；默认值为 0，表示禁用分页。 |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_owned/) | 该属性实现了 [`IDocumentsContainerLoadOptions.convert_owned`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owned/) ，默认值为 False。 |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_owner/) | 该属性实现了 [`IDocumentsContainerLoadOptions.convert_owner`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owner/) 。默认值为 True。 |
| [convert_range](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_range/) | 转换为非电子表格格式时的转换范围，例如 "D1:F8"。 |
| [culture_info](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/culture_info/) | 加载文件时使用的系统区域信息。 |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/default_font/) | 电子表格文档的默认字体。 |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/depth/) | 文档容器加载选项的深度。 |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/font_substitutes/) | 转换电子表格文档时使用的字体替代。 |
| [format](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/format/) | 输入文档的文件类型。 |
| [ignore_formula_calculation_errors](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/ignore_formula_calculation_errors/) | 该属性指示是否忽略公式计算错误。错误可能是不支持的函数、外部链接等。默认值为 False。 |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/margin_settings/) | 边距设置。 |
| [one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/one_page_per_sheet/) | 该属性指示是否将每个工作表的内容转换为 PDF 文档中的单页。默认值为 True。 |
| [optimize_pdf_size](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/optimize_pdf_size/) | 在转换为 PDF 时将此属性设为 True，可优化为更小的文件大小而非打印质量。 |
| [password](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/password/) | 用于解除受保护文档保护的密码。 |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/preserve_document_structure/) | 指示在转换为 PDF 时是否应保留文档结构的标志（默认值为 False）。 |
| [print_comments](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/print_comments/) | 工作表的批注打印方式。默认值为 PrintNoComments。 |
| [reset_font_folders](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/reset_font_folders/) | 加载文档前会重置字体文件夹。 |
| [rows_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/rows_per_page/) | 每页行数用于将工作表拆分为多页，默认值为 0 表示不分页。 |
| [sheet_indexes](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheet_indexes/) | 要转换的工作表索引列表。 |
| [sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheets/) | 要转换的工作表名称。 |
| [show_grid_lines](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_grid_lines/) | 在转换 Excel 文件时显示网格线的选项。 |
| [show_hidden_sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_hidden_sheets/) | 在转换 Excel 文件时显示隐藏工作表的选项。 |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/size_settings/) | 大小设置，按照 [`IPageSizeOptions`](/conversion/python-net/groupdocs.conversion.options/ipagesizeoptions/) 定义。 |
| [skip_empty_rows_and_columns](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_empty_rows_and_columns/) | 在转换时跳过空行和空列的设置。 |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_external_resources/) | 该属性实现了 [`IResourceLoadingOptions.skip_external_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/skip_external_resources/)。 |
| [skip_footers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_footers/) | 此属性决定在转换电子表格文档时是否跳过页脚。默认值：False。 |
| [skip_headers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_headers/) | 在转换电子表格文档时跳过页眉的选项。默认值：False。 |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/whitelisted_resources/) | 白名单资源，按照 [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/) 定义。 |

### 另见
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
