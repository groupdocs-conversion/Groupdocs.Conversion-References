---
title: Add a Watermark to Converted Document
linkTitle: "Add a Watermark"
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Stamp a text watermark on every page of a converted document with GroupDocs.Conversion for Python via .NET — control colour, size, position, rotation, transparency, and foreground or background placement via WatermarkTextOptions."
type: docs
url: /python-net/guides/add-watermark-to-converted-document/
is_root: false
weight: 80
---


This topic explains how to add a watermark during the conversion process using GroupDocs.Conversion for Python via .NET. The watermark can be applied to a document as it is converted to another format, helping to protect the content and ensure it is identifiable.

To enable watermarking, you can use the `watermark` attribute in the appropriate [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) classes. Below are the supported [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) classes that allow you to configure the watermark during conversion:

Looking for advanced watermarking capabilities? While GroupDocs.Conversion offers basic watermarking, you can explore [GroupDocs.Watermark](https://products.groupdocs.com/watermark/) for a comprehensive solution with enhanced features.

## Supported ConvertOptions Classes

The following [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) classes that provide `watermark` attribute.

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

The [`WatermarkTextOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/) class is used to configure the appearance of the watermark. The following options can be configured for adding a watermark:

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

The following example demonstrates how to convert DOCX document to PDF and add a watermark:

{{< tabs "example-1">}}
{{< tab "add_watermark_to_converted_document.py" >}}  
```python
from groupdocs.pydrawing import Color
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions, WatermarkTextOptions

def add_watermark_to_converted_document():
    # Instantiate Converter with the input document 
    with Converter("./professional-services.docx") as converter:
        # Set up the watermark options
        watermark = WatermarkTextOptions("DRAFT")
        watermark.color = Color.from_argb(128, 211, 211, 211) # lite gray
        watermark.top = 10
        watermark.left = 10
        watermark.width = 300
        watermark.height = 300
        watermark.background = True

        # Set up the conversion options
        options = PdfConvertOptions()
        options.pages_count = 1
        options.watermark = watermark
        
        # Perform the conversion
        converter.convert("./professional-services.pdf", options)    

if __name__ == "__main__":
    add_watermark_to_converted_document()
```
{{< /tab >}}
{{< tab "professional-services.docx" >}}  

`professional-services.docx` is the sample file used in this example. Click [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/add-watermark-to-converted-document/professional-services.docx) to download it.

{{< /tab >}}
{{< tab "professional-services.pdf" >}}  
```text
Binary file (PDF, 363 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/add-watermark-to-converted-document/add_watermark_to_converted_document/professional-services.pdf)
{{< /tab >}}
{{< /tabs >}}
