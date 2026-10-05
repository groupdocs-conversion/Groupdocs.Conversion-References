---
title: "PossibleConversions"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "특정 소스 파일 형식에 대해 지원되는 변환 쌍을 매핑하는 것을 나타냅니다"
type: docs
weight: 13
url: /ko/nodejs-java/com.groupdocs.conversion.contracts/possibleconversions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public final class PossibleConversions extends ValueObject
```

특정 소스 파일 형식에 대해 지원되는 변환 쌍을 매핑하는 것을 나타냅니다
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PossibleConversions(FileType source)](#PossibleConversions-com.groupdocs.conversion.filetypes.FileType-) | 지정된 소스 파일 형식에 대한 가능한 변환 목록을 생성합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [NULL](#NULL) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) | 현재 유형에서 변환하는 데 사용할 수 있는 미리 정의된 로드 옵션. |
| [getAll()](#getAll--) | 모든 대상 파일 유형 및 기본/보조 플래그 |
| [getTargetConversion(FileType target)](#getTargetConversion-com.groupdocs.conversion.filetypes.FileType-) | 지정된 대상 파일 유형에 대한 대상 변환을 반환합니다. |
| [getTargetConversion(String extension)](#getTargetConversion-java.lang.String-) |  |
| [getPrimary()](#getPrimary--) | 기본 대상 파일 유형 |
| [getSecondary()](#getSecondary--) | 보조 대상 파일 유형 |
| [add(ConversionPair pair)](#add-com.groupdocs.conversion.contracts.ConversionPair-) | 변환 쌍 추가 |
| [forTarget(FileType target)](#forTarget-com.groupdocs.conversion.filetypes.FileType-) | 대상 파일 유형에 대한 현재 목록에서 변환 쌍 찾기 |
| [getSource()](#getSource--) | 소스 파일 형식 |
### PossibleConversions(FileType source) {#PossibleConversions-com.groupdocs.conversion.filetypes.FileType-}
```
public PossibleConversions(FileType source)
```


지정된 소스 파일 형식에 대한 가능한 변환 목록을 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | 소스 파일 유형 |

### NULL {#NULL}
```
public static final PossibleConversions NULL
```


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


현재 유형에서 변환하는 데 사용할 수 있는 미리 정의된 로드 옵션.

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions) - load options
### getAll() {#getAll--}
```
public Iterable<TargetConversion> getAll()
```


모든 대상 파일 유형 및 기본/보조 플래그

**Returns:**
java.lang.Iterable<com.groupdocs.conversion.contracts.TargetConversion> - [TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion)의 Iterable
### getTargetConversion(FileType target) {#getTargetConversion-com.groupdocs.conversion.filetypes.FileType-}
```
public TargetConversion getTargetConversion(FileType target)
```


지정된 대상 파일 유형에 대한 대상 변환을 반환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | 대상 파일 유형 |

**Returns:**
[TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion) - conversions
### getTargetConversion(String extension) {#getTargetConversion-java.lang.String-}
```
public TargetConversion getTargetConversion(String extension)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 확장자 | java.lang.String |  |

**Returns:**
[TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion)
### getPrimary() {#getPrimary--}
```
public Iterable<FileType> getPrimary()
```


기본 대상 파일 유형

**Returns:**
java.lang.Iterable<com.groupdocs.conversion.filetypes.FileType> - 주 대상 파일 유형
### getSecondary() {#getSecondary--}
```
public Iterable<FileType> getSecondary()
```


보조 대상 파일 유형

**Returns:**
java.lang.Iterable<com.groupdocs.conversion.filetypes.FileType> - 보조 대상 파일 유형
### add(ConversionPair pair) {#add-com.groupdocs.conversion.contracts.ConversionPair-}
```
public void add(ConversionPair pair)
```


변환 쌍 추가

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pair | [ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) | 변환 쌍 |

### forTarget(FileType target) {#forTarget-com.groupdocs.conversion.filetypes.FileType-}
```
public ConversionPair forTarget(FileType target)
```


대상 파일 유형에 대한 현재 목록에서 변환 쌍 찾기

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | 대상 파일 유형 |

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - conversion pair
### getSource() {#getSource--}
```
public FileType getSource()
```


소스 파일 형식

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - file formats
