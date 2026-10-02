---
title: "EBookFileType"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يعرّف مستندات CAD (التصميم بمساعدة الحاسوب) التي تُستخدم لتنسيقات ملفات الرسوميات ثلاثية الأبعاد وقد تحتوي على تصاميم ثنائية أو ثلاثية الأبعاد."
type: docs
weight: 14
url: /ar/java/com.groupdocs.conversion.filetypes/ebookfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class EBookFileType extends FileType implements Serializable
```

يحدد مستندات CAD (التصميم المساعد بالحاسوب) التي تُستخدم لتنسيقات ملفات الرسومات ثلاثية الأبعاد وقد تحتوي على تصاميم ثنائية أو ثلاثية الأبعاد.
يتضمن الأنواع التالية:
[Epub](../../com.groupdocs.conversion.filetypes/ebookfiletype#Epub),
[Mobi](../../com.groupdocs.conversion.filetypes/ebookfiletype#Mobi),
[Azw3](../../com.groupdocs.conversion.filetypes/ebookfiletype#Azw3),
Learn more about CAD formats [here](../https://wiki.fileformat.com/cad).

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [EBookFileType()](#EBookFileType--) | منشئ التسلسل |
|
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Epub](#Epub) | امتداد EPUB هو تنسيق ملف كتاب إلكتروني يوفر تنسيق نشر رقمي قياسي للناشرين والمستهلكين. |
|
|  | [Mobi](#Mobi) | تنسيق ملف MOBI هو أحد أكثر تنسيقات الكتب الإلكترونية استخدامًا. |
|
|  | [Azw3](#Azw3) | AZW3، المعروف أيضًا باسم Kindle Format 8 (KF8)، هو النسخة المعدلة من تنسيق ملف الكتاب الإلكتروني AZW الذي تم تطويره لأجهزة Amazon Kindle. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### EBookFileType() {#EBookFileType--}
```
public EBookFileType()
```


منشئ التسلسل


### Epub {#Epub}
```
public static final EBookFileType Epub
```


امتداد EPUB هو تنسيق ملف كتاب إلكتروني يوفر تنسيق نشر رقمي قياسي للناشرين والمستهلكين. أصبح هذا التنسيق شائعًا إلى درجة أنه مدعوم من قبل العديد من القارئات الإلكترونية وتطبيقات البرمجيات. تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/ebook/epub).


### Mobi {#Mobi}
```
public static final EBookFileType Mobi
```


تنسيق ملف MOBI هو أحد أكثر تنسيقات الكتب الإلكترونية استخدامًا. هذا التنسيق هو تحسين لتنسيق OEB (Open Ebook Format) القديم وكان يُستخدم كتنسيق مملوك لبرنامج Mobipocket Reader. تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/ebook/mobi).


### Azw3 {#Azw3}
```
public static final EBookFileType Azw3
```


AZW3، المعروف أيضًا باسم Kindle Format 8 (KF8)، هو النسخة المعدلة من تنسيق ملف الكتاب الإلكتروني AZW الذي تم تطويره لأجهزة Amazon Kindle. هذا التنسيق هو تحسين لملفات AZW القديمة ويُستخدم فقط على أجهزة Kindle Fire مع الحفاظ على التوافق العكسي مع تنسيقات الملفات الأصلية أي MOBI و AZW. تعرف على المزيد حول هذا التنسيق [هنا](../https://docs.fileformat.com/ebook/azw3/).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


إعداد خيارات التحميل الافتراضية لنوع ملف المصدر


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


إعداد خيارات التحويل الافتراضية لنوع الملف


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
