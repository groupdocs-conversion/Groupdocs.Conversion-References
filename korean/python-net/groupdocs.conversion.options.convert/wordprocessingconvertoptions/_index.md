---
title: "WordProcessingConvertOptions 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "워드 프로세싱 파일 형식으로 변환하기 위한 옵션."
type: docs
url: /ko/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/
is_root: false
weight: 620
---


## WordProcessingConvertOptions class

워드 프로세싱 파일 형식으로 변환하기 위한 옵션.

WordProcessingConvertOptions 형식은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/__init__/) | 새 인스턴스를 초기화합니다 [`WordProcessingConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/). |

### 속성들
| 속성 | 설명 |
| :- | :- |
| [dpi](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/dpi/) | 변환 후 원하는 페이지 DPI입니다. 기본 해상도는 96 dpi입니다. |
| [fallback_page_size](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/fallback_page_size/) | 대체 페이지 크기입니다. |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/format/) | 입력 문서를 변환할 원하는 파일 형식입니다. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/margin_settings/) | 변환을 위한 여백 설정이며, [`IPageMarginOptions`](/conversion/python-net/groupdocs.conversion.options/ipagemarginoptions/) 로 표시됩니다. |
| [markdown_options](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/markdown_options/) | Markdown 변환 옵션입니다. |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/orientation_settings/) | 방향 설정입니다. |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/page_number/) | 변환을 시작할 페이지 번호입니다. |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/pages/) | 변환할 페이지 인덱스 목록입니다. 특정 페이지를 변환하려면 지정해야 합니다. |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/pages_count/) | `PageNumber`부터 변환할 페이지 수입니다. |
| [password](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/password/) | 변환된 문서를 보호하는 데 사용되는 비밀번호입니다. |
| [pdf_recognition_mode](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/pdf_recognition_mode/) | 변환에 사용되는 PDF 인식 모드이며, [`IPdfRecognitionModeOptions.pdf_recognition_mode`](/conversion/python-net/groupdocs.conversion.options.convert/ipdfrecognitionmodeoptions/pdf_recognition_mode/) 를 구현합니다. |
| [rtf_options](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/rtf_options/) | RTF 전용 변환 옵션입니다. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/size_settings/) | 변환을 위한 크기 설정입니다. |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/watermark/) | 워터마크 전용 옵션입니다. |
| [zoom](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/zoom/) | 백분율로 표시된 확대 수준입니다. |

### 예제

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import WordProcessingConvertOptions
from groupdocs.conversion.filetypes import WordProcessingFileType

with Converter("./business-plan.docx") as converter:
    options = WordProcessingConvertOptions()
    options.format = WordProcessingFileType.TXT
    converter.convert("./business-plan.txt", options)
```

### Guides
`WordProcessingConvertOptions` 를 사용하는 작업 가이드:

* [Convert a Document to Another Format](/conversion/python-net/guides/convert-document-to-another-format/)

### 또 보기
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
