---
title: "从本地磁盘加载文件"
linkTitle: "Load From Local Disk"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "使用绝对或相对文件路径实例化 Converter 类，以通过 .NET 的 GroupDocs.Conversion for Python 转换存储在本地文件系统上的文档。"
type: docs
url: /zh/python-net/guides/load-file-from-local-disk/
is_root: false
weight: 90
---


要从本地磁盘加载源文件，您可以在 GroupDocs.Conversion 中使用 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 类构造函数。该 API 提供了多种重载，允许在各种设置和选项之间保持灵活性：

* `Converter(file_path)`
* `Converter(file_path, load_options)`
* `Converter(file_path, converter_settings)`
* `Converter(file_path, load_options, converter_settings)`

每个构造函数都需要 `filePath` 参数，该参数定义源文件的路径。您可以将其指定为绝对路径或相对路径。请注意，如果指定的文件路径不存在，将会抛出异常。

只有在使用 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 类实例执行操作（例如，转换）时，GroupDocs.Conversion 才会访问该文件。

以下 Python 示例演示了如何从本地磁盘加载文件并将其转换为 PDF：

{{< tabs \"code-example\">}}
{{< tab \"convert_docx_to_pdf.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_docx_to_pdf():
    # 指定源文件位置
    converter = Converter("./business-plan.docx")
    
    # 指定输出文件位置和转换选项
    output_path = "./business-plan.pdf"
    pdf_options = PdfConvertOptions()
    
    # 转换并保存到输出路径
    converter.convert(output_path, pdf_options)

if __name__ == "__main__":
    convert_docx_to_pdf()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` 是本示例中使用的示例文件。点击 [此处](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/loading-documents/load-file-from-local-disk/business-plan.docx) 下载它。

{{< /tab >}}
{{< tab \"business-plan.pdf\" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/loading-documents/load-file-from-local-disk/convert_docx_to_pdf/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

GroupDocs.Conversion 根据文件扩展名确定文件类型。如果未设置文件扩展名，GroupDocs.Conversion 将尝试自动检测文件类型。根据文件类型和大小，自动文件类型检测会消耗额外的资源，例如内存和 CPU 时间。因此，我们建议确保文件具有正确的扩展名，或使用接受加载选项的 Converter 类构造函数。

### Explanation

- **Load Source File**: The [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) class is instantiated with the path to the source document ("business-plan.docx").
- **Conversion Options**: An instance of [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) is created to define the settings for PDF conversion.
- **Execute Conversion**: The `convert` method is used to convert the document and save it to the specified output path ("business-plan.pdf").

请参阅 [GroupDocs.Conversion API Reference](https://reference.groupdocs.com/conversion/python-net/) 以获取有关使用加载选项和其他构造函数重载的更多详细信息。
