---
title: DiagramFileType
second_title: .NET API 참조용 GroupDocs.Conversion
description: 다이어그램 문서를 정의합니다. 다음 유형을 포함합니다. Vdw./diagramfiletype/vdw  Vdx./diagramfiletype/vdx  Vsd./diagramfiletype/vsd  Vsdm./diagramfiletype/vsdm  Vsdx./diagramfiletype/vsdx  Vss./diagramfiletype/vss  Vssm./diagramfiletype/vssm  Vssx./diagramfiletype/vssx  Vst./diagramfiletype/vst  Vstm./diagramfiletype/vstm  Vstx./diagramfiletype/vstx  Vsx./diagramfiletype/vsx  Vtx./diagramfiletype/vtx .
type: docs
weight: 900
url: /ko/net/groupdocs.conversion.filetypes/diagramfiletype/
---
## DiagramFileType class

다이어그램 문서를 정의합니다. 다음 유형을 포함합니다. [`Vdw`](./vdw) , [`Vdx`](./vdx) , [`Vsd`](./vsd) , [`Vsdm`](./vsdm) , [`Vsdx`](./vsdx) , [`Vss`](./vss) , [`Vssm`](./vssm) , [`Vssx`](./vssx) , [`Vst`](./vst) , [`Vstm`](./vstm) , [`Vstx`](./vstx) , [`Vsx`](./vsx) , [`Vtx`](./vtx) .

```csharp
public sealed class DiagramFileType : FileType
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [DiagramFileType](diagramfiletype)() | 직렬화 생성자 |

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
| static readonly [Vdw](../../groupdocs.conversion.filetypes/diagramfiletype/vdw) | VDW는 웹 드로잉을 렌더링하는 데 필요한 스트림과 저장소를 지정하는 Visio Graphics Service 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/web/vdw) . |
| static readonly [Vdx](../../groupdocs.conversion.filetypes/diagramfiletype/vdx) | Microsoft Visio에서 생성되었지만 XML 형식으로 저장된 모든 그림 또는 차트는 .VDX 확장자를 갖습니다. Visio 드로잉 XML 파일은 Microsoft에서 개발한 Visio 소프트웨어에서 생성됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/vdx) . |
| static readonly [Vsd](../../groupdocs.conversion.filetypes/diagramfiletype/vsd) | VSD 파일은 다양한 그래픽 객체와 이들 사이의 상호 연결을 나타내기 위해 Microsoft Visio 응용 프로그램으로 만든 도면입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/vsd) . |
| static readonly [Vsdm](../../groupdocs.conversion.filetypes/diagramfiletype/vsdm) | 확장자가 VSDM인 파일은 매크로를 지원하는 Microsoft Visio 응용 프로그램으로 만든 도면 파일입니다. VSDM 파일은 VSDX와 유사한 OPC/XML 도면이지만 파일을 열 때 매크로를 실행할 수 있는 기능도 제공합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/vsdm) . |
| static readonly [Vsdx](../../groupdocs.conversion.filetypes/diagramfiletype/vsdx) | 확장자가 .VSDX인 파일은 Microsoft Office 2013부터 도입된 Microsoft Visio 파일 형식을 나타냅니다. 이전 버전의 Microsoft Visio에서 지원하는 이진 파일 형식인 .VSD를 대체하기 위해 개발되었습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/vsdx) . |
| static readonly [Vss](../../groupdocs.conversion.filetypes/diagramfiletype/vss) | VSS는 Microsoft Visio 2007 및 이전 버전에서 만든 스텐실 파일입니다. 스텐실 파일은 .VSD Visio 드로잉에 포함될 수 있는 드로잉 개체를 제공합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/vss) . |
| static readonly [Vssm](../../groupdocs.conversion.filetypes/diagramfiletype/vssm) | 확장자가 .VSSM인 파일은 매크로 지원을 제공하는 Microsoft Visio Stencil 파일입니다. VSSM 파일을 열면 매크로를 실행하여 다이어그램에서 모양의 원하는 서식 및 배치를 얻을 수 있습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/vssm) . |
| static readonly [Vssx](../../groupdocs.conversion.filetypes/diagramfiletype/vssx) | 확장자가 .VSSX인 파일은 Microsoft Visio 2013 이상에서 만든 도면 스텐실입니다. VSSX 파일 형식은 Visio 2013 이상에서 열 수 있습니다. Visio 파일은 셰이프 컬렉션, 커넥터, 순서도, 네트워크 레이아웃, UML 다이어그램, 와 같은 다양한 드로잉 요소를 표현하는 것으로 알려져 있습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/vssx) . |
| static readonly [Vst](../../groupdocs.conversion.filetypes/diagramfiletype/vst) | VST 확장자가 있는 파일은 Microsoft Visio로 만든 벡터 이미지 파일이며 추가 파일을 만들기 위한 템플릿 역할을 합니다. 이러한 템플릿 파일은 이진 파일 형식이며 새 Visio 드로잉 생성에 사용되는 기본 레이아웃 및 설정을 포함합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/vst) . |
| static readonly [Vstm](../../groupdocs.conversion.filetypes/diagramfiletype/vstm) | 확장자가 VSTM인 파일은 매크로를 지원하는 Microsoft Visio로 만든 템플릿 파일입니다. VSDX 파일과 달리 VSTM 템플릿에서 만든 파일은 VBA(Visual Basic for Applications) 코드로 개발된 매크로를 실행할 수 있습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/vstm) . |
| static readonly [Vstx](../../groupdocs.conversion.filetypes/diagramfiletype/vstx) | 확장자가 VSTX인 파일은 Microsoft Visio 2013 이상에서 만든 도면 템플릿 파일입니다. 이러한 VSTX 파일은 기본 레이아웃 및 설정과 함께 .VSDX 파일로 저장된 Visio 드로잉을 만들기 위한 시작점을 제공합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/vstx) . |
| static readonly [Vsx](../../groupdocs.conversion.filetypes/diagramfiletype/vsx) | 확장자가 .VSX인 파일은 Microsoft Visio에서 다이어그램을 만드는 데 사용되는 그림과 모양으로 구성된 스텐실을 나타냅니다. VSX 파일은 XML 파일 형식으로 저장되며 Visio 2013까지 지원되었습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/vsx) . |
| static readonly [Vtx](../../groupdocs.conversion.filetypes/diagramfiletype/vtx) | VTX 확장자를 가진 파일은 XML 파일 형식으로 디스크에 저장되는 Microsoft Visio 드로잉 템플릿입니다. 템플릿은 동일한 설정의 여러 Visio 파일을 만드는 데 사용할 수 있는 기본 설정이 포함된 파일을 제공하는 것을 목표로 합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/vtx) . |

### 또한보십시오

* class [FileType](../filetype)
* 네임스페이스 [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* 집회 [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
