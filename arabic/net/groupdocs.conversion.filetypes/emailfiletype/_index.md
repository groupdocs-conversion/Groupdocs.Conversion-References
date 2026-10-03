---
title: "EmailFileType"
second_title: "GroupDocs.Conversion لـ .NET مرجع API"
description: "يحدد تنسيقات ملفات البريد الإلكتروني التي تستخدمها تطبيقات البريد لتخزين بياناتها المتنوعة بما في ذلك رسائل البريد الإلكتروني والمرفقات والمجلدات ودفاتر العناوين وغيرها. يشمل الأنواع التالية من الملفات Eml./emailfiletype/eml Emlx./emailfiletype/emlx Msg./emailfiletype/msg Vcf./emailfiletype/vcf. Mbox./emailfiletype/mbox. Pst./emailfiletype/pst. Ost./emailfiletype/ost. Olm./emailfiletype/olm. تعرف على المزيد حول تنسيقات البريد الإلكتروني هناhttps//wiki.fileformat.com/email"
type: docs
weight: 1120
url: /ar/net/groupdocs.conversion.filetypes/emailfiletype/
---
## EmailFileType class

يحدد صيغ ملفات البريد الإلكتروني التي تستخدمها تطبيقات البريد لتخزين بياناتها المتنوعة بما في ذلك رسائل البريد، المرفقات، المجلدات، دفاتر العناوين وغيرها. يتضمن أنواع الملفات التالية: [`Eml`](./eml), [`Emlx`](./emlx), [`Msg`](./msg), [`Vcf`](./vcf). [`Mbox`](./mbox). [`Pst`](./pst). [`Ost`](./ost). [`Olm`](./olm). تعرف على المزيد حول صيغ البريد الإلكتروني [هنا](https://wiki.fileformat.com/email).

```csharp
public sealed class EmailFileType : FileType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmailFileType](emailfiletype)() | منشئ التسلسل |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | وصف نوع الملف |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | امتداد الملف |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | عائلة الملف |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | صيغة الملف |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | يقارن الكائن الحالي بآخر. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | ينفذ [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | يحدد ما إذا كان مثيلان للكائن متساويين. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | يعمل كدالة التجزئة الافتراضية. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | تمثيل النص |

## الحقول

| الاسم | الوصف |
| --- | --- |
| static readonly [Eml](../../groupdocs.conversion.filetypes/emailfiletype/eml) | تمثل صيغة ملف EML رسائل البريد الإلكتروني المحفوظة باستخدام Outlook وتطبيقات أخرى ذات صلة. تدعم تقريبًا جميع عملاء البريد هذا التنسيق لامتثاله لمعيار RFC-822 لتنسيق رسائل الإنترنت. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/email/eml). |
| static readonly [Emlx](../../groupdocs.conversion.filetypes/emailfiletype/emlx) | تم تنفيذ وتطوير صيغة ملف EMLX بواسطة Apple. يستخدم تطبيق Apple Mail صيغة ملف EMLX لتصدير رسائل البريد الإلكتروني. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/email/emlx). |
| static readonly [Ics](../../groupdocs.conversion.filetypes/emailfiletype/ics) | يُستخدم تنسيق ملف ICS (iCalendar) لتمثيل وتبادل معلومات التقويم والجدولة مثل الأحداث، والمهام، وبيانات الحالة المتفرغة/المشغولة. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/email/ics). |
| static readonly [Mbox](../../groupdocs.conversion.filetypes/emailfiletype/mbox) | صيغة ملف MBox هي مصطلح عام يمثل حاوية لمجموعة من رسائل البريد الإلكتروني. تُخزن الرسائل داخل الحاوية مع مرفقاتها. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/email/mbox/). |
| static readonly [Msg](../../groupdocs.conversion.filetypes/emailfiletype/msg) | MSG هو تنسيق ملف يستخدمه Microsoft Outlook وExchange لتخزين رسائل البريد الإلكتروني، جهات الاتصال، المواعيد، أو مهام أخرى. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/email/msg). |
| static readonly [Olm](../../groupdocs.conversion.filetypes/emailfiletype/olm) | الملف ذو الامتداد .olm هو ملف Microsoft Outlook لنظام تشغيل ماك. يخزن ملف OLM رسائل البريد الإلكتروني، اليوميات، بيانات التقويم، وأنواع أخرى من بيانات التطبيق. هذه الملفات مشابهة لملفات PST المستخدمة من قبل Outlook على نظام تشغيل ويندوز. ومع ذلك، لا يمكن فتح ملفات OLM التي أنشأها Outlook لنظام ماك في Outlook لنظام ويندوز. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/email/olm). |
| static readonly [Ost](../../groupdocs.conversion.filetypes/emailfiletype/ost) | تمثل ملفات OST أو Offline Storage بيانات صندوق بريد المستخدم في وضع عدم الاتصال على الجهاز المحلي عند التسجيل في خادم Exchange باستخدام Microsoft Outlook. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/email/ost). |
| static readonly [Pst](../../groupdocs.conversion.filetypes/emailfiletype/pst) | الملفات ذات الامتداد .PST تمثل ملفات Outlook Personal Storage (وتسمى أيضًا Personal Storage Table) التي تخزن مجموعة متنوعة من معلومات المستخدم. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/email/pst). |
| static readonly [Vcf](../../groupdocs.conversion.filetypes/emailfiletype/vcf) | VCF (Virtual Card Format) أو vCard هو تنسيق ملف رقمي لتخزين معلومات جهات الاتصال. يُستخدم هذا التنسيق على نطاق واسع لتبادل البيانات بين تطبيقات تبادل المعلومات الشائعة. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/email/vcf). |

### انظر أيضًا

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
