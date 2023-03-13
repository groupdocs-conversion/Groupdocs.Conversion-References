---
title: CadFileType
second_title: .NET API संदर्भ के लिए GroupDocs.Conversion
description: CAD दस्तवेज़ कंप्यूटर एडेड डज़इन क परभषत करत है ज 3D ग्रफ़क्स फ़इल स्वरूपं के लए उपयग कय जत है और इसमें 2D य 3D डज़इन ह सकते हैं में नम्न प्रकर शमल हैं Cf2./cadfiletype/cf2Dgn./cadfiletype/dgn  Dwf./cadfiletype/dwf  Dwfx./cadfiletype/dwfxDwg./cadfiletype/dwg  Dwt./cadfiletype/dwt  Dxf./cadfiletype/dxf  Ifc./cadfiletype/ifc  Igs./cadfiletype/igs  Plt./cadfiletype/plt  Stl./cadfiletype/stl . सएड प्ररूपं के बरे में अधक जनेंयहँhttps//wiki.fileformat.com/cad .
type: docs
weight: 860
url: /hi/net/groupdocs.conversion.filetypes/cadfiletype/
---
## CadFileType class

CAD दस्तावेज़ (कंप्यूटर एडेड डिज़ाइन) को परिभाषित करता है जो 3D ग्राफ़िक्स फ़ाइल स्वरूपों के लिए उपयोग किया जाता है और इसमें 2D या 3D डिज़ाइन हो सकते हैं। में निम्न प्रकार शामिल हैं: [`Cf2`](./cf2)[`Dgn`](./dgn) , [`Dwf`](./dwf) , [`Dwfx`](./dwfx)[`Dwg`](./dwg) , [`Dwt`](./dwt) , [`Dxf`](./dxf) , [`Ifc`](./ifc) , [`Igs`](./igs) , [`Plt`](./plt) , [`Stl`](./stl) . सीएडी प्रारूपों के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/cad) .

