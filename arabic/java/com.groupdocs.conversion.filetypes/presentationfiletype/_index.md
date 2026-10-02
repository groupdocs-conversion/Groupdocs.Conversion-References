---
title: "PresentationFileType"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يحدد تنسيقات ملفات العرض التي تخزن مجموعة من السجلات لاستيعاب بيانات العرض مثل الشرائح، الأشكال، النصوص، الرسوم المتحركة، الفيديو، الصوت والكائنات المدمجة."
type: docs
weight: 22
url: /ar/java/com.groupdocs.conversion.filetypes/presentationfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PresentationFileType extends FileType implements Serializable
```

يحدد صيغ ملفات العروض التقديمية التي تخزن مجموعة من السجلات لاستيعاب بيانات العرض مثل الشرائح، الأشكال، النص، الرسوم المتحركة، الفيديو، الصوت والكائنات المدمجة.
يتضمن أنواع الملفات التالية:
[Odp](../../com.groupdocs.conversion.filetypes/presentationfiletype#Odp),
[Otp](../../com.groupdocs.conversion.filetypes/presentationfiletype#Otp),
[Pot](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pot),
[Potm](../../com.groupdocs.conversion.filetypes/presentationfiletype#Potm),
[Potx](../../com.groupdocs.conversion.filetypes/presentationfiletype#Potx),
[Pps](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pps),
[Ppsm](../../com.groupdocs.conversion.filetypes/presentationfiletype#Ppsm),
[Ppsx](../../com.groupdocs.conversion.filetypes/presentationfiletype#Ppsx),
[Ppt](../../com.groupdocs.conversion.filetypes/presentationfiletype#Ppt),
[Pptm](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pptm),
[Pptx](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pptx).
تعرف على المزيد حول صيغ العروض التقديمية [هنا](../https://wiki.fileformat.com/presentation).

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [PresentationFileType()](#PresentationFileType--) | منشئ التسلسل |
|
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Ppt](#Ppt) | الملف ذو الامتداد PPT يمثل ملف PowerPoint يتكون من مجموعة من الشرائح للعرض كعرض شرائح. |
|
|  | [Pps](#Pps) | ملفات PPS، عرض شرائح PowerPoint، تُنشأ باستخدام Microsoft PowerPoint لغرض عرض الشرائح. |
|
|  | [Pptx](#Pptx) | الملفات ذات الامتداد PPTX هي ملفات عرض تم إنشاؤها باستخدام تطبيق Microsoft PowerPoint الشائع. |
|
|  | [Ppsx](#Ppsx) | ملفات PPSX، عرض شرائح PowerPoint، تُنشأ باستخدام Microsoft PowerPoint 2007 وما فوق لغرض عرض الشرائح. |
|
|  | [Odp](#Odp) | الملفات ذات الامتداد ODP تمثل صيغة ملف عرض تُستخدم من قبل OpenOffice.org في معيار OASISOpen. |
|
|  | [Otp](#Otp) | الملفات ذات الامتداد .OTP تمثل قوالب عرض تم إنشاؤها بواسطة التطبيقات وفق معيار OASIS OpenDocument. |
|
|  | [Potx](#Potx) | الملفات ذات الامتداد .POTX تمثل قوالب عروض Microsoft PowerPoint التي تم إنشاؤها باستخدام Microsoft PowerPoint 2007 وما فوق. |
|
|  | [Pot](#Pot) | الملفات ذات الامتداد .POT تمثل قوالب ملفات Microsoft PowerPoint التي تم إنشاؤها بواسطة إصدارات PowerPoint 97-2003. |
|
|  | [Potm](#Potm) | الملفات ذات الامتداد POTM هي قوالب ملفات Microsoft PowerPoint مع دعم للماكرو. |
|
|  | [Pptm](#Pptm) | الملفات ذات الامتداد PPTM هي ملفات عرض مدعومة بالماكرو تم إنشاؤها باستخدام Microsoft PowerPoint 2007 أو إصدارات أعلى. |
|
|  | [Ppsm](#Ppsm) | الملفات ذات الامتداد PPSM تمثل صيغة ملف عرض مدعومة بالماكرو تم إنشاؤها باستخدام Microsoft PowerPoint 2007 أو أعلى. |
|
|  | [Fodp](#Fodp) | الملفات ذات الامتداد FODP تمثل عرض OpenDocument Flat XML. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PresentationFileType() {#PresentationFileType--}
```
public PresentationFileType()
```


منشئ التسلسل


### Ppt {#Ppt}
```
public static final PresentationFileType Ppt
```


الملف ذو الامتداد PPT يمثل ملف PowerPoint يتكون من مجموعة من الشرائح للعرض كعرض شرائح. يحدد صيغة الملف الثنائي المستخدمة من قبل Microsoft PowerPoint 97-2003.
تعرف على المزيد حول صيغة الملف هذه [هنا](../https://wiki.fileformat.com/presentation/ppt).


### Pps {#Pps}
```
public static final PresentationFileType Pps
```


ملفات PPS، عرض شرائح PowerPoint، تُنشأ باستخدام Microsoft PowerPoint لغرض عرض الشرائح. قراءة وإنشاء ملفات PPS مدعومة من قبل Microsoft PowerPoint 97-2003.
تعرف على المزيد حول صيغة الملف هذه [هنا](../https://wiki.fileformat.com/presentation/pps).


### Pptx {#Pptx}
```
public static final PresentationFileType Pptx
```


الملفات ذات الامتداد PPTX هي ملفات عرض تم إنشاؤها باستخدام تطبيق Microsoft PowerPoint الشائع. على عكس النسخة السابقة من صيغة ملف العرض PPT التي كانت ثنائية، فإن صيغة PPTX تعتمد على صيغة عرض Microsoft PowerPoint المفتوحة XML.
تعرف على المزيد حول صيغة الملف هذه [هنا](../https://wiki.fileformat.com/presentation/pptx).


### Ppsx {#Ppsx}
```
public static final PresentationFileType Ppsx
```


ملفات PPSX، عرض شرائح PowerPoint، تُنشأ باستخدام Microsoft PowerPoint 2007 وما فوق لغرض عرض الشرائح.
تعرف على المزيد حول صيغة الملف هذه [هنا](../https://wiki.fileformat.com/presentation/ppsx).


### Odp {#Odp}
```
public static final PresentationFileType Odp
```


الملفات ذات الامتداد ODP تمثل صيغة ملف عرض تُستخدم من قبل OpenOffice.org في معيار OASISOpen.
تعرف على المزيد حول صيغة الملف هذه [هنا](../https://wiki.fileformat.com/presentation/odp).


### Otp {#Otp}
```
public static final PresentationFileType Otp
```


الملفات ذات الامتداد .OTP تمثل قوالب عرض تم إنشاؤها بواسطة التطبيقات وفق معيار OASIS OpenDocument.
تعرف على المزيد حول صيغة الملف هذه [هنا](../https://wiki.fileformat.com/presentation/otp).


### Potx {#Potx}
```
public static final PresentationFileType Potx
```


الملفات ذات الامتداد .POTX تمثل قوالب عروض Microsoft PowerPoint التي تم إنشاؤها باستخدام Microsoft PowerPoint 2007 وما فوق.
تعرف على المزيد حول صيغة الملف هذه [هنا](../https://wiki.fileformat.com/presentation/potx).


### Pot {#Pot}
```
public static final PresentationFileType Pot
```


الملفات ذات الامتداد .POT تمثل قوالب ملفات Microsoft PowerPoint التي تم إنشاؤها بواسطة إصدارات PowerPoint 97-2003.
تعرف على المزيد حول صيغة الملف هذه [هنا](../https://wiki.fileformat.com/presentation/pot).


### Potm {#Potm}
```
public static final PresentationFileType Potm
```


الملفات ذات امتداد POTM هي ملفات قالب Microsoft PowerPoint مع دعم للماكرو. يتم إنشاء ملفات POTM باستخدام PowerPoint 2007 أو أحدث وتحتوي على إعدادات افتراضية يمكن استخدامها لإنشاء ملفات عروض تقديمية أخرى.
تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/presentation/potm).


### Pptm {#Pptm}
```
public static final PresentationFileType Pptm
```


الملفات ذات الامتداد PPTM هي ملفات عرض مدعومة بالماكرو تم إنشاؤها باستخدام Microsoft PowerPoint 2007 أو إصدارات أعلى.
تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/presentation/pptm).


### Ppsm {#Ppsm}
```
public static final PresentationFileType Ppsm
```


الملفات ذات الامتداد PPSM تمثل صيغة ملف عرض مدعومة بالماكرو تم إنشاؤها باستخدام Microsoft PowerPoint 2007 أو أعلى.
تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/presentation/ppsm).


### Fodp {#Fodp}
```
public static final PresentationFileType Fodp
```


الملفات ذات امتداد FODP تمثل عرض تقديمي OpenDocument Flat XML. يتم حفظ ملف العرض بتنسيق OpenDocument، ولكن باستخدام تنسيق XML مسطح بدلاً من حاوية .ZIP المستخدمة في ملفات .ODP القياسية.


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
