---
title: WordProcessingFileType
second_title: GroupDocs.Conversion لمرجع .NET API
description: يحدد ملفات معالجة الكلمات التي تحتوي على معلومات المستخدم بتنسيق نص عادي أو نص منسق. يحتوي تنسيق ملف نص عادي على نص غير منسق ولا يمكن تطبيق أي إعدادات للخط أو الصفحة وما إلى ذلك. في المقابل  يسمح تنسيق ملف النص المنسق بخيارات التنسيق مثل تعيين نوع الخطوط والأنماط غامق ومائل وتسطير  وما إلى ذلك  وهوامش الصفحة والعناوين والتعداد النقطي والأرقام والعديد من ميزات التنسيق الأخرى. يتضمن أنواع الملفات التالية Doc./wordprocessingfiletype/doc  Docm./wordprocessingfiletype/docm  Docx./wordprocessingfiletype/docx  Dot./wordprocessingfiletype/dot  Dotm./wordprocessingfiletype/dotm  Dotx./wordprocessingfiletype/dotx  Mobi./wordprocessingfiletype/mobi  Odt./wordprocessingfiletype/odt  Ott./wordprocessingfiletype/ott  Rtf./wordprocessingfiletype/rtf  Txt./wordprocessingfiletype/txt . Md./wordprocessingfiletype/md . Log./wordprocessingfiletype/log . تعرف على المزيد حول تنسيقات معالجة الكلماتهناhttps//wiki.fileformat.com/wordprocessing .
type: docs
weight: 960
url: /ar/net/groupdocs.conversion.filetypes/wordprocessingfiletype/
---
## WordProcessingFileType class

