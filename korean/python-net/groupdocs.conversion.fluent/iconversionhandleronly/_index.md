---
title: "IConversionHandlerOnly 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "변환 핸들러만 설정하기 위한 유창한 인터페이스를 제공합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.fluent/iconversionhandleronly/
is_root: false
weight: 250
---


## IConversionHandlerOnly class

변환 핸들러만 설정하기 위한 유창한 인터페이스를 제공합니다.

`Convert`/`Compress`에 대해 [`IConversionHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconconversionhandlersstage/)를 상속합니다; 단계별 `OnConversion*` 오버로드는 기존 반환 타입과 이전 호환성을 유지하기 위해 `new` 키워드로 유지됩니다.

IConversionHandlerOnly 타입은 다음 멤버를 노출합니다:

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/compress/#options) | 변환 결과를 압축합니다. |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/convert/) | 변환 체인을 실행합니다. |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/on_conversion_completed/#on_completed) | 문서 변환이 성공적으로 완료될 때 호출되는 콜백을 등록합니다. |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/on_conversion_failed/#on_failed) | 문서 변환이 실패할 때 호출되는 콜백을 등록합니다. |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/on_conversion_failed_action/) |  |

### 또 보기
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
