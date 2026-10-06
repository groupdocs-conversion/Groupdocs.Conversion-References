---
title: "IConversionHandlerCompleted 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "OnConversionFailed가 설정된 후의 유창한 인터페이스를 나타내며, OnConversionCompleted를 설정하거나 Convert/Compress로 진행할 수 있습니다."
type: docs
url: /ko/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/
is_root: false
weight: 230
---


## IConversionHandlerCompleted class

`OnConversionFailed`가 설정된 후 유창한 인터페이스를 나타내며, `OnConversionCompleted`를 설정하거나 `Convert`/`Compress`로 진행할 수 있습니다.

IConversionHandlerCompleted 유형은 다음 멤버를 노출합니다:

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/compress/#options) | 변환 결과를 압축하고 `Convert`로 진행하는 연속 작업을 반환합니다. |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/convert/) | 변환 체인을 실행합니다. |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/on_conversion_completed/#on_completed) | 문서 변환이 성공적으로 완료될 때 호출되는 콜백을 등록합니다. |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/on_conversion_failed/#on_failed) | 문서 변환이 실패했을 때 호출될 콜백을 등록합니다. 다시 호출하면 이전에 설정된 핸들러가 교체됩니다. |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/on_conversion_failed_action/) |  |

### 또 보기
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
