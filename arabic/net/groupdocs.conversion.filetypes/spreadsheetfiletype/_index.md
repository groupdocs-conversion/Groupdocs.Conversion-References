---
title: "SpreadsheetFileType"
second_title: "GroupDocs.Conversion لـ .NET مرجع API"
description: "يحدد مستندات Spreadsheet. يتضمن أنواع الملفات التالية Csv./spreadsheetfiletype/csv Fods./spreadsheetfiletype/fods Ods./spreadsheetfiletype/ods Ots./spreadsheetfiletype/ots Tsv./spreadsheetfiletype/tsv Xlam./spreadsheetfiletype/xlam Xls./spreadsheetfiletype/xls Xlsb./spreadsheetfiletype/xlsb Xlsm./spreadsheetfiletype/xlsm Xlsx./spreadsheetfiletype/xlsx Xlt./spreadsheetfiletype/xlt Xltm./spreadsheetfiletype/xltm Xltx./spreadsheetfiletype/xltx. تعرف على المزيد حول تنسيقات Spreadsheet هناhttps//wiki.fileformat.com/spreadsheet."
type: docs
weight: 1240
url: /ar/net/groupdocs.conversion.filetypes/spreadsheetfiletype/
---
## SpreadsheetFileType class

يحدد مستندات Spreadsheet. يتضمن أنواع الملفات التالية: [`Csv`](./csv), [`Fods`](./fods), [`Ods`](./ods), [`Ots`](./ots), [`Tsv`](./tsv), [`Xlam`](./xlam), [`Xls`](./xls), [`Xlsb`](./xlsb), [`Xlsm`](./xlsm), [`Xlsx`](./xlsx), [`Xlt`](./xlt), [`Xltm`](./xltm), [`Xltx`](./xltx). تعرف على المزيد حول تنسيقات Spreadsheet [هنا](https://wiki.fileformat.com/spreadsheet).

```csharp
public sealed class SpreadsheetFileType : FileType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [SpreadsheetFileType](spreadsheetfiletype)() | منشئ التسلسل |

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
| static readonly [Csv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/csv) | الملفات ذات امتداد CSV (Comma Separated Values) تمثل ملفات نصية عادية تحتوي على سجلات بيانات مفصولة بفواصل. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/spreadsheet/csv). |
| static readonly [Dif](../../groupdocs.conversion.filetypes/spreadsheetfiletype/dif) | DIF هو اختصار لـ Data Interchange Format الذي يُستخدم لاستيراد/تصدير بيانات جداول البيانات بين تطبيقات مختلفة. تشمل هذه Microsoft Excel وOpenOffice Calc وStarCalc والعديد غيرها. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/spreadsheet/dif). |
| static readonly [FlatOpc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/flatopc) | Flat OPC Excel هو Office Open XML SpreadsheetML مخزن في ملف XML مسطح بدلاً من حزمة ZIP. |
| static readonly [Fods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/fods) | الملف ذو امتداد .fods هو نوع من تنسيق مستندات OpenDocument Spreadsheet الذي يخزن البيانات في صفوف وأعمدة. يتم تحديد هذا التنسيق كجزء من مواصفات ODF 1.2 التي نشرتها وتديرها OASIS. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/spreadsheet/fods). |
| static readonly [Numbers](../../groupdocs.conversion.filetypes/spreadsheetfiletype/numbers) | الملفات ذات امتداد .numbers تُصنّف كنوع ملفات جداول بيانات، لذلك هي مشابهة لملفات .xlsx؛ لكن ملفات Numbers تُنشأ باستخدام برنامج Apple iWork Numbers لجداول البيانات. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/spreadsheet/numbers). |
| static readonly [Ods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ods) | الملفات ذات امتداد ODS تمثل تنسيق OpenDocument Spreadsheet Document القابل للتحرير من قبل المستخدم. يتم تخزين البيانات داخل ملف ODF في صفوف وأعمدة. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/spreadsheet/ods). |
| static readonly [Ots](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ots) | الملف ذو امتداد .ots هو ملف قالب OpenDocument Spreadsheet يتم إنشاؤه باستخدام برنامج Calc المضمن في Apache OpenOffice. برنامج Calc مشابه لبرنامج Excel المتوفر في Microsoft Office. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/spreadsheet/ots). |
| static readonly [Sxc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/sxc) | تنسيق الملف SXC (Sun XML Calc) ينتمي إلى مجموعة برامج مكتبية تسمى OpenOffice.org. هذا التنسيق يلبي احتياجات جداول البيانات للمستخدمين لأنه تنسيق ملف جداول بيانات مبني على XML. يدعم تنسيق SXC الصيغ والوظائف والماكرو والرسوم البيانية بالإضافة إلى DataPilot. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/spreadsheet/sxc). |
| static readonly [Tsv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/tsv) | تنسيق ملف القيم المفصولة بفواصل جدولة (TSV) يمثل البيانات المفصولة بفواصل جدولة في تنسيق نص عادي. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/spreadsheet/tsv). |
| static readonly [Xlam](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlam) | XLAM هو ملف إضافة مُمكّن للماكرو يُستخدم لإضافة وظائف جديدة إلى جداول البيانات. الإضافة هي برنامج مكمل يُشغل كودًا إضافيًا ويوفر وظائف إضافية لجداول البيانات. تعرف على المزيد حول تنسيق الملف هذا [here](https://docs.fileformat.com/spreadsheet/xlam/). |
| static readonly [Xls](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xls) | XLS يمثل تنسيق ملف Excel الثنائي. يمكن إنشاء مثل هذه الملفات بواسطة Microsoft Excel وكذلك برامج جداول بيانات مشابهة مثل OpenOffice Calc أو Apple Numbers. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/spreadsheet/xls). |
| static readonly [Xlsb](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsb) | تنسيق ملف XLSB يحدد تنسيق ملف Excel الثنائي، وهو مجموعة من السجلات والهياكل التي تحدد محتوى دفتر عمل Excel. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/spreadsheet/xlsb). |
| static readonly [Xlsm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsm) | XLSM هو نوع من ملفات جداول البيانات التي تدعم الماكرو. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/spreadsheet/xlsm). |
| static readonly [Xlsx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsx) | XLSX هو تنسيق معروف لمستندات Microsoft Excel تم تقديمه من قبل Microsoft مع إصدار Microsoft Office 2007. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/spreadsheet/xlsx). |
| static readonly [Xlt](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlt) | الملفات ذات الامتداد .XLT هي ملفات قالب تم إنشاؤها باستخدام Microsoft Excel وهو تطبيق جداول بيانات يأتي كجزء من مجموعة Microsoft Office. دعم Microsoft Office 97-2003 إنشاء ملفات XLT جديدة وكذلك فتحها. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/spreadsheet/xlt). |
| static readonly [Xltm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltm) | امتداد ملف XLTM يمثل الملفات التي يتم إنشاؤها بواسطة Microsoft Excel كملفات قالب مُمكّنة للماكرو. ملفات XLTM مشابهة لملفات XLTX في البنية باستثناء أن الأخيرة لا تدعم إنشاء ملفات قالب مع ماكرو. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/spreadsheet/xltm). |
| static readonly [Xltx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltx) | ملف XLTX يمثل قالب Microsoft Excel المستند إلى مواصفات تنسيق ملف Office OpenXML. يُستخدم لإنشاء ملف قالب قياسي يمكن استخدامه لتوليد ملفات XLSX التي تتطابق مع الإعدادات المحددة في ملف XLTX. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/spreadsheet/xltx). |

### انظر أيضًا

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
