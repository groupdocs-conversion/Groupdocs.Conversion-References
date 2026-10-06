---
title: "Добавить водяной знак в преобразованный документ"
linkTitle: "Add a Watermark"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Наложите текстовый водяной знак на каждую страницу преобразованного документа с помощью GroupDocs.Conversion для Python через .NET — контролируйте цвет, размер, позицию, вращение, прозрачность и размещение в переднем или заднем плане с помощью WatermarkTextOptions."
type: docs
url: /ru/python-net/guides/add-watermark-to-converted-document/
is_root: false
weight: 80
---


В этой статье объясняется, как добавить водяной знак во время процесса конвертации с использованием GroupDocs.Conversion для Python через .NET. Водяной знак может быть применён к документу при его преобразовании в другой формат, помогая защитить содержимое и обеспечить его идентифицируемость.

Чтобы включить наложение водяных знаков, вы можете использовать атрибут `watermark` в соответствующих классах [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/). Ниже перечислены поддерживаемые классы [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/), которые позволяют настроить водяной знак во время конвертации:

Ищете расширенные возможности наложения водяных знаков? Хотя GroupDocs.Conversion предлагает базовое наложение, вы можете изучить [GroupDocs.Watermark](https://products.groupdocs.com/watermark/) для комплексного решения с расширенными функциями.

## Supported ConvertOptions Classes

Следующие классы [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/), предоставляющие атрибут `watermark`.

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

Класс [`WatermarkTextOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/) используется для настройки внешнего вида водяного знака. Следующие параметры можно настроить для добавления водяного знака:

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

В следующем примере показано, как преобразовать документ DOCX в PDF и добавить водяной знак:

{{< tabs \"example-1\">}}
{{< tab \"add_watermark_to_converted_document.py\" >}}
```python
from groupdocs.pydrawing import Color
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions, WatermarkTextOptions

def add_watermark_to_converted_document():
    # Создайте экземпляр Converter с входным документом 
    with Converter("./professional-services.docx") as converter:
        # Настройте параметры водяного знака
        watermark = WatermarkTextOptions("DRAFT")
        watermark.color = Color.from_argb(128, 211, 211, 211) # lite gray
        watermark.top = 10
        watermark.left = 10
        watermark.width = 300
        watermark.height = 300
        watermark.background = True

        # Настройте параметры конвертации
        options = PdfConvertOptions()
        options.pages_count = 1
        options.watermark = watermark
        
        # Выполните конвертацию
        converter.convert("./professional-services.pdf", options)    

if __name__ == "__main__":
    add_watermark_to_converted_document()
```
{{< /tab >}}
{{< tab \"professional-services.docx\" >}}

`professional-services.docx` является примером файла, используемого в этом примере. Нажмите [здесь](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/add-watermark-to-converted-document/professional-services.docx) чтобы скачать его.

{{< /tab >}}
{{< tab \"professional-services.pdf\" >}}
```text
Binary file (PDF, 363 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/add-watermark-to-converted-document/add_watermark_to_converted_document/professional-services.pdf)
{{< /tab >}}
{{< /tabs >}}
