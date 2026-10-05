---
title: "Dokument in mehrere Seiten-Dateien konvertieren"
linkTitle: "Convert Document To Multiple"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "id: convert-document-to-multiple-page-files"
type: docs
url: /de/python-net/guides/convert-document-to-multiple-page-files/
is_root: false
weight: 60
---


---
id: convert-document-to-multiple-page-files
url: conversion/python-net/developer-guide/converting-documents/convert-document-to-multiple-page-files
title: Ein Dokument in mehrere Seiten-Dateien konvertieren
linkTitle: In mehrere Dateien konvertieren
weight: 3
description: "Rendern Sie jede Seite eines mehrseitigen Dokuments in eine eigene Ausgabedatei — Schleifen Sie page_number mit pages_count=1 und Converter.convert(), um pro Seite ein PNG, PDF oder Bild mit GroupDocs.Conversion für Python via .NET zu erzeugen."
keywords: in mehrere Dateien konvertieren, Ausgabe pro Seite, page_number, pages_count, Seitenschleife, Präsentationsseiten konvertieren, PDF-Seiten in PNG konvertieren, ImageConvertOptions, GroupDocs.Conversion, Python
productName: GroupDocs.Conversion für Python via .NET
hideChildren: false
toc: true
---

Dieses Dokumentationsthema behandelt die Konvertierung eines einzelnen mehrseitigen Dokuments in einzelne Seiten‑Dateien. Das folgende Diagramm veranschaulicht den Prozess der Umwandlung einer mehrseitigen Datei in separate Seiten:

flowchart LR
%% Nodes
A["Eingabedokument"]
B["Conversion"]
C["Konvertierte Seite 1"]
D["Konvertierte Seite 2"]
E["Konvertierte Seite N"]

%% Edge connections between nodes
A --> B --> C
B --> D
B --> E

Um ein Dokument in pro‑Seite‑Dateien zu konvertieren, verwenden Sie die Methode `Converter.convert(file_path, convert_options)` zusammen mit den Attributen `page_number` und `pages_count` der unterstützten Klassen [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/).

- **`page_number`**: One-based index of the first page to convert.
- **`pages_count`**: Number of consecutive pages to convert starting from `page_number`.

Um pro Seite eine Ausgabedatei zu erzeugen, schleifen Sie von `1` bis `converter.get_document_info().pages_count`, wobei Sie `page_number` bei jeder Iteration aktualisieren und in einen anderen Ausgabepfad schreiben. Das Setzen von `pages_count = 1` stellt sicher, dass jeder Aufruf eine einzelne Seite ausgibt.

## Supported ConvertOptions Classes

Die folgenden Klassen [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) stellen die in diesem Thema verwendeten Attribute `page_number` und `pages_count` bereit:

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

Das folgende Beispiel zeigt, wie jede Folie einer PPTX‑Präsentation in ein PNG‑Bild konvertiert und die Ausgabebilder in einem angegebenen Ordner gespeichert werden.
 
Die Dateinamen‑Vorlage für die Ausgabedateien lautet `converted-page-{page number}.{output file extension}`. In diesem Beispiel wird die erste Folie als `converted-page-1.png` gespeichert.

{{< tabs "example-1">}}
{{< tab "convert_all_document_pages.py" >}}
```python
import os
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_all_document_pages():
    output_folder = "./converted-pages"
    os.makedirs(output_folder, exist_ok=True)

    # Instanziieren Sie den Converter mit dem Eingabedokument
    with Converter("./basic-presentation.pptx") as converter:
        # Ermitteln Sie die Gesamtzahl der Seiten im Quell-Dokument
        pages_count = converter.get_document_info().pages_count

        # Instanziieren Sie Konvertierungsoptionen einmal und verwenden Sie sie innerhalb der Schleife erneut
        png_convert_options = ImageConvertOptions()
        png_convert_options.format = ImageFileType.PNG
        png_convert_options.pages_count = 1

        # Jede Seite in eine separate PNG-Datei konvertieren
        for page_number in range(1, pages_count + 1):
            png_convert_options.page_number = page_number
            output_file = os.path.join(output_folder, f"converted-page-{page_number}.png")
            converter.convert(output_file, png_convert_options)

if __name__ == "__main__":
    convert_all_document_pages()
```
{{< /tab >}}
{{< tab "basic-presentation.pptx" >}}

