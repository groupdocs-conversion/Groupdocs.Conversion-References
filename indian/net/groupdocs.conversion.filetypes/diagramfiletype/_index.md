---
title: "DiagramFileType"
second_title: "GroupDocs.Conversion for .NET API Reference"
description: "Diagram दस्तावेज़ों को परिभाषित करता है। निम्नलिखित प्रकार शामिल हैं Drawio./diagramfiletype/drawio Mmd./diagramfiletype/mmd Vdw./diagramfiletype/vdw Vdx./diagramfiletype/vdx Vsd./diagramfiletype/vsd Vsdm./diagramfiletype/vsdm Vsdx./diagramfiletype/vsdx Vss./diagramfiletype/vss Vssm./diagramfiletype/vssm Vssx./diagramfiletype/vssx Vst./diagramfiletype/vst Vstm./diagramfiletype/vstm Vstx./diagramfiletype/vstx Vsx./diagramfiletype/vsx Vtx./diagramfiletype/vtx."
type: docs
weight: 1100
url: /hi/net/groupdocs.conversion.filetypes/diagramfiletype/
---
## DiagramFileType class

Diagram दस्तावेज़ों को परिभाषित करता है। निम्नलिखित प्रकार शामिल हैं: [`Drawio`](./drawio), [`Mmd`](./mmd), [`Vdw`](./vdw), [`Vdx`](./vdx), [`Vsd`](./vsd), [`Vsdm`](./vsdm), [`Vsdx`](./vsdx), [`Vss`](./vss), [`Vssm`](./vssm), [`Vssx`](./vssx), [`Vst`](./vst), [`Vstm`](./vstm), [`Vstx`](./vstx), [`Vsx`](./vsx), [`Vtx`](./vtx).

