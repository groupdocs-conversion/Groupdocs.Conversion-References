---
title: Convert
second_title: .NET API संदर्भ के लिए GroupDocs.Conversion
description: स्रत दस्तवेज़ क रूपंतरत करत है पूरे रूपंतरत दस्तवेज़ क सहेजत है
type: docs
weight: 20
url: /hi/net/groupdocs.conversion/converter/convert/
---
## Convert(Func&lt;Stream&gt;, ConvertOptions) {#convert}

स्रोत दस्तावेज़ को रूपांतरित करता है। पूरे रूपांतरित दस्तावेज़ को सहेजता है।

```csharp
public void Convert(Func<Stream> document, ConvertOptions convertOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Func`1 | प्रतिनिधि जो रूपांतरित दस्तावेज़ को स्ट्रीम में सहेजता है। |
| convertOptions | ConvertOptions | वांछित लक्ष्य फ़ाइल प्रकार के लिए विशिष्ट कन्वर्ट विकल्प। |

### टिप्पणियों

**और अधिक जानें**

* दस्तावेज़ रूपांतरण बुनियादी परिदृश्यों के बारे में अधिक जानकारी: [दस्तावेज़ को 3 चरणों में कैसे बदलें](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* रूपांतरण उपयोग के उदाहरण, उन्नत सेटिंग और अनुकूलन: [दस्तावेज़ को उन्नत सेटिंग्स के साथ बदलें](https://docs.groupdocs.com/display/conversionnet/Converting)

### यह सभी देखें

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* नाम स्थान [GroupDocs.Conversion](../../converter)
* सभा [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) {#convert_1}

स्रोत दस्तावेज़ को रूपांतरित करता है। पूरे रूपांतरित दस्तावेज़ को सहेजता है।

```csharp
public void Convert(Func<Stream> document, Action<Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Func`1 | प्रतिनिधि जो रूपांतरित दस्तावेज़ को स्ट्रीम में सहेजता है। |
| documentCompleted | Action`2 | प्रतिनिधि जो परिवर्तित दस्तावेज़ स्ट्रीम प्राप्त करता है। फ़ाइल सामग्री स्ट्रीमफ़ाइल का नाम |
| convertOptions | ConvertOptions | वांछित लक्ष्य फ़ाइल प्रकार के लिए विशिष्ट कन्वर्ट विकल्प। |

### टिप्पणियों

**और अधिक जानें**

* दस्तावेज़ रूपांतरण बुनियादी परिदृश्यों के बारे में अधिक जानकारी: [दस्तावेज़ को 3 चरणों में कैसे बदलें](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* रूपांतरण उपयोग के उदाहरण, उन्नत सेटिंग और अनुकूलन: [दस्तावेज़ को उन्नत सेटिंग्स के साथ बदलें](https://docs.groupdocs.com/display/conversionnet/Converting)

### यह सभी देखें

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* नाम स्थान [GroupDocs.Conversion](../../converter)
* सभा [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_3}

स्रोत दस्तावेज़ को रूपांतरित करता है। पूरे रूपांतरित दस्तावेज़ को सहेजता है।

```csharp
public void Convert(Func<Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Func`1 | प्रतिनिधि जो रूपांतरित दस्तावेज़ को स्ट्रीम में सहेजता है। |
| convertOptionsProvider | Func`3 | कन्वर्ट विकल्प प्रदाता। वांछित लक्ष्य दस्तावेज़ प्रकार के लिए विशिष्ट रूपांतरण विकल्प प्रदान करने के लिए प्रत्येक रूपांतरण के लिए बुलाया जाएगा। फ़ाइल का नामफ़ाइल का प्रकार |

### टिप्पणियों

**और अधिक जानें**

* दस्तावेज़ रूपांतरण बुनियादी परिदृश्यों के बारे में अधिक जानकारी: [दस्तावेज़ को 3 चरणों में कैसे बदलें](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* रूपांतरण उपयोग के उदाहरण, उन्नत सेटिंग और अनुकूलन: [दस्तावेज़ को उन्नत सेटिंग्स के साथ बदलें](https://docs.groupdocs.com/display/conversionnet/Converting)

### यह सभी देखें

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* नाम स्थान [GroupDocs.Conversion](../../converter)
* सभा [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_2}

स्रोत दस्तावेज़ को रूपांतरित करता है। पूरे रूपांतरित दस्तावेज़ को सहेजता है।

```csharp
public void Convert(Func<Stream> document, Action<Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Func`1 | प्रतिनिधि जो रूपांतरित दस्तावेज़ को स्ट्रीम में सहेजता है। |
| documentCompleted | Action`2 | प्रतिनिधि जो परिवर्तित दस्तावेज़ स्ट्रीम प्राप्त करता है। फ़ाइल सामग्री स्ट्रीमफ़ाइल का नाम |
| convertOptionsProvider | Func`3 | कन्वर्ट विकल्प प्रदाता। वांछित लक्ष्य दस्तावेज़ प्रकार के लिए विशिष्ट रूपांतरण विकल्प प्रदान करने के लिए प्रत्येक रूपांतरण के लिए बुलाया जाएगा। फ़ाइल का नामफ़ाइल का प्रकार |

### टिप्पणियों

**और अधिक जानें**

* दस्तावेज़ रूपांतरण बुनियादी परिदृश्यों के बारे में अधिक जानकारी: [दस्तावेज़ को 3 चरणों में कैसे बदलें](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* रूपांतरण उपयोग के उदाहरण, उन्नत सेटिंग और अनुकूलन: [दस्तावेज़ को उन्नत सेटिंग्स के साथ बदलें](https://docs.groupdocs.com/display/conversionnet/Converting)

### यह सभी देखें

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* नाम स्थान [GroupDocs.Conversion](../../converter)
* सभा [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, ConvertOptions) {#convert_4}

स्रोत दस्तावेज़ को रूपांतरित करता है। पूरे रूपांतरित दस्तावेज़ को सहेजता है।

```csharp
public void Convert(Func<FileType, Stream> document, ConvertOptions convertOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Func`2 | प्रतिनिधि जो कनवर्ट किए गए दस्तावेज़ को स्ट्रीम में सहेजता है. स्रोत फ़ाइल का प्रकार |
| convertOptions | ConvertOptions | वांछित लक्ष्य फ़ाइल प्रकार के लिए विशिष्ट कन्वर्ट विकल्प। |

### टिप्पणियों

**और अधिक जानें**

* दस्तावेज़ रूपांतरण बुनियादी परिदृश्यों के बारे में अधिक जानकारी: [दस्तावेज़ को 3 चरणों में कैसे बदलें](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* रूपांतरण उपयोग के उदाहरण, उन्नत सेटिंग और अनुकूलन: [दस्तावेज़ को उन्नत सेटिंग्स के साथ बदलें](https://docs.groupdocs.com/display/conversionnet/Converting)

### यह सभी देखें

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* नाम स्थान [GroupDocs.Conversion](../../converter)
* सभा [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) {#convert_5}

स्रोत दस्तावेज़ को रूपांतरित करता है। पूरे रूपांतरित दस्तावेज़ को सहेजता है।

```csharp
public void Convert(Func<FileType, Stream> document, Action<Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Func`2 | प्रतिनिधि जो कनवर्ट किए गए दस्तावेज़ को स्ट्रीम में सहेजता है. स्रोत फ़ाइल का प्रकार |
| documentCompleted | Action`2 | प्रतिनिधि जो परिवर्तित दस्तावेज़ स्ट्रीम प्राप्त करता है। फ़ाइल सामग्री स्ट्रीमफ़ाइल का नाम |
| convertOptions | ConvertOptions | वांछित लक्ष्य फ़ाइल प्रकार के लिए विशिष्ट कन्वर्ट विकल्प। |

### टिप्पणियों

**और अधिक जानें**

* दस्तावेज़ रूपांतरण बुनियादी परिदृश्यों के बारे में अधिक जानकारी: [दस्तावेज़ को 3 चरणों में कैसे बदलें](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* रूपांतरण उपयोग के उदाहरण, उन्नत सेटिंग और अनुकूलन: [दस्तावेज़ को उन्नत सेटिंग्स के साथ बदलें](https://docs.groupdocs.com/display/conversionnet/Converting)

### यह सभी देखें

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* नाम स्थान [GroupDocs.Conversion](../../converter)
* सभा [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_7}

स्रोत दस्तावेज़ को रूपांतरित करता है। पूरे रूपांतरित दस्तावेज़ को सहेजता है।

```csharp
public void Convert(Func<FileType, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Func`2 | प्रतिनिधि जो कनवर्ट किए गए दस्तावेज़ को स्ट्रीम में सहेजता है. स्रोत फ़ाइल का प्रकार |
| convertOptionsProvider | Func`3 | कन्वर्ट विकल्प प्रदाता। वांछित लक्ष्य दस्तावेज़ प्रकार के लिए विशिष्ट रूपांतरण विकल्प प्रदान करने के लिए प्रत्येक रूपांतरण के लिए बुलाया जाएगा। फ़ाइल का नामफ़ाइल का प्रकार |

### टिप्पणियों

**और अधिक जानें**

* दस्तावेज़ रूपांतरण बुनियादी परिदृश्यों के बारे में अधिक जानकारी: [दस्तावेज़ को 3 चरणों में कैसे बदलें](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* रूपांतरण उपयोग के उदाहरण, उन्नत सेटिंग और अनुकूलन: [दस्तावेज़ को उन्नत सेटिंग्स के साथ बदलें](https://docs.groupdocs.com/display/conversionnet/Converting)

### यह सभी देखें

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* नाम स्थान [GroupDocs.Conversion](../../converter)
* सभा [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_6}

स्रोत दस्तावेज़ को रूपांतरित करता है। पूरे रूपांतरित दस्तावेज़ को सहेजता है।

```csharp
public void Convert(Func<FileType, Stream> document, Action<Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Func`2 | प्रतिनिधि जो कनवर्ट किए गए दस्तावेज़ को स्ट्रीम में सहेजता है. स्रोत फ़ाइल का प्रकार |
| documentCompleted | Action`2 | प्रतिनिधि जो परिवर्तित दस्तावेज़ स्ट्रीम प्राप्त करता है। फ़ाइल सामग्री स्ट्रीमफ़ाइल का नाम |
| convertOptionsProvider | Func`3 | कन्वर्ट विकल्प प्रदाता। वांछित लक्ष्य दस्तावेज़ प्रकार के लिए विशिष्ट रूपांतरण विकल्प प्रदान करने के लिए प्रत्येक रूपांतरण के लिए बुलाया जाएगा। फ़ाइल का नामफ़ाइल का प्रकार |

### टिप्पणियों

**और अधिक जानें**

* दस्तावेज़ रूपांतरण बुनियादी परिदृश्यों के बारे में अधिक जानकारी: [दस्तावेज़ को 3 चरणों में कैसे बदलें](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* रूपांतरण उपयोग के उदाहरण, उन्नत सेटिंग और अनुकूलन: [दस्तावेज़ को उन्नत सेटिंग्स के साथ बदलें](https://docs.groupdocs.com/display/conversionnet/Converting)

### यह सभी देखें

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* नाम स्थान [GroupDocs.Conversion](../../converter)
* सभा [GroupDocs.Conversion](../../../)

---

## Convert(string, ConvertOptions) {#convert_16}

स्रोत दस्तावेज़ को रूपांतरित करता है। पूरे रूपांतरित दस्तावेज़ को सहेजता है।

```csharp
public void Convert(string filePath, ConvertOptions convertOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | स्रोत दस्तावेज़ के लिए फ़ाइल पथ। |
| convertOptions | ConvertOptions | वांछित लक्ष्य फ़ाइल प्रकार के लिए विशिष्ट कन्वर्ट विकल्प। |

### टिप्पणियों

**और अधिक जानें**

* दस्तावेज़ रूपांतरण बुनियादी परिदृश्यों के बारे में अधिक जानकारी: [दस्तावेज़ को 3 चरणों में कैसे बदलें](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* रूपांतरण उपयोग के उदाहरण, उन्नत सेटिंग और अनुकूलन: [दस्तावेज़ को उन्नत सेटिंग्स के साथ बदलें](https://docs.groupdocs.com/display/conversionnet/Converting)

### यह सभी देखें

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* नाम स्थान [GroupDocs.Conversion](../../converter)
* सभा [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, ConvertOptions) {#convert_8}

स्रोत दस्तावेज़ को रूपांतरित करता है। परिवर्तित दस्तावेज़ पृष्ठ पृष्ठ द्वारा सहेजता है।

```csharp
public void Convert(Func<int, Stream> document, ConvertOptions convertOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Func`2 | प्रतिनिधि जो कनवर्ट किए गए दस्तावेज़ को स्ट्रीम में सहेजता है. पृष्ठ संख्या |
| convertOptions | ConvertOptions | वांछित लक्ष्य फ़ाइल प्रकार के लिए विशिष्ट कन्वर्ट विकल्प। |

### टिप्पणियों

**और अधिक जानें**

* दस्तावेज़ रूपांतरण बुनियादी परिदृश्यों के बारे में अधिक जानकारी: [दस्तावेज़ को 3 चरणों में कैसे बदलें](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* रूपांतरण उपयोग के उदाहरण, उन्नत सेटिंग और अनुकूलन: [दस्तावेज़ को उन्नत सेटिंग्स के साथ बदलें](https://docs.groupdocs.com/display/conversionnet/Converting)

### यह सभी देखें

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* नाम स्थान [GroupDocs.Conversion](../../converter)
* सभा [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) {#convert_9}

स्रोत दस्तावेज़ को रूपांतरित करता है। परिवर्तित दस्तावेज़ पृष्ठ पृष्ठ द्वारा सहेजता है।

```csharp
public void Convert(Func<int, Stream> document, Action<int, Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Func`2 | प्रतिनिधि जो रूपांतरित दस्तावेज़ पृष्ठ को स्ट्रीम में सहेजता है. पृष्ठ संख्या |
| documentCompleted | Action`3 | प्रतिनिधि जो परिवर्तित दस्तावेज़ पेज स्ट्रीम प्राप्त करता है। पृष्ठ संख्याफ़ाइल सामग्री स्ट्रीमफ़ाइल का नाम |
| convertOptions | ConvertOptions | वांछित लक्ष्य फ़ाइल प्रकार के लिए विशिष्ट कन्वर्ट विकल्प। |

### टिप्पणियों

**और अधिक जानें**

* दस्तावेज़ रूपांतरण बुनियादी परिदृश्यों के बारे में अधिक जानकारी: [दस्तावेज़ को 3 चरणों में कैसे बदलें](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* रूपांतरण उपयोग के उदाहरण, उन्नत सेटिंग और अनुकूलन: [दस्तावेज़ को उन्नत सेटिंग्स के साथ बदलें](https://docs.groupdocs.com/display/conversionnet/Converting)

### यह सभी देखें

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* नाम स्थान [GroupDocs.Conversion](../../converter)
* सभा [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_11}

स्रोत दस्तावेज़ को रूपांतरित करता है। परिवर्तित दस्तावेज़ पृष्ठ पृष्ठ द्वारा सहेजता है।

```csharp
public void Convert(Func<int, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Func`2 | प्रतिनिधि जो कनवर्ट किए गए दस्तावेज़ को स्ट्रीम में सहेजता है. पृष्ठ संख्या |
| convertOptionsProvider | Func`3 | कन्वर्ट विकल्प प्रदाता। वांछित लक्ष्य दस्तावेज़ प्रकार के लिए विशिष्ट रूपांतरण विकल्प प्रदान करने के लिए प्रत्येक रूपांतरण के लिए बुलाया जाएगा। फ़ाइल का नामफ़ाइल का प्रकार |

### टिप्पणियों

**और अधिक जानें**

* दस्तावेज़ रूपांतरण बुनियादी परिदृश्यों के बारे में अधिक जानकारी: [दस्तावेज़ को 3 चरणों में कैसे बदलें](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* रूपांतरण उपयोग के उदाहरण, उन्नत सेटिंग और अनुकूलन: [दस्तावेज़ को उन्नत सेटिंग्स के साथ बदलें](https://docs.groupdocs.com/display/conversionnet/Converting)

### यह सभी देखें

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* नाम स्थान [GroupDocs.Conversion](../../converter)
* सभा [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_10}

स्रोत दस्तावेज़ को रूपांतरित करता है। परिवर्तित दस्तावेज़ पृष्ठ पृष्ठ द्वारा सहेजता है।

```csharp
public void Convert(Func<int, Stream> document, Action<int, Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Func`2 | प्रतिनिधि जो रूपांतरित दस्तावेज़ पृष्ठ को स्ट्रीम में सहेजता है. पृष्ठ संख्या |
| documentCompleted | Action`3 | प्रतिनिधि जो परिवर्तित दस्तावेज़ पेज स्ट्रीम प्राप्त करता है। पृष्ठ संख्याफ़ाइल सामग्री स्ट्रीमफ़ाइल का नाम |
| convertOptionsProvider | Func`3 | कन्वर्ट विकल्प प्रदाता। वांछित लक्ष्य दस्तावेज़ प्रकार के लिए विशिष्ट रूपांतरण विकल्प प्रदान करने के लिए प्रत्येक रूपांतरण के लिए बुलाया जाएगा। फ़ाइल का नामफ़ाइल का प्रकार |

### टिप्पणियों

**और अधिक जानें**

* दस्तावेज़ रूपांतरण बुनियादी परिदृश्यों के बारे में अधिक जानकारी: [दस्तावेज़ को 3 चरणों में कैसे बदलें](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* रूपांतरण उपयोग के उदाहरण, उन्नत सेटिंग और अनुकूलन: [दस्तावेज़ को उन्नत सेटिंग्स के साथ बदलें](https://docs.groupdocs.com/display/conversionnet/Converting)

### यह सभी देखें

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* नाम स्थान [GroupDocs.Conversion](../../converter)
* सभा [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, ConvertOptions) {#convert_12}

स्रोत दस्तावेज़ को रूपांतरित करता है। परिवर्तित दस्तावेज़ पृष्ठ पृष्ठ द्वारा सहेजता है।

```csharp
public void Convert(Func<int, FileType, Stream> document, ConvertOptions convertOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Func`3 | प्रतिनिधि जो कनवर्ट किए गए दस्तावेज़ को स्ट्रीम में सहेजता है. पृष्ठ संख्या |
| convertOptions | ConvertOptions | वांछित लक्ष्य फ़ाइल प्रकार के लिए विशिष्ट कन्वर्ट विकल्प। |

### टिप्पणियों

**और अधिक जानें**

* दस्तावेज़ रूपांतरण बुनियादी परिदृश्यों के बारे में अधिक जानकारी: [दस्तावेज़ को 3 चरणों में कैसे बदलें](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* रूपांतरण उपयोग के उदाहरण, उन्नत सेटिंग और अनुकूलन: [दस्तावेज़ को उन्नत सेटिंग्स के साथ बदलें](https://docs.groupdocs.com/display/conversionnet/Converting)

### यह सभी देखें

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* नाम स्थान [GroupDocs.Conversion](../../converter)
* सभा [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) {#convert_13}

स्रोत दस्तावेज़ को रूपांतरित करता है। परिवर्तित दस्तावेज़ पृष्ठ पृष्ठ द्वारा सहेजता है।

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Action<int, Stream, string> documentCompleted, ConvertOptions convertOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Func`3 | प्रतिनिधि जो रूपांतरित दस्तावेज़ पृष्ठ को स्ट्रीम में सहेजता है. पृष्ठ संख्याफाइल का प्रकार |
| documentCompleted | Action`3 | प्रतिनिधि जो परिवर्तित दस्तावेज़ पेज स्ट्रीम प्राप्त करता है। पृष्ठ संख्याफ़ाइल सामग्री स्ट्रीमफ़ाइल का नाम |
| convertOptions | ConvertOptions | वांछित लक्ष्य फ़ाइल प्रकार के लिए विशिष्ट कन्वर्ट विकल्प। |

### टिप्पणियों

**और अधिक जानें**

* दस्तावेज़ रूपांतरण बुनियादी परिदृश्यों के बारे में अधिक जानकारी: [दस्तावेज़ को 3 चरणों में कैसे बदलें](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* रूपांतरण उपयोग के उदाहरण, उन्नत सेटिंग और अनुकूलन: [दस्तावेज़ को उन्नत सेटिंग्स के साथ बदलें](https://docs.groupdocs.com/display/conversionnet/Converting)

### यह सभी देखें

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* नाम स्थान [GroupDocs.Conversion](../../converter)
* सभा [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_15}

स्रोत दस्तावेज़ को रूपांतरित करता है। परिवर्तित दस्तावेज़ पृष्ठ पृष्ठ द्वारा सहेजता है।

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Func`3 | प्रतिनिधि जो कनवर्ट किए गए दस्तावेज़ को स्ट्रीम में सहेजता है. पृष्ठ संख्याफाइल का प्रकार |
| convertOptionsProvider | Func`3 | कन्वर्ट विकल्प प्रदाता। वांछित लक्ष्य दस्तावेज़ प्रकार के लिए विशिष्ट रूपांतरण विकल्प प्रदान करने के लिए प्रत्येक रूपांतरण के लिए बुलाया जाएगा। फ़ाइल का नामफ़ाइल का प्रकार |

### टिप्पणियों

**और अधिक जानें**

* दस्तावेज़ रूपांतरण बुनियादी परिदृश्यों के बारे में अधिक जानकारी: [दस्तावेज़ को 3 चरणों में कैसे बदलें](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* रूपांतरण उपयोग के उदाहरण, उन्नत सेटिंग और अनुकूलन: [दस्तावेज़ को उन्नत सेटिंग्स के साथ बदलें](https://docs.groupdocs.com/display/conversionnet/Converting)

### यह सभी देखें

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* नाम स्थान [GroupDocs.Conversion](../../converter)
* सभा [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_14}

स्रोत दस्तावेज़ को रूपांतरित करता है। परिवर्तित दस्तावेज़ पृष्ठ पृष्ठ द्वारा सहेजता है।

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Action<int, Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Func`3 | प्रतिनिधि जो रूपांतरित दस्तावेज़ पृष्ठ को स्ट्रीम में सहेजता है. पृष्ठ संख्याफाइल का प्रकार |
| documentCompleted | Action`3 | प्रतिनिधि जो परिवर्तित दस्तावेज़ पेज स्ट्रीम प्राप्त करता है। पृष्ठ संख्याफ़ाइल सामग्री स्ट्रीमफ़ाइल का नाम |
| convertOptionsProvider | Func`3 | कन्वर्ट विकल्प प्रदाता। वांछित लक्ष्य दस्तावेज़ प्रकार के लिए विशिष्ट रूपांतरण विकल्प प्रदान करने के लिए प्रत्येक रूपांतरण के लिए बुलाया जाएगा। फ़ाइल का नामफ़ाइल का प्रकार |

### टिप्पणियों

**और अधिक जानें**

* दस्तावेज़ रूपांतरण बुनियादी परिदृश्यों के बारे में अधिक जानकारी: [दस्तावेज़ को 3 चरणों में कैसे बदलें](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* रूपांतरण उपयोग के उदाहरण, उन्नत सेटिंग और अनुकूलन: [दस्तावेज़ को उन्नत सेटिंग्स के साथ बदलें](https://docs.groupdocs.com/display/conversionnet/Converting)

### यह सभी देखें

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* नाम स्थान [GroupDocs.Conversion](../../converter)
* सभा [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
