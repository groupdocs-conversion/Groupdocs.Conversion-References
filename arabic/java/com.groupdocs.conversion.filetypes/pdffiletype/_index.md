---
title: "PdfFileType"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يحدد مستندات PDF."
type: docs
weight: 21
url: /ar/java/com.groupdocs.conversion.filetypes/pdffiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfFileType extends FileType implements Serializable
```

يحدد مستندات PDF. يتضمن أنواع الملفات التالية:
[Pdf](../../com.groupdocs.conversion.filetypes/pdffiletype#Pdf),

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [PdfFileType()](#PdfFileType--) | منشئ التسلسل |
|
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Pdf](#Pdf) | Portable Document Format (PDF) هو نوع من المستندات تم إنشاؤه بواسطة Adobe في التسعينيات. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PdfFileType() {#PdfFileType--}
```
public PdfFileType()
```


منشئ التسلسل


### Pdf {#Pdf}
```
public static final PdfFileType Pdf
```


Portable Document Format (PDF) هو نوع من المستندات تم إنشاؤه بواسطة Adobe في التسعينيات. الهدف من هذا التنسيق هو تقديم معيار لتمثيل المستندات والمواد المرجعية الأخرى في تنسيق لا يعتمد على برنامج تطبيق، أو عتاد، أو نظام تشغيل.
تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/view/pdf).


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
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static final FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
