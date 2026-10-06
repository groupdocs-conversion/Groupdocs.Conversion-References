---
title: "Convertir un documento a otro formato"
linkTitle: "Convert to Another Format"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Convertir un solo documento de un formato a otro, opcionalmente seleccionando páginas específicas o un rango de páginas mediante los atributos pages / page_number / pages_count en ConvertOptions con GroupDocs.Conversion para Python a través de .NET."
type: docs
url: /es/python-net/guides/convert-document-to-another-format/
is_root: false
weight: 40
---


Este tema de documentación cubre la conversión de un solo documento a otro formato, donde solo se produce un documento como salida. El siguiente diagrama ilustra el proceso de convertir un archivo de un formato a otro:

flowchart LR
%% Nodes
A["Input Document (e.g. DOCX)"]
B["Conversion"]
C["Converted Document (e.g. PDF)"]

%% Conexiones de aristas entre nodos
A --> B --> C

Para convertir y guardar un documento, use los siguientes métodos de clase [`Converter`](/conversion/python-net/groupdocs.conversion/converter/):

- **`convert(file_path, convert_options)`**: Converts a document to a specified single output format and saves it to a file, such as converting a DOCX to PDF.
- **`convert(stream, convert_options)`**: Converts the document and writes it to a provided stream instead of a file path.

## Convert a Complete Document 

La siguiente lista de clases [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) puede usarse para convertir un documento a un formato de salida único específico:

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

El siguiente ejemplo muestra cómo convertir un archivo DOCX a PDF:

{{< tabs "example-1">}}
{{< tab "convert_document_to_another_format.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document_to_another_format():
    # Instanciar Converter con el documento de entrada 
    with Converter("./business-plan.docx") as converter:
        # Instanciar opciones de conversión para definir el formato de salida
        pdf_convert_options = PdfConvertOptions()
        
        # Convertir el documento de entrada a PDF
        converter.convert("./business-plan.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_document_to_another_format()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx` es el archivo de muestra utilizado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) para descargarlo.

{{< /tab >}}
{{< tab "business-plan.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_document_to_another_format/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

### Example 2: Specify Output Format

De forma predeterminada, cada una de las clases [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) tiene su propio formato de destino predeterminado. Por ejemplo, el formato de salida predeterminado para [WordProcessingConvertOptions](https://reference.groupdocs.com/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/) es [DOCX](https://reference.groupdocs.com/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/docx/).

Para establecer un formato de salida diferente dentro de la familia de formatos, use la propiedad `format`. El siguiente ejemplo muestra cómo especificar el formato de destino como `TXT` al convertir un archivo `DOCX`:

{{< tabs "example-2">}}
{{< tab "specify_output_format.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import WordProcessingConvertOptions
from groupdocs.conversion.filetypes import WordProcessingFileType

def specify_output_format():
    # Instanciar Converter con el documento de entrada 
    with Converter("./business-plan.docx") as converter:
        # Instanciar opciones de conversión para definir el formato de salida, por defecto es DOCX
        word_convert_options = WordProcessingConvertOptions()
        # Cambiar el formato de salida dentro de la familia de formatos de DOCX a TXT
        word_convert_options.format = WordProcessingFileType.TXT
        
        # Convertir el documento de entrada a TXT
        converter.convert("./business-plan.txt", word_convert_options)    

if __name__ == "__main__":
    specify_output_format()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx` es el archivo de muestra utilizado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) para descargarlo.

{{< /tab >}}
{{< tab \"business-plan.txt\" >}}
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

Descubra cómo obtener el número de páginas del documento en el tema de documentación [Getting Document Information]().

Para convertir páginas específicas del documento, puede usar las siguientes clases [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/), que proporcionan los atributos `pages`, `page_number` y `pages_count`. Estas opciones le permiten especificar páginas individuales o un rango de páginas para convertir.

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

Puede especificar qué páginas del documento desea convertir, como se muestra en el siguiente ejemplo:

{{< tabs \"example-3\">}}
{{< tab \"convert_specific_document_pages.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_specific_document_pages():
    # Instanciar Converter con el documento de entrada 
    with Converter("./business-plan.docx") as converter:
        # Instanciar opciones de conversión para definir el formato de salida
        pdf_convert_options = PdfConvertOptions()
        # Especifique qué páginas del documento convertir
        pdf_convert_options.pages = [1, 3, 5]

        # Convierta las páginas especificadas del documento de entrada a PDF
        converter.convert("./pages-1-3-5.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_specific_document_pages()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx` es el archivo de muestra utilizado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) para descargarlo.

{{< /tab >}}
{{< tab \"pages-1-3-5.pdf\" >}}
```text
Binary file (PDF, 156 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_specific_document_pages/pages-1-3-5.pdf)
{{< /tab >}}
{{< /tabs >}}

### Example 2: Convert N Consecutive Pages

Como alternativa, puede especificar un número de páginas consecutivas para convertir, como se muestra en el siguiente ejemplo:

{{< tabs \"example-4\">}}
{{< tab \"convert_consecutive_document_pages.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_consecutive_document_pages():
    # Instanciar Converter con el documento de entrada 
    with Converter("./business-plan.docx") as converter:
        # Instanciar opciones de conversión para definir el formato de salida
        pdf_convert_options = PdfConvertOptions()
        # Especifique la página inicial y el número de páginas a convertir
        pdf_convert_options.page_number = 1
        pdf_convert_options.pages_count = 5

        # Convierta el rango especificado de páginas del documento a PDF
        converter.convert("./pages-1-through-5.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_consecutive_document_pages()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx` es el archivo de muestra utilizado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) para descargarlo.

{{< /tab >}}
{{< tab \"pages-1-through-5.pdf\" >}}
```text
Binary file (PDF, 216 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_consecutive_document_pages/pages-1-through-5.pdf)
{{< /tab >}}
{{< /tabs >}}
