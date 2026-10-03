---
title: "PageDescriptionLanguageFileType"
second_title: "GroupDocs.Conversion لـ .NET مرجع API"
description: "يحدد مستندات وصف الصفحات. يتضمن أنواع الملفات التالية Svg./pagedescriptionlanguagefiletype/svgSvgz./pagedescriptionlanguagefiletype/svgzEps./pagedescriptionlanguagefiletype/epsCgm./pagedescriptionlanguagefiletype/cgmXps./pagedescriptionlanguagefiletype/xpsTex./pagedescriptionlanguagefiletype/texPs./pagedescriptionlanguagefiletype/psPcl./pagedescriptionlanguagefiletype/pclOxps./pagedescriptionlanguagefiletype/oxps"
type: docs
weight: 1190
url: /ar/net/groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/
---
## PageDescriptionLanguageFileType class

يحدد مستندات وصف الصفحات. يتضمن أنواع الملفات التالية: [`Svg`](./svg)[`Svgz`](./svgz)[`Eps`](./eps)[`Cgm`](./cgm)[`Xps`](./xps)[`Tex`](./tex)[`Ps`](./ps)[`Pcl`](./pcl)[`Oxps`](./oxps)

```csharp
public sealed class PageDescriptionLanguageFileType : FileType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PageDescriptionLanguageFileType](pagedescriptionlanguagefiletype)() | منشئ التسلسل |

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
| static readonly [Cgm](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/cgm) | Computer Graphics Metafile (CGM) هو تنسيق ملف ميتا مجاني، مستقل عن المنصة، معيار دولي لتخزين وتبادل الرسومات المتجهية (2D)، الرسومات النقطية، والنص. يستخدم CGM نهجًا موجهًا للكائنات والعديد من الوظائف لإنتاج الصور. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/page-description-language/cgm). |
| static readonly [Eps](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/eps) | الملفات ذات امتداد EPS تصف أساسًا برنامج لغة Encapsulated PostScript الذي يحدد مظهر صفحة واحدة. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/page-description-language/eps). |
| static readonly [Oxps](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/oxps) | يُعرف تنسيق الملف OXPS باسم Open XML Paper Specification. إنه لغة وصف صفحات وتنسيق مستندات. مايكروسوفت هي مطور هذا التنسيق. تنسيق ملف OXPS مشابه جدًا لملفات PDF. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/page-description-language/oxps). |
| static readonly [Pcl](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/pcl) | PCL هو اختصار لـ Printer Command Language وهو لغة وصف صفحات قدمتها شركة Hewlett Packard (HP). تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/page-description-language/pcl). |
| static readonly [Ps](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/ps) | PostScript (PS) هو لغة وصف صفحات عامة الاستخدام تُستخدم في أعمال النشر المكتبي والإلكتروني. التركيز الرئيسي لـ PostScript (PS) هو تسهيل التصميم الرسومي ثنائي الأبعاد. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/page-description-language/ps). |
| static readonly [Svg](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/svg) | ملف SVG هو ملف رسومات متجهية قياسية يستخدم تنسيق نص مبني على XML لوصف مظهر الصورة. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/page-description-language/svg). |
| static readonly [Svgz](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/svgz) | ملف SVGZ هو في الواقع نسخة مضغوطة من ملف SVG. هذا يسمح بتوزيع أسهل للملف عبر الإنترنت. عندما يتم ضغط ملف SVG باستخدام خوارزمية الضغط .GZIP، يُعطى لاحقًا امتداد الملف .svgz. |
| static readonly [Tex](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/tex) | TeX هي لغة تتضمن برمجة بالإضافة إلى ميزات الترميز، وتُستخدم لتنسيق المستندات. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/page-description-language/tex). |
| static readonly [Xps](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/xps) | ملف XPS يمثل ملفات تخطيط الصفحات التي تعتمد على مواصفات ورق XML التي أنشأتها مايكروسوفت. تم تطوير هذا التنسيق من قبل مايكروسوفت كبديل لتنسيق ملف EMF وهو مشابه لتنسيق ملف PDF، لكنه يستخدم XML في تخطيط ومظهر ومعلومات الطباعة للوثيقة. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/page-description-language/xps). |

### انظر أيضًا

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
