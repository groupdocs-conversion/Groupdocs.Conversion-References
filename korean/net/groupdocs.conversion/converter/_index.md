---
title: Converter
second_title: .NET API 참조용 GroupDocs.Conversion
description: 문서 변환 프로세스를 제어하는 메인 클래스를 나타냅니다.
type: docs
weight: 730
url: /ko/net/groupdocs.conversion/converter/
---
## Converter class

문서 변환 프로세스를 제어하는 메인 클래스를 나타냅니다.

```csharp
public sealed class Converter : IConversionSettingsOrConversionFrom, IDisposable
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Converter](converter#constructor)() | 의 새 인스턴스를 초기화합니다.[`Converter`](../converter) 유창한 변환 설정을 위한 클래스. |
| [Converter](converter#constructor_1)(Func&lt;Stream&gt;) | 의 새 인스턴스를 초기화합니다.[`Converter`](../converter) 클래스. |
| [Converter](converter#constructor_7)(string) | 의 새 인스턴스를 초기화합니다.[`Converter`](../converter) 클래스. |
| [Converter](converter#constructor_2)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) | 의 새 인스턴스를 초기화합니다.[`Converter`](../converter) 클래스. |
| [Converter](converter#constructor_5)(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;) | 의 새 인스턴스를 초기화합니다.[`Converter`](../converter) 클래스. |
| [Converter](converter#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) | 의 새 인스턴스를 초기화합니다.[`Converter`](../converter) 클래스. |
| [Converter](converter#constructor_8)(string, Func&lt;ConverterSettings&gt;) | 의 새 인스턴스를 초기화합니다.[`Converter`](../converter) 클래스. |
| [Converter](converter#constructor_11)(string, Func&lt;FileType, LoadOptions&gt;) | 의 새 인스턴스를 초기화합니다.[`Converter`](../converter) 클래스. |
| [Converter](converter#constructor_9)(string, Func&lt;LoadOptions&gt;) | 의 새 인스턴스를 초기화합니다.[`Converter`](../converter) 클래스. |
| [Converter](converter#constructor_6)(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | 의 새 인스턴스를 초기화합니다.[`Converter`](../converter) 클래스. |
| [Converter](converter#constructor_4)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | 의 새 인스턴스를 초기화합니다.[`Converter`](../converter) 클래스. |
| [Converter](converter#constructor_12)(string, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | 의 새 인스턴스를 초기화합니다.[`Converter`](../converter) 클래스. |
| [Converter](converter#constructor_10)(string, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | 의 새 인스턴스를 초기화합니다.[`Converter`](../converter) 클래스. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [Convert](../../groupdocs.conversion/converter/convert#convert_4)(Func&lt;FileType, Stream&gt;, ConvertOptions) | 소스 문서를 변환합니다. 변환된 문서 전체를 저장합니다. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_7)(Func&lt;FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | 소스 문서를 변환합니다. 변환된 문서 전체를 저장합니다. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_12)(Func&lt;int, FileType, Stream&gt;, ConvertOptions) | 소스 문서를 변환합니다. 변환된 문서를 페이지별로 저장합니다. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_15)(Func&lt;int, FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | 소스 문서를 변환합니다. 변환된 문서를 페이지별로 저장합니다. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_8)(Func&lt;int, Stream&gt;, ConvertOptions) | 소스 문서를 변환합니다. 변환된 문서를 페이지별로 저장합니다. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_11)(Func&lt;int, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | 소스 문서를 변환합니다. 변환된 문서를 페이지별로 저장합니다. |
| [Convert](../../groupdocs.conversion/converter/convert#convert)(Func&lt;Stream&gt;, ConvertOptions) | 소스 문서를 변환합니다. 변환된 문서 전체를 저장합니다. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_3)(Func&lt;Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | 소스 문서를 변환합니다. 변환된 문서 전체를 저장합니다. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_16)(string, ConvertOptions) | 소스 문서를 변환합니다. 변환된 문서 전체를 저장합니다. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_5)(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) | 소스 문서를 변환합니다. 변환된 문서 전체를 저장합니다. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_6)(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | 소스 문서를 변환합니다. 변환된 문서 전체를 저장합니다. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_13)(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) | 소스 문서를 변환합니다. 변환된 문서를 페이지별로 저장합니다. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_14)(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | 소스 문서를 변환합니다. 변환된 문서를 페이지별로 저장합니다. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_9)(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) | 소스 문서를 변환합니다. 변환된 문서를 페이지별로 저장합니다. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_10)(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | 소스 문서를 변환합니다. 변환된 문서를 페이지별로 저장합니다. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_1)(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) | 소스 문서를 변환합니다. 변환된 문서 전체를 저장합니다. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_2)(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | 소스 문서를 변환합니다. 변환된 문서 전체를 저장합니다. |
| [Dispose](../../groupdocs.conversion/converter/dispose)() | 리소스를 해제합니다. |
| [GetDocumentInfo](../../groupdocs.conversion/converter/getdocumentinfo)() | 원본 문서 정보 가져오기 - 페이지 수 및 파일 형식에 특정한 기타 문서 속성. |
| [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)() | 소스 문서에 대한 가능한 변환을 가져옵니다. |
| [Load](../../groupdocs.conversion/converter/load#load_1)(Func&lt;Stream&gt;) | 소스 문서 stream 구성 |
| [Load](../../groupdocs.conversion/converter/load#load)(Func&lt;Stream[]&gt;) | 소스 문서 집합 구성 streams |
| [Load](../../groupdocs.conversion/converter/load#load_2)(string) | conversion 에 대한 소스 문서 구성 |
| [Load](../../groupdocs.conversion/converter/load#load_3)(string[]) | 소스 문서 세트 구성 |
| [WithSettings](../../groupdocs.conversion/converter/withsettings)(Func&lt;ConverterSettings&gt;) | 변환 설정 구성 |
| static [GetAllPossibleConversions](../../groupdocs.conversion/converter/getallpossibleconversions)() | 지원되는 모든 전환 가져오기 |
| static [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)(string) | 제공된 문서 extension 에 대해 지원되는 변환 가져오기 |

### 또한보십시오

* interface [IConversionSettingsOrConversionFrom](../../groupdocs.conversion.fluent/iconversionsettingsorconversionfrom)
* 네임스페이스 [GroupDocs.Conversion](../../groupdocs.conversion)
* 집회 [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
