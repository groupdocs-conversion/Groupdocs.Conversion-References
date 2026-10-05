---
title: "ImageConvertOptions क्लास"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "दस्तावेज़ को इमेज फ़ाइल प्रकार में रूपांतरण के विकल्पों का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.options.convert/imageconvertoptions/
is_root: false
weight: 230
---


## ImageConvertOptions class

दस्तावेज़ को इमेज फ़ाइल प्रकार में रूपांतरण के विकल्पों का प्रतिनिधित्व करता है।

ImageConvertOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/__init__/) | एक नया ImageConvertOptions इंस्टेंस प्रारंभ करता है। |

### गुणधर्म
| गुण | विवरण |
| :- | :- |
| [background_color](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/background_color/) | स्रोत फ़ॉर्मेट द्वारा समर्थित होने पर उपयोग करने के लिए पृष्ठभूमि रंग। |
| [brightness](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/brightness/) | छवि चमक समायोजन। |
| [cap_resolution_to_page_content](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/) | यह प्रॉपर्टी प्रति-पृष्ठ PDF रेंडर रिज़ॉल्यूशन को पृष्ठ के मूल रास्टर रिज़ॉल्यूशन तक सीमित करती है, जिससे एम्बेडेड छवि से अधिक DPI पर रेंडरिंग रोकती है और अंतिम आउटपुट में पृष्ठ को उसके मूल (छोटे) पिक्सेल आयाम और DPI पर उत्पन्न करती है। |
| [contrast](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/contrast/) | छवि पर लागू कंट्रास्ट समायोजन। |
| [crop_area](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/crop_area/) | रूपांतरण के बाद रास्टर छवि का क्रॉप क्षेत्र। |
| [flip_mode](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/flip_mode/) | छवि फ़्लिप मोड। |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/format/) | इनपुट दस्तावेज़ को जिस इच्छित फ़ाइल प्रकार में परिवर्तित किया जाना चाहिए। |
| [gamma](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/gamma/) | छवि गामा समायोजन। |
| [grayscale](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/grayscale/) | विकल्प जो दर्शाता है कि छवि को ग्रेस्केल में परिवर्तित किया जाए या नहीं। |
| [height](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/height/) | परिवर्तन के बाद वांछित छवि ऊँचाई। |
| [horizontal_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/horizontal_resolution/) | परिवर्तन के बाद वांछित छवि क्षैतिज रिज़ॉल्यूशन; डिफ़ॉल्ट रूप से इनपुट फ़ाइल की रिज़ॉल्यूशन या 96 dpi। |
| [jpeg_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/jpeg_options/) | JPEG के विशिष्ट रूपांतरण विकल्प। |
| [min_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/min_resolution/) | जब [`ImageConvertOptions.CapResolutionToPageContent`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/) सक्षम हो, तब सीमित रेंडर DPI पर लागू प्रति-अक्ष निचली सीमा। |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/page_number/) | जिस पेज नंबर से रूपांतरण शुरू करना है। |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/pages/) | रूपांतरण के लिए पेज इंडेक्स की सूची। विशिष्ट पेजों को रूपांतरित करने के लिए इसे निर्दिष्ट करना चाहिए। |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/pages_count/) | `PageNumber` से शुरू होने वाले रूपांतरण पेजों की संख्या। |
| [psd_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/psd_options/) | PSD-विशिष्ट रूपांतरण विकल्प। |
| [rotate_angle](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/rotate_angle/) | छवि घुमाव कोण। |
| [tiff_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/tiff_options/) | Tiff के विशिष्ट रूपांतरण विकल्प। |
| [use_pdf](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/use_pdf/) | UsePdf प्रॉपर्टी। |
| [vertical_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/vertical_resolution/) | परिवर्तन के बाद वांछित छवि लंबवत रिज़ॉल्यूशन। डिफ़ॉल्ट रिज़ॉल्यूशन इनपुट फ़ाइल की रिज़ॉल्यूशन या 96 dpi है। |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/watermark/) | वॉटरमार्क के विशिष्ट विकल्प। |
| [webp_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/webp_options/) | WebP के विशिष्ट रूपांतरण विकल्प। |
| [width](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/width/) | परिवर्तन के बाद वांछित छवि चौड़ाई। |

### उदाहरण

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

with Converter("slides.pptx") as converter:
    options = ImageConvertOptions()
    options.format = ImageFileType.PNG
    options.page_number = 1
    options.pages_count = 1
    converter.convert("slide-1.png", options)
```

### Guides
`ImageConvertOptions` का उपयोग करने वाले कार्य मार्गदर्शिकाएँ:

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert Document To Multiple Page Files](/conversion/python-net/guides/convert-document-to-multiple-page-files/)

### साथ ही देखें
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
