---
title: "ThreeDFileType"
second_title: "GroupDocs.Conversion for .NET API Reference"
description: "3D दस्तावेज़ों को परिभाषित करता है निम्नलिखित प्रकार शामिल हैं Fbx./threedfiletype/fbxThreeDS./threedfiletype/threedsThreeMF./threedfiletype/threemfAmf./threedfiletype/amfAse./threedfiletype/aseRvm./threedfiletype/rvmDae./threedfiletype/daeDrc./threedfiletype/drcGltf./threedfiletype/gltfObj./threedfiletype/objPly./threedfiletype/plyJt./threedfiletype/jtU3d./threedfiletype/u3dUsd./threedfiletype/usdUsdz./threedfiletype/usdzVrml./threedfiletype/vrmlX./threedfiletype/xGlb./threedfiletype/glbMa./threedfiletype/maMb./threedfiletype/mb 3D फ़ॉर्मेट्स के बारे में अधिक जानने के लिए यहाँhttps//wiki.fileformat.com/3d."
type: docs
weight: 1250
url: /hi/net/groupdocs.conversion.filetypes/threedfiletype/
---
## ThreeDFileType class

3D दस्तावेज़ों को परिभाषित करता है निम्नलिखित प्रकार शामिल हैं: [`Fbx`](./fbx)[`ThreeDS`](./threeds)[`ThreeMF`](./threemf)[`Amf`](./amf)[`Ase`](./ase)[`Rvm`](./rvm)[`Dae`](./dae)[`Drc`](./drc)[`Gltf`](./gltf)[`Obj`](./obj)[`Ply`](./ply)[`Jt`](./jt)[`U3d`](./u3d)[`Usd`](./usd)[`Usdz`](./usdz)[`Vrml`](./vrml)[`X`](./x)[`Glb`](./glb)[`Ma`](./ma)[`Mb`](./mb) 3D फ़ॉर्मेट्स के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/3d).

