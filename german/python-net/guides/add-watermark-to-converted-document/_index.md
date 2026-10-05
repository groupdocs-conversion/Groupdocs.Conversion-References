---
title: "Ein Wasserzeichen zum konvertierten Dokument hinzufügen"
linkTitle: "Add a Watermark"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Stempeln Sie ein Textwasserzeichen auf jede Seite eines konvertierten Dokuments mit GroupDocs.Conversion für Python über .NET — steuern Sie Farbe, Größe, Position, Drehung, Transparenz sowie Vorder- oder Hintergrundplatzierung über WatermarkTextOptions."
type: docs
url: /de/python-net/guides/add-watermark-to-converted-document/
is_root: false
weight: 80
---


Dieses Thema erklärt, wie man während des Konvertierungsprozesses ein Wasserzeichen mit GroupDocs.Conversion für Python über .NET hinzufügt. Das Wasserzeichen kann auf ein Dokument angewendet werden, während es in ein anderes Format konvertiert wird, um den Inhalt zu schützen und sicherzustellen, dass er erkennbar ist.

Um Wasserzeichen zu aktivieren, können Sie das Attribut `watermark` in den entsprechenden [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) Klassen verwenden. Nachfolgend sind die unterstützten [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) Klassen aufgeführt, die es Ihnen ermöglichen, das Wasserzeichen während der Konvertierung zu konfigurieren:

Suchen Sie erweiterte Wasserzeichenfunktionen? Während GroupDocs.Conversion grundlegende Wasserzeichen bietet, können Sie [GroupDocs.Watermark](https://products.groupdocs.com/watermark/) für eine umfassende Lösung mit erweiterten Funktionen erkunden.

## Supported ConvertOptions Classes

Die folgenden [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) Klassen, die das Attribut `watermark` bereitstellen.

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

Die [`WatermarkTextOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/) Klasse wird verwendet, um das Aussehen des Wasserzeichens zu konfigurieren. Die folgenden Optionen können für das Hinzufügen eines Wasserzeichens konfiguriert werden:

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

Das folgende Beispiel zeigt, wie ein DOCX-Dokument in PDF konvertiert und ein Wasserzeichen hinzugefügt wird:

{{< tabs "example-1">}}
{{< tab "add_watermark_to_converted_document.py" >}}
```python
from groupdocs.pydrawing import Color
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions, WatermarkTextOptions

def add_watermark_to_converted_document():
    # Instanziieren Sie den Converter mit dem Eingabedokument 
    with Converter("./professional-services.docx") as converter:
        # Richten Sie die Wasserzeichen-Optionen ein
        watermark = WatermarkTextOptions("DRAFT")
        watermark.color = Color.from_argb(128, 211, 211, 211) # lite gray
        watermark.top = 10
        watermark.left = 10
        watermark.width = 300
        watermark.height = 300
        watermark.background = True

        # Richten Sie die Konvertierungsoptionen ein
        options = PdfConvertOptions()
        options.pages_count = 1
        options.watermark = watermark
        
        # Führen Sie die Konvertierung durch
        converter.convert("./professional-services.pdf", options)    

if __name__ == "__main__":
    add_watermark_to_converted_document()
```
{{< /tab >}}
{{< tab "professional-services.docx" >}}

`professional-services.docx` ist die in diesem Beispiel verwendete Beispieldatei. Klicken Sie [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/add-watermark-to-converted-document/professional-services.docx), um sie herunterzuladen.

{{< /tab >}}
{{< tab "professional-services.pdf" >}}
```text
Binary file (PDF, 363 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/add-watermark-to-converted-document/add_watermark_to_converted_document/professional-services.pdf)
{{< /tab >}}
{{< /tabs >}}
