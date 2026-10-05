---
title: "PdfLoadOptions 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "加载 PDF 文档的选项。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.load/pdfloadoptions/
is_root: false
weight: 370
---


## PdfLoadOptions class

加载 PDF 文档的选项。

PdfLoadOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/__init__/) | 初始化 PdfLoadOptions 的新实例。 |

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
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/clear_built_in_document_properties/) | ClearBuiltInDocumentProperties 属性。 |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/clear_custom_document_properties/) | ClearCustomDocumentProperties 属性决定在加载 PDF 时是否清除自定义文档属性。 |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/convert_owned/) | ConvertOwned 标志实现 IDocumentsContainerLoadOptions.convert_owned。默认值为 False。 |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/convert_owner/) | 来自 [`IDocumentsContainerLoadOptions`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/) 的 ConvertOwner 标志。默认值为 True。 |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/default_font/) | PDF 文档的默认字体。如果缺少字体，将使用此字体。 |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/depth/) | 文档容器加载选项的深度。 |
| [flatten_all_fields](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/flatten_all_fields/) | flatten_all_fields 属性决定是否将 PDF 表单的所有字段展平。 |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/font_substitutes/) | 在转换 PDF 文档时用于替换特定字体的字体替代。 |
| [font_transformations](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/font_transformations/) | 在文档加载和字体替代后应用的字体转换，允许修改文档中的任何字体，包括已成功加载的字体。 |
| [format](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/format/) | 输入文档的文件类型。 |
| [hide_pdf_annotations](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/hide_pdf_annotations/) | 隐藏 PDF 文档注释的属性。 |
| [page_numbering](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/page_numbering/) | 转换后文档的页码生成标志（默认：False）。 |
| [password](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/password/) | 用于解除受保护文档保护的密码。 |
| [remove_embedded_files](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/remove_embedded_files/) | 移除嵌入文件的选项。 |
| [remove_javascript](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/remove_javascript/) | 移除 JavaScript 的选项。 |
| [reset_font_folders](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/reset_font_folders/) | 在加载文档之前重置字体文件夹的标志。 |

### 另见
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
