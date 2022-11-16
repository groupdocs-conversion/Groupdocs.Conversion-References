---
title: SpreadsheetFileType
second_title: GroupDocs.Conversion لمرجع .NET API
description: يحدد مستندات جداول البيانات. يتضمن أنواع الملفات التالية Csv./spreadsheetfiletype/csv  Fods./spreadsheetfiletype/fods  Ods./spreadsheetfiletype/ods  Ots./spreadsheetfiletype/ots  Tsv./spreadsheetfiletype/tsv  Xlam./spreadsheetfiletype/xlam  Xls./spreadsheetfiletype/xls  Xlsb./spreadsheetfiletype/xlsb  Xlsm./spreadsheetfiletype/xlsm  Xlsx./spreadsheetfiletype/xlsx  Xlt./spreadsheetfiletype/xlt  Xltm./spreadsheetfiletype/xltm  Xltx./spreadsheetfiletype/xltx . تعرف على المزيد حول تنسيقات جداول البياناتهناhttps//wiki.fileformat.com/spreadsheet .
type: docs
weight: 930
url: /ar/net/groupdocs.conversion.filetypes/spreadsheetfiletype/
---
## SpreadsheetFileType class

يحدد مستندات جداول البيانات. يتضمن أنواع الملفات التالية: [`Csv`](./csv) ، [`Fods`](./fods) ، [`Ods`](./ods) ، [`Ots`](./ots) ، [`Tsv`](./tsv) ، [`Xlam`](./xlam) ، [`Xls`](./xls) ، [`Xlsb`](./xlsb) ، [`Xlsm`](./xlsm) ، [`Xlsx`](./xlsx) ، [`Xlt`](./xlt) ، [`Xltm`](./xltm) ، [`Xltx`](./xltx) . تعرف على المزيد حول تنسيقات جداول البيانات[هنا](https://wiki.fileformat.com/spreadsheet) .

```csharp
public sealed class SpreadsheetFileType : FileType
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [SpreadsheetFileType](spreadsheetfiletype)() | مُنشئ التسلسل |

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
| static readonly [Csv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/csv) | تمثل الملفات ذات الامتداد CSV (قيم مفصولة بفواصل) ملفات نصية عادية تحتوي على سجلات بيانات بقيم مفصولة بفواصل . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/csv) . |
| static readonly [Dif](../../groupdocs.conversion.filetypes/spreadsheetfiletype/dif) | يرمز DIF إلى تنسيق تبادل البيانات المستخدم لاستيراد / تصدير بيانات جداول البيانات بين التطبيقات المختلفة. وتشمل هذه Microsoft Excel و OpenOffice Calc و StarCalc وغيرها الكثير. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/dif) . |
| static readonly [Fods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/fods) | جدول بيانات XML مسطح OpenDocument |
| static readonly [Numbers](../../groupdocs.conversion.filetypes/spreadsheetfiletype/numbers) | تم تصنيف الملفات ذات الامتداد .numbers كنوع ملف جدول بيانات ، وهذا هو سبب تشابهها مع ملفات .xlsx ؛ ولكن يتم إنشاء ملفات Numbers باستخدام برنامج جداول بيانات Apple iWork Numbers . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/spreadsheet/numbers) . |
| static readonly [Ods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ods) | تمثل الملفات ذات ملحق ODS تنسيق OpenDocument Spreadsheet Document الذي يمكن للمستخدم تحريره. يتم تخزين البيانات داخل ملف ODF في صفوف وأعمدة. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [Ots](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ots) | قالب جدول بيانات OpenDocument |
| static readonly [Sxc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/sxc) | تنسيق مستند إلى XML يستخدمه OpenOffice و StarOffice |
| static readonly [Tsv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/tsv) | يمثل تنسيق ملف قيم مفصولة بعلامات جدولة (TSV) بيانات مفصولة بعلامات تبويب بتنسيق نص عادي. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/tsv) . |
| static readonly [Xlam](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlam) | تنسيق مستند Xlam |
| static readonly [Xls](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xls) | يمثل XLS تنسيق ملف Excel الثنائي. يمكن إنشاء مثل هذه الملفات بواسطة Microsoft Excel بالإضافة إلى برامج جداول البيانات المماثلة الأخرى مثل OpenOffice Calc أو Apple Numbers. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [Xlsb](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsb) | يحدد تنسيق ملف XLSB تنسيق ملف Excel الثنائي ، وهو عبارة عن مجموعة من السجلات والهياكل التي تحدد محتوى مصنف Excel. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [Xlsm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsm) | XLSM هو نوع من ملفات جداول البيانات التي تدعم وحدات الماكرو . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [Xlsx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsx) | XLSX هو تنسيق معروف لمستندات Microsoft Excel تم تقديمه بواسطة Microsoft مع إصدار Microsoft Office 2007. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [Xlt](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlt) | الملفات ذات الامتداد .XLT هي ملفات قوالب تم إنشاؤها باستخدام Microsoft Excel وهو تطبيق جداول بيانات يأتي كجزء من مجموعة Microsoft Office. دعم Microsoft Office 97-2003 إنشاء ملفات XLT جديدة بالإضافة إلى فتحها. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [Xltm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltm) | يمثل امتداد الملف XLTM الملفات التي تم إنشاؤها بواسطة Microsoft Excel كملفات قوالب ممكنة بماكرو. تتشابه ملفات XLTM مع XLTX من حيث البنية بخلاف أن أحدثها لا يدعم إنشاء ملفات القوالب باستخدام وحدات الماكرو. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/xltm) . |
| static readonly [Xltx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltx) | يمثل ملف XLTX قالب Microsoft Excel الذي يستند إلى مواصفات تنسيق ملف Office OpenXML. يتم استخدامه لإنشاء ملف قالب قياسي يمكن استخدامه لإنشاء ملفات XLSX التي تعرض نفس الإعدادات المحددة في ملف XLTX . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/xltx) . |

### أنظر أيضا

* class [FileType](../filetype)
* مساحة الاسم [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* المجسم [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