`basic-presentation.pptx` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) zum Herunterladen.

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

Erfahren Sie, wie Sie die Anzahl der Dokumentseiten im Dokumentationsthema [Getting Document Information]() erhalten.

Das folgende Beispiel zeigt, wie man eine bestimmte Folie in einer PPTX‑Präsentation konvertiert und als separate Datei speichert.

{{< tabs "example-2">}}
{{< tab \"convert_specific_document_page_to_file.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_specific_document_page_to_file():
    # Instanziieren Sie den Converter mit dem Eingabedokument
    with Converter("./basic-presentation.pptx") as converter:
        # Instanziieren Sie Konvertierungsoptionen
        png_convert_options = ImageConvertOptions()
        # Definieren Sie das Ausgabeformat als PNG
        png_convert_options.format = ImageFileType.PNG

        # Geben Sie die einzelne zu konvertierende Seite an
        png_convert_options.page_number = 3
        png_convert_options.pages_count = 1

        # Speichern Sie die konvertierte Seite in einer Datei
        converter.convert("./slide-3.png", png_convert_options)

if __name__ == "__main__":
    convert_specific_document_page_to_file()
```
{{< /tab >}}
{{< tab "basic-presentation.pptx" >}}

`basic-presentation.pptx` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) zum Herunterladen.

{{< /tab >}}
{{< tab \"slide-3.png\" >}}
```text
Binary file (PNG, 797 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_specific_document_page_to_file/slide-3.png)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Convert a Specific Page and Load Output Into a Stream

Erfahren Sie, wie Sie die Anzahl der Dokumentseiten im Dokumentationsthema [Getting Document Information]() erhalten.

Falls Sie die konvertierte Seite als In‑Memory‑Puffer benötigen (z. B. um sie an eine andere API weiterzuleiten, ohne das Dateisystem anschließend zu berühren), konvertieren Sie die Seite zuerst in eine Datei und lesen Sie sie dann in ein `BytesIO`‑Objekt ein:

{{< tabs "example-3">}}
{{< tab \"convert_specific_document_page_to_stream.py\" >}}
```python
import io
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_specific_document_page_to_stream():
    page_number_to_convert = 5
    output_file = f"./slide-{page_number_to_convert}.png"

    # Instanziieren Sie den Converter mit dem Eingabedokument
    with Converter("./basic-presentation.pptx") as converter:
        # Instanziieren Sie Konvertierungsoptionen
        png_convert_options = ImageConvertOptions()
        # Definieren Sie das Ausgabeformat als PNG
        png_convert_options.format = ImageFileType.PNG

        # Geben Sie die einzelne zu konvertierende Seite an
        png_convert_options.page_number = page_number_to_convert
        png_convert_options.pages_count = 1

        # Konvertieren und speichern Sie die Seite in einer Datei auf der Festplatte
        converter.convert(output_file, png_convert_options)

    # Laden Sie die konvertierte Seite in einen In‑Memory‑Stream für die nachgelagerte Verwendung
    with open(output_file, "rb") as file_handle:
        page_stream = io.BytesIO(file_handle.read())

    # page_stream enthält nun die PNG‑Bytes und kann an jeden Verbraucher übergeben werden
    print(f"Loaded {page_stream.getbuffer().nbytes} bytes into memory")

if __name__ == "__main__":
    convert_specific_document_page_to_stream()
```
{{< /tab >}}
{{< tab "basic-presentation.pptx" >}}

`basic-presentation.pptx` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) zum Herunterladen.

{{< /tab >}}
{{< tab \"slide-5.png\" >}}
```text
Binary file (PNG, 75 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_specific_document_page_to_stream/slide-5.png)
{{< /tab >}}
{{< /tabs >}}
