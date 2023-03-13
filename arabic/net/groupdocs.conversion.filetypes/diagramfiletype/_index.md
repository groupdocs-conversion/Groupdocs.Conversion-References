---
title: DiagramFileType
second_title: GroupDocs.Conversion لمرجع .NET API
description: يحدد وثائق الرسم التخطيطي. يشمل الأنواع التالية Vdw./diagramfiletype/vdw  Vdx./diagramfiletype/vdx  Vsd./diagramfiletype/vsd  Vsdm./diagramfiletype/vsdm  Vsdx./diagramfiletype/vsdx  Vss./diagramfiletype/vss  Vssm./diagramfiletype/vssm  Vssx./diagramfiletype/vssx  Vst./diagramfiletype/vst  Vstm./diagramfiletype/vstm  Vstx./diagramfiletype/vstx  Vsx./diagramfiletype/vsx  Vtx./diagramfiletype/vtx .
type: docs
weight: 900
url: /ar/net/groupdocs.conversion.filetypes/diagramfiletype/
---
## DiagramFileType class

يحدد وثائق الرسم التخطيطي. يشمل الأنواع التالية: [`Vdw`](./vdw) ، [`Vdx`](./vdx) ، [`Vsd`](./vsd) ، [`Vsdm`](./vsdm) ، [`Vsdx`](./vsdx) ، [`Vss`](./vss) ، [`Vssm`](./vssm) ، [`Vssx`](./vssx) ، [`Vst`](./vst) ، [`Vstm`](./vstm) ، [`Vstx`](./vstx) ، [`Vsx`](./vsx) ، [`Vtx`](./vtx) .

```csharp
public sealed class DiagramFileType : FileType
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [DiagramFileType](diagramfiletype)() | مُنشئ التسلسل |

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
| static readonly [Vdw](../../groupdocs.conversion.filetypes/diagramfiletype/vdw) | VDW هو تنسيق ملف Visio Graphics Service الذي يحدد التدفقات والمخازن المطلوبة لتقديم رسم ويب. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/web/vdw) . |
| static readonly [Vdx](../../groupdocs.conversion.filetypes/diagramfiletype/vdx) | أي رسم أو مخطط تم إنشاؤه في Microsoft Visio ، ولكن تم حفظه بتنسيق XML له امتداد .VDX. يتم إنشاء ملف Visio للرسم XML في برنامج Visio ، الذي تم تطويره بواسطة Microsoft . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/vdx) . |
| static readonly [Vsd](../../groupdocs.conversion.filetypes/diagramfiletype/vsd) | ملفات VSD هي رسومات تم إنشاؤها باستخدام تطبيق Microsoft Visio لتمثيل مجموعة متنوعة من الكائنات الرسومية والترابط بين هذه . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/vsd) . |
| static readonly [Vsdm](../../groupdocs.conversion.filetypes/diagramfiletype/vsdm) | الملفات ذات الامتداد VSDM هي ملفات رسم تم إنشاؤها باستخدام تطبيق Microsoft Visio الذي يدعم وحدات الماكرو. ملفات VSDM هي رسومات OPC / XML تشبه VSDX ، ولكنها توفر أيضًا القدرة على تشغيل وحدات الماكرو عند فتح الملف. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/vsdm) . |
| static readonly [Vsdx](../../groupdocs.conversion.filetypes/diagramfiletype/vsdx) | تمثل الملفات ذات الامتداد .VSDX تنسيق ملف Microsoft Visio المقدم من Microsoft Office 2013 فصاعدًا. تم تطويره ليحل محل تنسيق الملف الثنائي ، .VSD ، الذي تدعمه الإصدارات السابقة من Microsoft Visio . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/vsdx) . |
| static readonly [Vss](../../groupdocs.conversion.filetypes/diagramfiletype/vss) | VSS هي ملفات استنسل تم إنشاؤها باستخدام Microsoft Visio 2007 والإصدارات الأقدم. توفر ملفات الاستنسل كائنات رسومية يمكن تضمينها في رسم .VSD Visio . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/vss) . |
| static readonly [Vssm](../../groupdocs.conversion.filetypes/diagramfiletype/vssm) | الملفات ذات الامتداد .VSSM هي ملفات Microsoft Visio Stencil التي تدعم توفير الدعم لوحدات الماكرو. يسمح ملف VSSM عند فتحه بتشغيل وحدات الماكرو لتحقيق التنسيق المطلوب ووضع الأشكال في رسم تخطيطي . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/vssm) . |
| static readonly [Vssx](../../groupdocs.conversion.filetypes/diagramfiletype/vssx) | تقوم الملفات ذات الامتداد .VSSX برسم قوالب استنسل تم إنشاؤها باستخدام Microsoft Visio 2013 وما بعده. يمكن فتح تنسيق ملف VSSX باستخدام Visio 2013 وما فوق. تُعرف ملفات Visio بتمثيل مجموعة متنوعة من عناصر الرسم مثل مجموعة الأشكال والموصلات والمخططات الانسيابية وتخطيط الشبكة ومخططات UML و تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/vssx) . |
| static readonly [Vst](../../groupdocs.conversion.filetypes/diagramfiletype/vst) | الملفات ذات الامتداد VST هي ملفات صور متجهة تم إنشاؤها باستخدام Microsoft Visio وتعمل كقالب لإنشاء المزيد من الملفات. ملفات القوالب هذه بتنسيق ملف ثنائي وتحتوي على التخطيط والإعدادات الافتراضية المستخدمة لإنشاء رسومات Visio الجديدة . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/vst) . |
| static readonly [Vstm](../../groupdocs.conversion.filetypes/diagramfiletype/vstm) | الملفات ذات الامتداد VSTM هي ملفات قوالب تم إنشاؤها باستخدام Microsoft Visio التي تدعم وحدات الماكرو. بخلاف ملفات VSDX ، يمكن للملفات التي تم إنشاؤها من قوالب VSTM تشغيل وحدات الماكرو التي تم تطويرها في التعليمات البرمجية لـ Visual Basic for Applications (VBA). تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/vstm) . |
| static readonly [Vstx](../../groupdocs.conversion.filetypes/diagramfiletype/vstx) | الملفات ذات الامتدادات VSTX هي ملفات قوالب رسم تم إنشاؤها باستخدام Microsoft Visio 2013 وما بعده. توفر ملفات VSTX هذه نقطة بداية لإنشاء رسومات Visio ، المحفوظة كملفات .VSDX ، مع التخطيط والإعدادات الافتراضية. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/vstx) . |
| static readonly [Vsx](../../groupdocs.conversion.filetypes/diagramfiletype/vsx) | تشير الملفات ذات الامتداد .VSX إلى قوالب الإستنسل التي تتكون من رسومات وأشكال تُستخدم لإنشاء الرسوم التخطيطية في Microsoft Visio. يتم حفظ ملفات VSX بتنسيق ملف XML وتم دعمها حتى Visio 2013. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/vsx) . |
| static readonly [Vtx](../../groupdocs.conversion.filetypes/diagramfiletype/vtx) | الملف ذو الملحق VTX هو قالب رسم Microsoft Visio يتم حفظه على قرص بتنسيق ملف XML. يهدف القالب إلى توفير ملف بالإعدادات الأساسية التي يمكن استخدامها لإنشاء ملفات Visio متعددة بنفس الإعدادات . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/vtx) . |

### أنظر أيضا

* class [FileType](../filetype)
* مساحة الاسم [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* المجسم [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
