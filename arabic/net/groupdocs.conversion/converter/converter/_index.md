---
title: "Converter"
second_title: "GroupDocs.Conversion لـ .NET مرجع API"
description: "ينشئ مثيلًا جديدًا من فئة Convertergroupdocs.conversion/converter."
type: docs
weight: 10
url: /ar/net/groupdocs.conversion/converter/converter/
---
## Converter(Func&lt;Stream&gt;) {#constructor}

ينشئ مثيلًا جديدًا من فئة [`Converter`](../../converter).

```csharp
public Converter(Func<Stream> sourceStreamProvider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | الطريقة التي تُعيد تدفقًا قابلًا للقراءة. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يُرمى عندما يكون *sourceStreamProvider* فارغًا. |

### ملاحظات

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### انظر أيضًا

* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) {#constructor_1}

ينشئ مثيلًا جديدًا من فئة [`Converter`](../../converter).

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<ConverterSettings> settings)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | الطريقة التي تُعيد تدفقًا قابلًا للقراءة. |
| settings | Func`1 | إعدادات المحول. |

### ملاحظات

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### انظر أيضًا

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_3}

ينشئ مثيلًا جديدًا من فئة [`Converter`](../../converter).

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | الطريقة التي تُعيد تدفقًا قابلًا للقراءة. |
| loadOptions | Func`2 | المندوب الذي يوفر خيارات التحميل للمستند. التوقيع: `Func<LoadContext, LoadOptions>`. المعامل [`LoadContext`](../../loadcontext) يحتوي على معلومات حول المستند الذي يتم تحميله. |
| settings | Func`1 | إعدادات المحول. |

### ملاحظات

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### انظر أيضًا

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_4}

يُنشئ مثيلاً جديدًا لفئة [`Converter`](../../converter) مع أحداث تحويل صريحة.

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | الطريقة التي تُعيد تدفقًا قابلًا للقراءة. |
| loadOptions | Func`2 | المندوب الذي يوفر خيارات التحميل للمستند. |
| settings | Func`1 | إعدادات المحول. |
| events | Func`1 | المندوب الذي يوفر [`ConversionEvents`](../../conversionevents) المجمعة المسجلة طوال عمر المحول. |

### انظر أيضًا

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_2}

يُنشئ مثيلاً جديدًا لفئة [`Converter`](../../converter) مع أحداث تحويل صريحة.

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<ConverterSettings> settings, 
    Func<ConversionEvents> events)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | الطريقة التي تُعيد تدفقًا قابلًا للقراءة. |
| settings | Func`1 | إعدادات المحول. |
| events | Func`1 | المندوب الذي يوفر [`ConversionEvents`](../../conversionevents) المجمعة المسجلة طوال عمر المحول. |

### انظر أيضًا

* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string) {#constructor_5}

ينشئ مثيلًا جديدًا من فئة [`Converter`](../../converter).

```csharp
public Converter(string filePath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف للمستند المصدر. |

### ملاحظات

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### انظر أيضًا

* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;) {#constructor_6}

ينشئ مثيلًا جديدًا من فئة [`Converter`](../../converter).

```csharp
public Converter(string filePath, Func<ConverterSettings> settings)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف للمستند المصدر. |
| settings | Func`1 | إعدادات المحول. |

### ملاحظات

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### انظر أيضًا

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_8}

ينشئ مثيلًا جديدًا من فئة [`Converter`](../../converter).

```csharp
public Converter(string filePath, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف للمستند المصدر. |
| loadOptions | Func`2 | المندوب الذي يوفر خيارات التحميل للمستند. التوقيع: `Func<LoadContext, LoadOptions>`. المعامل [`LoadContext`](../../loadcontext) يحتوي على معلومات حول المستند الذي يتم تحميله. |
| settings | Func`1 | إعدادات المحول. |

### ملاحظات

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### انظر أيضًا

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_9}

يُنشئ مثيلاً جديدًا لفئة [`Converter`](../../converter) مع أحداث تحويل صريحة.

```csharp
public Converter(string filePath, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف للمستند المصدر. |
| loadOptions | Func`2 | المندوب الذي يوفر خيارات التحميل للمستند. |
| settings | Func`1 | إعدادات المحول. |
| events | Func`1 | المندوب الذي يوفر [`ConversionEvents`](../../conversionevents) المجمعة المسجلة طوال عمر المحول. |

### انظر أيضًا

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_7}

يُنشئ مثيلاً جديدًا لفئة [`Converter`](../../converter) مع أحداث تحويل صريحة.

```csharp
public Converter(string filePath, Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف للمستند المصدر. |
| settings | Func`1 | إعدادات المحول. |
| events | Func`1 | المندوب الذي يوفر [`ConversionEvents`](../../conversionevents) المجمعة المسجلة طوال عمر المحول. |

### انظر أيضًا

* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
