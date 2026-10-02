---
title: "SpreadsheetFileType"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يحدد مستندات جداول البيانات."
type: docs
weight: 25
url: /ar/java/com.groupdocs.conversion.filetypes/spreadsheetfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class SpreadsheetFileType extends FileType implements Serializable
```

يحدد مستندات جداول البيانات. يتضمن أنواع الملفات التالية:
[Csv](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Csv),
[Fods](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Fods),
[Ods](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Ods),
[Ots](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Ots),
[Tsv](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Tsv),
[Xlam](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlam),
[Xls](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xls),
[Xlsb](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlsb),
[Xlsm](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlsm),
[Xlsx](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlsx),
[Xlt](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlt),
[Xltm](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xltm),
[Xltx](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xltx).
تعرف على المزيد حول تنسيقات جداول البيانات [هنا](../https://wiki.fileformat.com/spreadsheet).

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [SpreadsheetFileType()](#SpreadsheetFileType--) | منشئ التسلسل |
|
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Xls](#Xls) | XLS تمثل تنسيق ملف Excel الثنائي. |
|
|  | [Xlsx](#Xlsx) | XLSX هو تنسيق معروف جيدًا لمستندات Microsoft Excel تم تقديمه من قبل Microsoft مع إصدار Microsoft Office 2007. |
|
|  | [Xlsm](#Xlsm) | XLSM هو نوع من ملفات جداول البيانات التي تدعم وحدات الماكرو. |
|
|  | [Xlsb](#Xlsb) | تنسيق ملف XLSB يحدد تنسيق ملف Excel الثنائي، وهو مجموعة من السجلات والهياكل التي تحدد محتوى دفتر عمل Excel. |
|
|  | [Ods](#Ods) | الملفات ذات الامتداد ODS تمثل تنسيق مستند جداول بيانات OpenDocument القابل للتحرير من قبل المستخدم. |
|
|  | [Ots](#Ots) | الملف ذو الامتداد .ots هو قالب مستند جداول بيانات OpenDocument يتم إنشاؤه باستخدام برنامج تطبيق Calc المضمن في Apache OpenOffice. |
|
|  | [Xltx](#Xltx) | ملف XLTX يمثل قالب Microsoft Excel المستند إلى مواصفات تنسيق ملف Office OpenXML. |
|
|  | [Xlt](#Xlt) | الملفات ذات الامتداد .XLT هي ملفات قالب تم إنشاؤها باستخدام Microsoft Excel، وهو تطبيق جداول بيانات يأتي كجزء من مجموعة Microsoft Office. |
|
|  | [Xltm](#Xltm) | امتداد ملف XLTM يمثل الملفات التي يتم إنشاؤها بواسطة Microsoft Excel كقوالب مُمكّنة للماكرو. |
|
|  | [Tsv](#Tsv) | تنسيق ملف القيم المفصولة بالجدولة (TSV) يمثل البيانات المفصولة بأشرطة الجدولة في تنسيق نص عادي. |
|
|  | [Xlam](#Xlam) | XLAM هو ملف إضافة مُمكّن للماكرو يُستخدم لإضافة وظائف جديدة إلى جداول البيانات. |
|
|  | [Csv](#Csv) | الملفات ذات الامتداد CSV (قيم مفصولة بفواصل) تمثل ملفات نصية عادية تحتوي على سجلات بيانات مفصولة بفواصل. |
|
|  | [Fods](#Fods) | الملف ذو الامتداد .fods هو نوع من تنسيق مستند جداول بيانات OpenDocument الذي يخزن البيانات في صفوف وأعمدة. |
|
|  | [Dif](#Dif) | DIF يرمز إلى تنسيق تبادل البيانات الذي يُستخدم لاستيراد/تصدير بيانات جداول البيانات بين التطبيقات المختلفة. |
|
|  | [Sxc](#Sxc) | تنسيق الملف SXC (Sun XML Calc) ينتمي إلى مجموعة مكتبية تُدعى OpenOffice.org. |
|
|  | [Numbers](#Numbers) | الملفات ذات امتداد .numbers تُصنّف كنوع ملف جدول بيانات، وهذا هو السبب في تشابهها مع ملفات .xlsx؛ لكن ملفات Numbers تُنشأ باستخدام برنامج Apple iWork Numbers لجداول البيانات. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### SpreadsheetFileType() {#SpreadsheetFileType--}
```
public SpreadsheetFileType()
```


منشئ التسلسل


### Xls {#Xls}
```
public static final SpreadsheetFileType Xls
```


XLS يمثل تنسيق ملف Excel الثنائي. يمكن إنشاء مثل هذه الملفات بواسطة Microsoft Excel وكذلك برامج الجداول الحسابية المماثلة مثل OpenOffice Calc أو Apple Numbers.
تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/spreadsheet/xls).


### Xlsx {#Xlsx}
```
public static final SpreadsheetFileType Xlsx
```


XLSX هو تنسيق معروف جيدًا لمستندات Microsoft Excel تم تقديمه من قبل Microsoft مع إصدار Microsoft Office 2007.
تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/spreadsheet/xlsx).


### Xlsm {#Xlsm}
```
public static final SpreadsheetFileType Xlsm
```


XLSM هو نوع من ملفات جداول البيانات التي تدعم وحدات الماكرو.
تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/spreadsheet/xlsm).


### Xlsb {#Xlsb}
```
public static final SpreadsheetFileType Xlsb
```


تنسيق ملف XLSB يحدد تنسيق ملف Excel الثنائي، وهو مجموعة من السجلات والهياكل التي تحدد محتوى دفتر عمل Excel.
تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/spreadsheet/xlsb).


### Ods {#Ods}
```
public static final SpreadsheetFileType Ods
```


الملفات ذات امتداد ODS تمثل تنسيق مستند جدول بيانات OpenDocument القابل للتحرير من قبل المستخدم. يتم تخزين البيانات داخل ملف ODF في صفوف وأعمدة.
تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/spreadsheet/ods).


### Ots {#Ots}
```
public static final SpreadsheetFileType Ots
```


الملف ذو امتداد .ots هو ملف قالب جدول بيانات OpenDocument يتم إنشاؤه باستخدام برنامج Calc المضمن في Apache OpenOffice. برنامج Calc مشابه لبرنامج Excel المتوفر في Microsoft Office.
تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/spreadsheet/ots).


### Xltx {#Xltx}
```
public static final SpreadsheetFileType Xltx
```


ملف XLTX يمثل قالب Microsoft Excel المستند إلى مواصفات تنسيق ملف Office OpenXML. يُستخدم لإنشاء ملف قالب قياسي يمكن استخدامه لتوليد ملفات XLSX التي تتضمن نفس الإعدادات المحددة في ملف XLTX.
تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/spreadsheet/xltx).


### Xlt {#Xlt}
```
public static final SpreadsheetFileType Xlt
```


الملفات ذات امتداد .XLT هي ملفات قالب تم إنشاؤها باستخدام Microsoft Excel وهو تطبيق جدول بيانات يأتي كجزء من مجموعة Microsoft Office. دعم Microsoft Office 97-2003 إنشاء ملفات XLT جديدة وكذلك فتحها.
تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/spreadsheet/xlt).


### Xltm {#Xltm}
```
public static final SpreadsheetFileType Xltm
```


امتداد ملف XLTM يمثل ملفات يتم إنشاؤها بواسطة Microsoft Excel كقوالب مفعّلة بالماكرو. ملفات XLTM مشابهة لملفات XLTX في البنية باستثناء أن الأخيرة لا تدعم إنشاء قوالب تحتوي على ماكرو.
تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/spreadsheet/xltm).


### Tsv {#Tsv}
```
public static final SpreadsheetFileType Tsv
```


تنسيق ملف القيم المفصولة بالجدولة (TSV) يمثل البيانات المفصولة بأشرطة الجدولة في تنسيق نص عادي.
تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/spreadsheet/tsv).


### Xlam {#Xlam}
```
public static final SpreadsheetFileType Xlam
```


XLAM هو ملف إضافة مفعّل بالماكرو يُستخدم لإضافة وظائف جديدة إلى جداول البيانات. الإضافة هي برنامج مكمل يُنفّذ كودًا إضافيًا ويوفر وظائف إضافية لجداول البيانات.
تعرف على المزيد حول هذا التنسيق [هنا](../https://docs.fileformat.com/spreadsheet/xlam/)


### Csv {#Csv}
```
public static final SpreadsheetFileType Csv
```


الملفات ذات الامتداد CSV (قيم مفصولة بفواصل) تمثل ملفات نصية عادية تحتوي على سجلات بيانات مفصولة بفواصل.
تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/spreadsheet/csv).


### Fods {#Fods}
```
public static final SpreadsheetFileType Fods
```


الملف ذو امتداد .fods هو نوع من تنسيق مستند جدول بيانات OpenDocument الذي يخزن البيانات في صفوف وأعمدة. يُحدد هذا التنسيق كجزء من مواصفات ODF 1.2 التي نشرتها وتديرها OASIS. تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/spreadsheet/fods).


### Dif {#Dif}
```
public static final SpreadsheetFileType Dif
```


DIF هو اختصار لـ Data Interchange Format يُستخدم لاستيراد/تصدير بيانات جداول البيانات بين تطبيقات مختلفة. تشمل هذه التطبيقات Microsoft Excel وOpenOffice Calc وStarCalc والعديد غيرها. تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/spreadsheet/dif).


### Sxc {#Sxc}
```
public static final SpreadsheetFileType Sxc
```


تنسيق الملف SXC (Sun XML Calc) ينتمي إلى مجموعة مكتبية تُدعى OpenOffice.org. يتعامل هذا التنسيق عمومًا مع احتياجات المستخدمين من جداول البيانات لأنه تنسيق ملف جدول بيانات قائم على XML. يدعم تنسيق SXC الصيغ، الدوال، الماكرو والرسوم البيانية بالإضافة إلى DataPilot. تعرف على المزيد حول هذا التنسيق [هنا](../https://wiki.fileformat.com/spreadsheet/sxc).


### Numbers {#Numbers}
```
public static final SpreadsheetFileType Numbers
```


الملفات ذات الامتداد .numbers تُصنّف كنوع ملف جدول بيانات، وهذا هو السبب في تشابهها مع ملفات .xlsx؛ لكن ملفات Numbers تُنشأ باستخدام برنامج Apple iWork Numbers لجدول البيانات. Learn more about this file format [here](../https://docs.fileformat.com/spreadsheet/numbers).


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
