---
title: "EmailFileType"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يحدد تنسيقات ملفات البريد الإلكتروني التي تستخدمها تطبيقات البريد لتخزين بياناتها المتنوعة بما في ذلك رسائل البريد، المرفقات، المجلدات، دفاتر العناوين، إلخ."
type: docs
weight: 15
url: /ar/java/com.groupdocs.conversion.filetypes/emailfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class EmailFileType extends FileType implements Serializable
```

يحدد تنسيقات ملفات البريد الإلكتروني التي تُستخدم بواسطة تطبيقات البريد لتخزين بياناتها المختلفة بما في ذلك رسائل البريد، المرفقات، المجلدات، دفاتر العناوين، إلخ.
يتضمن أنواع الملفات التالية:
[Eml](../../com.groupdocs.conversion.filetypes/emailfiletype#Eml),
[Emlx](../../com.groupdocs.conversion.filetypes/emailfiletype#Emlx),
[Msg](../../com.groupdocs.conversion.filetypes/emailfiletype#Msg),
[Vcf](../../com.groupdocs.conversion.filetypes/emailfiletype#Vcf).
[Pst](../../com.groupdocs.conversion.filetypes/emailfiletype#Pst).
[Ost](../../com.groupdocs.conversion.filetypes/emailfiletype#Ost).
[Olm](../../com.groupdocs.conversion.filetypes/emailfiletype#Olm).
تعرف على المزيد حول تنسيقات البريد الإلكتروني [هنا](../https://wiki.fileformat.com/email).

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [EmailFileType()](#EmailFileType--) | منشئ التسلسل |
|
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Msg](#Msg) | MSG هو تنسيق ملف يستخدمه Microsoft Outlook و Exchange لتخزين رسائل البريد الإلكتروني، جهات الاتصال، المواعيد، أو مهام أخرى. |
|
|  | [Eml](#Eml) | تنسيق ملف EML يمثل رسائل البريد الإلكتروني المحفوظة باستخدام Outlook وتطبيقات أخرى ذات صلة. |
|
|  | [Emlx](#Emlx) | تم تنفيذ وتطوير تنسيق ملف EMLX بواسطة Apple. |
|
|  | [Vcf](#Vcf) | VCF (تنسيق البطاقة الافتراضية) أو vCard هو تنسيق ملف رقمي لتخزين معلومات الاتصال. |
|
|  | [Mbox](#Mbox) | تنسيق ملف MBox هو مصطلح عام يمثل حاوية لمجموعة من رسائل البريد الإلكتروني. |
|
|  | [Pst](#Pst) | الملفات ذات الامتداد .PST تمثل ملفات تخزين شخصية Outlook (المعروفة أيضًا باسم Personal Storage Table) التي تخزن مجموعة متنوعة من معلومات المستخدم. |
|
|  | [Ost](#Ost) | تمثل ملفات OST أو ملفات التخزين غير المتصلة بيانات صندوق بريد المستخدم في وضع غير متصل على الجهاز المحلي عند التسجيل في خادم Exchange باستخدام Microsoft Outlook. |
|
|  | [Olm](#Olm) | ملف بامتداد .olm هو ملف Microsoft Outlook لنظام تشغيل ماك. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### EmailFileType() {#EmailFileType--}
```
public EmailFileType()
```


منشئ التسلسل


### Msg {#Msg}
```
public static final EmailFileType Msg
```


MSG هو تنسيق ملف يستخدمه Microsoft Outlook و Exchange لتخزين رسائل البريد الإلكتروني، جهات الاتصال، المواعيد، أو مهام أخرى.
تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/email/msg).


### Eml {#Eml}
```
public static final EmailFileType Eml
```


يمثل تنسيق ملف EML رسائل البريد الإلكتروني المحفوظة باستخدام Outlook وتطبيقات أخرى ذات صلة. تدعم تقريبًا جميع عملاء البريد هذا التنسيق لتوافقه مع معيار RFC-822 لتنسيق رسائل الإنترنت.
تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/email/eml).


### Emlx {#Emlx}
```
public static final EmailFileType Emlx
```


تم تنفيذ وتطوير تنسيق ملف EMLX بواسطة Apple. يستخدم تطبيق Apple Mail تنسيق EMLX لتصدير الرسائل.
تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/email/emlx).


### Vcf {#Vcf}
```
public static final EmailFileType Vcf
```


VCF (تنسيق البطاقة الافتراضية) أو vCard هو تنسيق ملف رقمي لتخزين معلومات الاتصال. يُستخدم هذا التنسيق على نطاق واسع لتبادل البيانات بين تطبيقات تبادل المعلومات الشائعة.
تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/email/vcf).


### Mbox {#Mbox}
```
public static final EmailFileType Mbox
```


تنسيق ملف MBox هو مصطلح عام يمثل حاوية لمجموعة من رسائل البريد الإلكتروني. تُخزن الرسائل داخل الحاوية مع مرفقاتها.
تعرف على المزيد حول هذا التنسيق [هنا](../https://docs.fileformat.com/email/mbox/).


### Pst {#Pst}
```
public static final EmailFileType Pst
```


تمثل الملفات ذات الامتداد .PST ملفات تخزين شخصية لـ Outlook (وتُسمى أيضًا جدول التخزين الشخصي) التي تخزن مجموعة متنوعة من معلومات المستخدم. تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/email/pst).


### Ost {#Ost}
```
public static final EmailFileType Ost
```


تمثل ملفات OST أو ملفات التخزين غير المتصلة بيانات صندوق بريد المستخدم في وضع غير متصل على الجهاز المحلي عند التسجيل في خادم Exchange باستخدام Microsoft Outlook. تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/email/ost).


### Olm {#Olm}
```
public static final EmailFileType Olm
```


ملف بامتداد .olm هو ملف Microsoft Outlook لنظام تشغيل ماك. يخزن ملف OLM رسائل البريد الإلكتروني، واليوميات، وبيانات التقويم، وأنواع أخرى من بيانات التطبيق. هذه مشابهة لملفات PST المستخدمة بواسطة Outlook على نظام تشغيل Windows. ومع ذلك، لا يمكن فتح ملفات OLM التي تم إنشاؤها بواسطة Outlook لنظام ماك في Outlook لنظام Windows. تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/email/olm).


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
