---
title: "PdfConvertOptions 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "转换为 PDF 文件类型的选项。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/
is_root: false
weight: 340
---


## PdfConvertOptions class

转换为 PDF 文件类型的选项。

PdfConvertOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/__init__/) | 初始化一个新的 [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) 实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [dpi](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/dpi/) | 转换后所需的页面 DPI。默认分辨率为 96 dpi。 |
| [embed_full_fonts](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/embed_full_fonts/) | 此属性决定是否将完整字体文件嵌入 PDF，而不是子集。 |
| [fallback_page_size](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/fallback_page_size/) | 备用页面尺寸。 |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/format/) | 输入文档应转换为的目标文件类型。 |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/margin_settings/) | PDF 转换期间应用的页边距设置。 |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/orientation_settings/) | 方向设置。 |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/page_number/) | 开始转换的页码。 |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/pages/) | 要转换的页面索引列表；指定以转换特定页面。 |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/pages_count/) | 从 `page_number` 开始要转换的页面数量。 |
| [password](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/password/) | 用于保护已转换文档的密码。 |
| [pdf_options](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/pdf_options/) | PDF 特定的转换选项。 |
| [resize_mode](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/resize_mode/) | 缩放模式指定在更改页面大小时内容应如何缩放。默认是 AlignTopLeft（不缩放）。 |
| [rotate](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/rotate/) | 页面旋转。 |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/size_settings/) | PDF 转换期间使用的页面尺寸设置。 |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/watermark/) | 水印特定选项。 |

### 示例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Guides
使用 `PdfConvertOptions` 的任务指南：

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert a Document to Another Format](/conversion/python-net/guides/convert-document-to-another-format/)
* [Convert Files Within Document Containers](/conversion/python-net/guides/convert-files-within-document-containers/)
* [Add a Watermark to Converted Document](/conversion/python-net/guides/add-watermark-to-converted-document/)
* [Load File From Local Disk](/conversion/python-net/guides/load-file-from-local-disk/)
* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)

### 另见
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
