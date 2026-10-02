---
title: "PageDescriptionLanguageFileType"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يحدد مستندات وصف الصفحة."
type: docs
weight: 20
url: /ar/java/com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PageDescriptionLanguageFileType extends FileType implements Serializable
```

يحدد مستندات وصف الصفحة.
يتضمن الأنواع التالية:
[Svg](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype#Svg),
[Eps](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype#Eps),
[Cgm](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype#Cgm),
[Xps](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype#Xps),
[Tex](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype#Tex),
[Ps](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype#Ps),
[Pcl](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype#Pcl),
[Oxps](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype#Oxps),

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [PageDescriptionLanguageFileType()](#PageDescriptionLanguageFileType--) | منشئ التسلسل |
|
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Svg](#Svg) | ملف SVG هو ملف رسومات متجهية قياسية يستخدم تنسيق نصي مبني على XML لوصف مظهر الصورة. |
|
|  | [Eps](#Eps) | الملفات ذات امتداد EPS تصف أساسًا برنامج لغة Encapsulated PostScript الذي يصف مظهر صفحة واحدة. |
|
|  | [Cgm](#Cgm) | Computer Graphics Metafile (CGM) هو تنسيق ملف مجاني، مستقل عن المنصة، ومعيار دولي لتخزين وتبادل الرسومات المتجهية (2D)، الرسومات النقطية، والنص. |
|
|  | [Xps](#Xps) | ملف XPS يمثل ملفات تخطيط الصفحات التي تستند إلى مواصفات XML Paper التي أنشأتها Microsoft. |
|
|  | [Tex](#Tex) | TeX هي لغة تتضمن ميزات برمجة بالإضافة إلى ميزات الترميز، وتُستخدم لتنسيق المستندات. |
|
|  | [Ps](#Ps) | PostScript (PS) هي لغة وصف صفحات عامة الاستخدام تُستخدم في مجال النشر المكتبي والإلكتروني. |
|
|  | [Pcl](#Pcl) | PCL هو اختصار لـ Printer Command Language وهي لغة وصف صفحات تم تقديمها من قبل Hewlett Packard (HP). |
|
|  | [Oxps](#Oxps) | تنسيق الملف OXPS يُعرف باسم Open XML Paper Specification. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PageDescriptionLanguageFileType() {#PageDescriptionLanguageFileType--}
```
public PageDescriptionLanguageFileType()
```


منشئ التسلسل


### Svg {#Svg}
```
public static final PageDescriptionLanguageFileType Svg
```


ملف SVG هو ملف Scalar Vector Graphics يستخدم تنسيق نص مبني على XML لوصف مظهر الصورة. تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/page-description-language/svg).


### Eps {#Eps}
```
public static final PageDescriptionLanguageFileType Eps
```


الملفات ذات الامتداد EPS تصف أساسًا برنامج لغة Encapsulated PostScript الذي يصف مظهر صفحة واحدة. تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/page-description-language/eps).


### Cgm {#Cgm}
```
public static final PageDescriptionLanguageFileType Cgm
```


Computer Graphics Metafile (CGM) هو تنسيق ملف ميتا مجاني، غير معتمد على منصة، معيار دولي لتخزين وتبادل الرسومات المتجهية (2D) والرسومات النقطية والنص. يستخدم CGM نهجًا موجهًا للكائنات والعديد من الوظائف لإنتاج الصور. تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/page-description-language/cgm).


### Xps {#Xps}
```
public static final PageDescriptionLanguageFileType Xps
```


ملف XPS يمثل ملفات تخطيط الصفحات المستندة إلى XML Paper Specifications التي أنشأتها Microsoft. تم تطوير هذا التنسيق من قبل Microsoft كبديل لتنسيق ملف EMF وهو مشابه لتنسيق PDF، لكنه يستخدم XML في التخطيط والمظهر ومعلومات الطباعة للوثيقة. تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/page-description-language/xps).


### Tex {#Tex}
```
public static final PageDescriptionLanguageFileType Tex
```


TeX هي لغة تشمل البرمجة بالإضافة إلى ميزات الترميز، وتُستخدم لتنسيق المستندات. تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/page-description-language/tex).


### Ps {#Ps}
```
public static final PageDescriptionLanguageFileType Ps
```


PostScript (PS) هي لغة وصف صفحات عامة الاستخدام تُستخدم في مجال النشر المكتبي والإلكتروني. التركيز الرئيسي لـ PostScript (PS) هو تسهيل التصميم الرسومي ثنائي الأبعاد. تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/page-description-language/ps).


### Pcl {#Pcl}
```
public static final PageDescriptionLanguageFileType Pcl
```


PCL هو اختصار لـ Printer Command Language وهي لغة وصف صفحات تم تقديمها من قبل Hewlett Packard (HP). تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/page-description-language/pcl).


### Oxps {#Oxps}
```
public static final PageDescriptionLanguageFileType Oxps
```


تنسيق الملف OXPS يُعرف باسم Open XML Paper Specification. إنه لغة وصف صفحات وتنسيق مستندات. Microsoft هي المطور لهذا التنسيق. تنسيق ملف OXPS مألوف جدًا لملفات PDF هذه. تعرف على المزيد حول هذا التنسيق [هنا](../https://docs.fileformat.com/page-description-language/oxps).


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
