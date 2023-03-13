---
title: ThreeDFileType
second_title: .NET API 참조용 GroupDocs.Conversion
description: 3D 문서 정의 다음 유형 포함 Fbx./threedfiletype/fbxThreeDS./threedfiletype/threedsThreeMF./threedfiletype/threemfAmf./threedfiletype/amfAse./threedfiletype/aseRvm./threedfiletype/rvmDae./threedfiletype/daeDrc./threedfiletype/drcGltf./threedfiletype/gltfObj./threedfiletype/objPly./threedfiletype/plyJt./threedfiletype/jtU3d./threedfiletype/u3dUsd./threedfiletype/usdUsdz./threedfiletype/usdzVrml./threedfiletype/vrmlX./threedfiletype/x 3D 형식에 대해 자세히 알아보기여기https//wiki.fileformat.com/3d .
type: docs
weight: 1060
url: /ko/net/groupdocs.conversion.filetypes/threedfiletype/
---
## ThreeDFileType class

3D 문서 정의 다음 유형 포함: [`Fbx`](./fbx)[`ThreeDS`](./threeds)[`ThreeMF`](./threemf)[`Amf`](./amf)[`Ase`](./ase)[`Rvm`](./rvm)[`Dae`](./dae)[`Drc`](./drc)[`Gltf`](./gltf)[`Obj`](./obj)[`Ply`](./ply)[`Jt`](./jt)[`U3d`](./u3d)[`Usd`](./usd)[`Usdz`](./usdz)[`Vrml`](./vrml)[`X`](./x) 3D 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/3d) .

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
| static readonly [Amf](../../groupdocs.conversion.filetypes/threedfiletype/amf) | AMF 파일은 적층 가공 프로세스에서 사용하기 위한 개체 설명에 대한 지침으로 구성됩니다. 여는 XML 태그를 포함하고 요소로 끝납니다. 파일의 XML 버전과 인코딩을 지정하는 XML 선언 줄이 앞에 옵니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/3d/amf) . |
| static readonly [Ase](../../groupdocs.conversion.filetypes/threedfiletype/ase) | 확장자가 .ase인 파일은 Autodesk를 사용하여 장면 데이터를 내보내는 동안 2D 또는 3D 정보를 포함하는 장면의 ASCII 표현인 Autodesk ASCII 장면 내보내기 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/3d/ase) . |
| static readonly [Dae](../../groupdocs.conversion.filetypes/threedfiletype/dae) | DAE 파일은 대화형 3D 응용 프로그램 간에 데이터를 교환하는 데 사용되는 디지털 자산 교환 파일 형식입니다. 이 파일 형식은 그래픽 소프트웨어 응용 프로그램 간에 디지털 자산을 교환하기 위한 개방형 표준 XML 스키마인 COLLADA(COLLAborative Design Activity) XML 스키마를 기반으로 합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/3d/dae) . |
| static readonly [Drc](../../groupdocs.conversion.filetypes/threedfiletype/drc) | 확장자가 .drc인 파일은 Google Draco 라이브러리로 만든 압축된 3D 파일 형식입니다. Google은 Draco를 3D 기하학적 메시 및 포인트 클라우드 압축 및 압축 해제를 위한 오픈 소스 라이브러리로 제공하고 3D 그래픽의 저장 및 전송을 개선합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/3d/drc) . |
| static readonly [Fbx](../../groupdocs.conversion.filetypes/threedfiletype/fbx) | FBX, FilmBox는 원래 Kaydara가 MotionBuilder용으로 개발한 인기 있는 3D 파일 형식입니다. 2006년 Autodesk Inc에 인수되었으며 현재 많은 3D 도구에서 사용되는 주요 3D 교환 형식 중 하나입니다. FBX는 바이너리 및 ASCII 파일 형식으로 사용할 수 있습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/3d/fbx) . |
| static readonly [Gltf](../../groupdocs.conversion.filetypes/threedfiletype/gltf) | glTF(GL Transmission Format)는 3D 모델 정보를 JSON 형식으로 저장하는 3D 파일 형식입니다. JSON을 사용하면 3D 자산의 크기와 해당 자산의 압축을 풀고 사용하는 데 필요한 런타임 처리가 모두 최소화됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/3d/gltf) . |
| static readonly [Jt](../../groupdocs.conversion.filetypes/threedfiletype/jt) | JT(Jupiter Tessellation)는 Siemens PLM Software에서 개발한 효율적이고 산업 중심적이며 유연한 ISO 표준 3D 데이터 형식입니다. 항공우주, 자동차 산업 및 중장비의 기계 CAD 도메인은 JT를 가장 선도적인 3D 시각화 형식으로 사용합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/3d/jt) . |
| static readonly [Obj](../../groupdocs.conversion.filetypes/threedfiletype/obj) | OBJ 파일은 Wavefront의 Advanced Visualizer 응용 프로그램에서 기하학적 개체를 정의하고 저장하는 데 사용됩니다. OBJ 파일을 통해 기하 데이터의 전후방 전송이 가능합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/3d/obj) . |
| static readonly [Ply](../../groupdocs.conversion.filetypes/threedfiletype/ply) | PLY, 다각형 파일 형식은 다각형 모음으로 설명된 그래픽 개체를 저장하는 3D 파일 형식을 나타냅니다. 이 파일 형식의 목적은 다양한 모델에 유용할 만큼 충분히 일반적인 간단하고 쉬운 파일 형식을 설정하는 것이었습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/3d/ply) . |
| static readonly [Rvm](../../groupdocs.conversion.filetypes/threedfiletype/rvm) | RVM 데이터 파일은 AVEVA PDMS와 관련이 있습니다. RVM 파일은 AVEVA Plant Design Management System Model 프로젝트 파일입니다. AVEVA의 PDMS(Plant Design Management System)는 프로젝트 관리를 위해 데이터 중심 기술을 사용하는 가장 인기 있는 3D 설계 시스템입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/3d/rvm) . |
| static readonly [ThreeDS](../../groupdocs.conversion.filetypes/threedfiletype/threeds) | 확장자가 .3ds인 파일은 Autodesk 3D Studio에서 사용하는 3D Sudio(DOS) 메시 파일 형식을 나타냅니다. Autodesk 3D Studio는 1990년대부터 3D 파일 형식 시장에 있었고 이제 3D 모델링, 애니메이션 및 렌더링 작업을 위해 3D Studio MAX로 발전했습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/3d/3ds) . |
| static readonly [ThreeMF](../../groupdocs.conversion.filetypes/threedfiletype/threemf) | 3MF(3D 제조 형식)는 응용 프로그램에서 3D 개체 모델을 다양한 다른 응용 프로그램, 플랫폼, 서비스 및 프린터에 렌더링하는 데 사용됩니다. 최신 버전의 3D 프린터로 작업하기 위해 STL과 같은 다른 3D 파일 형식의 제한과 문제를 피하기 위해 제작되었습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/3d/3mf) . |
| static readonly [U3d](../../groupdocs.conversion.filetypes/threedfiletype/u3d) | U3D(Universal 3D)는 3D 컴퓨터 그래픽용 압축 파일 형식 및 데이터 구조입니다. 삼각형 메쉬, 조명, 음영, 모션 데이터, 색상 및 구조가 있는 선 및 점과 같은 3D 모델 정보를 포함합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/3d/u3d) . |
| static readonly [Usd](../../groupdocs.conversion.filetypes/threedfiletype/usd) | 확장자가 .usd인 파일은 디지털 콘텐츠 생성 응용 프로그램 간에 데이터 교환 및 보강을 목적으로 데이터를 인코딩하는 범용 장면 설명 파일 형식입니다. Pixar에서 개발한 USD는 요소 자산(예: 모델) 또는 애니메이션을 교환할 수 있는 기능을 제공합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/3d/usd) . |
| static readonly [Usdz](../../groupdocs.conversion.filetypes/threedfiletype/usdz) | .usdz가 포함된 파일은 압축 및 암호화되지 않은 USD(Universal Scene Description) 파일 형식용 ZIP 아카이브로, 아카이브 내에 포함된 다른 형식(예: 텍스처 및 애니메이션)의 파일을 포함하고 이를 프록시하여 직접 실행합니다. 압축을 풀 필요가 없는 USD 런타임. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/3d/usdz) . |
| static readonly [Vrml](../../groupdocs.conversion.filetypes/threedfiletype/vrml) | VRML(Virtual Reality Modeling Language)은 www(World Wide Web)를 통해 대화형 3D 세계 개체를 표현하기 위한 파일 형식입니다. 일러스트레이션, 정의 및 가상 현실 프레젠테이션과 같은 복잡한 장면의 3차원 표현을 만드는 데 사용됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/3d/vrml) . |
| static readonly [X](../../groupdocs.conversion.filetypes/threedfiletype/x) | 확장자가 .x인 파일은 Microsoft DirectX 2.0과 함께 도입된 DirectX 3D 그래픽 레거시 파일 형식을 나타냅니다. 게임에서 3D 그래픽 렌더링에 사용되었으며 메쉬, 텍스처, 애니메이션 및 사용자 정의 개체의 구조를 지정합니다. Autodesk FBX 파일 형식이 더 현대적인 형식으로 더 잘 작동하므로 2014년 이후로 더 이상 사용되지 않습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/3d/x) . |

### 또한보십시오

* class [FileType](../filetype)
* 네임스페이스 [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* 집회 [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
