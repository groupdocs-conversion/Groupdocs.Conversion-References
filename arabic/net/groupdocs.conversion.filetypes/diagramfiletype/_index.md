---
title: "DiagramFileType"
second_title: "GroupDocs.Conversion لـ .NET مرجع API"
description: "يحدد مستندات Diagram. يتضمن الأنواع التالية Drawio./diagramfiletype/drawio Mmd./diagramfiletype/mmd Vdw./diagramfiletype/vdw Vdx./diagramfiletype/vdx Vsd./diagramfiletype/vsd Vsdm./diagramfiletype/vsdm Vsdx./diagramfiletype/vsdx Vss./diagramfiletype/vss Vssm./diagramfiletype/vssm Vssx./diagramfiletype/vssx Vst./diagramfiletype/vst Vstm./diagramfiletype/vstm Vstx./diagramfiletype/vstx Vsx./diagramfiletype/vsx Vtx./diagramfiletype/vtx."
type: docs
weight: 1100
url: /ar/net/groupdocs.conversion.filetypes/diagramfiletype/
---
## DiagramFileType class

يحدد مستندات Diagram. يتضمن الأنواع التالية: [`Drawio`](./drawio), [`Mmd`](./mmd), [`Vdw`](./vdw), [`Vdx`](./vdx), [`Vsd`](./vsd), [`Vsdm`](./vsdm), [`Vsdx`](./vsdx), [`Vss`](./vss), [`Vssm`](./vssm), [`Vssx`](./vssx), [`Vst`](./vst), [`Vstm`](./vstm), [`Vstx`](./vstx), [`Vsx`](./vsx), [`Vtx`](./vtx).

