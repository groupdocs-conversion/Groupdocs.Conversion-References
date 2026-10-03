---
title: "CompressionFileType"
second_title: "GroupDocs.Conversion لـ .NET مرجع API"
description: "يحدد صيغ الضغط. يتضمن أنواع الملفات التالية Zip./compressionfiletype/zip. Rar./compressionfiletype/rar. SevenZ./compressionfiletype/sevenz. Tar./compressionfiletype/tar. Gz./compressionfiletype/gz. Gzip./compressionfiletype/gzip. Bz2./compressionfiletype/bz2. Lz./compressionfiletype/lz. Z./compressionfiletype/z. Xz./compressionfiletype/xz. Xz./compressionfiletype/xz. Cpio./compressionfiletype/cpio. Cab./compressionfiletype/cab. Lzma./compressionfiletype/lzma. Zst./compressionfiletype/zst. Uue./compressionfiletype/uue. Lha./compressionfiletype/lha. Lz4./compressionfiletype/lz4. Xar./compressionfiletype/xar. Wim./compressionfiletype/wim. Aar./compressionfiletype/aar. Alz./compressionfiletype/alz. تعرف على المزيد حول صيغ الضغط هناhttps//docs.fileformat.com/compression/."
type: docs
weight: 1080
url: /ar/net/groupdocs.conversion.filetypes/compressionfiletype/
---
## CompressionFileType class

