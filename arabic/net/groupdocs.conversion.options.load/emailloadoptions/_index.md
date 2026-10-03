---
title: "EmailLoadOptions"
second_title: "GroupDocs.Conversion لـ .NET مرجع API"
description: "خيارات تحميل مستندات البريد الإلكتروني."
type: docs
weight: 2500
url: /ar/net/groupdocs.conversion.options.load/emailloadoptions/
---
## EmailLoadOptions class

خيارات تحميل مستندات البريد الإلكتروني.

```csharp
public sealed class EmailLoadOptions : LoadOptions, ICustomCssStyleOptions, 
    IDocumentsContainerLoadOptions, IFontSubstituteLoadOptions, IPageLayoutOptions, 
    IPageMarginOptions, IPageOrientationOptions, IPageSizeOptions, IResourceLoadingOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmailLoadOptions](emailloadoptions)() | ينشئ مثيلاً جديدًا من الفئة [`EmailLoadOptions`](../emailloadoptions). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AttachmentIcons](../../groupdocs.conversion.options.load/emailloadoptions/attachmenticons) { get; set; } | يحصل أو يعيّن قائمة أيقونات المرفقات. يمكن تخصيص القائمة لتوفير أيقونات محددة لأنواع الملفات المختلفة. بشكل افتراضي، تحتوي على أيقونات أنواع الملفات الشائعة. |
| [ConvertOwned](../../groupdocs.conversion.options.load/emailloadoptions/convertowned) { get; set; } | يطبق [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned). القيمة الافتراضية هي true |
| [ConvertOwner](../../groupdocs.conversion.options.load/emailloadoptions/convertowner) { get; set; } | تنفيذ [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) القيمة الافتراضية هي true |
| [CustomCssStyle](../../groupdocs.conversion.options.load/emailloadoptions/customcssstyle) { get; set; } | ينفذ [`CustomCssStyle`](../icustomcssstyleoptions/customcssstyle) |
| [DefaultFont](../../groupdocs.conversion.options.load/emailloadoptions/defaultfont) { get; set; } | الخط الافتراضي لمستند البريد الإلكتروني. سيتم استخدام الخط التالي إذا كان الخط مفقودًا. |
| [Depth](../../groupdocs.conversion.options.load/emailloadoptions/depth) { get; set; } | تنفيذ [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) القيمة الافتراضية: 1 |
| [DisplayAttachments](../../groupdocs.conversion.options.load/emailloadoptions/displayattachments) { get; set; } | خيار لعرض أو إخفاء المرفقات في الرأس. الافتراضي: true. |
| [DisplayBccEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displaybccemailaddress) { get; set; } | خيار لعرض أو إخفاء عنوان البريد الإلكتروني "Bcc". الافتراضي: false. |
| [DisplayCcEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayccemailaddress) { get; set; } | خيار لعرض أو إخفاء عنوان البريد الإلكتروني "Cc". الافتراضي: false. |
| [DisplayEmailAddresses](../../groupdocs.conversion.options.load/emailloadoptions/displayemailaddresses) { get; set; } | خيار للتحكم فيما إذا كانت عناوين البريد الإلكتروني تُعرض بجانب الأسماء. مثال: "John Doe &lt;john.doe@sample.com&gt;" أو فقط "John Doe." الافتراضي: true. |
| [DisplayFromEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayfromemailaddress) { get; set; } | خيار لعرض أو إخفاء عنوان البريد الإلكتروني "from". الافتراضي: true. |
| [DisplayHeader](../../groupdocs.conversion.options.load/emailloadoptions/displayheader) { get; set; } | خيار لعرض أو إخفاء رأس البريد الإلكتروني. الافتراضي: true. |
| [DisplaySent](../../groupdocs.conversion.options.load/emailloadoptions/displaysent) { get; set; } | خيار لعرض أو إخفاء تاريخ/وقت الإرسال في الرأس. الافتراضي: true. |
| [DisplaySubject](../../groupdocs.conversion.options.load/emailloadoptions/displaysubject) { get; set; } | خيار لعرض أو إخفاء الموضوع في الرأس. الافتراضي: true. |
| [DisplayToEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displaytoemailaddress) { get; set; } | خيار لعرض أو إخفاء عنوان البريد الإلكتروني "to". الافتراضي: true. |
| [FieldTextMap](../../groupdocs.conversion.options.load/emailloadoptions/fieldtextmap) { get; set; } | التطابق بين رسالة البريد الإلكتروني [`EmailField`](../emailfield) وتمثيل النص الحقل |
| [FontSubstitutes](../../groupdocs.conversion.options.load/emailloadoptions/fontsubstitutes) { get; set; } | قائمة بدائل الخطوط. |
| [Format](../../groupdocs.conversion.options.load/emailloadoptions/format) { get; set; } | نوع ملف المستند المدخل. يكون `null` حتى يتم تعيين تنسيق، لذا اختبره مقابل `null` بدلاً من مقارنة بـ [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown)، والذي لا يساويه أبداً. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | نوع ملف المستند المدخل. |
| [MarginSettings](../../groupdocs.conversion.options.load/emailloadoptions/marginsettings) { get; set; } | إعدادات هوامش الصفحة |
| [OrientationSettings](../../groupdocs.conversion.options.load/emailloadoptions/orientationsettings) { get; set; } | إعدادات اتجاه الصفحة |
| [PageLayoutOptions](../../groupdocs.conversion.options.load/emailloadoptions/pagelayoutoptions) { get; set; } | ينفذ [`PageLayoutOptions`](../ipagelayoutoptions/pagelayoutoptions) |
| [PreserveOriginalDate](../../groupdocs.conversion.options.load/emailloadoptions/preserveoriginaldate) { get; set; } | يحدد ما إذا كان يجب الاحتفاظ بسلسلة تاريخ الرأس الأصلي في رسالة البريد عند الحفظ أم لا (القيمة الافتراضية هي true) |
| [ResourceLoadingTimeout](../../groupdocs.conversion.options.load/emailloadoptions/resourceloadingtimeout) { get; set; } | مهلة لتحميل الموارد الخارجية |
| [SizeSettings](../../groupdocs.conversion.options.load/emailloadoptions/sizesettings) { get; set; } | إعدادات حجم الصفحة |
| [SkipExternalResources](../../groupdocs.conversion.options.load/emailloadoptions/skipexternalresources) { get; set; } | تنفيذ [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [TimeZoneOffset](../../groupdocs.conversion.options.load/emailloadoptions/timezoneoffset) { get; set; } | يحصل أو يضبط إزاحة التوقيت العالمي المنسق (UTC) لتواريخ الرسائل. تُحدد هذه الخاصية فرق المنطقة الزمنية بين الوقت المحلي وUTC. |
| [UseDefaultAttachmentIcons](../../groupdocs.conversion.options.load/emailloadoptions/usedefaultattachmenticons) { get; set; } | يحصل أو يضبط ما إذا كان سيتم استخدام أيقونات المرفقات الافتراضية. الافتراضي: true. |
| [WhitelistedResources](../../groupdocs.conversion.options.load/emailloadoptions/whitelistedresources) { get; set; } | تنفيذ [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/emailloadoptions/clone)() | ينسخ النسخة الحالية. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | يحدد ما إذا كان مثيلان للكائن متساويين. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | يحدد ما إذا كان مثيلان للكائن متساويين. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | يعمل كدالة التجزئة الافتراضية. |

### انظر أيضًا

* class [LoadOptions](../loadoptions)
* interface [ICustomCssStyleOptions](../icustomcssstyleoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IPageLayoutOptions](../ipagelayoutoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageOrientationOptions](../../groupdocs.conversion.options/ipageorientationoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
