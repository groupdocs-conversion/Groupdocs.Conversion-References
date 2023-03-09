---
title: PresentationFileType
second_title: .NET API 참조용 GroupDocs.Conversion
description: 슬라이드 도형 텍스트 애니메이션 비디오 오디오 및 포함 개체와 같은 프레젠테이션 데이터를 수용하기 위해 레코드 모음을 저장하는 프레젠테이션 파일 형식을 정의합니다. 다음 파일 유형을 포함합니다. Odp./presentationfiletype/odp  Otp./presentationfiletype/otp  Pot./presentationfiletype/pot  Potm./presentationfiletype/potm  Potx./presentationfiletype/potx  Pps./presentationfiletype/pps  Ppsm./presentationfiletype/ppsm  Ppsx./presentationfiletype/ppsx  Ppt./presentationfiletype/ppt  Pptm./presentationfiletype/pptm  Pptx./presentationfiletype/pptx . 프레젠테이션 형식에 대해 자세히 알아보기여기https//wiki.fileformat.com/presentation .
type: docs
weight: 1020
url: /ko/net/groupdocs.conversion.filetypes/presentationfiletype/
---
## PresentationFileType class

슬라이드, 도형, 텍스트, 애니메이션, 비디오, 오디오 및 포함 개체와 같은 프레젠테이션 데이터를 수용하기 위해 레코드 모음을 저장하는 프레젠테이션 파일 형식을 정의합니다. 다음 파일 유형을 포함합니다. [`Odp`](./odp) , [`Otp`](./otp) , [`Pot`](./pot) , [`Potm`](./potm) , [`Potx`](./potx) , [`Pps`](./pps) , [`Ppsm`](./ppsm) , [`Ppsx`](./ppsx) , [`Ppt`](./ppt) , [`Pptm`](./pptm) , [`Pptx`](./pptx) . 프레젠테이션 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation) .

```csharp
public sealed class PresentationFileType : FileType
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PresentationFileType](presentationfiletype)() | 직렬화 생성자 |

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
| static readonly [Fodp](../../groupdocs.conversion.filetypes/presentationfiletype/fodp) | FODP 확장자를 가진 파일은 OpenDocument 플랫 XML 프리젠테이션을 나타냅니다. OpenDocument 형식으로 저장되었지만 표준 .ODP 파일에서 사용하는 .ZIP 컨테이너 대신 플랫 XML 형식을 사용하여 저장된 프레젠테이션 파일 |
| static readonly [Odp](../../groupdocs.conversion.filetypes/presentationfiletype/odp) | ODP 확장자를 가진 파일은 OASISOpen 표준에서 OpenOffice.org에서 사용하는 프레젠테이션 파일 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [Otp](../../groupdocs.conversion.filetypes/presentationfiletype/otp) | 확장자가 .OTP인 파일은 응용 프로그램에서 OASIS OpenDocument 표준 형식으로 만든 프레젠테이션 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [Pot](../../groupdocs.conversion.filetypes/presentationfiletype/pot) | 확장자가 .POT인 파일은 PowerPoint 97-2003 버전에서 만든 Microsoft PowerPoint 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [Potm](../../groupdocs.conversion.filetypes/presentationfiletype/potm) | 확장자가 POTM인 파일은 매크로를 지원하는 Microsoft PowerPoint 템플릿 파일입니다. POTM 파일은 PowerPoint 2007 이상에서 생성되며 추가 프레젠테이션 파일을 생성하는 데 사용할 수 있는 기본 설정을 포함합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [Potx](../../groupdocs.conversion.filetypes/presentationfiletype/potx) | 확장자가 .POTX인 파일은 Microsoft PowerPoint 2007 이상에서 만든 Microsoft PowerPoint 템플릿 프레젠테이션을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [Pps](../../groupdocs.conversion.filetypes/presentationfiletype/pps) | PPS, PowerPoint 슬라이드 쇼, 파일은 슬라이드 쇼 목적으로 Microsoft PowerPoint를 사용하여 생성됩니다. PPS 파일 읽기 및 생성은 Microsoft PowerPoint 97-2003에서 지원됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [Ppsm](../../groupdocs.conversion.filetypes/presentationfiletype/ppsm) | 확장자가 PPSM인 파일은 Microsoft PowerPoint 2007 이상에서 만든 매크로 사용 슬라이드 쇼 파일 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [Ppsx](../../groupdocs.conversion.filetypes/presentationfiletype/ppsx) | PPSX, Power Point Slide Show, 파일은 슬라이드 쇼 목적으로 Microsoft PowerPoint 2007 이상을 사용하여 생성됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [Ppt](../../groupdocs.conversion.filetypes/presentationfiletype/ppt) | PPT 확장자를 가진 파일은 슬라이드 쇼로 보여주기 위한 슬라이드 모음으로 구성된 파워포인트 파일을 나타냅니다. Microsoft PowerPoint 97-2003에서 사용하는 이진 파일 형식을 지정합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [Pptm](../../groupdocs.conversion.filetypes/presentationfiletype/pptm) | 확장자가 PPTM인 파일은 Microsoft PowerPoint 2007 이상 버전에서 생성된 매크로 사용 프레젠테이션 파일입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [Pptx](../../groupdocs.conversion.filetypes/presentationfiletype/pptx) | 확장자가 PPTX인 파일은 널리 사용되는 Microsoft PowerPoint 응용 프로그램으로 만든 프레젠테이션 파일입니다. 프레젠테이션 파일 형식 PPT의 이전 버전인 바이너리와 달리 PPTX 형식은 Microsoft PowerPoint 개방형 XML 프레젠테이션 파일 형식을 기반으로 합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/pptx) . |

### 또한보십시오

* class [FileType](../filetype)
* 네임스페이스 [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* 집회 [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
