---
title: Converter
second_title: GroupDocs.Conversion لمرجع .NET API
description: تهيئة مثيل جديد لـConvertergroupdocs.conversion/converter فئة .
type: docs
weight: 10
url: /ar/net/groupdocs.conversion/converter/converter/
---
## Converter(Func&lt;Stream&gt;) {#constructor_1}

تهيئة مثيل جديد لـ[`Converter`](../../converter) فئة .

```csharp
public Converter(Func<Stream> document)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Func`1 | الطريقة التي ترجع الدفق المقروء. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*document* باطل. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول كيفية تحميل وتحويل المستندات المخزنة في FTP أو Amazon S3 Storage أو Windows Azure أو أي وحدة تخزين أخرى تابعة لجهة خارجية: [تحميل المستند من مصادر مختلفة](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* المزيد حول خيارات تحميل المستندات التي تعتمد على نوع الملف: [خيارات التحميل لأنواع المستندات المختلفة](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### أنظر أيضا

* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) {#constructor_2}

تهيئة مثيل جديد لـ[`Converter`](../../converter) فئة .

```csharp
public Converter(Func<Stream> document, Func<ConverterSettings> settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Func`1 | الطريقة التي ترجع الدفق المقروء. |
| settings | Func`1 | إعدادات المحول. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول كيفية تحميل وتحويل المستندات المخزنة في FTP أو Amazon S3 Storage أو Windows Azure أو أي وحدة تخزين أخرى تابعة لجهة خارجية: [تحميل المستند من مصادر مختلفة](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* المزيد حول خيارات تحميل المستندات التي تعتمد على نوع الملف: [خيارات التحميل لأنواع المستندات المختلفة](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### أنظر أيضا

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_3}

تهيئة مثيل جديد لـ[`Converter`](../../converter) فئة .

```csharp
public Converter(Func<Stream> document, Func<LoadOptions> loadOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Func`1 | الطريقة التي ترجع الدفق المقروء. |
| loadOptions | Func`1 | الطرق التي ترجع خيارات تحميل المستند. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول كيفية تحميل وتحويل المستندات المخزنة في FTP أو Amazon S3 Storage أو Windows Azure أو أي وحدة تخزين أخرى تابعة لجهة خارجية: [تحميل المستند من مصادر مختلفة](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* المزيد حول خيارات تحميل المستندات التي تعتمد على نوع الملف: [خيارات التحميل لأنواع المستندات المختلفة](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### أنظر أيضا

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_4}

تهيئة مثيل جديد لـ[`Converter`](../../converter) فئة .

```csharp
public Converter(Func<Stream> document, Func<LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Func`1 | الطريقة التي ترجع الدفق المقروء. |
| loadOptions | Func`1 | الطرق التي ترجع خيارات تحميل المستند. |
| settings | Func`1 | إعدادات المحول. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول كيفية تحميل وتحويل المستندات المخزنة في FTP أو Amazon S3 Storage أو Windows Azure أو أي وحدة تخزين أخرى تابعة لجهة خارجية: [تحميل المستند من مصادر مختلفة](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* المزيد حول خيارات تحميل المستندات التي تعتمد على نوع الملف: [خيارات التحميل لأنواع المستندات المختلفة](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### أنظر أيضا

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;) {#constructor_5}

تهيئة مثيل جديد لـ[`Converter`](../../converter) فئة .

```csharp
public Converter(Func<Stream> document, Func<FileType, LoadOptions> loadOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Func`1 | الطريقة التي ترجع الدفق المقروء. |
| loadOptions | Func`2 | الطرق التي تُرجع خيارات تحميل المستند.نوع الملف المصدر |

### ملاحظات

**يتعلم أكثر**

* المزيد حول كيفية تحميل وتحويل المستندات المخزنة في FTP أو Amazon S3 Storage أو Windows Azure أو أي وحدة تخزين أخرى تابعة لجهة خارجية: [تحميل المستند من مصادر مختلفة](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* المزيد حول خيارات تحميل المستندات التي تعتمد على نوع الملف: [خيارات التحميل لأنواع المستندات المختلفة](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### أنظر أيضا

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_6}

تهيئة مثيل جديد لـ[`Converter`](../../converter) فئة .

```csharp
public Converter(Func<Stream> document, Func<FileType, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Func`1 | الطريقة التي ترجع الدفق المقروء. |
| loadOptions | Func`2 | الطرق التي تُرجع خيارات تحميل المستند.نوع الملف المصدر |
| settings | Func`1 | إعدادات المحول. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول كيفية تحميل وتحويل المستندات المخزنة في FTP أو Amazon S3 Storage أو Windows Azure أو أي وحدة تخزين أخرى تابعة لجهة خارجية: [تحميل المستند من مصادر مختلفة](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* المزيد حول خيارات تحميل المستندات التي تعتمد على نوع الملف: [خيارات التحميل لأنواع المستندات المختلفة](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### أنظر أيضا

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Converter(string) {#constructor_7}

تهيئة مثيل جديد لـ[`Converter`](../../converter) فئة .

```csharp
public Converter(string filePath)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | مسار الملف إلى المستند المصدر. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول كيفية تحميل وتحويل المستندات المخزنة في FTP أو Amazon S3 Storage أو Windows Azure أو أي وحدة تخزين أخرى تابعة لجهة خارجية: [تحميل المستند من مصادر مختلفة](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* المزيد حول خيارات تحميل المستندات التي تعتمد على نوع الملف: [خيارات التحميل لأنواع المستندات المختلفة](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### أنظر أيضا

* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;) {#constructor_8}

تهيئة مثيل جديد لـ[`Converter`](../../converter) فئة .

```csharp
public Converter(string filePath, Func<ConverterSettings> settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | مسار الملف إلى المستند المصدر. |
| settings | Func`1 | إعدادات المحول. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول كيفية تحميل وتحويل المستندات المخزنة في FTP أو Amazon S3 Storage أو Windows Azure أو أي وحدة تخزين أخرى تابعة لجهة خارجية: [تحميل المستند من مصادر مختلفة](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* المزيد حول خيارات تحميل المستندات التي تعتمد على نوع الملف: [خيارات التحميل لأنواع المستندات المختلفة](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### أنظر أيضا

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadOptions&gt;) {#constructor_9}

تهيئة مثيل جديد لـ[`Converter`](../../converter) فئة .

```csharp
public Converter(string filePath, Func<LoadOptions> loadOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | مسار الملف إلى المستند المصدر. |
| loadOptions | Func`1 | الطرق التي ترجع خيارات تحميل المستند. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول كيفية تحميل وتحويل المستندات المخزنة في FTP أو Amazon S3 Storage أو Windows Azure أو أي وحدة تخزين أخرى تابعة لجهة خارجية: [تحميل المستند من مصادر مختلفة](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* المزيد حول خيارات تحميل المستندات التي تعتمد على نوع الملف: [خيارات التحميل لأنواع المستندات المختلفة](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### أنظر أيضا

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_10}

تهيئة مثيل جديد لـ[`Converter`](../../converter) فئة .

```csharp
public Converter(string filePath, Func<LoadOptions> loadOptions, Func<ConverterSettings> settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | مسار الملف إلى المستند المصدر. |
| loadOptions | Func`1 | الطرق التي ترجع خيارات تحميل المستند. |
| settings | Func`1 | إعدادات المحول. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول كيفية تحميل وتحويل المستندات المخزنة في FTP أو Amazon S3 Storage أو Windows Azure أو أي وحدة تخزين أخرى تابعة لجهة خارجية: [تحميل المستند من مصادر مختلفة](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* المزيد حول خيارات تحميل المستندات التي تعتمد على نوع الملف: [خيارات التحميل لأنواع المستندات المختلفة](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### أنظر أيضا

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;FileType, LoadOptions&gt;) {#constructor_11}

تهيئة مثيل جديد لـ[`Converter`](../../converter) فئة .

```csharp
public Converter(string filePath, Func<FileType, LoadOptions> loadOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | مسار الملف إلى المستند المصدر. |
| loadOptions | Func`2 | الطرق التي تُرجع خيارات تحميل المستند.نوع الملف المصدر |

### ملاحظات

**يتعلم أكثر**

* المزيد حول كيفية تحميل وتحويل المستندات المخزنة في FTP أو Amazon S3 Storage أو Windows Azure أو أي وحدة تخزين أخرى تابعة لجهة خارجية: [تحميل المستند من مصادر مختلفة](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* المزيد حول خيارات تحميل المستندات التي تعتمد على نوع الملف: [خيارات التحميل لأنواع المستندات المختلفة](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### أنظر أيضا

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_12}

تهيئة مثيل جديد لـ[`Converter`](../../converter) فئة .

```csharp
public Converter(string filePath, Func<FileType, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | مسار الملف إلى المستند المصدر. |
| loadOptions | Func`2 | الطرق التي تُرجع خيارات تحميل المستند.نوع الملف المصدر |
| settings | Func`1 | إعدادات المحول. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول كيفية تحميل وتحويل المستندات المخزنة في FTP أو Amazon S3 Storage أو Windows Azure أو أي وحدة تخزين أخرى تابعة لجهة خارجية: [تحميل المستند من مصادر مختلفة](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* المزيد حول خيارات تحميل المستندات التي تعتمد على نوع الملف: [خيارات التحميل لأنواع المستندات المختلفة](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### أنظر أيضا

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Converter() {#constructor}

تهيئة مثيل جديد لـ[`Converter`](../../converter) فئة لإعداد التحويل بطلاقة.

```csharp
public Converter()
```

### ملاحظات

نموذج استخدام التحويل بطلاقة:

```csharp
var converter = new Converter();
```

```csharp
converter
    .Load("")
    .ConvertTo("")
    .Convert();
```

```csharp
converter
    .WithSettings(() => new ConverterSettings())
    .Load("").WithOptions(new PdfLoadOptions())
    .ConvertTo("").WithOptions(new PdfConvertOptions())
    .OnConversionCompleted(convertedDocumentStream => { })
    .Convert();
```

```csharp
converter
    .Load("").WithOptions(new PdfLoadOptions())
    .ConvertByPageTo((number => new FileStream("", FileMode.Create))).WithOptions(new PdfConvertOptions())
    .OnConversionCompleted((number, stream) => {})
    .Convert();
```

```csharp
converter.Load("").GetPossibleConversions();
converter.Load("").GetDocumentInfo();
converter.Load("").WithOptions(new PdfLoadOptions()).GetPossibleConversions();
converter.Load("").WithOptions(new PdfLoadOptions()).GetDocumentInfo();
```

### أنظر أيضا

* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
