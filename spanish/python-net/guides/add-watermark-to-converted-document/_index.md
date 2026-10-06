---
title: "Agregar una marca de agua al documento convertido"
linkTitle: "Add a Watermark"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Estampe una marca de agua de texto en cada página de un documento convertido con GroupDocs.Conversion para Python a través de .NET — controle el color, tamaño, posición, rotación, transparencia y la colocación en primer plano o fondo mediante WatermarkTextOptions."
type: docs
url: /es/python-net/guides/add-watermark-to-converted-document/
is_root: false
weight: 80
---


Este tema explica cómo agregar una marca de agua durante el proceso de conversión usando GroupDocs.Conversion para Python a través de .NET. La marca de agua puede aplicarse a un documento mientras se convierte a otro formato, ayudando a proteger el contenido y asegurando que sea identificable.

Para habilitar la marca de agua, puedes usar el atributo `watermark` en las clases [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) apropiadas. A continuación se presentan las clases [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) compatibles que te permiten configurar la marca de agua durante la conversión:

¿Buscas capacidades avanzadas de marcas de agua? Mientras GroupDocs.Conversion ofrece marcas de agua básicas, puedes explorar [GroupDocs.Watermark](https://products.groupdocs.com/watermark/) para una solución integral con funciones mejoradas.

## Supported ConvertOptions Classes

Las siguientes clases [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) que proporcionan el atributo `watermark`.

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

La clase [`WatermarkTextOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/) se usa para configurar la apariencia de la marca de agua. Las siguientes opciones pueden configurarse para agregar una marca de agua:

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

El siguiente ejemplo muestra cómo convertir un documento DOCX a PDF y agregar una marca de agua:

{{< tabs "example-1">}}
{{< tab "add_watermark_to_converted_document.py" >}}
```python
from groupdocs.pydrawing import Color
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions, WatermarkTextOptions

def add_watermark_to_converted_document():
    # Instanciar Converter con el documento de entrada 
    with Converter("./professional-services.docx") as converter:
        # Configurar las opciones de la marca de agua
        watermark = WatermarkTextOptions("DRAFT")
        watermark.color = Color.from_argb(128, 211, 211, 211) # lite gray
        watermark.top = 10
        watermark.left = 10
        watermark.width = 300
        watermark.height = 300
        watermark.background = True

        # Configurar las opciones de conversión
        options = PdfConvertOptions()
        options.pages_count = 1
        options.watermark = watermark
        
        # Ejecutar la conversión
        converter.convert("./professional-services.pdf", options)    

if __name__ == "__main__":
    add_watermark_to_converted_document()
```
{{< /tab >}}
{{< tab "professional-services.docx" >}}

`professional-services.docx` es el archivo de ejemplo utilizado en este caso. Haga clic [aquí](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/add-watermark-to-converted-document/professional-services.docx) para descargarlo.

{{< /tab >}}
{{< tab "professional-services.pdf" >}}
```text
Binary file (PDF, 363 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/add-watermark-to-converted-document/add_watermark_to_converted_document/professional-services.pdf)
{{< /tab >}}
{{< /tabs >}}
