---
title: "문서를 여러 페이지 파일로 변환"
linkTitle: "Convert Document To Multiple"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "id: convert-document-to-multiple-page-files"
type: docs
url: /ko/python-net/guides/convert-document-to-multiple-page-files/
is_root: false
weight: 60
---


---
id: convert-document-to-multiple-page-files
url: conversion/python-net/developer-guide/converting-documents/convert-document-to-multiple-page-files
title: 문서를 여러 페이지 파일로 변환
linkTitle: 여러 파일로 변환
weight: 3
description: "다중 페이지 문서의 각 페이지를 개별 출력 파일로 렌더링합니다 — pages_count=1로 page_number를 반복하고 Converter.convert()를 사용하여 GroupDocs.Conversion for Python via .NET으로 페이지당 PNG, PDF 또는 이미지를 생성합니다."
keywords: 다중 파일로 변환, 페이지당 출력, page_number, pages_count, 페이지 루프, 프레젠테이션 페이지 변환, PDF 페이지를 PNG로 변환, ImageConvertOptions, GroupDocs.Conversion, python
productName: GroupDocs.Conversion for Python via .NET
hideChildren: false
toc: true
---

이 문서 항목은 단일 다중 페이지 문서를 개별 페이지 파일로 변환하는 내용을 다룹니다. 다음 다이어그램은 다중 페이지 파일을 별도 페이지로 변환하는 과정을 보여줍니다:

flowchart LR
%% Nodes
A["입력 문서"]
B[\"Conversion\"]
C["변환된 페이지 1"]
D["변환된 페이지 2"]
E["변환된 페이지 N"]

%% Edge connections between nodes
A --> B --> C
B --> D
B --> E

문서를 페이지당 파일로 변환하려면, 지원되는 [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) 클래스의 `page_number` 및 `pages_count` 속성과 함께 `Converter.convert(file_path, convert_options)` 메서드를 사용하십시오:

- **`page_number`**: One-based index of the first page to convert.
- **`pages_count`**: Number of consecutive pages to convert starting from `page_number`.

페이지당 하나의 출력 파일을 생성하려면, `1`부터 `converter.get_document_info().pages_count`까지 반복하면서 각 반복에서 `page_number`를 업데이트하고 다른 출력 경로에 기록하십시오. `pages_count = 1`을 설정하면 각 호출이 단일 페이지를 내보냅니다.

## Supported ConvertOptions Classes

다음 [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) 클래스는 이 항목에서 사용되는 `page_number` 및 `pages_count` 속성을 노출합니다:

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

다음 예제는 PPTX 프레젠테이션의 각 슬라이드를 PNG 이미지로 변환하고 출력 이미지를 지정된 폴더에 저장하는 방법을 보여줍니다.
 
출력 파일의 파일 이름 템플릿은 `converted-page-{page number}.{output file extension}`입니다. 이 예제에서는 첫 번째 슬라이드가 `converted-page-1.png`로 저장됩니다.

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

    # 입력 문서로 Converter를 인스턴스화합니다.
    with Converter("./basic-presentation.pptx") as converter:
        # 원본 문서의 총 페이지 수를 확인합니다
        pages_count = converter.get_document_info().pages_count

        # 변환 옵션을 한 번 인스턴스화하고 루프 내부에서 재사용하십시오
        png_convert_options = ImageConvertOptions()
        png_convert_options.format = ImageFileType.PNG
        png_convert_options.pages_count = 1

        # 각 페이지를 별도의 PNG 파일로 변환합니다
        for page_number in range(1, pages_count + 1):
            png_convert_options.page_number = page_number
            output_file = os.path.join(output_folder, f"converted-page-{page_number}.png")
            converter.convert(output_file, png_convert_options)

if __name__ == "__main__":
    convert_all_document_pages()
```
{{< /tab >}}
{{< tab "basic-presentation.pptx" >}}

`basic-presentation.pptx`는 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [여기](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx)를 클릭하십시오.

{{< /tab >}}
{{< tab "convert-all-document-pages-outputs.zip" >}}
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

문서 페이지 수를 확인하는 방법을 [Getting Document Information]() 문서 항목에서 알아보세요.

다음 예제는 PPTX 프레젠테이션에서 특정 슬라이드를 변환하고 별도 파일로 저장하는 방법을 보여줍니다.

{{< tabs "example-2">}}
{{< tab "convert_specific_document_page_to_file.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_specific_document_page_to_file():
    # 입력 문서로 Converter를 인스턴스화합니다.
    with Converter("./basic-presentation.pptx") as converter:
        # 변환 옵션을 인스턴스화합니다
        png_convert_options = ImageConvertOptions()
        # 출력 형식을 PNG로 정의하십시오
        png_convert_options.format = ImageFileType.PNG

        # 변환할 단일 페이지를 지정하세요
        png_convert_options.page_number = 3
        png_convert_options.pages_count = 1

        # 변환된 페이지를 파일에 저장합니다
        converter.convert("./slide-3.png", png_convert_options)

if __name__ == "__main__":
    convert_specific_document_page_to_file()
```
{{< /tab >}}
{{< tab "basic-presentation.pptx" >}}

`basic-presentation.pptx`는 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [여기](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx)를 클릭하십시오.

{{< /tab >}}
{{< tab \"slide-3.png\" >}}
```text
Binary file (PNG, 797 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_specific_document_page_to_file/slide-3.png)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Convert a Specific Page and Load Output Into a Stream

문서 페이지 수를 확인하는 방법을 [Getting Document Information]() 문서 항목에서 알아보세요.

변환된 페이지를 메모리 버퍼로 필요로 하는 경우(예: 파일 시스템을 건드리지 않고 다른 API로 전달하려면), 먼저 페이지를 파일로 변환한 다음 `BytesIO` 객체로 읽어들입니다:

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

    # 입력 문서로 Converter를 인스턴스화합니다.
    with Converter("./basic-presentation.pptx") as converter:
        # 변환 옵션을 인스턴스화합니다
        png_convert_options = ImageConvertOptions()
        # 출력 형식을 PNG로 정의하십시오
        png_convert_options.format = ImageFileType.PNG

        # 변환할 단일 페이지를 지정하세요
        png_convert_options.page_number = page_number_to_convert
        png_convert_options.pages_count = 1

        # 페이지를 변환하여 디스크에 파일로 저장합니다
        converter.convert(output_file, png_convert_options)

    # 변환된 페이지를 메모리 스트림에 로드하여 이후에 사용합니다
    with open(output_file, "rb") as file_handle:
        page_stream = io.BytesIO(file_handle.read())

    # page_stream은 이제 PNG 바이트 데이터를 보유하고 있으며, 모든 소비자에게 전달할 수 있습니다
    print(f"Loaded {page_stream.getbuffer().nbytes} bytes into memory")

if __name__ == "__main__":
    convert_specific_document_page_to_stream()
```
{{< /tab >}}
{{< tab "basic-presentation.pptx" >}}

`basic-presentation.pptx`는 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [여기](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx)를 클릭하십시오.

{{< /tab >}}
{{< tab \"slide-5.png\" >}}
```text
Binary file (PNG, 75 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_specific_document_page_to_stream/slide-5.png)
{{< /tab >}}
{{< /tabs >}}
