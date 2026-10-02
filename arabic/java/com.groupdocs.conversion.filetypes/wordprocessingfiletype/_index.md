---
title: "WordProcessingFileType"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يحدد ملفات معالجة النصوص التي تحتوي على معلومات المستخدم بنص عادي أو بصيغة نص منسق."
type: docs
weight: 28
url: /ar/java/com.groupdocs.conversion.filetypes/wordprocessingfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class WordProcessingFileType extends FileType implements Serializable
```

يحدد ملفات معالجة النصوص التي تحتوي على معلومات المستخدم بنص عادي أو تنسيق نص غني. يحتوي تنسيق الملف النصي العادي على نص غير منسق ولا يمكن تطبيق أي إعدادات للخط أو الصفحة وما إلى ذلك. بالمقابل، يسمح تنسيق النص الغني بخيارات التنسيق مثل تحديد نوع الخطوط، الأنماط (عريض، مائل، تحت الخط، إلخ)، هوامش الصفحة، العناوين، القوائم النقطية والمرقمة، والعديد من ميزات التنسيق الأخرى.
يتضمن أنواع الملفات التالية:
[Doc](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Doc),
[Docm](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Docm),
[Docx](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Docx),
[Dot](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Dot),
[Dotm](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Dotm),
[Dotx](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Dotx),
[Odt](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Odt),
[Ott](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Ott),
[Rtf](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Rtf),
[Txt](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Txt),
[Md](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Md),
تعرف على المزيد حول تنسيقات معالجة النصوص [هنا](../https://wiki.fileformat.com/word-processing).


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [WordProcessingFileType()](#WordProcessingFileType--) | منشئ التسلسل |
|
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Doc](#Doc) | الملفات ذات الامتداد .doc تمثل مستندات تم إنشاؤها بواسطة Microsoft Word أو مستندات معالجة نصوص أخرى بتنسيق ملف ثنائي. |
|
|  | [Docm](#Docm) | ملفات DOCM هي مستندات تم إنشاؤها بواسطة Microsoft Word 2007 أو أحدث مع القدرة على تشغيل الماكرو. |
|
|  | [Docx](#Docx) | DOCX هو تنسيق معروف لمستندات Microsoft Word. |
|
|  | [Dot](#Dot) | الملفات ذات الامتداد .DOT هي ملفات قالب تم إنشاؤها بواسطة Microsoft Word لتحتوي على إعدادات مسبقة للتنسيق لتوليد ملفات DOC أو DOCX إضافية. |
|
|  | [Dotm](#Dotm) | الملف ذو الامتداد DOTM يمثل ملف قالب تم إنشاؤه باستخدام Microsoft Word 2007 أو أحدث. |
|
|  | [Dotx](#Dotx) | الملفات ذات الامتداد DOTX هي ملفات قالب تم إنشاؤها بواسطة Microsoft Word لتحتوي على إعدادات مسبقة للتنسيق لتوليد ملفات DOCX إضافية. |
|
|  | [Rtf](#Rtf) | تم تقديم وتوثيق تنسيق النص الغني (RTF) من قبل Microsoft، وهو يمثل طريقة لتشفير النص المنسق والرسومات للاستخدام داخل التطبيقات. |
|
|  | [Odt](#Odt) | ملفات ODT هي نوع من المستندات التي تم إنشاؤها باستخدام تطبيقات معالجة النصوص المستندة إلى تنسيق ملف نص OpenDocument. |
|
|  | [Ott](#Ott) | الملفات ذات الامتداد OTT تمثل مستندات قالب تم إنشاؤها بواسطة التطبيقات وفقًا لتنسيق معيار OpenDocument الخاص بـ OASIS. |
|
|  | [Txt](#Txt) | الملف ذو الامتداد .TXT يمثل مستند نصي يحتوي على نص عادي على شكل أسطر. |
|
|  | [Md](#Md) | يتم حفظ ملفات النص التي تم إنشاؤها باستخدام لهجات لغة Markdown بالامتداد .MD أو .MARKDOWN. |
|
|  | [Ml](#Ml) | ملف Ml |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### WordProcessingFileType() {#WordProcessingFileType--}
```
public WordProcessingFileType()
```


منشئ التسلسل


### Doc {#Doc}
```
public static final WordProcessingFileType Doc
```


الملفات ذات الامتداد .doc تمثل مستندات تم إنشاؤها بواسطة Microsoft Word أو مستندات معالجة نصوص أخرى بتنسيق ملف ثنائي.
تعرف على المزيد حول تنسيق الملف هذا [هنا](../https://wiki.fileformat.com/word-processing/doc).


### Docm {#Docm}
```
public static final WordProcessingFileType Docm
```


ملفات DOCM هي مستندات تم إنشاؤها بواسطة Microsoft Word 2007 أو أحدث مع القدرة على تشغيل الماكرو.
تعرف على المزيد حول تنسيق الملف هذا [هنا](../https://wiki.fileformat.com/word-processing/docm).


### Docx {#Docx}
```
public static final WordProcessingFileType Docx
```


DOCX هو تنسيق معروف لمستندات Microsoft Word. تم تقديمه منذ عام 2007 مع إصدار Microsoft Office 2007، وتم تغيير بنية هذا التنسيق الجديد من ثنائي عادي إلى مزيج من ملفات XML والملفات الثنائية.
تعرف على المزيد حول تنسيق الملف هذا [هنا](../https://wiki.fileformat.com/word-processing/docx).


### Dot {#Dot}
```
public static final WordProcessingFileType Dot
```


الملفات ذات الامتداد .DOT هي ملفات قالب تم إنشاؤها بواسطة Microsoft Word لتحتوي على إعدادات مسبقة للتنسيق لتوليد ملفات DOC أو DOCX إضافية.
تعرف على المزيد حول تنسيق الملف هذا [هنا](../https://wiki.fileformat.com/word-processing/dot).


### Dotm {#Dotm}
```
public static final WordProcessingFileType Dotm
```


الملف ذو الامتداد DOTM يمثل ملف قالب تم إنشاؤه باستخدام Microsoft Word 2007 أو أحدث.
تعرف على المزيد حول تنسيق الملف هذا [هنا](../https://wiki.fileformat.com/word-processing/dotm).


### Dotx {#Dotx}
```
public static final WordProcessingFileType Dotx
```


الملفات ذات الامتداد DOTX هي ملفات قالب تم إنشاؤها بواسطة Microsoft Word لتحتوي على إعدادات مسبقة للتنسيق لتوليد ملفات DOCX إضافية.
تعرف على المزيد حول تنسيق الملف هذا [هنا](../https://wiki.fileformat.com/word-processing/dotx).


### Rtf {#Rtf}
```
public static final WordProcessingFileType Rtf
```


تم تقديم وتوثيق تنسيق النص الغني (RTF) من قبل Microsoft، وهو يمثل طريقة لتشفير النص المنسق والرسومات للاستخدام داخل التطبيقات.
تعرف على المزيد حول تنسيق الملف هذا [هنا](../https://wiki.fileformat.com/word-processing/rtf).


### Odt {#Odt}
```
public static final WordProcessingFileType Odt
```


ملفات ODT هي نوع من المستندات التي تم إنشاؤها باستخدام تطبيقات معالجة النصوص المستندة إلى تنسيق ملف نص OpenDocument.
تعرف على المزيد حول تنسيق الملف هذا [هنا](../https://wiki.fileformat.com/word-processing/odt).


### Ott {#Ott}
```
public static final WordProcessingFileType Ott
```


الملفات ذات الامتداد OTT تمثل مستندات قالب تم إنشاؤها بواسطة التطبيقات وفقًا لتنسيق معيار OpenDocument الخاص بـ OASIS.
تعرف على المزيد حول تنسيق الملف هذا [هنا](../https://wiki.fileformat.com/word-processing/ott).


### Txt {#Txt}
```
public static final WordProcessingFileType Txt
```


الملف ذو الامتداد .TXT يمثل مستند نصي يحتوي على نص عادي على شكل أسطر.
تعرف على المزيد حول تنسيق الملف هذا [هنا](../https://wiki.fileformat.com/word-processing/txt).


### Md {#Md}
```
public static final WordProcessingFileType Md
```


يتم حفظ ملفات النص التي تم إنشاؤها باستخدام لهجات لغة Markdown بامتداد .MD أو .MARKDOWN. تُحفظ ملفات MD بتنسيق نص عادي يستخدم لغة Markdown التي تشمل أيضًا رموز النص المضمنة، وتحدد كيفية تنسيق النص مثل المسافات البادئة، وتنسيق الجداول، والخطوط، والعناوين. تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/word-processing/md).


### Ml {#Ml}
```
public static final WordProcessingFileType Ml
```


ملف Ml


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


إعداد خيارات التحميل الافتراضية لنوع ملف المصدر


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions<WordProcessingFileType> getConvertOptions()
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
