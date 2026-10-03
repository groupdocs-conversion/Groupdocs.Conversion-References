---
title: "WordProcessingLoadOptions"
second_title: "GroupDocs.Conversion لـ .NET مرجع API"
description: "خيارات تحميل مستندات WordProcessing."
type: docs
weight: 2950
url: /ar/net/groupdocs.conversion.options.load/wordprocessingloadoptions/
---
## WordProcessingLoadOptions class

خيارات تحميل مستندات WordProcessing.

```csharp
public class WordProcessingLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IFontTransformationLoadOptions, IMetadataLoadOptions, 
    IPageMarginOptions, IPageNumberingLoadOptions, IPageSizeOptions, IResourceLoadingOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [WordProcessingLoadOptions](wordprocessingloadoptions)() | يُنشئ مثيلاً جديدًا للفئة [`WordProcessingLoadOptions`](../wordprocessingloadoptions). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AutoDetectRtlDirection](../../groupdocs.conversion.options.load/wordprocessingloadoptions/autodetectrtldirection) { get; set; } | عند التعيين إلى true (الافتراضي)، سيتم إصلاح علامات bidi للفقرة والقطع التي يكون نصها يساريًا إلى يمينًا بشكل مهيمن قبل التحويل. يتطابق هذا مع الخوارزمية التي يستخدمها Microsoft Word وLibreOffice ويُصحح عرض المستندات العربية/العبرية التي ينتجها المولدون (وخاصة Google Docs) الذين يولّدون OOXML بدون &lt;w:bidi/&gt; ومع &lt;w:rtl w:val=\"0\"/&gt; على القطع التي تحتوي فقط على نص RTL. اضبطه إلى false للحفاظ على تفسير OOXML الصارم للعلامات المصدرية. |
| [BookmarkOptions](../../groupdocs.conversion.options.load/wordprocessingloadoptions/bookmarkoptions) { get; set; } | خيارات الإشارات المرجعية |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/wordprocessingloadoptions/clearbuiltindocumentproperties) { get; set; } | يزيل خصائص البيانات الوصفية المدمجة من المستند. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/wordprocessingloadoptions/clearcustomdocumentproperties) { get; set; } | يزيل خصائص البيانات الوصفية المخصصة من المستند. |
| [CommentDisplayMode](../../groupdocs.conversion.options.load/wordprocessingloadoptions/commentdisplaymode) { get; set; } | يحدد كيفية عرض التعليقات في المستند الناتج. الافتراضي هو ShowInBalloons. |
| [ConvertOwned](../../groupdocs.conversion.options.load/wordprocessingloadoptions/convertowned) { get; set; } | تنفيذ [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) القيمة الافتراضية هي false |
| [ConvertOwner](../../groupdocs.conversion.options.load/wordprocessingloadoptions/convertowner) { get; set; } | تنفيذ [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) القيمة الافتراضية هي true |
| [DefaultFont](../../groupdocs.conversion.options.load/wordprocessingloadoptions/defaultfont) { get; set; } | يضبط الخط الافتراضي لمستند WordProcessing. |
| [Depth](../../groupdocs.conversion.options.load/wordprocessingloadoptions/depth) { get; set; } | تنفيذ [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) القيمة الافتراضية: 1 |
| [EmbedTrueTypeFonts](../../groupdocs.conversion.options.load/wordprocessingloadoptions/embedtruetypefonts) { get; set; } | إذا كان EmbedTrueTypeFonts صحيحًا، فإن GroupDocs.Conversion يدمج خطوط True Type في المستند الناتج. القيمة الافتراضية: true |
| [FontConfigSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontconfigsubstitutionenabled) { get; set; } | يستبدل الخطوط المفقودة تلقائيًا بناءً على FontConfig في النظام. القيمة الافتراضية: false. |
| [FontInfoSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontinfosubstitutionenabled) { get; set; } | يستبدل الخطوط المفقودة تلقائيًا بناءً على FontInfo في المستند. القيمة الافتراضية: false. |
| [FontNameSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontnamesubstitutionenabled) { get; set; } | يستبدل الخطوط المفقودة تلقائيًا بناءً على اسم الخط. القيمة الافتراضية: false. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontsubstitutes) { get; set; } | يستبدل خطوطًا محددة عند تحويل مستند WordsProcessing. |
| [FontTransformations](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fonttransformations) { get; set; } | تحويل الخطوط الموجودة بعد اكتمال تحميل المستند واستبدال الخطوط. يمكن لتحويلات الخطوط تعديل أي خطوط في المستند، بما في ذلك الخطوط التي تم تحميلها بنجاح. |
| [Format](../../groupdocs.conversion.options.load/wordprocessingloadoptions/format) { get; set; } | نوع ملف المستند المدخل. يكون `null` حتى يتم تعيين تنسيق، لذا اختبره مقابل `null` بدلاً من مقارنة بـ [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown)، والذي لا يساويه أبداً. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | نوع ملف المستند المدخل. |
| [HideWordTrackedChanges](../../groupdocs.conversion.options.load/wordprocessingloadoptions/hidewordtrackedchanges) { get; set; } | إخفاء العلامات وتتبع التغييرات لمستندات Word. |
| [HyphenationOptions](../../groupdocs.conversion.options.load/wordprocessingloadoptions/hyphenationoptions) { get; set; } | ضبط خيارات التجزئة لكلمات المستندات WordProcessing. |
| [KeepDateFieldOriginalValue](../../groupdocs.conversion.options.load/wordprocessingloadoptions/keepdatefieldoriginalvalue) { get; set; } | الاحتفاظ بالقيمة الأصلية لحقل التاريخ. القيمة الافتراضية: false |
| [MarginSettings](../../groupdocs.conversion.options.load/wordprocessingloadoptions/marginsettings) { get; set; } | إعدادات هوامش الصفحة |
| [PageNumbering](../../groupdocs.conversion.options.load/wordprocessingloadoptions/pagenumbering) { get; set; } | تمكين أو تعطيل إنشاء ترقيم الصفحات في المستند المحول. القيمة الافتراضية: false |
| [Password](../../groupdocs.conversion.options.load/wordprocessingloadoptions/password) { get; set; } | تعيين كلمة مرور لإلغاء حماية المستند المحمي. |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/wordprocessingloadoptions/preservedocumentstructure) { get; set; } | يحدد ما إذا كان يجب الحفاظ على بنية المستند عند التحويل إلى PDF (القيمة الافتراضية هي false). |
| [PreserveFormFields](../../groupdocs.conversion.options.load/wordprocessingloadoptions/preserveformfields) { get; set; } | يحدد ما إذا كان يجب الحفاظ على حقول نماذج Microsoft Word كحقول نماذج في PDF أو تحويلها إلى نص. القيمة الافتراضية هي false. |
| [ShowFullCommenterName](../../groupdocs.conversion.options.load/wordprocessingloadoptions/showfullcommentername) { get; set; } | عرض الاسم الكامل للمعلق في التعليقات. القيمة الافتراضية هي false. |
| [SizeSettings](../../groupdocs.conversion.options.load/wordprocessingloadoptions/sizesettings) { get; set; } | إعدادات حجم الصفحة |
| [SkipExternalResources](../../groupdocs.conversion.options.load/wordprocessingloadoptions/skipexternalresources) { get; set; } | تنفيذ [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [UpdateFields](../../groupdocs.conversion.options.load/wordprocessingloadoptions/updatefields) { get; set; } | تحديث الحقول بعد التحميل. القيمة الافتراضية: false |
| [UpdatePageLayout](../../groupdocs.conversion.options.load/wordprocessingloadoptions/updatepagelayout) { get; set; } | تحديث تخطيط الصفحة بعد التحميل. القيمة الافتراضية: false |
| [UseTextShaper](../../groupdocs.conversion.options.load/wordprocessingloadoptions/usetextshaper) { get; set; } | يحدد ما إذا كان يجب استخدام مُشكل نص لتحسين عرض التباعد بين الحروف. القيمة الافتراضية هي false. |
| [WhitelistedResources](../../groupdocs.conversion.options.load/wordprocessingloadoptions/whitelistedresources) { get; set; } | تنفيذ [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | يحدد ما إذا كان مثيلان للكائن متساويين. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | يحدد ما إذا كان مثيلان للكائن متساويين. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | يعمل كدالة التجزئة الافتراضية. |

### ملاحظات

**Font Processing Pipeline:**

**Phase 1 - Font Substitution (during document loading):**

• يتعامل مع الخطوط المفقودة/غير المتوفرة باستخدام FontSubstitutes و DefaultFont واستبدال النظام

• ترتيب المعالجة: FontName → FontConfig → FontSubstitutes → FontInfo → DefaultFont

**Phase 2 - Font Replacement (after document loading):**

• يعدل أي خطوط موجودة في المستند المحمَّل باستخدام FontReplacements

• يُطبق بعد اكتمال جميع استبدالات الخطوط

### انظر أيضًا

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IFontTransformationLoadOptions](../ifonttransformationloadoptions)
* interface [IMetadataLoadOptions](../imetadataloadoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageNumberingLoadOptions](../ipagenumberingloadoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
