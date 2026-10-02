---
title: "DiagramFileType"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يحدد مستندات المخطط."
type: docs
weight: 13
url: /ar/java/com.groupdocs.conversion.filetypes/diagramfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DiagramFileType extends FileType implements Serializable
```

يحدد مستندات المخطط. يتضمن الأنواع التالية:
[Vdw](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vdw),
[Vdx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vdx),
[Vsd](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsd),
[Vsdm](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsdm),
[Vsdx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsdx),
[Vss](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vss),
[Vssm](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vssm),
[Vssx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vssx),
[Vst](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vst),
[Vstm](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vstm),
[Vstx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vstx),
[Vsx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsx),
[Vtx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vtx).

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [DiagramFileType()](#DiagramFileType--) | منشئ التسلسل |
|
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Vsd](#Vsd) | ملفات VSD هي رسومات تم إنشاؤها باستخدام تطبيق Microsoft Visio لتمثيل مجموعة متنوعة من الكائنات الرسومية والاتصالات بينها. |
|
|  | [Vsdx](#Vsdx) | الملفات ذات الامتداد .VSDX تمثل تنسيق ملفات Microsoft Visio الذي تم تقديمه بدءًا من Microsoft Office 2013 فصاعدًا. |
|
|  | [Vss](#Vss) | VSS هي ملفات قوالب تم إنشاؤها باستخدام Microsoft Visio 2007 وما قبله. |
|
|  | [Vst](#Vst) | الملفات ذات الامتداد VST هي ملفات صور متجهة تم إنشاؤها باستخدام Microsoft Visio وتعمل كقالب لإنشاء ملفات أخرى. |
|
|  | [Vsx](#Vsx) | الملفات ذات الامتداد .VSX تشير إلى قوالب تتكون من رسومات وأشكال تُستخدم لإنشاء مخططات في Microsoft Visio. |
|
|  | [Vtx](#Vtx) | الملف ذو الامتداد VTX هو قالب رسم Microsoft Visio يتم حفظه على القرص بتنسيق ملف XML. |
|
|  | [Vdw](#Vdw) | VDW هو تنسيق ملف Visio Graphics Service الذي يحدد التدفقات والتخزينات المطلوبة لتصيير رسم ويب. |
|
|  | [Vdx](#Vdx) | أي رسم أو مخطط تم إنشاؤه في Microsoft Visio، ولكن تم حفظه بتنسيق XML يحمل الامتداد .VDX. |
|
|  | [Vssx](#Vssx) | الملفات ذات الامتداد .VSSX هي قوالب رسومات تم إنشاؤها باستخدام Microsoft Visio 2013 وما بعده. |
|
|  | [Vstx](#Vstx) | الملفات ذات الامتداد VSTX هي ملفات قالب رسم تم إنشاؤها باستخدام Microsoft Visio 2013 وما بعده. |
|
|  | [Vsdm](#Vsdm) | الملفات ذات الامتداد VSDM هي ملفات رسومات تم إنشاؤها باستخدام تطبيق Microsoft Visio الذي يدعم الماكرو. |
|
|  | [Vssm](#Vssm) | الملفات ذات الامتداد .VSSM هي ملفات قوالب Microsoft Visio التي توفر دعمًا للماكرو. |
|
|  | [Vstm](#Vstm) | الملفات ذات الامتداد VSTM هي ملفات قالب تم إنشاؤها باستخدام Microsoft Visio وتدعم الماكرو. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### DiagramFileType() {#DiagramFileType--}
```
public DiagramFileType()
```


منشئ التسلسل


### Vsd {#Vsd}
```
public static final DiagramFileType Vsd
```


ملفات VSD هي رسومات تم إنشاؤها باستخدام تطبيق Microsoft Visio لتمثيل مجموعة متنوعة من الكائنات الرسومية والاتصالات بينها.
تعرف على المزيد حول تنسيق الملف هذا [هنا](../https://wiki.fileformat.com/image/vsd).


### Vsdx {#Vsdx}
```
public static final DiagramFileType Vsdx
```


الملفات ذات الامتداد .VSDX تمثل تنسيق ملف Microsoft Visio الذي تم تقديمه بدءًا من Microsoft Office 2013 فصاعدًا. تم تطويره لاستبدال تنسيق الملف الثنائي .VSD، الذي تدعمه الإصدارات السابقة من Microsoft Visio.
تعرف على المزيد حول تنسيق الملف هذا [هنا](../https://wiki.fileformat.com/image/vsdx).


### Vss {#Vss}
```
public static final DiagramFileType Vss
```


VSS هي ملفات قوالب تم إنشاؤها باستخدام Microsoft Visio 2007 وما قبله. توفر ملفات القوالب كائنات رسم يمكن تضمينها في رسم .VSD في Visio.
تعرف على المزيد حول تنسيق الملف هذا [هنا](../https://wiki.fileformat.com/image/vss).


### Vst {#Vst}
```
public static final DiagramFileType Vst
```


الملفات ذات الامتداد VST هي ملفات صور متجهة تم إنشاؤها باستخدام Microsoft Visio وتعمل كقالب لإنشاء ملفات أخرى. هذه الملفات القالبية بتنسيق ملف ثنائي وتحتوي على التخطيط والإعدادات الافتراضية التي تُستَخدم لإنشاء رسومات Visio جديدة.
تعرف على المزيد حول تنسيق الملف هذا [هنا](../https://wiki.fileformat.com/image/vst).


### Vsx {#Vsx}
```
public static final DiagramFileType Vsx
```


الملفات ذات الامتداد .VSX تشير إلى قوالب تتكون من رسومات وأشكال تُستخدم لإنشاء مخططات في Microsoft Visio. تُحفظ ملفات VSX بتنسيق XML وقد تم دعمها حتى Visio 2013.
تعرف على المزيد حول تنسيق الملف هذا [هنا](../https://wiki.fileformat.com/image/vsx).


### Vtx {#Vtx}
```
public static final DiagramFileType Vtx
```


الملف ذو الامتداد VTX هو قالب رسم Microsoft Visio يتم حفظه على القرص بتنسيق XML. يهدف القالب إلى توفير ملف بإعدادات أساسية يمكن استخدامها لإنشاء ملفات Visio متعددة بنفس الإعدادات.
تعرف على المزيد حول تنسيق الملف هذا [هنا](../https://wiki.fileformat.com/image/vtx).


### Vdw {#Vdw}
```
public static final DiagramFileType Vdw
```


VDW هو تنسيق ملف Visio Graphics Service الذي يحدد التدفقات والتخزينات المطلوبة لتصيير رسم ويب.
تعرف على المزيد حول تنسيق الملف هذا [هنا](../https://wiki.fileformat.com/web/vdw).


### Vdx {#Vdx}
```
public static final DiagramFileType Vdx
```


أي رسم أو مخطط تم إنشاؤه في Microsoft Visio، ولكن تم حفظه بتنسيق XML له امتداد .VDX. يتم إنشاء ملف رسم XML في Visio باستخدام برنامج Visio، الذي تطوره Microsoft.
تعرف على المزيد حول تنسيق الملف هذا [هنا](../https://wiki.fileformat.com/image/vdx).


### Vssx {#Vssx}
```
public static final DiagramFileType Vssx
```


الملفات ذات الامتداد .VSSX هي قوالب رسومات تم إنشاؤها باستخدام Microsoft Visio 2013 وما فوق. يمكن فتح تنسيق ملف VSSX باستخدام Visio 2013 وما فوق. تُعرف ملفات Visio بتمثيل مجموعة متنوعة من عناصر الرسم مثل مجموعة الأشكال، الموصلات، المخططات الانسيابية، تخطيط الشبكات، مخططات UML،
تعرف على المزيد حول تنسيق الملف هذا [هنا](../https://wiki.fileformat.com/image/vssx).


### Vstx {#Vstx}
```
public static final DiagramFileType Vstx
```


الملفات ذات الامتداد VSTX هي ملفات قوالب رسومات تم إنشاؤها باستخدام Microsoft Visio 2013 وما فوق. توفر ملفات VSTX نقطة انطلاق لإنشاء رسومات Visio، تُحفظ كملفات .VSDX، مع تخطيط وإعدادات افتراضية.
تعرف على المزيد حول تنسيق الملف هذا [هنا](../https://wiki.fileformat.com/image/vstx).


### Vsdm {#Vsdm}
```
public static final DiagramFileType Vsdm
```


الملفات ذات الامتداد VSDM هي ملفات رسومات تم إنشاؤها باستخدام تطبيق Microsoft Visio الذي يدعم الماكرو. ملفات VSDM هي رسومات OPC/XML تشبه VSDX، لكنها توفر أيضًا القدرة على تشغيل الماكرو عند فتح الملف.
تعرف على المزيد حول تنسيق الملف هذا [هنا](../https://wiki.fileformat.com/image/vsdm).


### Vssm {#Vssm}
```
public static final DiagramFileType Vssm
```


الملفات ذات الامتداد .VSSM هي ملفات قوالب Microsoft Visio التي تدعم الماكرو. عند فتح ملف VSSM يسمح بتشغيل الماكرو لتحقيق التنسيق المطلوب ووضع الأشكال في المخطط.
تعرف على المزيد حول تنسيق الملف هذا [هنا](../https://wiki.fileformat.com/image/vssm).


### Vstm {#Vstm}
```
public static final DiagramFileType Vstm
```


الملفات ذات الامتداد VSTM هي ملفات قوالب تم إنشاؤها باستخدام Microsoft Visio وتدعم الماكرو. على عكس ملفات VSDX، يمكن للملفات التي تم إنشاؤها من قوالب VSTM تشغيل الماكرو الذي تم تطويره بلغة Visual Basic for Applications (VBA).
تعرف على المزيد حول تنسيق الملف هذا [هنا](../https://wiki.fileformat.com/image/vstm).


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
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static final FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
