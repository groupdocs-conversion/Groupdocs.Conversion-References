---
title: "DatabaseFileType"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "3D grafik dosya formatları için kullanılan ve 2D veya 3D tasarımlar içerebilen CAD (Computer Aided Design) belgelerini tanımlar."
type: docs
weight: 12
url: /tr/nodejs-java/com.groupdocs.conversion.filetypes/databasefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DatabaseFileType extends FileType implements Serializable
```

CAD belgelerini (Computer Aided Design) tanımlar; bu belgeler 3D grafik dosya formatları için kullanılır ve 2D veya 3D tasarımlar içerebilir. Aşağıdaki türleri içerir: [Nsf](../../com.groupdocs.conversion.filetypes/databasefiletype\#Nsf), [Log](../../com.groupdocs.conversion.filetypes/databasefiletype\#Log), [Sql](../../com.groupdocs.conversion.filetypes/databasefiletype\#Sql), CAD formatları hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/cad
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [DatabaseFileType()](#DatabaseFileType--) | Serileştirme yapıcısı |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Nsf](#Nsf) | .nsf (Notes Storage Facility) uzantılı bir dosya, IBM Notes yazılımı tarafından kullanılan, daha önce Lotus Notes olarak bilinen bir veritabanı dosya formatıdır. |
| [Log](#Log) | .log uzantılı bir dosya, zaman damgası içeren düz metin listesini içerir. |
| [Sql](#Sql) | .sql uzantılı bir dosya, ilişkisel veritabanlarıyla çalışmak için kod içeren Structured Query Language (SQL) dosyasıdır. |
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


.nsf (Notes Storage Facility) uzantılı bir dosya, IBM Notes yazılımı tarafından kullanılan, daha önce Lotus Notes olarak bilinen bir veritabanı dosya formatıdır. E-postalar, randevular, belgeler, formlar ve görünümler gibi farklı nesne türlerini depolamak için şemayı tanımlar. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/database/nsf

### Log {#Log}
```
public static final DatabaseFileType Log
```


.log uzantılı bir dosya, zaman damgası içeren düz metin listesini içerir. Genellikle, belirli etkinlik ayrıntıları, geliştiricilerin veya kullanıcıların belirli bir zaman diliminde neler olduğunu izlemelerine yardımcı olmak için yazılımlar veya işletim sistemleri tarafından kaydedilir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/database/log

### Sql {#Sql}
```
public static final DatabaseFileType Sql
```


.sql uzantılı bir dosya, ilişkisel veritabanlarıyla çalışmak için kod içeren Structured Query Language (SQL) dosyasıdır. Veritabanları üzerinde CRUD (Create, Read, Update, and Delete) işlemleri için SQL ifadeleri yazmak amacıyla kullanılır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/database/sql

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Kaynak dosya türü için varsayılan yükleme seçenekleri hazırlandı

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
