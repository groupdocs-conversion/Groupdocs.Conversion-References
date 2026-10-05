---
title: "Ajouter un filigrane au document converti"
linkTitle: "Add a Watermark"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Apposez un filigrane texte sur chaque page d'un document converti avec GroupDocs.Conversion for Python via .NET — contrôlez la couleur, la taille, la position, la rotation, la transparence et le placement en avant-plan ou en arrière-plan via WatermarkTextOptions."
type: docs
url: /fr/python-net/guides/add-watermark-to-converted-document/
is_root: false
weight: 80
---


Ce sujet explique comment ajouter un filigrane pendant le processus de conversion à l'aide de GroupDocs.Conversion for Python via .NET. Le filigrane peut être appliqué à un document lors de sa conversion vers un autre format, aidant à protéger le contenu et à le rendre identifiable.

Pour activer le filigrane, vous pouvez utiliser l'attribut `watermark` dans les classes appropriées [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/). Ci-dessous les classes [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) prises en charge qui vous permettent de configurer le filigrane pendant la conversion :

Vous cherchez des capacités avancées de filigrane ? Bien que GroupDocs.Conversion propose un filigrane de base, vous pouvez explorer [GroupDocs.Watermark](https://products.groupdocs.com/watermark/) pour une solution complète avec des fonctionnalités améliorées.

## Supported ConvertOptions Classes

Les classes [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) suivantes offrent l'attribut `watermark`.

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

La classe [`WatermarkTextOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/) est utilisée pour configurer l'apparence du filigrane. Les options suivantes peuvent être configurées pour ajouter un filigrane :

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

L'exemple suivant montre comment convertir un document DOCX en PDF et ajouter un filigrane :

{{< tabs \"example-1\">}}
{{< tab \"add_watermark_to_converted_document.py\" >}}
```python
from groupdocs.pydrawing import Color
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions, WatermarkTextOptions

def add_watermark_to_converted_document():
    # Instancier le Convertisseur avec le document d'entrée 
    with Converter("./professional-services.docx") as converter:
        # Configurer les options du filigrane
        watermark = WatermarkTextOptions("DRAFT")
        watermark.color = Color.from_argb(128, 211, 211, 211) # lite gray
        watermark.top = 10
        watermark.left = 10
        watermark.width = 300
        watermark.height = 300
        watermark.background = True

        # Configurer les options de conversion
        options = PdfConvertOptions()
        options.pages_count = 1
        options.watermark = watermark
        
        # Effectuer la conversion
        converter.convert("./professional-services.pdf", options)    

if __name__ == "__main__":
    add_watermark_to_converted_document()
```
{{< /tab >}}
{{< tab \"professional-services.docx\" >}}

`professional-services.docx` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/add-watermark-to-converted-document/professional-services.docx) pour le télécharger.

{{< /tab >}}
{{< tab \"professional-services.pdf\" >}}
```text
Binary file (PDF, 363 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/add-watermark-to-converted-document/add_watermark_to_converted_document/professional-services.pdf)
{{< /tab >}}
{{< /tabs >}}
