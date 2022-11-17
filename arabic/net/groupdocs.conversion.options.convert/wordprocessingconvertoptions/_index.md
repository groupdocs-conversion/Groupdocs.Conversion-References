---
title: WordProcessingConvertOptions
second_title: GroupDocs.Conversion لمرجع .NET API
description: خيارات للتحويل إلى نوع ملف معالجة الكلمات.
type: docs
weight: 1810
url: /ar/net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/
---
## WordProcessingConvertOptions class

خيارات للتحويل إلى نوع ملف معالجة الكلمات.

```csharp
public class WordProcessingConvertOptions : CommonConvertOptions<WordProcessingFileType>, 
    IPageMarginConvertOptions, IPageOrientationConvertOptions, IPageSizeConvertOptions, 
    IPdfRecognitionModeOptions
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [WordProcessingConvertOptions](wordprocessingconvertoptions)() | تهيئة مثيل جديد لـ[`WordProcessingConvertOptions`](../wordprocessingconvertoptions) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Dpi](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/dpi) { get; set; } | الصفحة المطلوبة DPI بعد التحويل. الدقة الافتراضية هي: 96 نقطة في البوصة . |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | نوع الملف المطلوب يجب تحويل مستند الإدخال إليه. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | نوع الملف المطلوب يجب تحويل مستند الإدخال إليه. |
| [Height](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/height) { get; set; } | ارتفاع الصفحة المطلوب بعد التحويل. |
| [MarginBottom](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginbottom) { get; set; } | الهامش السفلي للصفحة المرغوب فيه بالبكسل بعد التحويل. |
| [MarginLeft](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginleft) { get; set; } | الهامش الأيسر للصفحة المرغوبة بالبكسل بعد التحويل. |
| [MarginRight](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginright) { get; set; } | الهامش الأيمن للصفحة المطلوبة بالبكسل بعد التحويل. |
| [MarginTop](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/margintop) { get; set; } | الهامش العلوي المطلوب للصفحة بالبكسل بعد التحويل. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | رقم الصفحة الذي سيبدأ التحويل منه . |
| [PageOrientation](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pageorientation) { get; set; } | اتجاه الصفحة المطلوب بعد التحويل |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | قائمة فهارس الصفحات المطلوب تحويلها. يجب تحديده لتحويل صفحات معينة. |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | عدد الصفحات المطلوب التحويل منها بدءًا من`رقم الصفحة` . |
| [PageSize](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pagesize) { get; set; } | حجم الصفحة المطلوب بعد التحويل |
| [Password](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/password) { get; set; } | قم بتعيين هذه الخاصية إذا كنت تريد حماية المستند المحول بكلمة مرور. |
| [PdfRecognitionMode](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pdfrecognitionmode) { get; set; } | وضع التعرف عند التحويل من pdf |
| [RtfOptions](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/rtfoptions) { get; set; } | خيارات تحويل محددة RTF |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | خيارات محددة للعلامة المائية |
| [Width](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/width) { get; set; } | عرض الصفحة المطلوب بعد التحويل . |
| [Zoom](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/zoom) { get; set; } | يحدد مستوى التكبير بالنسبة المئوية. الافتراضي هو 100. يتم دعم التكبير الافتراضي حتى Microsoft Word 2010. بدءًا من Microsoft Word 2013 ، لم يعد التكبير الافتراضي قد تم تعيينه للمستند ، وبدلاً من ذلك يبدو أنه يستخدم عامل التكبير / التصغير الخاص بآخر مستند تم فتحه. |

## طُرق

| اسم | وصف |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | مثيل الخيارات الحالية للنسخ . |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | تحديد ما إذا كان مثيلا الكائن متساويان. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | تحديد ما إذا كان مثيلا الكائن متساويان. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | تعمل كوظيفة تجزئة افتراضية . |

### أنظر أيضا

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [WordProcessingFileType](../../groupdocs.conversion.filetypes/wordprocessingfiletype)
* interface [IPageMarginConvertOptions](../ipagemarginconvertoptions)
* interface [IPageOrientationConvertOptions](../ipageorientationconvertoptions)
* interface [IPageSizeConvertOptions](../ipagesizeconvertoptions)
* interface [IPdfRecognitionModeOptions](../ipdfrecognitionmodeoptions)
* مساحة الاسم [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* المجسم [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
