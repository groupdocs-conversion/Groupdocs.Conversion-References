---
title: "CadFileType"
second_title: "GroupDocs.Conversion for .NET API Reference"
description: "CAD दस्तावेज़ (Computer Aided Design) को परिभाषित करता है जो 3D ग्राफ़िक्स फ़ाइल फ़ॉर्मेट के लिए उपयोग होते हैं और 2D या 3D डिज़ाइन शामिल कर सकते हैं। निम्नलिखित प्रकार शामिल हैं Cf2./cadfiletype/cf2Dgn./cadfiletype/dgn Dwf./cadfiletype/dwf Dwfx./cadfiletype/dwfxDwg./cadfiletype/dwg Dwt./cadfiletype/dwt Dxf./cadfiletype/dxf Ifc./cadfiletype/ifc Igs./cadfiletype/igs Plt./cadfiletype/plt Stl./cadfiletype/stl. CAD फ़ॉर्मेट के बारे में अधिक जानें herehttps//wiki.fileformat.com/cad।"
type: docs
weight: 1070
url: /hi/net/groupdocs.conversion.filetypes/cadfiletype/
---
## CadFileType class

CAD दस्तावेज़ (Computer Aided Design) को परिभाषित करता है जो 3D ग्राफ़िक्स फ़ाइल फ़ॉर्मेट के लिए उपयोग होते हैं और 2D या 3D डिज़ाइन शामिल कर सकते हैं। निम्नलिखित प्रकार शामिल हैं: [`Cf2`](./cf2)[`Dgn`](./dgn), [`Dwf`](./dwf), [`Dwfx`](./dwfx)[`Dwg`](./dwg), [`Dwt`](./dwt), [`Dxf`](./dxf), [`Ifc`](./ifc), [`Igs`](./igs), [`Plt`](./plt), [`Stl`](./stl). CAD फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/cad)।

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
| static readonly [Cf2](../../groupdocs.conversion.filetypes/cadfiletype/cf2) | Common File Format File. CAD फ़ाइल जिसमें 3D पैकेज डिज़ाइन या अन्य मॉडल डेटा होते हैं; इसे CAD/CAM मशीन द्वारा प्रोसेस और कट किया जा सकता है, जैसे डाई कटिंग डिवाइस। |
| static readonly [Dgn](../../groupdocs.conversion.filetypes/cadfiletype/dgn) | DGN, Design, फ़ाइलें ड्रॉइंग हैं जो CAD अनुप्रयोगों जैसे माइक्रोस्टेशन और इंटरग्राफ इंटरएक्टिव ग्राफ़िक्स डिज़ाइन सिस्टम द्वारा बनाई और समर्थित होती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/cad/dgn)। |
| static readonly [Dwf](../../groupdocs.conversion.filetypes/cadfiletype/dwf) | Design Web Format (DWF) 2D/3D ड्रॉइंग को संकुचित फ़ॉर्मेट में दर्शाता है ताकि उसे देखा, समीक्षा किया या प्रिंट किया जा सके। इसमें ग्राफ़िक्स और टेक्स्ट डिज़ाइन डेटा का हिस्सा होते हैं और संकुचित फ़ॉर्मेट के कारण फ़ाइल का आकार घट जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/cad/dwf)। |
| static readonly [Dwfx](../../groupdocs.conversion.filetypes/cadfiletype/dwfx) | DWFX फ़ाइल Autodesk CAD सॉफ़्टवेयर से बनाई गई 2D या 3D ड्राइंग है। इसे DWFx फ़ॉर्मेट में सहेजा जाता है, जो . DWF फ़ाइल के समान है, लेकिन Microsoft के XML पेपर स्पेसिफिकेशन (XPS) का उपयोग करके फ़ॉर्मेट किया गया है। |
| static readonly [Dwg](../../groupdocs.conversion.filetypes/cadfiletype/dwg) | DWG एक्सटेंशन वाली फ़ाइलें स्वामित्व वाली बाइनरी फ़ाइलें हैं जो 2D और 3D डिज़ाइन डेटा को समाहित करने के लिए उपयोग होती हैं। DXF की तरह, जो ASCII फ़ाइलें हैं, DWG CAD (Computer Aided Design) ड्रॉइंग्स के लिए बाइनरी फ़ाइल फ़ॉर्मेट का प्रतिनिधित्व करती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://wiki.fileformat.com/cad/dwg). |
| static readonly [Dwt](../../groupdocs.conversion.filetypes/cadfiletype/dwt) | DWT फ़ाइल AutoCAD ड्रॉइंग टेम्प्लेट फ़ाइल है जो ड्रॉइंग्स बनाने के लिए शुरुआती रूप में उपयोग की जाती है, जिन्हें DWG फ़ाइलों के रूप में सहेजा जा सकता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://wiki.fileformat.com/cad/dwt). |
| static readonly [Dxf](../../groupdocs.conversion.filetypes/cadfiletype/dxf) | DXF, Drawing Interchange Format, या Drawing Exchange Format, AutoCAD ड्रॉइंग फ़ाइल का टैग्ड डेटा प्रतिनिधित्व है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://wiki.fileformat.com/cad/dxf). |
| static readonly [Ifc](../../groupdocs.conversion.filetypes/cadfiletype/ifc) | IFC एक्सटेंशन वाली फ़ाइलें Industry Foundation Classes (IFC) फ़ाइल फ़ॉर्मेट को दर्शाती हैं जो भवन वस्तुओं और उनकी प्रॉपर्टीज़ को आयात और निर्यात करने के लिए अंतर्राष्ट्रीय मानक स्थापित करती हैं। यह फ़ाइल फ़ॉर्मेट विभिन्न सॉफ़्टवेयर अनुप्रयोगों के बीच इंटरऑपरेबिलिटी प्रदान करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://wiki.fileformat.com/cad/ifc). |
| static readonly [Igs](../../groupdocs.conversion.filetypes/cadfiletype/igs) | Igs दस्तावेज़ फ़ॉर्मेट |
| static readonly [Plt](../../groupdocs.conversion.filetypes/cadfiletype/plt) | PLT फ़ाइल फ़ॉर्मेट Autodesk, Inc. द्वारा प्रस्तुत एक वेक्टर-आधारित प्लॉटर फ़ाइल है और यह किसी विशेष CAD फ़ाइल की जानकारी रखती है। प्लॉटिंग विवरणों को उत्पादन में सटीकता और परिशुद्धता की आवश्यकता होती है, और PLT फ़ाइल का उपयोग यह सुनिश्चित करता है क्योंकि सभी छवियां बिंदुओं के बजाय रेखाओं से प्रिंट की जाती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://wiki.fileformat.com/cad/plt). |
| static readonly [Stl](../../groupdocs.conversion.filetypes/cadfiletype/stl) | STL, stereolithrography का संक्षिप्त रूप, एक इंटरचेंजेबल फ़ाइल फ़ॉर्मेट है जो 3-आयामी सतह ज्यामिति को दर्शाता है। यह फ़ॉर्मेट तेज़ प्रोटोटाइपिंग, 3D प्रिंटिंग और कंप्यूटर-एडेड मैन्युफैक्चरिंग जैसे कई क्षेत्रों में उपयोग पाया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://wiki.fileformat.com/cad/stl). |

### देखें भी

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
