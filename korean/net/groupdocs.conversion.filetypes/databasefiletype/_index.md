---
title: DatabaseFileType
second_title: .NET API 참조용 GroupDocs.Conversion
description: 데이터베이스 문서를 정의합니다. 다음 파일 형식을 포함합니다. Nsf./databasefiletype/nsfLog./databasefiletype/logSql./databasefiletype/sql
type: docs
weight: 890
url: /ko/net/groupdocs.conversion.filetypes/databasefiletype/
---
## DatabaseFileType class

데이터베이스 문서를 정의합니다. 다음 파일 형식을 포함합니다. [`Nsf`](./nsf)[`Log`](./log)[`Sql`](./sql)

```csharp
public sealed class DatabaseFileType : FileType
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [DatabaseFileType](databasefiletype)() | 직렬화 생성자 |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | 파일 형식 description |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | 파일 확장자 |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | 파일 family |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | 파일 형식 |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 현재 개체를 다른 개체와 비교합니다. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | 두 개체 인스턴스가 같은지 여부를 결정합니다. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 두 개체 인스턴스가 같은지 여부를 결정합니다. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | 기본 해시 함수 역할을 합니다. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | 문자열 표현 |

## 필드

| 이름 | 설명 |
| --- | --- |
| static readonly [Log](../../groupdocs.conversion.filetypes/databasefiletype/log) | 확장자가 .log인 파일에는 타임스탬프가 있는 일반 텍스트 목록이 포함되어 있습니다. 일반적으로 개발자나 사용자가 특정 기간에 발생한 일을 추적할 수 있도록 소프트웨어 또는 운영 체제에서 특정 활동 세부 정보를 기록합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/database/log) . |
| static readonly [Nsf](../../groupdocs.conversion.filetypes/databasefiletype/nsf) | 확장자가 .nsf(Notes Storage Facility)인 파일은 이전에 Lotus Notes로 알려진 IBM Notes 소프트웨어에서 사용하는 데이터베이스 파일 형식입니다. 이메일, 약속, 문서, 양식 및 보기와 같은 다양한 종류의 개체를 저장하는 스키마를 정의합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/database/nsf) . |
| static readonly [Sql](../../groupdocs.conversion.filetypes/databasefiletype/sql) | 확장자가 .sql인 파일은 관계형 데이터베이스와 함께 작동하는 코드가 포함된 SQL(Structured Query Language) 파일입니다. 데이터베이스에서 CRUD(Create, Read, Update 및 Delete) 작업을 위한 SQL 문을 작성하는 데 사용됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/database/sql) . |

### 또한보십시오

* class [FileType](../filetype)
* 네임스페이스 [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* 집회 [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
