---
title: "CorruptOrDamagedFileException"
second_title: "GroupDocs.Conversion for Java API 레퍼런스"
description: "파일이 손상되었거나 깨졌을 때 발생하는 GroupDocs 예외"
type: docs
weight: 11
url: /ko/java/com.groupdocs.conversion.exceptions/corruptordamagedfileexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.groupdocs.conversion.exceptions.GroupDocsConversionException](../../com.groupdocs.conversion.exceptions/groupdocsconversionexception)
```
public final class CorruptOrDamagedFileException extends GroupDocsConversionException
```

파일이 손상되었거나 깨졌을 때 발생하는 GroupDocs 예외

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [CorruptOrDamagedFileException()](#CorruptOrDamagedFileException--) | 기본 생성자 |
|
|  | [CorruptOrDamagedFileException(FileType fileType)](#CorruptOrDamagedFileException-com.groupdocs.conversion.filetypes.FileType-) | FileType을 사용하여 예외 인스턴스를 생성합니다 |
|
|  | [CorruptOrDamagedFileException(String message)](#CorruptOrDamagedFileException-java.lang.String-) | 메시지를 사용하여 예외 인스턴스를 생성합니다 |
|
|  | [CorruptOrDamagedFileException(String message, RuntimeException exception)](#CorruptOrDamagedFileException-java.lang.String-java.lang.RuntimeException-) | 메시지를 포함한 예외 인스턴스를 생성하고 내부 예외를 전파합니다. |
|
### CorruptOrDamagedFileException() {#CorruptOrDamagedFileException--}
```
public CorruptOrDamagedFileException()
```


기본 생성자


### CorruptOrDamagedFileException(FileType fileType) {#CorruptOrDamagedFileException-com.groupdocs.conversion.filetypes.FileType-}
```
public CorruptOrDamagedFileException(FileType fileType)
```


FileType을 사용하여 예외 인스턴스를 생성합니다


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | 파일 유형 |
|

### CorruptOrDamagedFileException(String message) {#CorruptOrDamagedFileException-java.lang.String-}
```
public CorruptOrDamagedFileException(String message)
```


메시지를 사용하여 예외 인스턴스를 생성합니다


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 메시지 | java.lang.String | 메시지 |
|

### CorruptOrDamagedFileException(String message, RuntimeException exception) {#CorruptOrDamagedFileException-java.lang.String-java.lang.RuntimeException-}
```
public CorruptOrDamagedFileException(String message, RuntimeException exception)
```


메시지를 포함한 예외 인스턴스를 생성하고 내부 예외를 전파합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 메시지 | java.lang.String | 메시지 |
|
|  | 예외 | java.lang.RuntimeException | 내부 예외 |
|

