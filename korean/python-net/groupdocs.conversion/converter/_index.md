---
title: "Converter 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "문서 변환 프로세스를 제어하는 주요 클래스를 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.conversion/converter/
is_root: false
weight: 80
---


## Converter class

문서 변환 프로세스를 제어하는 주요 클래스를 나타냅니다.

Converter 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider) | 새 Converter 인스턴스를 초기화합니다. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-settings) | 새 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 인스턴스를 초기화합니다. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-load_options-settings) | 새 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 인스턴스를 초기화합니다. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-load_options-settings-events) | 명시적 변환 이벤트가 있는 새 Converter를 초기화합니다. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-settings-events) | 명시적 변환 이벤트가 있는 새 Converter 인스턴스를 초기화합니다. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path) | 새 Converter 인스턴스를 초기화합니다. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-settings) | 새 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 인스턴스를 초기화합니다. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-load_options-settings) | 새 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 클래스 인스턴스를 초기화합니다. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-load_options-settings-events) | 명시적 변환 이벤트가 있는 새 Converter를 초기화합니다. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-settings-events) | 명시적 변환 이벤트가 있는 새 Converter를 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options) | 소스 문서를 변환하고 전체 변환된 문서를 저장합니다. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options-document_completed) | 소스 문서를 변환하고 전체 변환된 문서를 저장합니다. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options_provider) | 소스 문서를 변환하고 전체 변환된 문서를 저장합니다. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options_provider-document_completed) | 소스 문서를 변환하고 전체 변환된 문서를 저장합니다. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#file_path-convert_options) | 소스 문서를 변환하고 전체 변환된 문서를 저장합니다. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options_provider) | 소스 문서를 변환하고 변환된 문서를 페이지별로 저장합니다. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options) | 소스 문서를 변환하고 변환된 문서를 페이지별로 저장합니다. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options-document_completed) | 소스 문서를 변환하고 변환된 문서를 페이지별로 저장합니다. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options_provider-document_completed) | 소스 문서를 변환하고 변환된 문서를 페이지별로 저장합니다. |
| [convert_convert_options](/conversion/python-net/groupdocs.conversion/converter/convert_convert_options/) |  |
| [convert_file](/conversion/python-net/groupdocs.conversion/converter/convert_file/) |  |
| [convert_func](/conversion/python-net/groupdocs.conversion/converter/convert_func/) |  |
| [convert_string](/conversion/python-net/groupdocs.conversion/converter/convert_string/) |  |
| [dispose](/conversion/python-net/groupdocs.conversion/converter/dispose/) | 리소스를 해제합니다. |
| [get_all_possible_conversions](/conversion/python-net/groupdocs.conversion/converter/get_all_possible_conversions/) | 지원되는 모든 변환을 가져옵니다. |
| [get_document_info](/conversion/python-net/groupdocs.conversion/converter/get_document_info/) | 페이지 수 및 파일 유형에 특화된 기타 속성을 포함한 소스 문서 정보를 검색합니다. |
| [get_possible_conversions](/conversion/python-net/groupdocs.conversion/converter/get_possible_conversions/) | 소스 문서에 대한 가능한 변환을 검색합니다. |
| [get_possible_conversions_by_extension](/conversion/python-net/groupdocs.conversion/converter/get_possible_conversions_by_extension/#extension) | 제공된 문서 확장자에 대한 지원되는 변환을 가져옵니다. |
| [is_document_password_protected](/conversion/python-net/groupdocs.conversion/converter/is_document_password_protected/) | 소스 문서가 암호로 보호되어 있는지 확인합니다. |

### 예제

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("sample.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Guides
`Converter`를 사용하는 작업 가이드:

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert a Document to Another Format](/conversion/python-net/guides/convert-document-to-another-format/)
* [Get Possible Conversions](/conversion/python-net/guides/get-possible-conversions/)
* [Convert Document To Multiple Page Files](/conversion/python-net/guides/convert-document-to-multiple-page-files/)
* [Convert Files Within Document Containers](/conversion/python-net/guides/convert-files-within-document-containers/)
* [Add a Watermark to Converted Document](/conversion/python-net/guides/add-watermark-to-converted-document/)
* [Load File From Local Disk](/conversion/python-net/guides/load-file-from-local-disk/)
* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)
* [Getting Document Information](/conversion/python-net/guides/getting-document-info/)

### 또 보기
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
