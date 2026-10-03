---
title: "FontFileType"
second_title: "GroupDocs.Conversion for Java API 레퍼런스"
description: "글꼴 문서를 정의합니다."
type: docs
weight: 17
url: /ko/java/com.groupdocs.conversion.filetypes/fontfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class FontFileType extends FileType implements Serializable
```

글꼴 문서를 정의합니다.
다음 유형을 포함합니다:
[Ttf](../../com.groupdocs.conversion.filetypes/fontfiletype#Ttf),
[Eot](../../com.groupdocs.conversion.filetypes/fontfiletype#Eot),
[Otf](../../com.groupdocs.conversion.filetypes/fontfiletype#Otf),
[Cff](../../com.groupdocs.conversion.filetypes/fontfiletype#Cff),
[Type1](../../com.groupdocs.conversion.filetypes/fontfiletype#Type1),
[Woff](../../com.groupdocs.conversion.filetypes/fontfiletype#Woff),
[Woff2](../../com.groupdocs.conversion.filetypes/fontfiletype#Woff2),
폰 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/font).

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [FontFileType()](#FontFileType--) | 직렬화 생성자 |
|
## 필드

| 필드 | 설명 |
| --- | --- |
|  | [Ttf](#Ttf) | .ttf 확장자를 가진 파일은 TrueType 사양 기반의 폰트 기술을 사용한 폰트 파일을 나타냅니다. |
|
|  | [Eot](#Eot) | .eot 확장자를 가진 파일은 문서에 포함된 OpenType 글꼴입니다. |
|
|  | [Otf](#Otf) | .otf 확장자를 가진 파일은 OpenType 글꼴 형식을 의미합니다. |
|
|  | [Cff](#Cff) | .cff 확장자를 가진 파일은 Compact Font Format이며, PostScript Type 1 또는 CIDFont으로도 알려져 있습니다. |
|
|  | [Type1](#Type1) | Type 1 글꼴은 Adobe의 구식 기술로, PostScript를 사용할 수 있는 데스크톱 기반 출판 소프트웨어와 프린터에서 널리 사용되었습니다. |
|
|  | [Woff](#Woff) | .woff 확장자를 가진 파일은 Web Open Font Format (WOFF)을 기반으로 하는 웹 글꼴 파일입니다. |
|
|  | [Woff2](#Woff2) | .woff 확장자를 가진 파일은 Web Open Font Format (WOFF)을 기반으로 하는 웹 글꼴 파일입니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### FontFileType() {#FontFileType--}
```
public FontFileType()
```


직렬화 생성자


### Ttf {#Ttf}
```
public static final FontFileType Ttf
```


.ttf 확장자를 가진 파일은 TrueType 사양 글꼴 기술을 기반으로 하는 글꼴 파일을 나타냅니다. 처음에는 Apple Computer, Inc가 Mac OS용으로 설계·출시했으며, 이후 Microsoft가 Windows OS용으로 채택했습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](../https://docs.fileformat.com/font/ttf/)를 클릭하십시오.


### Eot {#Eot}
```
public static final FontFileType Eot
```


.eot 확장자를 가진 파일은 문서에 포함된 OpenType 글꼴입니다. 주로 웹 페이지와 같은 웹 파일에서 사용됩니다. Microsoft가 만들었으며 PowerPoint 프레젠테이션 .pps 파일을 포함한 Microsoft 제품에서 지원됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here](../https://docs.fileformat.com/font/eot/)를 클릭하십시오.


### Otf {#Otf}
```
public static final FontFileType Otf
```


.otf 확장자를 가진 파일은 OpenType 글꼴 형식을 의미합니다. OTF 글꼴 형식은 더 확장성이 높으며 디지털 타이포그래피를 위해 기존 TTF 형식의 기능을 확장합니다. Microsoft와 Adobe가 개발한 OTF는 PostScript와 TrueType 글꼴 형식의 기능을 결합합니다. 이 파일 형식에 대해 자세히 알아보려면 [here](../https://docs.fileformat.com/font/otf/)를 클릭하십시오.


### Cff {#Cff}
```
public static final FontFileType Cff
```


.cff 확장자를 가진 파일은 Compact Font Format이며, PostScript Type 1 또는 CIDFont으로도 알려져 있습니다. CFF는 여러 글꼴을 FontSet이라고 하는 단일 단위에 함께 저장하는 컨테이너 역할을 합니다. 이 파일 형식에 대해 자세히 알아보려면 [here](../https://docs.fileformat.com/font/cff/)를 클릭하십시오.


### Type1 {#Type1}
```
public static final FontFileType Type1
```


Type 1 글꼴은 Adobe의 구식 기술로, PostScript를 사용할 수 있는 데스크톱 기반 출판 소프트웨어와 프린터에서 널리 사용되었습니다. 많은 최신 플랫폼, 웹 브라우저 및 모바일 운영 체제에서는 Type 1 글꼴을 지원하지 않지만 일부 운영 체제에서는 여전히 지원됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here](../https://docs.fileformat.com/font/type1/)를 클릭하십시오.


### Woff {#Woff}
```
public static final FontFileType Woff
```


.woff 확장자를 가진 파일은 Web Open Font Format (WOFF)을 기반으로 하는 웹 글꼴 파일입니다. TrueType(.TTF) 또는 OpenType(.OTT) 글꼴 유형 중 하나를 기반으로 하는 형식별 압축 컨테이너를 가지고 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](../https://docs.fileformat.com/font/woff/)를 클릭하십시오.


### Woff2 {#Woff2}
```
public static final FontFileType Woff2
```


.woff 확장자를 가진 파일은 Web Open Font Format (WOFF)을 기반으로 하는 웹 글꼴 파일입니다. TrueType(.TTF) 또는 OpenType(.OTT) 글꼴 유형 중 하나를 기반으로 하는 형식별 압축 컨테이너를 가지고 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](../https://docs.fileformat.com/font/woff/)를 클릭하십시오.


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
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
