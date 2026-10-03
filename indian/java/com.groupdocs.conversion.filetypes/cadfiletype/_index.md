---
title: "CadFileType"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "CAD दस्तावेज़ (Computer Aided Design) को परिभाषित करता है, जो 3D ग्राफ़िक्स फ़ाइल फ़ॉर्मेट के लिए उपयोग होते हैं और 2D या 3D डिज़ाइन शामिल कर सकते हैं।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.conversion.filetypes/cadfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CadFileType extends FileType implements Serializable
```

CAD दस्तावेज़ (Computer Aided Design) को परिभाषित करता है जो 3d ग्राफ़िक्स फ़ाइल फ़ॉर्मेट के लिए उपयोग होते हैं और 2d या 3d डिज़ाइन शामिल कर सकते हैं।
निम्नलिखित प्रकार शामिल हैं:
[Dgn](../../com.groupdocs.conversion.filetypes/cadfiletype#Dgn),
[Dwf](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwf),
[Dwg](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwg),
[Dwt](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwt),
[Dxf](../../com.groupdocs.conversion.filetypes/cadfiletype#Dxf),
[Ifc](../../com.groupdocs.conversion.filetypes/cadfiletype#Ifc),
[Igs](../../com.groupdocs.conversion.filetypes/cadfiletype#Igs),
[Plt](../../com.groupdocs.conversion.filetypes/cadfiletype#Plt),
[Stl](../../com.groupdocs.conversion.filetypes/cadfiletype#Stl).
[Cf2](../../com.groupdocs.conversion.filetypes/cadfiletype#Cf2).
[Dwfx](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwfx).
CAD फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](../https://wiki.fileformat.com/cad).

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [CadFileType()](#CadFileType--) | सीरियलाइज़ेशन कंस्ट्रक्टर |
|
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
|  | [Dxf](#Dxf) | DXF, Drawing Interchange Format, या Drawing Exchange Format, AutoCAD ड्राइंग फ़ाइल का टैग्ड डेटा प्रतिनिधित्व है। |
|
|  | [Dwg](#Dwg) | DWG एक्सटेंशन वाली फ़ाइलें 2D और 3D डिज़ाइन डेटा को समाहित करने के लिए उपयोग की जाने वाली स्वामित्व बाइनरी फ़ाइलें हैं। |
|
|  | [Dgn](#Dgn) | DGN, Design, फ़ाइलें उन ड्रॉइंग्स को दर्शाती हैं जो MicroStation और Intergraph Interactive Graphics Design System जैसे CAD अनुप्रयोगों द्वारा बनाई और समर्थित होती हैं। |
|
|  | [Dwf](#Dwf) | Design Web Format (DWF) 2D/3D ड्रॉइंग को संकुचित फ़ॉर्मेट में दर्शाता है, जिससे डिज़ाइन फ़ाइलों को देखना, समीक्षा करना या प्रिंट करना संभव हो। |
|
|  | [Stl](#Stl) | STL, stereolithrography का संक्षिप्त रूप, एक इंटरचेंजेबल फ़ाइल फ़ॉर्मेट है जो 3-आयामी सतह ज्यामिति को दर्शाता है। |
|
|  | [Ifc](#Ifc) | IFC एक्सटेंशन वाली फ़ाइलें Industry Foundation Classes (IFC) फ़ाइल फ़ॉर्मेट को संदर्भित करती हैं, जो भवन वस्तुओं और उनकी विशेषताओं को आयात और निर्यात करने के लिए अंतर्राष्ट्रीय मानक स्थापित करती हैं। |
|
|  | [Plt](#Plt) | PLT फ़ाइल फ़ॉर्मेट Autodesk, Inc. द्वारा प्रस्तुत एक वेक्टर-आधारित प्लॉटर फ़ाइल है। |
|
|  | [Igs](#Igs) | Igs दस्तावेज़ फ़ॉर्मेट |
|
|  | [Dwt](#Dwt) | DWT फ़ाइल AutoCAD ड्रॉइंग टेम्पलेट फ़ाइल है, जिसका उपयोग उन ड्रॉइंग्स को शुरू करने के लिए किया जाता है जिन्हें DWG फ़ाइलों के रूप में सहेजा जा सकता है। |
|
|  | [Dwfx](#Dwfx) | DWFX फ़ाइल Autodesk CAD सॉफ़्टवेयर से बनाई गई 2D या 3D ड्रॉइंग है। |
|
|  | [Cf2](#Cf2) | कॉमन फ़ाइल फ़ॉर्मेट फ़ाइल। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### CadFileType() {#CadFileType--}
```
public CadFileType()
```


सीरियलाइज़ेशन कंस्ट्रक्टर


### Dxf {#Dxf}
```
public static final CadFileType Dxf
```


DXF, Drawing Interchange Format, या Drawing Exchange Format, AutoCAD ड्राइंग फ़ाइल का टैग्ड डेटा प्रतिनिधित्व है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](../https://wiki.fileformat.com/cad/dxf).


### Dwg {#Dwg}
```
public static final CadFileType Dwg
```


DWG एक्सटेंशन वाली फ़ाइलें 2D और 3D डिज़ाइन डेटा को समाहित करने के लिए उपयोग की जाने वाली स्वामित्व बाइनरी फ़ाइलें हैं। DXF की तरह, जो ASCII फ़ाइलें हैं, DWG CAD (Computer Aided Design) ड्रॉइंग्स के लिए बाइनरी फ़ाइल फ़ॉर्मेट का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](../https://wiki.fileformat.com/cad/dwg)


### Dgn {#Dgn}
```
public static final CadFileType Dgn
```


DGN, Design, फ़ाइलें उन ड्रॉइंग्स को दर्शाती हैं जो MicroStation और Intergraph Interactive Graphics Design System जैसे CAD अनुप्रयोगों द्वारा बनाई और समर्थित होती हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](../https://wiki.fileformat.com/cad/dgn).


### Dwf {#Dwf}
```
public static final CadFileType Dwf
```


Design Web Format (DWF) 2D/3D ड्रॉइंग को संकुचित प्रारूप में दर्शाने, समीक्षा करने या डिज़ाइन फ़ाइलों को प्रिंट करने के लिए प्रस्तुत करता है। यह डिज़ाइन डेटा के हिस्से के रूप में ग्राफ़िक्स और टेक्स्ट शामिल करता है और इसके संकुचित प्रारूप के कारण फ़ाइल का आकार कम करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/cad/dwf).


### Stl {#Stl}
```
public static final CadFileType Stl
```


STL, stereolithrography का संक्षिप्त रूप, एक इंटरचेंजेबल फ़ाइल फ़ॉर्मेट है जो 3-आयामी सतह ज्यामिति को दर्शाता है। यह फ़ाइल फ़ॉर्मेट तेज़ प्रोटोटाइपिंग, 3D प्रिंटिंग और कंप्यूटर‑सहायता निर्मा‍ण जैसे कई क्षेत्रों में उपयोग पाया है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/cad/stl).


### Ifc {#Ifc}
```
public static final CadFileType Ifc
```


IFC एक्सटेंशन वाली फ़ाइलें Industry Foundation Classes (IFC) फ़ाइल फ़ॉर्मेट को दर्शाती हैं जो भवन वस्तुओं और उनकी गुणधर्मों को आयात और निर्यात करने के लिए अंतरराष्ट्रीय मानक स्थापित करती हैं। यह फ़ाइल फ़ॉर्मेट विभिन्न सॉफ़्टवेयर अनुप्रयोगों के बीच अंतःक्रियाशीलता प्रदान करती है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/cad/ifc).


### Plt {#Plt}
```
public static final CadFileType Plt
```


PLT फ़ाइल फ़ॉर्मेट Autodesk, Inc. द्वारा प्रस्तुत एक वेक्टर‑आधारित प्लॉटर फ़ाइल है और यह किसी विशिष्ट CAD फ़ाइल की जानकारी रखती है। प्लॉटिंग विवरणों को उत्पादन में शुद्धता और सटीकता की आवश्यकता होती है, और PLT फ़ाइल का उपयोग यह सुनिश्चित करता है क्योंकि सभी छवियां बिंदुओं के बजाय रेखाओं से प्रिंट की जाती हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/cad/plt).


### Igs {#Igs}
```
public static final CadFileType Igs
```


Igs दस्तावेज़ फ़ॉर्मेट


### Dwt {#Dwt}
```
public static final CadFileType Dwt
```


DWT फ़ाइल AutoCAD ड्रॉइंग टेम्पलेट फ़ाइल है, जिसका उपयोग उन ड्रॉइंग्स को शुरू करने के लिए किया जाता है जिन्हें DWG फ़ाइलों के रूप में सहेजा जा सकता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/cad/dwt).


### Dwfx {#Dwfx}
```
public static final CadFileType Dwfx
```


DWFX फ़ाइल Autodesk CAD सॉफ़्टवेयर से निर्मित 2D या 3D ड्रॉइंग है। यह DWFx प्रारूप में सहेजी जाती है, जो .DWF फ़ाइल के समान है, लेकिन Microsoft के XML Paper Specification (XPS) का उपयोग करके स्वरूपित की गई है।


### Cf2 {#Cf2}
```
public static final CadFileType Cf2
```


Common File Format फ़ाइल। CAD फ़ाइल जिसमें 3D पैकेज डिज़ाइन या अन्य मॉडल डेटा शामिल है; इसे CAD/CAM मशीन, जैसे डाई कटिंग डिवाइस, द्वारा प्रोसेस और कट किया जा सकता है।


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


स्रोत फ़ाइल प्रकार के लिए डिफ़ॉल्ट लोड विकल्प तैयार किए गए


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


फ़ाइल प्रकार के लिए डिफ़ॉल्ट रूपांतरण विकल्प तैयार किए गए


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
