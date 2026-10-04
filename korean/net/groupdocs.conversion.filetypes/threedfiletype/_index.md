---
title: "ThreeDFileType"
second_title: "GroupDocs.Conversion for .NET API 참조"
description: "3D 문서를 정의합니다. 다음 유형을 포함합니다 Fbx./threedfiletype/fbxThreeDS./threedfiletype/threedsThreeMF./threedfiletype/threemfAmf./threedfiletype/amfAse./threedfiletype/aseRvm./threedfiletype/rvmDae./threedfiletype/daeDrc./threedfiletype/drcGltf./threedfiletype/gltfObj./threedfiletype/objPly./threedfiletype/plyJt./threedfiletype/jtU3d./threedfiletype/u3dUsd./threedfiletype/usdUsdz./threedfiletype/usdzVrml./threedfiletype/vrmlX./threedfiletype/xGlb./threedfiletype/glbMa./threedfiletype/maMb./threedfiletype/mb 3D 형식에 대해 자세히 알아보려면 여기https//wiki.fileformat.com/3d."
type: docs
weight: 1250
url: /ko/net/groupdocs.conversion.filetypes/threedfiletype/
---
## ThreeDFileType class

3D 문서를 정의합니다. 다음 유형을 포함합니다: [`Fbx`](./fbx)[`ThreeDS`](./threeds)[`ThreeMF`](./threemf)[`Amf`](./amf)[`Ase`](./ase)[`Rvm`](./rvm)[`Dae`](./dae)[`Drc`](./drc)[`Gltf`](./gltf)[`Obj`](./obj)[`Ply`](./ply)[`Jt`](./jt)[`U3d`](./u3d)[`Usd`](./usd)[`Usdz`](./usdz)[`Vrml`](./vrml)[`X`](./x)[`Glb`](./glb)[`Ma`](./ma)[`Mb`](./mb) 3D 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/3d).

