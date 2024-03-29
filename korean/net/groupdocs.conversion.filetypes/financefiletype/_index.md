---
title: FinanceFileType
second_title: .NET API 참조용 GroupDocs.Conversion
description: 재무 문서를 정의합니다. 다음 유형을 포함합니다. Xbrl./financefiletype/xbrlIXbrl./financefiletype/ixbrlOfx./financefiletype/ofx 재무 형식에 대해 자세히 알아보기여기https//docs.fileformat.com/finance/ .
type: docs
weight: 940
url: /ko/net/groupdocs.conversion.filetypes/financefiletype/
---
## FinanceFileType class

재무 문서를 정의합니다. 다음 유형을 포함합니다. [`Xbrl`](./xbrl)[`IXbrl`](./ixbrl)[`Ofx`](./ofx) 재무 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/finance/) .

```csharp
public sealed class FinanceFileType : FileType
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [FinanceFileType](financefiletype)() | 직렬화 생성자 |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | 파일 형식 description |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | 파일 확장자 |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | 파일 family |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | 파일 형식 |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 현재 개체를 다른 개체와 비교합니다. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | 두 개체 인스턴스가 같은지 여부를 결정합니다. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 두 개체 인스턴스가 같은지 여부를 결정합니다. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | 기본 해시 함수 역할을 합니다. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | 문자열 표현 |

## 필드

| 이름 | 설명 |
| --- | --- |
| static readonly [IXbrl](../../groupdocs.conversion.filetypes/financefiletype/ixbrl) | iXBRL 내에서 XBRL의 내용은 XML 태그를 사용하는 xHTML 파일 형식으로 래핑됩니다. XBRL과 마찬가지로 iXBRL 파일의 루트 요소입니다. XHTML 형식은 다양한 문서 유형 및 모듈의 모음으로 내용을 나타냅니다. XHTML의 모든 파일은 XML 파일 형식을 기반으로 하며 XML 문서 표준을 준수합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/finance/ixbrl/) . |
| static readonly [Ofx](../../groupdocs.conversion.filetypes/financefiletype/ofx) | OFX(Open Financial Exchange)는 Microsoft의 OFC(Open Financial Connectivity) 및 Intuit의 Open Exchange 파일 형식에서 발전한 재무 정보 교환을 위한 데이터 스트림 형식입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://en.wikipedia.org/wiki/Open_Financial_Exchange) . |
| static readonly [Xbrl](../../groupdocs.conversion.filetypes/financefiletype/xbrl) | XBRL은 전 세계적으로 널리 사용되는 디지털 비즈니스 보고를 위한 개방형 국제 표준입니다. 보고서 정렬 및 분석을 위한 데이터를 공식화하기 위해 비즈니스 데이터의 각 항목을 설명하기 위해 태그로 알려진 XBRL 요소를 사용하는 XML 기반 언어입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/finance/xbrl/) . |

### 또한보십시오

* class [FileType](../filetype)
* 네임스페이스 [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* 집회 [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
