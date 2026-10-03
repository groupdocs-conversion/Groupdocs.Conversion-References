---
title: "WordProcessingFileType"
second_title: "GroupDocs.Conversion لـ .NET مرجع API"
description: "يحدد ملفات معالجة النصوص التي تحتوي على معلومات المستخدم بنص عادي أو تنسيق نص غني. يحتوي تنسيق الملف النصي العادي على نص غير منسق ولا يمكن تطبيق أي إعدادات للخط أو الصفحة إلخ. في المقابل، يسمح تنسيق النص الغني بخيارات تنسيق مثل تعيين الخطوط، الأنواع، الأنماط، الغامق، المائل، التسطير إلخ، وهوامش الصفحة، العناوين، القوائم النقطية والمرقمة، والعديد من ميزات التنسيق الأخرى. يتضمن أنواع الملفات التالية: Doc./wordprocessingfiletype/doc Docm./wordprocessingfiletype/docm Docx./wordprocessingfiletype/docx Dot./wordprocessingfiletype/dot Dotm./wordprocessingfiletype/dotm Dotx./wordprocessingfiletype/dotx Odt./wordprocessingfiletype/odt Ott./wordprocessingfiletype/ott Rtf./wordprocessingfiletype/rtf Txt./wordprocessingfiletype/txt. Md./wordprocessingfiletype/md. تعرف على المزيد حول صيغ معالجة النصوص هناhttps//wiki.fileformat.com/wordprocessing."
type: docs
weight: 1280
url: /ar/net/groupdocs.conversion.filetypes/wordprocessingfiletype/
---
## WordProcessingFileType class

يحدد ملفات معالجة النصوص التي تحتوي على معلومات المستخدم بنص عادي أو تنسيق نص غني. يحتوي تنسيق الملف النصي العادي على نص غير منسق ولا يمكن تطبيق أي إعدادات للخط أو الصفحة وغيرها. بالمقابل، يسمح تنسيق النص الغني بخيارات تنسيق مثل تحديد نوع الخطوط، الأنماط (عريض، مائل، تحتي، إلخ)، هوامش الصفحة، العناوين، القوائم النقطية والرقمية، والعديد من ميزات التنسيق الأخرى. يتضمن أنواع الملفات التالية: [`Doc`](./doc)، [`Docm`](./docm)، [`Docx`](./docx)، [`Dot`](./dot)، [`Dotm`](./dotm)، [`Dotx`](./dotx)، [`Odt`](./odt)، [`Ott`](./ott)، [`Rtf`](./rtf)، [`Txt`](./txt). [`Md`](./md). تعرف على المزيد حول تنسيقات معالجة النصوص [هنا](https://wiki.fileformat.com/word-processing).

```csharp
public sealed class WordProcessingFileType : FileType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [WordProcessingFileType](wordprocessingfiletype)() | منشئ التسلسل |

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
| static readonly [Doc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/doc) | الملفات ذات الامتداد .doc تمثل مستندات تم إنشاؤها بواسطة Microsoft Word أو مستندات معالجة نصوص أخرى بتنسيق ملف ثنائي. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/doc). |
| static readonly [Docm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docm) | ملفات DOCM هي مستندات تم إنشاؤها بواسطة Microsoft Word 2007 أو أعلى مع القدرة على تشغيل الماكرو. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/docm). |
| static readonly [Docx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docx) | DOCX هو تنسيق معروف لمستندات Microsoft Word. تم تقديمه منذ 2007 مع إصدار Microsoft Office 2007، وتم تغيير بنية هذا التنسيق الجديد من ملف ثنائي عادي إلى مزيج من ملفات XML وملفات ثنائية. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/docx). |
| static readonly [Dot](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dot) | الملفات ذات الامتداد .DOT هي ملفات قالب تم إنشاؤها بواسطة Microsoft Word لتحتوي على إعدادات مسبقة التنسيق لإنشاء ملفات DOC أو DOCX إضافية. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/dot). |
| static readonly [Dotm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotm) | الملف ذو الامتداد DOTM يمثل ملف قالب تم إنشاؤه باستخدام Microsoft Word 2007 أو أعلى. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/dotm). |
| static readonly [Dotx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotx) | الملفات ذات الامتداد DOTX هي ملفات قالب تم إنشاؤها بواسطة Microsoft Word لتحتوي على إعدادات مسبقة التنسيق لإنشاء ملفات DOCX إضافية. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/dotx). |
| static readonly [FlatOpc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/flatopc) | Flat OPC Word هو Office Open XML WordprocessingML مخزن في ملف XML مسطح بدلاً من حزمة ZIP. |
| static readonly [Md](../../groupdocs.conversion.filetypes/wordprocessingfiletype/md) | ملفات النص التي تم إنشاؤها باستخدام لهجات لغة Markdown تُحفظ بامتداد .MD أو .MARKDOWN. تُحفظ ملفات MD بتنسيق نص عادي يستخدم لغة Markdown التي تشمل أيضاً رموز النص المضمن، وتحدد كيفية تنسيق النص مثل المسافات البادئة، تنسيق الجداول، الخطوط، والعناوين. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/md). |
| static readonly [Odt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/odt) | ملفات ODT هي نوع من المستندات التي تم إنشاؤها باستخدام تطبيقات معالجة النصوص القائمة على تنسيق ملف نص OpenDocument. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/odt). |
| static readonly [Ott](../../groupdocs.conversion.filetypes/wordprocessingfiletype/ott) | الملفات ذات الامتداد OTT تمثل مستندات قالب تم إنشاؤها بواسطة تطبيقات متوافقة مع معيار OpenDocument الخاص بـ OASIS. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/ott). |
| static readonly [Rtf](../../groupdocs.conversion.filetypes/wordprocessingfiletype/rtf) | تم تقديم وتوثيق Rich Text Format (RTF) من قبل Microsoft، وهو يمثل طريقة لتشفير النص المنسق والرسومات للاستخدام داخل التطبيقات. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/rtf). |
| static readonly [Txt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/txt) | الملف ذو الامتداد .TXT يمثل مستند نص يحتوي على نص عادي على شكل أسطر. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/txt). |

### انظر أيضًا

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
