---
title: TxtLoadOptions
second_title: .NET API 참조용 GroupDocs.Conversion
description: Txt 문서 로드 옵션.
type: docs
weight: 2300
url: /ko/net/groupdocs.conversion.options.load/txtloadoptions/
---
## TxtLoadOptions class

Txt 문서 로드 옵션.

```csharp
public sealed class TxtLoadOptions : LoadOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TxtLoadOptions](txtloadoptions)() | 의 새 인스턴스를 초기화합니다.[`TxtLoadOptions`](../txtloadoptions) 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [DetectNumberingWithWhitespaces](../../groupdocs.conversion.options.load/txtloadoptions/detectnumberingwithwhitespaces) { get; set; } | 일반 텍스트 문서가 변환될 때 번호가 매겨진 목록 항목을 인식하는 방법을 지정할 수 있습니다. 기본값은 true입니다. |
| [Encoding](../../groupdocs.conversion.options.load/txtloadoptions/encoding) { get; set; } | Txt 문서를 로드할 때 사용할 인코딩을 가져오거나 설정합니다. null일 수 있습니다. 기본값은 null입니다. |
| [Format](../../groupdocs.conversion.options.load/txtloadoptions/format) { get; } | 입력 문서 파일 유형. (2 properties) |
| [LeadingSpacesOptions](../../groupdocs.conversion.options.load/txtloadoptions/leadingspacesoptions) { get; set; } | 선행 공백 처리의 기본 옵션을 가져오거나 설정합니다. 기본값은[`ConvertToIndent`](../txtleadingspacesoptions/converttoindent) . |
| [TrailingSpacesOptions](../../groupdocs.conversion.options.load/txtloadoptions/trailingspacesoptions) { get; set; } | 후행 공백 처리의 기본 옵션을 가져오거나 설정합니다. 기본값은[`Trim`](../txttrailingspacesoptions/trim) . |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 두 개체 인스턴스가 같은지 여부를 결정합니다. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 두 개체 인스턴스가 같은지 여부를 결정합니다. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 기본 해시 함수 역할을 합니다. |

### 또한보십시오

* class [LoadOptions](../loadoptions)
* 네임스페이스 [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* 집회 [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->