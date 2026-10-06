---
title: "Document converteren naar meerdere paginabestanden"
linkTitle: "Convert Document To Multiple"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "id: convert-document-to-multiple-page-files"
type: docs
url: /nl/python-net/guides/convert-document-to-multiple-page-files/
is_root: false
weight: 60
---


---
id: convert-document-to-multiple-page-files
url: conversion/python-net/developer-guide/converting-documents/convert-document-to-multiple-page-files
title: Document converteren naar meerdere paginabestanden
linkTitle: Converteren naar meerdere bestanden
weight: 3
description: "Render elke pagina van een meerpagina-document naar een eigen uitvoerbestand — loop page_number met pages_count=1 en Converter.convert() om één PNG, PDF of afbeelding per pagina te produceren met GroupDocs.Conversion voor Python via .NET."
keywords: converteren naar meerdere bestanden, per-pagina uitvoer, page_number, pages_count, paginalus, presentatiepagina's converteren, PDF-pagina's converteren naar PNG, ImageConvertOptions, GroupDocs.Conversion, python
productName: GroupDocs.Conversion voor Python via .NET
hideChildren: false
toc: true
---

Dit documentatiethema behandelt de conversie van een enkel meerpagina-document naar individuele paginabestanden. Het volgende diagram illustreert het proces van het converteren van een meerpagina-bestand naar afzonderlijke pagina's:

flowchart LR
%% Nodes
A["Invoerdocument"]
B["Conversie"]
C["Geconverteerde pagina 1"]
D["Geconverteerde pagina 2"]
E["Geconverteerde pagina N"]

%% Edge connections between nodes
A --> B --> C
B --> D
B --> E

Om een document naar per-pagina bestanden te converteren, gebruik je de `Converter.convert(file_path, convert_options)` methode samen met de `page_number` en `pages_count` attributen op de ondersteunde [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) klassen:

- **`page_number`**: One-based index of the first page to convert.
- **`pages_count`**: Number of consecutive pages to convert starting from `page_number`.

Om één uitvoerbestand per pagina te produceren, loop van `1` tot `converter.get_document_info().pages_count`, waarbij je `page_number` bij elke iteratie bijwerkt en naar een ander uitvoerpad schrijft. Het instellen van `pages_count = 1` zorgt ervoor dat elke oproep één enkele pagina genereert.

## Supported ConvertOptions Classes

De volgende [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) klassen tonen de `page_number` en `pages_count` attributen die in dit onderwerp worden gebruikt:

- **PdfConvertOptions** – Options for converting to [PDF]() format.
- **ImageConvertOptions** – Options for converting to [Image]() formats (e.g., PNG, JPEG).
- **WordProcessingConvertOptions** – Options for converting to [Word Processing]() formats.
- **SpreadsheetConvertOptions** – Options for converting to [Spreadsheet]() formats.
- **PresentationConvertOptions** – Options for converting to [Presentation]() formats.
- **WebConvertOptions** – Options for converting to [Web]() formats (e.g., HTML).
- **EBookConvertOptions** – Options for converting to [EBook]() formats (e.g., EPUB, MOBI).
- **DiagramConvertOptions** – Options for converting to [Diagram]() formats (e.g., VSDX).
- **PageDescriptionLanguageConvertOptions** – Options for converting to [Page Description Language]() formats (e.g., PostScript).
- **CadConvertOptions** – Options for converting to [CAD]() formats (e.g., DWG).
- **ThreeDConvertOptions** – Options for converting to [3D]() formats.
- **FinanceConvertOptions** – Options for converting to [Finance]() formats (e.g., XBRL).

## Example 1: Convert All Pages of a Document and Save Output to a Folder

Het volgende voorbeeld laat zien hoe je elke dia in een PPTX-presentatie naar een PNG-afbeelding converteert en de uitvoerafbeeldingen opslaat in een opgegeven map.
 
Het bestandsnaamsjabloon voor de uitvoerbestanden is `converted-page-{page number}.{output file extension}`. In dit voorbeeld wordt de eerste dia opgeslagen als `converted-page-1.png`.

