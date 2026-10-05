---
title: "DiagramFileType"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "다이어그램 문서를 정의합니다."
type: docs
weight: 13
url: /ko/nodejs-java/com.groupdocs.conversion.filetypes/diagramfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DiagramFileType extends FileType implements Serializable
```

Diagram 문서를 정의합니다. 다음 유형을 포함합니다: [Vdw](../../com.groupdocs.conversion.filetypes/diagramfiletype\\#Vdw), [Vdx](../../com.groupdocs.conversion.filetypes/diagramfiletype\\#Vdx), [Vsd](../../com.groupdocs.conversion.filetypes/diagramfiletype\\#Vsd), [Vsdm](../../com.groupdocs.conversion.filetypes/diagramfiletype\\#Vsdm), [Vsdx](../../com.groupdocs.conversion.filetypes/diagramfiletype\\#Vsdx), [Vss](../../com.groupdocs.conversion.filetypes/diagramfiletype\\#Vss), [Vssm](../../com.groupdocs.conversion.filetypes/diagramfiletype\\#Vssm), [Vssx](../../com.groupdocs.conversion.filetypes/diagramfiletype\\#Vssx), [Vst](../../com.groupdocs.conversion.filetypes/diagramfiletype\\#Vst), [Vstm](../../com.groupdocs.conversion.filetypes/diagramfiletype\\#Vstm), [Vstx](../../com.groupdocs.conversion.filetypes/diagramfiletype\\#Vstx), [Vsx](../../com.groupdocs.conversion.filetypes/diagramfiletype\\#Vsx), [Vtx](../../com.groupdocs.conversion.filetypes/diagramfiletype\\#Vtx).
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [DiagramFileType()](#DiagramFileType--) | 직렬화 생성자 |
## 필드

| 필드 | 설명 |
| --- | --- |
| [Vsd](#Vsd) | VSD 파일은 Microsoft Visio 애플리케이션으로 만든 도면으로, 다양한 그래픽 객체와 이들 간의 연결을 나타냅니다. |
| [Vsdx](#Vsdx) | .VSDX 확장자를 가진 파일은 Microsoft Office 2013 이후에 도입된 Microsoft Visio 파일 형식을 나타냅니다. |
| [Vss](#Vss) | VSS는 Microsoft Visio 2007 및 이전 버전으로 만든 스텐실 파일입니다. |
| [Vst](#Vst) | VST 확장자를 가진 파일은 Microsoft Visio로 만든 벡터 이미지 파일이며, 추가 파일을 만들기 위한 템플릿 역할을 합니다. |
| [Vsx](#Vsx) | .VSX 확장자를 가진 파일은 Microsoft Visio에서 다이어그램을 만들 때 사용되는 도면 및 도형으로 구성된 스텐실을 의미합니다. |
| [Vtx](#Vtx) | VTX 확장자를 가진 파일은 XML 파일 형식으로 디스크에 저장되는 Microsoft Visio 도면 템플릿입니다. |
| [Vdw](#Vdw) | VDW는 웹 도면을 렌더링하는 데 필요한 스트림 및 스토리지를 지정하는 Visio Graphics Service 파일 형식입니다. |
| [Vdx](#Vdx) | Microsoft Visio에서 만든 모든 도면이나 차트가 XML 형식으로 저장될 경우 .VDX 확장자를 가집니다. |
| [Vssx](#Vssx) | .VSSX 확장자를 가진 파일은 Microsoft Visio 2013 이상에서 만든 도면 스텐실입니다. |
| [Vstx](#Vstx) | VSTX 확장자를 가진 파일은 Microsoft Visio 2013 이상에서 만든 도면 템플릿 파일입니다. |
| [Vsdm](#Vsdm) | VSDM 확장자를 가진 파일은 매크로를 지원하는 Microsoft Visio 애플리케이션으로 만든 도면 파일입니다. |
| [Vssm](#Vssm) | .VSSM 확장자를 가진 파일은 매크로를 지원하는 Microsoft Visio 스텐실 파일입니다. |
| [Vstm](#Vstm) | VSTM 확장자를 가진 파일은 매크로를 지원하는 Microsoft Visio로 만든 템플릿 파일입니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### DiagramFileType() {#DiagramFileType--}
```
public DiagramFileType()
```


직렬화 생성자

### Vsd {#Vsd}
```
public static final DiagramFileType Vsd
```


VSD 파일은 다양한 그래픽 객체와 그들 간의 연결을 나타내기 위해 Microsoft Visio 애플리케이션으로 만든 도면입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/image/vsd

### Vsdx {#Vsdx}
```
public static final DiagramFileType Vsdx
```


.VSDX 확장자를 가진 파일은 Microsoft Office 2013 이후 도입된 Microsoft Visio 파일 형식을 나타냅니다. 이는 이전 버전 Microsoft Visio에서 지원하던 바이너리 파일 형식인 .VSD를 대체하기 위해 개발되었습니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/image/vsdx

### Vss {#Vss}
```
public static final DiagramFileType Vss
```


VSS는 Microsoft Visio 2007 및 이전 버전으로 만든 스텐실 파일입니다. 스텐실 파일은 .VSD Visio 도면에 포함될 수 있는 도면 객체를 제공합니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/image/vss

### Vst {#Vst}
```
public static final DiagramFileType Vst
```


VST 확장자를 가진 파일은 Microsoft Visio로 만든 벡터 이미지 파일이며, 추가 파일을 만들기 위한 템플릿 역할을 합니다. 이러한 템플릿 파일은 바이너리 파일 형식이며, 새로운 Visio 도면을 만들 때 사용되는 기본 레이아웃과 설정을 포함합니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/image/vst

### Vsx {#Vsx}
```
public static final DiagramFileType Vsx
```


.VSX 확장자를 가진 파일은 Microsoft Visio에서 다이어그램을 만들 때 사용되는 도면 및 도형으로 구성된 스텐실을 의미합니다. VSX 파일은 XML 파일 형식으로 저장되며 Visio 2013까지 지원되었습니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/image/vsx

### Vtx {#Vtx}
```
public static final DiagramFileType Vtx
```


VTX 확장자를 가진 파일은 XML 파일 형식으로 디스크에 저장되는 Microsoft Visio 도면 템플릿입니다. 이 템플릿은 동일한 설정을 가진 여러 Visio 파일을 만들 때 사용할 수 있는 기본 설정을 제공하도록 설계되었습니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/image/vtx

### Vdw {#Vdw}
```
public static final DiagramFileType Vdw
```


VDW는 웹 도면을 렌더링하는 데 필요한 스트림 및 스토리지를 지정하는 Visio Graphics Service 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/web/vdw

### Vdx {#Vdx}
```
public static final DiagramFileType Vdx
```


Microsoft Visio에서 만든 모든 도면이나 차트가 XML 형식으로 저장될 경우 .VDX 확장자를 가집니다. Visio XML 파일은 Microsoft에서 개발한 Visio 소프트웨어에서 생성됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/image/vdx

### Vssx {#Vssx}
```
public static final DiagramFileType Vssx
```


.VSSX 확장자를 가진 파일은 Microsoft Visio 2013 이상에서 만든 도면 스텐실입니다. VSSX 파일 형식은 Visio 2013 이상에서 열 수 있습니다. Visio 파일은 도형 컬렉션, 커넥터, 흐름도, 네트워크 레이아웃, UML 다이어그램 등 다양한 도면 요소를 표현하는 것으로 알려져 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/image/vssx

### Vstx {#Vstx}
```
public static final DiagramFileType Vstx
```


VSTX 확장자를 가진 파일은 Microsoft Visio 2013 이상에서 만든 도면 템플릿 파일입니다. 이러한 VSTX 파일은 기본 레이아웃과 설정을 갖춘 .VSDX 파일로 저장되는 Visio 도면을 만들기 위한 시작점을 제공합니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/image/vstx

### Vsdm {#Vsdm}
```
public static final DiagramFileType Vsdm
```


VSDM 확장자를 가진 파일은 매크로를 지원하는 Microsoft Visio 애플리케이션으로 만든 도면 파일입니다. VSDM 파일은 VSDX와 유사한 OPC/XML 도면이며, 파일이 열릴 때 매크로를 실행할 수 있는 기능도 제공합니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/image/vsdm

### Vssm {#Vssm}
```
public static final DiagramFileType Vssm
```


.VSSM 확장자를 가진 파일은 매크로를 지원하는 Microsoft Visio 스텐실 파일입니다. VSSM 파일을 열면 매크로를 실행하여 다이어그램에서 원하는 형식 지정 및 도형 배치를 할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/image/vssm

### Vstm {#Vstm}
```
public static final DiagramFileType Vstm
```


VSTM 확장자를 가진 파일은 매크로를 지원하는 Microsoft Visio로 만든 템플릿 파일입니다. VSDX 파일과 달리 VSTM 템플릿에서 만든 파일은 Visual Basic for Applications (VBA) 코드로 개발된 매크로를 실행할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/image/vstm

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
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static final FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