```csharp
public sealed class DiagramFileType : FileType
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [DiagramFileType](diagramfiletype)() | सीरियलाइज़ेशन कंस्ट्रक्टर |

## गुण

| नाम | विवरण |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | फ़ाइल प्रकार विवरण |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | फ़ाइल एक्सटेंशन |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | फ़ाइल परिवार |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | फ़ाइल फ़ॉर्मेट |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | वर्तमान ऑब्जेक्ट की तुलना अन्य से करता है। |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) को लागू करता है। |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | निर्धारित करता है कि दो ऑब्जेक्ट इंस्टेंस समान हैं या नहीं। |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | डिफ़ॉल्ट हैश फ़ंक्शन के रूप में कार्य करता है। |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | स्ट्रिंग प्रतिनिधित्व |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| static readonly [Drawio](../../groupdocs.conversion.filetypes/diagramfiletype/drawio) | DRAWIO एक्सटेंशन वाली फ़ाइल diagrams.net (पूर्व में draw.io) द्वारा बनाई गई एक डायग्राम है। यह XML फ़ाइल फ़ॉर्मेट में mxfile रूट एलिमेंट के साथ संग्रहीत होती है और डायग्राम तत्वों जैसे टेक्स्ट, छवियां, लेआउट, आकार और पोजिशनिंग की सामग्री और फ़ॉर्मेटिंग रखती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here](https://wiki.fileformat.com/web/drawio)। |
| static readonly [Mmd](../../groupdocs.conversion.filetypes/diagramfiletype/mmd) | MMD एक्सटेंशन वाली फ़ाइल Mermaid मार्कअप भाषा में लिखी गई एक डायग्राम है। यह एक साधारण टेक्स्ट दस्तावेज़ के रूप में संग्रहीत होती है जो डायग्राम घोषणा से शुरू होती है, जैसे flowchart या sequenceDiagram, उसके बाद नोड्स की परिभाषा और उनके बीच के कनेक्शन होते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here](https://mermaid.js.org/intro/)। |
| static readonly [Vdw](../../groupdocs.conversion.filetypes/diagramfiletype/vdw) | VDW Visio ग्राफ़िक्स सर्विस फ़ाइल फ़ॉर्मेट है जो वेब ड्रॉइंग को रेंडर करने के लिए आवश्यक स्ट्रीम और स्टोरेज को निर्दिष्ट करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here](https://wiki.fileformat.com/web/vdw)। |
| static readonly [Vdx](../../groupdocs.conversion.filetypes/diagramfiletype/vdx) | Microsoft Visio में बनाया गया कोई भी ड्रॉइंग या चार्ट, लेकिन XML फ़ॉर्मेट में सहेजा गया हो, .VDX एक्सटेंशन रखता है। Visio सॉफ़्टवेयर, जो Microsoft द्वारा विकसित किया गया है, में Visio ड्रॉइंग XML फ़ाइल बनाई जाती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here](https://wiki.fileformat.com/image/vdx)। |
| static readonly [Vsd](../../groupdocs.conversion.filetypes/diagramfiletype/vsd) | VSD फ़ाइलें Microsoft Visio एप्लिकेशन द्वारा बनाई गई ड्रॉइंग हैं जो विभिन्न ग्राफ़िकल ऑब्जेक्ट्स और उनके बीच के इंटरकनेक्शन को दर्शाती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here](https://wiki.fileformat.com/image/vsd)। |
| static readonly [Vsdm](../../groupdocs.conversion.filetypes/diagramfiletype/vsdm) | VSDM एक्सटेंशन वाली फ़ाइलें ड्रॉइंग फ़ाइलें हैं जो Microsoft Visio एप्लिकेशन द्वारा बनाई गई हैं और मैक्रो का समर्थन करती हैं। VSDM फ़ाइलें OPC/XML ड्रॉइंग हैं जो VSDX के समान हैं, लेकिन फ़ाइल खोलने पर मैक्रो चलाने की क्षमता भी प्रदान करती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://wiki.fileformat.com/image/vsdm). |
| static readonly [Vsdx](../../groupdocs.conversion.filetypes/diagramfiletype/vsdx) | VSDX एक्सटेंशन वाली फ़ाइलें Microsoft Visio फ़ाइल फ़ॉर्मेट को दर्शाती हैं, जिसे Microsoft Office 2013 से आगे पेश किया गया था। इसे बाइनरी फ़ाइल फ़ॉर्मेट .VSD को बदलने के लिए विकसित किया गया था, जो Microsoft Visio के पुराने संस्करणों द्वारा समर्थित था। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://wiki.fileformat.com/image/vsdx). |
| static readonly [Vss](../../groupdocs.conversion.filetypes/diagramfiletype/vss) | VSS स्टेंसिल फ़ाइलें हैं जो Microsoft Visio 2007 और उससे पहले के संस्करणों द्वारा बनाई गई थीं। स्टेंसिल फ़ाइलें ड्रॉइंग ऑब्जेक्ट्स प्रदान करती हैं जिन्हें .VSD Visio ड्रॉइंग में शामिल किया जा सकता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://wiki.fileformat.com/image/vss). |
| static readonly [Vssm](../../groupdocs.conversion.filetypes/diagramfiletype/vssm) | .VSSM एक्सटेंशन वाली फ़ाइलें Microsoft Visio स्टेंसिल फ़ाइलें हैं जो मैक्रो का समर्थन करती हैं। जब VSSM फ़ाइल को खोला जाता है, तो यह मैक्रो चलाने की अनुमति देती है ताकि आरेख में आकृतियों का वांछित फ़ॉर्मेटिंग और प्लेसमेंट प्राप्त किया जा सके। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://wiki.fileformat.com/image/vssm). |
| static readonly [Vssx](../../groupdocs.conversion.filetypes/diagramfiletype/vssx) | .VSSX एक्सटेंशन वाली फ़ाइलें ड्रॉइंग स्टेंसिल हैं जो Microsoft Visio 2013 और उसके बाद के संस्करणों द्वारा बनाई गई हैं। VSSX फ़ाइल फ़ॉर्मेट को Visio 2013 और उसके बाद के संस्करणों में खोला जा सकता है। Visio फ़ाइलें विभिन्न ड्रॉइंग तत्वों जैसे आकृतियों का संग्रह, कनेक्टर, फ्लोचार्ट, नेटवर्क लेआउट, UML आरेख आदि के प्रतिनिधित्व के लिए जानी जाती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://wiki.fileformat.com/image/vssx). |
| static readonly [Vst](../../groupdocs.conversion.filetypes/diagramfiletype/vst) | VST एक्सटेंशन वाली फ़ाइलें वेक्टर इमेज फ़ाइलें हैं जो Microsoft Visio द्वारा बनाई गई हैं और आगे की फ़ाइलें बनाने के लिए टेम्प्लेट के रूप में कार्य करती हैं। ये टेम्प्लेट फ़ाइलें बाइनरी फ़ाइल फ़ॉर्मेट में होती हैं और डिफ़ॉल्ट लेआउट और सेटिंग्स शामिल करती हैं जो नई Visio ड्रॉइंग बनाने में उपयोग की जाती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://wiki.fileformat.com/image/vst). |
| static readonly [Vstm](../../groupdocs.conversion.filetypes/diagramfiletype/vstm) | VSTM एक्सटेंशन वाली फ़ाइलें टेम्प्लेट फ़ाइलें हैं जो Microsoft Visio द्वारा बनाई गई हैं और मैक्रो का समर्थन करती हैं। VSDX फ़ाइलों के विपरीत, VSTM टेम्प्लेट से बनाई गई फ़ाइलें Visual Basic for Applications (VBA) कोड में विकसित मैक्रो चला सकती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://wiki.fileformat.com/image/vstm). |
| static readonly [Vstx](../../groupdocs.conversion.filetypes/diagramfiletype/vstx) | VSTX एक्सटेंशन वाली फ़ाइलें ड्रॉइंग टेम्प्लेट फ़ाइलें हैं जो Microsoft Visio 2013 और उसके बाद के संस्करणों द्वारा बनाई गई हैं। ये VSTX फ़ाइलें Visio ड्रॉइंग बनाने के लिए प्रारंभिक बिंदु प्रदान करती हैं, जो .VSDX फ़ाइलों के रूप में सहेजी जाती हैं, और डिफ़ॉल्ट लेआउट और सेटिंग्स रखती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://wiki.fileformat.com/image/vstx). |
| static readonly [Vsx](../../groupdocs.conversion.filetypes/diagramfiletype/vsx) | .VSX एक्सटेंशन वाली फ़ाइलें स्टेंसिल को दर्शाती हैं जिनमें ड्रॉइंग और आकृतियाँ होती हैं जो Microsoft Visio में आरेख बनाने के लिए उपयोग की जाती हैं। VSX फ़ाइलें XML फ़ाइल फ़ॉर्मेट में सहेजी जाती हैं और Visio 2013 तक समर्थित थीं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://wiki.fileformat.com/image/vsx). |
| static readonly [Vtx](../../groupdocs.conversion.filetypes/diagramfiletype/vtx) | VTX एक्सटेंशन वाली फ़ाइल एक Microsoft Visio ड्रॉइंग टेम्प्लेट है जो XML फ़ाइल फ़ॉर्मेट में डिस्क पर सहेजा जाता है। यह टेम्प्लेट मूल सेटिंग्स वाली फ़ाइल प्रदान करने के लिए बनाया गया है जिसे समान सेटिंग्स वाली कई Visio फ़ाइलें बनाने में उपयोग किया जा सकता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://wiki.fileformat.com/image/vtx). |

### देखें भी

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
