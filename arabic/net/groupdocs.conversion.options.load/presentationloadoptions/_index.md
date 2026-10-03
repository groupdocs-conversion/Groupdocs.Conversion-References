---
title: "PresentationLoadOptions"
second_title: "GroupDocs.Conversion لـ .NET مرجع API"
description: "خيارات تحميل مستندات Presentation."
type: docs
weight: 2770
url: /ar/net/groupdocs.conversion.options.load/presentationloadoptions/
---
## PresentationLoadOptions class

خيارات تحميل مستندات Presentation.

```csharp
public class PresentationLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IMetadataLoadOptions, IResourceLoadingOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PresentationLoadOptions](presentationloadoptions)() | يُنشئ مثلاً جديدًا من الفئة [`PresentationLoadOptions`](../presentationloadoptions). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/presentationloadoptions/clearbuiltindocumentproperties) { get; set; } | يزيل خصائص البيانات الوصفية المدمجة من المستند. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/presentationloadoptions/clearcustomdocumentproperties) { get; set; } | يزيل خصائص البيانات الوصفية المخصصة من المستند. |
| [CommentsPosition](../../groupdocs.conversion.options.load/presentationloadoptions/commentsposition) { get; set; } | يمثل الطريقة التي تُطبع بها التعليقات مع الشريحة. القيمة الافتراضية هي None. |
| [ConvertOwned](../../groupdocs.conversion.options.load/presentationloadoptions/convertowned) { get; set; } | تنفيذ [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) القيمة الافتراضية هي false |
| [ConvertOwner](../../groupdocs.conversion.options.load/presentationloadoptions/convertowner) { get; set; } | تنفيذ [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) القيمة الافتراضية هي true |
| [DefaultFont](../../groupdocs.conversion.options.load/presentationloadoptions/defaultfont) { get; set; } | الخط الافتراضي لتصيير العرض التقديمي. سيتم استخدام الخط التالي إذا كان خط العرض مفقودًا. |
| [Depth](../../groupdocs.conversion.options.load/presentationloadoptions/depth) { get; set; } | تنفيذ [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) القيمة الافتراضية: 1 |
| [FontSubstitutes](../../groupdocs.conversion.options.load/presentationloadoptions/fontsubstitutes) { get; set; } | استبدال الخطوط المحددة عند تحويل مستند العرض التقديمي. |
| [Format](../../groupdocs.conversion.options.load/presentationloadoptions/format) { get; set; } | نوع ملف المستند المدخل. يكون `null` حتى يتم تعيين تنسيق، لذا اختبره مقابل `null` بدلاً من مقارنة بـ [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown)، والذي لا يساويه أبداً. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | نوع ملف المستند المدخل. |
| [NotesPosition](../../groupdocs.conversion.options.load/presentationloadoptions/notesposition) { get; set; } | يمثل الطريقة التي تُطبع بها الملاحظات مع الشريحة. القيمة الافتراضية هي None. |
| [Password](../../groupdocs.conversion.options.load/presentationloadoptions/password) { get; set; } | تعيين كلمة مرور لإلغاء حماية المستند المحمي. |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/presentationloadoptions/preservedocumentstructure) { get; set; } | يحدد ما إذا كان يجب الحفاظ على بنية المستند عند التحويل إلى PDF (القيمة الافتراضية هي false). |
| [ShowHiddenSlides](../../groupdocs.conversion.options.load/presentationloadoptions/showhiddenslides) { get; set; } | إظهار الشرائح المخفية. |
| [SkipExternalResources](../../groupdocs.conversion.options.load/presentationloadoptions/skipexternalresources) { get; set; } | تنفيذ [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [WhitelistedResources](../../groupdocs.conversion.options.load/presentationloadoptions/whitelistedresources) { get; set; } | تنفيذ [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | يحدد ما إذا كان مثيلان للكائن متساويين. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | يحدد ما إذا كان مثيلان للكائن متساويين. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | يعمل كدالة التجزئة الافتراضية. |
| [SetVideoConnector](../../groupdocs.conversion.options.load/presentationloadoptions/setvideoconnector)(IPresentationVideoConnector) | حدد موصل مستند الفيديو |

### انظر أيضًا

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IMetadataLoadOptions](../imetadataloadoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
