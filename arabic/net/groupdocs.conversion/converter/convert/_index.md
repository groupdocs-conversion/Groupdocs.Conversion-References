---
title: "تحويل"
second_title: "GroupDocs.Conversion لـ .NET مرجع API"
description: "يحوِّل مستند المصدر. يحفظ المستند المُحوَّل بالكامل."
type: docs
weight: 20
url: /ar/net/groupdocs.conversion/converter/convert/
---
## Convert(Func&lt;SaveContext, Stream&gt;, ConvertOptions, CancellationToken) {#convert_4}

يحوِّل مستند المصدر. يحفظ المستند المُحوَّل بالكامل.

```csharp
public void Convert(Func<SaveContext, Stream> targetStreamProvider, ConvertOptions convertOptions, 
    CancellationToken cancellationToken = default)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| targetStreamProvider | Func`2 | المندوب الذي يحفظ المستند المحول إلى تدفق. |
| convertOptions | ConvertOptions | خيارات التحويل الخاصة بنوع الملف الهدف المطلوب. |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### ملاحظات

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### انظر أيضًا

* class [SaveContext](../../savecontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(ConvertOptions, Action&lt;ConvertedContext&gt;, CancellationToken) {#convert}

يحوِّل مستند المصدر. يحفظ المستند المُحوَّل بالكامل.

```csharp
public void Convert(ConvertOptions convertOptions, Action<ConvertedContext> documentCompleted, 
    CancellationToken cancellationToken = default)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| convertOptions | ConvertOptions | خيارات التحويل الخاصة بنوع الملف الهدف المطلوب. |
| documentCompleted | Action`1 | المندوب الذي يستقبل تدفق المستند المحول. التوقيع: `Action<ConvertedContext>`. المعامل [`ConvertedContext`](../../convertedcontext) يحتوي على تدفق المستند المحول والبيانات الوصفية. |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### ملاحظات

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### انظر أيضًا

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedContext](../../convertedcontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SaveContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) {#convert_5}

يحوِّل مستند المصدر. يحفظ المستند المُحوَّل بالكامل.

```csharp
public void Convert(Func<SaveContext, Stream> targetStreamProvider, 
    Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    CancellationToken cancellationToken = default)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| targetStreamProvider | Func`2 | المندوب الذي يوفر التدفق لحفظ المستند المحول. التوقيع: `Func<SaveContext, Stream>`. المعامل [`SaveContext`](../../savecontext) يحتوي على معلومات حول عملية الحفظ. |
| convertOptionsProvider | Func`2 | المندوب الذي يوفر خيارات التحويل. التوقيع: `Func<ConvertContext, ConvertOptions>`. المعامل [`ConvertContext`](../../convertcontext) يحتوي على معلومات حول عملية التحويل. |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### ملاحظات

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### انظر أيضًا

* class [SaveContext](../../savecontext)
* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedContext&gt;, CancellationToken) {#convert_2}

يحوِّل مستند المصدر. يحفظ المستند المُحوَّل بالكامل.

```csharp
public void Convert(Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    Action<ConvertedContext> documentCompleted, CancellationToken cancellationToken = default)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | المندوب الذي يوفر خيارات التحويل. التوقيع: `Func<ConvertContext, ConvertOptions>`. المعامل [`ConvertContext`](../../convertcontext) يحتوي على معلومات حول عملية التحويل. |
| documentCompleted | Action`1 | المندوب الذي يستقبل تدفق المستند المحول. التوقيع: `Action<ConvertedContext>`. المعامل [`ConvertedContext`](../../convertedcontext) يحتوي على تدفق المستند المحول والبيانات الوصفية. |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### ملاحظات

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### انظر أيضًا

* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedContext](../../convertedcontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(string, ConvertOptions, CancellationToken) {#convert_8}

يحوِّل مستند المصدر. يحفظ المستند المُحوَّل بالكامل.

```csharp
public void Convert(string filePath, ConvertOptions convertOptions, 
    CancellationToken cancellationToken = default)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف للمستند المصدر. |
| convertOptions | ConvertOptions | خيارات التحويل الخاصة بنوع الملف الهدف المطلوب. |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### ملاحظات

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### انظر أيضًا

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SavePageContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) {#convert_7}

يحوِّل مستند المصدر. يحفظ المستند المُحوَّل صفحةً بصفحة.

```csharp
public void Convert(Func<SavePageContext, Stream> targetStreamProvider, 
    Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    CancellationToken cancellationToken = default)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| targetStreamProvider | Func`2 | المندوب الذي يوفر تدفقًا لحفظ كل صفحة محولة. التوقيع: `Func<SavePageContext, Stream>`. المعامل [`SavePageContext`](../../savepagecontext) يحتوي على رقم الصفحة ومعلومات المستند. |
| convertOptionsProvider | Func`2 | المندوب الذي يوفر خيارات التحويل. التوقيع: `Func<ConvertContext, ConvertOptions>`. المعامل [`ConvertContext`](../../convertcontext) يحتوي على معلومات حول عملية التحويل. |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### ملاحظات

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### انظر أيضًا

* class [SavePageContext](../../savepagecontext)
* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SavePageContext, Stream&gt;, ConvertOptions, CancellationToken) {#convert_6}

يحوِّل مستند المصدر. يحفظ المستند المُحوَّل صفحةً بصفحة.

```csharp
public void Convert(Func<SavePageContext, Stream> targetStreamProvider, 
    ConvertOptions convertOptions, CancellationToken cancellationToken = default)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| targetStreamProvider | Func`2 | المندوب الذي يوفر تدفقًا لحفظ كل صفحة محولة. التوقيع: `Func<SavePageContext, Stream>`. المعامل [`SavePageContext`](../../savepagecontext) يحتوي على رقم الصفحة ومعلومات المستند. |
| convertOptions | ConvertOptions | خيارات التحويل الخاصة بنوع الملف الهدف المطلوب. |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### ملاحظات

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### انظر أيضًا

* class [SavePageContext](../../savepagecontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(ConvertOptions, Action&lt;ConvertedPageContext&gt;, CancellationToken) {#convert_1}

يحوِّل مستند المصدر. يحفظ المستند المُحوَّل صفحةً بصفحة.

```csharp
public void Convert(ConvertOptions convertOptions, Action<ConvertedPageContext> documentCompleted, 
    CancellationToken cancellationToken = default)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| documentCompleted | ConvertOptions | المندوب الذي يستقبل كل صفحة محولة. التوقيع: `Action<ConvertedPageContext>`. المعامل [`ConvertedPageContext`](../../convertedpagecontext) يحتوي على رقم الصفحة، التدفق، اسم ملف المصدر، ونوع الملف الهدف. |
| convertOptions | Action`1 | خيارات التحويل الخاصة بنوع الملف الهدف المطلوب. |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### ملاحظات

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### انظر أيضًا

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedPageContext](../../convertedpagecontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedPageContext&gt;, CancellationToken) {#convert_3}

يحوِّل مستند المصدر. يحفظ المستند المُحوَّل صفحةً بصفحة.

```csharp
public void Convert(Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    Action<ConvertedPageContext> documentCompleted, CancellationToken cancellationToken = default)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | المندوب الذي يوفر خيارات التحويل. التوقيع: `Func<ConvertContext, ConvertOptions>`. المعامل [`ConvertContext`](../../convertcontext) يحتوي على معلومات حول عملية التحويل. |
| documentCompleted | Action`1 | المندوب الذي يستقبل كل صفحة محولة. التوقيع: `Action<ConvertedPageContext>`. المعامل [`ConvertedPageContext`](../../convertedpagecontext) يحتوي على رقم الصفحة، التدفق، اسم ملف المصدر، ونوع الملف الهدف. |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### ملاحظات

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### انظر أيضًا

* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedPageContext](../../convertedpagecontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
