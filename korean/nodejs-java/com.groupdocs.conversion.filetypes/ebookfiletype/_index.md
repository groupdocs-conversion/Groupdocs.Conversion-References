---
title: "EBookFileType"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "CAD 문서(Computer Aided Design)를 정의하며, 3D 그래픽 파일 형식에 사용되고 2D 또는 3D 디자인을 포함할 수 있습니다."
type: docs
weight: 14
url: /ko/nodejs-java/com.groupdocs.conversion.filetypes/ebookfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class EBookFileType extends FileType implements Serializable
```

CAD 문서(Computer Aided Design)를 정의하며, 3D 그래픽 파일 형식에 사용되고 2D 또는 3D 디자인을 포함할 수 있습니다. 다음 유형을 포함합니다: [Epub](../../com.groupdocs.conversion.filetypes/ebookfiletype\#Epub), [Mobi](../../com.groupdocs.conversion.filetypes/ebookfiletype\#Mobi), [Azw3](../../com.groupdocs.conversion.filetypes/ebookfiletype\#Azw3), CAD 형식에 대해 자세히 알아보려면 [여기][].


[here]: https://wiki.fileformat.com/cad
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [EBookFileType()](#EBookFileType--) | 직렬화 생성자 |
## 필드

| 필드 | 설명 |
| --- | --- |
| [Epub](#Epub) | EPUB 확장자는 출판사와 소비자를 위한 표준 디지털 출판 형식을 제공하는 전자책 파일 형식입니다. |
| [Mobi](#Mobi) | MOBI 파일 형식은 가장 널리 사용되는 전자책 파일 형식 중 하나입니다. |
| [Azw3](#Azw3) | AZW3는 Kindle Format 8(KF8)이라고도 하며, Amazon Kindle 기기를 위해 개발된 AZW 전자책 디지털 파일 형식의 수정 버전입니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### EBookFileType() {#EBookFileType--}
```
public EBookFileType()
```


직렬화 생성자

### Epub {#Epub}
```
public static final EBookFileType Epub
```


EPUB 확장자는 출판사와 소비자를 위한 표준 디지털 출판 형식을 제공하는 전자책 파일 형식입니다. 이 형식은 이제 매우 일반화되어 많은 전자책 리더와 소프트웨어 애플리케이션에서 지원됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/ebook/epub

### Mobi {#Mobi}
```
public static final EBookFileType Mobi
```


MOBI 파일 형식은 가장 널리 사용되는 전자책 파일 형식 중 하나입니다. 이 형식은 기존 OEB(Open Ebook Format) 형식을 개선한 것이며 Mobipocket Reader의 독점 형식으로 사용되었습니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/ebook/mobi

### Azw3 {#Azw3}
```
public static final EBookFileType Azw3
```


AZW3는 Kindle Format 8(KF8)이라고도 하며, Amazon Kindle 기기를 위해 개발된 AZW 전자책 디지털 파일 형식의 수정 버전입니다. 이 형식은 이전 AZW 파일을 개선한 것이며 Kindle Fire 기기에서만 사용되며, 이전 파일 형식인 MOBI와 AZW와의 하위 호환성을 제공합니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/ebook/azw3/

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