{{< tabs \"example-1\">}}
{{< tab "convert_all_document_pages.py" >}}
```python
import os
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_all_document_pages():
    output_folder = "./converted-pages"
    os.makedirs(output_folder, exist_ok=True)

    # Instantieer Converter met het invoerdocument
    with Converter("./basic-presentation.pptx") as converter:
        # Bepaal het totale aantal pagina's in het bron‑document
        pages_count = converter.get_document_info().pages_count

        # Instantieer converteeropties één keer en hergebruik ze binnen de lus
        png_convert_options = ImageConvertOptions()
        png_convert_options.format = ImageFileType.PNG
        png_convert_options.pages_count = 1

        # Converteer elke pagina naar een afzonderlijk PNG‑bestand
        for page_number in range(1, pages_count + 1):
            png_convert_options.page_number = page_number
            output_file = os.path.join(output_folder, f"converted-page-{page_number}.png")
            converter.convert(output_file, png_convert_options)

if __name__ == "__main__":
    convert_all_document_pages()
```
{{< /tab >}}
{{< tab "basic-presentation.pptx" >}}

`basic-presentation.pptx` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) om het te downloaden.

{{< /tab >}}
{{< tab "convert-all-document-pages-outputs.zip" >}}
```text
converted-pages/converted-page-1.png (26 KB)
converted-pages/converted-page-10.png (81 KB)
converted-pages/converted-page-11.png (67 KB)
converted-pages/converted-page-12.png (70 KB)
converted-pages/converted-page-13.png (36 KB)
converted-pages/converted-page-2.png (34 KB)
converted-pages/converted-page-3.png (797 KB)
converted-pages/converted-page-4.png (1262 KB)
converted-pages/converted-page-5.png (75 KB)
converted-pages/converted-page-6.png (33 KB)
[TRUNCATED] (13 files total)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_all_document_pages/convert-all-document-pages-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

## Example 2: Convert a Specific Page and Save Output to a File

Ontdek hoe u het aantal documentpagina's kunt verkrijgen in het [Getting Document Information]() documentatietopic.

Het volgende voorbeeld toont hoe je een specifieke dia in een PPTX-presentatie converteert en opslaat als een afzonderlijk bestand.

{{< tabs "example-2">}}
{{< tab "convert_specific_document_page_to_file.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_specific_document_page_to_file():
    # Instantieer Converter met het invoerdocument
    with Converter("./basic-presentation.pptx") as converter:
        # Instantieer converteeropties
        png_convert_options = ImageConvertOptions()
        # Definieer het uitvoerformaat als PNG
        png_convert_options.format = ImageFileType.PNG

        # Specificeer de enkele pagina die moet worden geconverteerd
        png_convert_options.page_number = 3
        png_convert_options.pages_count = 1

        # Sla de geconverteerde pagina op in een bestand
        converter.convert("./slide-3.png", png_convert_options)

if __name__ == "__main__":
    convert_specific_document_page_to_file()
```
{{< /tab >}}
{{< tab "basic-presentation.pptx" >}}

`basic-presentation.pptx` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) om het te downloaden.

{{< /tab >}}
{{< tab "slide-3.png" >}}
```text
Binary file (PNG, 797 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_specific_document_page_to_file/slide-3.png)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Convert a Specific Page and Load Output Into a Stream

Ontdek hoe u het aantal documentpagina's kunt verkrijgen in het [Getting Document Information]() documentatietopic.

Als je de geconverteerde pagina nodig hebt als een in‑memory buffer (bijv. om deze door te sturen naar een andere API zonder later het bestandssysteem aan te raken), converteer de pagina eerst naar een bestand en lees deze vervolgens in een `BytesIO`-object:

{{< tabs "example-3">}}
{{< tab "convert_specific_document_page_to_stream.py" >}}
```python
import io
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_specific_document_page_to_stream():
    page_number_to_convert = 5
    output_file = f"./slide-{page_number_to_convert}.png"

    # Instantieer Converter met het invoerdocument
    with Converter("./basic-presentation.pptx") as converter:
        # Instantieer converteeropties
        png_convert_options = ImageConvertOptions()
        # Definieer het uitvoerformaat als PNG
        png_convert_options.format = ImageFileType.PNG

        # Specificeer de enkele pagina die moet worden geconverteerd
        png_convert_options.page_number = page_number_to_convert
        png_convert_options.pages_count = 1

        # Converteer en sla de pagina op als een bestand op schijf
        converter.convert(output_file, png_convert_options)

    # Laad de geconverteerde pagina in een in‑memory stream voor downstream gebruik
    with open(output_file, "rb") as file_handle:
        page_stream = io.BytesIO(file_handle.read())

    # page_stream bevat nu de PNG-bytes en kan aan elke consument worden doorgegeven
    print(f"Loaded {page_stream.getbuffer().nbytes} bytes into memory")

if __name__ == "__main__":
    convert_specific_document_page_to_stream()
```
{{< /tab >}}
{{< tab "basic-presentation.pptx" >}}

`basic-presentation.pptx` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) om het te downloaden.

{{< /tab >}}
{{< tab "slide-5.png" >}}
```text
Binary file (PNG, 75 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_specific_document_page_to_stream/slide-5.png)
{{< /tab >}}
{{< /tabs >}}
