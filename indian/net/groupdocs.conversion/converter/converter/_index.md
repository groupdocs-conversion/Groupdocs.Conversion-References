---
title: "Converter"
second_title: "GroupDocs.Conversion for .NET API Reference"
description: "Convertergroupdocs.conversion/converter क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।"
type: docs
weight: 10
url: /hi/net/groupdocs.conversion/converter/converter/
---
## Converter(Func&lt;Stream&gt;) {#constructor}

[`Converter`](../../converter) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public Converter(Func<Stream> sourceStreamProvider)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | पढ़ने योग्य स्ट्रीम लौटाने वाली मेथड। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *sourceStreamProvider* के null होने पर थ्रो किया जाता है। |

### टिप्पणियाँ

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### देखें भी

* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) {#constructor_1}

[`Converter`](../../converter) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<ConverterSettings> settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | पढ़ने योग्य स्ट्रीम लौटाने वाली मेथड। |
| settings | Func`1 | कनवर्टर सेटिंग्स। |

### टिप्पणियाँ

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### देखें भी

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_3}

[`Converter`](../../converter) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings = null)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | पढ़ने योग्य स्ट्रीम लौटाने वाली मेथड। |
| loadOptions | Func`2 | दस्तावेज़ के लिए लोड विकल्प प्रदान करने वाला डेलीगेट। हस्ताक्षर: `Func<LoadContext, LoadOptions>`. [`LoadContext`](../../loadcontext) पैरामीटर में लोड हो रहे दस्तावेज़ की जानकारी शामिल है। |
| settings | Func`1 | कनवर्टर सेटिंग्स। |

### टिप्पणियाँ

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### देखें भी

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_4}

स्पष्ट रूपांतरण इवेंट्स के साथ [`Converter`](../../converter) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | पढ़ने योग्य स्ट्रीम लौटाने वाली मेथड। |
| loadOptions | Func`2 | दस्तावेज़ के लिए लोड विकल्प प्रदान करने वाला डेलीगेट। |
| settings | Func`1 | कनवर्टर सेटिंग्स। |
| events | Func`1 | कनवर्टर के जीवनकाल के लिए पंजीकृत एकत्रित [`ConversionEvents`](../../conversionevents) प्रदान करने वाला डेलीगेट। |

### देखें भी

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_2}

स्पष्ट रूपांतरण इवेंट्स के साथ [`Converter`](../../converter) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<ConverterSettings> settings, 
    Func<ConversionEvents> events)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | पढ़ने योग्य स्ट्रीम लौटाने वाली मेथड। |
| settings | Func`1 | कनवर्टर सेटिंग्स। |
| events | Func`1 | कनवर्टर के जीवनकाल के लिए पंजीकृत एकत्रित [`ConversionEvents`](../../conversionevents) प्रदान करने वाला डेलीगेट। |

### देखें भी

* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string) {#constructor_5}

[`Converter`](../../converter) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public Converter(string filePath)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | स्ट्रिंग | स्रोत दस्तावेज़ का फ़ाइल पथ। |

### टिप्पणियाँ

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### देखें भी

* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;) {#constructor_6}

[`Converter`](../../converter) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public Converter(string filePath, Func<ConverterSettings> settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | स्ट्रिंग | स्रोत दस्तावेज़ का फ़ाइल पथ। |
| settings | Func`1 | कनवर्टर सेटिंग्स। |

### टिप्पणियाँ

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### देखें भी

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_8}

[`Converter`](../../converter) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public Converter(string filePath, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings = null)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | स्ट्रिंग | स्रोत दस्तावेज़ का फ़ाइल पथ। |
| loadOptions | Func`2 | दस्तावेज़ के लिए लोड विकल्प प्रदान करने वाला डेलीगेट। हस्ताक्षर: `Func<LoadContext, LoadOptions>`. [`LoadContext`](../../loadcontext) पैरामीटर में लोड हो रहे दस्तावेज़ की जानकारी शामिल है। |
| settings | Func`1 | कनवर्टर सेटिंग्स। |

### टिप्पणियाँ

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### देखें भी

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_9}

स्पष्ट रूपांतरण इवेंट्स के साथ [`Converter`](../../converter) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public Converter(string filePath, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | स्ट्रिंग | स्रोत दस्तावेज़ का फ़ाइल पथ। |
| loadOptions | Func`2 | दस्तावेज़ के लिए लोड विकल्प प्रदान करने वाला डेलीगेट। |
| settings | Func`1 | कनवर्टर सेटिंग्स। |
| events | Func`1 | कनवर्टर के जीवनकाल के लिए पंजीकृत एकत्रित [`ConversionEvents`](../../conversionevents) प्रदान करने वाला डेलीगेट। |

### देखें भी

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_7}

स्पष्ट रूपांतरण इवेंट्स के साथ [`Converter`](../../converter) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public Converter(string filePath, Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | स्ट्रिंग | स्रोत दस्तावेज़ का फ़ाइल पथ। |
| settings | Func`1 | कनवर्टर सेटिंग्स। |
| events | Func`1 | कनवर्टर के जीवनकाल के लिए पंजीकृत एकत्रित [`ConversionEvents`](../../conversionevents) प्रदान करने वाला डेलीगेट। |

### देखें भी

* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
