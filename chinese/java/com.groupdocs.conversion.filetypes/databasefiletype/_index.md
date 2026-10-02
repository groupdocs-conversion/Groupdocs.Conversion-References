---
title: "DatabaseFileType"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "定义用于 3D 图形文件格式的 CAD（Computer Aided Design）文档，可能包含 2D 或 3D 设计。"
type: docs
weight: 12
url: /zh/java/com.groupdocs.conversion.filetypes/databasefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DatabaseFileType extends FileType implements Serializable
```

定义 CAD 文档（计算机辅助设计），用于 3D 图形文件格式，可能包含 2D 或 3D 设计。
包括以下类型：
[Nsf](../../com.groupdocs.conversion.filetypes/databasefiletype#Nsf),
[Log](../../com.groupdocs.conversion.filetypes/databasefiletype#Log),
[Sql](../../com.groupdocs.conversion.filetypes/databasefiletype#Sql),
了解更多关于 CAD 格式的信息，请点击[此处](../https://wiki.fileformat.com/cad)。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [DatabaseFileType()](#DatabaseFileType--) | 序列化构造函数 |
|
## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Nsf](#Nsf) | 带有 .nsf（Notes Storage Facility）扩展名的文件是 IBM Notes 软件使用的数据库文件格式，该软件以前称为 Lotus Notes。 |
|
|  | [Log](#Log) | 带有 .log 扩展名的文件包含带时间戳的纯文本列表。 |
|
|  | [Sql](#Sql) | 带有 .sql 扩展名的文件是结构化查询语言（SQL）文件，包含用于操作关系型数据库的代码。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
### DatabaseFileType() {#DatabaseFileType--}
```
public DatabaseFileType()
```


序列化构造函数


### Nsf {#Nsf}
```
public static final DatabaseFileType Nsf
```


带有 .nsf（Notes Storage Facility）扩展名的文件是 IBM Notes 软件使用的数据库文件格式，该软件以前称为 Lotus Notes。它定义了用于存储各种对象（如电子邮件、约会、文档、表单和视图）的模式。了解更多关于此文件格式的信息 [here](../https://docs.fileformat.com/database/nsf)。


### Log {#Log}
```
public static final DatabaseFileType Log
```


带有 .log 扩展名的文件包含带时间戳的纯文本列表。通常，软件或操作系统会记录某些活动细节，以帮助开发者或用户追踪特定时间段内发生的情况。了解更多关于此文件格式的信息 [here](../https://docs.fileformat.com/database/log)。


### Sql {#Sql}
```
public static final DatabaseFileType Sql
```


带有 .sql 扩展名的文件是结构化查询语言（SQL）文件，包含用于操作关系型数据库的代码。它用于编写用于对数据库进行增删改查（Create、Read、Update、Delete）操作的 SQL 语句。了解更多关于此文件格式的信息 [here](../https://docs.fileformat.com/database/sql)。


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


为源文件类型准备了默认加载选项


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
