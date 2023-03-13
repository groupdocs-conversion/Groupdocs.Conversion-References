---
title: Converter
second_title: GroupDocs.Conversion لمرجع .NET API
description: يمثل الفئة الرئيسية التي تتحكم في عملية تحويل المستند.
type: docs
weight: 730
url: /ar/net/groupdocs.conversion/converter/
---
## Converter class

يمثل الفئة الرئيسية التي تتحكم في عملية تحويل المستند.

```csharp
public sealed class Converter : IConversionSettingsOrConversionFrom, IDisposable
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Converter](converter#constructor)() | تهيئة مثيل جديد لـ[`Converter`](../converter) فئة لإعداد التحويل بطلاقة. |
| [Converter](converter#constructor_1)(Func&lt;Stream&gt;) | تهيئة مثيل جديد لـ[`Converter`](../converter) فئة . |
| [Converter](converter#constructor_7)(string) | تهيئة مثيل جديد لـ[`Converter`](../converter) فئة . |
| [Converter](converter#constructor_2)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) | تهيئة مثيل جديد لـ[`Converter`](../converter) فئة . |
| [Converter](converter#constructor_5)(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;) | تهيئة مثيل جديد لـ[`Converter`](../converter) فئة . |
| [Converter](converter#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) | تهيئة مثيل جديد لـ[`Converter`](../converter) فئة . |
| [Converter](converter#constructor_8)(string, Func&lt;ConverterSettings&gt;) | تهيئة مثيل جديد لـ[`Converter`](../converter) فئة . |
| [Converter](converter#constructor_11)(string, Func&lt;FileType, LoadOptions&gt;) | تهيئة مثيل جديد لـ[`Converter`](../converter) فئة . |
| [Converter](converter#constructor_9)(string, Func&lt;LoadOptions&gt;) | تهيئة مثيل جديد لـ[`Converter`](../converter) فئة . |
| [Converter](converter#constructor_6)(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | تهيئة مثيل جديد لـ[`Converter`](../converter) فئة . |
| [Converter](converter#constructor_4)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | تهيئة مثيل جديد لـ[`Converter`](../converter) فئة . |
| [Converter](converter#constructor_12)(string, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | تهيئة مثيل جديد لـ[`Converter`](../converter) فئة . |
| [Converter](converter#constructor_10)(string, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | تهيئة مثيل جديد لـ[`Converter`](../converter) فئة . |

## طُرق

| اسم | وصف |
| --- | --- |
| [Convert](../../groupdocs.conversion/converter/convert#convert_4)(Func&lt;FileType, Stream&gt;, ConvertOptions) | تحويل المستند المصدر. يحفظ المستند المحول بالكامل. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_7)(Func&lt;FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | تحويل المستند المصدر. يحفظ المستند المحول بالكامل. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_12)(Func&lt;int, FileType, Stream&gt;, ConvertOptions) | تحويل المستند المصدر. يحفظ صفحة الوثيقة المحولة بالصفحة. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_15)(Func&lt;int, FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | تحويل المستند المصدر. يحفظ صفحة الوثيقة المحولة بالصفحة. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_8)(Func&lt;int, Stream&gt;, ConvertOptions) | تحويل المستند المصدر. يحفظ صفحة الوثيقة المحولة بالصفحة. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_11)(Func&lt;int, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | تحويل المستند المصدر. يحفظ صفحة الوثيقة المحولة بالصفحة. |
| [Convert](../../groupdocs.conversion/converter/convert#convert)(Func&lt;Stream&gt;, ConvertOptions) | تحويل المستند المصدر. يحفظ المستند المحول بالكامل. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_3)(Func&lt;Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | تحويل المستند المصدر. يحفظ المستند المحول بالكامل. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_16)(string, ConvertOptions) | تحويل المستند المصدر. يحفظ المستند المحول بالكامل. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_5)(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) | تحويل المستند المصدر. يحفظ المستند المحول بالكامل. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_6)(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | تحويل المستند المصدر. يحفظ المستند المحول بالكامل. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_13)(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) | تحويل المستند المصدر. يحفظ صفحة الوثيقة المحولة بالصفحة. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_14)(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | تحويل المستند المصدر. يحفظ صفحة الوثيقة المحولة بالصفحة. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_9)(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) | تحويل المستند المصدر. يحفظ صفحة الوثيقة المحولة بالصفحة. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_10)(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | تحويل المستند المصدر. يحفظ صفحة الوثيقة المحولة بالصفحة. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_1)(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) | تحويل المستند المصدر. يحفظ المستند المحول بالكامل. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_2)(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | تحويل المستند المصدر. يحفظ المستند المحول بالكامل. |
| [Dispose](../../groupdocs.conversion/converter/dispose)() | إصدارات الموارد . |
| [GetDocumentInfo](../../groupdocs.conversion/converter/getdocumentinfo)() | الحصول على معلومات المستند المصدر - عدد الصفحات وخصائص المستند الأخرى الخاصة بنوع الملف. |
| [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)() | يحصل على تحويلات محتملة للوثيقة المصدر. |
| [Load](../../groupdocs.conversion/converter/load#load_1)(Func&lt;Stream&gt;) | تكوين تدفق المستند المصدر |
| [Load](../../groupdocs.conversion/converter/load#load)(Func&lt;Stream[]&gt;) | تكوين مجموعة من تدفقات المستندات المصدر |
| [Load](../../groupdocs.conversion/converter/load#load_2)(string) | تكوين المستند المصدر للتحويل |
| [Load](../../groupdocs.conversion/converter/load#load_3)(string[]) | تكوين مجموعة من المستندات المصدر |
| [WithSettings](../../groupdocs.conversion/converter/withsettings)(Func&lt;ConverterSettings&gt;) | تكوين إعدادات التحويل |
| static [GetAllPossibleConversions](../../groupdocs.conversion/converter/getallpossibleconversions)() | يحصل على جميع التحويلات المدعومة |
| static [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)(string) | الحصول على التحويلات المدعومة لملحق المستند المقدم |

### أنظر أيضا

* interface [IConversionSettingsOrConversionFrom](../../groupdocs.conversion.fluent/iconversionsettingsorconversionfrom)
* مساحة الاسم [GroupDocs.Conversion](../../groupdocs.conversion)
* المجسم [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
