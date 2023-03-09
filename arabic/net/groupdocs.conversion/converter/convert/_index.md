---
title: Convert
second_title: GroupDocs.Conversion لمرجع .NET API
description: تحويل المستند المصدر. يحفظ المستند المحول بالكامل.
type: docs
weight: 20
url: /ar/net/groupdocs.conversion/converter/convert/
---
## Convert(Func&lt;Stream&gt;, ConvertOptions) {#convert}

تحويل المستند المصدر. يحفظ المستند المحول بالكامل.

```csharp
public void Convert(Func<Stream> document, ConvertOptions convertOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Func`1 | المفوض الذي يحفظ المستند المحول إلى دفق. |
| convertOptions | ConvertOptions | خيارات التحويل الخاصة بنوع الملف الهدف المطلوب. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول السيناريوهات الأساسية لتحويل المستندات: [كيفية تحويل المستند في 3 خطوات](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* حالات استخدام التحويل والإعدادات والتخصيصات المتقدمة: [تحويل المستند مع الإعدادات المتقدمة](https://docs.groupdocs.com/display/conversionnet/Converting)

### أنظر أيضا

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) {#convert_1}

تحويل المستند المصدر. يحفظ المستند المحول بالكامل.

```csharp
public void Convert(Func<Stream> document, Action<Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Func`1 | المفوض الذي يحفظ المستند المحول إلى دفق. |
| documentCompleted | Action`2 | المفوض الذي يتلقى دفق المستند المحول.دفق محتوى الملفاسم الملف |
| convertOptions | ConvertOptions | خيارات التحويل الخاصة بنوع الملف الهدف المطلوب. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول السيناريوهات الأساسية لتحويل المستندات: [كيفية تحويل المستند في 3 خطوات](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* حالات استخدام التحويل والإعدادات والتخصيصات المتقدمة: [تحويل المستند مع الإعدادات المتقدمة](https://docs.groupdocs.com/display/conversionnet/Converting)

### أنظر أيضا

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_3}

تحويل المستند المصدر. يحفظ المستند المحول بالكامل.

```csharp
public void Convert(Func<Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Func`1 | المفوض الذي يحفظ المستند المحول إلى دفق. |
| convertOptionsProvider | Func`3 | تحويل مزود الخيارات. سيتم استدعاؤها لكل تحويل لتوفير خيارات تحويل محددة لنوع المستند المستهدف المطلوب.اسم الملفنوع الملف |

### ملاحظات

**يتعلم أكثر**

* المزيد حول السيناريوهات الأساسية لتحويل المستندات: [كيفية تحويل المستند في 3 خطوات](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* حالات استخدام التحويل والإعدادات والتخصيصات المتقدمة: [تحويل المستند مع الإعدادات المتقدمة](https://docs.groupdocs.com/display/conversionnet/Converting)

### أنظر أيضا

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_2}

تحويل المستند المصدر. يحفظ المستند المحول بالكامل.

```csharp
public void Convert(Func<Stream> document, Action<Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Func`1 | المفوض الذي يحفظ المستند المحول إلى دفق. |
| documentCompleted | Action`2 | المفوض الذي يتلقى دفق المستند المحول.دفق محتوى الملفاسم الملف |
| convertOptionsProvider | Func`3 | تحويل مزود الخيارات. سيتم استدعاؤها لكل تحويل لتوفير خيارات تحويل محددة لنوع المستند المستهدف المطلوب.اسم الملفنوع الملف |

### ملاحظات

**يتعلم أكثر**

* المزيد حول السيناريوهات الأساسية لتحويل المستندات: [كيفية تحويل المستند في 3 خطوات](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* حالات استخدام التحويل والإعدادات والتخصيصات المتقدمة: [تحويل المستند مع الإعدادات المتقدمة](https://docs.groupdocs.com/display/conversionnet/Converting)

### أنظر أيضا

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, ConvertOptions) {#convert_4}

تحويل المستند المصدر. يحفظ المستند المحول بالكامل.

```csharp
public void Convert(Func<FileType, Stream> document, ConvertOptions convertOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Func`2 | المفوض الذي يحفظ المستند المحول إلى دفق.نوع الملف المصدر |
| convertOptions | ConvertOptions | خيارات التحويل الخاصة بنوع الملف الهدف المطلوب. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول السيناريوهات الأساسية لتحويل المستندات: [كيفية تحويل المستند في 3 خطوات](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* حالات استخدام التحويل والإعدادات والتخصيصات المتقدمة: [تحويل المستند مع الإعدادات المتقدمة](https://docs.groupdocs.com/display/conversionnet/Converting)

### أنظر أيضا

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) {#convert_5}

تحويل المستند المصدر. يحفظ المستند المحول بالكامل.

```csharp
public void Convert(Func<FileType, Stream> document, Action<Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Func`2 | المفوض الذي يحفظ المستند المحول إلى دفق.نوع الملف المصدر |
| documentCompleted | Action`2 | المفوض الذي يتلقى دفق المستند المحول.دفق محتوى الملفاسم الملف |
| convertOptions | ConvertOptions | خيارات التحويل الخاصة بنوع الملف الهدف المطلوب. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول السيناريوهات الأساسية لتحويل المستندات: [كيفية تحويل المستند في 3 خطوات](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* حالات استخدام التحويل والإعدادات والتخصيصات المتقدمة: [تحويل المستند مع الإعدادات المتقدمة](https://docs.groupdocs.com/display/conversionnet/Converting)

### أنظر أيضا

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_7}

تحويل المستند المصدر. يحفظ المستند المحول بالكامل.

```csharp
public void Convert(Func<FileType, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Func`2 | المفوض الذي يحفظ المستند المحول إلى دفق.نوع الملف المصدر |
| convertOptionsProvider | Func`3 | تحويل مزود الخيارات. سيتم استدعاؤها لكل تحويل لتوفير خيارات تحويل محددة لنوع المستند المستهدف المطلوب.اسم الملفنوع الملف |

### ملاحظات

**يتعلم أكثر**

* المزيد حول السيناريوهات الأساسية لتحويل المستندات: [كيفية تحويل المستند في 3 خطوات](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* حالات استخدام التحويل والإعدادات والتخصيصات المتقدمة: [تحويل المستند مع الإعدادات المتقدمة](https://docs.groupdocs.com/display/conversionnet/Converting)

### أنظر أيضا

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_6}

تحويل المستند المصدر. يحفظ المستند المحول بالكامل.

```csharp
public void Convert(Func<FileType, Stream> document, Action<Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Func`2 | المفوض الذي يحفظ المستند المحول إلى دفق.نوع الملف المصدر |
| documentCompleted | Action`2 | المفوض الذي يتلقى دفق المستند المحول.دفق محتوى الملفاسم الملف |
| convertOptionsProvider | Func`3 | تحويل مزود الخيارات. سيتم استدعاؤها لكل تحويل لتوفير خيارات تحويل محددة لنوع المستند المستهدف المطلوب.اسم الملفنوع الملف |

### ملاحظات

**يتعلم أكثر**

* المزيد حول السيناريوهات الأساسية لتحويل المستندات: [كيفية تحويل المستند في 3 خطوات](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* حالات استخدام التحويل والإعدادات والتخصيصات المتقدمة: [تحويل المستند مع الإعدادات المتقدمة](https://docs.groupdocs.com/display/conversionnet/Converting)

### أنظر أيضا

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Convert(string, ConvertOptions) {#convert_16}

تحويل المستند المصدر. يحفظ المستند المحول بالكامل.

```csharp
public void Convert(string filePath, ConvertOptions convertOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | مسار الملف إلى المستند المصدر. |
| convertOptions | ConvertOptions | خيارات التحويل الخاصة بنوع الملف الهدف المطلوب. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول السيناريوهات الأساسية لتحويل المستندات: [كيفية تحويل المستند في 3 خطوات](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* حالات استخدام التحويل والإعدادات والتخصيصات المتقدمة: [تحويل المستند مع الإعدادات المتقدمة](https://docs.groupdocs.com/display/conversionnet/Converting)

### أنظر أيضا

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, ConvertOptions) {#convert_8}

تحويل المستند المصدر. يحفظ صفحة الوثيقة المحولة بالصفحة.

```csharp
public void Convert(Func<int, Stream> document, ConvertOptions convertOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Func`2 | المفوض الذي يحفظ المستند المحول إلى دفق.رقم الصفحة |
| convertOptions | ConvertOptions | خيارات التحويل الخاصة بنوع الملف الهدف المطلوب. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول السيناريوهات الأساسية لتحويل المستندات: [كيفية تحويل المستند في 3 خطوات](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* حالات استخدام التحويل والإعدادات والتخصيصات المتقدمة: [تحويل المستند مع الإعدادات المتقدمة](https://docs.groupdocs.com/display/conversionnet/Converting)

### أنظر أيضا

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) {#convert_9}

تحويل المستند المصدر. يحفظ صفحة الوثيقة المحولة بالصفحة.

```csharp
public void Convert(Func<int, Stream> document, Action<int, Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Func`2 | المفوض الذي يحفظ صفحة المستند المحولة إلى تدفق.رقم الصفحة |
| documentCompleted | Action`3 | المفوض الذي يتلقى دفق صفحة المستند المحول.رقم الصفحةدفق محتوى الملفاسم الملف |
| convertOptions | ConvertOptions | خيارات التحويل الخاصة بنوع الملف الهدف المطلوب. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول السيناريوهات الأساسية لتحويل المستندات: [كيفية تحويل المستند في 3 خطوات](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* حالات استخدام التحويل والإعدادات والتخصيصات المتقدمة: [تحويل المستند مع الإعدادات المتقدمة](https://docs.groupdocs.com/display/conversionnet/Converting)

### أنظر أيضا

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_11}

تحويل المستند المصدر. يحفظ صفحة الوثيقة المحولة بالصفحة.

```csharp
public void Convert(Func<int, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Func`2 | المفوض الذي يحفظ المستند المحول إلى دفق.رقم الصفحة |
| convertOptionsProvider | Func`3 | تحويل مزود الخيارات. سيتم استدعاؤها لكل تحويل لتوفير خيارات تحويل محددة لنوع المستند المستهدف المطلوب.اسم الملفنوع الملف |

### ملاحظات

**يتعلم أكثر**

* المزيد حول السيناريوهات الأساسية لتحويل المستندات: [كيفية تحويل المستند في 3 خطوات](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* حالات استخدام التحويل والإعدادات والتخصيصات المتقدمة: [تحويل المستند مع الإعدادات المتقدمة](https://docs.groupdocs.com/display/conversionnet/Converting)

### أنظر أيضا

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_10}

تحويل المستند المصدر. يحفظ صفحة الوثيقة المحولة بالصفحة.

```csharp
public void Convert(Func<int, Stream> document, Action<int, Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Func`2 | المفوض الذي يحفظ صفحة المستند المحولة إلى تدفق.رقم الصفحة |
| documentCompleted | Action`3 | المفوض الذي يتلقى دفق صفحة المستند المحول.رقم الصفحةدفق محتوى الملفاسم الملف |
| convertOptionsProvider | Func`3 | تحويل مزود الخيارات. سيتم استدعاؤها لكل تحويل لتوفير خيارات تحويل محددة لنوع المستند المستهدف المطلوب.اسم الملفنوع الملف |

### ملاحظات

**يتعلم أكثر**

* المزيد حول السيناريوهات الأساسية لتحويل المستندات: [كيفية تحويل المستند في 3 خطوات](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* حالات استخدام التحويل والإعدادات والتخصيصات المتقدمة: [تحويل المستند مع الإعدادات المتقدمة](https://docs.groupdocs.com/display/conversionnet/Converting)

### أنظر أيضا

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, ConvertOptions) {#convert_12}

تحويل المستند المصدر. يحفظ صفحة الوثيقة المحولة بالصفحة.

```csharp
public void Convert(Func<int, FileType, Stream> document, ConvertOptions convertOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Func`3 | المفوض الذي يحفظ المستند المحول إلى دفق.رقم الصفحة |
| convertOptions | ConvertOptions | خيارات التحويل الخاصة بنوع الملف الهدف المطلوب. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول السيناريوهات الأساسية لتحويل المستندات: [كيفية تحويل المستند في 3 خطوات](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* حالات استخدام التحويل والإعدادات والتخصيصات المتقدمة: [تحويل المستند مع الإعدادات المتقدمة](https://docs.groupdocs.com/display/conversionnet/Converting)

### أنظر أيضا

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) {#convert_13}

تحويل المستند المصدر. يحفظ صفحة الوثيقة المحولة بالصفحة.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Action<int, Stream, string> documentCompleted, ConvertOptions convertOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Func`3 | المفوض الذي يحفظ صفحة المستند المحولة إلى تدفق.رقم الصفحةنوع الملف |
| documentCompleted | Action`3 | المفوض الذي يتلقى دفق صفحة المستند المحول.رقم الصفحةدفق محتوى الملفاسم الملف |
| convertOptions | ConvertOptions | خيارات التحويل الخاصة بنوع الملف الهدف المطلوب. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول السيناريوهات الأساسية لتحويل المستندات: [كيفية تحويل المستند في 3 خطوات](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* حالات استخدام التحويل والإعدادات والتخصيصات المتقدمة: [تحويل المستند مع الإعدادات المتقدمة](https://docs.groupdocs.com/display/conversionnet/Converting)

### أنظر أيضا

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_15}

تحويل المستند المصدر. يحفظ صفحة الوثيقة المحولة بالصفحة.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Func`3 | المفوض الذي يحفظ المستند المحول إلى دفق.رقم الصفحةنوع الملف |
| convertOptionsProvider | Func`3 | تحويل مزود الخيارات. سيتم استدعاؤها لكل تحويل لتوفير خيارات تحويل محددة لنوع المستند المستهدف المطلوب.اسم الملفنوع الملف |

### ملاحظات

**يتعلم أكثر**

* المزيد حول السيناريوهات الأساسية لتحويل المستندات: [كيفية تحويل المستند في 3 خطوات](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* حالات استخدام التحويل والإعدادات والتخصيصات المتقدمة: [تحويل المستند مع الإعدادات المتقدمة](https://docs.groupdocs.com/display/conversionnet/Converting)

### أنظر أيضا

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_14}

تحويل المستند المصدر. يحفظ صفحة الوثيقة المحولة بالصفحة.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Action<int, Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Func`3 | المفوض الذي يحفظ صفحة المستند المحولة إلى تدفق.رقم الصفحةنوع الملف |
| documentCompleted | Action`3 | المفوض الذي يتلقى دفق صفحة المستند المحول.رقم الصفحةدفق محتوى الملفاسم الملف |
| convertOptionsProvider | Func`3 | تحويل مزود الخيارات. سيتم استدعاؤها لكل تحويل لتوفير خيارات تحويل محددة لنوع المستند المستهدف المطلوب.اسم الملفنوع الملف |

### ملاحظات

**يتعلم أكثر**

* المزيد حول السيناريوهات الأساسية لتحويل المستندات: [كيفية تحويل المستند في 3 خطوات](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* حالات استخدام التحويل والإعدادات والتخصيصات المتقدمة: [تحويل المستند مع الإعدادات المتقدمة](https://docs.groupdocs.com/display/conversionnet/Converting)

### أنظر أيضا

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
