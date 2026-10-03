---
title: "ImageFileType"
second_title: "GroupDocs.Conversion for .NET API Reference"
description: "छवि दस्तावेज़ों को परिभाषित करता है। निम्नलिखित फ़ाइल प्रकार शामिल हैं Ai./imagefiletype/ai Avif./imagefiletype/avif Bmp./imagefiletype/bmp Cdr./imagefiletype/cdr Cmx./imagefiletype/cmx Dcm./imagefiletype/dcm Dib./imagefiletype/dib DjVu./imagefiletype/djvu Dng./imagefiletype/dng Emf./imagefiletype/emf Emz./imagefiletype/emz Gif./imagefiletype/gif Heic./imagefiletype/heicIco./imagefiletype/ico J2c./imagefiletype/j2c J2k./imagefiletype/j2k Jls./imagefiletype/jls Jp2./imagefiletype/jp2 Jpc./imagefiletype/jpc Jfif./imagefiletype/jfif. Jpeg./imagefiletype/jpeg Jpf./imagefiletype/jpf Jpg./imagefiletype/jpg Jpm./imagefiletype/jpm Jpx./imagefiletype/jpx Odg./imagefiletype/odg Png./imagefiletype/png Psd./imagefiletype/psd Tif./imagefiletype/tif Tiff./imagefiletype/tiff Webp./imagefiletype/webp Wmf./imagefiletype/wmf. Wmz./imagefiletype/wmz. छवि फ़ॉर्मेट के बारे में अधिक जानें यहाँ https//wiki.fileformat.com/image."
type: docs
weight: 1170
url: /hi/net/groupdocs.conversion.filetypes/imagefiletype/
---
## ImageFileType class

छवि दस्तावेज़ों को परिभाषित करता है। निम्नलिखित फ़ाइल प्रकार शामिल हैं: [`Ai`](./ai), [`Avif`](./avif), [`Bmp`](./bmp), [`Cdr`](./cdr), [`Cmx`](./cmx), [`Dcm`](./dcm), [`Dib`](./dib), [`DjVu`](./djvu), [`Dng`](./dng), [`Emf`](./emf), [`Emz`](./emz), [`Gif`](./gif), [`Heic`](./heic)[`Ico`](./ico), [`J2c`](./j2c), [`J2k`](./j2k), [`Jls`](./jls), [`Jp2`](./jp2), [`Jpc`](./jpc), [`Jfif`](./jfif). [`Jpeg`](./jpeg), [`Jpf`](./jpf), [`Jpg`](./jpg), [`Jpm`](./jpm), [`Jpx`](./jpx), [`Odg`](./odg), [`Png`](./png), [`Psd`](./psd), [`Tif`](./tif), [`Tiff`](./tiff), [`Webp`](./webp), [`Wmf`](./wmf). [`Wmz`](./wmz). छवि फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/image).

