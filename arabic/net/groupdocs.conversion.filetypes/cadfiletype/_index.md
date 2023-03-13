---
title: CadFileType
second_title: GroupDocs.Conversion لمرجع .NET API
description: يحدد مستندات CAD التصميم بمساعدة الكمبيوتر التي تُستخدم لتنسيقات ملفات رسومات ثلاثية الأبعاد وقد تحتوي على تصميمات ثنائية أو ثلاثية الأبعاد . تتضمن الأنواع التالية Cf2./cadfiletype/cf2Dgn./cadfiletype/dgn  Dwf./cadfiletype/dwf  Dwfx./cadfiletype/dwfxDwg./cadfiletype/dwg  Dwt./cadfiletype/dwt  Dxf./cadfiletype/dxf  Ifc./cadfiletype/ifc  Igs./cadfiletype/igs  Plt./cadfiletype/plt  Stl./cadfiletype/stl . تعرف على المزيد حول تنسيقات CADهناhttps//wiki.fileformat.com/cad .
type: docs
weight: 860
url: /ar/net/groupdocs.conversion.filetypes/cadfiletype/
---
## CadFileType class

يحدد مستندات CAD (التصميم بمساعدة الكمبيوتر) التي تُستخدم لتنسيقات ملفات رسومات ثلاثية الأبعاد وقد تحتوي على تصميمات ثنائية أو ثلاثية الأبعاد . تتضمن الأنواع التالية: [`Cf2`](./cf2)[`Dgn`](./dgn) ، [`Dwf`](./dwf) ، [`Dwfx`](./dwfx)[`Dwg`](./dwg) ، [`Dwt`](./dwt) ، [`Dxf`](./dxf) ، [`Ifc`](./ifc) ، [`Igs`](./igs) ، [`Plt`](./plt) ، [`Stl`](./stl) . تعرف على المزيد حول تنسيقات CAD[هنا](https://wiki.fileformat.com/cad) .

```csharp
public sealed class CadFileType : FileType
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [CadFileType](cadfiletype)() | مُنشئ التسلسل |

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
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | تحديد ما إذا كان مثيلا الكائن متساويان. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | تحديد ما إذا كان مثيلا الكائن متساويان. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | تعمل كوظيفة تجزئة افتراضية . |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | تمثيل السلسلة |

## مجالات

| اسم | وصف |
| --- | --- |
| static readonly [Cf2](../../groupdocs.conversion.filetypes/cadfiletype/cf2) | ملف تنسيق الملف العام. ملف CAD يحتوي على تصميمات حزمة ثلاثية الأبعاد أو بيانات نموذج أخرى ؛ يمكن معالجتها وقطعها بواسطة آلة CAD / CAM ، مثل جهاز قطع القوالب. |
| static readonly [Dgn](../../groupdocs.conversion.filetypes/cadfiletype/dgn) | DGN ، التصميم ، الملفات هي رسومات تم إنشاؤها بواسطة تطبيقات CAD ودعمها مثل MicroStation و Intergraph Interactive Graphics Design System . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/cad/dgn) . |
| static readonly [Dwf](../../groupdocs.conversion.filetypes/cadfiletype/dwf) | يمثل تنسيق تصميم الويب (DWF) رسمًا ثنائي الأبعاد / ثلاثي الأبعاد بتنسيق مضغوط لعرض ملفات التصميم أو مراجعتها أو طباعتها. يحتوي على رسومات ونصوص كجزء من بيانات التصميم وتقليل حجم الملف بسبب تنسيقه المضغوط . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/cad/dwf) . |
| static readonly [Dwfx](../../groupdocs.conversion.filetypes/cadfiletype/dwfx) | ملف DWFX هو رسم ثنائي الأبعاد أو ثلاثي الأبعاد تم إنشاؤه باستخدام برنامج Autodesk CAD. يتم حفظه بتنسيق DWFx ، والذي يشبه ملف. DWF ، ولكن تم تنسيقه باستخدام مواصفات ورق XML (XPS) من Microsoft. |
| static readonly [Dwg](../../groupdocs.conversion.filetypes/cadfiletype/dwg) | تمثل الملفات ذات الامتداد DWG الملفات الثنائية الخاصة المستخدمة لاحتواء بيانات التصميم ثنائية وثلاثية الأبعاد. مثل DXF ، وهي ملفات ASCII ، تمثل DWG تنسيق الملف الثنائي لرسومات CAD (التصميم بمساعدة الكمبيوتر). تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/cad/dwg) . |
| static readonly [Dwt](../../groupdocs.conversion.filetypes/cadfiletype/dwt) | ملف DWT هو ملف قالب رسم AutoCAD يتم استخدامه كبداية لإنشاء رسومات يمكن حفظها كملفات DWG . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/cad/dwt) . |
| static readonly [Dxf](../../groupdocs.conversion.filetypes/cadfiletype/dxf) | DXF ، تنسيق تبادل الرسم ، أو تنسيق تبادل الرسم ، هو تمثيل بيانات مميز لملف رسم AutoCAD . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/cad/dxf) . |
| static readonly [Ifc](../../groupdocs.conversion.filetypes/cadfiletype/ifc) | تشير الملفات ذات امتداد IFC إلى تنسيق ملف فئات مؤسسة الصناعة (IFC) الذي يحدد المعايير الدولية لاستيراد وتصدير كائنات البناء وخصائصها. يوفر تنسيق الملف هذا إمكانية التشغيل البيني بين تطبيقات البرامج المختلفة. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/cad/ifc) . |
| static readonly [Igs](../../groupdocs.conversion.filetypes/cadfiletype/igs) | تنسيق مستند Igs |
| static readonly [Plt](../../groupdocs.conversion.filetypes/cadfiletype/plt) | تنسيق ملف PLT هو ملف رسام يعتمد على المتجهات تم تقديمه بواسطة شركة Autodesk، Inc. ويحتوي على معلومات لملف CAD معين. تتطلب تفاصيل التخطيط الدقة والدقة في الإنتاج ، ويضمن استخدام ملف PLT ذلك حيث تتم طباعة جميع الصور باستخدام خطوط بدلاً من النقاط. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/cad/plt) . |
| static readonly [Stl](../../groupdocs.conversion.filetypes/cadfiletype/stl) | STL ، اختصار للطباعة الحجرية الحجرية ، هو تنسيق ملف قابل للتبديل يمثل هندسة السطح ثلاثية الأبعاد. يجد تنسيق الملف استخدامه في عدة مجالات مثل النماذج الأولية السريعة والطباعة ثلاثية الأبعاد والتصنيع بمساعدة الكمبيوتر . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/cad/stl) . |

### أنظر أيضا

* class [FileType](../filetype)
* مساحة الاسم [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* المجسم [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
