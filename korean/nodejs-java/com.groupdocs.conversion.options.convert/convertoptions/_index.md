---
title: "ConvertOptions"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "일반 변환 옵션 클래스."
type: docs
weight: 12
url: /ko/nodejs-java/com.groupdocs.conversion.options.convert/convertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions), java.lang.Cloneable
```
public abstract class ConvertOptions<TFileType> extends ValueObject implements Serializable, IConvertOptions, Cloneable
```

일반 변환 옵션 클래스.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFormat()](#getFormat--) | \{@inheritDoc\} |
| [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) | 입력 문서를 변환해야 하는 원하는 파일 형식. |
| [deepClone()](#deepClone--) | 현재 옵션 인스턴스를 복제합니다. |
| [getFormat_ConvertOptions_New()](#getFormat-ConvertOptions-New--) | 입력 문서를 변환해야 하는 원하는 파일 형식. |
| [setFormat_ConvertOptions_New(TFileType value)](#setFormat-ConvertOptions-New-TFileType-) | 입력 문서를 변환해야 하는 원하는 파일 형식. |
### getFormat() {#getFormat--}
```
public FileType getFormat()
```


입력 문서를 변환해야 하는 원하는 파일 형식을 가져옵니다.

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


입력 문서를 변환해야 하는 원하는 파일 형식.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


현재 옵션 인스턴스를 복제합니다.

**Returns:**
java.lang.Object -
### getFormat_ConvertOptions_New() {#getFormat-ConvertOptions-New--}
```
public final TFileType getFormat_ConvertOptions_New()
```


입력 문서를 변환해야 하는 원하는 파일 형식.

**Returns:**
TFileType
### setFormat_ConvertOptions_New(TFileType value) {#setFormat-ConvertOptions-New-TFileType-}
```
public final void setFormat_ConvertOptions_New(TFileType value)
```


입력 문서를 변환해야 하는 원하는 파일 형식.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | TFileType |  |

