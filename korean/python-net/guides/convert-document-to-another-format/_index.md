---
title: "문서를 다른 형식으로 변환"
linkTitle: "Convert to Another Format"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "GroupDocs.Conversion for Python via .NET에서 ConvertOptions의 pages / page_number / pages_count 속성을 사용하여 특정 페이지 또는 페이지 범위를 선택적으로 지정하면서 단일 문서를 한 형식에서 다른 형식으로 변환합니다."
type: docs
url: /ko/python-net/guides/convert-document-to-another-format/
is_root: false
weight: 40
---


이 문서 항목은 단일 문서를 다른 형식으로 변환하는 내용을 다루며, 출력으로 하나의 문서만 생성됩니다. 다음 다이어그램은 파일을 한 형식에서 다른 형식으로 변환하는 과정을 보여줍니다:

flowchart LR
%% Nodes
A[\"Input Document (e.g. DOCX)\"]
B[\"Conversion\"]
C[\"Converted Document (e.g. PDF)\"]

%% Edge connections between nodes
A --> B --> C

문서를 변환하고 저장하려면 다음 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 클래스 메서드를 사용하십시오:

- **`convert(file_path, convert_options)`**: Converts a document to a specified single output format and saves it to a file, such as converting a DOCX to PDF.
- **`convert(stream, convert_options)`**: Converts the document and writes it to a provided stream instead of a file path.

## Convert a Complete Document 

다음 [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) 클래스 목록을 사용하여 문서를 특정 단일 출력 형식으로 변환할 수 있습니다:

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

다음 예제는 DOCX 파일을 PDF로 변환하는 방법을 보여줍니다:

{{< tabs "example-1">}}
{{< tab "convert_document_to_another_format.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document_to_another_format():
    # 입력 문서로 Converter를 인스턴스화합니다 
    with Converter("./business-plan.docx") as converter:
        # 출력 형식을 정의하기 위해 변환 옵션을 인스턴스화합니다
        pdf_convert_options = PdfConvertOptions()
        
        # 입력 문서를 PDF로 변환합니다
        converter.convert("./business-plan.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_document_to_another_format()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx`는 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx)를 클릭하십시오.

{{< /tab >}}
{{< tab "business-plan.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_document_to_another_format/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

### Example 2: Specify Output Format

기본적으로, 각 [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) 클래스는 자체 기본 대상 형식을 가지고 있습니다. 예를 들어, [WordProcessingConvertOptions](https://reference.groupdocs.com/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/)의 기본 출력 형식은 [DOCX](https://reference.groupdocs.com/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/docx/)입니다.

형식군 내에서 다른 출력 형식을 설정하려면 `format` 속성을 사용하십시오. 다음 예제는 `DOCX` 파일을 변환할 때 대상 형식을 `TXT`로 지정하는 방법을 보여줍니다:

{{< tabs "example-2">}}
{{< tab "specify_output_format.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import WordProcessingConvertOptions
from groupdocs.conversion.filetypes import WordProcessingFileType

def specify_output_format():
    # 입력 문서로 Converter를 인스턴스화합니다 
    with Converter("./business-plan.docx") as converter:
        # 출력 형식을 정의하기 위해 변환 옵션을 인스턴스화합니다. 기본값은 DOCX입니다.
        word_convert_options = WordProcessingConvertOptions()
        # 형식군 내에서 출력 형식을 DOCX에서 TXT로 변경합니다.
        word_convert_options.format = WordProcessingFileType.TXT
        
        # 입력 문서를 TXT로 변환합니다.
        converter.convert("./business-plan.txt", word_convert_options)    

if __name__ == "__main__":
    specify_output_format()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx`는 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx)를 클릭하십시오.

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

문서 페이지 수를 확인하는 방법을 [Getting Document Information]() 문서 항목에서 알아보세요.

특정 문서 페이지를 변환하려면 다음 [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) 클래스를 사용할 수 있으며, 이 클래스는 `pages`, `page_number`, `pages_count` 속성을 제공합니다. 이러한 옵션을 사용하면 변환할 개별 페이지 또는 페이지 범위를 지정할 수 있습니다.

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

다음 예시와 같이 변환하려는 문서 페이지를 지정할 수 있습니다:

{{< tabs "example-3">}}
{{< tab "convert_specific_document_pages.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_specific_document_pages():
    # 입력 문서로 Converter를 인스턴스화합니다 
    with Converter("./business-plan.docx") as converter:
        # 출력 형식을 정의하기 위해 변환 옵션을 인스턴스화합니다
        pdf_convert_options = PdfConvertOptions()
        # 변환할 문서 페이지를 지정하세요
        pdf_convert_options.pages = [1, 3, 5]

        # 입력 문서의 지정된 페이지를 PDF로 변환합니다
        converter.convert("./pages-1-3-5.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_specific_document_pages()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx`는 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx)를 클릭하십시오.

{{< /tab >}}
{{< tab "pages-1-3-5.pdf" >}}
```text
Binary file (PDF, 156 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_specific_document_pages/pages-1-3-5.pdf)
{{< /tab >}}
{{< /tabs >}}

### Example 2: Convert N Consecutive Pages

대안으로, 다음 예시와 같이 연속된 페이지 수를 지정하여 변환할 수 있습니다:

{{< tabs "example-4">}}
{{< tab "convert_consecutive_document_pages.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_consecutive_document_pages():
    # 입력 문서로 Converter를 인스턴스화합니다 
    with Converter("./business-plan.docx") as converter:
        # 출력 형식을 정의하기 위해 변환 옵션을 인스턴스화합니다
        pdf_convert_options = PdfConvertOptions()
        # 시작 페이지와 변환할 페이지 수를 지정하세요
        pdf_convert_options.page_number = 1
        pdf_convert_options.pages_count = 5

        # 문서의 지정된 페이지 범위를 PDF로 변환합니다
        converter.convert("./pages-1-through-5.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_consecutive_document_pages()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx`는 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx)를 클릭하십시오.

{{< /tab >}}
{{< tab "pages-1-through-5.pdf" >}}
```text
Binary file (PDF, 216 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_consecutive_document_pages/pages-1-through-5.pdf)
{{< /tab >}}
{{< /tabs >}}
