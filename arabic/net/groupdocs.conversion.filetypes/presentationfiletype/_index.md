---
title: PresentationFileType
second_title: GroupDocs.Conversion لمرجع .NET API
description: يحدد تنسيقات ملفات العرض التقديمي التي تخزن مجموعة من السجلات لتلائم بيانات العرض التقديمي مثل الشرائح والأشكال والنص والرسوم المتحركة والفيديو والصوت والكائنات المضمنة. يتضمن أنواع الملفات التالية Odp./presentationfiletype/odp  Otp./presentationfiletype/otp  Pot./presentationfiletype/pot  Potm./presentationfiletype/potm  Potx./presentationfiletype/potx  Pps./presentationfiletype/pps  Ppsm./presentationfiletype/ppsm  Ppsx./presentationfiletype/ppsx  Ppt./presentationfiletype/ppt  Pptm./presentationfiletype/pptm  Pptx./presentationfiletype/pptx . تعرف على المزيد حول تنسيقات العروض التقديميةهناhttps//wiki.fileformat.com/presentation .
type: docs
weight: 910
url: /ar/net/groupdocs.conversion.filetypes/presentationfiletype/
---
## PresentationFileType class

يحدد تنسيقات ملفات العرض التقديمي التي تخزن مجموعة من السجلات لتلائم بيانات العرض التقديمي مثل الشرائح والأشكال والنص والرسوم المتحركة والفيديو والصوت والكائنات المضمنة. يتضمن أنواع الملفات التالية: [`Odp`](./odp) ، [`Otp`](./otp) ، [`Pot`](./pot) ، [`Potm`](./potm) ، [`Potx`](./potx) ، [`Pps`](./pps) ، [`Ppsm`](./ppsm) ، [`Ppsx`](./ppsx) ، [`Ppt`](./ppt) ، [`Pptm`](./pptm) ، [`Pptx`](./pptx) . تعرف على المزيد حول تنسيقات العروض التقديمية[هنا](https://wiki.fileformat.com/presentation) .

```csharp
public sealed class PresentationFileType : FileType
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PresentationFileType](presentationfiletype)() | مُنشئ التسلسل |

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
| static readonly [Fodp](../../groupdocs.conversion.filetypes/presentationfiletype/fodp) | الملفات ذات الامتداد FODP تمثل OpenDocument Flat XML Presentation. تم حفظ ملف العرض التقديمي بتنسيق OpenDocument ، ولكن تم حفظه باستخدام تنسيق XML ثابت بدلاً من حاوية .ZIP المستخدمة بواسطة ملفات .ODP القياسية |
| static readonly [Odp](../../groupdocs.conversion.filetypes/presentationfiletype/odp) | تمثل الملفات ذات الامتداد ODP تنسيق ملف العرض التقديمي المستخدم بواسطة OpenOffice.org في معيار OASISOpen . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [Otp](../../groupdocs.conversion.filetypes/presentationfiletype/otp) | تمثل الملفات ذات الامتداد .OTP ملفات قالب العرض التقديمي التي تم إنشاؤها بواسطة التطبيقات بتنسيق OASIS OpenDocument القياسي . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [Pot](../../groupdocs.conversion.filetypes/presentationfiletype/pot) | تمثل الملفات ذات الامتداد .POT ملفات قوالب Microsoft PowerPoint التي تم إنشاؤها بواسطة إصدارات PowerPoint 97-2003. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [Potm](../../groupdocs.conversion.filetypes/presentationfiletype/potm) | الملفات ذات الامتداد POTM هي ملفات قوالب Microsoft PowerPoint مع دعم لوحدات الماكرو. يتم إنشاء ملفات POTM باستخدام PowerPoint 2007 أو إصدار أحدث وتحتوي على الإعدادات الافتراضية التي يمكن استخدامها لإنشاء المزيد من ملفات العروض التقديمية . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [Potx](../../groupdocs.conversion.filetypes/presentationfiletype/potx) | الملفات ذات الامتداد .POTX تمثل العروض التقديمية لقوالب Microsoft PowerPoint التي تم إنشاؤها باستخدام Microsoft PowerPoint 2007 والإصدارات الأحدث . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [Pps](../../groupdocs.conversion.filetypes/presentationfiletype/pps) | PPS ، عرض شرائح PowerPoint ، يتم إنشاء الملفات باستخدام Microsoft PowerPoint لغرض عرض الشرائح. يتم دعم قراءة ملف PPS وإنشائه بواسطة Microsoft PowerPoint 97-2003. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [Ppsm](../../groupdocs.conversion.filetypes/presentationfiletype/ppsm) | تمثل الملفات ذات الامتداد PPSM تنسيق ملف عرض الشرائح ممكّن بماكرو تم إنشاؤه باستخدام Microsoft PowerPoint 2007 أو أعلى . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [Ppsx](../../groupdocs.conversion.filetypes/presentationfiletype/ppsx) | PPSX ، عرض شرائح Power Point ، يتم إنشاء الملف باستخدام Microsoft PowerPoint 2007 والإصدارات الأحدث لغرض عرض الشرائح. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [Ppt](../../groupdocs.conversion.filetypes/presentationfiletype/ppt) | يمثل ملف بامتداد PPT ملف PowerPoint يتكون من مجموعة من الشرائح لعرضها على هيئة عرض شرائح. تحدد تنسيق الملف الثنائي المستخدم بواسطة Microsoft PowerPoint 97-2003. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [Pptm](../../groupdocs.conversion.filetypes/presentationfiletype/pptm) | الملفات ذات الامتداد PPTM هي ملفات عرض تقديمية تم تمكين الماكرو تم إنشاؤها باستخدام Microsoft PowerPoint 2007 أو الإصدارات الأحدث . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [Pptx](../../groupdocs.conversion.filetypes/presentationfiletype/pptx) | الملفات ذات امتداد PPTX هي ملفات عروض تقديمية تم إنشاؤها باستخدام تطبيق Microsoft PowerPoint الشهير. على عكس الإصدار السابق من تنسيق ملف العرض التقديمي PPT الذي كان ثنائيًا ، يعتمد تنسيق PPTX على تنسيق ملف العرض التقديمي XML المفتوح لبرنامج Microsoft PowerPoint. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/pptx) . |

### أنظر أيضا

* class [FileType](../filetype)
* مساحة الاسم [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* المجسم [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
