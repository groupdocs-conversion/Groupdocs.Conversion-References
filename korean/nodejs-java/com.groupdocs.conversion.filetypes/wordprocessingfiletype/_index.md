---
title: "WordProcessingFileType"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "일반 텍스트 또는 서식 있는 텍스트 형식으로 사용자 정보를 포함하는 Word Processing 파일을 정의합니다."
type: docs
weight: 28
url: /ko/nodejs-java/com.groupdocs.conversion.filetypes/wordprocessingfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class WordProcessingFileType extends FileType implements Serializable
```

워드 프로세싱 파일을 정의하며, 사용자 정보가 일반 텍스트 또는 리치 텍스트 형식으로 포함됩니다. 일반 텍스트 파일 형식은 서식이 없는 텍스트이며 글꼴이나 페이지 설정 등을 적용할 수 없습니다. 반면 리치 텍스트 파일 형식은 글꼴 유형 설정, 스타일(굵게, 기울임, 밑줄 등), 페이지 여백, 제목, 글머리표 및 번호 매기기 등 여러 서식 옵션을 허용합니다. 다음 파일 유형을 포함합니다: [Doc](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Doc), [Docm](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Docm), [Docx](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Docx), [Dot](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Dot), [Dotm](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Dotm), [Dotx](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Dotx), [Odt](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Odt), [Ott](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Ott), [Rtf](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Rtf), [Txt](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Txt), [Md](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Md), 워드 프로세싱 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/word-processing
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [WordProcessingFileType()](#WordProcessingFileType--) | 직렬화 생성자 |
## 필드

| 필드 | 설명 |
| --- | --- |
| [Doc](#Doc) | .doc 확장자를 가진 파일은 Microsoft Word 또는 기타 워드 프로세서에서 생성된 이진 파일 형식의 문서를 나타냅니다. |
| [Docm](#Docm) | DOCM 파일은 매크로 실행 기능을 갖춘 Microsoft Word 2007 이상에서 생성된 문서입니다. |
| [Docx](#Docx) | DOCX는 Microsoft Word 문서에 널리 알려진 형식입니다. |
| [Dot](#Dot) | .DOT 확장자를 가진 파일은 추가 DOC 또는 DOCX 파일 생성을 위해 미리 서식이 지정된 설정을 가진 Microsoft Word 템플릿 파일입니다. |
| [Dotm](#Dotm) | DOTM 확장자를 가진 파일은 Microsoft Word 2007 이상에서 만든 템플릿 파일을 나타냅니다. |
| [Dotx](#Dotx) | DOTX 확장자를 가진 파일은 추가 DOCX 파일 생성을 위해 미리 서식이 지정된 설정을 가진 Microsoft Word 템플릿 파일입니다. |
| [Rtf](#Rtf) | Microsoft에서 도입하고 문서화한 리치 텍스트 포맷(RTF)은 애플리케이션 내에서 사용하기 위한 서식이 적용된 텍스트와 그래픽을 인코딩하는 방법을 나타냅니다. |
| [Odt](#Odt) | ODT 파일은 OpenDocument 텍스트 파일 형식을 기반으로 하는 워드 프로세싱 애플리케이션으로 만든 문서 유형입니다. |
| [Ott](#Ott) | OTT 확장자를 가진 파일은 OASIS의 OpenDocument 표준 형식을 준수하는 애플리케이션에서 생성된 템플릿 문서를 나타냅니다. |
| [Txt](#Txt) | .TXT 확장자를 가진 파일은 줄 형태의 일반 텍스트를 포함하는 텍스트 문서를 나타냅니다. |
| [Md](#Md) | Markdown 언어 방언으로 만든 텍스트 파일은 .MD 또는 .MARKDOWN 파일 확장자로 저장됩니다. |
| [Ml](#Ml) | Ml 파일 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### WordProcessingFileType() {#WordProcessingFileType--}
```
public WordProcessingFileType()
```


직렬화 생성자

### Doc {#Doc}
```
public static final WordProcessingFileType Doc
```


.doc 확장자를 가진 파일은 Microsoft Word 또는 기타 워드 프로세서에서 생성된 이진 파일 형식의 문서를 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/word-processing/doc

### Docm {#Docm}
```
public static final WordProcessingFileType Docm
```


DOCM 파일은 매크로 실행 기능을 갖춘 Microsoft Word 2007 이상에서 생성된 문서입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/word-processing/docm

### Docx {#Docx}
```
public static final WordProcessingFileType Docx
```


DOCX는 Microsoft Word 문서에 널리 알려진 형식입니다. 2007년 Microsoft Office 2007 출시와 함께 도입된 이 새로운 문서 형식의 구조는 기존의 순수 이진 형식에서 XML과 이진 파일의 조합으로 변경되었습니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/word-processing/docx

### Dot {#Dot}
```
public static final WordProcessingFileType Dot
```


.DOT 확장자를 가진 파일은 추가 DOC 또는 DOCX 파일 생성을 위해 미리 서식이 지정된 설정을 가진 Microsoft Word 템플릿 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/word-processing/dot

### Dotm {#Dotm}
```
public static final WordProcessingFileType Dotm
```


DOTM 확장자를 가진 파일은 Microsoft Word 2007 이상에서 만든 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/word-processing/dotm

### Dotx {#Dotx}
```
public static final WordProcessingFileType Dotx
```


DOTX 확장자를 가진 파일은 추가 DOCX 파일 생성을 위해 미리 서식이 지정된 설정을 가진 Microsoft Word 템플릿 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/word-processing/dotx

### Rtf {#Rtf}
```
public static final WordProcessingFileType Rtf
```


Microsoft에서 도입하고 문서화한 Rich Text Format (RTF)은 애플리케이션 내에서 사용하기 위해 서식이 지정된 텍스트와 그래픽을 인코딩하는 방법을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기][].


[here]: https://wiki.fileformat.com/word-processing/rtf

### Odt {#Odt}
```
public static final WordProcessingFileType Odt
```


ODT 파일은 OpenDocument Text File 형식을 기반으로 하는 워드 프로세싱 애플리케이션으로 만든 문서 유형입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기][].


[here]: https://wiki.fileformat.com/word-processing/odt

### Ott {#Ott}
```
public static final WordProcessingFileType Ott
```


OTT 확장자를 가진 파일은 OASIS의 OpenDocument 표준 형식을 준수하는 애플리케이션에서 생성된 템플릿 문서를 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기][].


[here]: https://wiki.fileformat.com/word-processing/ott

### Txt {#Txt}
```
public static final WordProcessingFileType Txt
```


.TXT 확장자를 가진 파일은 줄 형태의 일반 텍스트를 포함하는 텍스트 문서를 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기][].


[here]: https://wiki.fileformat.com/word-processing/txt

### Md {#Md}
```
public static final WordProcessingFileType Md
```


Markdown 언어 방언으로 만든 텍스트 파일은 .MD 또는 .MARKDOWN 파일 확장자로 저장됩니다. MD 파일은 Markdown 언어를 사용한 일반 텍스트 형식으로 저장되며, 여기에는 들여쓰기, 표 서식, 글꼴 및 헤더와 같은 텍스트 서식을 정의하는 인라인 텍스트 기호가 포함됩니다. 이 파일 형식에 대해 자세히 알아보려면 [여기][].


[here]: https://wiki.fileformat.com/word-processing/md

### Ml {#Ml}
```
public static final WordProcessingFileType Ml
```


Ml 파일

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


소스 파일 유형에 대한 기본 로드 옵션을 준비했습니다.

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions<WordProcessingFileType> getConvertOptions()
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
