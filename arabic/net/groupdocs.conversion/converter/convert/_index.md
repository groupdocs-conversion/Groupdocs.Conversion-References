---
title: Convert
second_title: GroupDocs.Conversion لمرجع .NET API
description: تحويل المستند المصدر. يحفظ المستند المحول بالكامل.
type: docs
weight: 20
url: /ar/net/groupdocs.conversion/converter/convert/
---
## Convert(SaveDocumentStream, ConvertOptions) {#convert_3}

تحويل المستند المصدر. يحفظ المستند المحول بالكامل.

```csharp
public void Convert(SaveDocumentStream document, ConvertOptions convertOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | SaveDocumentStream | المفوض الذي يحفظ المستند المحول إلى دفق. |
| convertOptions | ConvertOptions | خيارات التحويل الخاصة بنوع الملف الهدف المطلوب. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول السيناريوهات الأساسية لتحويل المستندات: [كيفية تحويل المستند في 3 خطوات](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* حالات استخدام التحويل والإعدادات والتخصيصات المتقدمة: [تحويل المستند مع الإعدادات المتقدمة](https://docs.groupdocs.com/display/conversionnet/Converting)

### أنظر أيضا

* delegate [SaveDocumentStream](../../../groupdocs.conversion.contracts/savedocumentstream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStream, ConvertedDocumentStream, ConvertOptions) {#convert_1}

تحويل المستند المصدر. يحفظ المستند المحول بالكامل.

```csharp
public void Convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, 
    ConvertOptions convertOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | SaveDocumentStream | المفوض الذي يحفظ المستند المحول إلى دفق. |
