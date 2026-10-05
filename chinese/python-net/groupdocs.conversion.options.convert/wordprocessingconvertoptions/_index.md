---
title: "WordProcessingConvertOptions 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "转换为文字处理文件类型的选项。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/
is_root: false
weight: 620
---


## WordProcessingConvertOptions class

转换为文字处理文件类型的选项。

WordProcessingConvertOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/__init__/) | 初始化一个新的 [`WordProcessingConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/) 实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [dpi](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/dpi/) | 转换后所需的页面 DPI。默认分辨率为 96 dpi。 |
| [fallback_page_size](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/fallback_page_size/) | 备用页面尺寸。 |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/format/) | 输入文档应转换为的目标文件类型。 |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/margin_settings/) | 转换的页边距设置，由 [`IPageMarginOptions`](/conversion/python-net/groupdocs.conversion.options/ipagemarginoptions/) 表示。 |
| [markdown_options](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/markdown_options/) | Markdown 转换选项。 |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/orientation_settings/) | 方向设置。 |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/page_number/) | 开始转换的页码。 |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/pages/) | 要转换的页索引列表。应指定以转换特定页面。 |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/pages_count/) | 从 `PageNumber` 开始要转换的页数。 |
| [password](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/password/) | 用于保护已转换文档的密码。 |
| [pdf_recognition_mode](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/pdf_recognition_mode/) | 用于转换的 PDF 识别模式，实现了 [`IPdfRecognitionModeOptions.pdf_recognition_mode`](/conversion/python-net/groupdocs.conversion.options.convert/ipdfrecognitionmodeoptions/pdf_recognition_mode/)。 |
| [rtf_options](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/rtf_options/) | RTF 特定的转换选项。 |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/size_settings/) | 转换的尺寸设置。 |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/watermark/) | 水印特定选项。 |
| [zoom](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/zoom/) | 缩放比例（百分比）。 |

### 示例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import WordProcessingConvertOptions
from groupdocs.conversion.filetypes import WordProcessingFileType

with Converter("./business-plan.docx") as converter:
    options = WordProcessingConvertOptions()
    options.format = WordProcessingFileType.TXT
    converter.convert("./business-plan.txt", options)
```

### Guides
使用 `WordProcessingConvertOptions` 的任务指南：

* [Convert a Document to Another Format](/conversion/python-net/guides/convert-document-to-another-format/)

### 另见
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
