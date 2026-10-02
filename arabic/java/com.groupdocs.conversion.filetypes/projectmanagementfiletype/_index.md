---
title: "ProjectManagementFileType"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يحدد تنسيقات ملفات المشروع التي يتم إنشاؤها بواسطة برامج إدارة المشاريع مثل Microsoft Project وPrimavera P6 وغيرها."
type: docs
weight: 23
url: /ar/java/com.groupdocs.conversion.filetypes/projectmanagementfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public final class ProjectManagementFileType extends FileType
```

يحدد تنسيقات ملفات المشروع التي يتم إنشاؤها بواسطة برامج إدارة المشاريع مثل Microsoft Project وPrimavera P6 وغيرها. ملف المشروع هو مجموعة من المهام والموارد وجدولتها للحصول على نتيجة قابلة للقياس على شكل منتج أو خدمة.
وثائق إدارة المشروع. تشمل أنواع الملفات التالية:
[Mpp](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype#Mpp),
[Mpt](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype#Mpt),
[Mpx](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype#Mpx).
تعرف على المزيد حول تنسيقات إدارة المشروع [هنا](../https://wiki.fileformat.com/project-management).

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [ProjectManagementFileType()](#ProjectManagementFileType--) | منشئ التسلسل |
|
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Mpt](#Mpt) | ملفات قالب Microsoft Project، تحتوي على معلومات أساسية وبنية بالإضافة إلى إعدادات المستند لإنشاء ملفات .MPP. |
|
|  | [Mpp](#Mpp) | MPP هو ملف بيانات Microsoft Project يخزن المعلومات المتعلقة بإدارة المشروع بطريقة متكاملة. |
|
|  | [Mpx](#Mpx) | Microsoft Exchange File Format هو تنسيق ملف ASCII لنقل معلومات المشروع بين Microsoft Project (MSP) وتطبيقات أخرى تدعم تنسيق ملف MPX مثل Primavera Project Planner وSciforma وTimerline Precision Estimating. |
|
|  | [Xer](#Xer) | تنسيق ملف XER هو تنسيق ملف مشروع مملوك يستخدمه تطبيق تخطيط وإدارة المشاريع Primavera P6. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### ProjectManagementFileType() {#ProjectManagementFileType--}
```
public ProjectManagementFileType()
```


منشئ التسلسل


### Mpt {#Mpt}
```
public static final ProjectManagementFileType Mpt
```


ملفات قالب Microsoft Project، تحتوي على معلومات أساسية وبنية بالإضافة إلى إعدادات المستند لإنشاء ملفات .MPP.
تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/project-management/mpt).


### Mpp {#Mpp}
```
public static final ProjectManagementFileType Mpp
```


MPP هو ملف بيانات Microsoft Project يخزن المعلومات المتعلقة بإدارة المشروع بطريقة متكاملة.
تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/project-management/mpp).


### Mpx {#Mpx}
```
public static final ProjectManagementFileType Mpx
```


Microsoft Exchange File Format هو تنسيق ملف ASCII لنقل معلومات المشروع بين Microsoft Project (MSP) وتطبيقات أخرى تدعم تنسيق ملف MPX مثل Primavera Project Planner وSciforma وTimerline Precision Estimating.
تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/project-management/mpx).


### Xer {#Xer}
```
public static final ProjectManagementFileType Xer
```


تنسيق ملف XER هو تنسيق ملف مشروع مملوك يستخدمه تطبيق تخطيط وإدارة المشاريع Primavera P6.
تعرف على المزيد حول هذا التنسيق [هنا](../https://docs.fileformat.com/project-management/xer).


### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


إعداد خيارات التحويل الافتراضية لنوع الملف


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
