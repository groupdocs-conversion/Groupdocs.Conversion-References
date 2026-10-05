---
title: "WebFileType"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "Web 문서를 정의합니다."
type: docs
weight: 27
url: /ko/nodejs-java/com.groupdocs.conversion.filetypes/webfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class WebFileType extends FileType implements Serializable
```

웹 문서를 정의합니다. 다음 유형을 포함합니다: [Xml](../../com.groupdocs.conversion.filetypes/webfiletype\#Xml), [Json](../../com.groupdocs.conversion.filetypes/webfiletype\#Json), [Html](../../com.groupdocs.conversion.filetypes/webfiletype\#Html), [Htm](../../com.groupdocs.conversion.filetypes/webfiletype\#Htm), [Mht](../../com.groupdocs.conversion.filetypes/webfiletype\#Mht), [Mhtml](../../com.groupdocs.conversion.filetypes/webfiletype\#Mhtml), [Chm](../../com.groupdocs.conversion.filetypes/webfiletype\#Chm), 웹 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/web
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [WebFileType()](#WebFileType--) | 직렬화 생성자 |
## 필드

| 필드 | 설명 |
| --- | --- |
| [Xml](#Xml) | XML은 객체를 정의하기 위해 태그를 사용하는 방식은 다르지만 HTML과 유사한 Extensible Markup Language를 의미합니다. |
| [Json](#Json) | JSON (JavaScript Object Notation)은 데이터를 저장하고 전송하기 위해 사람이 읽을 수 있는 텍스트를 사용하는 데이터 공유를 위한 개방형 표준 파일 형식입니다. |
| [Html](#Html) | HTML (Hyper Text Markup Language)은 브라우저에서 표시되는 웹 페이지의 확장자입니다. |
| [Htm](#Htm) | HTM (Hyper Text Markup Language)은 브라우저에서 표시되는 웹 페이지의 확장자입니다. |
| [Mht](#Mht) | MHTML 확장자를 가진 파일은 다양한 애플리케이션에서 생성할 수 있는 웹 페이지 아카이브 형식을 나타냅니다. |
| [Mhtml](#Mhtml) | MHTML 확장자를 가진 파일은 다양한 애플리케이션에서 생성할 수 있는 웹 페이지 아카이브 형식을 나타냅니다. |
| [Chm](#Chm) | CHM 파일 형식은 HTML 페이지 모음으로 구성된 Microsoft HTML 도움말 파일을 나타냅니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### WebFileType() {#WebFileType--}
```
public WebFileType()
```


직렬화 생성자

### Xml {#Xml}
```
public static final WebFileType Xml
```


XML은 객체를 정의하기 위해 태그를 사용하는 방식은 다르지만 HTML과 유사한 Extensible Markup Language를 의미합니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/web/xml

### Json {#Json}
```
public static final WebFileType Json
```


JSON (JavaScript Object Notation)은 데이터를 저장하고 전송하기 위해 사람이 읽을 수 있는 텍스트를 사용하는 데이터 공유를 위한 개방형 표준 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/web/json

### Html {#Html}
```
public static final WebFileType Html
```


HTML (Hyper Text Markup Language)은 브라우저에서 표시되는 웹 페이지의 확장자입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/web/html

### Htm {#Htm}
```
public static final WebFileType Htm
```


HTM (Hyper Text Markup Language)은 브라우저에서 표시되는 웹 페이지의 확장자입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/web/html

### Mht {#Mht}
```
public static final WebFileType Mht
```


MHTML 확장자를 가진 파일은 다양한 애플리케이션에서 생성할 수 있는 웹 페이지 아카이브 형식을 나타냅니다. 이 형식은 웹 HTML 코드와 관련 리소스를 하나의 파일에 저장하기 때문에 아카이브 형식으로 알려져 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/web/mhtml

### Mhtml {#Mhtml}
```
public static final WebFileType Mhtml
```


MHTML 확장자를 가진 파일은 다양한 애플리케이션에서 생성할 수 있는 웹 페이지 아카이브 형식을 나타냅니다. 이 형식은 웹 HTML 코드와 관련 리소스를 하나의 파일에 저장하기 때문에 아카이브 형식으로 알려져 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/web/mhtml

### Chm {#Chm}
```
public static final WebFileType Chm
```


CHM 파일 형식은 HTML 페이지 모음으로 구성된 Microsoft HTML 도움말 파일을 나타냅니다. 이는 주제에 빠르게 접근하고 도움말 문서의 다양한 부분으로 이동할 수 있는 인덱스를 제공합니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/web/chm

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
