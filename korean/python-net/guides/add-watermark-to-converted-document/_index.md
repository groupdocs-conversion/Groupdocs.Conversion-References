---
title: "변환된 문서에 워터마크 추가"
linkTitle: "Add a Watermark"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "GroupDocs.Conversion for Python via .NET을 사용하여 변환된 문서의 모든 페이지에 텍스트 워터마크를 찍습니다 — 색상, 크기, 위치, 회전, 투명도 및 전경 또는 배경 배치를 WatermarkTextOptions 로 제어합니다."
type: docs
url: /ko/python-net/guides/add-watermark-to-converted-document/
is_root: false
weight: 80
---


이 항목에서는 GroupDocs.Conversion for Python via .NET을 사용하여 변환 과정 중에 워터마크를 추가하는 방법을 설명합니다. 워터마크는 문서가 다른 형식으로 변환되는 동안 적용되어 콘텐츠를 보호하고 식별 가능하도록 합니다.

워터마크를 사용하려면 적절한 [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) 클래스에서 `watermark` 속성을 사용할 수 있습니다. 아래는 변환 중에 워터마크를 구성할 수 있는 지원되는 [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) 클래스 목록입니다:

고급 워터마크 기능을 찾고 계신가요? GroupDocs.Conversion은 기본 워터마크를 제공하지만, 향상된 기능을 갖춘 포괄적인 솔루션을 위해 [GroupDocs.Watermark](https://products.groupdocs.com/watermark/)을 탐색해 보세요.

## Supported ConvertOptions Classes

다음은 `watermark` 속성을 제공하는 [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) 클래스입니다.

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

The [`WatermarkTextOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/) 클래스는 워터마크의 모양을 구성하는 데 사용됩니다. 워터마크 추가를 위해 다음 옵션을 구성할 수 있습니다:

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

다음 예제는 DOCX 문서를 PDF로 변환하고 워터마크를 추가하는 방법을 보여줍니다:

{{< tabs "example-1">}}
{{< tab "add_watermark_to_converted_document.py" >}}
```python
from groupdocs.pydrawing import Color
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions, WatermarkTextOptions

def add_watermark_to_converted_document():
    # 입력 문서로 Converter를 인스턴스화합니다 
    with Converter("./professional-services.docx") as converter:
        # 워터마크 옵션을 설정합니다
        watermark = WatermarkTextOptions("DRAFT")
        watermark.color = Color.from_argb(128, 211, 211, 211) # lite gray
        watermark.top = 10
        watermark.left = 10
        watermark.width = 300
        watermark.height = 300
        watermark.background = True

        # 변환 옵션을 설정합니다
        options = PdfConvertOptions()
        options.pages_count = 1
        options.watermark = watermark
        
        # 변환을 수행합니다
        converter.convert("./professional-services.pdf", options)    

if __name__ == "__main__":
    add_watermark_to_converted_document()
```
{{< /tab >}}
{{< tab "professional-services.docx" >}}

`professional-services.docx`는 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/add-watermark-to-converted-document/professional-services.docx)를 클릭하십시오.

{{< /tab >}}
{{< tab "professional-services.pdf" >}}
```text
Binary file (PDF, 363 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/add-watermark-to-converted-document/add_watermark_to_converted_document/professional-services.pdf)
{{< /tab >}}
{{< /tabs >}}
