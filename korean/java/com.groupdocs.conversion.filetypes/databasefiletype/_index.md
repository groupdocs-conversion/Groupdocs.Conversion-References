---
title: "DatabaseFileType"
second_title: "GroupDocs.Conversion for Java API 레퍼런스"
description: "CAD(Computer Aided Design) 문서를 정의하며, 3D 그래픽 파일 형식에 사용되고 2D 또는 3D 디자인을 포함할 수 있습니다."
type: docs
weight: 12
url: /ko/java/com.groupdocs.conversion.filetypes/databasefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DatabaseFileType extends FileType implements Serializable
```

CAD 문서(Computer Aided Design)를 정의합니다. 이 문서는 3D 그래픽 파일 형식에 사용되며 2D 또는 3D 디자인을 포함할 수 있습니다.
다음 유형을 포함합니다:
[Nsf](../../com.groupdocs.conversion.filetypes/databasefiletype#Nsf),
[Log](../../com.groupdocs.conversion.filetypes/databasefiletype#Log),
[Sql](../../com.groupdocs.conversion.filetypes/databasefiletype#Sql),
CAD 형식에 대해 자세히 알아보려면 [here](../https://wiki.fileformat.com/cad)에서 확인하세요.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [DatabaseFileType()](#DatabaseFileType--) | 직렬화 생성자 |
|
## 필드

| 필드 | 설명 |
| --- | --- |
|  | [Nsf](#Nsf) | .nsf (Notes Storage Facility) 확장자를 가진 파일은 IBM Notes 소프트웨어에서 사용되는 데이터베이스 파일 형식이며, 이전에는 Lotus Notes로 알려졌습니다. |
|
|  | [Log](#Log) | .log 확장자를 가진 파일은 타임스탬프가 포함된 일반 텍스트 목록을 포함합니다. |
|
|  | [Sql](#Sql) | .sql 확장자를 가진 파일은 관계형 데이터베이스와 작업하기 위한 코드를 포함하는 Structured Query Language (SQL) 파일입니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
### DatabaseFileType() {#DatabaseFileType--}
```
public DatabaseFileType()
```


직렬화 생성자


### Nsf {#Nsf}
```
public static final DatabaseFileType Nsf
```


.nsf (Notes Storage Facility) 확장자를 가진 파일은 IBM Notes 소프트웨어에서 사용되는 데이터베이스 파일 형식이며, 이전에는 Lotus Notes로 알려졌습니다. 이 파일은 이메일, 약속, 문서, 양식 및 뷰와 같은 다양한 종류의 객체를 저장하기 위한 스키마를 정의합니다. 이 파일 형식에 대해 자세히 알아보려면 [here](../https://docs.fileformat.com/database/nsf)를 클릭하십시오.


### Log {#Log}
```
public static final DatabaseFileType Log
```


.log 확장자를 가진 파일은 타임스탬프가 포함된 일반 텍스트 목록을 포함합니다. 일반적으로 소프트웨어나 운영 체제에서 특정 활동 세부 정보를 기록하여 개발자나 사용자가 특정 시간대에 무슨 일이 있었는지 추적할 수 있도록 합니다. 이 파일 형식에 대해 자세히 알아보려면 [here](../https://docs.fileformat.com/database/log)를 클릭하십시오.


### Sql {#Sql}
```
public static final DatabaseFileType Sql
```


.sql 확장자를 가진 파일은 관계형 데이터베이스와 작업하기 위한 코드를 포함하는 Structured Query Language (SQL) 파일입니다. 이 파일은 데이터베이스에 대한 CRUD (Create, Read, Update, Delete) 작업을 수행하는 SQL 문을 작성하는 데 사용됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here](../https://docs.fileformat.com/database/sql)를 클릭하십시오.


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


소스 파일 유형에 대한 기본 로드 옵션을 준비했습니다


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
