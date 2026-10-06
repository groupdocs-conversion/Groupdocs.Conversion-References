---
title: "変換されたドキュメントに透かしを追加する"
linkTitle: "Add a Watermark"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "GroupDocs.Conversion for Python via .NET を使用して、変換されたドキュメントの各ページにテキスト透かしをスタンプします — WatermarkTextOptions を使用して色、サイズ、位置、回転、透明度、前景または背景への配置を制御できます。"
type: docs
url: /ja/python-net/guides/add-watermark-to-converted-document/
is_root: false
weight: 80
---


このトピックでは、GroupDocs.Conversion for Python via .NET を使用して変換プロセス中に透かしを追加する方法を説明します。透かしはドキュメントが別の形式に変換される際に適用でき、コンテンツの保護と識別可能性を確保します。

透かし機能を有効にするには、適切な [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) クラスで `watermark` 属性を使用できます。以下は、変換中に透かしを設定できるサポート対象の [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) クラスです:

高度な透かし機能をお探しですか？GroupDocs.Conversion は基本的な透かし機能を提供しますが、拡張機能を備えた包括的なソリューションとして [GroupDocs.Watermark](https://products.groupdocs.com/watermark/) を検討できます。

## Supported ConvertOptions Classes

`[`ConvertOptions`]` クラスは `watermark` 属性を提供する以下のクラスです。

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

The [`WatermarkTextOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/) クラスは透かしの外観を設定するために使用されます。透かしを追加する際に設定できるオプションは以下の通りです:

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

以下の例は DOCX ドキュメントを PDF に変換し、透かしを追加する方法を示しています:

{{< tabs "example-1">}}
{{< tab "add_watermark_to_converted_document.py" >}}
```python
from groupdocs.pydrawing import Color
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions, WatermarkTextOptions

def add_watermark_to_converted_document():
    # 入力ドキュメントで Converter をインスタンス化します 
    with Converter("./professional-services.docx") as converter:
        # 透かしオプションを設定します
        watermark = WatermarkTextOptions("DRAFT")
        watermark.color = Color.from_argb(128, 211, 211, 211) # lite gray
        watermark.top = 10
        watermark.left = 10
        watermark.width = 300
        watermark.height = 300
        watermark.background = True

        # 変換オプションを設定します
        options = PdfConvertOptions()
        options.pages_count = 1
        options.watermark = watermark
        
        # 変換を実行します
        converter.convert("./professional-services.pdf", options)    

if __name__ == "__main__":
    add_watermark_to_converted_document()
```
{{< /tab >}}
{{< tab "professional-services.docx" >}}

`professional-services.docx` はこの例で使用されるサンプルファイルです。ダウンロードするには [こちら](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/add-watermark-to-converted-document/professional-services.docx) をクリックしてください。

{{< /tab >}}
{{< tab "professional-services.pdf" >}}
```text
Binary file (PDF, 363 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/add-watermark-to-converted-document/add_watermark_to_converted_document/professional-services.pdf)
{{< /tab >}}
{{< /tabs >}}
