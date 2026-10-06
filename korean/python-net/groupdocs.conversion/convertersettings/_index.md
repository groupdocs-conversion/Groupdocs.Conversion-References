---
title: "ConverterSettings 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "Converter 동작을 사용자 정의하기 위한 설정을 정의합니다."
type: docs
url: /ko/python-net/groupdocs.conversion/convertersettings/
is_root: false
weight: 90
---


## ConverterSettings class

Converter 동작을 사용자 정의하기 위한 설정을 정의합니다.

ConverterSettings 타입은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/convertersettings/__init__/) | ConverterSettings의 새 인스턴스를 기본값으로 초기화합니다. |

### 속성들
| 속성 | 설명 |
| :- | :- |
| [cache](/conversion/python-net/groupdocs.conversion/convertersettings/cache/) | 변환 결과를 저장하는 데 사용되는 캐시 구현입니다. |
| [font_directories](/conversion/python-net/groupdocs.conversion/convertersettings/font_directories/) | 사용자 정의 폰트 디렉터리 경로입니다. |
| [listener](/conversion/python-net/groupdocs.conversion/convertersettings/listener/) | 변환 상태와 진행 상황을 모니터링하기 위해 사용되는 컨버터 리스너 구현으로, Started, Progress 및 Completed 콜백이 [`ConversionEvents.on_conversion_started`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/), [`ConversionEvents.on_conversion_progress`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/), 그리고 [`ConversionEvents.on_conversion_completed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) 로 전달되며, [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 생성 중에 사용됩니다. |
| [logger](/conversion/python-net/groupdocs.conversion/convertersettings/logger/) | 변환 프로세스를 로깅하는 데 사용되는 로거 구현입니다. |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion/convertersettings/on_compression_completed/) | 압축 완료 시 이벤트 핸들러입니다. |
| [on_conversion_by_page_failed](/conversion/python-net/groupdocs.conversion/convertersettings/on_conversion_by_page_failed/) | 페이지별 변환이 실패했을 때 호출되는 이벤트 핸들러입니다. |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion/convertersettings/on_conversion_failed/) | 변환이 실패했을 때 호출되는 이벤트 핸들러입니다. |
| [scan_font_directories_recursively](/conversion/python-net/groupdocs.conversion/convertersettings/scan_font_directories_recursively/) | True로 설정된 경우 컨버터가 폰트 디렉터리를 재귀적으로 스캔합니다. |
| [temp_folder](/conversion/python-net/groupdocs.conversion/convertersettings/temp_folder/) | 변환에 사용되는 임시 폴더입니다. |

### 예제

```python
from groupdocs.conversion import Converter, ConverterSettings
from groupdocs.conversion.logging import ConsoleLogger
from groupdocs.conversion.options.convert import PdfConvertOptions

settings = ConverterSettings()
settings.logger = ConsoleLogger()

with Converter("input.docx", settings) as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### 또 보기
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
