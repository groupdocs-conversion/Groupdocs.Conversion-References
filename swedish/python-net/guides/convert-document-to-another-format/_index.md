---
title: "Konvertera ett dokument till ett annat format"
linkTitle: "Convert to Another Format"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Konvertera ett enda dokument från ett format till ett annat, eventuellt genom att välja specifika sidor eller ett sidintervall med hjälp av attributen pages / page_number / pages_count på ConvertOptions med GroupDocs.Conversion för Python via .NET."
type: docs
url: /sv/python-net/guides/convert-document-to-another-format/
is_root: false
weight: 40
---


Detta dokumentationsämne täcker konverteringen av ett enda dokument till ett annat format, där endast ett dokument produceras som output. Följande diagram illustrerar processen att konvertera en fil från ett format till ett annat:

flowchart LR
%% Nodes
A["Input Document (e.g. DOCX)"]
B["Conversion"]
C["Converted Document (e.g. PDF)"]

%% Kantanslutningar mellan noder
A --> B --> C

För att konvertera och spara ett dokument, använd följande [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) klassmetoder:

- **`convert(file_path, convert_options)`**: Converts a document to a specified single output format and saves it to a file, such as converting a DOCX to PDF.
- **`convert(stream, convert_options)`**: Converts the document and writes it to a provided stream instead of a file path.

## Convert a Complete Document 

Följande lista med [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) klasser kan användas för att konvertera ett dokument till ett specifikt enskilt outputformat:

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

Följande exempel visar hur man konverterar en DOCX-fil till PDF:

{{< tabs "example-1">}}
{{< tab "convert_document_to_another_format.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document_to_another_format():
    # Instansiera Converter med inmatningsdokumentet 
    with Converter("./business-plan.docx") as converter:
        # Instansiera konverteringsalternativ för att definiera outputformatet
        pdf_convert_options = PdfConvertOptions()
        
        # Konvertera inmatningsdokumentet till PDF
        converter.convert("./business-plan.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_document_to_another_format()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx` är exempelfilen som används i detta exempel. Klicka på [här](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) för att ladda ner den.

{{< /tab >}}
{{< tab "business-plan.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_document_to_another_format/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

### Example 2: Specify Output Format

Som standard har varje av [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) klasser sitt eget standardmålformat. Till exempel är standardoutputformatet för [WordProcessingConvertOptions](https://reference.groupdocs.com/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/) [DOCX](https://reference.groupdocs.com/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/docx/).

För att ange ett annat outputformat inom formatfamiljen, använd egenskapen `format`. Följande exempel visar hur man specificerar målformatet som `TXT` när man konverterar en `DOCX`-fil:

{{< tabs "example-2">}}
{{< tab "specify_output_format.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import WordProcessingConvertOptions
from groupdocs.conversion.filetypes import WordProcessingFileType

def specify_output_format():
    # Instansiera Converter med inmatningsdokumentet 
    with Converter("./business-plan.docx") as converter:
        # Instansiera konverteringsalternativ för att definiera outputformatet, som standard är det DOCX
        word_convert_options = WordProcessingConvertOptions()
        # Ändra utdataformatet inom formatfamiljen från DOCX till TXT
        word_convert_options.format = WordProcessingFileType.TXT
        
        # Konvertera inmatningsdokumentet till TXT
        converter.convert("./business-plan.txt", word_convert_options)    

if __name__ == "__main__":
    specify_output_format()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx` är exempelfilen som används i detta exempel. Klicka på [här](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) för att ladda ner den.

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

Ta reda på hur du får antalet dokumentsidor i dokumentationsämnet [Getting Document Information]().

För att konvertera specifika dokumentsidor kan du använda följande [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) klasser, som tillhandahåller attributen `pages`, `page_number` och `pages_count`. Dessa alternativ låter dig ange enskilda sidor eller ett intervall av sidor att konvertera.

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

Du kan ange vilka dokumentsidor du vill konvertera, som visas i följande exempel:

{{< tabs "example-3">}}
{{< tab "convert_specific_document_pages.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_specific_document_pages():
    # Instansiera Converter med inmatningsdokumentet 
    with Converter("./business-plan.docx") as converter:
        # Instansiera konverteringsalternativ för att definiera outputformatet
        pdf_convert_options = PdfConvertOptions()
        # Ange vilka dokumentsidor som ska konverteras
        pdf_convert_options.pages = [1, 3, 5]

        # Konvertera de angivna sidorna i inmatningsdokumentet till PDF
        converter.convert("./pages-1-3-5.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_specific_document_pages()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx` är exempelfilen som används i detta exempel. Klicka på [här](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) för att ladda ner den.

{{< /tab >}}
{{< tab "pages-1-3-5.pdf" >}}
```text
Binary file (PDF, 156 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_specific_document_pages/pages-1-3-5.pdf)
{{< /tab >}}
{{< /tabs >}}

### Example 2: Convert N Consecutive Pages

Som ett alternativ kan du ange ett antal på varandra följande sidor att konvertera, som visas i följande exempel:

{{< tabs "example-4">}}
{{< tab "convert_consecutive_document_pages.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_consecutive_document_pages():
    # Instansiera Converter med inmatningsdokumentet 
    with Converter("./business-plan.docx") as converter:
        # Instansiera konverteringsalternativ för att definiera outputformatet
        pdf_convert_options = PdfConvertOptions()
        # Ange startsid och antal sidor att konvertera
        pdf_convert_options.page_number = 1
        pdf_convert_options.pages_count = 5

        # Konvertera det angivna sidintervallet i dokumentet till PDF
        converter.convert("./pages-1-through-5.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_consecutive_document_pages()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx` är exempelfilen som används i detta exempel. Klicka på [här](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) för att ladda ner den.

{{< /tab >}}
{{< tab "pages-1-through-5.pdf" >}}
```text
Binary file (PDF, 216 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_consecutive_document_pages/pages-1-through-5.pdf)
{{< /tab >}}
{{< /tabs >}}
