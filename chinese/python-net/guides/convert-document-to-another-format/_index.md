---
title: "将文档转换为其他格式"
linkTitle: "Convert to Another Format"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "将单个文档从一种格式转换为另一种格式，可选地使用 ConvertOptions 上的 pages / page_number / pages_count 属性选择特定页面或页面范围，使用适用于 .NET 的 Python 版 GroupDocs.Conversion。"
type: docs
url: /zh/python-net/guides/convert-document-to-another-format/
is_root: false
weight: 40
---


本文档主题介绍单个文档转换为另一种格式的过程，输出仅生成一个文档。下图展示了将文件从一种格式转换为另一种格式的流程：

flowchart LR
%% Nodes
A[\"Input Document (e.g. DOCX)\"]
B[\"Conversion\"]
C[\"Converted Document (e.g. PDF)\"]

%% 节点之间的边连接
A --> B --> C

要转换并保存文档，请使用以下 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 类方法：

- **`convert(file_path, convert_options)`**: Converts a document to a specified single output format and saves it to a file, such as converting a DOCX to PDF.
- **`convert(stream, convert_options)`**: Converts the document and writes it to a provided stream instead of a file path.

## Convert a Complete Document 

以下 [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) 类列表可用于将文档转换为特定的单一输出格式：

- **PdfConvertOptions** – Options for converting to [PDF]() format.
- **WordProcessingConvertOptions** – Options for converting to [Word Processing]() formats.
- **SpreadsheetConvertOptions** – Options for converting to [Spreadsheet]() formats.
- **PresentationConvertOptions** – Options for converting to [Presentation]() formats.
- **ImageConvertOptions** – Options for converting to [Image]() formats (e.g., PNG, JPEG).
- **WebConvertOptions** – Options for converting to [Web]() formats (e.g., HTML).
- **PageDescriptionLanguageConvertOptions** – Options for converting to [Page Description Language]() formats (e.g., PostScript).
- **EBookConvertOptions** – Options for converting to [EBook]() formats (e.g., EPUB, MOBI).
- **EmailConvertOptions** – Options for converting to [Email]() formats (e.g., EML, MSG).
- **DiagramConvertOptions** – Options for converting to [Diagram]() formats (e.g., VSDX).
- **CadConvertOptions** – Options for converting to [CAD]() formats (e.g., DWG).
- **ThreeDConvertOptions** – Options for converting to [3D]() formats.
- **ProjectManagementConvertOptions** – Options for converting to [Project Management]() formats (e.g., MPP).
- **GisConvertOptions** – Options for converting to [GIS]() formats.
- **FontConvertOptions** – Options for converting to [Font]() formats (e.g., TTF, OTF).
- **FinanceConvertOptions** – Options for converting to [Finance]() formats (e.g., XBRL).
- **CompressionConvertOptions** – Options for converting to [Compression]() formats (e.g., ZIP).
- **NoConvertOptions** – A special option class that instructs the converter to copy the source document without any modifications.

### Example 1: Convert a Document to Another Format

以下示例演示如何将 DOCX 文件转换为 PDF：

{{< tabs \"example-1\">}}
{{< tab "convert_document_to_another_format.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document_to_another_format():
    # 实例化 Converter 并使用输入文档 
    with Converter("./business-plan.docx") as converter:
        # 实例化转换选项以定义输出格式
        pdf_convert_options = PdfConvertOptions()
        
        # 将输入文档转换为 PDF
        converter.convert("./business-plan.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_document_to_another_format()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` 是本示例使用的示例文件。点击 [此处](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) 下载。

{{< /tab >}}
{{< tab \"business-plan.pdf\" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_document_to_another_format/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

### Example 2: Specify Output Format

默认情况下，所有 [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) 类都有各自的默认目标格式。例如，[WordProcessingConvertOptions](https://reference.groupdocs.com/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/) 的默认输出格式是 [DOCX](https://reference.groupdocs.com/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/docx/)。

要在同一格式系列中设置不同的输出格式，请使用 `format` 属性。以下示例演示在将 `DOCX` 文件转换时如何将目标格式指定为 `TXT`：

{{< tabs "example-2">}}
{{< tab "specify_output_format.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import WordProcessingConvertOptions
from groupdocs.conversion.filetypes import WordProcessingFileType

def specify_output_format():
    # 实例化 Converter 并使用输入文档 
    with Converter("./business-plan.docx") as converter:
        # 实例化转换选项以定义输出格式，默认情况下为 DOCX
        word_convert_options = WordProcessingConvertOptions()
        # 将同一格式系列中的输出格式从 DOCX 更改为 TXT
        word_convert_options.format = WordProcessingFileType.TXT
        
        # 将输入文档转换为 TXT
        converter.convert("./business-plan.txt", word_convert_options)    

if __name__ == "__main__":
    specify_output_format()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` 是本示例使用的示例文件。点击 [此处](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) 下载。

{{< /tab >}}
{{< tab "business-plan.txt" >}}
```text
﻿HOME BASED

PROFESSIONAL SERVICES

Business Plan

[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/specify_output_format/business-plan.txt)
{{< /tab >}}
{{< /tabs >}}

## Specify Document Pages to Convert

了解如何在 [Getting Document Information]() 文档主题中获取文档页数。

要转换特定的文档页，您可以使用以下 [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) 类，它们提供 `pages`、`page_number` 和 `pages_count` 属性。这些选项允许您指定单个页或页范围进行转换。

- **PdfConvertOptions** – Options for converting to [PDF]() format.
- **ImageConvertOptions** – Options for converting to [Image]() formats (e.g., PNG, JPEG).
- **WordProcessingConvertOptions** – Options for converting to [Word Processing]() formats.
- **SpreadsheetConvertOptions** – Options for converting to [Spreadsheet]() formats.
- **PresentationConvertOptions** – Options for converting to [Presentation]() formats.
- **WebConvertOptions** – Options for converting to [Web]() formats (e.g., HTML).
- **EBookConvertOptions** – Options for converting to [EBook]() formats (e.g., EPUB, MOBI).
- **DiagramConvertOptions** – Options for converting to [Diagram]() formats (e.g., VSDX).
- **PageDescriptionLanguageConvertOptions** – Options for converting to [Page Description Language]() formats (e.g., PostScript).
- **CadConvertOptions** – Options for converting to [CAD]() formats (e.g., DWG).
- **ThreeDConvertOptions** – Options for converting to [3D]() formats.
- **FinanceConvertOptions** – Options for converting to [Finance]() formats (e.g., XBRL).

### Example 1: Convert Specific Document Pages to Another Format

您可以指定要转换的文档页，如下例所示：

{{< tabs "example-3">}}
{{< tab "convert_specific_document_pages.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_specific_document_pages():
    # 实例化 Converter 并使用输入文档 
    with Converter("./business-plan.docx") as converter:
        # 实例化转换选项以定义输出格式
        pdf_convert_options = PdfConvertOptions()
        # 指定要转换的文档页
        pdf_convert_options.pages = [1, 3, 5]

        # 将输入文档的指定页转换为 PDF
        converter.convert("./pages-1-3-5.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_specific_document_pages()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` 是本示例使用的示例文件。点击 [此处](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) 下载。

{{< /tab >}}
{{< tab "pages-1-3-5.pdf" >}}
```text
Binary file (PDF, 156 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_specific_document_pages/pages-1-3-5.pdf)
{{< /tab >}}
{{< /tabs >}}

### Example 2: Convert N Consecutive Pages

作为替代，您可以指定一系列连续的页进行转换，如下例所示：

{{< tabs "example-4">}}
{{< tab "convert_consecutive_document_pages.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_consecutive_document_pages():
    # 实例化 Converter 并使用输入文档 
    with Converter("./business-plan.docx") as converter:
        # 实例化转换选项以定义输出格式
        pdf_convert_options = PdfConvertOptions()
        # 指定起始页和要转换的页数
        pdf_convert_options.page_number = 1
        pdf_convert_options.pages_count = 5

        # 将文档中指定范围的页转换为 PDF
        converter.convert("./pages-1-through-5.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_consecutive_document_pages()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` 是本示例使用的示例文件。点击 [此处](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) 下载。

{{< /tab >}}
{{< tab "pages-1-through-5.pdf" >}}
```text
Binary file (PDF, 216 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_consecutive_document_pages/pages-1-through-5.pdf)
{{< /tab >}}
{{< /tabs >}}
