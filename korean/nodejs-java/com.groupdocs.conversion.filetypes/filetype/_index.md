---
title: "FileType"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "파일 유형 기본 클래스"
type: docs
weight: 16
url: /ko/nodejs-java/com.groupdocs.conversion.filetypes/filetype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration)
```
public class FileType extends Enumeration
```

파일 유형 기본 클래스
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FileType()](#FileType--) | 직렬화 생성자 |
## 필드

| 필드 | 설명 |
| --- | --- |
| [Unknown](#Unknown) | 알 수 없는 파일 유형 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | 파일 형식 |
| [getExtension()](#getExtension--) | 파일 확장자 |
| [getFamily()](#getFamily--) | 파일 계열 |
| [getDescription()](#getDescription--) | 파일 유형에 대한 설명 |
| [fromFilename(String fileName)](#fromFilename-java.lang.String-) | 지정된 fileName에 대한 FileType을 반환합니다 |
| [fromExtension(String fileExtension)](#fromExtension-java.lang.String-) | 제공된 fileExtension에 대한 FileType을 가져옵니다 |
| [fromStream(InputStream inputStream)](#fromStream-java.io.InputStream-) | 제공된 문서 스트림에 대한 FileType을 반환합니다 |
| [<T>getAllTypes(Class<T> typeOfT)](#-T-getAllTypes-java.lang.Class-T--) | 모든 열거값을 반환합니다. |
| [<T>getAllTypes(Class<T> typeOfT, FileType[] excluded)](#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType---) |  |
| [<T>getAllTypes(Class<T> typeOfT, FileType[][] excluded)](#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType--...-) |  |
| [toString()](#toString--) | 문자열 표현 |
| [getLoadOptions()](#getLoadOptions--) | 소스 파일 유형에 대한 기본 로드 옵션을 준비했습니다. |
| [getConvertOptions()](#getConvertOptions--) | 파일 유형에 대한 기본 변환 옵션을 준비했습니다. |
| [isObsolete()](#isObsolete--) |  |
| [equals(Enumeration other)](#equals-com.groupdocs.conversion.contracts.Enumeration-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
### FileType() {#FileType--}
```
public FileType()
```


직렬화 생성자

### Unknown {#Unknown}
```
public static final FileType Unknown
```


알 수 없는 파일 유형

### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


파일 형식

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


파일 확장자

**Returns:**
java.lang.String
### getFamily() {#getFamily--}
```
public String getFamily()
```


파일 계열

**Returns:**
java.lang.String - 파일 패밀리
### getDescription() {#getDescription--}
```
public final String getDescription()
```


파일 유형에 대한 설명

**Returns:**
java.lang.String - 설명
### fromFilename(String fileName) {#fromFilename-java.lang.String-}
```
public static FileType fromFilename(String fileName)
```


지정된 fileName에 대한 FileType을 반환합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String | 파일 이름 |

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - The file type of specified file name
### fromExtension(String fileExtension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String fileExtension)
```


제공된 fileExtension에 대한 FileType을 가져옵니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileExtension | java.lang.String | 파일 확장자 |

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - file type
### fromStream(InputStream inputStream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream inputStream)
```


제공된 문서 스트림에 대한 FileType을 반환합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 탐색될 TStream |

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - The file type of provided stream
### <T>getAllTypes(Class<T> typeOfT) {#-T-getAllTypes-java.lang.Class-T--}
```
public static List<FileType> <T>getAllTypes(Class<T> typeOfT)
```


모든 열거값을 반환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List<com.groupdocs.conversion.filetypes.FileType> - 파일 유형의 열거형

T : 열거된 객체 유형.
### <T>getAllTypes(Class<T> typeOfT, FileType[] excluded) {#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType---}
```
public static List<FileType> <T>getAllTypes(Class<T> typeOfT, FileType[] excluded)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
| excluded | [FileType\[\]](../../com.groupdocs.conversion.filetypes/filetype) |  |

**Returns:**
java.util.List<com.groupdocs.conversion.filetypes.FileType>
### <T>getAllTypes(Class<T> typeOfT, FileType[][] excluded) {#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType--...-}
```
public static List<FileType> <T>getAllTypes(Class<T> typeOfT, FileType[][] excluded)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
| excluded | [FileType\[\]](../../com.groupdocs.conversion.filetypes/filetype) |  |

**Returns:**
java.util.List<com.groupdocs.conversion.filetypes.FileType>
### toString() {#toString--}
```
public String toString()
```


문자열 표현

**Returns:**
java.lang.String - 파일 유형의 문자열 표현
### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


소스 파일 유형에 대한 기본 로드 옵션을 준비했습니다.

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions) - NULL if there is not file type specific load options
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


파일 유형에 대한 기본 변환 옵션을 준비했습니다.

**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions) - NULL if the conversion to the type not supported
### isObsolete() {#isObsolete--}
```
public boolean isObsolete()
```




**Returns:**
boolean
### equals(Enumeration other) {#equals-com.groupdocs.conversion.contracts.Enumeration-}
```
public boolean equals(Enumeration other)
```


두 객체 인스턴스가 같은지 여부를 판단합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| other | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) |  |

**Returns:**
boolean
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


두 객체 인스턴스가 같은지 여부를 판단합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```


기본 해시 함수로 사용됩니다.

**Returns:**
int
