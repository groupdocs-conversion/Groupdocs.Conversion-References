---
title: "WordProcessingConvertOptions क्लास"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "वर्डप्रोसेसिंग फ़ाइल प्रकार में रूपांतरण के विकल्प।"
type: docs
url: /hi/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/
is_root: false
weight: 620
---


## WordProcessingConvertOptions class

वर्डप्रोसेसिंग फ़ाइल प्रकार में रूपांतरण के विकल्प।

WordProcessingConvertOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/__init__/) | एक नया उदाहरण प्रारंभ करता है [`WordProcessingConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/). |

### गुणधर्म
| गुण | विवरण |
| :- | :- |
| [dpi](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/dpi/) | परिवर्तन के बाद वांछित पृष्ठ DPI। डिफ़ॉल्ट रिज़ॉल्यूशन 96 dpi है। |
| [fallback_page_size](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/fallback_page_size/) | फ़ॉलबैक पृष्ठ आकार। |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/format/) | इनपुट दस्तावेज़ को जिस इच्छित फ़ाइल प्रकार में परिवर्तित किया जाना चाहिए। |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/margin_settings/) | परिवर्तन के लिए मार्जिन सेटिंग्स, जो [`IPageMarginOptions`](/conversion/python-net/groupdocs.conversion.options/ipagemarginoptions/) द्वारा प्रतिनिधित्व की गई हैं। |
| [markdown_options](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/markdown_options/) | Markdown रूपांतरण विकल्प। |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/orientation_settings/) | ओरिएंटेशन सेटिंग्स। |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/page_number/) | जिस पेज नंबर से रूपांतरण शुरू करना है। |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/pages/) | रूपांतरण के लिए पेज इंडेक्स की सूची। विशिष्ट पेजों को रूपांतरित करने के लिए इसे निर्दिष्ट करना चाहिए। |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/pages_count/) | `PageNumber` से शुरू होने वाले रूपांतरण पेजों की संख्या। |
| [password](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/password/) | रूपांतरित दस्तावेज़ को सुरक्षित करने के लिए उपयोग किया गया पासवर्ड। |
| [pdf_recognition_mode](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/pdf_recognition_mode/) | परिवर्तन के लिए उपयोग किया गया PDF पहचान मोड, जो [`IPdfRecognitionModeOptions.pdf_recognition_mode`](/conversion/python-net/groupdocs.conversion.options.convert/ipdfrecognitionmodeoptions/pdf_recognition_mode/) को लागू करता है। |
| [rtf_options](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/rtf_options/) | RTF विशिष्ट रूपांतरण विकल्प। |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/size_settings/) | परिवर्तन के लिए आकार सेटिंग्स। |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/watermark/) | वॉटरमार्क के विशिष्ट विकल्प। |
| [zoom](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/zoom/) | प्रतिशत में ज़ूम स्तर। |

### उदाहरण

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import WordProcessingConvertOptions
from groupdocs.conversion.filetypes import WordProcessingFileType

with Converter("./business-plan.docx") as converter:
    options = WordProcessingConvertOptions()
    options.format = WordProcessingFileType.TXT
    converter.convert("./business-plan.txt", options)
```

### Guides
टास्क गाइड्स जो `WordProcessingConvertOptions` का उपयोग करते हैं:

* [Convert a Document to Another Format](/conversion/python-net/guides/convert-document-to-another-format/)

### साथ ही देखें
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
