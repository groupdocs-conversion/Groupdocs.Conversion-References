---
title: "ConversionEvents 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "변환 수명 주기 이벤트 핸들러를 집계합니다."
type: docs
url: /ko/python-net/groupdocs.conversion/conversionevents/
is_root: false
weight: 20
---


## ConversionEvents class

변환 수명 주기 이벤트 핸들러를 집계합니다.

인스턴스를 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 생성자의 `events` 매개변수에 전달하거나 fluent `WithEvents` 메서드에 전달하십시오.

개별 [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/) 핸들러 속성보다 이것을 선호하십시오. 해당 속성은 더 이상 사용되지 않습니다.

ConversionEvents 타입은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/conversionevents/__init__/) |  |

### 속성들
| 속성 | 설명 |
| :- | :- |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion/conversionevents/on_compression_completed/) | 변환 출력 압축이 완료될 때 발생하는 이벤트입니다. 압축 파이프라인(LIB_ZIP)이 포함된 빌드에서만 호출됩니다. |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) | 변환 실행이 완료될 때 한 번 발생하는 이벤트이며, 성공 여부와 관계없이 발생합니다. |
| [on_conversion_progress](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/) | 변환 진행률을 백분율(0–100)로 표시하며, 주기적으로 발생합니다. |
| [on_conversion_started](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/) | 변환 실행 시작 시, 문서가 처리되기 전에 한 번 발생하는 이벤트입니다. |
| [on_document_converted](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_converted/) | 전체 문서 변환이 성공적으로 완료될 때마다 한 번 발생하는 이벤트입니다. |
| [on_document_failed](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_failed/) | 전체 문서 변환이 실패할 때마다 한 번 발생하는 이벤트입니다. |
| [on_font_substituted](/conversion/python-net/groupdocs.conversion/conversionevents/on_font_substituted/) | 소스 문서에서 참조된 글꼴을 사용할 수 없고 대체될 때 발생하는 이벤트이며(고객 제공 [`FontSubstitute`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitute/) 규칙, 구성된 기본 글꼴, 또는 변환 파이프라인의 내부 대체에 의해). |
| [on_page_converted](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_converted/) | 페이지별 변환이 성공적으로 완료될 때마다 페이지당 한 번 발생하는 이벤트입니다. |
| [on_page_failed](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_failed/) | 페이지별 변환이 실패할 때마다 페이지당 한 번 발생하는 이벤트입니다. |

### 또 보기
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
