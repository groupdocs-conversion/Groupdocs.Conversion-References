---
title: "NoteFileType"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يحدد صيغ تدوين الملاحظات."
type: docs
weight: 19
url: /ar/java/com.groupdocs.conversion.filetypes/notefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public final class NoteFileType extends FileType
```

يحدد صيغ تدوين الملاحظات. يتضمن أنواع الملفات التالية:
[One](../../com.groupdocs.conversion.filetypes/notefiletype#One).
تعرف على المزيد حول صيغ تدوين الملاحظات [هنا](../https://wiki.fileformat.com/note-taking).

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [NoteFileType()](#NoteFileType--) | منشئ التسلسل |
|
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [One](#One) | الملف الذي يحمل امتداد .ONE يتم إنشاؤه بواسطة تطبيق Microsoft OneNote. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
### NoteFileType() {#NoteFileType--}
```
public NoteFileType()
```


منشئ التسلسل


### One {#One}
```
public static final NoteFileType One
```


الملف الذي يحمل امتداد .ONE يتم إنشاؤه بواسطة تطبيق Microsoft OneNote. يتيح لك OneNote جمع المعلومات باستخدام التطبيق كما لو كنت تستخدم دفتر مسوداتك لتدوين الملاحظات.
تعرف على المزيد حول تنسيق الملف هذا [هنا](../https://wiki.fileformat.com/note-taking/one).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


إعداد خيارات التحميل الافتراضية لنوع ملف المصدر


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
