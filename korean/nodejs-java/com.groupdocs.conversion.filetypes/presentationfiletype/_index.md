---
title: "PresentationFileType"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "Defines Presentation file formats that store collection of records to accommodate presentation data such as slides shapes text animations video audio and embedded objects."
type: docs
weight: 22
url: /ko/nodejs-java/com.groupdocs.conversion.filetypes/presentationfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PresentationFileType extends FileType implements Serializable
```

Defines Presentation file formats that store collection of records to accommodate presentation data such as slides, shapes, text, animations, video, audio and embedded objects. Includes the following file types: [Odp](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Odp), [Otp](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Otp), [Pot](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Pot), [Potm](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Potm), [Potx](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Potx), [Pps](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Pps), [Ppsm](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Ppsm), [Ppsx](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Ppsx), [Ppt](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Ppt), [Pptm](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Pptm), [Pptx](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Pptx). Learn more about Presentation formats [here][].


[here]: https://wiki.fileformat.com/presentation
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PresentationFileType()](#PresentationFileType--) | 직렬화 생성자 |
## 필드

| 필드 | 설명 |
| --- | --- |
| [Ppt](#Ppt) | A file with PPT extension represents PowerPoint file that consists of a collection of slides for displaying as SlideShow. |
| [Pps](#Pps) | PPS, PowerPoint Slide Show, files are created using Microsoft PowerPoint for Slide Show purpose. |
| [Pptx](#Pptx) | Files with PPTX extension are presentation files created with popular Microsoft PowerPoint application. |
| [Ppsx](#Ppsx) | PPSX, Power Point Slide Show, file are created using Microsoft PowerPoint 2007 and above for Slide Show purpose. |
| [Odp](#Odp) | Files with ODP extension represent presentation file format used by OpenOffice.org in the OASISOpen standard. |
| [Otp](#Otp) | Files with .OTP extension represent presentation template files created by applications in OASIS OpenDocument standard format. |
| [Potx](#Potx) | Files with .POTX extension represent Microsoft PowerPoint template presentations that are created with Microsoft PowerPoint 2007 and above. |
| [Pot](#Pot) | Files with .POT extension represent Microsoft PowerPoint template files created by PowerPoint 97-2003 versions. |
| [Potm](#Potm) | Files with POTM extension are Microsoft PowerPoint template files with support for Macros. |
| [Pptm](#Pptm) | Files with PPTM extension are Macro-enabled Presentation files that are created with Microsoft PowerPoint 2007 or higher versions. |
| [Ppsm](#Ppsm) | Files with PPSM extension represent Macro-enabled Slide Show file format created with Microsoft PowerPoint 2007 or higher. |
| [Fodp](#Fodp) | FODP 확장자를 가진 파일은 OpenDocument Flat XML 프레젠테이션을 나타냅니다. |
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


PPT 확장자를 가진 파일은 슬라이드쇼로 표시되는 슬라이드 모음으로 구성된 PowerPoint 파일을 나타냅니다. 이는 Microsoft PowerPoint 97-2003에서 사용되는 바이너리 파일 형식을 지정합니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/presentation/ppt

### Pps {#Pps}
```
public static final PresentationFileType Pps
```


PPS, PowerPoint 슬라이드 쇼 파일은 슬라이드 쇼 용도로 Microsoft PowerPoint를 사용하여 생성됩니다. PPS 파일 읽기 및 생성은 Microsoft PowerPoint 97-2003에서 지원됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/presentation/pps

### Pptx {#Pptx}
```
public static final PresentationFileType Pptx
```


PPTX 확장자를 가진 파일은 널리 사용되는 Microsoft PowerPoint 애플리케이션으로 만든 프레젠테이션 파일입니다. 이전 버전인 바이너리 PPT와 달리 PPTX 형식은 Microsoft PowerPoint 오픈 XML 프레젠테이션 파일 형식을 기반으로 합니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/presentation/pptx

### Ppsx {#Ppsx}
```
public static final PresentationFileType Ppsx
```


PPSX, PowerPoint 슬라이드 쇼 파일은 슬라이드 쇼 용도로 Microsoft PowerPoint 2007 이상을 사용하여 생성됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/presentation/ppsx

### Odp {#Odp}
```
public static final PresentationFileType Odp
```


ODP 확장자를 가진 파일은 OASIS Open 표준에서 OpenOffice.org가 사용하는 프레젠테이션 파일 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/presentation/odp

### Otp {#Otp}
```
public static final PresentationFileType Otp
```


.OTP 확장자를 가진 파일은 OASIS OpenDocument 표준 형식으로 애플리케이션에서 만든 프레젠테이션 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/presentation/otp

### Potx {#Potx}
```
public static final PresentationFileType Potx
```


.POTX 확장자를 가진 파일은 Microsoft PowerPoint 2007 이상으로 만든 Microsoft PowerPoint 템플릿 프레젠테이션을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/presentation/potx

### Pot {#Pot}
```
public static final PresentationFileType Pot
```


.POT 확장자를 가진 파일은 PowerPoint 97-2003 버전으로 만든 Microsoft PowerPoint 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/presentation/pot

### Potm {#Potm}
```
public static final PresentationFileType Potm
```


POTM 확장자를 가진 파일은 매크로를 지원하는 Microsoft PowerPoint 템플릿 파일입니다. POTM 파일은 PowerPoint 2007 이상으로 생성되며 추가 프레젠테이션 파일을 만들 때 사용할 수 있는 기본 설정을 포함합니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/presentation/potm

### Pptm {#Pptm}
```
public static final PresentationFileType Pptm
```


PPTM 확장자를 가진 파일은 Microsoft PowerPoint 2007 이상 버전으로 만든 매크로 사용 프레젠테이션 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/presentation/pptm

### Ppsm {#Ppsm}
```
public static final PresentationFileType Ppsm
```


PPSM 확장자를 가진 파일은 Microsoft PowerPoint 2007 이상으로 만든 매크로 사용 슬라이드 쇼 파일 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/presentation/ppsm

### Fodp {#Fodp}
```
public static final PresentationFileType Fodp
```


FODP 확장자를 가진 파일은 OpenDocument Flat XML 프레젠테이션을 나타냅니다. 프레젠테이션 파일이 OpenDocument 형식으로 저장되지만, 표준 .ODP 파일이 사용하는 .ZIP 컨테이너 대신 플랫 XML 형식으로 저장됩니다.

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
