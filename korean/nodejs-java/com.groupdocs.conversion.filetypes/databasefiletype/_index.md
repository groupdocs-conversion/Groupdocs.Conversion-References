---
title: "DatabaseFileType"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "CAD 문서(Computer Aided Design)를 정의하며, 3D 그래픽 파일 형식에 사용되고 2D 또는 3D 디자인을 포함할 수 있습니다."
type: docs
weight: 12
url: /ko/nodejs-java/com.groupdocs.conversion.filetypes/databasefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DatabaseFileType extends FileType implements Serializable
```

Defines CAD documents (Computer Aided Design) that are used for a 3D graphics file formats and may contain 2D or 3D designs. Includes the following types: [Nsf](../../com.groupdocs.conversion.filetypes/databasefiletype\#Nsf), [Log](../../com.groupdocs.conversion.filetypes/databasefiletype\#Log), [Sql](../../com.groupdocs.conversion.filetypes/databasefiletype\#Sql), Learn more about CAD formats [here][].


[here]: https://wiki.fileformat.com/cad
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [DatabaseFileType()](#DatabaseFileType--) | 직렬화 생성자 |
## 필드

| 필드 | 설명 |
| --- | --- |
| [Nsf](#Nsf) | A file with .nsf (Notes Storage Facility) extension is a database file format used by the IBM Notes software, which was previously known as Lotus Notes. |
| [Log](#Log) | A file with .log extension contains the list of plain text with timestamp. |
| [Sql](#Sql) | A file with .sql extension is a Structured Query Language (SQL) file that contains code to work with relational databases. |
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


A file with .nsf (Notes Storage Facility) extension is a database file format used by the IBM Notes software, which was previously known as Lotus Notes. It defines the schema to store different kind of objects such like emails, appointments, documents, forms and views. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/database/nsf

### Log {#Log}
```
public static final DatabaseFileType Log
```


A file with .log extension contains the list of plain text with timestamp. Usually, certain activity detail is logged by the softwares or operating systems to help the developers or users to track what was happening at a certain time period. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/database/log

### Sql {#Sql}
```
public static final DatabaseFileType Sql
```


A file with .sql extension is a Structured Query Language (SQL) file that contains code to work with relational databases. It is used to write SQL statements for CRUD (Create, Read, Update, and Delete) operations on databases. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/database/sql

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


소스 파일 유형에 대한 기본 로드 옵션을 준비했습니다.

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
