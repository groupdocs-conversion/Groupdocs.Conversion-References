---
title: "快速入门指南"
linkTitle: "Quick Start Guide"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "设置虚拟环境，安装 groupdocs-conversion-net，并在五分钟内运行三个最小示例 — DOCX → PDF、PDF → 按页 PNG、ZIP → 合并 PDF —。"
type: docs
url: /zh/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


本指南简要概述了如何通过 .NET 设置并开始使用 GroupDocs.Conversion for Python。该库使开发者能够以最少的配置在各种文件格式（例如 DOCX、PDF、PNG）之间进行转换。

## Prerequisites

要继续，请确保您拥有：

1. **Configured** 环境，如 [System Requirements]() 章节所述。
2. **Optionally** 您可以 [Get a Temporary License](https://purchase.groupdocs.com/temporary-license/) 来测试所有产品功能。

## Set Up Your Development Environment

为获得最佳实践，请使用虚拟环境来管理 Python 应用程序的依赖项。了解更多关于虚拟环境的信息，请参阅文档主题 [Create and Use Virtual Environments](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments)。

### Create and Activate a Virtual Environment

创建虚拟环境：

{{< tabs \"example1\">}}
{{< tab \"Windows\" >}}
```ps
py -m venv .venv
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< /tabs >}}

激活虚拟环境：

{{< tabs \"example2\">}}
{{< tab \"Windows\" >}}
```ps
.venv\Scripts\activate
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< /tabs >}}

### Install `groupdocs-conversion-net` Package

激活虚拟环境后，在终端中运行以下命令以安装最新版本的包：

{{< tabs \"example3\">}}
{{< tab \"Windows\" >}}
```ps
py -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< /tabs >}}

确保包已成功安装。您应该会看到以下信息

```bash
Successfully installed groupdocs-conversion-net-*
```

## Example 1: Convert document

为了快速测试库，让我们将 DOCX 文件转换为 PDF。您也可以在 [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_docx_to_pdf.zip) 下载我们即将构建的应用程序。

{{< tabs \"demo_app_convert_docx_to_pdf\">}}
{{< tab \"convert_docx_to_pdf.py\" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_docx_to_pdf():
    # 获取许可证文件的绝对路径
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # 创建许可证并设置路径
        license = License()
        license.set_license(license_path)

    # 加载 DOCX 文件
    with Converter("./business-plan.docx") as converter:
        # 创建转换选项
        pdf_convert_options = PdfConvertOptions()

        # 将 DOCX 转换为 PDF
        converter.convert("./business-plan.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_docx_to_pdf()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` 是本示例中使用的示例文件。点击 [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/business-plan.docx) 下载它。

{{< /tab >}}
{{< tab \"business-plan.pdf\" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_docx_to_pdf/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

您的文件夹结构应类似于以下目录结构：

```Directory
📂 demo-app
 ├──convert_docx_to_pdf.py
 ├──business-plan.docx
 └──GroupDocs.Conversion.lic (Optionally)
```

### Run the App

{{< tabs "run-the-app">}}
{{< tab \"Windows\" >}}
```ps
py convert_docx_to_pdf.py
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 convert_docx_to_pdf.py
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 convert_docx_to_pdf.py
```
{{< /tab >}}
{{< /tabs >}}

运行应用后，您可以通过执行 `deactivate` 或关闭终端来停用虚拟环境。

### Explanation
- `Converter("./business-plan.docx")`: Initializes the converter with the DOCX file.
- `PdfConvertOptions()`: Specifies the output format as PDF.
- `converter.convert("./business-plan.pdf", pdf_convert_options)`: Converts the DOCX file to PDF and saves it as `business-plan.pdf`.

## Example 2: Convert document pages

在本示例中，我们将把 PDF 文档页面转换为 PNG。您可以下载我们即将构建的应用 [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_pdf_pages_to_png.zip)。

{{< tabs "demo_app_convert_pdf_pages_to_png">}}
{{< tab "convert_pdf_pages_to_png.py" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_pdf_pages_to_png():
    # 获取许可证文件的绝对路径
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # 创建许可证并设置路径
        license = License()
        license.set_license(license_path)

    output_folder = "./converted-pages"
    os.makedirs(output_folder, exist_ok=True)

    # 加载 PDF 文档
    with Converter("./annual-review.pdf") as converter:
        # 确定源文档的总页数
        pages_count = converter.get_document_info().pages_count

        # 创建转换选项并在循环中重复使用它们
        png_convert_options = ImageConvertOptions()
        png_convert_options.format = ImageFileType.PNG
        png_convert_options.pages_count = 1

        # 将每页转换为单独的 PNG 文件
        for page_number in range(1, pages_count + 1):
            png_convert_options.page_number = page_number
            output_file = os.path.join(output_folder, f"converted-page-{page_number}.png")
            converter.convert(output_file, png_convert_options)

if __name__ == "__main__":
    convert_pdf_pages_to_png()
```
{{< /tab >}}
{{< tab "annual-review.pdf" >}}

`annual-review.pdf` 是本示例中使用的示例文件。点击 [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/annual-review.pdf) 下载它。

{{< /tab >}}
{{< tab "convert-pdf-pages-to-png-outputs.zip" >}}
```text
converted-pages/converted-page-1.png (1148 KB)
converted-pages/converted-page-2.png (89 KB)
converted-pages/converted-page-3.png (83 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_pdf_pages_to_png/convert-pdf-pages-to-png-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

您的文件夹结构应类似于以下目录结构：

```Directory
📂 demo-app
 ├──annual-review.pdf
 ├──convert_pdf_pages_to_png.py
 └──GroupDocs.Conversion.lic (Optionally)
```

### Run the App

{{< tabs "run_the_app_convert_pdf_pages_to_png">}}
{{< tab \"Windows\" >}}
```ps
py convert_pdf_pages_to_png.py
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 convert_pdf_pages_to_png.py
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 convert_pdf_pages_to_png.py
```
{{< /tab >}}
{{< /tabs >}}

运行应用后，您可以通过执行 `deactivate` 或关闭终端来停用虚拟环境。

### Explanation
- `Converter("./annual-review.pdf")`: Initializes the converter with the PDF file.
- `converter.get_document_info().pages_count`: Retrieves the total number of pages in the source document.
- `ImageConvertOptions()` with `format = ImageFileType.PNG`: Specifies the output format as PNG image.
- The loop updates `png_convert_options.page_number` on each iteration (with `pages_count = 1`) and calls `converter.convert(...)` to write one PNG file per page into the `converted-pages` folder.

## Example 3: Convert files in archive

在本示例中，我们将把 ZIP 存档的内容转换为 PDF。GroupDocs.Conversion 打开存档，转换其中的文件，并生成一个包含所有转换后文档的单一合并 PDF。您可以下载我们即将构建的应用 [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_files_in_archive.zip)。

{{< tabs "demo_app_convert_files_in_archive">}}
{{< tab "convert_files_in_archive.py" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_files_in_archive():
    # 获取许可证文件的绝对路径
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # 创建许可证并设置路径
        license = License()
        license.set_license(license_path)

    # 加载 ZIP 文件
    with Converter("./compressed.zip") as converter:
        # 创建转换选项
        pdf_convert_options = PdfConvertOptions()

        # 解压存档，转换其内容，并保存为合并的 PDF
        converter.convert("./converted.pdf", pdf_convert_options)

if __name__ == "__main__":
    convert_files_in_archive()
```
{{< /tab >}}
{{< tab "compressed.zip" >}}

`compressed.zip` 是本示例中使用的示例文件。点击 [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/compressed.zip) 下载它。

{{< /tab >}}
{{< tab "converted.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_files_in_archive/converted.pdf)
{{< /tab >}}
{{< /tabs >}}

您的文件夹结构应类似于以下目录结构：

```Directory
📂 demo-app
 ├──compressed.zip
 ├──convert_files_in_archive.py
 └──GroupDocs.Conversion.lic (Optionally)
```

### Run the App

{{< tabs "run_the_app_convert_files_in_archive">}}
{{< tab \"Windows\" >}}
```ps
py convert_files_in_archive.py
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 convert_files_in_archive.py
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 convert_files_in_archive.py
```
{{< /tab >}}
{{< /tabs >}}

运行应用后，您可以通过执行 `deactivate` 或关闭终端来停用虚拟环境。

### Explanation
- `Converter("./compressed.zip")`: Initializes the converter with the ZIP file.
- `PdfConvertOptions()`: Specifies the output format as PDF.
- `converter.convert("./converted.pdf", pdf_convert_options)`: Extracts the archive, converts its contents, and writes a single consolidated PDF to `converted.pdf`.

## Next Steps

完成基础学习后，探索其他资源以提升您的使用效果：
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Check details on licensing and evaluation.
- [Technical Support](): Contact support for assistance if you encounter issues.
