---
title: "ConversionPair"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "변환 쌍을 나타냅니다"
type: docs
weight: 10
url: /ko/nodejs-java/com.groupdocs.conversion.contracts/conversionpair/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class ConversionPair extends ValueObject
```

변환 쌍을 나타냅니다
## 필드

| 필드 | 설명 |
| --- | --- |
| [NULL](#NULL) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createPrimary(FileType source, FileType target)](#createPrimary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | 기본 변환 쌍을 생성합니다 |
| [createPrimary(List<? extends FileType> sources, List<? extends FileType> targets)](#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--) | 기본 변환 쌍들을 생성합니다 |
| [createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs)](#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--com.groupdocs.conversion.contracts.Pair-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType----) |  |
| [createSecondary(FileType source, FileType target)](#createSecondary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | 보조 변환 쌍을 생성합니다 |
| [createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets)](#createSecondary-java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--) | 보조 변환 쌍들을 생성합니다 |
| [getEqualityComponents()](#getEqualityComponents--) | 동등성 구성 요소 |
| [toString()](#toString--) | 변환 쌍 문자열 표현 |
| [getSource()](#getSource--) | 소스 파일 형식 |
| [getTarget()](#getTarget--) | 대상 파일 형식 |
| [isPrimary()](#isPrimary--) | 주 변환 쌍인지 여부 |
### NULL {#NULL}
```
public static final ConversionPair NULL
```


### createPrimary(FileType source, FileType target) {#createPrimary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public static ConversionPair createPrimary(FileType source, FileType target)
```


기본 변환 쌍을 생성합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | 소스 |
| target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | 대상 |

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - ConversionPair
### createPrimary(List<? extends FileType> sources, List<? extends FileType> targets) {#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--}
```
public static List<ConversionPair> createPrimary(List<? extends FileType> sources, List<? extends FileType> targets)
```


기본 변환 쌍들을 생성합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 소스 | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> | 소스 파일 유형 |
| 대상 | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> | 대상 파일 유형 |

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair> - 주 변환 쌍
### createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs) {#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--com.groupdocs.conversion.contracts.Pair-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType----}
```
public static List<ConversionPair> createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 소스 | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> |  |
| 대상 | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> |  |
| excludedPairs | com.groupdocs.conversion.contracts.Pair<com.groupdocs.conversion.filetypes.FileType,com.groupdocs.conversion.filetypes.FileType>[] |  |

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair>
### createSecondary(FileType source, FileType target) {#createSecondary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public static ConversionPair createSecondary(FileType source, FileType target)
```


보조 변환 쌍을 생성합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | 소스 파일 유형 |
| target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | 대상 파일 유형 |

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - secondary conversion pair
### createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets) {#createSecondary-java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--}
```
public static List<ConversionPair> createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets)
```


보조 변환 쌍들을 생성합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 소스 | java.lang.Iterable<? extends com.groupdocs.conversion.filetypes.FileType> | 소스 파일 유형 |
| 대상 | java.lang.Iterable<? extends com.groupdocs.conversion.filetypes.FileType> | 대상 파일 유형 |

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair> - 보조 변환 쌍
### getEqualityComponents() {#getEqualityComponents--}
```
public System.Collections.Generic.IGenericEnumerable getEqualityComponents()
```


동등성 구성 요소

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable - 동등성 구성 요소
### toString() {#toString--}
```
public String toString()
```


변환 쌍 문자열 표현

**Returns:**
java.lang.String - 문자열
### getSource() {#getSource--}
```
public FileType getSource()
```


소스 파일 형식

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - source file format
### getTarget() {#getTarget--}
```
public FileType getTarget()
```


대상 파일 형식

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - target file format
### isPrimary() {#isPrimary--}
```
public boolean isPrimary()
```


주 변환 쌍인지 여부

**Returns:**
boolean - 기본이면 true, 그렇지 않으면 false
