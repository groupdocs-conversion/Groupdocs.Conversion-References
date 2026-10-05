---
title: "FontFileType"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "글꼴 문서를 정의합니다."
type: docs
weight: 17
url: /ko/nodejs-java/com.groupdocs.conversion.filetypes/fontfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class FontFileType extends FileType implements Serializable
```

Font 문서를 정의합니다. 포함되는 유형은 다음과 같습니다: [Ttf](../../com.groupdocs.conversion.filetypes/fontfiletype\\#Ttf), [Eot](../../com.groupdocs.conversion.filetypes/fontfiletype\\#Eot), [Otf](../../com.groupdocs.conversion.filetypes/fontfiletype\\#Otf), [Cff](../../com.groupdocs.conversion.filetypes/fontfiletype\\#Cff), [Type1](../../com.groupdocs.conversion.filetypes/fontfiletype\\#Type1), [Woff](../../com.groupdocs.conversion.filetypes/fontfiletype\\#Woff), [Woff2](../../com.groupdocs.conversion.filetypes/fontfiletype\\#Woff2). Font 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/font
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FontFileType()](#FontFileType--) | 직렬화 생성자 |
## 필드

| 필드 | 설명 |
| --- | --- |
| [Ttf](#Ttf) | .ttf 확장자를 가진 파일은 TrueType 사양 기반의 폰트 파일을 나타냅니다. |
| [Eot](#Eot) | .eot 확장자를 가진 파일은 문서에 포함된 OpenType 폰트입니다. |
| [Otf](#Otf) | .otf 확장자를 가진 파일은 OpenType 폰트 형식을 나타냅니다. |
| [Cff](#Cff) | .cff 확장자를 가진 파일은 Compact Font Format이며, PostScript Type 1 또는 CIDFont라고도 합니다. |
| [Type1](#Type1) | Type 1 폰트는 Adobe에서 더 이상 지원하지 않는 기술로, 데스크톱 출판 소프트웨어와 PostScript를 사용할 수 있는 프린터에서 널리 사용되었습니다. |
| [Woff](#Woff) | .woff 확장자를 가진 파일은 Web Open Font Format (WOFF) 기반의 웹 폰트 파일입니다. |
| [Woff2](#Woff2) | .woff 확장자를 가진 파일은 Web Open Font Format (WOFF) 기반의 웹 폰트 파일입니다. |
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


.ttf 확장자를 가진 파일은 TrueType 사양 기반의 폰트 파일을 나타냅니다. 이 파일은 원래 Apple Computer, Inc가 Mac OS용으로 설계·출시했으며, 이후 Microsoft가 Windows OS용으로 채택했습니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/font/ttf/

### Eot {#Eot}
```
public static final FontFileType Eot
```


.eot 확장자를 가진 파일은 문서에 포함된 OpenType 폰트이며, 주로 웹 페이지와 같은 웹 파일에서 사용됩니다. 이 폰트는 Microsoft가 만들었으며 PowerPoint 프레젠테이션 .pps 파일을 포함한 Microsoft 제품에서 지원됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/font/eot/

### Otf {#Otf}
```
public static final FontFileType Otf
```


.otf 확장자를 가진 파일은 OpenType 폰트 형식을 나타냅니다. OTF 폰트 형식은 더 확장성이 높으며 TTF 형식의 기존 기능을 디지털 타이포그래피에 맞게 확장합니다. Microsoft와 Adobe가 개발한 OTF는 PostScript와 TrueType 폰트 형식의 기능을 결합합니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/font/otf/

### Cff {#Cff}
```
public static final FontFileType Cff
```


A file with .cff extension is a Compact Font Format and is also known as a PostScript Type 1, or CIDFont. CFF acts as a container to store multiple fonts together in a single unit known as a FontSet. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/font/cff/

### Type1 {#Type1}
```
public static final FontFileType Type1
```


Type 1 fonts is a deprecated Adobe technology which was widely used in the desktop based publishing software and printers that could use PostScript. Although Type 1 fonts are not supported in many modern platforms, web browsers and mobile operating systems, but these are still supported in some of the operating systems. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/font/type1/

### Woff {#Woff}
```
public static final FontFileType Woff
```


A file with .woff extension is a web font file based on the Web Open Font Format (WOFF). It has format-specific compressed container based on either TrueType (.TTF) or OpenType (.OTT) font types. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/font/woff/

### Woff2 {#Woff2}
```
public static final FontFileType Woff2
```


A file with .woff extension is a web font file based on the Web Open Font Format (WOFF). It has format-specific compressed container based on either TrueType (.TTF) or OpenType (.OTT) font types. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/font/woff/

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
