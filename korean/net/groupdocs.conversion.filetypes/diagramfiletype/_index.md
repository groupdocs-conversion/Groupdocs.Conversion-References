---
title: "DiagramFileType"
second_title: "GroupDocs.Conversion for .NET API 참조"
description: "Diagram 문서를 정의합니다. 다음 유형을 포함합니다 Drawio./diagramfiletype/drawio Mmd./diagramfiletype/mmd Vdw./diagramfiletype/vdw Vdx./diagramfiletype/vdx Vsd./diagramfiletype/vsd Vsdm./diagramfiletype/vsdm Vsdx./diagramfiletype/vsdx Vss./diagramfiletype/vss Vssm./diagramfiletype/vssm Vssx./diagramfiletype/vssx Vst./diagramfiletype/vst Vstm./diagramfiletype/vstm Vstx./diagramfiletype/vstx Vsx./diagramfiletype/vsx Vtx./diagramfiletype/vtx."
type: docs
weight: 1100
url: /ko/net/groupdocs.conversion.filetypes/diagramfiletype/
---
## DiagramFileType class

Diagram 문서를 정의합니다. 다음 유형을 포함합니다: [`Drawio`](./drawio), [`Mmd`](./mmd), [`Vdw`](./vdw), [`Vdx`](./vdx), [`Vsd`](./vsd), [`Vsdm`](./vsdm), [`Vsdx`](./vsdx), [`Vss`](./vss), [`Vssm`](./vssm), [`Vssx`](./vssx), [`Vst`](./vst), [`Vstm`](./vstm), [`Vstx`](./vstx), [`Vsx`](./vsx), [`Vtx`](./vtx).

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
| static readonly [Drawio](../../groupdocs.conversion.filetypes/diagramfiletype/drawio) | DRAWIO 확장자를 가진 파일은 diagrams.net(이전 draw.io)으로 만든 다이어그램입니다. mxfile 루트 요소가 있는 XML 파일 형식으로 저장되며 텍스트, 이미지, 레이아웃, 도형 및 위치 지정과 같은 다이어그램 요소의 내용과 서식을 포함합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/web/drawio)를 클릭하세요. |
| static readonly [Mmd](../../groupdocs.conversion.filetypes/diagramfiletype/mmd) | MMD 확장자를 가진 파일은 Mermaid 마크업 언어로 작성된 다이어그램입니다. 다이어그램 선언(예: flowchart 또는 sequenceDiagram)으로 시작하고 노드와 연결 정의가 이어지는 일반 텍스트 문서로 저장됩니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://mermaid.js.org/intro/)를 클릭하세요. |
| static readonly [Vdw](../../groupdocs.conversion.filetypes/diagramfiletype/vdw) | VDW는 웹 드로잉을 렌더링하는 데 필요한 스트림 및 스토리지를 지정하는 Visio Graphics Service 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/web/vdw)를 클릭하세요. |
| static readonly [Vdx](../../groupdocs.conversion.filetypes/diagramfiletype/vdx) | Microsoft Visio에서 만든 모든 도면이나 차트가 XML 형식으로 저장될 경우 .VDX 확장자를 가집니다. Visio 소프트웨어(마이크로소프트에서 개발)에서 Visio 드로잉 XML 파일이 생성됩니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/vdx)를 클릭하세요. |
| static readonly [Vsd](../../groupdocs.conversion.filetypes/diagramfiletype/vsd) | VSD 파일은 Microsoft Visio 애플리케이션으로 만든 드로잉으로, 다양한 그래픽 객체와 그들 간의 상호 연결을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/vsd)를 클릭하세요. |
| static readonly [Vsdm](../../groupdocs.conversion.filetypes/diagramfiletype/vsdm) | VSDM 확장자를 가진 파일은 매크로를 지원하는 Microsoft Visio 애플리케이션으로 만든 드로잉 파일입니다. VSDM 파일은 VSDX와 유사한 OPC/XML 드로잉이며, 파일을 열 때 매크로를 실행할 수 있는 기능을 제공합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/vsdm)를 클릭하세요. |
| static readonly [Vsdx](../../groupdocs.conversion.filetypes/diagramfiletype/vsdx) | .VSDX 확장자를 가진 파일은 Microsoft Office 2013 이후에 도입된 Microsoft Visio 파일 형식을 나타냅니다. 이는 이전 버전 Microsoft Visio에서 지원하던 바이너리 파일 형식 .VSD를 대체하기 위해 개발되었습니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/vsdx)를 클릭하세요. |
| static readonly [Vss](../../groupdocs.conversion.filetypes/diagramfiletype/vss) | VSS는 Microsoft Visio 2007 및 이전 버전으로 만든 스텐실 파일입니다. 스텐실 파일은 .VSD Visio 드로잉에 포함될 수 있는 그리기 객체를 제공합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/vss)를 클릭하세요. |
| static readonly [Vssm](../../groupdocs.conversion.filetypes/diagramfiletype/vssm) | .VSSM 확장자를 가진 파일은 매크로를 지원하는 Microsoft Visio 스텐실 파일입니다. VSSM 파일을 열면 매크로를 실행하여 다이어그램에서 원하는 형태와 배치를 구현할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/vssm)를 클릭하세요. |
| static readonly [Vssx](../../groupdocs.conversion.filetypes/diagramfiletype/vssx) | .VSSX 확장자를 가진 파일은 Microsoft Visio 2013 이상으로 만든 드로잉 스텐실입니다. VSSX 파일 형식은 Visio 2013 이상에서 열 수 있습니다. Visio 파일은 도형, 커넥터, 플로우차트, 네트워크 레이아웃, UML 다이어그램 등 다양한 드로잉 요소를 표현하는 데 사용됩니다. 자세한 내용은 [여기](https://wiki.fileformat.com/image/vssx)에서 확인하세요. |
| static readonly [Vst](../../groupdocs.conversion.filetypes/diagramfiletype/vst) | VST 확장자를 가진 파일은 Microsoft Visio로 만든 벡터 이미지 파일이며, 추가 파일을 만들기 위한 템플릿 역할을 합니다. 이러한 템플릿 파일은 바이너리 파일 형식이며, 새로운 Visio 드로잉을 만들 때 사용되는 기본 레이아웃 및 설정을 포함합니다. 자세한 내용은 [여기](https://wiki.fileformat.com/image/vst)에서 확인하세요. |
| static readonly [Vstm](../../groupdocs.conversion.filetypes/diagramfiletype/vstm) | VSTM 확장자를 가진 파일은 매크로를 지원하는 Microsoft Visio로 만든 템플릿 파일입니다. VSDX 파일과 달리 VSTM 템플릿에서 만든 파일은 Visual Basic for Applications (VBA) 코드로 개발된 매크로를 실행할 수 있습니다. 자세한 내용은 [여기](https://wiki.fileformat.com/image/vstm)에서 확인하세요. |
| static readonly [Vstx](../../groupdocs.conversion.filetypes/diagramfiletype/vstx) | VSTX 확장자를 가진 파일은 Microsoft Visio 2013 이상으로 만든 드로잉 템플릿 파일입니다. 이러한 VSTX 파일은 기본 레이아웃 및 설정이 포함된 .VSDX 파일로 저장되는 Visio 드로잉을 만들기 위한 시작점을 제공합니다. 자세한 내용은 [여기](https://wiki.fileformat.com/image/vstx)에서 확인하세요. |
| static readonly [Vsx](../../groupdocs.conversion.filetypes/diagramfiletype/vsx) | .VSX 확장자를 가진 파일은 Microsoft Visio에서 다이어그램을 만들 때 사용되는 드로잉 및 도형으로 구성된 스텐실을 의미합니다. VSX 파일은 XML 파일 형식으로 저장되며 Visio 2013까지 지원되었습니다. 자세한 내용은 [여기](https://wiki.fileformat.com/image/vsx)에서 확인하세요. |
| static readonly [Vtx](../../groupdocs.conversion.filetypes/diagramfiletype/vtx) | VTX 확장자를 가진 파일은 XML 파일 형식으로 디스크에 저장되는 Microsoft Visio 드로잉 템플릿입니다. 이 템플릿은 동일한 설정을 가진 여러 Visio 파일을 만들 때 사용할 수 있는 기본 설정을 제공하도록 설계되었습니다. 자세한 내용은 [여기](https://wiki.fileformat.com/image/vtx)에서 확인하세요. |

### 또 보기

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
