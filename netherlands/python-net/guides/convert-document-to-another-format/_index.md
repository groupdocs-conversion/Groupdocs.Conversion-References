---
title: "Converteer een document naar een ander formaat"
linkTitle: "Convert to Another Format"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Converteer een enkel document van het ene formaat naar het andere, eventueel door specifieke pagina's of een paginabereik te selecteren met behulp van de attributen pages / page_number / pages_count op ConvertOptions met GroupDocs.Conversion voor Python via .NET."
type: docs
url: /nl/python-net/guides/convert-document-to-another-format/
is_root: false
weight: 40
---


Dit documentatiethema behandelt de conversie van een enkel document naar een ander formaat, waarbij slechts één document als output wordt geproduceerd. Het volgende diagram illustreert het proces van het converteren van een bestand van het ene formaat naar het andere:

flowchart LR
%% Nodes
A["Invoerdocument (bijv. DOCX)"]
B["Conversie"]
C["Geconverteerd document (bijv. PDF)"]

%% Edge connections between nodes
A --> B --> C

Om een document te converteren en op te slaan, gebruik je de volgende methoden van de [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) klasse:

- **`convert(file_path, convert_options)`**: Converts a document to a specified single output format and saves it to a file, such as converting a DOCX to PDF.
- **`convert(stream, convert_options)`**: Converts the document and writes it to a provided stream instead of a file path.

## Convert a Complete Document 

De volgende lijst met [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) klassen kan worden gebruikt om een document naar een specifiek enkel outputformaat te converteren:

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

Het volgende voorbeeld laat zien hoe je een DOCX‑bestand naar PDF converteert:

{{< tabs \"example-1\">}}
{{< tab "convert_document_to_another_format.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document_to_another_format():
    # Instantieer Converter met het invoerdocument 
    with Converter("./business-plan.docx") as converter:
        # Instantieer converteeropties om het outputformaat te definiëren
        pdf_convert_options = PdfConvertOptions()
        
        # Converteer het invoerdocument naar PDF
        converter.convert("./business-plan.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_document_to_another_format()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` is een voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) om het te downloaden.

{{< /tab >}}
{{< tab "business-plan.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_document_to_another_format/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

### Example 2: Specify Output Format

Standaard heeft elke van de [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) klassen zijn eigen standaarddoelformaat. Bijvoorbeeld, het standaard outputformaat voor [WordProcessingConvertOptions](https://reference.groupdocs.com/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/) is [DOCX](https://reference.groupdocs.com/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/docx/).

Om een ander outputformaat binnen dezelfde formaatfamilie in te stellen, gebruik je de `format`‑eigenschap. Het volgende voorbeeld laat zien hoe je het doelformaat instelt op `TXT` bij het converteren van een `DOCX`‑bestand:

{{< tabs "example-2">}}
{{< tab "specify_output_format.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import WordProcessingConvertOptions
from groupdocs.conversion.filetypes import WordProcessingFileType

def specify_output_format():
    # Instantieer Converter met het invoerdocument 
    with Converter("./business-plan.docx") as converter:
        # Instantieer conversie‑opties om het uitvoerformaat te definiëren, standaard is dit DOCX
        word_convert_options = WordProcessingConvertOptions()
        # Wijzig het uitvoerformaat binnen de formaatfamilie van DOCX naar TXT
        word_convert_options.format = WordProcessingFileType.TXT
        
        # Converteer het invoerdocument naar TXT
        converter.convert("./business-plan.txt", word_convert_options)    

if __name__ == "__main__":
    specify_output_format()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` is een voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) om het te downloaden.

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

Ontdek hoe u het aantal documentpagina's kunt verkrijgen in het [Getting Document Information]() documentatietopic.

Om specifieke documentpagina's te converteren, kunt u de volgende [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) klassen gebruiken, die de attributen `pages`, `page_number` en `pages_count` bieden. Deze opties stellen u in staat om individuele pagina's of een bereik van pagina's op te geven om te converteren.

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

U kunt opgeven welke documentpagina's u wilt converteren, zoals weergegeven in het volgende voorbeeld:

{{< tabs "example-3">}}
{{< tab "convert_specific_document_pages.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_specific_document_pages():
    # Instantieer Converter met het invoerdocument 
    with Converter("./business-plan.docx") as converter:
        # Instantieer converteeropties om het outputformaat te definiëren
        pdf_convert_options = PdfConvertOptions()
        # Geef aan welke documentpagina's moeten worden geconverteerd
        pdf_convert_options.pages = [1, 3, 5]

        # Converteer de opgegeven pagina's van het invoerdocument naar PDF
        converter.convert("./pages-1-3-5.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_specific_document_pages()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` is een voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) om het te downloaden.

{{< /tab >}}
{{< tab "pages-1-3-5.pdf" >}}
```text
Binary file (PDF, 156 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_specific_document_pages/pages-1-3-5.pdf)
{{< /tab >}}
{{< /tabs >}}

### Example 2: Convert N Consecutive Pages

Als alternatief kunt u een aantal opeenvolgende pagina's opgeven om te converteren, zoals weergegeven in het volgende voorbeeld:

{{< tabs "example-4">}}
{{< tab "convert_consecutive_document_pages.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_consecutive_document_pages():
    # Instantieer Converter met het invoerdocument 
    with Converter("./business-plan.docx") as converter:
        # Instantieer converteeropties om het outputformaat te definiëren
        pdf_convert_options = PdfConvertOptions()
        # Geef de startpagina en het aantal pagina's op om te converteren
        pdf_convert_options.page_number = 1
        pdf_convert_options.pages_count = 5

        # Converteer het opgegeven paginabereik in het document naar PDF
        converter.convert("./pages-1-through-5.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_consecutive_document_pages()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` is een voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) om het te downloaden.

{{< /tab >}}
{{< tab "pages-1-through-5.pdf" >}}
```text
Binary file (PDF, 216 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_consecutive_document_pages/pages-1-through-5.pdf)
{{< /tab >}}
{{< /tabs >}}
