---
title: "IConversionByPageHandlerOnly 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "페이지별 변환 핸들러만 설정하기 위한 유창한 인터페이스를 제공합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/
is_root: false
weight: 50
---


## IConversionByPageHandlerOnly class

페이지별 변환 핸들러만 설정하기 위한 유창한 인터페이스를 제공합니다.

`Convert`/`Compress`를 위해 [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/)를 상속합니다; 단계별 `OnConversion*` 오버로드는 `new` 키워드를 사용하여 이전 호환성을 유지합니다.

IConversionByPageHandlerOnly 유형은 다음 멤버를 노출합니다:

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress/#options) | 변환 결과를 압축합니다; 구식 유창 체인 메서드 대신 [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/)를 통해 진입 단계에서 압축 스트림 핸들러를 등록합니다(`OnCompressionCompleted` 설정). |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/convert/) | 변환 체인을 실행합니다. |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed/#on_completed) | 페이지 변환이 성공적으로 완료될 때 호출되는 콜백을 등록합니다. |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_failed/#on_failed) | 페이지 변환이 실패할 때 호출되는 콜백을 등록합니다. |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_failed_action/) |  |

### 또 보기
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
