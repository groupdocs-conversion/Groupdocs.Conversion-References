---
title: "CadFileType"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "CAD 문서(Computer Aided Design)를 정의하며, 3D 그래픽 파일 형식에 사용되고 2D 또는 3D 디자인을 포함할 수 있습니다."
type: docs
weight: 11
url: /ko/nodejs-java/com.groupdocs.conversion.filetypes/cadfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CadFileType extends FileType implements Serializable
```

CAD 문서(Computer Aided Design)를 정의하며, 3D 그래픽 파일 형식에 사용되고 2D 또는 3D 디자인을 포함할 수 있습니다. 다음 유형을 포함합니다: [Dgn](../../com.groupdocs.conversion.filetypes/cadfiletype\#Dgn), [Dwf](../../com.groupdocs.conversion.filetypes/cadfiletype\#Dwf), [Dwg](../../com.groupdocs.conversion.filetypes/cadfiletype\#Dwg), [Dwt](../../com.groupdocs.conversion.filetypes/cadfiletype\#Dwt), [Dxf](../../com.groupdocs.conversion.filetypes/cadfiletype\#Dxf), [Ifc](../../com.groupdocs.conversion.filetypes/cadfiletype\#Ifc), [Igs](../../com.groupdocs.conversion.filetypes/cadfiletype\#Igs), [Plt](../../com.groupdocs.conversion.filetypes/cadfiletype\#Plt), [Stl](../../com.groupdocs.conversion.filetypes/cadfiletype\#Stl). [Cf2](../../com.groupdocs.conversion.filetypes/cadfiletype\#Cf2). [Dwfx](../../com.groupdocs.conversion.filetypes/cadfiletype\#Dwfx). CAD 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/cad
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [CadFileType()](#CadFileType--) | 직렬화 생성자 |
## 필드

| 필드 | 설명 |
| --- | --- |
| [Dxf](#Dxf) | DXF(드로잉 인터체인지 포맷) 또는 드로잉 익스체인지 포맷은 AutoCAD 도면 파일의 태그된 데이터 표현입니다. |
| [Dwg](#Dwg) | DWG 확장자를 가진 파일은 2D 및 3D 디자인 데이터를 포함하는 독점 바이너리 파일을 나타냅니다. |
| [Dgn](#Dgn) | DGN(디자인) 파일은 MicroStation 및 Intergraph Interactive Graphics Design System과 같은 CAD 애플리케이션에서 생성 및 지원되는 도면입니다. |
| [Dwf](#Dwf) | Design Web Format(DWF)은 디자인 파일을 보기, 검토 또는 인쇄하기 위한 압축 형식의 2D/3D 도면을 나타냅니다. |
| [Stl](#Stl) | STL은 스테레오리소그래피의 약자로, 3차원 표면 기하학을 나타내는 교환 가능한 파일 형식입니다. |
| [Ifc](#Ifc) | IFC 확장자를 가진 파일은 건물 객체와 그 속성을 가져오고 내보내기 위한 국제 표준을 설정하는 Industry Foundation Classes(IFC) 파일 형식을 의미합니다. |
| [Plt](#Plt) | PLT 파일 형식은 Autodesk, Inc.에서 도입한 벡터 기반 플로터 파일입니다. |
| [Igs](#Igs) | Igs 문서 형식 |
| [Dwt](#Dwt) | DWT 파일은 DWG 파일로 저장할 수 있는 도면을 만들기 위한 시작 템플릿으로 사용되는 AutoCAD 도면 템플릿 파일입니다. |
| [Dwfx](#Dwfx) | DWFX 파일은 Autodesk CAD 소프트웨어로 만든 2D 또는 3D 도면입니다. |
| [Cf2](#Cf2) | Common File Format 파일. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### CadFileType() {#CadFileType--}
```
public CadFileType()
```


직렬화 생성자

### Dxf {#Dxf}
```
public static final CadFileType Dxf
```


DXF(드로잉 인터체인지 포맷) 또는 드로잉 익스체인지 포맷은 AutoCAD 도면 파일의 태그된 데이터 표현입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/cad/dxf

### Dwg {#Dwg}
```
public static final CadFileType Dwg
```


DWG 확장자를 가진 파일은 2D 및 3D 디자인 데이터를 포함하는 독점 바이너리 파일을 나타냅니다. ASCII 파일인 DXF와 달리, DWG는 CAD(Computer Aided Design) 도면을 위한 바이너리 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][]


[here]: https://wiki.fileformat.com/cad/dwg

### Dgn {#Dgn}
```
public static final CadFileType Dgn
```


DGN(디자인) 파일은 MicroStation 및 Intergraph Interactive Graphics Design System과 같은 CAD 애플리케이션에서 생성 및 지원되는 도면입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/cad/dgn

### Dwf {#Dwf}
```
public static final CadFileType Dwf
```


Design Web Format(DWF)은 디자인 파일을 보기, 검토 또는 인쇄하기 위한 압축 형식의 2D/3D 도면을 나타냅니다. 압축 형식으로 인해 그래픽과 텍스트가 디자인 데이터의 일부로 포함되며 파일 크기가 감소합니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/cad/dwf

### Stl {#Stl}
```
public static final CadFileType Stl
```


STL은 스테레오리소그래피의 약자로, 3차원 표면 기하학을 나타내는 교환 가능한 파일 형식입니다. 이 파일 형식은 급속 프로토타이핑, 3D 프린팅 및 컴퓨터 지원 제조와 같은 여러 분야에서 사용됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/cad/stl

### Ifc {#Ifc}
```
public static final CadFileType Ifc
```


IFC 확장자를 가진 파일은 건물 객체와 그 속성을 가져오고 내보내기 위한 국제 표준을 설정하는 Industry Foundation Classes(IFC) 파일 형식을 의미합니다. 이 파일 형식은 다양한 소프트웨어 애플리케이션 간의 상호 운용성을 제공합니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/cad/ifc

### Plt {#Plt}
```
public static final CadFileType Plt
```


PLT 파일 형식은 Autodesk, Inc.에서 도입한 벡터 기반 플로터 파일이며 특정 CAD 파일에 대한 정보를 포함합니다. 플로팅 세부 사항은 생산에서 정확성과 정밀성을 요구하며, PLT 파일을 사용하면 모든 이미지가 점이 아닌 선으로 인쇄되어 이를 보장합니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/cad/plt

### Igs {#Igs}
```
public static final CadFileType Igs
```


Igs 문서 형식

### Dwt {#Dwt}
```
public static final CadFileType Dwt
```


DWT 파일은 AutoCAD 도면 템플릿 파일로, DWG 파일로 저장할 수 있는 도면을 만들기 위한 시작 파일로 사용됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/cad/dwt

### Dwfx {#Dwfx}
```
public static final CadFileType Dwfx
```


DWFX 파일은 Autodesk CAD 소프트웨어로 만든 2D 또는 3D 도면입니다. 이 파일은 DWFx 형식으로 저장되며, .DWF 파일과 유사하지만 Microsoft의 XML Paper Specification (XPS)을 사용해 포맷됩니다.

### Cf2 {#Cf2}
```
public static final CadFileType Cf2
```


Common File Format 파일. CAD 파일로 3D 패키지 설계 또는 기타 모델 데이터를 포함하며; 다이 커팅 장치와 같은 CAD/CAM 기계로 가공 및 절단할 수 있습니다.

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


소스 파일 유형에 대한 기본 로드 옵션을 준비했습니다.

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


파일 유형에 대한 기본 변환 옵션을 준비했습니다.

**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
