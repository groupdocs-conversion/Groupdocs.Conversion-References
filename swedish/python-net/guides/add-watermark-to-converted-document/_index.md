---
title: "Lägg till en vattenstämpel i konverterat dokument"
linkTitle: "Add a Watermark"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Stämpla en textvattenstämpel på varje sida i ett konverterat dokument med GroupDocs.Conversion för Python via .NET — kontrollera färg, storlek, position, rotation, transparens samt förgrunds- eller bakgrundsplacering via WatermarkTextOptions."
type: docs
url: /sv/python-net/guides/add-watermark-to-converted-document/
is_root: false
weight: 80
---


Detta ämne förklarar hur man lägger till en vattenstämpel under konverteringsprocessen med GroupDocs.Conversion för Python via .NET. Vattenstämpeln kan appliceras på ett dokument när det konverteras till ett annat format, vilket hjälper till att skydda innehållet och säkerställa att det är identifierbart.

För att aktivera vattenstämpling kan du använda attributet `watermark` i lämpliga [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/)‑klasser. Nedan följer de stödjade [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/)‑klasserna som låter dig konfigurera vattenstämpeln under konverteringen:

Letar du efter avancerade vattenstämplingsfunktioner? Medan GroupDocs.Conversion erbjuder grundläggande vattenstämpling, kan du utforska [GroupDocs.Watermark](https://products.groupdocs.com/watermark/) för en omfattande lösning med förbättrade funktioner.

## Supported ConvertOptions Classes

Följande [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/)‑klasser som tillhandahåller `watermark`‑attributet.

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

[`WatermarkTextOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/)‑klassen används för att konfigurera vattenstämpelns utseende. Följande alternativ kan konfigureras för att lägga till en vattenstämpel:

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

Följande exempel visar hur man konverterar ett DOCX-dokument till PDF och lägger till en vattenstämpel:

{{< tabs "example-1">}}
{{< tab "add_watermark_to_converted_document.py" >}}
```python
from groupdocs.pydrawing import Color
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions, WatermarkTextOptions

def add_watermark_to_converted_document():
    # Instansiera Converter med inmatningsdokumentet 
    with Converter("./professional-services.docx") as converter:
        # Ställ in vattenstämpelalternativen
        watermark = WatermarkTextOptions("DRAFT")
        watermark.color = Color.from_argb(128, 211, 211, 211) # lite gray
        watermark.top = 10
        watermark.left = 10
        watermark.width = 300
        watermark.height = 300
        watermark.background = True

        # Ställ in konverteringsalternativen
        options = PdfConvertOptions()
        options.pages_count = 1
        options.watermark = watermark
        
        # Utför konverteringen
        converter.convert("./professional-services.pdf", options)    

if __name__ == "__main__":
    add_watermark_to_converted_document()
```
{{< /tab >}}
{{< tab "professional-services.docx" >}}

`professional-services.docx` är exempelfilen som används i detta exempel. Klicka [här](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/add-watermark-to-converted-document/professional-services.docx) för att ladda ner den.

{{< /tab >}}
{{< tab "professional-services.pdf" >}}
```text
Binary file (PDF, 363 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/add-watermark-to-converted-document/add_watermark_to_converted_document/professional-services.pdf)
{{< /tab >}}
{{< /tabs >}}