```csharp
public sealed class ThreeDFileType : FileType
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [ThreeDFileType](threedfiletype)() | सीरियलाइज़ेशन कंस्ट्रक्टर |

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
| static readonly [Amf](../../groupdocs.conversion.filetypes/threedfiletype/amf) | एक AMF फ़ाइल वस्तुओं के विवरण के लिए दिशानिर्देशों से बनी होती है ताकि इसे एडिटिव मैन्युफैक्चरिंग प्रक्रियाओं में उपयोग किया जा सके। यह एक प्रारंभिक XML टैग रखती है और एक तत्व के साथ समाप्त होती है। इसके पहले एक XML घोषणा पंक्ति होती है जो फ़ाइल के XML संस्करण और एन्कोडिंग को निर्दिष्ट करती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/3d/amf). |
| static readonly [Ase](../../groupdocs.conversion.filetypes/threedfiletype/ase) | .ase एक्सटेंशन वाली फ़ाइल Autodesk ASCII सीन एक्सपोर्ट फ़ाइल फ़ॉर्मेट है जो सीन का ASCII प्रतिनिधित्व है, जिसमें 2D या 3D जानकारी होती है जबकि Autodesk का उपयोग करके सीन डेटा निर्यात किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/3d/ase). |
| static readonly [Dae](../../groupdocs.conversion.filetypes/threedfiletype/dae) | एक DAE फ़ाइल डिजिटल एसेट एक्सचेंज फ़ाइल फ़ॉर्मेट है जो इंटरैक्टिव 3D अनुप्रयोगों के बीच डेटा का आदान‑प्रदान करने के लिए उपयोग की जाती है। यह फ़ाइल फ़ॉर्मेट COLLADA (COLLAborative Design Activity) XML स्कीमा पर आधारित है, जो ग्राफ़िक्स सॉफ़्टवेयर अनुप्रयोगों के बीच डिजिटल एसेट्स के आदान‑प्रदान के लिए एक ओपन स्टैंडर्ड XML स्कीमा है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/3d/dae). |
| static readonly [Drc](../../groupdocs.conversion.filetypes/threedfiletype/drc) | .drc एक्सटेंशन वाली फ़ाइल Google Draco लाइब्रेरी द्वारा बनाई गई एक संकुचित 3D फ़ाइल फ़ॉर्मेट है। Google Draco को 3D ज्यामितीय मेष और पॉइंट क्लाउड को संपीड़ित और डिकम्प्रेस करने के लिए एक ओपन सोर्स लाइब्रेरी के रूप में प्रदान करता है, और 3D ग्राफ़िक्स के संग्रहण और ट्रांसमिशन को बेहतर बनाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/3d/drc). |
| static readonly [Fbx](../../groupdocs.conversion.filetypes/threedfiletype/fbx) | FBX, FilmBox, एक लोकप्रिय 3D फ़ाइल फ़ॉर्मेट है जिसे मूल रूप से Kaydara ने MotionBuilder के लिए विकसित किया था। इसे 2006 में Autodesk Inc ने अधिग्रहित किया और अब यह कई 3D टूल्स द्वारा उपयोग किए जाने वाले मुख्य 3D एक्सचेंज फ़ॉर्मेट्स में से एक है। FBX बाइनरी और ASCII दोनों फ़ाइल फ़ॉर्मेट में उपलब्ध है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/3d/fbx). |
| static readonly [Glb](../../groupdocs.conversion.filetypes/threedfiletype/glb) | GLB, GL ट्रांसमिशन फ़ॉर्मेट (glTF) में सहेजे गए 3D मॉडल्स का बाइनरी फ़ाइल फ़ॉर्मेट प्रतिनिधित्व है। यह बाइनरी फ़ॉर्मेट glTF एसेट (JSON, .bin और इमेजेज) को एक बाइनरी ब्लॉब में संग्रहीत करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/3d/glb). |
| static readonly [Gltf](../../groupdocs.conversion.filetypes/threedfiletype/gltf) | glTF (GL ट्रांसमिशन फ़ॉर्मेट) एक 3D फ़ाइल फ़ॉर्मेट है जो 3D मॉडल जानकारी को JSON फ़ॉर्मेट में संग्रहीत करता है। JSON के उपयोग से 3D एसेट्स का आकार और उन एसेट्स को अनपैक और उपयोग करने के लिए आवश्यक रनटाइम प्रोसेसिंग दोनों कम हो जाते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/3d/gltf). |
| static readonly [Jt](../../groupdocs.conversion.filetypes/threedfiletype/jt) | JT (Jupiter Tessellation) एक कुशल, उद्योग‑उन्मुख और लचीला ISO‑मानकीकृत 3D डेटा फ़ॉर्मेट है जिसे Siemens PLM Software ने विकसित किया है। एयरोस्पेस, ऑटोमोबाइल उद्योग और हेवी इक्विपमेंट के मैकेनिकल CAD क्षेत्रों में JT को उनके प्रमुख 3D विज़ुअलाइज़ेशन फ़ॉर्मेट के रूप में उपयोग किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/3d/jt). |
| static readonly [Ma](../../groupdocs.conversion.filetypes/threedfiletype/ma) | .ma एक्सटेंशन वाली फ़ाइल Autodesk Maya एप्लिकेशन से बनाई गई 3D प्रोजेक्ट फ़ाइल है। यह फ़ाइल के बारे में जानकारी निर्दिष्ट करने के लिए टेक्स्टुअल कमांड्स की बड़ी सूची रखती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/3d/ma). |
| static readonly [Mb](../../groupdocs.conversion.filetypes/threedfiletype/mb) | .mb एक्सटेंशन वाली फ़ाइल Autodesk Maya एप्लिकेशन द्वारा बनाई गई एक बाइनरी प्रोजेक्ट फ़ाइल है। MA फ़ाइल फ़ॉर्मेट, जो ASCII फ़ाइल फ़ॉर्मेट में है, के विपरीत, MB फ़ाइलें बाइनरी फ़ाइल फ़ॉर्मेट में संग्रहीत होती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://docs.fileformat.com/3d/mb). |
| static readonly [Obj](../../groupdocs.conversion.filetypes/threedfiletype/obj) | OBJ फ़ाइलें Wavefront के Advanced Visualizer एप्लिकेशन द्वारा ज्यामितीय वस्तुओं को परिभाषित करने और संग्रहीत करने के लिए उपयोग की जाती हैं। ज्यामितीय डेटा का बैकवर्ड और फॉरवर्ड ट्रांसमिशन OBJ फ़ाइलों के माध्यम से संभव होता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://docs.fileformat.com/3d/obj). |
| static readonly [Ply](../../groupdocs.conversion.filetypes/threedfiletype/ply) | PLY, Polygon File Format, एक 3D फ़ाइल फ़ॉर्मेट है जो बहुभुजों के संग्रह के रूप में वर्णित ग्राफ़िकल वस्तुओं को संग्रहीत करता है। इस फ़ाइल फ़ॉर्मेट का उद्देश्य एक सरल और आसान फ़ाइल प्रकार स्थापित करना था जो विभिन्न मॉडलों के लिए पर्याप्त सामान्य हो। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://docs.fileformat.com/3d/ply). |
| static readonly [Rvm](../../groupdocs.conversion.filetypes/threedfiletype/rvm) | RVM डेटा फ़ाइलें AVEVA PDMS से संबंधित हैं। RVM फ़ाइल AVEVA Plant Design Management System मॉडल प्रोजेक्ट फ़ाइल है। AVEVA का Plant Design Management System (PDMS) डेटा‑सेंट्रिक तकनीक का उपयोग करके प्रोजेक्ट्स को प्रबंधित करने वाला सबसे लोकप्रिय 3D डिज़ाइन सिस्टम है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://docs.fileformat.com/3d/rvm). |
| static readonly [ThreeDS](../../groupdocs.conversion.filetypes/threedfiletype/threeds) | .3ds एक्सटेंशन वाली फ़ाइल Autodesk 3D Studio द्वारा उपयोग किया जाने वाला 3D Sudio (DOS) मेष फ़ाइल फ़ॉर्मेट दर्शाती है। Autodesk 3D Studio 1990 के दशक से 3D फ़ाइल फ़ॉर्मेट बाजार में है और अब 3D Studio MAX में विकसित होकर 3D मॉडलिंग, एनीमेशन और रेंडरिंग के लिए उपयोग किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://docs.fileformat.com/3d/3ds). |
| static readonly [ThreeMF](../../groupdocs.conversion.filetypes/threedfiletype/threemf) | 3MF, 3D Manufacturing Format, विभिन्न एप्लिकेशन, प्लेटफ़ॉर्म, सेवाओं और प्रिंटरों को 3D ऑब्जेक्ट मॉडल रेंडर करने के लिए उपयोग किया जाता है। इसे अन्य 3D फ़ाइल फ़ॉर्मेट, जैसे STL, में मौजूद सीमाओं और समस्याओं से बचने के लिए बनाया गया था, ताकि नवीनतम 3D प्रिंटरों के साथ काम किया जा सके। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://docs.fileformat.com/3d/3mf). |
| static readonly [U3d](../../groupdocs.conversion.filetypes/threedfiletype/u3d) | U3D (Universal 3D) एक संकुचित फ़ाइल फ़ॉर्मेट और डेटा संरचना है 3D कंप्यूटर ग्राफ़िक्स के लिए। इसमें त्रिकोणीय मेष, लाइटिंग, शेडिंग, मोशन डेटा, रेखाएँ और बिंदु रंग और संरचना के साथ शामिल होते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://docs.fileformat.com/3d/u3d). |
| static readonly [Usd](../../groupdocs.conversion.filetypes/threedfiletype/usd) | .usd एक्सटेंशन वाली फ़ाइल एक Universal Scene Description फ़ाइल फ़ॉर्मेट है जो डिजिटल कंटेंट क्रिएशन एप्लिकेशन के बीच डेटा का आदान‑प्रदान और वृद्धि के लिए डेटा एन्कोड करती है। Pixar द्वारा विकसित, USD मौलिक एसेट (जैसे मॉडल) या एनीमेशन को बदलने की क्षमता प्रदान करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://docs.fileformat.com/3d/usd). |
| static readonly [Usdz](../../groupdocs.conversion.filetypes/threedfiletype/usdz) | .usdz एक अनकम्प्रेस्ड और अनएन्क्रिप्टेड ZIP आर्काइव है USD (Universal Scene Description) फ़ाइल फ़ॉर्मेट के लिए, जिसमें अन्य फ़ॉर्मेट की फ़ाइलें (जैसे टेक्सचर और एनीमेशन) एम्बेडेड होती हैं और इसे सीधे USD रन‑टाइम के साथ बिना अनज़िप किए चलाया जा सकता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://docs.fileformat.com/3d/usdz). |
| static readonly [Vrml](../../groupdocs.conversion.filetypes/threedfiletype/vrml) | Virtual Reality Modeling Language (VRML) एक फ़ाइल फ़ॉर्मेट है जो World Wide Web (www) पर इंटरैक्टिव 3D विश्व वस्तुओं का प्रतिनिधित्व करता है। इसका उपयोग जटिल दृश्यों जैसे चित्रण, परिभाषा और वर्चुअल रियलिटी प्रस्तुतियों के त्रि‑आयामी प्रतिनिधित्व बनाने में किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://docs.fileformat.com/3d/vrml). |
| static readonly [X](../../groupdocs.conversion.filetypes/threedfiletype/x) | .x एक्सटेंशन वाली फ़ाइल DirectX 3D Graphics की लेगेसी फ़ाइल फ़ॉर्मेट को दर्शाती है, जो Microsoft DirectX 2.0 के साथ पेश की गई थी। इसका उपयोग गेम्स में 3D ग्राफ़िक्स रेंडरिंग के लिए किया जाता था और यह मेष, टेक्सचर, एनीमेशन और उपयोगकर्ता‑परिभाषित वस्तुओं की संरचनाओं को निर्दिष्ट करती है। इसे 2014 से अप्रचलित कर दिया गया है क्योंकि Autodesk FBX फ़ाइल फ़ॉर्मेट अधिक आधुनिक विकल्प के रूप में बेहतर है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://docs.fileformat.com/3d/x). |

### देखें भी

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
