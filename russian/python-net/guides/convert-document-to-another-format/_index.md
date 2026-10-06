---
title: "Преобразовать документ в другой формат"
linkTitle: "Convert to Another Format"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Преобразуйте один документ из одного формата в другой, при необходимости выбирая определённые страницы или диапазон страниц с помощью атрибутов pages / page_number / pages_count в ConvertOptions при работе с GroupDocs.Conversion для Python через .NET."
type: docs
url: /ru/python-net/guides/convert-document-to-another-format/
is_root: false
weight: 40
---


Эта тема документации охватывает преобразование одного документа в другой формат, при котором в качестве результата создаётся только один документ. Ниже приведена диаграмма, иллюстрирующая процесс преобразования файла из одного формата в другой:

flowchart LR
%% Nodes
A[\"Input Document (e.g. DOCX)\"]
B[\"Conversion\"]
C[\"Converted Document (e. g. PDF)\"]

%% Edge connections between nodes
A --> B --> C

Чтобы преобразовать и сохранить документ, используйте следующие методы класса [`Converter`](/conversion/python-net/groupdocs.conversion/converter/):

- **`convert(file_path, convert_options)`**: Converts a document to a specified single output format and saves it to a file, such as converting a DOCX to PDF.
- **`convert(stream, convert_options)`**: Converts the document and writes it to a provided stream instead of a file path.

## Convert a Complete Document 

Следующий список классов [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) может быть использован для преобразования документа в конкретный одиночный формат вывода:

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

Следующий пример демонстрирует, как преобразовать файл DOCX в PDF:

{{< tabs \"example-1\">}}
{{< tab \"convert_document_to_another_format.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document_to_another_format():
    # Создайте экземпляр Converter с входным документом 
    with Converter("./business-plan.docx") as converter:
        # Создайте параметры преобразования для определения формата вывода
        pdf_convert_options = PdfConvertOptions()
        
        # Преобразуйте входной документ в PDF
        converter.convert("./business-plan.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_document_to_another_format()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` является примером файла, используемого в этом примере. Нажмите [здесь](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx), чтобы скачать его.

{{< /tab >}}
{{< tab \"business-plan.pdf\" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_document_to_another_format/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

### Example 2: Specify Output Format

По умолчанию каждый из классов [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) имеет собственный формат назначения по умолчанию. Например, формат вывода по умолчанию для [WordProcessingConvertOptions](https://reference.groupdocs.com/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/) — это [DOCX](https://reference.groupdocs.com/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/docx/).

Чтобы задать другой формат вывода в рамках семейства форматов, используйте свойство `format`. Следующий пример демонстрирует, как указать целевой формат как `TXT` при преобразовании файла `DOCX`:

{{< tabs \"example-2\">}}
{{< tab \"specify_output_format.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import WordProcessingConvertOptions
from groupdocs.conversion.filetypes import WordProcessingFileType

def specify_output_format():
    # Создайте экземпляр Converter с входным документом 
    with Converter("./business-plan.docx") as converter:
        # Создайте параметры преобразования, чтобы определить формат вывода, по умолчанию это DOCX
        word_convert_options = WordProcessingConvertOptions()
        # Измените формат вывода в рамках семейства форматов с DOCX на TXT
        word_convert_options.format = WordProcessingFileType.TXT
        
        # Конвертируйте входной документ в TXT
        converter.convert("./business-plan.txt", word_convert_options)    

if __name__ == "__main__":
    specify_output_format()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` является примером файла, используемого в этом примере. Нажмите [здесь](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx), чтобы скачать его.

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

Узнайте, как получить количество страниц документа в теме документации [Getting Document Information]().

Чтобы преобразовать отдельные страницы документа, вы можете использовать следующие классы [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/), которые предоставляют атрибуты `pages`, `page_number` и `pages_count`. Эти параметры позволяют указать отдельные страницы или диапазон страниц для преобразования.

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

Вы можете указать, какие страницы документа следует преобразовать, как показано в следующем примере:

{{< tabs \"example-3\">}}
{{< tab \"convert_specific_document_pages.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_specific_document_pages():
    # Создайте экземпляр Converter с входным документом 
    with Converter("./business-plan.docx") as converter:
        # Создайте параметры преобразования для определения формата вывода
        pdf_convert_options = PdfConvertOptions()
        # Укажите, какие страницы документа преобразовать
        pdf_convert_options.pages = [1, 3, 5]

        # Преобразуйте указанные страницы входного документа в PDF
        converter.convert("./pages-1-3-5.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_specific_document_pages()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` является примером файла, используемого в этом примере. Нажмите [здесь](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx), чтобы скачать его.

{{< /tab >}}
{{< tab \"pages-1-3-5.pdf\" >}}
```text
Binary file (PDF, 156 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_specific_document_pages/pages-1-3-5.pdf)
{{< /tab >}}
{{< /tabs >}}

### Example 2: Convert N Consecutive Pages

В качестве альтернативы вы можете указать количество последовательных страниц для преобразования, как показано в следующем примере:

{{< tabs \"example-4\">}}
{{< tab \"convert_consecutive_document_pages.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_consecutive_document_pages():
    # Создайте экземпляр Converter с входным документом 
    with Converter("./business-plan.docx") as converter:
        # Создайте параметры преобразования для определения формата вывода
        pdf_convert_options = PdfConvertOptions()
        # Укажите начальную страницу и количество страниц для преобразования
        pdf_convert_options.page_number = 1
        pdf_convert_options.pages_count = 5

        # Преобразуйте указанный диапазон страниц документа в PDF
        converter.convert("./pages-1-through-5.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_consecutive_document_pages()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` является примером файла, используемого в этом примере. Нажмите [здесь](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx), чтобы скачать его.

{{< /tab >}}
{{< tab \"pages-1-through-5.pdf\" >}}
```text
Binary file (PDF, 216 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_consecutive_document_pages/pages-1-through-5.pdf)
{{< /tab >}}
{{< /tabs >}}
