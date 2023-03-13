---
title: Converter
second_title: .NET API संदर्भ के लिए GroupDocs.Conversion
description: क नय उदहरण शुरू करत हैConvertergroupdocs.conversion/converter वर्ग.
type: docs
weight: 10
url: /hi/net/groupdocs.conversion/converter/converter/
---
## Converter(Func&lt;Stream&gt;) {#constructor_1}

का नया उदाहरण शुरू करता है[`Converter`](../../converter) वर्ग.

```csharp
public Converter(Func<Stream> document)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Func`1 | वह विधि जो पठनीय स्ट्रीम लौटाती है। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | कब फेंका*document* शून्य है। |

### टिप्पणियों

**और अधिक जानें**

* FTP, Amazon S3 Storage, Windows Azure या किसी अन्य तृतीय-पक्ष संग्रहण में संग्रहीत दस्तावेज़ों को लोड और परिवर्तित करने के तरीके के बारे में अधिक जानकारी: [विभिन्न स्रोतों से दस्तावेज़ लोड हो रहा है](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* फ़ाइल प्रकार पर निर्भर दस्तावेज़ लोड करने के विकल्पों के बारे में अधिक जानकारी: [विभिन्न दस्तावेज़ प्रकारों के लिए लोड विकल्प](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### यह सभी देखें

* class [Converter](../../converter)
* नाम स्थान [GroupDocs.Conversion](../../converter)
* सभा [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) {#constructor_2}

का नया उदाहरण शुरू करता है[`Converter`](../../converter) वर्ग.

```csharp
public Converter(Func<Stream> document, Func<ConverterSettings> settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Func`1 | वह विधि जो पठनीय स्ट्रीम लौटाती है। |
| settings | Func`1 | कनवर्टर सेटिंग्स। |

### टिप्पणियों

**और अधिक जानें**

* FTP, Amazon S3 Storage, Windows Azure या किसी अन्य तृतीय-पक्ष संग्रहण में संग्रहीत दस्तावेज़ों को लोड और परिवर्तित करने के तरीके के बारे में अधिक जानकारी: [विभिन्न स्रोतों से दस्तावेज़ लोड हो रहा है](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* फ़ाइल प्रकार पर निर्भर दस्तावेज़ लोड करने के विकल्पों के बारे में अधिक जानकारी: [विभिन्न दस्तावेज़ प्रकारों के लिए लोड विकल्प](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### यह सभी देखें

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* नाम स्थान [GroupDocs.Conversion](../../converter)
* सभा [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_3}

का नया उदाहरण शुरू करता है[`Converter`](../../converter) वर्ग.

```csharp
public Converter(Func<Stream> document, Func<LoadOptions> loadOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Func`1 | वह विधि जो पठनीय स्ट्रीम लौटाती है। |
| loadOptions | Func`1 | दस्तावेज़ लोड विकल्प लौटाने वाली विधियाँ। |

### टिप्पणियों

**और अधिक जानें**

* FTP, Amazon S3 Storage, Windows Azure या किसी अन्य तृतीय-पक्ष संग्रहण में संग्रहीत दस्तावेज़ों को लोड और परिवर्तित करने के तरीके के बारे में अधिक जानकारी: [विभिन्न स्रोतों से दस्तावेज़ लोड हो रहा है](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* फ़ाइल प्रकार पर निर्भर दस्तावेज़ लोड करने के विकल्पों के बारे में अधिक जानकारी: [विभिन्न दस्तावेज़ प्रकारों के लिए लोड विकल्प](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### यह सभी देखें

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* नाम स्थान [GroupDocs.Conversion](../../converter)
* सभा [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_4}

का नया उदाहरण शुरू करता है[`Converter`](../../converter) वर्ग.

```csharp
public Converter(Func<Stream> document, Func<LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Func`1 | वह विधि जो पठनीय स्ट्रीम लौटाती है। |
| loadOptions | Func`1 | दस्तावेज़ लोड विकल्प लौटाने वाली विधियाँ। |
| settings | Func`1 | कनवर्टर सेटिंग्स। |

### टिप्पणियों

**और अधिक जानें**

* FTP, Amazon S3 Storage, Windows Azure या किसी अन्य तृतीय-पक्ष संग्रहण में संग्रहीत दस्तावेज़ों को लोड और परिवर्तित करने के तरीके के बारे में अधिक जानकारी: [विभिन्न स्रोतों से दस्तावेज़ लोड हो रहा है](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* फ़ाइल प्रकार पर निर्भर दस्तावेज़ लोड करने के विकल्पों के बारे में अधिक जानकारी: [विभिन्न दस्तावेज़ प्रकारों के लिए लोड विकल्प](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### यह सभी देखें

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* नाम स्थान [GroupDocs.Conversion](../../converter)
* सभा [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;) {#constructor_5}

का नया उदाहरण शुरू करता है[`Converter`](../../converter) वर्ग.

```csharp
public Converter(Func<Stream> document, Func<FileType, LoadOptions> loadOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Func`1 | वह विधि जो पठनीय स्ट्रीम लौटाती है। |
| loadOptions | Func`2 | दस्तावेज़ लोड विकल्प लौटाने वाली विधियाँ। स्रोत फ़ाइल का प्रकार |

### टिप्पणियों

**और अधिक जानें**

* FTP, Amazon S3 Storage, Windows Azure या किसी अन्य तृतीय-पक्ष संग्रहण में संग्रहीत दस्तावेज़ों को लोड और परिवर्तित करने के तरीके के बारे में अधिक जानकारी: [विभिन्न स्रोतों से दस्तावेज़ लोड हो रहा है](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* फ़ाइल प्रकार पर निर्भर दस्तावेज़ लोड करने के विकल्पों के बारे में अधिक जानकारी: [विभिन्न दस्तावेज़ प्रकारों के लिए लोड विकल्प](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### यह सभी देखें

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* नाम स्थान [GroupDocs.Conversion](../../converter)
* सभा [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_6}

का नया उदाहरण शुरू करता है[`Converter`](../../converter) वर्ग.

```csharp
public Converter(Func<Stream> document, Func<FileType, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Func`1 | वह विधि जो पठनीय स्ट्रीम लौटाती है। |
| loadOptions | Func`2 | दस्तावेज़ लोड विकल्प लौटाने वाली विधियाँ। स्रोत फ़ाइल का प्रकार |
| settings | Func`1 | कनवर्टर सेटिंग्स। |

### टिप्पणियों

**और अधिक जानें**

* FTP, Amazon S3 Storage, Windows Azure या किसी अन्य तृतीय-पक्ष संग्रहण में संग्रहीत दस्तावेज़ों को लोड और परिवर्तित करने के तरीके के बारे में अधिक जानकारी: [विभिन्न स्रोतों से दस्तावेज़ लोड हो रहा है](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* फ़ाइल प्रकार पर निर्भर दस्तावेज़ लोड करने के विकल्पों के बारे में अधिक जानकारी: [विभिन्न दस्तावेज़ प्रकारों के लिए लोड विकल्प](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### यह सभी देखें

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* नाम स्थान [GroupDocs.Conversion](../../converter)
* सभा [GroupDocs.Conversion](../../../)

---

## Converter(string) {#constructor_7}

का नया उदाहरण शुरू करता है[`Converter`](../../converter) वर्ग.

```csharp
public Converter(string filePath)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | स्रोत दस्तावेज़ के लिए फ़ाइल पथ। |

### टिप्पणियों

**और अधिक जानें**

* FTP, Amazon S3 Storage, Windows Azure या किसी अन्य तृतीय-पक्ष संग्रहण में संग्रहीत दस्तावेज़ों को लोड और परिवर्तित करने के तरीके के बारे में अधिक जानकारी: [विभिन्न स्रोतों से दस्तावेज़ लोड हो रहा है](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* फ़ाइल प्रकार पर निर्भर दस्तावेज़ लोड करने के विकल्पों के बारे में अधिक जानकारी: [विभिन्न दस्तावेज़ प्रकारों के लिए लोड विकल्प](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### यह सभी देखें

* class [Converter](../../converter)
* नाम स्थान [GroupDocs.Conversion](../../converter)
* सभा [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;) {#constructor_8}

का नया उदाहरण शुरू करता है[`Converter`](../../converter) वर्ग.

```csharp
public Converter(string filePath, Func<ConverterSettings> settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | स्रोत दस्तावेज़ के लिए फ़ाइल पथ। |
| settings | Func`1 | कनवर्टर सेटिंग्स। |

### टिप्पणियों

**और अधिक जानें**

* FTP, Amazon S3 Storage, Windows Azure या किसी अन्य तृतीय-पक्ष संग्रहण में संग्रहीत दस्तावेज़ों को लोड और परिवर्तित करने के तरीके के बारे में अधिक जानकारी: [विभिन्न स्रोतों से दस्तावेज़ लोड हो रहा है](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* फ़ाइल प्रकार पर निर्भर दस्तावेज़ लोड करने के विकल्पों के बारे में अधिक जानकारी: [विभिन्न दस्तावेज़ प्रकारों के लिए लोड विकल्प](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### यह सभी देखें

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* नाम स्थान [GroupDocs.Conversion](../../converter)
* सभा [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadOptions&gt;) {#constructor_9}

का नया उदाहरण शुरू करता है[`Converter`](../../converter) वर्ग.

```csharp
public Converter(string filePath, Func<LoadOptions> loadOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | स्रोत दस्तावेज़ के लिए फ़ाइल पथ। |
| loadOptions | Func`1 | दस्तावेज़ लोड विकल्प लौटाने वाली विधियाँ। |

### टिप्पणियों

**और अधिक जानें**

* FTP, Amazon S3 Storage, Windows Azure या किसी अन्य तृतीय-पक्ष संग्रहण में संग्रहीत दस्तावेज़ों को लोड और परिवर्तित करने के तरीके के बारे में अधिक जानकारी: [विभिन्न स्रोतों से दस्तावेज़ लोड हो रहा है](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* फ़ाइल प्रकार पर निर्भर दस्तावेज़ लोड करने के विकल्पों के बारे में अधिक जानकारी: [विभिन्न दस्तावेज़ प्रकारों के लिए लोड विकल्प](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### यह सभी देखें

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* नाम स्थान [GroupDocs.Conversion](../../converter)
* सभा [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_10}

का नया उदाहरण शुरू करता है[`Converter`](../../converter) वर्ग.

```csharp
public Converter(string filePath, Func<LoadOptions> loadOptions, Func<ConverterSettings> settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | स्रोत दस्तावेज़ के लिए फ़ाइल पथ। |
| loadOptions | Func`1 | दस्तावेज़ लोड विकल्प लौटाने वाली विधियाँ। |
| settings | Func`1 | कनवर्टर सेटिंग्स। |

### टिप्पणियों

**और अधिक जानें**

* FTP, Amazon S3 Storage, Windows Azure या किसी अन्य तृतीय-पक्ष संग्रहण में संग्रहीत दस्तावेज़ों को लोड और परिवर्तित करने के तरीके के बारे में अधिक जानकारी: [विभिन्न स्रोतों से दस्तावेज़ लोड हो रहा है](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* फ़ाइल प्रकार पर निर्भर दस्तावेज़ लोड करने के विकल्पों के बारे में अधिक जानकारी: [विभिन्न दस्तावेज़ प्रकारों के लिए लोड विकल्प](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### यह सभी देखें

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* नाम स्थान [GroupDocs.Conversion](../../converter)
* सभा [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;FileType, LoadOptions&gt;) {#constructor_11}

का नया उदाहरण शुरू करता है[`Converter`](../../converter) वर्ग.

```csharp
public Converter(string filePath, Func<FileType, LoadOptions> loadOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | स्रोत दस्तावेज़ के लिए फ़ाइल पथ। |
| loadOptions | Func`2 | दस्तावेज़ लोड विकल्प लौटाने वाली विधियाँ। स्रोत फ़ाइल का प्रकार |

### टिप्पणियों

**और अधिक जानें**

* FTP, Amazon S3 Storage, Windows Azure या किसी अन्य तृतीय-पक्ष संग्रहण में संग्रहीत दस्तावेज़ों को लोड और परिवर्तित करने के तरीके के बारे में अधिक जानकारी: [विभिन्न स्रोतों से दस्तावेज़ लोड हो रहा है](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* फ़ाइल प्रकार पर निर्भर दस्तावेज़ लोड करने के विकल्पों के बारे में अधिक जानकारी: [विभिन्न दस्तावेज़ प्रकारों के लिए लोड विकल्प](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### यह सभी देखें

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* नाम स्थान [GroupDocs.Conversion](../../converter)
* सभा [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_12}

का नया उदाहरण शुरू करता है[`Converter`](../../converter) वर्ग.

```csharp
public Converter(string filePath, Func<FileType, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | स्रोत दस्तावेज़ के लिए फ़ाइल पथ। |
| loadOptions | Func`2 | दस्तावेज़ लोड विकल्प लौटाने वाली विधियाँ। स्रोत फ़ाइल का प्रकार |
| settings | Func`1 | कनवर्टर सेटिंग्स। |

### टिप्पणियों

**और अधिक जानें**

* FTP, Amazon S3 Storage, Windows Azure या किसी अन्य तृतीय-पक्ष संग्रहण में संग्रहीत दस्तावेज़ों को लोड और परिवर्तित करने के तरीके के बारे में अधिक जानकारी: [विभिन्न स्रोतों से दस्तावेज़ लोड हो रहा है](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* फ़ाइल प्रकार पर निर्भर दस्तावेज़ लोड करने के विकल्पों के बारे में अधिक जानकारी: [विभिन्न दस्तावेज़ प्रकारों के लिए लोड विकल्प](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### यह सभी देखें

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* नाम स्थान [GroupDocs.Conversion](../../converter)
* सभा [GroupDocs.Conversion](../../../)

---

## Converter() {#constructor}

का नया उदाहरण शुरू करता है[`Converter`](../../converter) धाराप्रवाह रूपांतरण सेटअप के लिए वर्ग।

```csharp
public Converter()
```

### टिप्पणियों

धाराप्रवाह रूपांतरण उपयोग का नमूना:

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

### यह सभी देखें

* class [Converter](../../converter)
* नाम स्थान [GroupDocs.Conversion](../../converter)
* सभा [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