```csharp
public sealed class ImageFileType : FileType
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [ImageFileType](imagefiletype)() | सीरियलाइज़ेशन कंस्ट्रक्टर |

## गुण

| नाम | विवरण |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | फ़ाइल प्रकार विवरण |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | फ़ाइल एक्सटेंशन |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | फ़ाइल परिवार |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | फ़ाइल फ़ॉर्मेट |
| [IsRaster](../../groupdocs.conversion.filetypes/imagefiletype/israster) { get; } | परिभाषित करता है कि छवि रास्टर है या नहीं |

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
| static readonly [Ai](../../groupdocs.conversion.filetypes/imagefiletype/ai) | AI, Adobe Illustrator Artwork, एकल‑पृष्ठ वेक्टर‑आधारित चित्रण को EPS या PDF फ़ॉर्मेट में दर्शाता है। |
| static readonly [Avif](../../groupdocs.conversion.filetypes/imagefiletype/avif) | AVIF (AV1 इमेज फ़ाइल फ़ॉर्मेट) एक इमेज फ़ाइल फ़ॉर्मेट है जो AV1 के साथ संकुचित छवियों को HEIF फ़ाइल फ़ॉर्मेट में संग्रहीत करता है। AVIF फ़ाइलें .avif एक्सटेंशन के साथ संग्रहीत होती हैं। AVIF का संस्करण 1 फरवरी 2019 में अंतिम रूप दिया गया था। इसमें हाई डायनामिक रेंज (HDR), 8, 10 और 12 रंग गहराई का समर्थन, किसी भी रंग स्थान (ISO/IEC CICP और ICC प्रोफ़ाइल, विस्तृत रंग गामट) का समर्थन आदि जैसी विशेषताएँ हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/image/avif/). |
| static readonly [Bmp](../../groupdocs.conversion.filetypes/imagefiletype/bmp) | BMP बिटमैप इमेज फ़ाइलों को दर्शाता है जो बिटमैप डिजिटल छवियों को संग्रहीत करने के लिए उपयोग की जाती हैं। ये छवियाँ ग्राफ़िक्स एडाप्टर से स्वतंत्र होती हैं और इन्हें डिवाइस इंडिपेंडेंट बिटमैप (DIB) फ़ाइल फ़ॉर्मेट भी कहा जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/image/bmp). |
| static readonly [Cdr](../../groupdocs.conversion.filetypes/imagefiletype/cdr) | एक CDR फ़ाइल एक वेक्टर ड्रॉइंग इमेज फ़ाइल है जो मूल रूप से CorelDRAW के साथ डिजिटल इमेज को एन्कोड और संकुचित करने के लिए बनाई जाती है। ऐसी ड्रॉइंग फ़ाइल में टेक्स्ट, लाइन्स, शैप्स, इमेजेज, रंग और इफ़ेक्ट्स होते हैं जो इमेज सामग्री का वेक्टर प्रतिनिधित्व करते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://wiki.fileformat.com/image/cdr). |
| static readonly [Cmx](../../groupdocs.conversion.filetypes/imagefiletype/cmx) | CMX एक्सटेंशन वाली फ़ाइलें Corel Exchange इमेज फ़ाइल फ़ॉर्मेट हैं जो CorelSuite एप्लिकेशन द्वारा प्रस्तुति के रूप में उपयोग की जाती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://wiki.fileformat.com/image/cmx). |
| static readonly [Dcm](../../groupdocs.conversion.filetypes/imagefiletype/dcm) | .DCM एक्सटेंशन वाली फ़ाइलें डिजिटल इमेज का प्रतिनिधित्व करती हैं जो रोगियों की मेडिकल जानकारी जैसे MRI, CT स्कैन और अल्ट्रासाउंड इमेजेज को संग्रहीत करती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://wiki.fileformat.com/image/dcm). |
| static readonly [Dib](../../groupdocs.conversion.filetypes/imagefiletype/dib) | DIB (Device Independent Bitmap) फ़ाइल एक रास्टर इमेज फ़ाइल है जो संरचना में मानक Bitmap फ़ाइलों (BMP) के समान है लेकिन इसका हेडर अलग होता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://wiki.fileformat.com/image/dib). |
| static readonly [Dicom](../../groupdocs.conversion.filetypes/imagefiletype/dicom) | .DICOM एक्सटेंशन वाली फ़ाइलें डिजिटल इमेज का प्रतिनिधित्व करती हैं जो रोगियों की मेडिकल जानकारी जैसे MRI, CT स्कैन और अल्ट्रासाउंड इमेजेज को संग्रहीत करती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://wiki.fileformat.com/image/dicom). |
| static readonly [DjVu](../../groupdocs.conversion.filetypes/imagefiletype/djvu) | DjVu एक ग्राफ़िक्स फ़ाइल फ़ॉर्मेट है जो स्कैन किए गए दस्तावेज़ों और पुस्तकों के लिए बनाया गया है, विशेष रूप से उन में जो टेक्स्ट, ड्रॉइंग, इमेजेज और फ़ोटोग्राफ़ का संयोजन रखते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://wiki.fileformat.com/image/djvu). |
| static readonly [Dng](../../groupdocs.conversion.filetypes/imagefiletype/dng) | DNG एक डिजिटल कैमरा इमेज फ़ॉर्मेट है जो रॉ फ़ाइलों के भंडारण के लिए उपयोग किया जाता है। इसे Adobe ने सितंबर 2004 में विकसित किया था। यह मूल रूप से डिजिटल फ़ोटोग्राफी के लिए विकसित किया गया था। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://wiki.fileformat.com/image/dng). |
| static readonly [Emf](../../groupdocs.conversion.filetypes/imagefiletype/emf) | Enhanced metafile format (EMF) ग्राफ़िकल इमेजेज को डिवाइस-स्वतंत्र रूप से संग्रहीत करता है। EMF के मेटाफाइल में क्रमिक क्रम में वैरिएबल-लेंथ रिकॉर्ड होते हैं जो किसी भी आउटपुट डिवाइस पर पार्स करने के बाद संग्रहीत इमेज को रेंडर कर सकते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://wiki.fileformat.com/image/emf). |
| static readonly [Emz](../../groupdocs.conversion.filetypes/imagefiletype/emz) | EMZ फ़ाइल वास्तव में Microsoft EMF फ़ाइल का संकुचित संस्करण है। यह फ़ाइल को ऑनलाइन आसान वितरण की अनुमति देता है। जब EMF फ़ाइल को .GZIP संपीड़न एल्गोरिदम से संकुचित किया जाता है, तो इसे .emz फ़ाइल एक्सटेंशन दिया जाता है। |
| static readonly [Fodg](../../groupdocs.conversion.filetypes/imagefiletype/fodg) | FODG एक अनकम्प्रेस्ड XML-फ़ॉर्मेट फ़ाइल है जो OpenDocument टेक्स्ट डेटा को संग्रहीत करने के लिए उपयोग की जाती है। FODG एक्सटेंशन ओपन सोर्स ऑफिस प्रोडक्टिविटी सूट Libre Office और OpenOffice.org से जुड़ा है। |
| static readonly [Gif](../../groupdocs.conversion.filetypes/imagefiletype/gif) | GIF या Graphical Interchange Format एक अत्यधिक संकुचित इमेज प्रकार है। प्रत्येक इमेज के लिए GIF सामान्यतः प्रति पिक्सेल 8 बिट्स और कुल 256 रंगों की अनुमति देता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://wiki.fileformat.com/image/gif). |
| static readonly [Heic](../../groupdocs.conversion.filetypes/imagefiletype/heic) | HEIC फ़ाइल एक हाई-एफ़िशिएंसी कंटेनर इमेज फ़ाइल फ़ॉर्मेट है जो कई इमेजेज को एक ही फ़ाइल में संग्रह के रूप में संग्रहीत कर सकता है। यह फ़ॉर्मेट Apple द्वारा iOS 11 के लॉन्च के साथ HEIF का वैरिएंट के रूप में अपनाया गया था। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://docs.fileformat.com/image/heic/). |
| static readonly [Ico](../../groupdocs.conversion.filetypes/imagefiletype/ico) | ICO एक्सटेंशन वाली फ़ाइलें इमेज फ़ाइल प्रकार हैं जो Microsoft Windows पर किसी एप्लिकेशन का प्रतिनिधित्व करने के लिए आइकन के रूप में उपयोग की जाती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://wiki.fileformat.com/image/ico). |
| static readonly [J2c](../../groupdocs.conversion.filetypes/imagefiletype/j2c) | J2c दस्तावेज़ प्रारूप |
| static readonly [J2k](../../groupdocs.conversion.filetypes/imagefiletype/j2k) | J2K फ़ाइल एक इमेज है जो DCT संपीड़न के बजाय वेवलेट संपीड़न का उपयोग करके संकुचित की गई है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://wiki.fileformat.com/image/j2k). |
| static readonly [Jfif](../../groupdocs.conversion.filetypes/imagefiletype/jfif) | JFIF (JPEG File Interchange Format (JFIF)) एक इमेज फ़ॉर्मेट फ़ाइल है जो .jfif एक्सटेंशन का उपयोग करती है। JFIF जटिलता को कम करके और उसकी सीमाओं को हल करके JIF (JPEG Interchange Format) पर आधारित है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://docs.fileformat.com/image/jfif/). |
| static readonly [Jls](../../groupdocs.conversion.filetypes/imagefiletype/jls) | Jls दस्तावेज़ प्रारूप |
| static readonly [Jp2](../../groupdocs.conversion.filetypes/imagefiletype/jp2) | JPEG 2000 (JP2) एक इमेज कोडिंग सिस्टम और अत्याधुनिक इमेज संपीड़न मानक है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://wiki.fileformat.com/image/jp2). |
| static readonly [Jpc](../../groupdocs.conversion.filetypes/imagefiletype/jpc) | Jpc दस्तावेज़ प्रारूप |
| static readonly [Jpeg](../../groupdocs.conversion.filetypes/imagefiletype/jpeg) | JPEG एक प्रकार का इमेज फ़ॉर्मेट है जिसे लॉसी कम्प्रेशन विधि से सहेजा जाता है। कम्प्रेशन के परिणामस्वरूप आउटपुट इमेज, स्टोरेज आकार और इमेज गुणवत्ता के बीच संतुलन बनाती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/image/jpeg). |
| static readonly [Jpf](../../groupdocs.conversion.filetypes/imagefiletype/jpf) | Jpf दस्तावेज़ फ़ॉर्मेट |
| static readonly [Jpg](../../groupdocs.conversion.filetypes/imagefiletype/jpg) | JPG एक प्रकार का इमेज फ़ॉर्मेट है जिसे लॉसी कम्प्रेशन विधि से सहेजा जाता है। कम्प्रेशन के परिणामस्वरूप आउटपुट इमेज, स्टोरेज आकार और इमेज गुणवत्ता के बीच संतुलन बनाती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/image/jpeg). |
| static readonly [Jpm](../../groupdocs.conversion.filetypes/imagefiletype/jpm) | Jpm दस्तावेज़ फ़ॉर्मेट |
| static readonly [Jpx](../../groupdocs.conversion.filetypes/imagefiletype/jpx) | Jpx दस्तावेज़ फ़ॉर्मेट |
| static readonly [Odg](../../groupdocs.conversion.filetypes/imagefiletype/odg) | ODG फ़ाइल फ़ॉर्मेट Apache OpenOffice के Draw एप्लिकेशन द्वारा ड्रॉइंग तत्वों को वेक्टर इमेज के रूप में संग्रहीत करने के लिए उपयोग किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/image/odg). |
| static readonly [Otg](../../groupdocs.conversion.filetypes/imagefiletype/otg) | OTG फ़ाइल एक ड्रॉइंग टेम्प्लेट है जो OpenDocument मानक का उपयोग करके बनाई गई है और OASIS Office Applications 1.0 विनिर्देश का पालन करती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/image/otg). |
| static readonly [Png](../../groupdocs.conversion.filetypes/imagefiletype/png) | PNG, पोर्टेबल नेटवर्क ग्राफ़िक्स, एक प्रकार के रास्टर इमेज फ़ाइल फ़ॉर्मेट को दर्शाता है जो लॉसलेस कम्प्रेशन का उपयोग करता है। यह फ़ाइल फ़ॉर्मेट ग्राफ़िक्स इंटरचेंज फ़ॉर्मेट (GIF) के विकल्प के रूप में बनाया गया था और इसमें कोई कॉपीराइट प्रतिबंध नहीं है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/image/png). |
| static readonly [Psb](../../groupdocs.conversion.filetypes/imagefiletype/psb) | Adobe Photoshop फ़ाइलों को दो फ़ॉर्मेट में सहेजता है। 30,000 बाय 30,000 पिक्सेल आकार वाली फ़ाइलें PSD एक्सटेंशन के साथ सहेजी जाती हैं और PSD से बड़ी, 300,000 बाय 300,000 पिक्सेल तक की फ़ाइलें PSB एक्सटेंशन के साथ सहेजी जाती हैं जिसे “Photoshop Big” कहा जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/image/psb). |
| static readonly [Psd](../../groupdocs.conversion.filetypes/imagefiletype/psd) | PSD, Photoshop Document, Adobe Photoshop का मूल फ़ाइल फ़ॉर्मेट दर्शाता है जो ग्राफ़िक्स डिज़ाइन और विकास के लिए उपयोग होता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/image/psd). |
| static readonly [Tga](../../groupdocs.conversion.filetypes/imagefiletype/tga) | .tga एक्सटेंशन वाली फ़ाइल एक रास्टर ग्राफ़िक फ़ॉर्मेट है और इसे Truevision Inc. द्वारा बनाया गया था। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/image/tga). |
| static readonly [Tif](../../groupdocs.conversion.filetypes/imagefiletype/tif) | TIF, टैग्ड इमेज फ़ाइल फ़ॉर्मेट, रास्टर इमेज को दर्शाता है जो विभिन्न उपकरणों पर उपयोग के लिए उपयुक्त हैं जो इस फ़ाइल फ़ॉर्मेट मानक का पालन करते हैं। यह कई रंग स्थानों में बाइलैवल, ग्रेस्केल, पैलेट-कलर और फुल-कलर इमेज डेटा का वर्णन कर सकता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/image/tiff). |
| static readonly [Tiff](../../groupdocs.conversion.filetypes/imagefiletype/tiff) | TIFF, टैग्ड इमेज फ़ाइल फ़ॉर्मेट, रास्टर इमेज को दर्शाता है जो विभिन्न उपकरणों पर उपयोग के लिए उपयुक्त हैं जो इस फ़ाइल फ़ॉर्मेट मानक का पालन करते हैं। यह कई रंग स्थानों में बाइलैवल, ग्रेस्केल, पैलेट-कलर और फुल-कलर इमेज डेटा का वर्णन कर सकता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/image/tiff). |
| static readonly [Webp](../../groupdocs.conversion.filetypes/imagefiletype/webp) | WebP, Google द्वारा प्रस्तुत, एक आधुनिक रास्टर वेब इमेज फ़ाइल फ़ॉर्मेट है जो लॉसलेस और लॉसी कम्प्रेशन पर आधारित है। यह समान इमेज गुणवत्ता प्रदान करता है जबकि इमेज आकार को काफी कम करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/image/webp). |
| static readonly [Wmf](../../groupdocs.conversion.filetypes/imagefiletype/wmf) | WMF एक्सटेंशन वाली फ़ाइलें Microsoft Windows Metafile (WMF) को दर्शाती हैं जो वेक्टर और बिटमैप-फ़ॉर्मेट इमेज डेटा को संग्रहीत करने के लिए उपयोग होती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/image/wmf). |
| static readonly [Wmz](../../groupdocs.conversion.filetypes/imagefiletype/wmz) | WMZ फ़ाइल वास्तव में Microsoft WMF फ़ाइल का संकुचित संस्करण है। यह फ़ाइल को ऑनलाइन आसान वितरण की अनुमति देता है। जब एक EWMFMF फ़ाइल को .GZIP कम्प्रेशन एल्गोरिद्म से संकुचित किया जाता है, तो इसे .wmz फ़ाइल एक्सटेंशन दिया जाता है। |

### देखें भी

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
