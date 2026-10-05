---
title: "NoteFileType"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "노트 작성 형식을 정의합니다."
type: docs
weight: 19
url: /ko/nodejs-java/com.groupdocs.conversion.filetypes/notefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public final class NoteFileType extends FileType
```

노트 작성 형식을 정의합니다. 다음 파일 유형을 포함합니다: [One](../../com.groupdocs.conversion.filetypes/notefiletype\#One). 노트 작성 형식에 대해 자세히 알아보려면 [여기][].


[here]: https://wiki.fileformat.com/note-taking
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [NoteFileType()](#NoteFileType--) | 직렬화 생성자 |
## 필드

| 필드 | 설명 |
| --- | --- |
| [One](#One) | .ONE 확장자로 표시되는 파일은 Microsoft OneNote 애플리케이션에 의해 생성됩니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
### NoteFileType() {#NoteFileType--}
```
public NoteFileType()
```


직렬화 생성자

### One {#One}
```
public static final NoteFileType One
```


.ONE 확장자로 표시되는 파일은 Microsoft OneNote 애플리케이션에 의해 생성됩니다. OneNote를 사용하면 마치 초안 패드를 사용해 메모를 작성하는 것처럼 정보를 수집할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [여기][].


[here]: https://wiki.fileformat.com/note-taking/one

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


소스 파일 유형에 대한 기본 로드 옵션을 준비했습니다.

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
