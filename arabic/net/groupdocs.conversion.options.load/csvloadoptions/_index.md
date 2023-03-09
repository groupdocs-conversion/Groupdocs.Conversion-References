---
title: CsvLoadOptions
second_title: GroupDocs.Conversion لمرجع .NET API
description: خيارات لتحميل مستندات Csv .
type: docs
weight: 2050
url: /ar/net/groupdocs.conversion.options.load/csvloadoptions/
---
## CsvLoadOptions class

خيارات لتحميل مستندات Csv .

```csharp
public sealed class CsvLoadOptions : SpreadsheetLoadOptions
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [CsvLoadOptions](csvloadoptions)() | تهيئة مثيل جديد لـ[`CsvLoadOptions`](../csvloadoptions) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [CheckExcelRestriction](../../groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction) { get; set; } | ما إذا كان التحقق من تقييد ملف Excel عند تعديل المستخدم للكائنات ذات الصلة بالخلايا. على سبيل المثال ، لا يسمح Excel بإدخال قيمة سلسلة أطول من 32 كيلو بايت. عند إدخال قيمة أطول من 32 كيلو بايت ، إذا كانت هذه الخاصية صحيحة ، فستحصل على استثناء. إذا كانت هذه الخاصية خاطئة ، فسنقبل قيمة سلسلة الإدخال كقيمة للخلية بحيث يمكنك لاحقًا إخراج قيمة السلسلة الكاملة لتنسيقات الملفات الأخرى مثل CSV. ومع ذلك ، إذا قمت بتعيين مثل هذا النوع من القيمة غير الصالحة لتنسيق ملف Excel ، فلا يجب عليك حفظ المصنف كتنسيق ملف excel لاحقًا. وإلا فقد يكون هناك خطأ غير متوقع لملف Excel الذي تم إنشاؤه. |
| [ConvertDateTimeData](../../groupdocs.conversion.options.load/csvloadoptions/convertdatetimedata) { get; set; } | يشير إلى ما إذا كانت السلسلة في الملف قد تم تحويلها إلى تاريخ. الافتراضي هو صحيح. |
| [ConvertNumericData](../../groupdocs.conversion.options.load/csvloadoptions/convertnumericdata) { get; set; } | يشير إلى ما إذا كانت السلسلة في الملف قد تم تحويلها إلى رقم. الافتراضي هو صحيح. |
| [ConvertRange](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertrange) { get; set; } | تحويل نطاق معين عند التحويل إلى تنسيق آخر بخلاف تنسيق جدول البيانات. مثال: "D1: F8" . |
| [CultureInfo](../../groupdocs.conversion.options.load/spreadsheetloadoptions/cultureinfo) { get; set; } | الحصول على معلومات ثقافة النظام أو تعيينها في وقت تحميل الملف |
| [DefaultFont](../../groupdocs.conversion.options.load/spreadsheetloadoptions/defaultfont) { get; set; } | الخط الافتراضي لوثيقة جدول البيانات. سيتم استخدام الخط التالي إذا كان الخط مفقودًا. |
| [Encoding](../../groupdocs.conversion.options.load/csvloadoptions/encoding) { get; set; } | ترميز. الافتراضي هو الترميز. الافتراضي . |
| [FontSubstitutes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/fontsubstitutes) { get; set; } | استبدال خطوط معينة عند تحويل مستند جدول البيانات. |
| [Format](../../groupdocs.conversion.options.load/spreadsheetloadoptions/format) { get; set; } | نوع ملف مستند الإدخال . |
| [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | نوع ملف مستند الإدخال . |
| [HasFormula](../../groupdocs.conversion.options.load/csvloadoptions/hasformula) { get; set; } | يشير إلى ما إذا كان النص صيغة إذا كان يبدأ بـ "=" . |
| [HideComments](../../groupdocs.conversion.options.load/spreadsheetloadoptions/hidecomments) { get; set; } | إخفاء التعليقات. |
| [IsMultiEncoded](../../groupdocs.conversion.options.load/csvloadoptions/ismultiencoded) { get; set; } | صحيح يعني أن الملف يحتوي على عدة ترميزات. |
| [OnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/onepagepersheet) { get; set; } | إذا كان OnePagePerSheet صحيحًا ، فسيتم تحويل محتوى الورقة إلى صفحة واحدة في مستند PDF. القيمة الافتراضية هي صحيحة. |
| [OptimizePdfSize](../../groupdocs.conversion.options.load/spreadsheetloadoptions/optimizepdfsize) { get; set; } | إذا كان True والتحويل إلى Pdf ، فسيتم تحسين التحويل للحصول على حجم ملف أفضل من جودة الطباعة. |
| [Password](../../groupdocs.conversion.options.load/spreadsheetloadoptions/password) { get; set; } | تعيين كلمة المرور لإلغاء حماية المستند المحمي . |
| [Separator](../../groupdocs.conversion.options.load/csvloadoptions/separator) { get; set; } | محدد لملف Csv . |
| [SheetIndexes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheetindexes) { get; set; } | قائمة فهارس الأوراق المراد تحويلها. يجب أن تكون الفهارس صفرية |
| [Sheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheets) { get; set; } | اسم الورقة للتحويل |
| [ShowGridLines](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showgridlines) { get; set; } | إظهار خطوط الشبكة عند تحويل ملفات Excel. |
| [ShowHiddenSheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showhiddensheets) { get; set; } | إظهار الأوراق المخفية عند تحويل ملفات Excel. |
| [SkipEmptyRowsAndColumns](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipemptyrowsandcolumns) { get; set; } | يتخطى الصفوف والأعمدة الفارغة عند التحويل. الافتراضي هو صحيح. |

## طُرق

| اسم | وصف |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clone)() | النسخ الحالي للنسخ. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | تحديد ما إذا كان مثيلا الكائن متساويان. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | تحديد ما إذا كان مثيلا الكائن متساويان. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | تعمل كوظيفة تجزئة افتراضية . |

### أنظر أيضا

* class [SpreadsheetLoadOptions](../spreadsheetloadoptions)
* مساحة الاسم [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* المجسم [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