| documentCompleted | ConvertedDocumentStream | المفوض الذي يتلقى دفق المستند المحول. |
| convertOptions | ConvertOptions | خيارات التحويل الخاصة بنوع الملف الهدف المطلوب. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول السيناريوهات الأساسية لتحويل المستندات: [كيفية تحويل المستند في 3 خطوات](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* حالات استخدام التحويل والإعدادات والتخصيصات المتقدمة: [تحويل المستند مع الإعدادات المتقدمة](https://docs.groupdocs.com/display/conversionnet/Converting)

### أنظر أيضا

* delegate [SaveDocumentStream](../../../groupdocs.conversion.contracts/savedocumentstream)
* delegate [ConvertedDocumentStream](../../../groupdocs.conversion.contracts/converteddocumentstream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStream, ConvertOptionsProvider) {#convert_2}

تحويل المستند المصدر. يحفظ المستند المحول بالكامل.

```csharp
public void Convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | SaveDocumentStream | المفوض الذي يحفظ المستند المحول إلى دفق. |
| convertOptionsProvider | ConvertOptionsProvider | تحويل مزود الخيارات. سيتم استدعاؤها لكل تحويل لتوفير خيارات تحويل محددة لنوع المستند المستهدف المطلوب. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول السيناريوهات الأساسية لتحويل المستندات: [كيفية تحويل المستند في 3 خطوات](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* حالات استخدام التحويل والإعدادات والتخصيصات المتقدمة: [تحويل المستند مع الإعدادات المتقدمة](https://docs.groupdocs.com/display/conversionnet/Converting)

### أنظر أيضا

* delegate [SaveDocumentStream](../../../groupdocs.conversion.contracts/savedocumentstream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStream, ConvertedDocumentStream, ConvertOptionsProvider) {#convert}

تحويل المستند المصدر. يحفظ المستند المحول بالكامل.

```csharp
public void Convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, 
    ConvertOptionsProvider convertOptionsProvider)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | SaveDocumentStream | المفوض الذي يحفظ المستند المحول إلى دفق. |
| documentCompleted | ConvertedDocumentStream | المفوض الذي يتلقى دفق المستند المحول. |
| convertOptionsProvider | ConvertOptionsProvider | تحويل مزود الخيارات. سيتم استدعاؤها لكل تحويل لتوفير خيارات تحويل محددة لنوع المستند المستهدف المطلوب. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول السيناريوهات الأساسية لتحويل المستندات: [كيفية تحويل المستند في 3 خطوات](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* حالات استخدام التحويل والإعدادات والتخصيصات المتقدمة: [تحويل المستند مع الإعدادات المتقدمة](https://docs.groupdocs.com/display/conversionnet/Converting)

### أنظر أيضا

* delegate [SaveDocumentStream](../../../groupdocs.conversion.contracts/savedocumentstream)
* delegate [ConvertedDocumentStream](../../../groupdocs.conversion.contracts/converteddocumentstream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStreamForFileType, ConvertOptions) {#convert_7}

تحويل المستند المصدر. يحفظ المستند المحول بالكامل.

```csharp
public void Convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | SaveDocumentStreamForFileType | المفوض الذي يحفظ المستند المحول إلى دفق. |
| convertOptions | ConvertOptions | خيارات التحويل الخاصة بنوع الملف الهدف المطلوب. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول السيناريوهات الأساسية لتحويل المستندات: [كيفية تحويل المستند في 3 خطوات](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* حالات استخدام التحويل والإعدادات والتخصيصات المتقدمة: [تحويل المستند مع الإعدادات المتقدمة](https://docs.groupdocs.com/display/conversionnet/Converting)

### أنظر أيضا

* delegate [SaveDocumentStreamForFileType](../../../groupdocs.conversion.contracts/savedocumentstreamforfiletype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStreamForFileType, ConvertedDocumentStream, ConvertOptions) {#convert_5}

تحويل المستند المصدر. يحفظ المستند المحول بالكامل.

```csharp
public void Convert(SaveDocumentStreamForFileType document, 
    ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | SaveDocumentStreamForFileType | المفوض الذي يحفظ المستند المحول إلى دفق. |
| documentCompleted | ConvertedDocumentStream | المفوض الذي يتلقى دفق المستند المحول. |
| convertOptions | ConvertOptions | خيارات التحويل الخاصة بنوع الملف الهدف المطلوب. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول السيناريوهات الأساسية لتحويل المستندات: [كيفية تحويل المستند في 3 خطوات](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* حالات استخدام التحويل والإعدادات والتخصيصات المتقدمة: [تحويل المستند مع الإعدادات المتقدمة](https://docs.groupdocs.com/display/conversionnet/Converting)

### أنظر أيضا

* delegate [SaveDocumentStreamForFileType](../../../groupdocs.conversion.contracts/savedocumentstreamforfiletype)
* delegate [ConvertedDocumentStream](../../../groupdocs.conversion.contracts/converteddocumentstream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStreamForFileType, ConvertOptionsProvider) {#convert_6}

تحويل المستند المصدر. يحفظ المستند المحول بالكامل.

```csharp
public void Convert(SaveDocumentStreamForFileType document, 
    ConvertOptionsProvider convertOptionsProvider)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | SaveDocumentStreamForFileType | المفوض الذي يحفظ المستند المحول إلى دفق. |
| convertOptionsProvider | ConvertOptionsProvider | تحويل مزود الخيارات. سيتم استدعاؤها لكل تحويل لتوفير خيارات تحويل محددة لنوع المستند المستهدف المطلوب. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول السيناريوهات الأساسية لتحويل المستندات: [كيفية تحويل المستند في 3 خطوات](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* حالات استخدام التحويل والإعدادات والتخصيصات المتقدمة: [تحويل المستند مع الإعدادات المتقدمة](https://docs.groupdocs.com/display/conversionnet/Converting)

### أنظر أيضا

* delegate [SaveDocumentStreamForFileType](../../../groupdocs.conversion.contracts/savedocumentstreamforfiletype)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStreamForFileType, ConvertedDocumentStream, ConvertOptionsProvider) {#convert_4}

تحويل المستند المصدر. يحفظ المستند المحول بالكامل.

```csharp
public void Convert(SaveDocumentStreamForFileType document, 
    ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | SaveDocumentStreamForFileType | المفوض الذي يحفظ المستند المحول إلى دفق. |
| documentCompleted | ConvertedDocumentStream | المفوض الذي يتلقى دفق المستند المحول. |
| convertOptionsProvider | ConvertOptionsProvider | تحويل مزود الخيارات. سيتم استدعاؤها لكل تحويل لتوفير خيارات تحويل محددة لنوع المستند المستهدف المطلوب. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول السيناريوهات الأساسية لتحويل المستندات: [كيفية تحويل المستند في 3 خطوات](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* حالات استخدام التحويل والإعدادات والتخصيصات المتقدمة: [تحويل المستند مع الإعدادات المتقدمة](https://docs.groupdocs.com/display/conversionnet/Converting)

### أنظر أيضا

* delegate [SaveDocumentStreamForFileType](../../../groupdocs.conversion.contracts/savedocumentstreamforfiletype)
* delegate [ConvertedDocumentStream](../../../groupdocs.conversion.contracts/converteddocumentstream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
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

## Convert(SavePageStream, ConvertOptions) {#convert_11}

تحويل المستند المصدر. يحفظ صفحة الوثيقة المحولة بالصفحة.

```csharp
public void Convert(SavePageStream document, ConvertOptions convertOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | SavePageStream | المفوض الذي يحفظ المستند المحول إلى دفق. |
| convertOptions | ConvertOptions | خيارات التحويل الخاصة بنوع الملف الهدف المطلوب. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول السيناريوهات الأساسية لتحويل المستندات: [كيفية تحويل المستند في 3 خطوات](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* حالات استخدام التحويل والإعدادات والتخصيصات المتقدمة: [تحويل المستند مع الإعدادات المتقدمة](https://docs.groupdocs.com/display/conversionnet/Converting)

### أنظر أيضا

* delegate [SavePageStream](../../../groupdocs.conversion.contracts/savepagestream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStream, ConvertedPageStream, ConvertOptions) {#convert_9}

تحويل المستند المصدر. يحفظ صفحة الوثيقة المحولة بالصفحة.

```csharp
public void Convert(SavePageStream document, ConvertedPageStream documentCompleted, 
    ConvertOptions convertOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | SavePageStream | المفوض الذي يحفظ صفحة المستند المحولة إلى دفق. |
| documentCompleted | ConvertedPageStream | المفوض الذي يتلقى تدفق صفحة المستند المحول. |
| convertOptions | ConvertOptions | خيارات التحويل الخاصة بنوع الملف الهدف المطلوب. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول السيناريوهات الأساسية لتحويل المستندات: [كيفية تحويل المستند في 3 خطوات](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* حالات استخدام التحويل والإعدادات والتخصيصات المتقدمة: [تحويل المستند مع الإعدادات المتقدمة](https://docs.groupdocs.com/display/conversionnet/Converting)

### أنظر أيضا

* delegate [SavePageStream](../../../groupdocs.conversion.contracts/savepagestream)
* delegate [ConvertedPageStream](../../../groupdocs.conversion.contracts/convertedpagestream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStream, ConvertOptionsProvider) {#convert_10}

تحويل المستند المصدر. يحفظ صفحة الوثيقة المحولة بالصفحة.

```csharp
public void Convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | SavePageStream | المفوض الذي يحفظ المستند المحول إلى دفق. |
| convertOptionsProvider | ConvertOptionsProvider | تحويل مزود الخيارات. سيتم استدعاؤها لكل تحويل لتوفير خيارات تحويل محددة لنوع المستند المستهدف المطلوب. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول السيناريوهات الأساسية لتحويل المستندات: [كيفية تحويل المستند في 3 خطوات](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* حالات استخدام التحويل والإعدادات والتخصيصات المتقدمة: [تحويل المستند مع الإعدادات المتقدمة](https://docs.groupdocs.com/display/conversionnet/Converting)

### أنظر أيضا

* delegate [SavePageStream](../../../groupdocs.conversion.contracts/savepagestream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStream, ConvertedPageStream, ConvertOptionsProvider) {#convert_8}

تحويل المستند المصدر. يحفظ صفحة الوثيقة المحولة بالصفحة.

```csharp
public void Convert(SavePageStream document, ConvertedPageStream documentCompleted, 
    ConvertOptionsProvider convertOptionsProvider)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | SavePageStream | المفوض الذي يحفظ صفحة المستند المحولة إلى دفق. |
| documentCompleted | ConvertedPageStream | المفوض الذي يتلقى تدفق صفحة المستند المحول. |
| convertOptionsProvider | ConvertOptionsProvider | تحويل مزود الخيارات. سيتم استدعاؤها لكل تحويل لتوفير خيارات تحويل محددة لنوع المستند المستهدف المطلوب. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول السيناريوهات الأساسية لتحويل المستندات: [كيفية تحويل المستند في 3 خطوات](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* حالات استخدام التحويل والإعدادات والتخصيصات المتقدمة: [تحويل المستند مع الإعدادات المتقدمة](https://docs.groupdocs.com/display/conversionnet/Converting)

### أنظر أيضا

* delegate [SavePageStream](../../../groupdocs.conversion.contracts/savepagestream)
* delegate [ConvertedPageStream](../../../groupdocs.conversion.contracts/convertedpagestream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStreamForFileType, ConvertOptions) {#convert_15}

تحويل المستند المصدر. يحفظ صفحة الوثيقة المحولة بالصفحة.

```csharp
public void Convert(SavePageStreamForFileType document, ConvertOptions convertOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | SavePageStreamForFileType | المفوض الذي يحفظ المستند المحول إلى دفق. |
| convertOptions | ConvertOptions | خيارات التحويل الخاصة بنوع الملف الهدف المطلوب. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول السيناريوهات الأساسية لتحويل المستندات: [كيفية تحويل المستند في 3 خطوات](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* حالات استخدام التحويل والإعدادات والتخصيصات المتقدمة: [تحويل المستند مع الإعدادات المتقدمة](https://docs.groupdocs.com/display/conversionnet/Converting)

### أنظر أيضا

* delegate [SavePageStreamForFileType](../../../groupdocs.conversion.contracts/savepagestreamforfiletype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStreamForFileType, ConvertedPageStream, ConvertOptions) {#convert_13}

تحويل المستند المصدر. يحفظ صفحة الوثيقة المحولة بالصفحة.

```csharp
public void Convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, 
    ConvertOptions convertOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | SavePageStreamForFileType | المفوض الذي يحفظ صفحة المستند المحولة إلى دفق. |
| documentCompleted | ConvertedPageStream | المفوض الذي يتلقى تدفق صفحة المستند المحول. |
| convertOptions | ConvertOptions | خيارات التحويل الخاصة بنوع الملف الهدف المطلوب. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول السيناريوهات الأساسية لتحويل المستندات: [كيفية تحويل المستند في 3 خطوات](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* حالات استخدام التحويل والإعدادات والتخصيصات المتقدمة: [تحويل المستند مع الإعدادات المتقدمة](https://docs.groupdocs.com/display/conversionnet/Converting)

### أنظر أيضا

* delegate [SavePageStreamForFileType](../../../groupdocs.conversion.contracts/savepagestreamforfiletype)
* delegate [ConvertedPageStream](../../../groupdocs.conversion.contracts/convertedpagestream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStreamForFileType, ConvertOptionsProvider) {#convert_14}

تحويل المستند المصدر. يحفظ صفحة الوثيقة المحولة بالصفحة.

```csharp
public void Convert(SavePageStreamForFileType document, 
    ConvertOptionsProvider convertOptionsProvider)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | SavePageStreamForFileType | المفوض الذي يحفظ المستند المحول إلى دفق. |
| convertOptionsProvider | ConvertOptionsProvider | تحويل مزود الخيارات. سيتم استدعاؤها لكل تحويل لتوفير خيارات تحويل محددة لنوع المستند المستهدف المطلوب. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول السيناريوهات الأساسية لتحويل المستندات: [كيفية تحويل المستند في 3 خطوات](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* حالات استخدام التحويل والإعدادات والتخصيصات المتقدمة: [تحويل المستند مع الإعدادات المتقدمة](https://docs.groupdocs.com/display/conversionnet/Converting)

### أنظر أيضا

* delegate [SavePageStreamForFileType](../../../groupdocs.conversion.contracts/savepagestreamforfiletype)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStreamForFileType, ConvertedPageStream, ConvertOptionsProvider) {#convert_12}

تحويل المستند المصدر. يحفظ صفحة الوثيقة المحولة بالصفحة.

```csharp
public void Convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, 
    ConvertOptionsProvider convertOptionsProvider)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | SavePageStreamForFileType | المفوض الذي يحفظ صفحة المستند المحولة إلى دفق. |
| documentCompleted | ConvertedPageStream | المفوض الذي يتلقى تدفق صفحة المستند المحول. |
| convertOptionsProvider | ConvertOptionsProvider | تحويل مزود الخيارات. سيتم استدعاؤها لكل تحويل لتوفير خيارات تحويل محددة لنوع المستند المستهدف المطلوب. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول السيناريوهات الأساسية لتحويل المستندات: [كيفية تحويل المستند في 3 خطوات](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* حالات استخدام التحويل والإعدادات والتخصيصات المتقدمة: [تحويل المستند مع الإعدادات المتقدمة](https://docs.groupdocs.com/display/conversionnet/Converting)

### أنظر أيضا

* delegate [SavePageStreamForFileType](../../../groupdocs.conversion.contracts/savepagestreamforfiletype)
* delegate [ConvertedPageStream](../../../groupdocs.conversion.contracts/convertedpagestream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* مساحة الاسم [GroupDocs.Conversion](../../converter)
* المجسم [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
