---
title: ThreeDConvertOptions
second_title: GroupDocs.Conversion لمرجع .NET API
description: خيارات للتحويل إلى النوع ثلاثي الأبعاد .
type: docs
weight: 1910
url: /ar/net/groupdocs.conversion.options.convert/threedconvertoptions/
---
## ThreeDConvertOptions class

خيارات للتحويل إلى النوع ثلاثي الأبعاد .

```csharp
public class ThreeDConvertOptions : ConvertOptions<ThreeDFileType>, IPagedConvertOptions
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [ThreeDConvertOptions](threedconvertoptions)() | تهيئة مثيل جديد لـ[`ThreeDConvertOptions`](../threedconvertoptions) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | نوع الملف المطلوب يجب تحويل مستند الإدخال إليه. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | نوع الملف المطلوب يجب تحويل مستند الإدخال إليه. |
| [PageNumber](../../groupdocs.conversion.options.convert/threedconvertoptions/pagenumber) { get; set; } | رقم الصفحة الذي سيبدأ التحويل منه . |
| [PagesCount](../../groupdocs.conversion.options.convert/threedconvertoptions/pagescount) { get; set; } | عدد الصفحات المطلوب التحويل منها بدءًا من`رقم الصفحة` . |

## طُرق

| اسم | وصف |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | مثيل الخيارات الحالية للنسخ . |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | تحديد ما إذا كان مثيلا الكائن متساويان. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | تحديد ما إذا كان مثيلا الكائن متساويان. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | تعمل كوظيفة تجزئة افتراضية . |

### أنظر أيضا

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* class [ThreeDFileType](../../groupdocs.conversion.filetypes/threedfiletype)
* interface [IPagedConvertOptions](../ipagedconvertoptions)
* مساحة الاسم [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* المجسم [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
