---
title: "Aggiungi una filigrana al documento convertito"
linkTitle: "Add a Watermark"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Apponi una filigrana di testo su ogni pagina di un documento convertito con GroupDocs.Conversion per Python tramite .NET — controlla colore, dimensione, posizione, rotazione, trasparenza e posizionamento in primo piano o sfondo tramite WatermarkTextOptions."
type: docs
url: /it/python-net/guides/add-watermark-to-converted-document/
is_root: false
weight: 80
---


Questo argomento spiega come aggiungere una filigrana durante il processo di conversione utilizzando GroupDocs.Conversion per Python tramite .NET. La filigrana può essere applicata a un documento mentre viene convertito in un altro formato, contribuendo a proteggere il contenuto e a garantirne l'identificabilità.

Per abilitare le filigrane, è possibile utilizzare l'attributo `watermark` nelle classi [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) appropriate. Di seguito sono riportate le classi [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) supportate che consentono di configurare la filigrana durante la conversione:

Cerchi funzionalità avanzate di filigrana? Mentre GroupDocs.Conversion offre filigrane di base, puoi esplorare [GroupDocs.Watermark](https://products.groupdocs.com/watermark/) per una soluzione completa con funzionalità migliorate.

## Supported ConvertOptions Classes

Le seguenti classi [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) che forniscono l'attributo `watermark`.

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

La classe [`WatermarkTextOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/) è usata per configurare l'aspetto della filigrana. È possibile configurare le seguenti opzioni per aggiungere una filigrana:

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

Il seguente esempio dimostra come convertire un documento DOCX in PDF e aggiungere una filigrana:

{{< tabs \"example-1\">}}
{{< tab \"add_watermark_to_converted_document.py\" >}}
```python
from groupdocs.pydrawing import Color
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions, WatermarkTextOptions

def add_watermark_to_converted_document():
    # Istanziare Converter con il documento di input 
    with Converter("./professional-services.docx") as converter:
        # Impostare le opzioni della filigrana
        watermark = WatermarkTextOptions("DRAFT")
        watermark.color = Color.from_argb(128, 211, 211, 211) # lite gray
        watermark.top = 10
        watermark.left = 10
        watermark.width = 300
        watermark.height = 300
        watermark.background = True

        # Impostare le opzioni di conversione
        options = PdfConvertOptions()
        options.pages_count = 1
        options.watermark = watermark
        
        # Eseguire la conversione
        converter.convert("./professional-services.pdf", options)    

if __name__ == "__main__":
    add_watermark_to_converted_document()
```
{{< /tab >}}
{{< tab \"professional-services.docx\" >}}

`professional-services.docx` è il file di esempio utilizzato in questo esempio. Clicca [qui](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/add-watermark-to-converted-document/professional-services.docx) per scaricarlo.

{{< /tab >}}
{{< tab \"professional-services.pdf\" >}}
```text
Binary file (PDF, 363 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/add-watermark-to-converted-document/add_watermark_to_converted_document/professional-services.pdf)
{{< /tab >}}
{{< /tabs >}}
