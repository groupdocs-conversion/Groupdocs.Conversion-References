---
title: "Convert"
second_title: "GroupDocs.Conversion for .NET API Reference"
description: "स्रोत दस्तावेज़ को रूपांतरित करता है। पूरे रूपांतरित दस्तावेज़ को सहेजता है।"
type: docs
weight: 20
url: /hi/net/groupdocs.conversion/converter/convert/
---
## Convert(Func&lt;SaveContext, Stream&gt;, ConvertOptions, CancellationToken) {#convert_4}

स्रोत दस्तावेज़ को रूपांतरित करता है। पूरे रूपांतरित दस्तावेज़ को सहेजता है।

```csharp
public void Convert(Func<SaveContext, Stream> targetStreamProvider, ConvertOptions convertOptions, 
    CancellationToken cancellationToken = default)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| targetStreamProvider | Func`2 | कनवर्टेड दस्तावेज़ को स्ट्रीम में सहेजने वाला डेलीगेट। |
| convertOptions | ConvertOptions | वांछित लक्ष्य फ़ाइल प्रकार के लिए विशिष्ट रूपांतरण विकल्प। |
| cancellationToken | CancellationToken | रद्दीकरण टोकन। |

### टिप्पणियाँ

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### देखें भी

* class [SaveContext](../../savecontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(ConvertOptions, Action&lt;ConvertedContext&gt;, CancellationToken) {#convert}

स्रोत दस्तावेज़ को रूपांतरित करता है। पूरे रूपांतरित दस्तावेज़ को सहेजता है।

```csharp
public void Convert(ConvertOptions convertOptions, Action<ConvertedContext> documentCompleted, 
    CancellationToken cancellationToken = default)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| convertOptions | ConvertOptions | वांछित लक्ष्य फ़ाइल प्रकार के लिए विशिष्ट रूपांतरण विकल्प। |
| documentCompleted | Action`1 | कनवर्टेड दस्तावेज़ स्ट्रीम प्राप्त करने वाला डेलीगेट। हस्ताक्षर: `Action<ConvertedContext>`. [`ConvertedContext`](../../convertedcontext) पैरामीटर में कनवर्टेड दस्तावेज़ स्ट्रीम और मेटाडेटा शामिल है। |
| cancellationToken | CancellationToken | रद्दीकरण टोकन। |

### टिप्पणियाँ

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### देखें भी

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedContext](../../convertedcontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SaveContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) {#convert_5}

स्रोत दस्तावेज़ को रूपांतरित करता है। पूरे रूपांतरित दस्तावेज़ को सहेजता है।

```csharp
public void Convert(Func<SaveContext, Stream> targetStreamProvider, 
    Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    CancellationToken cancellationToken = default)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| targetStreamProvider | Func`2 | कनवर्टेड दस्तावेज़ को सहेजने के लिए स्ट्रीम प्रदान करने वाला डेलीगेट। हस्ताक्षर: `Func<SaveContext, Stream>`. [`SaveContext`](../../savecontext) पैरामीटर में सहेजने की प्रक्रिया की जानकारी शामिल है। |
| convertOptionsProvider | Func`2 | रूपांतरण विकल्प प्रदान करने वाला डेलीगेट। हस्ताक्षर: `Func<ConvertContext, ConvertOptions>`. [`ConvertContext`](../../convertcontext) पैरामीटर में रूपांतरण प्रक्रिया की जानकारी शामिल है। |
| cancellationToken | CancellationToken | रद्दीकरण टोकन। |

### टिप्पणियाँ

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### देखें भी

* class [SaveContext](../../savecontext)
* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedContext&gt;, CancellationToken) {#convert_2}

स्रोत दस्तावेज़ को रूपांतरित करता है। पूरे रूपांतरित दस्तावेज़ को सहेजता है।

```csharp
public void Convert(Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    Action<ConvertedContext> documentCompleted, CancellationToken cancellationToken = default)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | रूपांतरण विकल्प प्रदान करने वाला डेलीगेट। हस्ताक्षर: `Func<ConvertContext, ConvertOptions>`. [`ConvertContext`](../../convertcontext) पैरामीटर में रूपांतरण प्रक्रिया की जानकारी शामिल है। |
| documentCompleted | Action`1 | कनवर्टेड दस्तावेज़ स्ट्रीम प्राप्त करने वाला डेलीगेट। हस्ताक्षर: `Action<ConvertedContext>`. [`ConvertedContext`](../../convertedcontext) पैरामीटर में कनवर्टेड दस्तावेज़ स्ट्रीम और मेटाडेटा शामिल है। |
| cancellationToken | CancellationToken | रद्दीकरण टोकन। |

### टिप्पणियाँ

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### देखें भी

* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedContext](../../convertedcontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(string, ConvertOptions, CancellationToken) {#convert_8}

स्रोत दस्तावेज़ को रूपांतरित करता है। पूरे रूपांतरित दस्तावेज़ को सहेजता है।

```csharp
public void Convert(string filePath, ConvertOptions convertOptions, 
    CancellationToken cancellationToken = default)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | स्ट्रिंग | स्रोत दस्तावेज़ का फ़ाइल पथ। |
| convertOptions | ConvertOptions | वांछित लक्ष्य फ़ाइल प्रकार के लिए विशिष्ट रूपांतरण विकल्प। |
| cancellationToken | CancellationToken | रद्दीकरण टोकन। |

### टिप्पणियाँ

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### देखें भी

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SavePageContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) {#convert_7}

स्रोत दस्तावेज़ को रूपांतरित करता है। रूपांतरित दस्तावेज़ को पृष्ठ दर पृष्ठ सहेजता है।

```csharp
public void Convert(Func<SavePageContext, Stream> targetStreamProvider, 
    Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    CancellationToken cancellationToken = default)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| targetStreamProvider | Func`2 | प्रत्येक कनवर्टेड पृष्ठ को सहेजने के लिए स्ट्रीम प्रदान करने वाला डेलीगेट। हस्ताक्षर: `Func<SavePageContext, Stream>`. [`SavePageContext`](../../savepagecontext) पैरामीटर में पृष्ठ संख्या और दस्तावेज़ की जानकारी शामिल है। |
| convertOptionsProvider | Func`2 | रूपांतरण विकल्प प्रदान करने वाला डेलीगेट। हस्ताक्षर: `Func<ConvertContext, ConvertOptions>`. [`ConvertContext`](../../convertcontext) पैरामीटर में रूपांतरण प्रक्रिया की जानकारी शामिल है। |
| cancellationToken | CancellationToken | रद्दीकरण टोकन। |

### टिप्पणियाँ

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### देखें भी

* class [SavePageContext](../../savepagecontext)
* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SavePageContext, Stream&gt;, ConvertOptions, CancellationToken) {#convert_6}

स्रोत दस्तावेज़ को रूपांतरित करता है। रूपांतरित दस्तावेज़ को पृष्ठ दर पृष्ठ सहेजता है।

```csharp
public void Convert(Func<SavePageContext, Stream> targetStreamProvider, 
    ConvertOptions convertOptions, CancellationToken cancellationToken = default)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| targetStreamProvider | Func`2 | प्रत्येक कनवर्टेड पृष्ठ को सहेजने के लिए स्ट्रीम प्रदान करने वाला डेलीगेट। हस्ताक्षर: `Func<SavePageContext, Stream>`. [`SavePageContext`](../../savepagecontext) पैरामीटर में पृष्ठ संख्या और दस्तावेज़ की जानकारी शामिल है। |
| convertOptions | ConvertOptions | वांछित लक्ष्य फ़ाइल प्रकार के लिए विशिष्ट रूपांतरण विकल्प। |
| cancellationToken | CancellationToken | रद्दीकरण टोकन। |

### टिप्पणियाँ

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### देखें भी

* class [SavePageContext](../../savepagecontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(ConvertOptions, Action&lt;ConvertedPageContext&gt;, CancellationToken) {#convert_1}

स्रोत दस्तावेज़ को रूपांतरित करता है। रूपांतरित दस्तावेज़ को पृष्ठ दर पृष्ठ सहेजता है।

```csharp
public void Convert(ConvertOptions convertOptions, Action<ConvertedPageContext> documentCompleted, 
    CancellationToken cancellationToken = default)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| documentCompleted | ConvertOptions | प्रत्येक कनवर्टेड पृष्ठ को प्राप्त करने वाला डेलीगेट। हस्ताक्षर: `Action<ConvertedPageContext>`. [`ConvertedPageContext`](../../convertedpagecontext) पैरामीटर में पृष्ठ संख्या, स्ट्रीम, स्रोत फ़ाइल नाम, और लक्ष्य फ़ाइल प्रकार शामिल हैं। |
| convertOptions | Action`1 | वांछित लक्ष्य फ़ाइल प्रकार के लिए विशिष्ट रूपांतरण विकल्प। |
| cancellationToken | CancellationToken | रद्दीकरण टोकन। |

### टिप्पणियाँ

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### देखें भी

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedPageContext](../../convertedpagecontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedPageContext&gt;, CancellationToken) {#convert_3}

स्रोत दस्तावेज़ को रूपांतरित करता है। रूपांतरित दस्तावेज़ को पृष्ठ दर पृष्ठ सहेजता है।

```csharp
public void Convert(Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    Action<ConvertedPageContext> documentCompleted, CancellationToken cancellationToken = default)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | रूपांतरण विकल्प प्रदान करने वाला डेलीगेट। हस्ताक्षर: `Func<ConvertContext, ConvertOptions>`. [`ConvertContext`](../../convertcontext) पैरामीटर में रूपांतरण प्रक्रिया की जानकारी शामिल है। |
| documentCompleted | Action`1 | प्रत्येक कनवर्टेड पृष्ठ को प्राप्त करने वाला डेलीगेट। हस्ताक्षर: `Action<ConvertedPageContext>`. [`ConvertedPageContext`](../../convertedpagecontext) पैरामीटर में पृष्ठ संख्या, स्ट्रीम, स्रोत फ़ाइल नाम, और लक्ष्य फ़ाइल प्रकार शामिल हैं। |
| cancellationToken | CancellationToken | रद्दीकरण टोकन। |

### टिप्पणियाँ

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### देखें भी

* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedPageContext](../../convertedpagecontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
