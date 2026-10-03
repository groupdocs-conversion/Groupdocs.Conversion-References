---
title: "CadFileType"
second_title: "GroupDocs.Conversion لـ .NET مرجع API"
description: "يحدد مستندات CAD (التصميم بمساعدة الحاسوب) التي تُستخدم لتنسيقات ملفات الرسومات ثلاثية الأبعاد وقد تحتوي على تصاميم ثنائية أو ثلاثية الأبعاد. يتضمن الأنواع التالية Cf2./cadfiletype/cf2 Dgn./cadfiletype/dgn Dwf./cadfiletype/dwf Dwfx./cadfiletype/dwfx Dwg./cadfiletype/dwg Dwt./cadfiletype/dwt Dxf./cadfiletype/dxf Ifc./cadfiletype/ifc Igs./cadfiletype/igs Plt./cadfiletype/plt Stl./cadfiletype/stl. تعرف على المزيد حول تنسيقات CAD هناhttps//wiki.fileformat.com/cad."
type: docs
weight: 1070
url: /ar/net/groupdocs.conversion.filetypes/cadfiletype/
---
## CadFileType class

يحدد مستندات CAD (التصميم بمساعدة الحاسوب) التي تُستخدم لتنسيقات ملفات الرسومات ثلاثية الأبعاد وقد تحتوي على تصاميم ثنائية أو ثلاثية الأبعاد. يتضمن الأنواع التالية: [`Cf2`](./cf2)[`Dgn`](./dgn)، [`Dwf`](./dwf)، [`Dwfx`](./dwfx)[`Dwg`](./dwg)، [`Dwt`](./dwt)، [`Dxf`](./dxf)، [`Ifc`](./ifc)، [`Igs`](./igs)، [`Plt`](./plt)، [`Stl`](./stl). تعرف على المزيد حول تنسيقات CAD [here](https://wiki.fileformat.com/cad).

```csharp
public sealed class CadFileType : FileType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [CadFileType](cadfiletype)() | منشئ التسلسل |

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
| static readonly [Cf2](../../groupdocs.conversion.filetypes/cadfiletype/cf2) | ملف تنسيق شائع. ملف CAD يحتوي على تصاميم حزم ثلاثية الأبعاد أو بيانات نموذجية أخرى؛ يمكن معالجته وتقطيعه بواسطة آلة CAD/CAM، مثل جهاز القطع بالقالب. |
| static readonly [Dgn](../../groupdocs.conversion.filetypes/cadfiletype/dgn) | ملفات DGN، Design، هي رسومات تم إنشاؤها وتدعمها تطبيقات CAD مثل MicroStation وIntergraph Interactive Graphics Design System. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/cad/dgn). |
| static readonly [Dwf](../../groupdocs.conversion.filetypes/cadfiletype/dwf) | تنسيق الويب للتصميم (DWF) يمثل رسومات 2D/3D بتنسيق مضغوط للعرض أو المراجعة أو طباعة ملفات التصميم. يحتوي على رسومات ونص كجزء من بيانات التصميم ويقلل حجم الملف بفضل تنسيقه المضغوط. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/cad/dwf). |
| static readonly [Dwfx](../../groupdocs.conversion.filetypes/cadfiletype/dwfx) | ملف DWFX هو رسم ثنائي أو ثلاثي الأبعاد تم إنشاؤه باستخدام برنامج Autodesk CAD. يتم حفظه بتنسيق DWFx، وهو مشابه لملف .DWF، لكنه مُنسق باستخدام مواصفة ورق XML من مايكروسوفت (XPS). |
| static readonly [Dwg](../../groupdocs.conversion.filetypes/cadfiletype/dwg) | الملفات ذات الامتداد DWG تمثل ملفات ثنائية مملوكة تُستخدم لاحتواء بيانات التصميم ثنائية وثلاثية الأبعاد. مثل DXF، التي هي ملفات ASCII، تمثل DWG تنسيق الملف الثنائي لرسومات CAD (التصميم المساعد بالحاسوب). تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/cad/dwg). |
| static readonly [Dwt](../../groupdocs.conversion.filetypes/cadfiletype/dwt) | ملف DWT هو قالب رسم AutoCAD يُستخدم كنقطة انطلاق لإنشاء رسومات يمكن حفظها كملفات DWG. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/cad/dwt). |
| static readonly [Dxf](../../groupdocs.conversion.filetypes/cadfiletype/dxf) | DXF، اختصار لـ Drawing Interchange Format أو Drawing Exchange Format، هو تمثيل بيانات مُوسَّم لملف رسم AutoCAD. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/cad/dxf). |
| static readonly [Ifc](../../groupdocs.conversion.filetypes/cadfiletype/ifc) | الملفات ذات الامتداد IFC تشير إلى تنسيق ملفات Industry Foundation Classes (IFC) الذي يضع معايير دولية لاستيراد وتصدير كائنات المباني وخصائصها. يوفر هذا التنسيق قابلية التفاعل بين تطبيقات البرمجيات المختلفة. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/cad/ifc). |
| static readonly [Igs](../../groupdocs.conversion.filetypes/cadfiletype/igs) | تنسيق مستند Igs |
| static readonly [Plt](../../groupdocs.conversion.filetypes/cadfiletype/plt) | تنسيق ملف PLT هو ملف رسام متجه تم تقديمه من قبل Autodesk, Inc. ويحتوي على معلومات لملف CAD معين. تتطلب تفاصيل الرسم دقة وإتقان في الإنتاج، واستخدام ملف PLT يضمن ذلك لأن جميع الصور تُطبع باستخدام خطوط بدلاً من النقاط. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/cad/plt). |
| static readonly [Stl](../../groupdocs.conversion.filetypes/cadfiletype/stl) | STL، اختصار لـ stereolithrography، هو تنسيق ملف قابل للتبادل يمثل هندسة سطح ثلاثية الأبعاد. يُستخدم هذا التنسيق في عدة مجالات مثل النمذجة السريعة، الطباعة ثلاثية الأبعاد، والتصنيع المساعد بالحاسوب. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/cad/stl). |

### انظر أيضًا

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
