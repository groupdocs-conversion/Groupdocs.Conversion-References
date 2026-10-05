---
title: "向已转换文档添加水印"
linkTitle: "Add a Watermark"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "使用 GroupDocs.Conversion for Python via .NET 在已转换文档的每一页上盖上文字水印 — 通过 WatermarkTextOptions 控制颜色、大小、位置、旋转、透明度以及前景或背景放置。"
type: docs
url: /zh/python-net/guides/add-watermark-to-converted-document/
is_root: false
weight: 80
---


本主题说明如何在使用 GroupDocs.Conversion for Python via .NET 的转换过程中添加水印。水印可以在文档转换为其他格式时应用，以帮助保护内容并确保其可识别。

要启用水印功能，您可以在相应的 [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) 类中使用 `watermark` 属性。以下是支持在转换期间配置水印的 [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) 类：

寻找高级水印功能？虽然 GroupDocs.Conversion 提供基本的水印功能，但您可以探索 [GroupDocs.Watermark](https://products.groupdocs.com/watermark/) 以获得功能更强大的完整解决方案。

## Supported ConvertOptions Classes

以下 [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) 类提供 `watermark` 属性。

- **PdfConvertOptions** – Options for converting to [PDF]() format.
- **WordProcessingConvertOptions** – Options for converting to [Word Processing]() formats.
- **SpreadsheetConvertOptions** – Options for converting to [Spreadsheet]() formats.
- **PresentationConvertOptions** – Options for converting to [Presentation]() formats.
- **ImageConvertOptions** – Options for converting to [Image]() formats (e.g., PNG, JPEG).
- **WebConvertOptions** – Options for converting to [Web]() formats (e.g., HTML).
- **PageDescriptionLanguageConvertOptions** – Options for converting to [Page Description Language]() formats (e.g., PostScript).
- **EBookConvertOptions** – Options for converting to [EBook]() formats (e.g., EPUB, MOBI).
- **DiagramConvertOptions** – Options for converting to [Diagram]() formats (e.g., VSDX).

## WatermarkTextOptions Class Attributes

`[WatermarkTextOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/) 类用于配置水印的外观。以下选项可用于添加水印：

- **text**: The text to be used for the watermark.
- **font**: The font name used for the watermark text.
- **color**: The color of the watermark text.
- **width**: The width of the watermark.
- **height**: The height of the watermark.
- **top**: The top position of the watermark.
- **left**: The left position of the watermark.
- **rotation_angle**: The rotation angle of the watermark.
- **transparency**: The transparency level of the watermark.
- **background**: Specifies whether the watermark is stamped as a background. If set to `True`, the watermark is placed at the bottom. By default, it is `False`, and the watermark is placed on top of the content.

## Example: Add a Watermark to Converted Document

以下示例演示如何将 DOCX 文档转换为 PDF 并添加水印：

{{< tabs \"example-1\">}}
{{< tab \"add_watermark_to_converted_document.py\" >}}
```python
from groupdocs.pydrawing import Color
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions, WatermarkTextOptions

def add_watermark_to_converted_document():
    # 实例化 Converter 并使用输入文档 
    with Converter("./professional-services.docx") as converter:
        # 设置水印选项
        watermark = WatermarkTextOptions("DRAFT")
        watermark.color = Color.from_argb(128, 211, 211, 211) # lite gray
        watermark.top = 10
        watermark.left = 10
        watermark.width = 300
        watermark.height = 300
        watermark.background = True

        # 设置转换选项
        options = PdfConvertOptions()
        options.pages_count = 1
        options.watermark = watermark
        
        # 执行转换
        converter.convert("./professional-services.pdf", options)    

if __name__ == "__main__":
    add_watermark_to_converted_document()
```
{{< /tab >}}
{{< tab \"professional-services.docx\" >}}

`professional-services.docx` 是本示例中使用的示例文件。点击 [此处](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/add-watermark-to-converted-document/professional-services.docx) 下载它。

{{< /tab >}}
{{< tab \"professional-services.pdf\" >}}
```text
Binary file (PDF, 363 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/add-watermark-to-converted-document/add_watermark_to_converted_document/professional-services.pdf)
{{< /tab >}}
{{< /tabs >}}
