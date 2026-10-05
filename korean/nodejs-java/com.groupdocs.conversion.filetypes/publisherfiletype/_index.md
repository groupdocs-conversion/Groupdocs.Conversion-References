---
title: "PublisherFileType"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "Publisher 문서를 정의합니다."
type: docs
weight: 24
url: /ko/nodejs-java/com.groupdocs.conversion.filetypes/publisherfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PublisherFileType extends FileType implements Serializable
```

Publisher 문서를 정의합니다. 다음 유형을 포함합니다: [Pub](../../com.groupdocs.conversion.filetypes/publisherfiletype\\#Pub), 글꼴 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/publisher
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PublisherFileType()](#PublisherFileType--) | 직렬화 생성자 |
## 필드

| 필드 | 설명 |
| --- | --- |
| [Pub](#Pub) | PUB 파일은 Microsoft Publisher 문서 파일 형식입니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PublisherFileType() {#PublisherFileType--}
```
public PublisherFileType()
```


직렬화 생성자

### Pub {#Pub}
```
public static final PublisherFileType Pub
```


PUB 파일은 Microsoft Publisher 문서 파일 형식입니다. 이 파일은 뉴스레터, 전단지, 브로셔, 엽서 등 다양한 디자인 레이아웃 문서를 만드는 데 사용됩니다. PUB 파일은 텍스트, 래스터 및 벡터 이미지를 포함할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/publisher/pub/

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


소스 파일 유형에 대한 기본 로드 옵션을 준비했습니다.

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
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
