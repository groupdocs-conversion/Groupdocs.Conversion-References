---
title: "PresentationFileType"
second_title: "GroupDocs.Conversion for .NET API 참조"
description: "프레젠테이션 데이터를 수용하기 위해 슬라이드, 도형, 텍스트, 애니메이션, 비디오, 오디오 및 포함된 객체와 같은 레코드 컬렉션을 저장하는 프레젠테이션 파일 형식을 정의합니다. 다음 파일 유형을 포함합니다 Odp./presentationfiletype/odp Otp./presentationfiletype/otp Pot./presentationfiletype/pot Potm./presentationfiletype/potm Potx./presentationfiletype/potx Pps./presentationfiletype/pps Ppsm./presentationfiletype/ppsm Ppsx./presentationfiletype/ppsx Ppt./presentationfiletype/ppt Pptm./presentationfiletype/pptm Pptx./presentationfiletype/pptx. 프레젠테이션 형식에 대해 자세히 알아보려면 여기https//wiki.fileformat.com/presentation 를 방문하십시오."
type: docs
weight: 1210
url: /ko/net/groupdocs.conversion.filetypes/presentationfiletype/
---
## PresentationFileType class

프레젠테이션 데이터를 수용하기 위해 슬라이드, 도형, 텍스트, 애니메이션, 비디오, 오디오 및 포함된 객체와 같은 레코드 컬렉션을 저장하는 프레젠테이션 파일 형식을 정의합니다. 다음 파일 유형을 포함합니다: [`Odp`](./odp), [`Otp`](./otp), [`Pot`](./pot), [`Potm`](./potm), [`Potx`](./potx), [`Pps`](./pps), [`Ppsm`](./ppsm), [`Ppsx`](./ppsx), [`Ppt`](./ppt), [`Pptm`](./pptm), [`Pptx`](./pptx). 프레젠테이션 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation)를 클릭하십시오.

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
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | 파일 유형 설명 |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | 파일 확장자 |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | 파일 패밀리 |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | 파일 형식 |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 현재 객체를 다른 객체와 비교합니다. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | `[`Equals`](../../groupdocs.conversion.contracts/enumeration/equals)`를 구현합니다. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 두 객체 인스턴스가 같은지 여부를 결정합니다. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | 기본 해시 함수로 사용됩니다. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | 문자열 표현 |

## 필드

| 이름 | 설명 |
| --- | --- |
| static readonly [Fodp](../../groupdocs.conversion.filetypes/presentationfiletype/fodp) | FODP 확장자를 가진 파일은 OpenDocument Flat XML 프레젠테이션을 나타냅니다. 프레젠테이션 파일은 OpenDocument 형식으로 저장되지만, 표준 .ODP 파일에서 사용되는 .ZIP 컨테이너 대신 플랫 XML 형식으로 저장됩니다. |
| static readonly [Odp](../../groupdocs.conversion.filetypes/presentationfiletype/odp) | ODP 확장자를 가진 파일은 OASISOpen 표준에서 OpenOffice.org에서 사용되는 프레젠테이션 파일 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/odp)를 클릭하십시오. |
| static readonly [Otp](../../groupdocs.conversion.filetypes/presentationfiletype/otp) | .OTP 확장자를 가진 파일은 OASIS OpenDocument 표준 형식으로 애플리케이션에서 생성된 프레젠테이션 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/otp)를 클릭하십시오. |
| static readonly [Pot](../../groupdocs.conversion.filetypes/presentationfiletype/pot) | .POT 확장자를 가진 파일은 PowerPoint 97-2003 버전에서 생성된 Microsoft PowerPoint 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/pot)를 클릭하십시오. |
| static readonly [Potm](../../groupdocs.conversion.filetypes/presentationfiletype/potm) | POTM 확장자를 가진 파일은 매크로를 지원하는 Microsoft PowerPoint 템플릿 파일입니다. POTM 파일은 PowerPoint 2007 이상에서 생성되며, 추가 프레젠테이션 파일을 만들 때 사용할 수 있는 기본 설정을 포함합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/potm)를 클릭하십시오. |
| static readonly [Potx](../../groupdocs.conversion.filetypes/presentationfiletype/potx) | .POTX 확장자를 가진 파일은 Microsoft PowerPoint 2007 이상에서 생성된 Microsoft PowerPoint 템플릿 프레젠테이션을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/potx)를 클릭하십시오. |
| static readonly [Pps](../../groupdocs.conversion.filetypes/presentationfiletype/pps) | PPS, PowerPoint 슬라이드 쇼 파일은 슬라이드 쇼 용도로 Microsoft PowerPoint를 사용하여 생성됩니다. PPS 파일의 읽기 및 생성은 Microsoft PowerPoint 97-2003에서 지원됩니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/pps)를 클릭하십시오. |
| static readonly [Ppsm](../../groupdocs.conversion.filetypes/presentationfiletype/ppsm) | PPSM 확장자를 가진 파일은 Microsoft PowerPoint 2007 이상에서 생성된 매크로 지원 슬라이드 쇼 파일 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/ppsm)를 클릭하십시오. |
| static readonly [Ppsx](../../groupdocs.conversion.filetypes/presentationfiletype/ppsx) | PPSX, PowerPoint 슬라이드 쇼 파일은 슬라이드 쇼 용도로 Microsoft PowerPoint 2007 이상을 사용하여 생성됩니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/ppsx)를 클릭하십시오. |
| static readonly [Ppt](../../groupdocs.conversion.filetypes/presentationfiletype/ppt) | PPT 확장자를 가진 파일은 슬라이드 쇼로 표시되는 슬라이드 컬렉션으로 구성된 PowerPoint 파일을 나타냅니다. 이는 Microsoft PowerPoint 97-2003에서 사용되는 바이너리 파일 형식을 지정합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/ppt)를 클릭하십시오. |
| static readonly [Pptm](../../groupdocs.conversion.filetypes/presentationfiletype/pptm) | PPTM 확장자를 가진 파일은 Microsoft PowerPoint 2007 이상 버전에서 생성된 매크로 지원 프레젠테이션 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/pptm)를 클릭하십시오. |
| static readonly [Pptx](../../groupdocs.conversion.filetypes/presentationfiletype/pptx) | PPTX 확장자를 가진 파일은 널리 사용되는 Microsoft PowerPoint 애플리케이션으로 생성된 프레젠테이션 파일입니다. 이전 버전인 바이너리 PPT와 달리, PPTX 형식은 Microsoft PowerPoint Open XML 프레젠테이션 파일 형식을 기반으로 합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/pptx)를 클릭하십시오. |

### 또 보기

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
