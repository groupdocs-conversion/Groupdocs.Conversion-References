---
title: "WordProcessingConvertOptions"
second_title: "GroupDocs.Conversion لـ .NET مرجع API"
description: "خيارات التحويل إلى نوع ملف معالجة نصوص."
type: docs
weight: 2340
url: /ar/net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/
---
## WordProcessingConvertOptions class

خيارات التحويل إلى نوع ملف معالجة نصوص.

```csharp
public class WordProcessingConvertOptions : CommonConvertOptions<WordProcessingFileType>, 
    IDpiConvertOptions, IPageMarginOptions, IPageOrientationOptions, IPageSizeOptions, 
    IPasswordConvertOptions, IPdfRecognitionModeOptions, IZoomConvertOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [WordProcessingConvertOptions](wordprocessingconvertoptions)() | يُنشئ نسخة جديدة من الفئة [`WordProcessingConvertOptions`](../wordprocessingconvertoptions). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Dpi](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/dpi) { get; set; } | دقة DPI المطلوبة للصفحة بعد التحويل. الدقة الافتراضية هي: 96 نقطة في البوصة. |
| [FallbackPageSize](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/fallbackpagesize) { get; set; } | حجم الصفحة الاحتياطي |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | نوع الملف المطلوب تحويل المستند الإدخالي إليه. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | ينفذ [`Format`](../iconvertoptions/format) |
| [MarginSettings](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginsettings) { get; set; } | إعدادات هوامش الصفحة |
| [MarkdownOptions](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/markdownoptions) { get; set; } | يُطبق [`MarkdownOptions`](./markdownoptions) |
| [OrientationSettings](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/orientationsettings) { get; set; } | إعدادات اتجاه الصفحة |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | ينفذ [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | يطبق [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | يطبق [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [Password](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/password) { get; set; } | قم بتعيين هذه الخاصية إذا كنت ترغب في حماية المستند المحول بكلمة مرور. |
| [PdfRecognitionMode](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pdfrecognitionmode) { get; set; } | يُطبق [`PdfRecognitionMode`](../ipdfrecognitionmodeoptions/pdfrecognitionmode) |
| [RtfOptions](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/rtfoptions) { get; set; } | خيارات التحويل الخاصة بـ RTF |
| [SizeSettings](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/sizesettings) { get; set; } | إعدادات حجم الصفحة |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | يطبق [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [Zoom](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/zoom) { get; set; } | يحدد مستوى التكبير بالنسبة المئوية. القيمة الافتراضية هي 100. يدعم التكبير الافتراضي حتى Microsoft Word 2010. بدءًا من Microsoft Word 2013 لم يعد يتم تعيين التكبير الافتراضي للمستند، بل يبدو أنه يستخدم عامل التكبير للمستند الأخير المفتوح. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | ينسخ نسخة من كائن الخيارات الحالي. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | يحدد ما إذا كان مثيلان للكائن متساويين. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | يحدد ما إذا كان مثيلان للكائن متساويين. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | يعمل كدالة التجزئة الافتراضية. |

### انظر أيضًا

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [WordProcessingFileType](../../groupdocs.conversion.filetypes/wordprocessingfiletype)
* interface [IDpiConvertOptions](../idpiconvertoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageOrientationOptions](../../groupdocs.conversion.options/ipageorientationoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IPasswordConvertOptions](../ipasswordconvertoptions)
* interface [IPdfRecognitionModeOptions](../ipdfrecognitionmodeoptions)
* interface [IZoomConvertOptions](../izoomconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