يحدد ملفات معالجة الكلمات التي تحتوي على معلومات المستخدم بتنسيق نص عادي أو نص منسق. يحتوي تنسيق ملف نص عادي على نص غير منسق ولا يمكن تطبيق أي إعدادات للخط أو الصفحة وما إلى ذلك. في المقابل ، يسمح تنسيق ملف النص المنسق بخيارات التنسيق مثل تعيين نوع الخطوط والأنماط (غامق ومائل وتسطير ، وما إلى ذلك) ، وهوامش الصفحة والعناوين والتعداد النقطي والأرقام والعديد من ميزات التنسيق الأخرى. يتضمن أنواع الملفات التالية: [`Doc`](./doc) ، [`Docm`](./docm) ، [`Docx`](./docx) ، [`Dot`](./dot) ، [`Dotm`](./dotm) ، [`Dotx`](./dotx) ، [`Mobi`](./mobi) ، [`Odt`](./odt) ، [`Ott`](./ott) ، [`Rtf`](./rtf) ، [`Txt`](./txt) . [`Md`](./md) . [`Log`](./log) . تعرف على المزيد حول تنسيقات معالجة الكلمات[هنا](https://wiki.fileformat.com/word-processing) .

```csharp
public sealed class WordProcessingFileType : FileType
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [WordProcessingFileType](wordprocessingfiletype)() | مُنشئ التسلسل |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | نوع الملف description |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | امتداد الملف |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | الملف family |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | تنسيق الملف |

## طُرق

| اسم | وصف |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | مقارنة الكائن الحالي بآخر . |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | تحديد ما إذا كان مثيلا الكائن متساويان. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | تحديد ما إذا كان مثيلا الكائن متساويان. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | تعمل كوظيفة تجزئة افتراضية . |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | تمثيل السلسلة |

## مجالات

| اسم | وصف |
| --- | --- |
| static readonly [Azw3](../../groupdocs.conversion.filetypes/wordprocessingfiletype/azw3) | AZW3 ، المعروف أيضًا باسم Kindle Format 8 (KF8) ، هو النسخة المعدلة من تنسيق الملفات الرقمية AZW للكتب الإلكترونية المطورة لأجهزة Amazon Kindle. يعد التنسيق تحسينًا لملفات AZW الأقدم ويتم استخدامه على أجهزة Kindle Fire فقط مع التوافق مع الإصدارات السابقة لتنسيق ملف السلف مثل MOBI و AZW . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/ebook/azw3/) . |
| static readonly [Doc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/doc) | تمثل الملفات ذات الامتداد .doc المستندات التي تم إنشاؤها بواسطة Microsoft Word أو مستندات معالجة النصوص الأخرى بتنسيق ملف ثنائي . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [Docm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docm) | ملفات DOCM هي Microsoft Word 2007 أو مستندات تم إنشاؤها بأعلى مع إمكانية تشغيل وحدات الماكرو. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [Docx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docx) | DOCX هو تنسيق معروف لمستندات Microsoft Word. تم تقديمه من عام 2007 مع إصدار Microsoft Office 2007 ، تم تغيير هيكل تنسيق المستند الجديد هذا من ثنائي عادي إلى مجموعة من ملفات XML والملفات الثنائية. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [Dot](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dot) | الملفات ذات الامتداد .DOT هي ملفات قوالب تم إنشاؤها بواسطة Microsoft Word للحصول على إعدادات مهيأة مسبقًا لإنشاء المزيد من ملفات DOC أو DOCX. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [Dotm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotm) | يمثل ملف بامتداد DOTM ملف قالب تم إنشاؤه باستخدام Microsoft Word 2007 أو أعلى . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [Dotx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotx) | الملفات ذات امتداد DOTX هي ملفات قوالب تم إنشاؤها بواسطة Microsoft Word للحصول على إعدادات مهيأة مسبقًا لإنشاء ملفات DOCX أخرى. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [Log](../../groupdocs.conversion.filetypes/wordprocessingfiletype/log) | يمثل الملف بامتداد .LOG مستندًا نصيًا يحتوي على نص عادي في شكل أسطر. |
| static readonly [Md](../../groupdocs.conversion.filetypes/wordprocessingfiletype/md) | يتم حفظ الملفات النصية التي تم إنشاؤها باستخدام لهجات لغة Markdown بامتداد الملف .MD أو .MARKDOWN. يتم حفظ ملفات MD بتنسيق نص عادي يستخدم لغة Markdown التي تتضمن أيضًا رموز نص مضمنة ، وتحديد كيفية تنسيق النص مثل المسافات البادئة وتنسيق الجدول والخطوط والعناوين. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/md) . |
| static readonly [Mobi](../../groupdocs.conversion.filetypes/wordprocessingfiletype/mobi) | يعد تنسيق ملف MOBI أحد أكثر تنسيقات ملفات الكتب الإلكترونية استخدامًا. يعد التنسيق تحسينًا للتنسيق القديم OEB (تنسيق Open Ebook) وقد تم استخدامه كتنسيق خاص لـ Mobipocket Reader . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/ebook/mobi) . |
| static readonly [Odt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/odt) | ملفات ODT هي نوع من المستندات التي تم إنشاؤها باستخدام تطبيقات معالجة الكلمات التي تعتمد على تنسيق OpenDocument Text File. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [Ott](../../groupdocs.conversion.filetypes/wordprocessingfiletype/ott) | تمثل الملفات ذات الامتداد OTT مستندات النماذج التي تم إنشاؤها بواسطة التطبيقات وفقًا للتنسيق القياسي OpenDocument الخاص بـ OASIS. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [Rtf](../../groupdocs.conversion.filetypes/wordprocessingfiletype/rtf) | تم تقديمه وتوثيقه بواسطة Microsoft ، يمثل Rich Text Format (RTF) طريقة لترميز النص والرسومات المنسقة للاستخدام داخل التطبيقات. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [Sql](../../groupdocs.conversion.filetypes/wordprocessingfiletype/sql) | يمثل الملف بامتداد .SQL مستندًا نصيًا يحتوي على SQL. |
| static readonly [Txt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/txt) | يمثل الملف بامتداد .TXT مستندًا نصيًا يحتوي على نص عادي في شكل أسطر. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/txt) . |

### أنظر أيضا

* class [FileType](../filetype)
* مساحة الاسم [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* المجسم [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
