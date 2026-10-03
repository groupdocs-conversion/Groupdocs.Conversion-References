---
title: "PresentationFileType"
second_title: "GroupDocs.Conversion for Java API 레퍼런스"
description: "프레젠테이션 파일 형식은 슬라이드, 도형, 텍스트, 애니메이션, 비디오, 오디오 및 포함된 객체와 같은 프레젠테이션 데이터를 수용하기 위해 레코드 컬렉션을 저장하도록 정의합니다."
type: docs
weight: 22
url: /ko/java/com.groupdocs.conversion.filetypes/presentationfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PresentationFileType extends FileType implements Serializable
```

프레젠테이션 데이터(슬라이드, 도형, 텍스트, 애니메이션, 비디오, 오디오 및 포함된 객체 등)를 수용하기 위해 레코드 컬렉션을 저장하는 프레젠테이션 파일 형식을 정의합니다.
다음 파일 유형을 포함합니다:
[Odp](../../com.groupdocs.conversion.filetypes/presentationfiletype#Odp),
[Otp](../../com.groupdocs.conversion.filetypes/presentationfiletype#Otp),
[Pot](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pot),
[Potm](../../com.groupdocs.conversion.filetypes/presentationfiletype#Potm),
[Potx](../../com.groupdocs.conversion.filetypes/presentationfiletype#Potx),
[Pps](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pps),
[Ppsm](../../com.groupdocs.conversion.filetypes/presentationfiletype#Ppsm),
[Ppsx](../../com.groupdocs.conversion.filetypes/presentationfiletype#Ppsx),
[Ppt](../../com.groupdocs.conversion.filetypes/presentationfiletype#Ppt),
[Pptm](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pptm),
[Pptx](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pptx).
프레젠테이션 형식에 대해 자세히 알아보려면 [here](../https://wiki.fileformat.com/presentation)를 클릭하십시오.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [PresentationFileType()](#PresentationFileType--) | 직렬화 생성자 |
|
## 필드

| 필드 | 설명 |
| --- | --- |
|  | [Ppt](#Ppt) | PPT 확장자를 가진 파일은 슬라이드 쇼로 표시되는 슬라이드 컬렉션을 포함하는 PowerPoint 파일을 나타냅니다. |
|
|  | [Pps](#Pps) | PPS, PowerPoint Slide Show 파일은 슬라이드 쇼 용도로 Microsoft PowerPoint를 사용하여 생성됩니다. |
|
|  | [Pptx](#Pptx) | PPTX 확장자를 가진 파일은 널리 사용되는 Microsoft PowerPoint 애플리케이션으로 만든 프레젠테이션 파일입니다. |
|
|  | [Ppsx](#Ppsx) | PPSX, Power Point Slide Show 파일은 Microsoft PowerPoint 2007 이상을 사용하여 슬라이드 쇼 용도로 생성됩니다. |
|
|  | [Odp](#Odp) | ODP 확장자를 가진 파일은 OASISOpen 표준에서 OpenOffice.org가 사용하는 프레젠테이션 파일 형식을 나타냅니다. |
|
|  | [Otp](#Otp) | .OTP 확장자를 가진 파일은 OASIS OpenDocument 표준 형식으로 애플리케이션에서 만든 프레젠테이션 템플릿 파일을 나타냅니다. |
|
|  | [Potx](#Potx) | .POTX 확장자를 가진 파일은 Microsoft PowerPoint 2007 이상으로 만든 Microsoft PowerPoint 템플릿 프레젠테이션을 나타냅니다. |
|
|  | [Pot](#Pot) | .POT 확장자를 가진 파일은 PowerPoint 97-2003 버전으로 만든 Microsoft PowerPoint 템플릿 파일을 나타냅니다. |
|
|  | [Potm](#Potm) | POTM 확장자를 가진 파일은 매크로를 지원하는 Microsoft PowerPoint 템플릿 파일입니다. |
|
|  | [Pptm](#Pptm) | PPTM 확장자를 가진 파일은 Microsoft PowerPoint 2007 이상 버전으로 만든 매크로 지원 프레젠테이션 파일입니다. |
|
|  | [Ppsm](#Ppsm) | PPSM 확장자를 가진 파일은 Microsoft PowerPoint 2007 이상으로 만든 매크로 지원 슬라이드 쇼 파일 형식을 나타냅니다. |
|
|  | [Fodp](#Fodp) | FODP 확장자를 가진 파일은 OpenDocument 플랫 XML 프레젠테이션을 나타냅니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PresentationFileType() {#PresentationFileType--}
```
public PresentationFileType()
```


직렬화 생성자


### Ppt {#Ppt}
```
public static final PresentationFileType Ppt
```


PPT 확장자를 가진 파일은 슬라이드 쇼로 표시하기 위한 슬라이드 모음으로 구성된 PowerPoint 파일을 나타냅니다. 이는 Microsoft PowerPoint 97-2003에서 사용되는 이진 파일 형식을 지정합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/presentation/ppt)에서 확인하세요.


### Pps {#Pps}
```
public static final PresentationFileType Pps
```


PPS, PowerPoint Slide Show 파일은 슬라이드 쇼 용도로 Microsoft PowerPoint를 사용하여 생성됩니다. PPS 파일의 읽기 및 생성은 Microsoft PowerPoint 97-2003에서 지원됩니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/presentation/pps)에서 확인하세요.


### Pptx {#Pptx}
```
public static final PresentationFileType Pptx
```


PPTX 확장자를 가진 파일은 널리 사용되는 Microsoft PowerPoint 애플리케이션으로 만든 프레젠테이션 파일입니다. 이전의 이진 PPT 형식과 달리, PPTX 형식은 Microsoft PowerPoint 오픈 XML 프레젠테이션 파일 형식을 기반으로 합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/presentation/pptx)에서 확인하세요.


### Ppsx {#Ppsx}
```
public static final PresentationFileType Ppsx
```


PPSX, Power Point Slide Show 파일은 Microsoft PowerPoint 2007 이상을 사용하여 슬라이드 쇼 용도로 생성됩니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/presentation/ppsx)에서 확인하세요.


### Odp {#Odp}
```
public static final PresentationFileType Odp
```


ODP 확장자를 가진 파일은 OASISOpen 표준에서 OpenOffice.org가 사용하는 프레젠테이션 파일 형식을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/presentation/odp)에서 확인하세요.


### Otp {#Otp}
```
public static final PresentationFileType Otp
```


.OTP 확장자를 가진 파일은 OASIS OpenDocument 표준 형식으로 애플리케이션에서 만든 프레젠테이션 템플릿 파일을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/presentation/otp)에서 확인하세요.


### Potx {#Potx}
```
public static final PresentationFileType Potx
```


.POTX 확장자를 가진 파일은 Microsoft PowerPoint 2007 이상으로 만든 Microsoft PowerPoint 템플릿 프레젠테이션을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/presentation/potx)에서 확인하세요.


### Pot {#Pot}
```
public static final PresentationFileType Pot
```


.POT 확장자를 가진 파일은 PowerPoint 97-2003 버전으로 만든 Microsoft PowerPoint 템플릿 파일을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/presentation/pot)에서 확인하세요.


### Potm {#Potm}
```
public static final PresentationFileType Potm
```


POTM 확장자를 가진 파일은 매크로를 지원하는 Microsoft PowerPoint 템플릿 파일입니다. POTM 파일은 PowerPoint 2007 이상으로 생성되며, 추가 프레젠테이션 파일을 만들 때 사용할 수 있는 기본 설정을 포함합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/presentation/potm)에서 확인하세요.


### Pptm {#Pptm}
```
public static final PresentationFileType Pptm
```


PPTM 확장자를 가진 파일은 Microsoft PowerPoint 2007 이상 버전으로 만든 매크로 지원 프레젠테이션 파일입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/presentation/pptm)에서 확인하세요.


### Ppsm {#Ppsm}
```
public static final PresentationFileType Ppsm
```


PPSM 확장자를 가진 파일은 Microsoft PowerPoint 2007 이상으로 만든 매크로 지원 슬라이드 쇼 파일 형식을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/presentation/ppsm)에서 확인하세요.


### Fodp {#Fodp}
```
public static final PresentationFileType Fodp
```


FODP 확장자를 가진 파일은 OpenDocument 플랫 XML 프레젠테이션을 나타냅니다. 프레젠테이션 파일은 OpenDocument 형식으로 저장되지만, 표준 .ODP 파일에서 사용하는 .ZIP 컨테이너 대신 플랫 XML 형식으로 저장됩니다.


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


소스 파일 유형에 대한 기본 로드 옵션을 준비했습니다


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


파일 유형에 대한 기본 변환 옵션을 준비했습니다


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
