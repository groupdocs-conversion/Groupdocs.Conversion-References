---
title: "ConversionNotSupportedException"
second_title: "GroupDocs.Conversion for Java API 레퍼런스"
description: "소스 파일에서 대상 파일 유형으로의 변환이 지원되지 않을 때 발생하는 GroupDocs 예외"
type: docs
weight: 10
url: /ko/java/com.groupdocs.conversion.exceptions/conversionnotsupportedexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.groupdocs.conversion.exceptions.GroupDocsConversionException](../../com.groupdocs.conversion.exceptions/groupdocsconversionexception)
```
public final class ConversionNotSupportedException extends GroupDocsConversionException
```

소스 파일에서 대상 파일 유형으로의 변환이 지원되지 않을 때 발생하는 GroupDocs 예외

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [ConversionNotSupportedException()](#ConversionNotSupportedException--) | 기본 생성자 |
|
|  | [ConversionNotSupportedException(FileType source, FileType target)](#ConversionNotSupportedException-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | 소스 FileType과 대상 Filetype을 사용하여 예외 인스턴스를 생성합니다. |
|
|  | [ConversionNotSupportedException(String message)](#ConversionNotSupportedException-java.lang.String-) | 메시지를 사용하여 예외 인스턴스를 생성합니다 |
|
### ConversionNotSupportedException() {#ConversionNotSupportedException--}
```
public ConversionNotSupportedException()
```


기본 생성자


### ConversionNotSupportedException(FileType source, FileType target) {#ConversionNotSupportedException-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public ConversionNotSupportedException(FileType source, FileType target)
```


소스 FileType과 대상 Filetype을 사용하여 예외 인스턴스를 생성합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | 소스 파일 형식 |
|
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | 대상 파일 형식 |
|

### ConversionNotSupportedException(String message) {#ConversionNotSupportedException-java.lang.String-}
```
public ConversionNotSupportedException(String message)
```


메시지를 사용하여 예외 인스턴스를 생성합니다


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 메시지 | java.lang.String | 메시지 |
|

