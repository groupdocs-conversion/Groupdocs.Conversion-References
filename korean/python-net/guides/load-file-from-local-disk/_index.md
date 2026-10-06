---
title: "로컬 디스크에서 파일 로드"
linkTitle: "Load From Local Disk"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "절대 경로나 상대 경로 파일 경로를 사용하여 Converter 클래스를 인스턴스화하고, .NET을 통한 Python용 GroupDocs.Conversion으로 로컬 파일 시스템에 저장된 문서를 변환합니다."
type: docs
url: /ko/python-net/guides/load-file-from-local-disk/
is_root: false
weight: 90
---


로컬 디스크에서 소스 파일을 로드하려면 GroupDocs.Conversion의 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 클래스 생성자를 사용할 수 있습니다. API는 여러 오버로드를 제공하여 다양한 설정 및 옵션에 대한 유연성을 허용합니다:

* `Converter(file_path)`
* `Converter(file_path, load_options)`
* `Converter(file_path, converter_settings)`
* `Converter(file_path, load_options, converter_settings)`

각 생성자는 소스 파일 경로를 정의하는 `filePath` 매개변수가 필요합니다. 이를 절대 경로나 상대 경로로 지정할 수 있습니다. 지정된 파일 경로가 존재하지 않으면 예외가 발생한다는 점에 유의하십시오.

GroupDocs.Conversion은 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 클래스 인스턴스를 사용하여 작업(예: 변환)이 수행될 때만 파일에 접근합니다.

다음 Python 예제는 로컬 디스크에서 파일을 로드하고 PDF로 변환하는 방법을 보여줍니다:

{{< tabs "code-example">}}
{{< tab "convert_docx_to_pdf.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_docx_to_pdf():
    # 소스 파일 위치 지정
    converter = Converter("./business-plan.docx")
    
    # 출력 파일 위치 및 변환 옵션 지정
    output_path = "./business-plan.pdf"
    pdf_options = PdfConvertOptions()
    
    # 변환하고 출력 경로에 저장
    converter.convert(output_path, pdf_options)

if __name__ == "__main__":
    convert_docx_to_pdf()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx`는 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/loading-documents/load-file-from-local-disk/business-plan.docx)를 클릭하십시오.

{{< /tab >}}
{{< tab "business-plan.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/loading-documents/load-file-from-local-disk/convert_docx_to_pdf/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

GroupDocs.Conversion은 파일 확장자를 통해 파일 유형을 결정합니다. 파일 확장자가 설정되지 않은 경우, GroupDocs.Conversion은 파일 유형을 자동으로 감지하려 시도합니다. 파일 유형 및 크기에 따라 자동 파일 유형 감지는 메모리와 CPU 시간과 같은 추가 리소스를 소비합니다. 따라서 파일에 올바른 확장자가 있는지 확인하거나 로드 옵션을 허용하는 Converter 클래스 생성자를 사용하는 것을 권장합니다.

### Explanation

- **Load Source File**: The [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) class is instantiated with the path to the source document ("business-plan.docx").
- **Conversion Options**: An instance of [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) is created to define the settings for PDF conversion.
- **Execute Conversion**: The `convert` method is used to convert the document and save it to the specified output path ("business-plan.pdf").

로드 옵션 및 기타 생성자 오버로드 사용에 대한 자세한 내용은 [GroupDocs.Conversion API Reference](https://reference.groupdocs.com/conversion/python-net/)를 참조하십시오.
