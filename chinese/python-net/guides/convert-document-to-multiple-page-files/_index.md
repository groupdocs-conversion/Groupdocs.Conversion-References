---
title: "将文档转换为多个页面文件"
linkTitle: "Convert Document To Multiple"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "id: convert-document-to-multiple-page-files"
type: docs
url: /zh/python-net/guides/convert-document-to-multiple-page-files/
is_root: false
weight: 60
---


---
id: convert-document-to-multiple-page-files
url: conversion/python-net/developer-guide/converting-documents/convert-document-to-multiple-page-files
title: 将文档转换为多个页面文件
linkTitle: 转换为多个文件
weight: 3
description: "将多页文档的每一页渲染为单独的输出文件 — 将 page_number 与 pages_count=1 循环，并使用 Converter.convert() 生成每页的 PNG、PDF 或图像，使用 GroupDocs.Conversion for Python via .NET。"
keywords: "转换为多个文件, 每页输出, page_number, pages_count, 页面循环, 转换演示文稿页面, 将 PDF 页面转换为 PNG, ImageConvertOptions, GroupDocs.Conversion, python"
productName: GroupDocs.Conversion for Python via .NET
hideChildren: false
toc: true
---

本文档主题涵盖将单个多页文档转换为单独页面文件的过程。以下图示说明了将多页文件转换为独立页面的流程：

flowchart LR
%% Nodes
A["输入文档"]
B[\"Conversion\"]
C["已转换页面 1"]
D["已转换页面 2"]
E["已转换页面 N"]

%% 节点之间的边连接
A --> B --> C
B --> D
B --> E

要将文档转换为每页文件，请使用 `Converter.convert(file_path, convert_options)` 方法，并结合受支持的 [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) 类上的 `page_number` 和 `pages_count` 属性：

- **`page_number`**: One-based index of the first page to convert.
- **`pages_count`**: Number of consecutive pages to convert starting from `page_number`.

要为每页生成一个输出文件，请从 `1` 循环到 `converter.get_document_info().pages_count`，在每次迭代中更新 `page_number` 并写入不同的输出路径。将 `pages_count = 1` 设置为每次调用仅输出单页。

## Supported ConvertOptions Classes

以下 [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) 类公开了本主题使用的 `page_number` 和 `pages_count` 属性：

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

## Example 1: Convert All Pages of a Document and Save Output to a Folder

以下示例演示如何将 PPTX 演示文稿中的每张幻灯片转换为 PNG 图像并将输出图像保存到指定文件夹。
 
输出文件的文件名模板为 `converted-page-{page number}.{output file extension}`。在本示例中，第一张幻灯片将保存为 `converted-page-1.png`。

{{< tabs \"example-1\">}}
{{< tab \"convert_all_document_pages.py\" >}}
```python
import os
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_all_document_pages():
    output_folder = "./converted-pages"
    os.makedirs(output_folder, exist_ok=True)

    # 使用输入文档实例化 Converter
    with Converter("./basic-presentation.pptx") as converter:
        # 确定源文档的总页数
        pages_count = converter.get_document_info().pages_count

        # 在循环中实例化转换选项一次并重复使用它们
        png_convert_options = ImageConvertOptions()
        png_convert_options.format = ImageFileType.PNG
        png_convert_options.pages_count = 1

        # 将每页转换为单独的 PNG 文件
        for page_number in range(1, pages_count + 1):
            png_convert_options.page_number = page_number
            output_file = os.path.join(output_folder, f"converted-page-{page_number}.png")
            converter.convert(output_file, png_convert_options)

if __name__ == "__main__":
    convert_all_document_pages()
```
{{< /tab >}}
{{< tab \"basic-presentation.pptx\" >}}

`basic-presentation.pptx` 是本示例中使用的示例文件。点击 [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) 下载它。

{{< /tab >}}
{{< tab \"convert-all-document-pages-outputs.zip\" >}}
```text
converted-pages/converted-page-1.png (26 KB)
converted-pages/converted-page-10.png (81 KB)
converted-pages/converted-page-11.png (67 KB)
converted-pages/converted-page-12.png (70 KB)
converted-pages/converted-page-13.png (36 KB)
converted-pages/converted-page-2.png (34 KB)
converted-pages/converted-page-3.png (797 KB)
converted-pages/converted-page-4.png (1262 KB)
converted-pages/converted-page-5.png (75 KB)
converted-pages/converted-page-6.png (33 KB)
[TRUNCATED] (13 files total)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_all_document_pages/convert-all-document-pages-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

## Example 2: Convert a Specific Page and Save Output to a File

了解如何在 [Getting Document Information]() 文档主题中获取文档页数。

以下示例展示如何将 PPTX 演示文稿中的特定幻灯片转换并保存为单独的文件。

{{< tabs "example-2">}}
{{< tab \"convert_specific_document_page_to_file.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_specific_document_page_to_file():
    # 使用输入文档实例化 Converter
    with Converter("./basic-presentation.pptx") as converter:
        # 实例化转换选项
        png_convert_options = ImageConvertOptions()
        # 将输出格式定义为 PNG
        png_convert_options.format = ImageFileType.PNG

        # 指定要转换的单页
        png_convert_options.page_number = 3
        png_convert_options.pages_count = 1

        # 将转换后的页面保存到文件
        converter.convert("./slide-3.png", png_convert_options)

if __name__ == "__main__":
    convert_specific_document_page_to_file()
```
{{< /tab >}}
{{< tab \"basic-presentation.pptx\" >}}

`basic-presentation.pptx` 是本示例中使用的示例文件。点击 [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) 下载它。

{{< /tab >}}
{{< tab \"slide-3.png\" >}}
```text
Binary file (PNG, 797 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_specific_document_page_to_file/slide-3.png)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Convert a Specific Page and Load Output Into a Stream

了解如何在 [Getting Document Information]() 文档主题中获取文档页数。

如果您需要将转换后的页面作为内存缓冲区（例如，将其转发给另一个 API 而不在之后触碰文件系统），请先将页面转换为文件，然后再读取到 `BytesIO` 对象中：

{{< tabs "example-3">}}
{{< tab \"convert_specific_document_page_to_stream.py\" >}}
```python
import io
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_specific_document_page_to_stream():
    page_number_to_convert = 5
    output_file = f"./slide-{page_number_to_convert}.png"

    # 使用输入文档实例化 Converter
    with Converter("./basic-presentation.pptx") as converter:
        # 实例化转换选项
        png_convert_options = ImageConvertOptions()
        # 将输出格式定义为 PNG
        png_convert_options.format = ImageFileType.PNG

        # 指定要转换的单页
        png_convert_options.page_number = page_number_to_convert
        png_convert_options.pages_count = 1

        # 将页面转换并保存到磁盘上的文件
        converter.convert(output_file, png_convert_options)

    # 将转换后的页面加载到内存流中以供下游使用
    with open(output_file, "rb") as file_handle:
        page_stream = io.BytesIO(file_handle.read())

    # page_stream 现在保存了 PNG 字节，并且可以传递给任何使用者
    print(f"Loaded {page_stream.getbuffer().nbytes} bytes into memory")

if __name__ == "__main__":
    convert_specific_document_page_to_stream()
```
{{< /tab >}}
{{< tab \"basic-presentation.pptx\" >}}

`basic-presentation.pptx` 是本示例中使用的示例文件。点击 [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) 下载它。

{{< /tab >}}
{{< tab \"slide-5.png\" >}}
```text
Binary file (PNG, 75 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_specific_document_page_to_stream/slide-5.png)
{{< /tab >}}
{{< /tabs >}}
