---
title: "Voeg een watermerk toe aan het geconverteerde document"
linkTitle: "Add a Watermark"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Stempel een tekstwatermerk op elke pagina van een geconverteerd document met GroupDocs.Conversion voor Python via .NET — beheer kleur, grootte, positie, rotatie, transparantie en plaatsing op de voorgrond of achtergrond via WatermarkTextOptions."
type: docs
url: /nl/python-net/guides/add-watermark-to-converted-document/
is_root: false
weight: 80
---


Dit onderwerp legt uit hoe u een watermerk kunt toevoegen tijdens het conversieproces met GroupDocs.Conversion voor Python via .NET. Het watermerk kan op een document worden toegepast terwijl het naar een ander formaat wordt geconverteerd, waardoor de inhoud wordt beschermd en herkenbaar blijft.

Om watermerken in te schakelen, kunt u het `watermark`-attribuut gebruiken in de juiste [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/)-klassen. Hieronder staan de ondersteunde [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/)-klassen die u in staat stellen het watermerk tijdens de conversie te configureren:

Op zoek naar geavanceerde watermerkfunctionaliteit? Terwijl GroupDocs.Conversion basiswatermerken biedt, kunt u [GroupDocs.Watermark](https://products.groupdocs.com/watermark/) verkennen voor een uitgebreide oplossing met verbeterde functies.

## Supported ConvertOptions Classes

De volgende [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/)-klassen die het `watermark`-attribuut bieden.

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

De [`WatermarkTextOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/) klasse wordt gebruikt om het uiterlijk van het watermerk te configureren. De volgende opties kunnen worden geconfigureerd voor het toevoegen van een watermerk:

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

Het volgende voorbeeld toont hoe een DOCX-document te converteren naar PDF en een watermerk toe te voegen:

{{< tabs \"example-1\">}}
{{< tab \"add_watermark_to_converted_document.py\" >}}
```python
from groupdocs.pydrawing import Color
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions, WatermarkTextOptions

def add_watermark_to_converted_document():
    # Instantieer Converter met het invoerdocument 
    with Converter("./professional-services.docx") as converter:
        # Stel de watermerkopties in
        watermark = WatermarkTextOptions("DRAFT")
        watermark.color = Color.from_argb(128, 211, 211, 211) # lite gray
        watermark.top = 10
        watermark.left = 10
        watermark.width = 300
        watermark.height = 300
        watermark.background = True

        # Stel de conversieopties in
        options = PdfConvertOptions()
        options.pages_count = 1
        options.watermark = watermark
        
        # Voer de conversie uit
        converter.convert("./professional-services.pdf", options)    

if __name__ == "__main__":
    add_watermark_to_converted_document()
```
{{< /tab >}}
{{< tab \"professional-services.docx\" >}}

`professional-services.docx` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/add-watermark-to-converted-document/professional-services.docx) om het te downloaden.

{{< /tab >}}
{{< tab \"professional-services.pdf\" >}}
```text
Binary file (PDF, 363 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/add-watermark-to-converted-document/add_watermark_to_converted_document/professional-services.pdf)
{{< /tab >}}
{{< /tabs >}}
