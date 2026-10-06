---
title: "Converti un documento in un altro formato"
linkTitle: "Convert to Another Format"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Converti un singolo documento da un formato all'altro, opzionalmente selezionando pagine specifiche o un intervallo di pagine utilizzando gli attributi pages / page_number / pages_count su ConvertOptions con GroupDocs.Conversion per Python tramite .NET."
type: docs
url: /it/python-net/guides/convert-document-to-another-format/
is_root: false
weight: 40
---


Questo argomento della documentazione copre la conversione di un singolo documento in un altro formato, dove viene prodotto un solo documento in output. Il diagramma seguente illustra il processo di conversione di un file da un formato all'altro:

flowchart LR
%% Nodes
A[\"Input Document (e.g. DOCX)\"]
B[\"Conversion\"]
C[\"Converted Document (e.g. PDF)\"]

%% Edge connections between nodes
A --> B --> C

Per convertire e salvare un documento, utilizza i seguenti metodi della classe [`Converter`](/conversion/python-net/groupdocs.conversion/converter/):

- **`convert(file_path, convert_options)`**: Converts a document to a specified single output format and saves it to a file, such as converting a DOCX to PDF.
- **`convert(stream, convert_options)`**: Converts the document and writes it to a provided stream instead of a file path.

## Convert a Complete Document 

L'elenco seguente di classi [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) può essere utilizzato per convertire un documento in un formato di output specifico singolo:

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

L'esempio seguente dimostra come convertire un file DOCX in PDF:

{{< tabs \"example-1\">}}
{{< tab "convert_document_to_another_format.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document_to_another_format():
    # Istanziare Converter con il documento di input 
    with Converter("./business-plan.docx") as converter:
        # Istanzia le opzioni di conversione per definire il formato di output
        pdf_convert_options = PdfConvertOptions()
        
        # Converti il documento di input in PDF
        converter.convert("./business-plan.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_document_to_another_format()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) per scaricarlo.

{{< /tab >}}
{{< tab "business-plan.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_document_to_another_format/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

### Example 2: Specify Output Format

Per impostazione predefinita, ciascuna delle classi [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) ha il proprio formato di destinazione predefinito. Ad esempio, il formato di output predefinito per [WordProcessingConvertOptions](https://reference.groupdocs.com/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/) è [DOCX](https://reference.groupdocs.com/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/docx/).

Per impostare un formato di output diverso all'interno della stessa famiglia di formati, utilizza la proprietà `format`. L'esempio seguente dimostra come specificare il formato di destinazione come `TXT` durante la conversione di un file `DOCX`:

{{< tabs "example-2">}}
{{< tab "specify_output_format.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import WordProcessingConvertOptions
from groupdocs.conversion.filetypes import WordProcessingFileType

def specify_output_format():
    # Istanziare Converter con il documento di input 
    with Converter("./business-plan.docx") as converter:
        # Istanzia le opzioni di conversione per definire il formato di output, per impostazione predefinita è DOCX
        word_convert_options = WordProcessingConvertOptions()
        # Cambia il formato di output all'interno della famiglia di formati da DOCX a TXT
        word_convert_options.format = WordProcessingFileType.TXT
        
        # Converti il documento di input in TXT
        converter.convert("./business-plan.txt", word_convert_options)    

if __name__ == "__main__":
    specify_output_format()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) per scaricarlo.

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

Scopri come ottenere il numero di pagine del documento nella documentazione [Getting Document Information]().

Per convertire pagine specifiche del documento, puoi utilizzare le seguenti classi [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/), che forniscono gli attributi `pages`, `page_number` e `pages_count`. Queste opzioni ti consentono di specificare pagine individuali o un intervallo di pagine da convertire.

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

Puoi specificare quali pagine del documento desideri convertire, come mostrato nell'esempio seguente:

{{< tabs "example-3">}}
{{< tab "convert_specific_document_pages.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_specific_document_pages():
    # Istanziare Converter con il documento di input 
    with Converter("./business-plan.docx") as converter:
        # Istanzia le opzioni di conversione per definire il formato di output
        pdf_convert_options = PdfConvertOptions()
        # Specifica quali pagine del documento convertire
        pdf_convert_options.pages = [1, 3, 5]

        # Converti le pagine specificate del documento di input in PDF
        converter.convert("./pages-1-3-5.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_specific_document_pages()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) per scaricarlo.

{{< /tab >}}
{{< tab "pages-1-3-5.pdf" >}}
```text
Binary file (PDF, 156 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_specific_document_pages/pages-1-3-5.pdf)
{{< /tab >}}
{{< /tabs >}}

### Example 2: Convert N Consecutive Pages

In alternativa, puoi specificare un numero di pagine consecutive da convertire, come mostrato nell'esempio seguente:

{{< tabs "example-4">}}
{{< tab "convert_consecutive_document_pages.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_consecutive_document_pages():
    # Istanziare Converter con il documento di input 
    with Converter("./business-plan.docx") as converter:
        # Istanzia le opzioni di conversione per definire il formato di output
        pdf_convert_options = PdfConvertOptions()
        # Specifica la pagina iniziale e il numero di pagine da convertire
        pdf_convert_options.page_number = 1
        pdf_convert_options.pages_count = 5

        # Converti l'intervallo specificato di pagine del documento in PDF
        converter.convert("./pages-1-through-5.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_consecutive_document_pages()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) per scaricarlo.

{{< /tab >}}
{{< tab "pages-1-through-5.pdf" >}}
```text
Binary file (PDF, 216 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_consecutive_document_pages/pages-1-through-5.pdf)
{{< /tab >}}
{{< /tabs >}}
