---
title: "IConversionCompressResultCompletedOrConvert 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "Compress(...) 후의 연속 작업입니다."
type: docs
url: /ko/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/
is_root: false
weight: 130
---


## IConversionCompressResultCompletedOrConvert class

`Compress(...)` 이후의 연속입니다. `Convert`를 바로 진행하십시오; 상속된 [`IConversionCompressResultCompleted.OnCompressionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/on_compression_completed/)는 더 이상 사용되지 않으므로, 대신 [`IConversionSettings.WithEvents`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/)를 통해 진입 단계에서 핸들러를 등록하십시오.

IConversionCompressResultCompletedOrConvert 유형은 다음 멤버를 노출합니다:

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/convert/) | 변환 체인을 실행합니다. |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/on_compression_completed/#compressed_document_stream) | 압축된 문서 스트림을 받습니다. `Compress(CompressionConvertOptions)`가 설정된 경우에만 발생합니다. |
| [on_compression_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/on_compression_completed_action/) |  |

### 또 보기
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
