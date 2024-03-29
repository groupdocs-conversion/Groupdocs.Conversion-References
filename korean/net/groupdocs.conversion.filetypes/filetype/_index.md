---
title: FileType
second_title: .NET API 참조용 GroupDocs.Conversion
description: 파일 유형 기본 class
type: docs
weight: 930
url: /ko/net/groupdocs.conversion.filetypes/filetype/
---
## FileType class

파일 유형 기본 class

```csharp
public class FileType : Enumeration
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [FileType](filetype)() | 직렬화 생성자 |

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
| static [FromExtension](../../groupdocs.conversion.filetypes/filetype/fromextension)(string) | 제공된 fileExtension 에 대한 FileType을 가져옵니다. |
| static [FromFilename](../../groupdocs.conversion.filetypes/filetype/fromfilename)(string) | 지정된 fileName 에 대한 FileType을 반환합니다. |
| static [FromStream](../../groupdocs.conversion.filetypes/filetype/fromstream)(Stream) | 제공된 문서 stream 에 대한 FileType을 반환합니다. |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 현재 개체를 다른 개체와 비교합니다. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals#equals)(Enumeration) | 두 개체 인스턴스가 같은지 여부를 결정합니다. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 두 개체 인스턴스가 같은지 여부를 결정합니다. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | 기본 해시 함수 역할을 합니다. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | 문자열 표현 |
| static [GetAll&lt;T&gt;](../../groupdocs.conversion.filetypes/filetype/getall)() | 모든 열거형 값을 반환합니다. |
| [implicit operator](../../groupdocs.conversion.filetypes/filetype/op_implicit) | string 로의 암시적 변환 |

## 필드

| 이름 | 설명 |
| --- | --- |
| static readonly [Unknown](../../groupdocs.conversion.filetypes/filetype/unknown) | 알 수 없는 파일 형식 |

### 또한보십시오

* class [Enumeration](../../groupdocs.conversion.contracts/enumeration)
* 네임스페이스 [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* 집회 [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
