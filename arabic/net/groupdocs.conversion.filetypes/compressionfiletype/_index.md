---
title: CompressionFileType
second_title: GroupDocs.Conversion لمرجع .NET API
description: يحدد تنسيقات الضغط. يتضمن أنواع الملفات التالية Zip./compressionfiletype/zip . Rar./compressionfiletype/rar . SevenZ./compressionfiletype/sevenz . Tar./compressionfiletype/tar . Gz./compressionfiletype/gz . Gzip./compressionfiletype/gzip . Bz2./compressionfiletype/bz2 . اعرف المزيد حول تنسيقات الضغطهناhttps//docs.fileformat.com/compression/ .
type: docs
weight: 870
url: /ar/net/groupdocs.conversion.filetypes/compressionfiletype/
---
## CompressionFileType class

يحدد تنسيقات الضغط. يتضمن أنواع الملفات التالية: [`Zip`](./zip) . [`Rar`](./rar) . [`SevenZ`](./sevenz) . [`Tar`](./tar) . [`Gz`](./gz) . [`Gzip`](./gzip) . [`Bz2`](./bz2) . اعرف المزيد حول تنسيقات الضغط[هنا](https://docs.fileformat.com/compression/) .

```csharp
public sealed class CompressionFileType : FileType
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [CompressionFileType](compressionfiletype)() | مُنشئ التسلسل |

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
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | تحديد ما إذا كان مثيلا الكائن متساويان. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | تحديد ما إذا كان مثيلا الكائن متساويان. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | تعمل كوظيفة تجزئة افتراضية . |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | تمثيل السلسلة |

## مجالات

| اسم | وصف |
| --- | --- |
| static readonly [Bz2](../../groupdocs.conversion.filetypes/compressionfiletype/bz2) | BZ2 هي ملفات مضغوطة تم إنشاؤها باستخدام طريقة ضغط المصدر المفتوح BZIP2 ، ومعظمها على نظام UNIX أو Linux. يتم استخدامه لضغط ملف واحد ولا يُقصد به أرشفة ملفات متعددة. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/compression/bz2/) . |
| static readonly [Cab](../../groupdocs.conversion.filetypes/compressionfiletype/cab) | ينتمي ملف بملحق .cab إلى ملف خزانة Windows الذي ينتمي إلى فئة ملفات النظام. هو ملف يتم حفظه بتنسيق ملف الأرشيف في إصدارات Microsoft Windows التي تدعم خوارزميات البيانات المضغوطة ، مثل LZX و Quantum و ZIP . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/system/cab/) . |
| static readonly [Cpio](../../groupdocs.conversion.filetypes/compressionfiletype/cpio) | Cpio هي أداة عامة لأرشيف الملفات وتنسيق الملف المرتبط بها. يتم تثبيته بشكل أساسي على أنظمة تشغيل كمبيوتر تشبه Unix. |
| static readonly [Gz](../../groupdocs.conversion.filetypes/compressionfiletype/gz) | ملف GZ هو أرشيف مضغوط تم إنشاؤه باستخدام خوارزمية ضغط gzip القياسية (GNU zip). قد يحتوي على العديد من الملفات المضغوطة والدلائل وأوتار الملفات. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/compression/gz/) . |
| static readonly [Gzip](../../groupdocs.conversion.filetypes/compressionfiletype/gzip) | ملف Gzip هو أرشيف مضغوط يتم إنشاؤه باستخدام خوارزمية ضغط gzip القياسية (GNU zip). قد يحتوي على العديد من الملفات المضغوطة والدلائل وأوتار الملفات. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/compression/gz/) . |
| static readonly [Lz](../../groupdocs.conversion.filetypes/compressionfiletype/lz) | الملف ذو الامتداد .lz هو ملف أرشيف مضغوط تم إنشاؤه باستخدام Lzip ، وهو أداة سطر أوامر مجانية للضغط. وهو يدعم التسلسل لضغط ملفات الدعم. تحتوي ملفات LZ على تطبيق من نوع الوسائط / lzip وتدعم حصص ضغط أعلى من BZ2. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/compression/bz2/) . |
| static readonly [Lzma](../../groupdocs.conversion.filetypes/compressionfiletype/lzma) | ملف بامتداد .lzma هو ملف أرشيف مضغوط تم إنشاؤه باستخدام طريقة ضغط LZMA (خوارزمية سلسلة Lempel-Ziv-Markov). تم العثور عليها / استخدامها بشكل أساسي على نظام التشغيل Unix وتشبه خوارزميات الضغط الأخرى مثل ZIP لتقليل حجم الملف. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/compression/lzma/) . |
| static readonly [Rar](../../groupdocs.conversion.filetypes/compressionfiletype/rar) | الملفات ذات الامتداد .rar هي ملفات أرشيفية يتم إنشاؤها لتخزين المعلومات في شكل مضغوط أو عادي. RAR ، والذي يرمز إلى تنسيق ملف Roshal ARchive . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/compression/rar/) . |
| static readonly [SevenZ](../../groupdocs.conversion.filetypes/compressionfiletype/sevenz) | 7z هو تنسيق أرشفة لضغط الملفات والمجلدات بنسبة ضغط عالية. يعتمد على بنية مفتوحة المصدر تجعل من الممكن استخدام أي خوارزميات ضغط وتشفير. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/compression/7z/) . |
| static readonly [Tar](../../groupdocs.conversion.filetypes/compressionfiletype/tar) | الملفات ذات الامتداد .tar هي أرشيفات تم إنشاؤها باستخدام أداة مساعدة تستند إلى Unix لتجميع ملف واحد أو أكثر. يتم تخزين ملفات متعددة بتنسيق غير مضغوط بدعم من إضافة الملفات وكذلك المجلدات إلى الأرشيف. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/compression/tar/) . |
| static readonly [Xz](../../groupdocs.conversion.filetypes/compressionfiletype/xz) | XZ هو تنسيق ملف مضغوط يستخدم خوارزمية ضغط LZMA2. تم تصميمه كبديل لتنسيقات gzip و bzip2 الشائعة ، ويقدم عددًا من المزايا مقارنة بهذه المعايير القديمة . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/compression/xz/) . |
| static readonly [Z](../../groupdocs.conversion.filetypes/compressionfiletype/z) | ملف AZ هو فئة من الملفات التي تنتمي إلى ملفات بيانات UNIX المضغوطة. ملفات Unix المضغوطة هي أكثر أنواع الامتدادات شيوعًا والأكثر استخدامًا لملف Z. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/compression/z/) . |
| static readonly [Zip](../../groupdocs.conversion.filetypes/compressionfiletype/zip) | الملف ذو الامتداد .zip هو أرشيف يمكنه الاحتفاظ بملف أو مجلد واحد أو أكثر. يمكن أن يتم تطبيق ضغط الأرشيف على الملفات المضمنة لتقليل حجم ملف ZIP . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/compression/zip/) . |

### أنظر أيضا

* class [FileType](../filetype)
* مساحة الاسم [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* المجسم [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
