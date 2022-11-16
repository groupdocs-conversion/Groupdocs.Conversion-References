---
title: ThreeDFileType
second_title: GroupDocs.Conversion لمرجع .NET API
description: تعريف المستندات ثلاثية الأبعاد يشمل الأنواع التالية Fbx./threedfiletype/fbx تعرف على المزيد حول التنسيقات ثلاثية الأبعادهناhttps//wiki.fileformat.com/3d .
type: docs
weight: 940
url: /ar/net/groupdocs.conversion.filetypes/threedfiletype/
---
## ThreeDFileType class

تعريف المستندات ثلاثية الأبعاد يشمل الأنواع التالية: [`Fbx`](./fbx) تعرف على المزيد حول التنسيقات ثلاثية الأبعاد[هنا](https://wiki.fileformat.com/3d) .

```csharp
public sealed class ThreeDFileType : FileType
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [ThreeDFileType](threedfiletype)() | مُنشئ التسلسل |

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
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | تحديد ما إذا كان مثيلا الكائن متساويان. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | تحديد ما إذا كان مثيلا الكائن متساويان. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | تعمل كوظيفة تجزئة افتراضية . |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | تمثيل السلسلة |

## مجالات

| اسم | وصف |
| --- | --- |
| static readonly [Amf](../../groupdocs.conversion.filetypes/threedfiletype/amf) | يتكون ملف AMF من إرشادات لوصف الكائنات ليتم استخدامها بواسطة عمليات التصنيع المضافة. يحتوي على علامة XML افتتاحية وينتهي بعنصر. يسبق ذلك سطر إعلان XML يحدد إصدار XML وتشفير الملف . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/3d/amf) . |
| static readonly [Ase](../../groupdocs.conversion.filetypes/threedfiletype/ase) | ملف بامتداد .ase هو تنسيق ملف Autodesk ASCII Scene Export يمثل تمثيل ASCII لمشهد ، يحتوي على معلومات ثنائية أو ثلاثية الأبعاد أثناء تصدير بيانات المشهد باستخدام Autodesk . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/3d/ase) . |
| static readonly [Dae](../../groupdocs.conversion.filetypes/threedfiletype/dae) | ملف DAE هو تنسيق ملف تبادل الأصول الرقمية يُستخدم لتبادل البيانات بين التطبيقات ثلاثية الأبعاد التفاعلية. يعتمد تنسيق الملف هذا على مخطط XML COLLADA (نشاط تصميم COLLAborative) وهو مخطط XML قياسي مفتوح لتبادل الأصول الرقمية بين تطبيقات برامج الرسومات . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/3d/dae) . |
| static readonly [Drc](../../groupdocs.conversion.filetypes/threedfiletype/drc) | الملف بامتداد .drc هو تنسيق ملف ثلاثي الأبعاد تم إنشاؤه باستخدام مكتبة Google Draco. تقدم Google Draco كمكتبة مفتوحة المصدر لضغط وفك ضغط الشبكات الهندسية ثلاثية الأبعاد وسحب النقاط ، وتحسين تخزين ونقل الرسومات ثلاثية الأبعاد . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/3d/drc) . |
| static readonly [Fbx](../../groupdocs.conversion.filetypes/threedfiletype/fbx) | FBX ، FilmBox ، هو تنسيق ملف ثلاثي الأبعاد شائع تم تطويره في الأصل بواسطة Kaydara لصالح MotionBuilder. تم الحصول عليها من قبل شركة Autodesk Inc في عام 2006 وهي الآن واحدة من تنسيقات التبادل ثلاثية الأبعاد الرئيسية المستخدمة في العديد من الأدوات ثلاثية الأبعاد. يتوفر FBX في كل من تنسيق الملف الثنائي و ASCII . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/3d/fbx) . |
| static readonly [Gltf](../../groupdocs.conversion.filetypes/threedfiletype/gltf) | glTF (GL Transmission Format) هو تنسيق ملف ثلاثي الأبعاد يخزن معلومات النموذج ثلاثي الأبعاد بتنسيق JSON. يقلل استخدام JSON من حجم الأصول ثلاثية الأبعاد ومعالجة وقت التشغيل اللازمة لتفريغ واستخدام تلك الأصول. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/3d/gltf) . |
| static readonly [Jt](../../groupdocs.conversion.filetypes/threedfiletype/jt) | JT (Jupiter Tessellation) هو تنسيق بيانات ثلاثي الأبعاد يتسم بالكفاءة ويركز على الصناعة ومرنًا ومرنًا وفقًا لمعايير ISO تم تطويره بواسطة شركة Siemens PLM Software. تستخدم مجالات CAD الميكانيكية الخاصة بالفضاء وصناعة السيارات والمعدات الثقيلة JT كأفضل تنسيق مرئي ثلاثي الأبعاد . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/3d/jt) . |
| static readonly [Obj](../../groupdocs.conversion.filetypes/threedfiletype/obj) | يتم استخدام ملفات OBJ بواسطة تطبيق Wavefront's Advanced Visualizer لتحديد الكائنات الهندسية وتخزينها. أصبح النقل الخلفي والأمامي للبيانات الهندسية ممكنًا من خلال ملفات OBJ. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/3d/obj) . |
| static readonly [Ply](../../groupdocs.conversion.filetypes/threedfiletype/ply) | PLY ، تنسيق ملف Polygon ، يمثل تنسيق ملف ثلاثي الأبعاد يخزن كائنات رسومية موصوفة كمجموعة من المضلعات. كان الغرض من تنسيق الملف هذا هو إنشاء نوع ملف بسيط وسهل يكون عامًا بما يكفي ليكون مفيدًا لمجموعة كبيرة من الطرز . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/3d/ply) . |
| static readonly [Rvm](../../groupdocs.conversion.filetypes/threedfiletype/rvm) | ملفات بيانات RVM مرتبطة بـ AVEVA PDMS. ملف RVM هو ملف مشروع نموذج نظام إدارة تصميم مصنع AVEVA. يعد نظام إدارة تصميم المصنع (PDMS) من AVEVA هو أكثر أنظمة التصميم ثلاثية الأبعاد شيوعًا باستخدام تقنية تتمحور حول البيانات لإدارة المشاريع. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/3d/rvm) . |
| static readonly [ThreeDS](../../groupdocs.conversion.filetypes/threedfiletype/threeds) | يمثل الملف ذو الامتداد .3ds تنسيق ملف شبكة 3D Sudio (DOS) المستخدم بواسطة Autodesk 3D Studio. يعمل Autodesk 3D Studio في سوق تنسيقات الملفات ثلاثية الأبعاد منذ التسعينيات وقد تطور الآن إلى 3D Studio MAX للعمل مع النمذجة ثلاثية الأبعاد والرسوم المتحركة والعرض . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/3d/3ds) . |
| static readonly [ThreeMF](../../groupdocs.conversion.filetypes/threedfiletype/threemf) | 3MF ، تنسيق التصنيع ثلاثي الأبعاد ، تستخدمه التطبيقات لعرض نماذج الكائنات ثلاثية الأبعاد لمجموعة متنوعة من التطبيقات والأنظمة الأساسية والخدمات والطابعات الأخرى. تم إنشاؤه لتجنب القيود والمشكلات في تنسيقات الملفات ثلاثية الأبعاد الأخرى ، مثل STL ، للعمل مع أحدث إصدارات الطابعات ثلاثية الأبعاد . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/3d/3mf) . |
| static readonly [U3d](../../groupdocs.conversion.filetypes/threedfiletype/u3d) | U3D (Universal 3D) هو تنسيق ملف مضغوط وهيكل بيانات لرسومات الكمبيوتر ثلاثية الأبعاد. يحتوي على معلومات نموذج ثلاثي الأبعاد مثل شبكات المثلث والإضاءة والتظليل وبيانات الحركة والخطوط والنقاط ذات اللون والبنية. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/3d/u3d) . |
| static readonly [Usd](../../groupdocs.conversion.filetypes/threedfiletype/usd) | الملف ذو الامتداد .usd هو تنسيق ملف وصف المشهد العالمي الذي يقوم بترميز البيانات بغرض تبادل البيانات والزيادة بين تطبيقات إنشاء المحتوى الرقمي. يوفر الدولار الأمريكي ، الذي طورته شركة Pixar ، القدرة على تبادل الأصول الأولية (مثل النماذج) أو الرسوم المتحركة . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/3d/usd) . |
| static readonly [Usdz](../../groupdocs.conversion.filetypes/threedfiletype/usdz) | الملف الذي يحتوي على .usdz هو أرشيف ZIP غير مضغوط وغير مشفر لتنسيق ملف USD (وصف المشهد العام) الذي يحتوي على وكلاء لملفات من تنسيقات أخرى (مثل الأنسجة والرسوم المتحركة) المضمنة داخل الأرشيف ويتم تشغيلها مباشرة مع وقت التشغيل بالدولار الأمريكي دون الحاجة إلى تفريغ . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/3d/usdz) . |
| static readonly [Vrml](../../groupdocs.conversion.filetypes/threedfiletype/vrml) | لغة نمذجة الواقع الافتراضي (VRML) هي تنسيق ملف لتمثيل كائنات العالم التفاعلية ثلاثية الأبعاد عبر شبكة الويب العالمية (www). يجد استخدامه في إنشاء تمثيلات ثلاثية الأبعاد للمشاهد المعقدة مثل الرسوم التوضيحية والتعريف وعروض الواقع الافتراضي. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/3d/vrml) . |
| static readonly [X](../../groupdocs.conversion.filetypes/threedfiletype/x) | يشير الملف بملحق .x إلى تنسيق ملف DirectX 3D Graphics القديم الذي تم تقديمه مع Microsoft DirectX 2.0. تم استخدامه لعرض الرسومات ثلاثية الأبعاد في الألعاب وتحديد هياكل الشبكات والأنسجة والرسوم المتحركة والكائنات المحددة من قبل المستخدم. لقد تم إهماله منذ عام 2014 حيث أن تنسيق ملف Autodesk FBX يعمل بشكل أفضل كتنسيق أكثر حداثة. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/3d/x) . |

### أنظر أيضا

* class [FileType](../filetype)
* مساحة الاسم [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* المجسم [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
