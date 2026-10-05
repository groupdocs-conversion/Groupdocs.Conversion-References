---
title: "Convertir un document en un autre format"
linkTitle: "Convert to Another Format"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Convertir un seul document d'un format à un autre, en sélectionnant éventuellement des pages spécifiques ou une plage de pages à l'aide des attributs pages / page_number / pages_count sur ConvertOptions avec GroupDocs.Conversion pour Python via .NET."
type: docs
url: /fr/python-net/guides/convert-document-to-another-format/
is_root: false
weight: 40
---


Ce sujet de documentation couvre la conversion d'un seul document en un autre format, où un seul document est produit en sortie. Le diagramme suivant illustre le processus de conversion d'un fichier d'un format à un autre :

flowchart LR
%% Nodes
A[\"Input Document (e.g. DOCX)\"]
B[\"Conversion\"]
C[\"Converted Document (e.g. PDF)\"]

%% Edge connections between nodes
A --> B --> C

Pour convertir et enregistrer un document, utilisez les méthodes de classe suivantes du [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) :

- **`convert(file_path, convert_options)`**: Converts a document to a specified single output format and saves it to a file, such as converting a DOCX to PDF.
- **`convert(stream, convert_options)`**: Converts the document and writes it to a provided stream instead of a file path.

## Convert a Complete Document 

La liste suivante de classes [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) peut être utilisée pour convertir un document vers un format de sortie unique spécifique :

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

L'exemple suivant montre comment convertir un fichier DOCX en PDF :

{{< tabs \"example-1\">}}
{{< tab \"convert_document_to_another_format.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document_to_another_format():
    # Instancier le Convertisseur avec le document d'entrée 
    with Converter("./business-plan.docx") as converter:
        # Instancier les options de conversion pour définir le format de sortie
        pdf_convert_options = PdfConvertOptions()
        
        # Convertir le document d'entrée en PDF
        converter.convert("./business-plan.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_document_to_another_format()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) pour le télécharger.

{{< /tab >}}
{{< tab \"business-plan.pdf\" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_document_to_another_format/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

### Example 2: Specify Output Format

Par défaut, chaque classe [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) possède son propre format cible par défaut. Par exemple, le format de sortie par défaut pour [WordProcessingConvertOptions](https://reference.groupdocs.com/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/) est [DOCX](https://reference.groupdocs.com/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/docx/).

Pour définir un format de sortie différent au sein de la même famille de formats, utilisez la propriété `format`. L'exemple suivant montre comment spécifier le format cible comme `TXT` lors de la conversion d'un fichier `DOCX` :

{{< tabs \"example-2\">}}
{{< tab \"specify_output_format.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import WordProcessingConvertOptions
from groupdocs.conversion.filetypes import WordProcessingFileType

def specify_output_format():
    # Instancier le Convertisseur avec le document d'entrée 
    with Converter("./business-plan.docx") as converter:
        # Instanciez les options de conversion pour définir le format de sortie, par défaut c’est DOCX
        word_convert_options = WordProcessingConvertOptions()
        # Modifiez le format de sortie au sein de la famille de formats de DOCX à TXT
        word_convert_options.format = WordProcessingFileType.TXT
        
        # Convertissez le document d'entrée en TXT
        converter.convert("./business-plan.txt", word_convert_options)    

if __name__ == "__main__":
    specify_output_format()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) pour le télécharger.

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

Découvrez comment obtenir le nombre de pages du document dans le sujet de documentation [Getting Document Information]().

Pour convertir des pages spécifiques du document, vous pouvez utiliser les classes [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) suivantes, qui offrent les attributs `pages`, `page_number` et `pages_count`. Ces options vous permettent de spécifier des pages individuelles ou une plage de pages à convertir.

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

Vous pouvez spécifier quelles pages du document vous souhaitez convertir, comme indiqué dans l’exemple suivant :

{{< tabs "example-3">}}
{{< tab "convert_specific_document_pages.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_specific_document_pages():
    # Instancier le Convertisseur avec le document d'entrée 
    with Converter("./business-plan.docx") as converter:
        # Instancier les options de conversion pour définir le format de sortie
        pdf_convert_options = PdfConvertOptions()
        # Spécifiez les pages du document à convertir
        pdf_convert_options.pages = [1, 3, 5]

        # Convertissez les pages spécifiées du document d’entrée en PDF
        converter.convert("./pages-1-3-5.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_specific_document_pages()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) pour le télécharger.

{{< /tab >}}
{{< tab "pages-1-3-5.pdf" >}}
```text
Binary file (PDF, 156 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_specific_document_pages/pages-1-3-5.pdf)
{{< /tab >}}
{{< /tabs >}}

### Example 2: Convert N Consecutive Pages

En alternative, vous pouvez spécifier un nombre de pages consécutives à convertir, comme indiqué dans l’exemple suivant :

{{< tabs "example-4">}}
{{< tab "convert_consecutive_document_pages.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_consecutive_document_pages():
    # Instancier le Convertisseur avec le document d'entrée 
    with Converter("./business-plan.docx") as converter:
        # Instancier les options de conversion pour définir le format de sortie
        pdf_convert_options = PdfConvertOptions()
        # Spécifiez la page de départ et le nombre de pages à convertir
        pdf_convert_options.page_number = 1
        pdf_convert_options.pages_count = 5

        # Convertissez la plage de pages spécifiée du document en PDF
        converter.convert("./pages-1-through-5.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_consecutive_document_pages()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) pour le télécharger.

{{< /tab >}}
{{< tab "pages-1-through-5.pdf" >}}
```text
Binary file (PDF, 216 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_consecutive_document_pages/pages-1-through-5.pdf)
{{< /tab >}}
{{< /tabs >}}
