---
title: "IConversionHandlersStage 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "변환 핸들러 단계가 평탄화된 것을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/
is_root: false
weight: 270
---


## IConversionHandlersStage class

변환 핸들러 단계가 평탄화된 것을 나타냅니다.

`Convert` / `Compress`로 진행하기 전에 `OnConversionCompleted` 또는 `OnConversionFailed`를 순서와 횟수에 관계없이 설정할 수 있습니다. 이벤트는 이 단계가 아니라 [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/)를 통해 초기 단계에서 등록해야 합니다.

IConversionHandlersStage 유형은 다음 멤버를 노출합니다:

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress/#options) | 변환 결과를 압축합니다. |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/convert/) | 변환 체인을 실행합니다. |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed/#on_completed) | 문서 변환이 성공적으로 완료될 때 호출되는 콜백을 등록하며, 재호출 시 이전에 설정된 핸들러를 교체합니다. |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed/#on_failed) | 문서 변환이 실패할 때 호출되는 콜백을 등록합니다. |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed_action/) |  |

### 또 보기
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