```csharp
public sealed class DiagramFileType : FileType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [DiagramFileType](diagramfiletype)() | منشئ التسلسل |

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
| static readonly [Drawio](../../groupdocs.conversion.filetypes/diagramfiletype/drawio) | الملف ذو امتداد DRAWIO هو مخطط تم إنشاؤه باستخدام diagrams.net (المعروف سابقًا باسم draw.io). يتم تخزينه بتنسيق ملف XML مع عنصر الجذر mxfile ويحتوي على محتوى وتنسيق عناصر المخطط مثل النصوص، والصور، والتخطيط، والأشكال، والموضع. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/web/drawio). |
| static readonly [Mmd](../../groupdocs.conversion.filetypes/diagramfiletype/mmd) | الملف ذو امتداد MMD هو مخطط مكتوب بلغة توصيف Mermaid. يتم تخزينه كمستند نص عادي يبدأ بإعلان المخطط، مثل مخطط تدفق أو sequenceDiagram، يليه تعريف العقد والاتصالات بينها. تعرف على المزيد حول هذا التنسيق [هنا](https://mermaid.js.org/intro/). |
| static readonly [Vdw](../../groupdocs.conversion.filetypes/diagramfiletype/vdw) | VDW هو تنسيق ملف Visio Graphics Service الذي يحدد التدفقات والتخزينات المطلوبة لتصيير رسم ويب. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/web/vdw). |
| static readonly [Vdx](../../groupdocs.conversion.filetypes/diagramfiletype/vdx) | أي رسم أو مخطط تم إنشاؤه في Microsoft Visio، ولكن تم حفظه بتنسيق XML يحمل امتداد .VDX. يتم إنشاء ملف XML للرسم في Visio باستخدام برنامج Visio الذي طورته Microsoft. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/vdx). |
| static readonly [Vsd](../../groupdocs.conversion.filetypes/diagramfiletype/vsd) | ملفات VSD هي رسومات تم إنشاؤها باستخدام تطبيق Microsoft Visio لتمثيل مجموعة متنوعة من الكائنات الرسومية والاتصالات بينها. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/vsd). |
| static readonly [Vsdm](../../groupdocs.conversion.filetypes/diagramfiletype/vsdm) | الملفات ذات امتداد VSDM هي ملفات رسومات تم إنشاؤها باستخدام تطبيق Microsoft Visio الذي يدعم الماكرو. ملفات VSDM هي رسومات OPC/XML مشابهة لملفات VSDX، لكنها أيضًا توفر القدرة على تشغيل الماكرو عند فتح الملف. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/vsdm). |
| static readonly [Vsdx](../../groupdocs.conversion.filetypes/diagramfiletype/vsdx) | الملفات ذات امتداد .VSDX تمثل تنسيق ملفات Microsoft Visio الذي تم تقديمه بدءًا من Microsoft Office 2013 فصاعدًا. تم تطويره لاستبدال تنسيق الملف الثنائي .VSD، الذي تدعمه الإصدارات السابقة من Microsoft Visio. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/vsdx). |
| static readonly [Vss](../../groupdocs.conversion.filetypes/diagramfiletype/vss) | ملفات VSS هي ملفات قوالب تم إنشاؤها باستخدام Microsoft Visio 2007 وما قبله. توفر ملفات القوالب كائنات رسومية يمكن تضمينها في رسم Visio بامتداد .VSD. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/vss). |
| static readonly [Vssm](../../groupdocs.conversion.filetypes/diagramfiletype/vssm) | الملفات ذات امتداد .VSSM هي ملفات قوالب Microsoft Visio التي تدعم الماكرو. عند فتح ملف VSSM يسمح بتشغيل الماكرو لتحقيق التنسيق المطلوب ووضع الأشكال في المخطط. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/vssm). |
| static readonly [Vssx](../../groupdocs.conversion.filetypes/diagramfiletype/vssx) | الملفات ذات امتداد .VSSX هي قوالب رسومات تم إنشاؤها باستخدام Microsoft Visio 2013 وما فوق. يمكن فتح تنسيق ملف VSSX باستخدام Visio 2013 وما فوق. تُعرف ملفات Visio بتمثيل مجموعة متنوعة من عناصر الرسم مثل مجموعة الأشكال، الموصلات، المخططات الانسيابية، تخطيط الشبكة، مخططات UML. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/vssx). |
| static readonly [Vst](../../groupdocs.conversion.filetypes/diagramfiletype/vst) | الملفات ذات امتداد VST هي ملفات صور متجهة تم إنشاؤها باستخدام Microsoft Visio وتعمل كقالب لإنشاء ملفات أخرى. هذه القوالب بتنسيق ملف ثنائي وتحتوي على التخطيط والإعدادات الافتراضية المستخدمة لإنشاء رسومات Visio جديدة. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/vst). |
| static readonly [Vstm](../../groupdocs.conversion.filetypes/diagramfiletype/vstm) | الملفات ذات امتداد VSTM هي ملفات قوالب تم إنشاؤها باستخدام Microsoft Visio وتدعم الماكرو. على عكس ملفات VSDX، يمكن للملفات التي تم إنشاؤها من قوالب VSTM تشغيل الماكرو المطور بلغة Visual Basic for Applications (VBA). تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/vstm). |
| static readonly [Vstx](../../groupdocs.conversion.filetypes/diagramfiletype/vstx) | الملفات ذات امتداد VSTX هي ملفات قوالب رسومات تم إنشاؤها باستخدام Microsoft Visio 2013 وما فوق. توفر ملفات VSTX نقطة انطلاق لإنشاء رسومات Visio، تُحفظ كملفات .VSDX، مع التخطيط والإعدادات الافتراضية. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/vstx). |
| static readonly [Vsx](../../groupdocs.conversion.filetypes/diagramfiletype/vsx) | الملفات ذات امتداد .VSX تشير إلى قوالب تتكون من رسومات وأشكال تُستخدم لإنشاء مخططات في Microsoft Visio. تُحفظ ملفات VSX بتنسيق XML وكان الدعم متاحًا حتى Visio 2013. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/vsx). |
| static readonly [Vtx](../../groupdocs.conversion.filetypes/diagramfiletype/vtx) | الملف ذو امتداد VTX هو قالب رسم Microsoft Visio يُحفظ على القرص بتنسيق XML. يهدف القالب إلى توفير ملف بإعدادات أساسية يمكن استخدامها لإنشاء ملفات Visio متعددة بنفس الإعدادات. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/vtx). |

### انظر أيضًا

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
