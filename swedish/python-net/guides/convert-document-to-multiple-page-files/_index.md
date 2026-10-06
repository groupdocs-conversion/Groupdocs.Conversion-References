---
title: "Konvertera dokument till flera sidfiler"
linkTitle: "Convert Document To Multiple"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "id: convert-document-to-multiple-page-files"
type: docs
url: /sv/python-net/guides/convert-document-to-multiple-page-files/
is_root: false
weight: 60
---


---
id: convert-document-to-multiple-page-files
url: conversion/python-net/developer-guide/converting-documents/convert-document-to-multiple-page-files
title: Konvertera ett dokument till flera sidfiler
linkTitle: Konvertera till flera filer
weight: 3
description: "Render varje sida av ett flersidigt dokument till sin egen utdatafil — loop page_number med pages_count=1 och Converter.convert() för att producera en PNG, PDF eller bild per sida med GroupDocs.Conversion för Python via .NET."
keywords: konvertera till flera filer, per-sida utdata, page_number, pages_count, sidloop, konvertera presentationssidor, konvertera PDF-sidor till PNG, ImageConvertOptions, GroupDocs.Conversion, python
productName: GroupDocs.Conversion for Python via .NET
hideChildren: false
toc: true
---

Detta dokumentationsämne täcker konverteringen av ett enstaka flersidigt dokument till individuella sidfiler. Följande diagram illustrerar processen för att konvertera en flersidig fil till separata sidor:

flowchart LR
%% Nodes
A[\"Inmatningsdokument\"]
B["Conversion"]
C[\"Konverterad sida 1\"]
D[\"Konverterad sida 2\"]
E[\"Konverterad sida N\"]

%% Kantanslutningar mellan noder
A --> B --> C
B --> D
B --> E

För att konvertera ett dokument till fil per sida, använd metoden `Converter.convert(file_path, convert_options)` tillsammans med attributen `page_number` och `pages_count` på de stödda [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) klasserna:

- **`page_number`**: One-based index of the first page to convert.
- **`pages_count`**: Number of consecutive pages to convert starting from `page_number`.

För att producera en utdatafil per sida, loopa från `1` till `converter.get_document_info().pages_count`, uppdatera `page_number` i varje iteration och skriv till en annan utdataväg. Att sätta `pages_count = 1` säkerställer att varje anrop genererar en enskild sida.

## Supported ConvertOptions Classes

Följande [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) klasser exponerar attributen `page_number` och `pages_count` som används i detta ämne:

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

Följande exempel visar hur man konverterar varje bild i en PPTX-presentation till en PNG-bild och sparar utdata bilderna i en angiven mapp.
 
Filnamnsmallen för utdatafilerna är `converted-page-{page number}.{output file extension}`. I detta exempel kommer den första bilden att sparas som `converted-page-1.png`.

{{< tabs "example-1">}}
{{< tab \"convert_all_document_pages.py\" >}}
```python
import os
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_all_document_pages():
    output_folder = "./converted-pages"
    os.makedirs(output_folder, exist_ok=True)

    # Instansiera Converter med inmatningsdokumentet
    with Converter("./basic-presentation.pptx") as converter:
        # Bestäm det totala antalet sidor i källdokumentet
        pages_count = converter.get_document_info().pages_count

        # Instansiera konverteringsalternativ en gång och återanvänd dem i loopen
        png_convert_options = ImageConvertOptions()
        png_convert_options.format = ImageFileType.PNG
        png_convert_options.pages_count = 1

        # Konvertera varje sida till en separat PNG-fil
        for page_number in range(1, pages_count + 1):
            png_convert_options.page_number = page_number
            output_file = os.path.join(output_folder, f"converted-page-{page_number}.png")
            converter.convert(output_file, png_convert_options)

if __name__ == "__main__":
    convert_all_document_pages()
```
{{< /tab >}}
{{< tab \"basic-presentation.pptx\" >}}

`basic-presentation.pptx` är exempelfilen som används i detta exempel. Klicka [här](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) för att ladda ner den.

{{< /tab >}}
{{< tab \"convert-all-document-pages-outputs.zip\" >}}
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

Ta reda på hur du får antalet dokumentsidor i dokumentationsämnet [Getting Document Information]().

Följande exempel visar hur man konverterar en specifik bild i en PPTX-presentation och sparar den som en separat fil.

{{< tabs "example-2">}}
{{< tab \"convert_specific_document_page_to_file.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_specific_document_page_to_file():
    # Instansiera Converter med inmatningsdokumentet
    with Converter("./basic-presentation.pptx") as converter:
        # Instansiera konverteringsalternativ
        png_convert_options = ImageConvertOptions()
        # Definiera utdataformatet som PNG
        png_convert_options.format = ImageFileType.PNG

        # Ange den enda sidan att konvertera
        png_convert_options.page_number = 3
        png_convert_options.pages_count = 1

        # Spara den konverterade sidan till en fil
        converter.convert("./slide-3.png", png_convert_options)

if __name__ == "__main__":
    convert_specific_document_page_to_file()
```
{{< /tab >}}
{{< tab \"basic-presentation.pptx\" >}}

`basic-presentation.pptx` är exempelfilen som används i detta exempel. Klicka [här](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) för att ladda ner den.

{{< /tab >}}
{{< tab \"slide-3.png\" >}}
```text
Binary file (PNG, 797 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_specific_document_page_to_file/slide-3.png)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Convert a Specific Page and Load Output Into a Stream

Ta reda på hur du får antalet dokumentsidor i dokumentationsämnet [Getting Document Information]().

Om du behöver den konverterade sidan som en minnesbuffert (t.ex. för att vidarebefordra den till ett annat API utan att röra filsystemet efteråt), konvertera sidan till en fil först och läs sedan in den i ett `BytesIO`-objekt:

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

    # Instansiera Converter med inmatningsdokumentet
    with Converter("./basic-presentation.pptx") as converter:
        # Instansiera konverteringsalternativ
        png_convert_options = ImageConvertOptions()
        # Definiera utdataformatet som PNG
        png_convert_options.format = ImageFileType.PNG

        # Ange den enda sidan att konvertera
        png_convert_options.page_number = page_number_to_convert
        png_convert_options.pages_count = 1

        # Konvertera och spara sidan till en fil på disken
        converter.convert(output_file, png_convert_options)

    # Läs in den konverterade sidan i en minnesström för vidare användning
    with open(output_file, "rb") as file_handle:
        page_stream = io.BytesIO(file_handle.read())

    # page_stream innehåller nu PNG‑bytena och kan skickas till vilken konsument som helst
    print(f"Loaded {page_stream.getbuffer().nbytes} bytes into memory")

if __name__ == "__main__":
    convert_specific_document_page_to_stream()
```
{{< /tab >}}
{{< tab \"basic-presentation.pptx\" >}}

`basic-presentation.pptx` är exempelfilen som används i detta exempel. Klicka [här](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) för att ladda ner den.

{{< /tab >}}
{{< tab "slide-5.png" >}}
```text
Binary file (PNG, 75 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_specific_document_page_to_stream/slide-5.png)
{{< /tab >}}
{{< /tabs >}}
