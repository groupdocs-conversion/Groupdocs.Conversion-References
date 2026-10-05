---
title: "转换文档容器内的文件"
linkTitle: "Convert Archives and Containers"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "打开 ZIP、RAR、7Z、OST、PST 等容器格式，转换其内容，并在一次 Converter.convert() 调用中使用通过 .NET 的 GroupDocs.Conversion for Python 将结果写入统一的输出文档。"
type: docs
url: /zh/python-net/guides/convert-files-within-document-containers/
is_root: false
weight: 70
---


本主题介绍如何转换嵌入在文档容器中的文件，例如压缩或打包文件，转换为单独的输出文件。下图说明了在文档容器内提取并转换文件的过程：

flowchart LR
%% Nodes
A["文档容器"]
B["提取"]
C["转换"]
D["已转换文件 1"]
E["已转换文件 2"]
F["已转换文件 N"]

%% 节点之间的边连接
A --> B --> C --> D
C --> E
C --> F

提取和转换过程在一次调用 `convert(file_path, convert_options)` 方法时完成，该方法属于 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 类。GroupDocs.Conversion 打开容器，转换其中的文件，并写入一个合并的输出文档。

## Document Container File Types

以下文件类型被视为文档容器：

### Email and Outlook

- **EML** - Email Message File.
- **EMLX** - Apple Mail Email File.
- **MSG** - Microsoft Outlook Message File.
- **OST** - Outlook Offline Data File.
- **PST** - Outlook Personal Information Store File.

### PDF

- **PDF** - PDF files that contain embedded resources.

### Word Processing

- **DOC** - The older Microsoft Word binary format.
- **DOCX** - The modern Word format.
- **DOT and DOTX** - Word template files.
- **RTF** - Rich Text Format.

### Compression

- **7Z** - 7-Zip Compressed File.
- **BZ2** - Bzip2 Compressed File.
- **CAB** - Windows Cabinet File.
- **CPIO** - CPIO Compressed File.
- **GZ** - Gnu Zipped Archive.
- **GZIP** - Gzip Compressed File.
- **LZ** - Lzip Compressed File.
- **LZMA** - LZMA Compressed File.
- **RAR** - RAR Compressed Archive.
- **TAR** - Consolidated Unix File Archive.
- **XZ** - Xz Compressed File.
- **Z** - Unix Compressed File.
- **ZIP** - ZIP Compressed File.

## Example: Convert Files Within Document Container

以下示例演示如何将 ZIP 存档的内容转换为单个合并的 PDF：

{{< tabs \"example-1\">}}
{{< tab "convert_files_within_document_container.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_files_within_document_container():
    # 使用输入文档容器实例化 Converter
    with Converter("./compressed.zip") as converter:
        # 实例化转换选项
        pdf_convert_options = PdfConvertOptions()

        # 解压存档，转换其中的文件，并保存为合并的 PDF
        converter.convert("./converted.pdf", pdf_convert_options)

if __name__ == "__main__":
    convert_files_within_document_container()
```
{{< /tab >}}
{{< tab "compressed.zip" >}}

`compressed.zip` 是本示例中使用的示例文件。点击 [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-files-within-document-containers/compressed.zip) 下载它。

{{< /tab >}}
{{< tab "converted.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-files-within-document-containers/convert_files_within_document_container/converted.pdf)
{{< /tab >}}
{{< /tabs >}}
