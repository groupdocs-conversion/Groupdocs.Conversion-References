---
title: "Converti il documento in file a più pagine"
linkTitle: "Convert Document To Multiple"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "id: convert-document-to-multiple-page-files"
type: docs
url: /it/python-net/guides/convert-document-to-multiple-page-files/
is_root: false
weight: 60
---


---
id: convert-document-to-multiple-page-files
url: conversion/python-net/developer-guide/converting-documents/convert-document-to-multiple-page-files
title: Converti un documento in file a più pagine
linkTitle: Converti in più file
weight: 3
description: "Esegui il rendering di ogni pagina di un documento multipagina nel proprio file di output — itera page_number con pages_count=1 e Converter.convert() per produrre un PNG, PDF o immagine per pagina con GroupDocs.Conversion per Python via .NET."
keywords: convertire in più file, output per pagina, page_number, pages_count, ciclo di pagine, convertire pagine di presentazione, convertire pagine PDF in PNG, ImageConvertOptions, GroupDocs.Conversion, python
productName: GroupDocs.Conversion per Python via .NET
hideChildren: false
toc: true
---

Questo argomento della documentazione copre la conversione di un singolo documento multipagina in file di pagina individuali. Il diagramma seguente illustra il processo di conversione di un file multipagina in pagine separate:

flowchart LR
%% Nodes
A["Documento di input"]
B[\"Conversion\"]
C["Pagina convertita 1"]
D["Pagina convertita 2"]
E["Pagina convertita N"]

%% Edge connections between nodes
A --> B --> C
B --> D
B --> E

Per convertire un documento in file per pagina, utilizza il metodo `Converter.convert(file_path, convert_options)` insieme agli attributi `page_number` e `pages_count` sulle classi [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) supportate:

- **`page_number`**: One-based index of the first page to convert.
- **`pages_count`**: Number of consecutive pages to convert starting from `page_number`.

Per produrre un file di output per pagina, itera da `1` a `converter.get_document_info().pages_count`, aggiornando `page_number` ad ogni iterazione e scrivendo in un percorso di output diverso. Impostare `pages_count = 1` garantisce che ogni chiamata emetta una singola pagina.

## Supported ConvertOptions Classes

Le seguenti classi [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) espongono gli attributi `page_number` e `pages_count` utilizzati in questo argomento:

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

L'esempio seguente dimostra come convertire ogni diapositiva di una presentazione PPTX in un'immagine PNG e salvare le immagini di output in una cartella specificata.
 
Il modello di nome file per i file di output è `converted-page-{page number}.{output file extension}`. In questo esempio, la prima diapositiva verrà salvata come `converted-page-1.png`.

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

    # Istanzia Converter con il documento di input
    with Converter("./basic-presentation.pptx") as converter:
        # Determina il numero totale di pagine nel documento di origine
        pages_count = converter.get_document_info().pages_count

        # Istanzia le opzioni di conversione una volta e riutilizzale all'interno del ciclo
        png_convert_options = ImageConvertOptions()
        png_convert_options.format = ImageFileType.PNG
        png_convert_options.pages_count = 1

        # Converti ogni pagina in un file PNG separato
        for page_number in range(1, pages_count + 1):
            png_convert_options.page_number = page_number
            output_file = os.path.join(output_folder, f"converted-page-{page_number}.png")
            converter.convert(output_file, png_convert_options)

if __name__ == "__main__":
    convert_all_document_pages()
```
{{< /tab >}}
{{< tab "basic-presentation.pptx" >}}

`basic-presentation.pptx` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) per scaricarlo.

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

Scopri come ottenere il numero di pagine del documento nella documentazione [Getting Document Information]().

L'esempio seguente mostra come convertire una diapositiva specifica in una presentazione PPTX e salvarla come file separato.

{{< tabs "example-2">}}
{{< tab "convert_specific_document_page_to_file.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_specific_document_page_to_file():
    # Istanzia Converter con il documento di input
    with Converter("./basic-presentation.pptx") as converter:
        # Istanziare le opzioni di conversione
        png_convert_options = ImageConvertOptions()
        # Definisci il formato di output come PNG
        png_convert_options.format = ImageFileType.PNG

        # Specifica la singola pagina da convertire
        png_convert_options.page_number = 3
        png_convert_options.pages_count = 1

        # Salva la pagina convertita in un file
        converter.convert("./slide-3.png", png_convert_options)

if __name__ == "__main__":
    convert_specific_document_page_to_file()
```
{{< /tab >}}
{{< tab "basic-presentation.pptx" >}}

`basic-presentation.pptx` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) per scaricarlo.

{{< /tab >}}
{{< tab "slide-3.png" >}}
```text
Binary file (PNG, 797 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_specific_document_page_to_file/slide-3.png)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Convert a Specific Page and Load Output Into a Stream

Scopri come ottenere il numero di pagine del documento nella documentazione [Getting Document Information]().

Se hai bisogno della pagina convertita come buffer in memoria (ad esempio, per inoltrarla a un'altra API senza toccare il file system successivamente), converti prima la pagina in un file e poi leggila in un oggetto `BytesIO`:

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

    # Istanzia Converter con il documento di input
    with Converter("./basic-presentation.pptx") as converter:
        # Istanziare le opzioni di conversione
        png_convert_options = ImageConvertOptions()
        # Definisci il formato di output come PNG
        png_convert_options.format = ImageFileType.PNG

        # Specifica la singola pagina da convertire
        png_convert_options.page_number = page_number_to_convert
        png_convert_options.pages_count = 1

        # Converti e salva la pagina in un file su disco
        converter.convert(output_file, png_convert_options)

    # Carica la pagina convertita in uno stream in memoria per l'uso a valle
    with open(output_file, "rb") as file_handle:
        page_stream = io.BytesIO(file_handle.read())

    # page_stream ora contiene i byte PNG e può essere passato a qualsiasi consumatore
    print(f"Loaded {page_stream.getbuffer().nbytes} bytes into memory")

if __name__ == "__main__":
    convert_specific_document_page_to_stream()
```
{{< /tab >}}
{{< tab "basic-presentation.pptx" >}}

`basic-presentation.pptx` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) per scaricarlo.

{{< /tab >}}
{{< tab "slide-5.png" >}}
```text
Binary file (PNG, 75 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_specific_document_page_to_stream/slide-5.png)
{{< /tab >}}
{{< /tabs >}}
