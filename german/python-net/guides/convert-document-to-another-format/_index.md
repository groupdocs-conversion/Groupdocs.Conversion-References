---
title: "Ein Dokument in ein anderes Format konvertieren"
linkTitle: "Convert to Another Format"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Konvertieren Sie ein einzelnes Dokument von einem Format in ein anderes, optional indem Sie bestimmte Seiten oder einen Seitenbereich mithilfe der Attribute pages / page_number / pages_count in ConvertOptions mit GroupDocs.Conversion für Python über .NET auswählen."
type: docs
url: /de/python-net/guides/convert-document-to-another-format/
is_root: false
weight: 40
---


Dieses Dokumentationsthema behandelt die Konvertierung eines einzelnen Dokuments in ein anderes Format, bei der nur ein Dokument als Ausgabe erzeugt wird. Das folgende Diagramm veranschaulicht den Prozess der Konvertierung einer Datei von einem Format in ein anderes:

flowchart LR
%% Nodes
A["Input Document (e.g. DOCX)"]
B["Conversion"]
C["Converted Document (e.g. PDF)"]

%% Edge connections between nodes
A --> B --> C

Um ein Dokument zu konvertieren und zu speichern, verwenden Sie die folgenden Methoden der [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) Klasse:

- **`convert(file_path, convert_options)`**: Converts a document to a specified single output format and saves it to a file, such as converting a DOCX to PDF.
- **`convert(stream, convert_options)`**: Converts the document and writes it to a provided stream instead of a file path.

## Convert a Complete Document 

Die folgende Liste von [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) Klassen kann verwendet werden, um ein Dokument in ein bestimmtes einzelnes Ausgabeformat zu konvertieren:

- **PdfConvertOptions** – Options for converting to [PDF]() format.
- **WordProcessingConvertOptions** – Options for converting to [Word Processing]() formats.
- **SpreadsheetConvertOptions** – Options for converting to [Spreadsheet]() formats.
- **PresentationConvertOptions** – Options for converting to [Presentation]() formats.
- **ImageConvertOptions** – Options for converting to [Image]() formats (e.g., PNG, JPEG).
- **WebConvertOptions** – Options for converting to [Web]() formats (e.g., HTML).
- **PageDescriptionLanguageConvertOptions** – Options for converting to [Page Description Language]() formats (e.g., PostScript).
- **EBookConvertOptions** – Options for converting to [EBook]() formats (e.g., EPUB, MOBI).
- **EmailConvertOptions** – Options for converting to [Email]() formats (e.g., EML, MSG).
- **DiagramConvertOptions** – Options for converting to [Diagram]() formats (e.g., VSDX).
- **CadConvertOptions** – Options for converting to [CAD]() formats (e.g., DWG).
- **ThreeDConvertOptions** – Options for converting to [3D]() formats.
- **ProjectManagementConvertOptions** – Options for converting to [Project Management]() formats (e.g., MPP).
- **GisConvertOptions** – Options for converting to [GIS]() formats.
- **FontConvertOptions** – Options for converting to [Font]() formats (e.g., TTF, OTF).
- **FinanceConvertOptions** – Options for converting to [Finance]() formats (e.g., XBRL).
- **CompressionConvertOptions** – Options for converting to [Compression]() formats (e.g., ZIP).
- **NoConvertOptions** – A special option class that instructs the converter to copy the source document without any modifications.

### Example 1: Convert a Document to Another Format

Das folgende Beispiel zeigt, wie man eine DOCX‑Datei in PDF konvertiert:

