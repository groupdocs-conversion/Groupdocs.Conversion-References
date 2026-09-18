---
title: Convert a Document to Another Format
linkTitle: "Convert to Another Format"
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Convert a single document from one format to another, optionally selecting specific pages or a page range using the pages / page_number / pages_count attributes on ConvertOptions with GroupDocs.Conversion for Python via .NET."
type: docs
url: /python-net/guides/convert-document-to-another-format/
is_root: false
weight: 40
---


This documentation topic covers the conversion of a single document to another format, where only one document is produced as output. The following diagram illustrates the process of converting a file from one format to another:

flowchart LR
    %% Nodes
    A["Input Document (e.g. DOCX)"]
    B["Conversion"]
    C["Converted Document (e.g. PDF)"]

    %% Edge connections between nodes
    A --> B --> C

To convert and save a document, use the following [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) class methods:

- **`convert(file_path, convert_options)`**: Converts a document to a specified single output format and saves it to a file, such as converting a DOCX to PDF.
- **`convert(stream, convert_options)`**: Converts the document and writes it to a provided stream instead of a file path.

## Convert a Complete Document 

The following list of [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) classes can be used to convert a document to a specific single output format:

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

The following example demonstrates how to convert a DOCX file to PDF:

{{< tabs "example-1">}}
{{< tab "convert_document_to_another_format.py" >}}  
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document_to_another_format():
    # Instantiate Converter with the input document 
    with Converter("./business-plan.docx") as converter:
        # Instantiate convert options to define the output format
        pdf_convert_options = PdfConvertOptions()
        
        # Convert the input document to PDF
        converter.convert("./business-plan.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_document_to_another_format()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}  

`business-plan.docx` is the sample file used in this example. Click [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) to download it.

{{< /tab >}}
{{< tab "business-plan.pdf" >}}  
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_document_to_another_format/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

### Example 2: Specify Output Format

By default, each of the [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) classes has its own default target format. For example, the default output format for [WordProcessingConvertOptions](https://reference.groupdocs.com/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/) is [DOCX](https://reference.groupdocs.com/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/docx/).

To set a different output format within the format family, use the `format` property. The following example demonstrates how to specify the target format as `TXT` when converting a `DOCX` file:

{{< tabs "example-2">}}
{{< tab "specify_output_format.py" >}}  
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import WordProcessingConvertOptions
from groupdocs.conversion.filetypes import WordProcessingFileType

def specify_output_format():
    # Instantiate Converter with the input document 
    with Converter("./business-plan.docx") as converter:
        # Instantiate convert options to define the output format, by default it is DOCX
        word_convert_options = WordProcessingConvertOptions()
        # Change the output format within the format family from DOCX to TXT
        word_convert_options.format = WordProcessingFileType.TXT
        
        # Convert the input document to TXT
        converter.convert("./business-plan.txt", word_convert_options)    

if __name__ == "__main__":
    specify_output_format()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}  

`business-plan.docx` is the sample file used in this example. Click [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) to download it.

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

 Find out how to get the number of document pages in the [Getting Document Information]() documentation topic. 

To convert specific document pages, you can use the following [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) classes, which provide `pages`, `page_number`, and `pages_count` attributes. These options allow you to specify individual pages or a range of pages to convert.

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

You can specify which document pages you would like to convert, as shown in the following example:

{{< tabs "example-3">}}
{{< tab "convert_specific_document_pages.py" >}}  
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_specific_document_pages():
    # Instantiate Converter with the input document 
    with Converter("./business-plan.docx") as converter:
        # Instantiate convert options to define the output format
        pdf_convert_options = PdfConvertOptions()
        # Specify which document pages to convert
        pdf_convert_options.pages = [1, 3, 5]

        # Convert the specified pages of the input document to PDF
        converter.convert("./pages-1-3-5.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_specific_document_pages()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}  

`business-plan.docx` is the sample file used in this example. Click [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) to download it.

{{< /tab >}}
{{< tab "pages-1-3-5.pdf" >}}  
```text
Binary file (PDF, 156 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_specific_document_pages/pages-1-3-5.pdf)
{{< /tab >}}
{{< /tabs >}}

### Example 2: Convert N Consecutive Pages

As an alternative, you can specify a number of consecutive pages to convert, as shown in the following example:

{{< tabs "example-4">}}
{{< tab "convert_consecutive_document_pages.py" >}}  
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_consecutive_document_pages():
    # Instantiate Converter with the input document 
    with Converter("./business-plan.docx") as converter:
        # Instantiate convert options to define the output format
        pdf_convert_options = PdfConvertOptions()
        # Specify the starting page and number of pages to convert
        pdf_convert_options.page_number = 1
        pdf_convert_options.pages_count = 5

        # Convert the specified range of pages in the document to PDF
        converter.convert("./pages-1-through-5.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_consecutive_document_pages()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}  

`business-plan.docx` is the sample file used in this example. Click [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) to download it.

{{< /tab >}}
{{< tab "pages-1-through-5.pdf" >}}  
```text
Binary file (PDF, 216 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_consecutive_document_pages/pages-1-through-5.pdf)
{{< /tab >}}
{{< /tabs >}}
