---
title: "PdfConvertOptions 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "PDF 파일 형식으로 변환하기 위한 옵션."
type: docs
url: /ko/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/
is_root: false
weight: 340
---


## PdfConvertOptions class

PDF 파일 형식으로 변환하기 위한 옵션.

PdfConvertOptions 형식은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/__init__/) | 새로운 [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) 인스턴스를 초기화합니다. |

### 속성들
| 속성 | 설명 |
| :- | :- |
| [dpi](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/dpi/) | 변환 후 원하는 페이지 DPI입니다. 기본 해상도는 96 dpi입니다. |
| [embed_full_fonts](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/embed_full_fonts/) | 이 속성은 전체 글꼴 파일을 부분 집합 대신 PDF에 포함시킬지 여부를 결정합니다. |
| [fallback_page_size](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/fallback_page_size/) | 대체 페이지 크기입니다. |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/format/) | 입력 문서를 변환할 원하는 파일 형식입니다. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/margin_settings/) | PDF 변환 중 적용되는 여백 설정입니다. |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/orientation_settings/) | 방향 설정입니다. |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/page_number/) | 변환을 시작할 페이지 번호입니다. |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/pages/) | 변환할 페이지 인덱스 목록입니다; 특정 페이지를 변환하려면 지정하십시오. |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/pages_count/) | `page_number`부터 변환할 페이지 수입니다. |
| [password](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/password/) | 변환된 문서를 보호하는 데 사용되는 비밀번호입니다. |
| [pdf_options](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/pdf_options/) | PDF 전용 변환 옵션입니다. |
| [resize_mode](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/resize_mode/) | 크기 조정 모드는 페이지 크기가 변경될 때 콘텐츠를 어떻게 스케일링할지 지정합니다. 기본값은 AlignTopLeft(스케일링 없음)입니다. |
| [rotate](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/rotate/) | 페이지 회전입니다. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/size_settings/) | PDF 변환 중 사용되는 페이지 크기 설정입니다. |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/watermark/) | 워터마크 전용 옵션입니다. |

### 예제

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Guides
`PdfConvertOptions`를 사용하는 작업 가이드:

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert a Document to Another Format](/conversion/python-net/guides/convert-document-to-another-format/)
* [Convert Files Within Document Containers](/conversion/python-net/guides/convert-files-within-document-containers/)
* [Add a Watermark to Converted Document](/conversion/python-net/guides/add-watermark-to-converted-document/)
* [Load File From Local Disk](/conversion/python-net/guides/load-file-from-local-disk/)
* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)

### 또 보기
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
