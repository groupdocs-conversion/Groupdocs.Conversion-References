---
title: "PresentationFileType"
second_title: "GroupDocs.Conversion لـ .NET مرجع API"
description: "يحدد تنسيقات ملفات العرض التي تخزن مجموعة من السجلات لاستيعاب بيانات العرض مثل الشرائح والأشكال والنصوص والرسوم المتحركة والفيديو والصوت والكائنات المدمجة. يتضمن أنواع الملفات التالية Odp./presentationfiletype/odp Otp./presentationfiletype/otp Pot./presentationfiletype/pot Potm./presentationfiletype/potm Potx./presentationfiletype/potx Pps./presentationfiletype/pps Ppsm./presentationfiletype/ppsm Ppsx./presentationfiletype/ppsx Ppt./presentationfiletype/ppt Pptm./presentationfiletype/pptm Pptx./presentationfiletype/pptx. تعرف على تنسيقات العرض هناhttps//wiki.fileformat.com/presentation."
type: docs
weight: 1210
url: /ar/net/groupdocs.conversion.filetypes/presentationfiletype/
---
## PresentationFileType class

يحدد تنسيقات ملفات العرض التي تخزن مجموعة من السجلات لاستيعاب بيانات العرض مثل الشرائح، والأشكال، والنص، والرسوم المتحركة، والفيديو، والصوت والكائنات المدمجة. يتضمن أنواع الملفات التالية: [`Odp`](./odp), [`Otp`](./otp), [`Pot`](./pot), [`Potm`](./potm), [`Potx`](./potx), [`Pps`](./pps), [`Ppsm`](./ppsm), [`Ppsx`](./ppsx), [`Ppt`](./ppt), [`Pptm`](./pptm), [`Pptx`](./pptx). تعرف على تنسيقات العرض [هنا](https://wiki.fileformat.com/presentation).

```csharp
public sealed class PresentationFileType : FileType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PresentationFileType](presentationfiletype)() | منشئ التسلسل |

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
| static readonly [Fodp](../../groupdocs.conversion.filetypes/presentationfiletype/fodp) | الملفات ذات الامتداد FODP تمثل عرض OpenDocument Flat XML. يتم حفظ ملف العرض بتنسيق OpenDocument، ولكن يتم حفظه باستخدام تنسيق XML مسطح بدلاً من حاوية .ZIP المستخدمة في ملفات .ODP القياسية. |
| static readonly [Odp](../../groupdocs.conversion.filetypes/presentationfiletype/odp) | الملفات ذات الامتداد ODP تمثل تنسيق ملف عرض يستخدمه OpenOffice.org في معيار OASISOpen. تعرف على هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/odp). |
| static readonly [Otp](../../groupdocs.conversion.filetypes/presentationfiletype/otp) | الملفات ذات الامتداد .OTP تمثل ملفات قوالب عرض تم إنشاؤها بواسطة التطبيقات في تنسيق معيار OASIS OpenDocument. تعرف على هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/otp). |
| static readonly [Pot](../../groupdocs.conversion.filetypes/presentationfiletype/pot) | الملفات ذات الامتداد .POT تمثل ملفات قوالب Microsoft PowerPoint التي تم إنشاؤها بواسطة إصدارات PowerPoint 97-2003. تعرف على هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/pot). |
| static readonly [Potm](../../groupdocs.conversion.filetypes/presentationfiletype/potm) | الملفات ذات الامتداد POTM هي ملفات قوالب Microsoft PowerPoint مع دعم للماكرو. يتم إنشاء ملفات POTM باستخدام PowerPoint 2007 أو أحدث وتحتوي على إعدادات افتراضية يمكن استخدامها لإنشاء ملفات عرض أخرى. تعرف على هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/potm). |
| static readonly [Potx](../../groupdocs.conversion.filetypes/presentationfiletype/potx) | الملفات ذات الامتداد .POTX تمثل عروض قوالب Microsoft PowerPoint التي تم إنشاؤها باستخدام Microsoft PowerPoint 2007 وما فوق. تعرف على هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/potx). |
| static readonly [Pps](../../groupdocs.conversion.filetypes/presentationfiletype/pps) | ملفات PPS، PowerPoint Slide Show، يتم إنشاؤها باستخدام Microsoft PowerPoint لغرض عرض الشرائح. يتم دعم قراءة وإنشاء ملفات PPS بواسطة Microsoft PowerPoint 97-2003. تعرف على هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/pps). |
| static readonly [Ppsm](../../groupdocs.conversion.filetypes/presentationfiletype/ppsm) | الملفات ذات الامتداد PPSM تمثل تنسيق ملف عرض الشرائح المدعوم بالماكرو والذي تم إنشاؤه باستخدام Microsoft PowerPoint 2007 أو أحدث. تعرف على هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/ppsm). |
| static readonly [Ppsx](../../groupdocs.conversion.filetypes/presentationfiletype/ppsx) | ملفات PPSX، Power Point Slide Show، يتم إنشاؤها باستخدام Microsoft PowerPoint 2007 وما فوق لغرض عرض الشرائح. تعرف على هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/ppsx). |
| static readonly [Ppt](../../groupdocs.conversion.filetypes/presentationfiletype/ppt) | الملف ذو الامتداد PPT يمثل ملف PowerPoint يتكون من مجموعة من الشرائح لعرضها كعرض شرائح. يحدد تنسيق الملف الثنائي المستخدم بواسطة Microsoft PowerPoint 97-2003. تعرف على هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/ppt). |
| static readonly [Pptm](../../groupdocs.conversion.filetypes/presentationfiletype/pptm) | الملفات ذات الامتداد PPTM هي ملفات عرض مدعومة بالماكرو تم إنشاؤها باستخدام Microsoft PowerPoint 2007 أو إصدارات أعلى. تعرف على هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/pptm). |
| static readonly [Pptx](../../groupdocs.conversion.filetypes/presentationfiletype/pptx) | الملفات ذات امتداد PPTX هي ملفات عروض تقديمية تم إنشاؤها باستخدام تطبيق Microsoft PowerPoint الشهير. على عكس النسخة السابقة من تنسيق ملف العرض PPT الذي كان ثنائيًا، يعتمد تنسيق PPTX على تنسيق ملف عرض Microsoft PowerPoint المفتوح XML. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/pptx). |

### انظر أيضًا

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
