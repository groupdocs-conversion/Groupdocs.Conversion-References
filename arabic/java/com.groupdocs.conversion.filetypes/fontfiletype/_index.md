---
title: "FontFileType"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يحدد مستندات الخط."
type: docs
weight: 17
url: /ar/java/com.groupdocs.conversion.filetypes/fontfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class FontFileType extends FileType implements Serializable
```

يحدد مستندات الخط.
يتضمن الأنواع التالية:
[Ttf](../../com.groupdocs.conversion.filetypes/fontfiletype#Ttf),
[Eot](../../com.groupdocs.conversion.filetypes/fontfiletype#Eot),
[Otf](../../com.groupdocs.conversion.filetypes/fontfiletype#Otf),
[Cff](../../com.groupdocs.conversion.filetypes/fontfiletype#Cff),
[Type1](../../com.groupdocs.conversion.filetypes/fontfiletype#Type1),
[Woff](../../com.groupdocs.conversion.filetypes/fontfiletype#Woff),
[Woff2](../../com.groupdocs.conversion.filetypes/fontfiletype#Woff2),
تعرف على المزيد حول تنسيقات الخطوط [هنا](../https://wiki.fileformat.com/font).

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [FontFileType()](#FontFileType--) | منشئ التسلسل |
|
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Ttf](#Ttf) | الملف ذو الامتداد .ttf يمثل ملفات خطوط تعتمد على تقنية الخطوط وفق مواصفات TrueType. |
|
|  | [Eot](#Eot) | ملف بامتداد .eot هو خط OpenType يتم تضمينه في مستند. |
|
|  | [Otf](#Otf) | ملف بامتداد .otf يشير إلى تنسيق خط OpenType. |
|
|  | [Cff](#Cff) | ملف بامتداد .cff هو تنسيق خط مضغوط (Compact Font Format) ويُعرف أيضاً باسم PostScript Type 1 أو CIDFont. |
|
|  | [Type1](#Type1) | خطوط Type 1 هي تقنية Adobe قديمة تم إهمالها وكانت تُستخدم على نطاق واسع في برامج النشر المكتبي والطابعات التي تدعم PostScript. |
|
|  | [Woff](#Woff) | ملف بامتداد .woff هو ملف خط ويب يعتمد على تنسيق الخط المفتوح للويب (Web Open Font Format - WOFF). |
|
|  | [Woff2](#Woff2) | ملف بامتداد .woff هو ملف خط ويب يعتمد على تنسيق الخط المفتوح للويب (Web Open Font Format - WOFF). |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### FontFileType() {#FontFileType--}
```
public FontFileType()
```


منشئ التسلسل


### Ttf {#Ttf}
```
public static final FontFileType Ttf
```


ملف بامتداد .ttf يمثل ملفات خطوط تعتمد على تقنية الخط وفق مواصفات TrueType. تم تصميمه وإصداره في البداية من قبل شركة Apple Computer, Inc لنظام Mac OS ولاحقًا اعتمدته Microsoft لنظام Windows OS. تعرف على المزيد حول هذا التنسيق [هنا](../https://docs.fileformat.com/font/ttf/).


### Eot {#Eot}
```
public static final FontFileType Eot
```


ملف بامتداد .eot هو خط OpenType يتم تضمينه في مستند. تُستخدم هذه الملفات في الغالب في ملفات الويب مثل صفحات الويب. تم إنشاؤه بواسطة Microsoft ويدعمه منتجات Microsoft بما في ذلك ملفات عروض PowerPoint بامتداد .pps. تعرف على المزيد حول هذا التنسيق [هنا](../https://docs.fileformat.com/font/eot/).


### Otf {#Otf}
```
public static final FontFileType Otf
```


ملف بامتداد .otf يشير إلى تنسيق خط OpenType. تنسيق OTF أكثر قابلية للتوسع ويضيف ميزات إضافية إلى تنسيقات TTF للكتابة الرقمية. تم تطويره من قبل Microsoft وAdobe، ويجمع OTF بين ميزات تنسيقات الخط PostScript وTrueType. تعرف على المزيد حول هذا التنسيق [هنا](../https://docs.fileformat.com/font/otf/).


### Cff {#Cff}
```
public static final FontFileType Cff
```


ملف بامتداد .cff هو تنسيق خط مضغوط (Compact Font Format) ويُعرف أيضاً باسم PostScript Type 1 أو CIDFont. يعمل CFF كحاوية لتخزين خطوط متعددة معًا في وحدة واحدة تُسمى FontSet. تعرف على المزيد حول هذا التنسيق [هنا](../https://docs.fileformat.com/font/cff/).


### Type1 {#Type1}
```
public static final FontFileType Type1
```


خطوط Type 1 هي تقنية Adobe قديمة تم إهمالها وكانت تُستخدم على نطاق واسع في برامج النشر المكتبي والطابعات التي تدعم PostScript. على الرغم من أن خطوط Type 1 غير مدعومة في العديد من المنصات الحديثة ومتصفحات الويب وأنظمة التشغيل المحمولة، إلا أنها لا تزال مدعومة في بعض أنظمة التشغيل. تعرف على المزيد حول هذا التنسيق [هنا](../https://docs.fileformat.com/font/type1/).


### Woff {#Woff}
```
public static final FontFileType Woff
```


ملف بامتداد .woff هو ملف خط ويب يعتمد على تنسيق الخط المفتوح للويب (Web Open Font Format - WOFF). يحتوي على حاوية مضغوطة خاصة بالتنسيق تعتمد إما على خطوط TrueType (.TTF) أو OpenType (.OTT). تعرف على المزيد حول هذا التنسيق [هنا](../https://docs.fileformat.com/font/woff/).


### Woff2 {#Woff2}
```
public static final FontFileType Woff2
```


ملف بامتداد .woff هو ملف خط ويب يعتمد على تنسيق الخط المفتوح للويب (Web Open Font Format - WOFF). يحتوي على حاوية مضغوطة خاصة بالتنسيق تعتمد إما على خطوط TrueType (.TTF) أو OpenType (.OTT). تعرف على المزيد حول هذا التنسيق [هنا](../https://docs.fileformat.com/font/woff/).


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
