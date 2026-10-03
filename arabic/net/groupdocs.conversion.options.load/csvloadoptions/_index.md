---
title: "CsvLoadOptions"
second_title: "GroupDocs.Conversion لـ .NET مرجع API"
description: "خيارات تحميل مستندات Csv."
type: docs
weight: 2450
url: /ar/net/groupdocs.conversion.options.load/csvloadoptions/
---
## CsvLoadOptions class

خيارات تحميل مستندات Csv.

```csharp
public sealed class CsvLoadOptions : SpreadsheetLoadOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [CsvLoadOptions](csvloadoptions)() | يُنشئ مثلاً جديداً من الفئة [`CsvLoadOptions`](../csvloadoptions). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AllColumnsInOnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/allcolumnsinonepagepersheet) { get; set; } | إذا كان AllColumnsInOnePagePerSheet صحيحًا، فسيتم إخراج محتوى جميع الأعمدة في ورقة واحدة إلى صفحة واحدة فقط في النتيجة. سيصبح عرض حجم الورق في إعدادات الصفحة غير صالح، بينما ستظل الإعدادات الأخرى لإعدادات الصفحة سارية. |
| [AutoFitRows](../../groupdocs.conversion.options.load/spreadsheetloadoptions/autofitrows) { get; set; } | يضبط تلقائيًا جميع الصفوف عند التحويل |
| [CheckExcelRestriction](../../groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction) { get; set; } | ما إذا كان يتم التحقق من قيود ملف Excel عندما يقوم المستخدم بتعديل الكائنات المتعلقة بالخلايا. على سبيل المثال، لا يسمح Excel بإدخال قيمة نصية أطول من 32 كيلوبايت. عندما تُدخل قيمة أطول من 32 كيلوبايت، إذا كانت هذه الخاصية صحيحة، ستحصل على **Exception**. إذا كانت هذه الخاصية خاطئة، سنقبل قيمة النص التي أدخلتها كقيمة الخلية بحيث يمكنك لاحقًا إخراج القيمة النصية الكاملة إلى صيغ ملفات أخرى مثل CSV. ومع ذلك، إذا قمت بتعيين قيمة غير صالحة لتنسيق ملف Excel، يجب ألا تحفظ المصنف بتنسيق Excel لاحقًا. وإلا قد يحدث خطأ غير متوقع في ملف Excel المُنشأ. |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clearbuiltindocumentproperties) { get; set; } | يزيل خصائص البيانات الوصفية المدمجة من المستند. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clearcustomdocumentproperties) { get; set; } | يزيل خصائص البيانات الوصفية المخصصة من المستند. |
| [ColumnsPerPage](../../groupdocs.conversion.options.load/spreadsheetloadoptions/columnsperpage) { get; set; } | قسّم ورقة العمل إلى صفحات حسب الأعمدة. القيمة الافتراضية هي 0، بدون ترقيم صفحات. |
| [ConvertDateTimeData](../../groupdocs.conversion.options.load/csvloadoptions/convertdatetimedata) { get; set; } | يحدد ما إذا كان السلسلة في الملف تُحوَّل إلى تاريخ. القيمة الافتراضية هي True. |
| [ConvertNumericData](../../groupdocs.conversion.options.load/csvloadoptions/convertnumericdata) { get; set; } | يحدد ما إذا كان السلسلة في الملف تُحوَّل إلى رقم. القيمة الافتراضية هي True. |
| [ConvertOwned](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertowned) { get; set; } | تنفيذ [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) القيمة الافتراضية هي false |
| [ConvertOwner](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertowner) { get; set; } | تنفيذ [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) القيمة الافتراضية هي true |
| [ConvertRange](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertrange) { get; set; } | حوّل نطاقًا محددًا عند التحويل إلى صيغة غير جدول بيانات. مثال: "D1:F8". |
| [CultureInfo](../../groupdocs.conversion.options.load/spreadsheetloadoptions/cultureinfo) { get; set; } | احصل على أو عيّن معلومات الثقافة النظامية عند تحميل الملف. |
| [DefaultFont](../../groupdocs.conversion.options.load/spreadsheetloadoptions/defaultfont) { get; set; } | الخط الافتراضي لمستند جدول البيانات. سيتم استخدام الخط التالي إذا كان الخط مفقودًا. |
| [Depth](../../groupdocs.conversion.options.load/spreadsheetloadoptions/depth) { get; set; } | تنفيذ [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) القيمة الافتراضية: 1 |
| [Encoding](../../groupdocs.conversion.options.load/csvloadoptions/encoding) { get; set; } | الترميز. القيمة الافتراضية هي Encoding.Default. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/fontsubstitutes) { get; set; } | استبدل خطوطًا محددة عند تحويل مستند جدول البيانات. |
| [Format](../../groupdocs.conversion.options.load/csvloadoptions/format) { get; } | نوع ملف المستند المدخل. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | نوع ملف المستند المدخل. |
| [HasFormula](../../groupdocs.conversion.options.load/csvloadoptions/hasformula) { get; set; } | يحدد ما إذا كان النص صيغة إذا بدأ بـ "=". |
| [IgnoreFormulaCalculationErrors](../../groupdocs.conversion.options.load/spreadsheetloadoptions/ignoreformulacalculationerrors) { get; set; } | يحدد ما إذا كان يجب تجاهل أخطاء حساب الصيغ. قد يكون الخطأ نتيجة دالة غير مدعومة، روابط خارجية، إلخ. القيمة الافتراضية هي false. |
| [IsMultiEncoded](../../groupdocs.conversion.options.load/csvloadoptions/ismultiencoded) { get; set; } | True يعني أن الملف يحتوي على عدة ترميزات. |
| [MarginSettings](../../groupdocs.conversion.options.load/spreadsheetloadoptions/marginsettings) { get; set; } | إعدادات هوامش الصفحة |
| [OnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/onepagepersheet) { get; set; } | إذا كان **OnePagePerSheet** صحيحًا، سيتم تحويل محتوى الورقة إلى صفحة واحدة في مستند PDF. القيمة الافتراضية هي true. |
| [OptimizePdfSize](../../groupdocs.conversion.options.load/spreadsheetloadoptions/optimizepdfsize) { get; set; } | إذا كان True وعند التحويل إلى PDF، يتم تحسين التحويل للحصول على حجم ملف أصغر مقارنة بجودة الطباعة. |
| [Password](../../groupdocs.conversion.options.load/spreadsheetloadoptions/password) { get; set; } | تعيين كلمة مرور لإلغاء حماية المستند المحمي. |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/spreadsheetloadoptions/preservedocumentstructure) { get; set; } | يحدد ما إذا كان يجب الحفاظ على بنية المستند عند التحويل إلى PDF (القيمة الافتراضية هي false). |
| [PrintComments](../../groupdocs.conversion.options.load/spreadsheetloadoptions/printcomments) { get; set; } | يمثل طريقة طباعة التعليقات مع الورقة. القيمة الافتراضية هي PrintNoComments. |
| [ResetFontFolders](../../groupdocs.conversion.options.load/spreadsheetloadoptions/resetfontfolders) { get; set; } | أعد ضبط مجلدات الخطوط قبل تحميل المستند. |
| [RowsPerPage](../../groupdocs.conversion.options.load/spreadsheetloadoptions/rowsperpage) { get; set; } | قسّم ورقة العمل إلى صفحات حسب الصفوف. القيمة الافتراضية هي 0، بدون ترقيم صفحات. |
| [Separator](../../groupdocs.conversion.options.load/csvloadoptions/separator) { get; set; } | فاصل ملف Csv. |
| [SheetIndexes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheetindexes) { get; set; } | قائمة مؤشرات الأوراق للتحويل. يجب أن تكون المؤشرات صفرية الأساس. |
| [Sheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheets) { get; set; } | اسم الورقة للتحويل. |
| [ShowGridLines](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showgridlines) { get; set; } | إظهار خطوط الشبكة عند تحويل ملفات Excel. |
| [ShowHiddenSheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showhiddensheets) { get; set; } | إظهار الأوراق المخفية عند تحويل ملفات Excel. |
| [SizeSettings](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sizesettings) { get; set; } | إعدادات حجم الصفحة |
| [SkipEmptyRowsAndColumns](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipemptyrowsandcolumns) { get; set; } | يتخطى الصفوف والأعمدة الفارغة عند التحويل. القيمة الافتراضية هي True. |
| [SkipExternalResources](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipexternalresources) { get; set; } | تنفيذ [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [SkipFooters](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipfooters) { get; set; } | تخطي التذييلات عند تحويل مستندات جدول البيانات. القيمة الافتراضية: false. |
| [SkipHeaders](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipheaders) { get; set; } | تخطي الرؤوس عند تحويل مستندات جدول البيانات. القيمة الافتراضية: false. |
| [WhitelistedResources](../../groupdocs.conversion.options.load/spreadsheetloadoptions/whitelistedresources) { get; set; } | تنفيذ [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clone)() | ينسخ النسخة الحالية. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | يحدد ما إذا كان مثيلان للكائن متساويين. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | يحدد ما إذا كان مثيلان للكائن متساويين. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | يعمل كدالة التجزئة الافتراضية. |

### انظر أيضًا

* class [SpreadsheetLoadOptions](../spreadsheetloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