```csharp
public sealed class CadFileType : FileType
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [CadFileType](cadfiletype)() | सीरियलाइज़ेशन कंस्ट्रक्टर |

## गुण

| नाम | विवरण |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | फ़ाइल प्रकार विवरण |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | फ़ाइल एक्सटेंशन |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | फ़ाइल परिवार |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | फ़ाइल स्वरूप |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | वर्तमान वस्तु की तुलना अन्य से करता है। |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | निर्धारित करता है कि क्या दो वस्तु उदाहरण समान हैं। |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | निर्धारित करता है कि क्या दो वस्तु उदाहरण समान हैं। |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | डिफ़ॉल्ट हैश फ़ंक्शन के रूप में कार्य करता है। |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | स्ट्रिंग प्रतिनिधित्व |

## खेत

| नाम | विवरण |
| --- | --- |
| static readonly [Cf2](../../groupdocs.conversion.filetypes/cadfiletype/cf2) | सामान्य फ़ाइल स्वरूप फ़ाइल। CAD फ़ाइल जिसमें 3D पैकेज डिज़ाइन या अन्य मॉडल डेटा होता है; सीएडी/सीएएम मशीन द्वारा संसाधित और काटा जा सकता है, जैसे डाई कटिंग डिवाइस. |
| static readonly [Dgn](../../groupdocs.conversion.filetypes/cadfiletype/dgn) | DGN, डिज़ाइन, फ़ाइलें माइक्रोस्टेशन और इंटरग्राफ इंटरएक्टिव ग्राफ़िक्स डिज़ाइन सिस्टम जैसे CAD ऐप्लिकेशन द्वारा बनाई और समर्थित ड्रॉइंग हैं. इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/cad/dgn) . |
| static readonly [Dwf](../../groupdocs.conversion.filetypes/cadfiletype/dwf) | डिज़ाइन वेब फ़ॉर्मेट (DWF) डिज़ाइन फ़ाइलों को देखने, समीक्षा करने या प्रिंट करने के लिए संकुचित प्रारूप में 2D/3D ड्राइंग का प्रतिनिधित्व करता है। इसमें डिज़ाइन डेटा के हिस्से के रूप में ग्राफ़िक्स और टेक्स्ट शामिल हैं और इसके कंप्रेस्ड फ़ॉर्मेट के कारण फ़ाइल के आकार को कम करते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/cad/dwf) . |
| static readonly [Dwfx](../../groupdocs.conversion.filetypes/cadfiletype/dwfx) | DWFX फ़ाइल एक 2D या 3D ड्राइंग है जिसे Autodesk CAD सॉफ़्टवेयर के साथ बनाया गया है। यह DWFx प्रारूप में सहेजा जाता है, जो एक . DWF फ़ाइल, लेकिन Microsoft के XML पेपर स्पेसिफिकेशन (XPS) का उपयोग करके स्वरूपित किया गया है। |
| static readonly [Dwg](../../groupdocs.conversion.filetypes/cadfiletype/dwg) | DWG एक्सटेंशन वाली फाइलें 2डी और 3डी डिजाइन डेटा रखने के लिए उपयोग की जाने वाली मालिकाना बाइनरी फाइलों का प्रतिनिधित्व करती हैं। DXF की तरह, जो ASCII फाइलें हैं, DWG CAD (कंप्यूटर एडेड डिजाइन) ड्रॉइंग के लिए बाइनरी फाइल फॉर्मेट का प्रतिनिधित्व करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/cad/dwg) . |
| static readonly [Dwt](../../groupdocs.conversion.filetypes/cadfiletype/dwt) | एक डीडब्ल्यूटी फ़ाइल एक ऑटोकैड ड्राइंग टेम्पलेट फ़ाइल है जिसका उपयोग ऐसे चित्र बनाने के लिए स्टार्टर के रूप में किया जाता है जिन्हें डीडब्ल्यूजी फाइलों के रूप में सहेजा जा सकता है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/cad/dwt) . |
| static readonly [Dxf](../../groupdocs.conversion.filetypes/cadfiletype/dxf) | DXF, ड्रॉइंग इंटरचेंज फ़ॉर्मेट, या ड्रॉइंग एक्सचेंज फ़ॉर्मेट, ऑटोकैड ड्रॉइंग फ़ाइल का टैग किया गया डेटा प्रतिनिधित्व है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/cad/dxf) . |
| static readonly [Ifc](../../groupdocs.conversion.filetypes/cadfiletype/ifc) | IFC एक्सटेंशन वाली फाइलें इंडस्ट्री फाउंडेशन क्लासेस (IFC) फाइल फॉर्मेट को संदर्भित करती हैं जो बिल्डिंग ऑब्जेक्ट्स और उनकी संपत्तियों को आयात और निर्यात करने के लिए अंतर्राष्ट्रीय मानक स्थापित करती हैं। यह फ़ाइल स्वरूप विभिन्न सॉफ़्टवेयर अनुप्रयोगों के बीच अंतःक्रियाशीलता प्रदान करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/cad/ifc) . |
| static readonly [Igs](../../groupdocs.conversion.filetypes/cadfiletype/igs) | आईजीएस दस्तावेज़ स्वरूप |
| static readonly [Plt](../../groupdocs.conversion.filetypes/cadfiletype/plt) | PLT फ़ाइल स्वरूप एक वेक्टर-आधारित प्लॉटर फ़ाइल है जिसे Autodesk, Inc. द्वारा प्रस्तुत किया गया है और इसमें एक निश्चित CAD फ़ाइल के लिए जानकारी शामिल है। प्लॉटिंग विवरण के लिए उत्पादन में सटीकता और सटीकता की आवश्यकता होती है, और पीएलटी फ़ाइल का उपयोग इसकी गारंटी देता है क्योंकि सभी छवियां डॉट्स के बजाय लाइनों का उपयोग करके मुद्रित की जाती हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/cad/plt) . |
| static readonly [Stl](../../groupdocs.conversion.filetypes/cadfiletype/stl) | STL, स्टीरियोलिथ्रोग्राफी के लिए संक्षिप्त नाम, एक विनिमेय फ़ाइल प्रारूप है जो 3-आयामी सतह ज्यामिति का प्रतिनिधित्व करता है। फ़ाइल स्वरूप का उपयोग कई क्षेत्रों में किया जाता है, जैसे रैपिड प्रोटोटाइपिंग, 3डी प्रिंटिंग और कंप्यूटर-एडेड निर्माण। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/cad/stl) . |

### यह सभी देखें

* class [FileType](../filetype)
* नाम स्थान [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* सभा [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
