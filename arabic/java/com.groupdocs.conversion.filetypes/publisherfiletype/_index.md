---
title: "PublisherFileType"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يحدد مستندات Publisher."
type: docs
weight: 24
url: /ar/java/com.groupdocs.conversion.filetypes/publisherfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PublisherFileType extends FileType implements Serializable
```

يحدد مستندات Publisher.
يتضمن الأنواع التالية:
[Pub](../../com.groupdocs.conversion.filetypes/publisherfiletype#Pub),
تعرف على المزيد حول تنسيقات الخطوط [هنا](../https://wiki.fileformat.com/publisher).

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [PublisherFileType()](#PublisherFileType--) | منشئ التسلسل |
|
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Pub](#Pub) | ملف PUB هو تنسيق مستند Microsoft Publisher. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PublisherFileType() {#PublisherFileType--}
```
public PublisherFileType()
```


منشئ التسلسل


### Pub {#Pub}
```
public static final PublisherFileType Pub
```


ملف PUB هو تنسيق مستند Microsoft Publisher. يُستخدم لإنشاء عدة أنواع من مستندات تصميم التخطيط مثل النشرات الإخبارية، والنشرات، والكتيبات، وبطاقات البريد، وغيرها. يمكن لملفات PUB أن تحتوي على نصوص، وصور نقطية ومتجهية. تعرف على المزيد حول هذا التنسيق [هنا](../https://docs.fileformat.com/publisher/pub/).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


إعداد خيارات التحميل الافتراضية لنوع ملف المصدر


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
