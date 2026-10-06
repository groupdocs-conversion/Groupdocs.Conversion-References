---
title: "groupdocs.conversion.fluent"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "groupdocs.conversion.fluent 아래의 유형들."
type: docs
url: /ko/python-net/groupdocs.conversion.fluent/
is_root: false
weight: 50
---


`groupdocs.conversion.fluent` 아래의 유형들.

### 클래스
| 클래스 | 설명 |
| :- | :- |
| [`IConversionByPageCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/) | 변환 페이지 완료를 처리합니다. |
| [`IConversionByPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/) | 변환 완료를 처리하거나 변환을 실행합니다. |
| [`IConversionByPageHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/) | 페이지 변환에 대해 `OnConversionFailed`가 설정된 후 유창한 인터페이스를 제공합니다. `OnConversionCompleted`를 설정하거나 `Convert`/`Compress`로 진행할 수 있습니다. |
| [`IConversionByPageHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/) | `OnConversionCompleted`가 페이지 변환에 설정된 후 유창한 인터페이스를 나타내며, `OnConversionFailed`를 구성하거나 `Convert`/`Compress`로 진행할 수 있습니다. |
| [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/) | 페이지별 변환 핸들러만 설정하기 위한 유창한 인터페이스를 제공합니다. |
| [`IConversionByPageHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/) | 페이지 변환 핸들러를 설정하기 위한 유창한 인터페이스를 제공합니다. |
| [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/) | 페이지별 변환 핸들러 단계가 평탄화된 것을 나타냅니다. |
| [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/) | 페이지별 변환 옵션 또는 핸들러 설정을 위한 유창한 인터페이스입니다. |
| [`IConversionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompleted/) | 변환 완료를 처리합니다. |
| [`IConversionCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/) | 변환 완료를 처리하거나 변환을 실행합니다. |
| [`IConversionCompressResult`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresult/) | 모든 변환 결과를 하나의 압축 파일로 압축합니다. |
| [`IConversionCompressResultCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/) | 압축 완료를 처리합니다. |
| [`IConversionCompressResultCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/) | `Compress(...)` 이후의 연속입니다. `Convert`를 바로 진행하십시오; 상속된 [`IConversionCompressResultCompleted.OnCompressionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/on_compression_completed/)는 더 이상 사용되지 않으므로, 대신 [`IConversionSettings.WithEvents`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/)를 통해 진입 단계에서 핸들러를 등록하십시오. |
| [`IConversionConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvert/) | 변환을 실행합니다. |
| [`IConversionConvertByPageOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertbypageoptions/) | 변환 옵션을 나타냅니다. |
| [`IConversionConvertOptionOrCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/) | 변환 옵션, 완료 처리 또는 변환 실행을 나타냅니다. |
| [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/) | 변환 옵션, 완료 처리 또는 실행을 나타냅니다. |
| [`IConversionConvertOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptions/) | 변환 옵션을 나타냅니다. |
| [`IConversionConvertOrCompress`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertorcompress/) | 압축하거나 변환합니다. |
| [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/) | 변환을 위한 소스를 설정합니다. |
| [`IConversionGetDocumentInfo`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetdocumentinfo/) | 페이지 수 및 파일 유형에 특화된 기타 속성을 포함한 소스 문서 정보를 검색합니다. |
| [`IConversionGetPossibleConversions`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetpossibleconversions/) | 소스 문서에 대한 가능한 변환을 가져옵니다. |
| [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/) | `OnConversionFailed`가 설정된 후 유창한 인터페이스를 나타내며, `OnConversionCompleted`를 설정하거나 `Convert`/`Compress`로 진행할 수 있습니다. |
| [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/) | `OnConversionCompleted`가 설정된 후 유창한 인터페이스를 제공하며, `OnConversionFailed`를 구성하거나 `Convert`/`Compress`로 진행할 수 있습니다. |
| [`IConversionHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/) | 변환 핸들러만 설정하기 위한 유창한 인터페이스를 제공합니다. |
| [`IConversionHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/) | 변환 핸들러를 설정하기 위한 유창한 인터페이스를 제공합니다. `OnConversionCompleted` 및/또는 `OnConversionFailed`를 순서에 관계없이 각각 최대 한 번씩 설정하거나 두 항목을 모두 건너뛸 수 있습니다. |
| [`IConversionHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/) | 변환 핸들러 단계가 평탄화된 것을 나타냅니다. |
| [`IConversionIsPasswordProtected`](/conversion/python-net/groupdocs.conversion.fluent/iconversionispasswordprotected/) | 소스 문서가 비밀번호로 보호되어 있는지 확인합니다. |
| [`IConversionLoadOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptions/) | 변환 로드 옵션을 나타냅니다. |
| [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/) | 로드된 문서와 함께 변환 로드 옵션 또는 작업을 나타냅니다. |
| [`IConversionOptionsOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/) | 변환 옵션만 설정하기 위한 유창한 인터페이스를 제공합니다. |
| [`IConversionOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/) | 변환 옵션 또는 변환 핸들러 설정을 나타냅니다. |
| [`IConversionSettings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/) | 입력 단계(`Load` 이전)에서 변환 설정 또는 이벤트를 설정합니다. |
| [`IConversionSettingsOrConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/) | 변환 설정 또는 변환 소스를 나타냅니다. |
| [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/) | 로드된 문서와 가능한 작업을 제공합니다. |
| [`IConversionTo`](/conversion/python-net/groupdocs.conversion.fluent/iconversionto/) | 변환된 문서가 저장되는 방식을 설정합니다. |