يحدد صيغ الضغط. يتضمن أنواع الملفات التالية: [`Zip`](./zip). [`Rar`](./rar). [`SevenZ`](./sevenz). [`Tar`](./tar). [`Gz`](./gz). [`Gzip`](./gzip). [`Bz2`](./bz2). [`Lz`](./lz). [`Z`](./z). [`Xz`](./xz). [`Xz`](./xz). [`Cpio`](./cpio). [`Cab`](./cab). [`Lzma`](./lzma). [`Zst`](./zst). [`Uue`](./uue). [`Lha`](./lha). [`Lz4`](./lz4). [`Xar`](./xar). [`Wim`](./wim). [`Aar`](./aar). [`Alz`](./alz). تعرف على المزيد حول صيغ الضغط [هنا](https://docs.fileformat.com/compression/).

```csharp
public sealed class CompressionFileType : FileType
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | وصف نوع الملف |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | امتداد الملف |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | عائلة الملف |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | صيغة الملف |
| [IsMultiFileArchive](../../groupdocs.conversion.filetypes/compressionfiletype/ismultifilearchive) { get; } | يحدد ما إذا كانت الصيغة تدعم ملفات/مجلدات متعددة في أرشيف واحد. |

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
| static readonly [Aar](../../groupdocs.conversion.filetypes/compressionfiletype/aar) | الملف ذو الامتداد .aar هو أرشيف Apple، الحاوية التي تقدمها Apple مع macOS لتجميع الملفات والمجلدات. كل إدخال يُضغط بشكل منفصل، غالبًا باستخدام LZFSE. |
| static readonly [Alz](../../groupdocs.conversion.filetypes/compressionfiletype/alz) | الملف ذو الامتداد .alz هو أرشيف ALZip، صيغة من ESTsoft تُستخدم على نطاق واسع في كوريا الجنوبية. قد يتم تشفير الإدخالات بشكل فردي بكلمة مرور. تعرف على المزيد حول صيغة الملف هذه [هنا](https://docs.fileformat.com/compression/alz/). |
| static readonly [Bz2](../../groupdocs.conversion.filetypes/compressionfiletype/bz2) | ملفات BZ2 هي ملفات مضغوطة تم إنشاؤها باستخدام طريقة الضغط المفتوحة المصدر BZIP2، غالبًا على أنظمة UNIX أو Linux. تُستخدم لضغط ملف واحد ولا تُقصد لأرشفة ملفات متعددة. تعرف على المزيد حول صيغة الملف هذه [هنا](https://docs.fileformat.com/compression/bz2/). |
| static readonly [Cab](../../groupdocs.conversion.filetypes/compressionfiletype/cab) | الملف ذو الامتداد .cab هو ملف خزانة Windows ينتمي إلى فئة ملفات النظام. يتم حفظه بصيغة ملف أرشيف في إصدارات Microsoft Windows التي تدعم خوارزميات البيانات المضغوطة، مثل LZX وQuantum وZIP. تعرف على المزيد حول صيغة الملف هذه [هنا](https://docs.fileformat.com/system/cab/). |
| static readonly [Cpio](../../groupdocs.conversion.filetypes/compressionfiletype/cpio) | Cpio هو أداة أرشفة ملفات عامة وصيغتها المرتبطة. يتم تثبيته أساسًا على أنظمة تشغيل شبيهة Unix. |
| static readonly [Gz](../../groupdocs.conversion.filetypes/compressionfiletype/gz) | ملف GZ هو أرشيف مضغوط يتم إنشاؤه باستخدام خوارزمية الضغط القياسية gzip (GNU zip). قد يحتوي على ملفات مضغوطة متعددة، أدلة وملفات تجريبية. تعرف على المزيد حول صيغة الملف هذه [هنا](https://docs.fileformat.com/compression/gz/). |
| static readonly [Gzip](../../groupdocs.conversion.filetypes/compressionfiletype/gzip) | ملف Gzip هو أرشيف مضغوط يتم إنشاؤه باستخدام خوارزمية الضغط القياسية gzip (GNU zip). قد يحتوي على ملفات مضغوطة متعددة، أدلة وملفات تجريبية. تعرف على المزيد حول صيغة الملف هذه [هنا](https://docs.fileformat.com/compression/gz/). |
| static readonly [Iso](../../groupdocs.conversion.filetypes/compressionfiletype/iso) | ملف بامتداد .iso هو ملف صورة قرص أرشيف غير مضغوط يمثل محتويات البيانات الكاملة على قرص بصري مثل CD أو DVD. استنادًا إلى معيار ISO-9660، يحتوي تنسيق ملف صورة ISO على بيانات القرص بالإضافة إلى معلومات نظام الملفات المخزنة فيه. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/compression/iso/). |
| static readonly [Lha](../../groupdocs.conversion.filetypes/compressionfiletype/lha) | الملف بامتداد .lzh و .lha عادةً ما يتعلق بتنسيق ملف ضغط أرشيف. هذا التنسيق هو نفسه تنسيقات ضغط الملفات الأخرى مثل ZIP و RAR وغيرها. الهدف الرئيسي من هذه التنسيقات هو تقليل حجم الملف لتسهيل إرساله وكذلك الحفاظ عليه في شكل مضغوط. |
| static readonly [Lz](../../groupdocs.conversion.filetypes/compressionfiletype/lz) | الملف بامتداد .lz هو ملف أرشيف مضغوط تم إنشاؤه باستخدام Lzip، وهو أداة سطر أوامر مجانية للضغط. يدعم الجمع لضغط ملفات الدعم. ملفات LZ لها نوع وسائط application/lzip وتدعم نسب ضغط أعلى من BZ2. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/compression/bz2/). |
| static readonly [Lz4](../../groupdocs.conversion.filetypes/compressionfiletype/lz4) | الملف بامتداد .lz4 هو ملف أرشيف مضغوط تم إنشاؤه باستخدام التطبيقات/الأدوات التي تدعم ضغط LZ4. يركز خوارزمية LZ4 على الموازنة بين السرعة ونسبة الضغط. يمكن إنشاء أرشيفات LZ4 المضغوطة باستخدام أداة سطر الأوامر LZ4 ويمكن فك ضغطها باستخدام نفس الأداة. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/compression/lz4/). |
| static readonly [Lzma](../../groupdocs.conversion.filetypes/compressionfiletype/lzma) | الملف بامتداد .lzma هو ملف أرشيف مضغوط تم إنشاؤه باستخدام طريقة الضغط LZMA (خوارزمية ليمبل-زيف-ماركوف). تُستخدم هذه الملفات أساسًا على نظام تشغيل Unix وتتشابه مع خوارزميات الضغط الأخرى مثل ZIP لتقليل حجم الملف. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/compression/lzma/). |
| static readonly [Rar](../../groupdocs.conversion.filetypes/compressionfiletype/rar) | الملفات بامتداد .rar هي ملفات أرشيف تُنشأ لتخزين المعلومات بصيغة مضغوطة أو عادية. RAR هو اختصار لـ Roshal ARchive format. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/compression/rar/). |
| static readonly [SevenZ](../../groupdocs.conversion.filetypes/compressionfiletype/sevenz) | 7z هو تنسيق أرشفة لضغط الملفات والمجلدات بنسبة ضغط عالية. يعتمد على بنية مفتوحة المصدر مما يتيح إمكانية استخدام أي خوارزميات ضغط وتشفير. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/compression/7z/). |
| static readonly [Tar](../../groupdocs.conversion.filetypes/compressionfiletype/tar) | الملفات بامتداد .tar هي أرشيفات تم إنشاؤها باستخدام أداة قائمة على Unix لجمع ملف واحد أو أكثر. تُخزن الملفات المتعددة بصيغة غير مضغوطة مع إمكانية إضافة ملفات ومجلدات إلى الأرشيف. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/compression/tar/). |
| static readonly [Uue](../../groupdocs.conversion.filetypes/compressionfiletype/uue) | الأرشيف المشفر بصيغة uuencode هو ملف أو مجموعة ملفات تم ترميزها باستخدام مخطط الترميز Unix-to-Unix (uuencode). يحول هذا الأسلوب البيانات الثنائية إلى صيغة نصية، مما يسهل إرسال الملفات عبر القنوات التي تدعم النص فقط، مثل البريد الإلكتروني. |
| static readonly [Wim](../../groupdocs.conversion.filetypes/compressionfiletype/wim) | الملف بامتداد .wim هو أرشيف بصيغة Windows Imaging Format، وهو صورة قرص مبنية على الملفات تستخدمها مايكروسوفت لنشر نظام Windows. يحتوي الأرشيف الواحد على صورة واحدة أو أكثر ويخزن كل ملف مرة واحدة فقط، بغض النظر عن عدد الصور التي تشير إليه. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/disc-and-media/wim/). |
| static readonly [Xar](../../groupdocs.conversion.filetypes/compressionfiletype/xar) | الملف بامتداد .xar هو eXtensible ARchive، وهو تنسيق مبني حول جدول محتويات مخزن كملف XML مضغوط. يُستخدم لتوزيع حزم تثبيت macOS ويحافظ على ضغط كل مدخل على حدة. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/compression/xar/). |
| static readonly [Xz](../../groupdocs.conversion.filetypes/compressionfiletype/xz) | XZ هو تنسيق ملف مضغوط يستخدم خوارزمية الضغط LZMA2. صُمم كبديل لتنسيقات gzip و bzip2 الشهيرة، ويقدم عددًا من المزايا مقارنةً بهذه المعايير القديمة. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/compression/xz/). |
| static readonly [Z](../../groupdocs.conversion.filetypes/compressionfiletype/z) | ملف Z هو فئة من الملفات التي تنتمي إلى ملفات البيانات المضغوطة في UNIX. ملفات UNIX المضغوطة هي النوع الأكثر شعبية واستخدامًا على نطاق واسع من امتداد ملف Z. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/compression/z/). |
| static readonly [Zip](../../groupdocs.conversion.filetypes/compressionfiletype/zip) | الملف ذو امتداد .zip هو أرشيف يمكنه احتواء ملف واحد أو أكثر أو أدلة. يمكن تطبيق الضغط على الملفات المضمنة في الأرشيف لتقليل حجم ملف ZIP. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/compression/zip/). |
| static readonly [Zst](../../groupdocs.conversion.filetypes/compressionfiletype/zst) | ملف ZST هو ملف مضغوط يتم إنشاؤه باستخدام خوارزمية الضغط Zstandard (zstd). إنه ملف مضغوط تم إنشاؤه بضغط غير فقدان للبيانات بواسطة الخوارزمية. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/compression/zst/). |

### انظر أيضًا

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
