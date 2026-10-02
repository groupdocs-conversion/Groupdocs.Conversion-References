---
title: "PossibleConversions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يمثل تخطيطًا للأزواج التحويلية المدعومة لتنسيق ملف المصدر المحدد"
type: docs
weight: 13
url: /ar/java/com.groupdocs.conversion.contracts/possibleconversions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public final class PossibleConversions extends ValueObject
```

يمثل تخطيطًا للأزواج التحويلية المدعومة لتنسيق ملف المصدر المحدد

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [PossibleConversions(FileType source)](#PossibleConversions-com.groupdocs.conversion.filetypes.FileType-) | إنشاء قائمة تحويل محتملة لتنسيق ملف المصدر المحدد |
|
## الحقول

| حقل | الوصف |
| --- | --- |
| [NULL](#NULL) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getLoadOptions()](#getLoadOptions--) | خيارات التحميل المحددة مسبقًا والتي يمكن استخدامها للتحويل من النوع الحالي |
|
|  | [getAll()](#getAll--) | جميع أنواع ملفات الهدف وعلم الأساسي/الثانوي |
|
|  | [getTargetConversion(FileType target)](#getTargetConversion-com.groupdocs.conversion.filetypes.FileType-) | إرجاع التحويل الهدف لنوع ملف الهدف المحدد |
|
| [getTargetConversion(String extension)](#getTargetConversion-java.lang.String-) |  |
|  | [getPrimary()](#getPrimary--) | أنواع ملفات الهدف الأساسية |
|
|  | [getSecondary()](#getSecondary--) | أنواع ملفات الهدف الثانوية |
|
|  | [add(ConversionPair pair)](#add-com.groupdocs.conversion.contracts.ConversionPair-) | إضافة زوج تحويل |
|
|  | [forTarget(FileType target)](#forTarget-com.groupdocs.conversion.filetypes.FileType-) | العثور على زوج تحويل في القائمة الحالية لنوع ملف الهدف |
|
|  | [getSource()](#getSource--) | تنسيقات ملفات المصدر |
|
### PossibleConversions(FileType source) {#PossibleConversions-com.groupdocs.conversion.filetypes.FileType-}
```
public PossibleConversions(FileType source)
```


إنشاء قائمة تحويل محتملة لتنسيق ملف المصدر المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | نوع ملف المصدر |
|

### NULL {#NULL}
```
public static final PossibleConversions NULL
```


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


خيارات التحميل المحددة مسبقًا والتي يمكن استخدامها للتحويل من النوع الحالي


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions) - load options

### getAll() {#getAll--}
```
public Iterable<TargetConversion> getAll()
```


جميع أنواع ملفات الهدف وعلم الأساسي/الثانوي


**Returns:**
java.lang.Iterable<com.groupdocs.conversion.contracts.TargetConversion> - قابل للتكرار لـ [TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion)

### getTargetConversion(FileType target) {#getTargetConversion-com.groupdocs.conversion.filetypes.FileType-}
```
public TargetConversion getTargetConversion(FileType target)
```


إرجاع التحويل الهدف لنوع ملف الهدف المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | نوع ملف الهدف |
|

**Returns:**
[TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion) - conversions

### getTargetConversion(String extension) {#getTargetConversion-java.lang.String-}
```
public TargetConversion getTargetConversion(String extension)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| امتداد | java.lang.String |  |

**Returns:**
[TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion)
### getPrimary() {#getPrimary--}
```
public Iterable<FileType> getPrimary()
```


أنواع ملفات الهدف الأساسية


**Returns:**
java.lang.Iterable<com.groupdocs.conversion.filetypes.FileType> - أنواع ملفات الهدف الأساسية

### getSecondary() {#getSecondary--}
```
public Iterable<FileType> getSecondary()
```


أنواع ملفات الهدف الثانوية


**Returns:**
java.lang.Iterable<com.groupdocs.conversion.filetypes.FileType> - أنواع ملفات الهدف الثانوية

### add(ConversionPair pair) {#add-com.groupdocs.conversion.contracts.ConversionPair-}
```
public void add(ConversionPair pair)
```


إضافة زوج تحويل


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | pair | [ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) | زوج التحويل |
|

### forTarget(FileType target) {#forTarget-com.groupdocs.conversion.filetypes.FileType-}
```
public ConversionPair forTarget(FileType target)
```


العثور على زوج تحويل في القائمة الحالية لنوع ملف الهدف


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | نوع ملف الهدف |
|

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - conversion pair

### getSource() {#getSource--}
```
public FileType getSource()
```


تنسيقات ملفات المصدر


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - file formats

