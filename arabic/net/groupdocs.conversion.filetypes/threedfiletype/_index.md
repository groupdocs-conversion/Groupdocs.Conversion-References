---
title: "ThreeDFileType"
second_title: "GroupDocs.Conversion لـ .NET مرجع API"
description: "يحدد مستندات ثلاثية الأبعاد يتضمن الأنواع التالية Fbx./threedfiletype/fbxThreeDS./threedfiletype/threedsThreeMF./threedfiletype/threemfAmf./threedfiletype/amfAse./threedfiletype/aseRvm./threedfiletype/rvmDae./threedfiletype/daeDrc./threedfiletype/drcGltf./threedfiletype/gltfObj./threedfiletype/objPly./threedfiletype/plyJt./threedfiletype/jtU3d./threedfiletype/u3dUsd./threedfiletype/usdUsdz./threedfiletype/usdzVrml./threedfiletype/vrmlX./threedfiletype/xGlb./threedfiletype/glbMa./threedfiletype/maMb./threedfiletype/mb تعرف على المزيد حول صيغ 3D هناhttps//wiki.fileformat.com/3d."
type: docs
weight: 1250
url: /ar/net/groupdocs.conversion.filetypes/threedfiletype/
---
## ThreeDFileType class

يحدد مستندات ثلاثية الأبعاد يتضمن الأنواع التالية: [`Fbx`](./fbx)[`ThreeDS`](./threeds)[`ThreeMF`](./threemf)[`Amf`](./amf)[`Ase`](./ase)[`Rvm`](./rvm)[`Dae`](./dae)[`Drc`](./drc)[`Gltf`](./gltf)[`Obj`](./obj)[`Ply`](./ply)[`Jt`](./jt)[`U3d`](./u3d)[`Usd`](./usd)[`Usdz`](./usdz)[`Vrml`](./vrml)[`X`](./x)[`Glb`](./glb)[`Ma`](./ma)[`Mb`](./mb) تعرف على المزيد حول صيغ 3D [هنا](https://wiki.fileformat.com/3d).

```csharp
public sealed class ThreeDFileType : FileType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ThreeDFileType](threedfiletype)() | منشئ التسلسل |

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
| static readonly [Amf](../../groupdocs.conversion.filetypes/threedfiletype/amf) | ملف AMF يتكون من إرشادات لوصف الكائنات لاستخدامها في عمليات التصنيع الإضافي. يحتوي على وسم XML افتتاحي وينتهي بعنصر. يُسبق ذلك بسطر إعلان XML يحدد نسخة XML وترميز الملف. تعرف على المزيد حول صيغة الملف هذه [هنا](https://docs.fileformat.com/3d/amf). |
| static readonly [Ase](../../groupdocs.conversion.filetypes/threedfiletype/ase) | الملف ذو الامتداد .ase هو تنسيق ملف تصدير مشهد ASCII من Autodesk وهو تمثيل ASCII لمشهد، يحتوي على معلومات ثنائية أو ثلاثية الأبعاد أثناء تصدير بيانات المشهد باستخدام Autodesk. تعرف على المزيد حول صيغة الملف هذه [هنا](https://docs.fileformat.com/3d/ase). |
| static readonly [Dae](../../groupdocs.conversion.filetypes/threedfiletype/dae) | ملف DAE هو تنسيق ملف تبادل الأصول الرقمية يُستخدم لتبادل البيانات بين تطبيقات 3D التفاعلية. يعتمد هذا التنسيق على مخطط XML الخاص بـ COLLADA (نشاط التصميم التعاوني) وهو مخطط XML مفتوح المعيار لتبادل الأصول الرقمية بين تطبيقات برامج الرسوميات. تعرف على المزيد حول صيغة الملف هذه [هنا](https://docs.fileformat.com/3d/dae). |
| static readonly [Drc](../../groupdocs.conversion.filetypes/threedfiletype/drc) | الملف ذو الامتداد .drc هو تنسيق ملف 3D مضغوط تم إنشاؤه باستخدام مكتبة Google Draco. تقدم Google Draco كمكتبة مفتوحة المصدر لضغط وفك ضغط شبكات الهندسة الثلاثية الأبعاد والسحب النقطية، وتُحسّن تخزين ونقل الرسومات ثلاثية الأبعاد. تعرف على المزيد حول صيغة الملف هذه [هنا](https://docs.fileformat.com/3d/drc). |
| static readonly [Fbx](../../groupdocs.conversion.filetypes/threedfiletype/fbx) | FBX، FilmBox، هو تنسيق ملف 3D شائع تم تطويره أصلاً بواسطة Kaydara لـ MotionBuilder. تم الاستحواذ عليه من قبل Autodesk Inc في عام 2006 وهو الآن أحد تنسيقات تبادل 3D الرئيسية المستخدمة من قبل العديد من أدوات 3D. يتوفر FBX بصيغة ملف ثنائية وASCII. تعرف على المزيد حول صيغة الملف هذه [هنا](https://docs.fileformat.com/3d/fbx). |
| static readonly [Glb](../../groupdocs.conversion.filetypes/threedfiletype/glb) | GLB هو تمثيل تنسيق الملف الثنائي لنماذج 3D المحفوظة في تنسيق نقل GL (glTF). يخزن هذا التنسيق الثنائي أصل glTF (JSON، .bin والصور) في كتلة ثنائية. تعرف على المزيد حول صيغة الملف هذه [هنا](https://docs.fileformat.com/3d/glb). |
| static readonly [Gltf](../../groupdocs.conversion.filetypes/threedfiletype/gltf) | glTF (تنسيق نقل GL) هو تنسيق ملف 3D يخزن معلومات نموذج ثلاثي الأبعاد بصيغة JSON. يحدّ من حجم الأصول ثلاثية الأبعاد ومعالجة وقت التشغيل اللازمة لفك واستخدام تلك الأصول. تعرف على المزيد حول صيغة الملف هذه [هنا](https://docs.fileformat.com/3d/gltf). |
| static readonly [Jt](../../groupdocs.conversion.filetypes/threedfiletype/jt) | JT (Jupiter Tessellation) هو تنسيق بيانات 3D فعال وموجه للصناعة ومرن ومعتمد وفق ISO تم تطويره بواسطة Siemens PLM Software. تستخدم مجالات CAD الميكانيكية في الطيران، صناعة السيارات، والمعدات الثقيلة JT كأهم تنسيق لتصوير 3D. تعرف على المزيد حول صيغة الملف هذه [هنا](https://docs.fileformat.com/3d/jt). |
| static readonly [Ma](../../groupdocs.conversion.filetypes/threedfiletype/ma) | الملف ذو الامتداد .ma هو ملف مشروع 3D تم إنشاؤه باستخدام تطبيق Autodesk Maya. يحتوي على قائمة كبيرة من الأوامر النصية لتحديد معلومات حول الملف. تعرف على المزيد حول صيغة الملف هذه [هنا](https://docs.fileformat.com/3d/ma). |
| static readonly [Mb](../../groupdocs.conversion.filetypes/threedfiletype/mb) | ملف بامتداد .mb هو ملف مشروع ثنائي تم إنشاؤه باستخدام تطبيق Autodesk Maya. على عكس تنسيق ملف MA، الذي يكون بتنسيق ASCII، تُخزن ملفات MB بتنسيق ثنائي. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/3d/mb). |
| static readonly [Obj](../../groupdocs.conversion.filetypes/threedfiletype/obj) | تُستخدم ملفات OBJ بواسطة تطبيق Advanced Visualizer من Wavefront لتعريف وتخزين الكائنات الهندسية. تجعل ملفات OBJ نقل البيانات الهندسية إلى الأمام وإلى الخلف ممكنًا. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/3d/obj). |
| static readonly [Ply](../../groupdocs.conversion.filetypes/threedfiletype/ply) | يمثل تنسيق PLY (Polygon File Format) تنسيق ملفات ثلاثية الأبعاد يخزن الكائنات الرسومية الموصوفة كمجموعة من المضلعات. كان هدف هذا التنسيق إنشاء نوع ملف بسيط وسهل يكون عامًا بما يكفي ليكون مفيدًا لمجموعة واسعة من النماذج. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/3d/ply). |
| static readonly [Rvm](../../groupdocs.conversion.filetypes/threedfiletype/rvm) | ملفات بيانات RVM مرتبطة بـ AVEVA PDMS. ملف RVM هو ملف مشروع نموذج نظام إدارة تصميم النبات من AVEVA. يُعد نظام إدارة تصميم النبات (PDMS) من AVEVA أكثر أنظمة التصميم ثلاثية الأبعاد شهرةً باستخدام تقنية متمحورة حول البيانات لإدارة المشاريع. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/3d/rvm). |
| static readonly [ThreeDS](../../groupdocs.conversion.filetypes/threedfiletype/threeds) | ملف بامتداد .3ds يمثل تنسيق ملف شبكة 3D Sudio (DOS) المستخدم بواسطة Autodesk 3D Studio. كان Autodesk 3D Studio في سوق تنسيقات الملفات ثلاثية الأبعاد منذ التسعينيات وتطور الآن إلى 3D Studio MAX للعمل مع النمذجة ثلاثية الأبعاد، والرسوم المتحركة، والتصيير. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/3d/3ds). |
| static readonly [ThreeMF](../../groupdocs.conversion.filetypes/threedfiletype/threemf) | يُستخدم تنسيق 3MF (3D Manufacturing Format) من قبل التطبيقات لتصوير نماذج الكائنات ثلاثية الأبعاد إلى مجموعة متنوعة من التطبيقات الأخرى، والمنصات، والخدمات، والطابعات. تم إنشاؤه لتجنب القيود والمشكلات في تنسيقات الملفات ثلاثية الأبعاد الأخرى، مثل STL، للعمل مع أحدث إصدارات الطابعات ثلاثية الأبعاد. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/3d/3mf). |
| static readonly [U3d](../../groupdocs.conversion.filetypes/threedfiletype/u3d) | U3D (Universal 3D) هو تنسيق ملف مضغوط وبنية بيانات للرسومات الحاسوبية ثلاثية الأبعاد. يحتوي على معلومات نموذج ثلاثي الأبعاد مثل شبكات المثلثات، والإضاءة، والتظليل، وبيانات الحركة، والخطوط والنقاط مع اللون والبنية. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/3d/u3d). |
| static readonly [Usd](../../groupdocs.conversion.filetypes/threedfiletype/usd) | ملف بامتداد .usd هو تنسيق ملف Universal Scene Description الذي يشفّر البيانات لغرض تبادل البيانات وتعزيزها بين تطبيقات إنشاء المحتوى الرقمي. تم تطويره بواسطة Pixar، ويوفر USD القدرة على تبادل الأصول العنصرية (مثل النماذج) أو الرسوم المتحركة. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/3d/usd). |
| static readonly [Usdz](../../groupdocs.conversion.filetypes/threedfiletype/usdz) | ملف بامتداد .usdz هو أرشيف ZIP غير مضغوط وغير مشفر لتنسيق ملف USD (Universal Scene Description) يحتوي على ملفات من تنسيقات أخرى (مثل القوام والرسوم المتحركة) مدمجة داخل الأرشيف ويعمل عليها مباشرةً مع بيئة تشغيل USD دون الحاجة إلى فك الضغط. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/3d/usdz). |
| static readonly [Vrml](../../groupdocs.conversion.filetypes/threedfiletype/vrml) | لغة نمذجة الواقع الافتراضي (VRML) هي تنسيق ملف لتمثيل كائنات عالم ثلاثية الأبعاد تفاعلية عبر شبكة الويب العالمية (www). تُستخدم في إنشاء تمثيلات ثلاثية الأبعاد لمشاهد معقدة مثل الرسوم التوضيحية، والتعريف، وعروض الواقع الافتراضي. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/3d/vrml). |
| static readonly [X](../../groupdocs.conversion.filetypes/threedfiletype/x) | ملف بامتداد .x يشير إلى تنسيق ملف رسومات DirectX 3D القديم الذي تم تقديمه مع Microsoft DirectX 2.0. كان يُستخدم لتصيير الرسومات ثلاثية الأبعاد في الألعاب ويحدد البُنى الخاصة بالشبكات، والقوام، والرسوم المتحركة، والكائنات المعرفة من قبل المستخدم. تم إهماله منذ عام 2014 حيث يُعد تنسيق Autodesk FBX أكثر ملاءمة كتنسيق حديث. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/3d/x). |

### انظر أيضًا

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