```csharp
public sealed class ThreeDFileType : FileType
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ThreeDFileType](threedfiletype)() | 직렬화 생성자 |

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
| static readonly [Amf](../../groupdocs.conversion.filetypes/threedfiletype/amf) | AMF 파일은 적층 제조 프로세스에서 사용하기 위한 객체 설명 지침으로 구성됩니다. 파일은 시작 XML 태그를 포함하고 요소로 끝납니다. 이는 파일의 XML 버전 및 인코딩을 지정하는 XML 선언 라인이 앞에 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/3d/amf)에서 확인하세요. |
| static readonly [Ase](../../groupdocs.conversion.filetypes/threedfiletype/ase) | .ase 확장자를 가진 파일은 Autodesk ASCII Scene Export 파일 형식으로, 장면의 ASCII 표현이며 Autodesk를 사용해 장면 데이터를 내보낼 때 2D 또는 3D 정보를 포함합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/3d/ase)에서 확인하세요. |
| static readonly [Dae](../../groupdocs.conversion.filetypes/threedfiletype/dae) | DAE 파일은 인터랙티브 3D 애플리케이션 간 데이터 교환에 사용되는 Digital Asset Exchange 파일 형식입니다. 이 파일 형식은 디지털 자산 교환을 위한 개방형 표준 XML 스키마인 COLLADA(COLLAborative Design Activity) XML 스키마를 기반으로 합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/3d/dae)에서 확인하세요. |
| static readonly [Drc](../../groupdocs.conversion.filetypes/threedfiletype/drc) | .drc 확장자를 가진 파일은 Google Draco 라이브러리로 만든 압축 3D 파일 형식입니다. Google은 3D 기하 메시와 포인트 클라우드를 압축·압축 해제하기 위한 오픈 소스 라이브러리인 Draco를 제공하며, 3D 그래픽의 저장 및 전송을 개선합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/3d/drc)에서 확인하세요. |
| static readonly [Fbx](../../groupdocs.conversion.filetypes/threedfiletype/fbx) | FBX, FilmBox는 원래 Kaydara가 MotionBuilder용으로 개발한 인기 있는 3D 파일 형식입니다. 2006년에 Autodesk Inc가 인수했으며 현재 많은 3D 도구에서 사용되는 주요 3D 교환 형식 중 하나입니다. FBX는 바이너리와 ASCII 파일 형식 모두로 제공됩니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/3d/fbx)에서 확인하세요. |
| static readonly [Glb](../../groupdocs.conversion.filetypes/threedfiletype/glb) | GLB는 GL Transmission Format(glTF)으로 저장된 3D 모델의 바이너리 파일 형식 표현입니다. 이 바이너리 형식은 glTF 자산(JSON, .bin 및 이미지)을 바이너리 블롭에 저장합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/3d/glb)에서 확인하세요. |
| static readonly [Gltf](../../groupdocs.conversion.filetypes/threedfiletype/gltf) | glTF(GL Transmission Format)는 3D 모델 정보를 JSON 형식으로 저장하는 3D 파일 형식입니다. JSON을 사용하면 3D 자산의 크기와 해당 자산을 풀고 사용하는 데 필요한 런타임 처리를 최소화할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/3d/gltf)에서 확인하세요. |
| static readonly [Jt](../../groupdocs.conversion.filetypes/threedfiletype/jt) | JT(Jupiter Tessellation)는 Siemens PLM Software가 개발한 효율적이고 산업 중심적이며 유연한 ISO 표준 3D 데이터 형식입니다. 항공우주, 자동차 산업 및 중장비 분야의 기계 CAD 도메인에서는 JT를 주요 3D 시각화 형식으로 사용합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/3d/jt)에서 확인하세요. |
| static readonly [Ma](../../groupdocs.conversion.filetypes/threedfiletype/ma) | .ma 확장자를 가진 파일은 Autodesk Maya 애플리케이션으로 만든 3D 프로젝트 파일입니다. 파일에 대한 정보를 지정하는 텍스트 명령 목록을 포함합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/3d/ma)에서 확인하세요. |
| static readonly [Mb](../../groupdocs.conversion.filetypes/threedfiletype/mb) | .mb 확장자를 가진 파일은 Autodesk Maya 애플리케이션으로 만든 바이너리 프로젝트 파일입니다. ASCII 형식인 MA 파일 형식과 달리 MB 파일은 바이너리 파일 형식으로 저장됩니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/3d/mb)에서 확인하세요. |
| static readonly [Obj](../../groupdocs.conversion.filetypes/threedfiletype/obj) | OBJ 파일은 Wavefront의 Advanced Visualizer 애플리케이션에서 기하학적 객체를 정의하고 저장하는 데 사용됩니다. OBJ 파일을 통해 기하학 데이터의 전후 전송이 가능합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/3d/obj)에서 확인하세요. |
| static readonly [Ply](../../groupdocs.conversion.filetypes/threedfiletype/ply) | PLY, Polygon File Format은 다각형 집합으로 설명된 그래픽 객체를 저장하는 3D 파일 형식입니다. 이 파일 형식의 목적은 다양한 모델에 유용할 만큼 일반적인 간단하고 쉬운 파일 유형을 만드는 것이었습니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/3d/ply)에서 확인하세요. |
| static readonly [Rvm](../../groupdocs.conversion.filetypes/threedfiletype/rvm) | RVM 데이터 파일은 AVEVA PDMS와 관련이 있습니다. RVM 파일은 AVEVA Plant Design Management System 모델 프로젝트 파일입니다. AVEVA의 Plant Design Management System(PDMS)은 프로젝트 관리에 데이터 중심 기술을 사용하는 가장 인기 있는 3D 설계 시스템입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/3d/rvm)에서 확인하세요. |
| static readonly [ThreeDS](../../groupdocs.conversion.filetypes/threedfiletype/threeds) | .3ds 확장자를 가진 파일은 Autodesk 3D Sudio (DOS) 메시 파일 형식을 나타냅니다. Autodesk 3D Studio는 1990년대부터 3D 파일 형식 시장에 있었으며 현재는 3D 모델링, 애니메이션 및 렌더링 작업을 위한 3D Studio MAX로 발전했습니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/3d/3ds)에서 확인하세요. |
| static readonly [ThreeMF](../../groupdocs.conversion.filetypes/threedfiletype/threemf) | 3MF, 3D Manufacturing Format은 애플리케이션이 3D 객체 모델을 다양한 다른 애플리케이션, 플랫폼, 서비스 및 프린터에 렌더링하는 데 사용됩니다. 최신 3D 프린터와 작업하기 위해 STL과 같은 다른 3D 파일 형식의 제한 및 문제를 피하도록 설계되었습니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/3d/3mf)에서 확인하세요. |
| static readonly [U3d](../../groupdocs.conversion.filetypes/threedfiletype/u3d) | U3D (Universal 3D)는 3D 컴퓨터 그래픽을 위한 압축 파일 형식 및 데이터 구조입니다. 삼각형 메쉬, 조명, 셰이딩, 모션 데이터, 색상 및 구조가 포함된 선과 점과 같은 3D 모델 정보를 포함합니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://docs.fileformat.com/3d/u3d)에서 확인하세요. |
| static readonly [Usd](../../groupdocs.conversion.filetypes/threedfiletype/usd) | .usd 확장자를 가진 파일은 디지털 콘텐츠 제작 애플리케이션 간 데이터 교환 및 증강을 위해 데이터를 인코딩하는 Universal Scene Description 파일 형식입니다. Pixar에서 개발한 USD는 모델과 같은 기본 자산 또는 애니메이션을 교환할 수 있는 기능을 제공합니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://docs.fileformat.com/3d/usd)에서 확인하세요. |
| static readonly [Usdz](../../groupdocs.conversion.filetypes/threedfiletype/usdz) | .usdz 파일은 압축되지 않고 암호화되지 않은 ZIP 아카이브로, USD (Universal Scene Description) 파일 형식이며, 아카이브 내에 포함된 다른 형식(예: 텍스처 및 애니메이션) 파일에 대한 프록시 역할을 하며, 압축 해제 없이 USD 런타임에서 직접 실행됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://docs.fileformat.com/3d/usdz)에서 확인하세요. |
| static readonly [Vrml](../../groupdocs.conversion.filetypes/threedfiletype/vrml) | Virtual Reality Modeling Language (VRML)는 월드 와이드 웹(www)에서 인터랙티브 3D 세계 객체를 표현하기 위한 파일 형식입니다. 복잡한 장면의 3차원 표현, 일러스트레이션, 정의 및 가상 현실 프레젠테이션을 만드는 데 사용됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://docs.fileformat.com/3d/vrml)에서 확인하세요. |
| static readonly [X](../../groupdocs.conversion.filetypes/threedfiletype/x) | .x 확장자를 가진 파일은 Microsoft DirectX 2.0과 함께 도입된 DirectX 3D Graphics 레거시 파일 형식을 의미합니다. 게임에서 3D 그래픽 렌더링에 사용되며 메쉬, 텍스처, 애니메이션 및 사용자 정의 객체의 구조를 지정합니다. Autodesk FBX 파일 형식이 보다 현대적인 형식으로 대체되면서 2014년부터 사용이 중단되었습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://docs.fileformat.com/3d/x)에서 확인하세요. |

### 또 보기

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
