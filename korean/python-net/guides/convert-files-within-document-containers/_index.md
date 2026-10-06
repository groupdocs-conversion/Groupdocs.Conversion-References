---
title: "문서 컨테이너 내 파일 변환"
linkTitle: "Convert Archives and Containers"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "ZIP, RAR, 7Z, OST, PST 및 기타 컨테이너 형식을 열고, 내용물을 변환한 뒤, .NET을 통한 Python용 GroupDocs.Conversion의 단일 Converter.convert() 호출로 통합된 출력 문서를 작성합니다."
type: docs
url: /ko/python-net/guides/convert-files-within-document-containers/
is_root: false
weight: 70
---


이 항목에서는 압축 파일이나 패키지 파일과 같이 문서 컨테이너에 포함된 파일을 개별 출력 파일로 변환하는 방법을 다룹니다. 다음 다이어그램은 문서 컨테이너 내 파일을 추출하고 변환하는 과정을 보여줍니다:

flowchart LR
%% Nodes
A["문서 컨테이너"]
B["추출"]
C["변환"]
D["변환된 파일 1"]
E["변환된 파일 2"]
F["변환된 파일 N"]

%% Edge connections between nodes
A --> B --> C --> D
C --> E
C --> F

추출 및 변환 프로세스는 `convert(file_path, convert_options)` 메서드를 단일 호출로 수행합니다. 이 메서드는 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 클래스의 메서드입니다. GroupDocs.Conversion은 컨테이너를 열고, 포함된 파일들을 변환하며, 통합된 출력 문서를 작성합니다.

## Document Container File Types

다음 파일 유형은 문서 컨테이너로 간주됩니다:

### Email and Outlook

- **EML** - Email Message File.
- **EMLX** - Apple Mail Email File.
- **MSG** - Microsoft Outlook Message File.
- **OST** - Outlook Offline Data File.
- **PST** - Outlook Personal Information Store File.

### PDF

- **PDF** - PDF files that contain embedded resources.

### Word Processing

- **DOC** - The older Microsoft Word binary format.
- **DOCX** - The modern Word format.
- **DOT and DOTX** - Word template files.
- **RTF** - Rich Text Format.

### Compression

- **7Z** - 7-Zip Compressed File.
- **BZ2** - Bzip2 Compressed File.
- **CAB** - Windows Cabinet File.
- **CPIO** - CPIO Compressed File.
- **GZ** - Gnu Zipped Archive.
- **GZIP** - Gzip Compressed File.
- **LZ** - Lzip Compressed File.
- **LZMA** - LZMA Compressed File.
- **RAR** - RAR Compressed Archive.
- **TAR** - Consolidated Unix File Archive.
- **XZ** - Xz Compressed File.
- **Z** - Unix Compressed File.
- **ZIP** - ZIP Compressed File.

## Example: Convert Files Within Document Container

다음 예제는 ZIP 아카이브의 내용을 단일 통합 PDF로 변환하는 방법을 보여줍니다:

{{< tabs "example-1">}}
{{< tab "convert_files_within_document_container.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_files_within_document_container():
    # 입력 문서 컨테이너로 Converter를 인스턴스화합니다
    with Converter("./compressed.zip") as converter:
        # 변환 옵션을 인스턴스화합니다
        pdf_convert_options = PdfConvertOptions()

        # 아카이브를 추출하고, 포함된 파일들을 변환한 뒤, 통합 PDF를 저장합니다
        converter.convert("./converted.pdf", pdf_convert_options)

if __name__ == "__main__":
    convert_files_within_document_container()
```
{{< /tab >}}
{{< tab "compressed.zip" >}}

`compressed.zip`은 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-files-within-document-containers/compressed.zip)를 클릭하세요.

{{< /tab >}}
{{< tab "converted.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-files-within-document-containers/convert_files_within_document_container/converted.pdf)
{{< /tab >}}
{{< /tabs >}}