{{< tabs "example-1">}}
{{< tab "convert_document_to_another_format.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document_to_another_format():
    # Instanziieren Sie den Converter mit dem Eingabedokument 
    with Converter("./business-plan.docx") as converter:
        # Instanziieren Sie ConvertOptions, um das Ausgabeformat festzulegen
        pdf_convert_options = PdfConvertOptions()
        
        # Konvertieren Sie das Eingabedokument in PDF
        converter.convert("./business-plan.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_document_to_another_format()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) zum Herunterladen.

{{< /tab >}}
{{< tab "business-plan.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_document_to_another_format/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

### Example 2: Specify Output Format

Standardmäßig hat jede der [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) Klassen ihr eigenes Standardziel‑Format. Beispielsweise ist das Standardausgabeformat für [WordProcessingConvertOptions](https://reference.groupdocs.com/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/) [DOCX](https://reference.groupdocs.com/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/docx/).

Um ein anderes Ausgabeformat innerhalb der Formatfamilie festzulegen, verwenden Sie die Eigenschaft `format`. Das folgende Beispiel zeigt, wie man das Ziel­format auf `TXT` setzt, wenn man eine `DOCX`‑Datei konvertiert:

{{< tabs "example-2">}}
{{< tab "specify_output_format.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import WordProcessingConvertOptions
from groupdocs.conversion.filetypes import WordProcessingFileType

def specify_output_format():
    # Instanziieren Sie den Converter mit dem Eingabedokument 
    with Converter("./business-plan.docx") as converter:
        # Instanziieren Sie Konvertierungsoptionen, um das Ausgabeformat festzulegen; standardmäßig ist es DOCX.
        word_convert_options = WordProcessingConvertOptions()
        # Ändern Sie das Ausgabeformat innerhalb der Formatfamilie von DOCX zu TXT
        word_convert_options.format = WordProcessingFileType.TXT
        
        # Konvertieren Sie das Eingabedokument zu TXT
        converter.convert("./business-plan.txt", word_convert_options)    

if __name__ == "__main__":
    specify_output_format()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) zum Herunterladen.

{{< /tab >}}
{{< tab "business-plan.txt" >}}
```text
﻿HOME BASED

PROFESSIONAL SERVICES

Business Plan

[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/specify_output_format/business-plan.txt)
{{< /tab >}}
{{< /tabs >}}

## Specify Document Pages to Convert

Erfahren Sie, wie Sie die Anzahl der Dokumentseiten im Dokumentationsthema [Getting Document Information]() erhalten.

Um bestimmte Dokumentseiten zu konvertieren, können Sie die folgenden [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) Klassen verwenden, die die Attribute `pages`, `page_number` und `pages_count` bereitstellen. Diese Optionen ermöglichen es Ihnen, einzelne Seiten oder einen Seitenbereich zum Konvertieren anzugeben.

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

### Example 1: Convert Specific Document Pages to Another Format

Sie können angeben, welche Dokumentseiten Sie konvertieren möchten, wie im folgenden Beispiel gezeigt:

{{< tabs "example-3">}}
{{< tab "convert_specific_document_pages.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_specific_document_pages():
    # Instanziieren Sie den Converter mit dem Eingabedokument 
    with Converter("./business-plan.docx") as converter:
        # Instanziieren Sie ConvertOptions, um das Ausgabeformat festzulegen
        pdf_convert_options = PdfConvertOptions()
        # Geben Sie an, welche Dokumentseiten konvertiert werden sollen
        pdf_convert_options.pages = [1, 3, 5]

        # Konvertieren Sie die angegebenen Seiten des Eingabedokuments in PDF
        converter.convert("./pages-1-3-5.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_specific_document_pages()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) zum Herunterladen.

{{< /tab >}}
{{< tab "pages-1-3-5.pdf" >}}
```text
Binary file (PDF, 156 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_specific_document_pages/pages-1-3-5.pdf)
{{< /tab >}}
{{< /tabs >}}

### Example 2: Convert N Consecutive Pages

Alternativ können Sie eine Anzahl aufeinanderfolgender Seiten zum Konvertieren angeben, wie im folgenden Beispiel gezeigt:

{{< tabs "example-4">}}
{{< tab "convert_consecutive_document_pages.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_consecutive_document_pages():
    # Instanziieren Sie den Converter mit dem Eingabedokument 
    with Converter("./business-plan.docx") as converter:
        # Instanziieren Sie ConvertOptions, um das Ausgabeformat festzulegen
        pdf_convert_options = PdfConvertOptions()
        # Geben Sie die Startseite und die Anzahl der zu konvertierenden Seiten an
        pdf_convert_options.page_number = 1
        pdf_convert_options.pages_count = 5

        # Konvertieren Sie den angegebenen Seitenbereich im Dokument in PDF
        converter.convert("./pages-1-through-5.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_consecutive_document_pages()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) zum Herunterladen.

{{< /tab >}}
{{< tab "pages-1-through-5.pdf" >}}
```text
Binary file (PDF, 216 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_consecutive_document_pages/pages-1-through-5.pdf)
{{< /tab >}}
{{< /tabs >}}
