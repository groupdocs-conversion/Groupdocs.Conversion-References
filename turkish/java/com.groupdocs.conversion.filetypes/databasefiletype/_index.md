---
title: "DatabaseFileType"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "3B grafik dosya formatları için kullanılan ve 2D veya 3D tasarımlar içerebilen Bilgisayar Destekli Tasarım (CAD) belgelerini tanımlar."
type: docs
weight: 12
url: /tr/java/com.groupdocs.conversion.filetypes/databasefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DatabaseFileType extends FileType implements Serializable
```

CAD belgelerini (Computer Aided Design) tanımlar; bu belgeler 3D grafik dosya formatları için kullanılır ve 2D veya 3D tasarımlar içerebilir.
Aşağıdaki türleri içerir:
[Nsf](../../com.groupdocs.conversion.filetypes/databasefiletype#Nsf),
[Log](../../com.groupdocs.conversion.filetypes/databasefiletype#Log),
[Sql](../../com.groupdocs.conversion.filetypes/databasefiletype#Sql),
CAD formatları hakkında daha fazla bilgi edinin [here](../https://wiki.fileformat.com/cad).

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [DatabaseFileType()](#DatabaseFileType--) | Serileştirme yapıcısı |
|
## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [Nsf](#Nsf) | .nsf (Notes Storage Facility) uzantılı bir dosya, daha önce Lotus Notes olarak bilinen IBM Notes yazılımı tarafından kullanılan bir veritabanı dosya formatıdır. |
|
|  | [Log](#Log) | .log uzantılı bir dosya, zaman damgası içeren düz metin listesini içerir. |
|
|  | [Sql](#Sql) | .sql uzantılı bir dosya, ilişkisel veritabanlarıyla çalışmak için kod içeren Structured Query Language (SQL) dosyasıdır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
### DatabaseFileType() {#DatabaseFileType--}
```
public DatabaseFileType()
```


Serileştirme yapıcısı


### Nsf {#Nsf}
```
public static final DatabaseFileType Nsf
```


.nsf (Notes Storage Facility) uzantılı bir dosya, daha önce Lotus Notes olarak bilinen IBM Notes yazılımı tarafından kullanılan bir veritabanı dosya formatıdır. E‑postalar, randevular, belgeler, formlar ve görünümler gibi çeşitli nesne türlerini depolamak için şemayı tanımlar. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/database/nsf).


### Log {#Log}
```
public static final DatabaseFileType Log
```


.log uzantılı bir dosya, zaman damgası içeren düz metin listesini içerir. Genellikle, belirli bir zaman diliminde neler olduğunu izlemek için geliştiricilere veya kullanıcılara yardımcı olmak amacıyla yazılımlar veya işletim sistemleri tarafından aktivite detayları kaydedilir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/database/log).


### Sql {#Sql}
```
public static final DatabaseFileType Sql
```


.sql uzantılı bir dosya, ilişkisel veritabanlarıyla çalışmak için kod içeren Structured Query Language (SQL) dosyasıdır. Veritabanları üzerinde CRUD (Create, Read, Update, Delete) işlemleri için SQL ifadeleri yazmakta kullanılır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/database/sql).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Kaynak dosya türü için varsayılan yükleme seçenekleri hazırlandı


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
