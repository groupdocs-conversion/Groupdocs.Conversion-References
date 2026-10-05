---
title: "ProjectManagementFileType"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "Microsoft Project, Primavera P6 등과 같은 프로젝트 관리 소프트웨어에서 생성되는 프로젝트 파일 형식을 정의합니다."
type: docs
weight: 23
url: /ko/nodejs-java/com.groupdocs.conversion.filetypes/projectmanagementfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public final class ProjectManagementFileType extends FileType
```

Microsoft Project, Primavera P6 등과 같은 프로젝트 관리 소프트웨어에서 생성되는 프로젝트 파일 형식을 정의합니다. 프로젝트 파일은 작업, 리소스 및 일정이 모여 제품이나 서비스 형태의 측정 가능한 결과를 얻기 위한 컬렉션입니다. 프로젝트 관리 문서에는 다음 파일 형식이 포함됩니다: [Mpp](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype\\#Mpp), [Mpt](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype\\#Mpt), [Mpx](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype\\#Mpx). 프로젝트 관리 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/project-management
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ProjectManagementFileType()](#ProjectManagementFileType--) | 직렬화 생성자 |
## 필드

| 필드 | 설명 |
| --- | --- |
| [Mpt](#Mpt) | Microsoft Project 템플릿 파일은 .MPP 파일을 만들기 위한 기본 정보와 구조, 문서 설정을 포함합니다. |
| [Mpp](#Mpp) | MPP는 프로젝트 관리와 관련된 정보를 통합된 방식으로 저장하는 Microsoft Project 데이터 파일입니다. |
| [Mpx](#Mpx) | Microsoft Exchange 파일 형식은 Microsoft Project (MSP)와 Primavera Project Planner, Sciforma, Timerline Precision Estimating 등 MPX 파일 형식을 지원하는 다른 애플리케이션 간에 프로젝트 정보를 전송하기 위한 ASCII 파일 형식입니다. |
| [Xer](#Xer) | XER 파일 형식은 Primavera P6 프로젝트 계획 및 관리 애플리케이션에서 사용하는 독점 프로젝트 파일 형식입니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### ProjectManagementFileType() {#ProjectManagementFileType--}
```
public ProjectManagementFileType()
```


직렬화 생성자

### Mpt {#Mpt}
```
public static final ProjectManagementFileType Mpt
```


Microsoft Project 템플릿 파일은 .MPP 파일을 만들기 위한 기본 정보와 구조, 문서 설정을 포함합니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/project-management/mpt

### Mpp {#Mpp}
```
public static final ProjectManagementFileType Mpp
```


MPP는 프로젝트 관리와 관련된 정보를 통합된 방식으로 저장하는 Microsoft Project 데이터 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/project-management/mpp

### Mpx {#Mpx}
```
public static final ProjectManagementFileType Mpx
```


Microsoft Exchange 파일 형식은 Microsoft Project (MSP)와 Primavera Project Planner, Sciforma, Timerline Precision Estimating 등 MPX 파일 형식을 지원하는 다른 애플리케이션 간에 프로젝트 정보를 전송하기 위한 ASCII 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/project-management/mpx

### Xer {#Xer}
```
public static final ProjectManagementFileType Xer
```


XER 파일 형식은 Primavera P6 프로젝트 계획 및 관리 애플리케이션에서 사용하는 독점 프로젝트 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/project-management/xer

### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


파일 유형에 대한 기본 변환 옵션을 준비했습니다.

**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
