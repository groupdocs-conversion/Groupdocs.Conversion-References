---
title: "CadFileType"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يعرّف مستندات CAD (التصميم بمساعدة الحاسوب) التي تُستخدم لتنسيقات ملفات الرسوميات ثلاثية الأبعاد وقد تحتوي على تصاميم ثنائية أو ثلاثية الأبعاد."
type: docs
weight: 11
url: /ar/java/com.groupdocs.conversion.filetypes/cadfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CadFileType extends FileType implements Serializable
```

يحدد مستندات CAD (التصميم المساعد بالحاسوب) التي تُستخدم لتنسيقات ملفات الرسومات ثلاثية الأبعاد وقد تحتوي على تصاميم ثنائية أو ثلاثية الأبعاد.
يتضمن الأنواع التالية:
[Dgn](../../com.groupdocs.conversion.filetypes/cadfiletype#Dgn),
[Dwf](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwf),
[Dwg](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwg),
[Dwt](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwt),
[Dxf](../../com.groupdocs.conversion.filetypes/cadfiletype#Dxf),
[Ifc](../../com.groupdocs.conversion.filetypes/cadfiletype#Ifc),
[Igs](../../com.groupdocs.conversion.filetypes/cadfiletype#Igs),
[Plt](../../com.groupdocs.conversion.filetypes/cadfiletype#Plt),
[Stl](../../com.groupdocs.conversion.filetypes/cadfiletype#Stl).
[Cf2](../../com.groupdocs.conversion.filetypes/cadfiletype#Cf2).
[Dwfx](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwfx).
Learn more about CAD formats [here](../https://wiki.fileformat.com/cad).

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [CadFileType()](#CadFileType--) | منشئ التسلسل |
|
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Dxf](#Dxf) | DXF، Drawing Interchange Format، أو Drawing Exchange Format، هو تمثيل بيانات مُوسَّم لملف رسم AutoCAD. |
|
|  | [Dwg](#Dwg) | الملفات ذات الامتداد DWG تمثل ملفات ثنائية مملوكة تُستخدم لاحتواء بيانات التصميم ثنائية وثلاثية الأبعاد. |
|
|  | [Dgn](#Dgn) | DGN، Design، ملفات هي رسومات تم إنشاؤها ودعمها بواسطة تطبيقات CAD مثل MicroStation و Intergraph Interactive Graphics Design System. |
|
|  | [Dwf](#Dwf) | Design Web Format (DWF) يمثل رسومات ثنائية/ثلاثية الأبعاد بصيغة مضغوطة للعرض أو المراجعة أو طباعة ملفات التصميم. |
|
|  | [Stl](#Stl) | STL، اختصار لـ stereolithrography، هو تنسيق ملف قابل للتبادل يمثل هندسة سطح ثلاثية الأبعاد. |
|
|  | [Ifc](#Ifc) | الملفات ذات الامتداد IFC تشير إلى تنسيق ملفات Industry Foundation Classes (IFC) الذي يضع معايير دولية لاستيراد وتصدير كائنات المباني وخصائصها. |
|
|  | [Plt](#Plt) | تنسيق ملف PLT هو ملف رسام متجه تم تقديمه من قبل Autodesk, Inc. |
|
|  | [Igs](#Igs) | Igs document format |
|
|  | [Dwt](#Dwt) | ملف DWT هو قالب رسم AutoCAD يُستخدم كنقطة بداية لإنشاء رسومات يمكن حفظها كملفات DWG. |
|
|  | [Dwfx](#Dwfx) | ملف DWFX هو رسم ثنائي أو ثلاثي الأبعاد تم إنشاؤه باستخدام برنامج Autodesk CAD. |
|
|  | [Cf2](#Cf2) | Common File Format File. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### CadFileType() {#CadFileType--}
```
public CadFileType()
```


منشئ التسلسل


### Dxf {#Dxf}
```
public static final CadFileType Dxf
```


DXF، Drawing Interchange Format، أو Drawing Exchange Format، هو تمثيل بيانات مُوسَّم لملف رسم AutoCAD.
Learn more about this file format [here](../https://wiki.fileformat.com/cad/dxf).


### Dwg {#Dwg}
```
public static final CadFileType Dwg
```


الملفات ذات الامتداد DWG تمثل ملفات ثنائية مملوكة تُستخدم لاحتواء بيانات التصميم ثنائية وثلاثية الأبعاد. مثل DXF، التي هي ملفات ASCII، تمثل DWG تنسيق الملف الثنائي لرسومات CAD (التصميم بمساعدة الحاسوب).
Learn more about this file format [here](../https://wiki.fileformat.com/cad/dwg)


### Dgn {#Dgn}
```
public static final CadFileType Dgn
```


DGN، Design، ملفات هي رسومات تم إنشاؤها ودعمها بواسطة تطبيقات CAD مثل MicroStation و Intergraph Interactive Graphics Design System.
Learn more about this file format [here](../https://wiki.fileformat.com/cad/dgn).


### Dwf {#Dwf}
```
public static final CadFileType Dwf
```


Design Web Format (DWF) يمثل رسومات ثنائية/ثلاثية الأبعاد بصيغة مضغوطة للعرض أو المراجعة أو طباعة ملفات التصميم. يحتوي على رسومات ونص كجزء من بيانات التصميم ويقلل حجم الملف بفضل صيغته المضغوطة.
Learn more about this file format [here](../https://wiki.fileformat.com/cad/dwf).


### Stl {#Stl}
```
public static final CadFileType Stl
```


STL، اختصار لـ stereolithrography، هو تنسيق ملف قابل للتبادل يمثل هندسة سطح ثلاثية الأبعاد. يُستخدم هذا التنسيق في عدة مجالات مثل النمذجة السريعة، الطباعة ثلاثية الأبعاد، والتصنيع بمساعدة الحاسوب.
تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/cad/stl).


### Ifc {#Ifc}
```
public static final CadFileType Ifc
```


الملفات ذات الامتداد IFC تشير إلى تنسيق ملفات Industry Foundation Classes (IFC) الذي يضع معايير دولية لاستيراد وتصدير كائنات المباني وخصائصها. يوفر هذا التنسيق قابلية التفاعل بين تطبيقات البرمجيات المختلفة.
تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/cad/ifc).


### Plt {#Plt}
```
public static final CadFileType Plt
```


تنسيق ملف PLT هو ملف رسام متجه تم تقديمه من قبل Autodesk, Inc. ويحتوي على معلومات لملف CAD معين. تتطلب تفاصيل الرسم دقة وتحديد في الإنتاج، واستخدام ملف PLT يضمن ذلك حيث تُطبع جميع الصور باستخدام الخطوط بدلاً من النقاط.
تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/cad/plt).


### Igs {#Igs}
```
public static final CadFileType Igs
```


Igs document format


### Dwt {#Dwt}
```
public static final CadFileType Dwt
```


ملف DWT هو قالب رسم AutoCAD يُستخدم كنقطة بداية لإنشاء رسومات يمكن حفظها كملفات DWG.
تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/cad/dwt).


### Dwfx {#Dwfx}
```
public static final CadFileType Dwfx
```


ملف DWFX هو رسم ثنائي أو ثلاثي الأبعاد تم إنشاؤه باستخدام برنامج Autodesk CAD. يتم حفظه بتنسيق DWFx، وهو مشابه لملف .DWF، لكنه يُنسق باستخدام مواصفة XML Paper Specification (XPS) من مايكروسوفت.


### Cf2 {#Cf2}
```
public static final CadFileType Cf2
```


ملف تنسيق شائع. ملف CAD يحتوي على تصاميم حزم ثلاثية الأبعاد أو بيانات نماذج أخرى؛ يمكن معالجته وتقطيعه بواسطة آلة CAD/CAM، مثل جهاز القطع القالب.


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


إعداد خيارات التحميل الافتراضية لنوع ملف المصدر


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


إعداد خيارات التحويل الافتراضية لنوع الملف


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
