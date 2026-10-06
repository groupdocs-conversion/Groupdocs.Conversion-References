---
title: "빠른 시작 가이드"
linkTitle: "Quick Start Guide"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "가상 환경을 설정하고, groupdocs-conversion-net을 설치한 뒤, 세 가지 최소 예제 — DOCX → PDF, PDF → 페이지별 PNG, ZIP → 통합 PDF — 를 5분 이내에 실행합니다."
type: docs
url: /ko/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


이 가이드는 .NET을 통해 GroupDocs.Conversion for Python을 설정하고 사용을 시작하는 방법에 대한 간략한 개요를 제공합니다. 이 라이브러리를 사용하면 개발자가 다양한 파일 형식(DOCX, PDF, PNG 등) 간을 최소한의 구성으로 변환할 수 있습니다.

## Prerequisites

진행하려면 다음이 준비되어 있는지 확인하십시오:

1. **Configured** 환경을 [System Requirements]() 항목에 설명된 대로 설정합니다.
2. **Optionally** [Get a Temporary License](https://purchase.groupdocs.com/temporary-license/)를 받아 제품의 모든 기능을 테스트할 수 있습니다.

## Set Up Your Development Environment

최선의 방법으로, Python 애플리케이션에서 종속성을 관리하기 위해 가상 환경을 사용하십시오. 가상 환경에 대한 자세한 내용은 [Create and Use Virtual Environments](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments) 문서를 참고하십시오.

### Create and Activate a Virtual Environment

가상 환경을 생성합니다:

{{< tabs \"example1\">}}
{{< tab \"Windows\" >}}
```ps
py -m venv .venv
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< /tabs >}}

가상 환경을 활성화합니다:

{{< tabs \"example2\">}}
{{< tab \"Windows\" >}}
```ps
.venv\Scripts\activate
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< /tabs >}}

### Install `groupdocs-conversion-net` Package

가상 환경을 활성화한 후, 터미널에서 다음 명령을 실행하여 최신 버전의 패키지를 설치합니다:

{{< tabs \"example3\">}}
{{< tab \"Windows\" >}}
```ps
py -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< /tabs >}}

패키지가 성공적으로 설치되었는지 확인하십시오. 다음 메시지가 표시됩니다.

```bash
Successfully installed groupdocs-conversion-net-*
```

## Example 1: Convert document

라이브러리를 빠르게 테스트하려면 DOCX 파일을 PDF로 변환해 보겠습니다. 또한 우리가 만들 앱을 [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_docx_to_pdf.zip)에서 다운로드할 수 있습니다.

{{< tabs \"demo_app_convert_docx_to_pdf\">}}
{{< tab "convert_docx_to_pdf.py" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_docx_to_pdf():
    # 라이선스 파일 절대 경로 가져오기
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # 라이선스를 생성하고 경로를 설정합니다
        license = License()
        license.set_license(license_path)

    # DOCX 파일을 로드합니다
    with Converter("./business-plan.docx") as converter:
        # 변환 옵션을 생성합니다
        pdf_convert_options = PdfConvertOptions()

        # DOCX를 PDF로 변환합니다
        converter.convert("./business-plan.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_docx_to_pdf()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx`은 이 예제에서 사용되는 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/business-plan.docx) 를 클릭하십시오.

{{< /tab >}}
{{< tab "business-plan.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_docx_to_pdf/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

폴더 트리는 다음 디렉터리 구조와 비슷하게 보일 것입니다:

```Directory
📂 demo-app
 ├──convert_docx_to_pdf.py
 ├──business-plan.docx
 └──GroupDocs.Conversion.lic (Optionally)
```

### Run the App

{{< tabs \"run-the-app\">}}
{{< tab \"Windows\" >}}
```ps
py convert_docx_to_pdf.py
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 convert_docx_to_pdf.py
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 convert_docx_to_pdf.py
```
{{< /tab >}}
{{< /tabs >}}

앱을 실행한 후 `deactivate`를 실행하거나 셸을 닫아 가상 환경을 비활성화할 수 있습니다.

### Explanation
- `Converter("./business-plan.docx")`: Initializes the converter with the DOCX file.
- `PdfConvertOptions()`: Specifies the output format as PDF.
- `converter.convert("./business-plan.pdf", pdf_convert_options)`: Converts the DOCX file to PDF and saves it as `business-plan.pdf`.

## Example 2: Convert document pages

이 예제에서는 PDF 문서 페이지를 PNG로 변환합니다. 우리가 만들 앱을 [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_pdf_pages_to_png.zip)에서 다운로드할 수 있습니다.

{{< tabs \"demo_app_convert_pdf_pages_to_png\">}}
{{< tab \"convert_pdf_pages_to_png.py\" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_pdf_pages_to_png():
    # 라이선스 파일 절대 경로 가져오기
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # 라이선스를 생성하고 경로를 설정합니다
        license = License()
        license.set_license(license_path)

    output_folder = "./converted-pages"
    os.makedirs(output_folder, exist_ok=True)

    # PDF 문서를 로드합니다
    with Converter("./annual-review.pdf") as converter:
        # 원본 문서의 총 페이지 수를 확인합니다
        pages_count = converter.get_document_info().pages_count

        # 변환 옵션을 생성하고 루프 내에서 재사용합니다
        png_convert_options = ImageConvertOptions()
        png_convert_options.format = ImageFileType.PNG
        png_convert_options.pages_count = 1

        # 각 페이지를 별도의 PNG 파일로 변환합니다
        for page_number in range(1, pages_count + 1):
            png_convert_options.page_number = page_number
            output_file = os.path.join(output_folder, f"converted-page-{page_number}.png")
            converter.convert(output_file, png_convert_options)

if __name__ == "__main__":
    convert_pdf_pages_to_png()
```
{{< /tab >}}
{{< tab \"annual-review.pdf\" >}}

`annual-review.pdf`은 이 예제에서 사용되는 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/annual-review.pdf) 를 클릭하십시오.

{{< /tab >}}
{{< tab \"convert-pdf-pages-to-png-outputs.zip\" >}}
```text
converted-pages/converted-page-1.png (1148 KB)
converted-pages/converted-page-2.png (89 KB)
converted-pages/converted-page-3.png (83 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_pdf_pages_to_png/convert-pdf-pages-to-png-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

폴더 트리는 다음 디렉터리 구조와 비슷하게 보일 것입니다:

```Directory
📂 demo-app
 ├──annual-review.pdf
 ├──convert_pdf_pages_to_png.py
 └──GroupDocs.Conversion.lic (Optionally)
```

### Run the App

{{< tabs \"run_the_app_convert_pdf_pages_to_png\">}}
{{< tab \"Windows\" >}}
```ps
py convert_pdf_pages_to_png.py
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 convert_pdf_pages_to_png.py
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 convert_pdf_pages_to_png.py
```
{{< /tab >}}
{{< /tabs >}}

앱을 실행한 후 `deactivate`를 실행하거나 셸을 닫아 가상 환경을 비활성화할 수 있습니다.

### Explanation
- `Converter("./annual-review.pdf")`: Initializes the converter with the PDF file.
- `converter.get_document_info().pages_count`: Retrieves the total number of pages in the source document.
- `ImageConvertOptions()` with `format = ImageFileType.PNG`: Specifies the output format as PNG image.
- The loop updates `png_convert_options.page_number` on each iteration (with `pages_count = 1`) and calls `converter.convert(...)` to write one PNG file per page into the `converted-pages` folder.

## Example 3: Convert files in archive

이 예제에서는 ZIP 압축 파일의 내용을 PDF로 변환합니다. GroupDocs.Conversion은 압축 파일을 열고 내부 파일을 변환하여 모든 변환된 문서를 포함하는 단일 통합 PDF를 생성합니다. 우리가 만들 앱을 [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_files_in_archive.zip)에서 다운로드할 수 있습니다.

{{< tabs \"demo_app_convert_files_in_archive\">}}
{{< tab \"convert_files_in_archive.py\" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_files_in_archive():
    # 라이선스 파일 절대 경로 가져오기
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # 라이선스를 생성하고 경로를 설정합니다
        license = License()
        license.set_license(license_path)

    # ZIP 파일을 로드합니다
    with Converter("./compressed.zip") as converter:
        # 변환 옵션을 생성합니다
        pdf_convert_options = PdfConvertOptions()

        # 압축 파일을 추출하고, 내용을 변환한 뒤, 통합 PDF로 저장합니다
        converter.convert("./converted.pdf", pdf_convert_options)

if __name__ == "__main__":
    convert_files_in_archive()
```
{{< /tab >}}
{{< tab "compressed.zip" >}}

`compressed.zip`은 이 예제에서 사용되는 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/compressed.zip) 를 클릭하십시오.

{{< /tab >}}
{{< tab "converted.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_files_in_archive/converted.pdf)
{{< /tab >}}
{{< /tabs >}}

폴더 트리는 다음 디렉터리 구조와 비슷하게 보일 것입니다:

```Directory
📂 demo-app
 ├──compressed.zip
 ├──convert_files_in_archive.py
 └──GroupDocs.Conversion.lic (Optionally)
```

### Run the App

{{< tabs "run_the_app_convert_files_in_archive">}}
{{< tab \"Windows\" >}}
```ps
py convert_files_in_archive.py
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 convert_files_in_archive.py
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 convert_files_in_archive.py
```
{{< /tab >}}
{{< /tabs >}}

앱을 실행한 후 `deactivate`를 실행하거나 셸을 닫아 가상 환경을 비활성화할 수 있습니다.

### Explanation
- `Converter("./compressed.zip")`: Initializes the converter with the ZIP file.
- `PdfConvertOptions()`: Specifies the output format as PDF.
- `converter.convert("./converted.pdf", pdf_convert_options)`: Extracts the archive, converts its contents, and writes a single consolidated PDF to `converted.pdf`.

## Next Steps

기본을 마친 후, 사용성을 향상시키기 위해 추가 리소스를 탐색하세요:
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Check details on licensing and evaluation.
- [Technical Support](): Contact support for assistance if you encounter issues.
