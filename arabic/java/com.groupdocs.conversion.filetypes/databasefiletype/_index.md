---
title: "DatabaseFileType"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يعرّف مستندات CAD (التصميم بمساعدة الحاسوب) التي تُستخدم لتنسيقات ملفات الرسوميات ثلاثية الأبعاد وقد تحتوي على تصاميم ثنائية أو ثلاثية الأبعاد."
type: docs
weight: 12
url: /ar/java/com.groupdocs.conversion.filetypes/databasefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DatabaseFileType extends FileType implements Serializable
```

يحدد مستندات CAD (التصميم المساعد بالحاسوب) التي تُستخدم لتنسيقات ملفات الرسومات ثلاثية الأبعاد وقد تحتوي على تصاميم ثنائية أو ثلاثية الأبعاد.
يتضمن الأنواع التالية:
[Nsf](../../com.groupdocs.conversion.filetypes/databasefiletype#Nsf),
[Log](../../com.groupdocs.conversion.filetypes/databasefiletype#Log),
[Sql](../../com.groupdocs.conversion.filetypes/databasefiletype#Sql),
Learn more about CAD formats [here](../https://wiki.fileformat.com/cad).

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [DatabaseFileType()](#DatabaseFileType--) | منشئ التسلسل |
|
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Nsf](#Nsf) | ملف بامتداد .nsf (Notes Storage Facility) هو تنسيق ملف قاعدة بيانات يستخدمه برنامج IBM Notes، والذي كان يُعرف سابقًا باسم Lotus Notes. |
|
|  | [Log](#Log) | ملف بامتداد .log يحتوي على قائمة نصية عادية مع طابع زمني. |
|
|  | [Sql](#Sql) | ملف بامتداد .sql هو ملف Structured Query Language (SQL) يحتوي على شفرة للعمل مع قواعد البيانات العلائقية. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
### DatabaseFileType() {#DatabaseFileType--}
```
public DatabaseFileType()
```


منشئ التسلسل


### Nsf {#Nsf}
```
public static final DatabaseFileType Nsf
```


ملف بامتداد .nsf (Notes Storage Facility) هو تنسيق ملف قاعدة بيانات يستخدمه برنامج IBM Notes، والذي كان يُعرف سابقًا باسم Lotus Notes. يحدد المخطط لتخزين أنواع مختلفة من الكائنات مثل الرسائل الإلكترونية، المواعيد، المستندات، النماذج والعروض. تعرف على المزيد حول هذا التنسيق [هنا](../https://docs.fileformat.com/database/nsf).


### Log {#Log}
```
public static final DatabaseFileType Log
```


ملف بامتداد .log يحتوي على قائمة نصية عادية مع طابع زمني. عادةً ما يتم تسجيل تفاصيل نشاط معينة بواسطة البرامج أو أنظمة التشغيل لمساعدة المطورين أو المستخدمين على تتبع ما كان يحدث خلال فترة زمنية معينة. تعرف على المزيد حول هذا التنسيق [هنا](../https://docs.fileformat.com/database/log).


### Sql {#Sql}
```
public static final DatabaseFileType Sql
```


ملف بامتداد .sql هو ملف Structured Query Language (SQL) يحتوي على شفرة للعمل مع قواعد البيانات العلائقية. يُستخدم لكتابة عبارات SQL لعمليات CRUD (إنشاء، قراءة، تحديث، حذف) على قواعد البيانات. تعرف على المزيد حول هذا التنسيق [هنا](../https://docs.fileformat.com/database/sql).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


إعداد خيارات التحميل الافتراضية لنوع ملف المصدر


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
