---
title: "PdfConvertOptions क्लास"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "PDF फ़ाइल प्रकार में रूपांतरण के विकल्प।"
type: docs
url: /hi/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/
is_root: false
weight: 340
---


## PdfConvertOptions class

PDF फ़ाइल प्रकार में रूपांतरण के विकल्प।

PdfConvertOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/__init__/) | [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) का नया उदाहरण आरंभ करता है। |

### गुणधर्म
| गुण | विवरण |
| :- | :- |
| [dpi](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/dpi/) | परिवर्तन के बाद वांछित पृष्ठ DPI। डिफ़ॉल्ट रिज़ॉल्यूशन 96 dpi है। |
| [embed_full_fonts](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/embed_full_fonts/) | यह प्रॉपर्टी निर्धारित करती है कि पूर्ण फ़ॉन्ट फ़ाइल को उपसमुच्चय के बजाय PDF में एम्बेड किया जाए। |
| [fallback_page_size](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/fallback_page_size/) | फ़ॉलबैक पृष्ठ आकार। |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/format/) | इनपुट दस्तावेज़ को जिस इच्छित फ़ाइल प्रकार में परिवर्तित किया जाना चाहिए। |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/margin_settings/) | PDF रूपांतरण के दौरान लागू मार्जिन सेटिंग्स। |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/orientation_settings/) | ओरिएंटेशन सेटिंग्स। |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/page_number/) | जिस पेज नंबर से रूपांतरण शुरू करना है। |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/pages/) | रूपांतरण के लिए पृष्ठ अनुक्रमणिकाओं की सूची; विशिष्ट पृष्ठों को रूपांतरित करने के लिए निर्दिष्ट करें। |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/pages_count/) | `page_number` से शुरू होने वाले रूपांतरण पृष्ठों की संख्या। |
| [password](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/password/) | रूपांतरित दस्तावेज़ को सुरक्षित करने के लिए उपयोग किया गया पासवर्ड। |
| [pdf_options](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/pdf_options/) | PDF-विशिष्ट रूपांतरण विकल्प। |
| [resize_mode](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/resize_mode/) | रिसाइज़ मोड निर्दिष्ट करता है कि पृष्ठ आकार बदलने पर सामग्री को कैसे स्केल किया जाए। डिफ़ॉल्ट AlignTopLeft (कोई स्केलिंग नहीं) है। |
| [rotate](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/rotate/) | पृष्ठ घूर्णन। |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/size_settings/) | PDF रूपांतरण के दौरान उपयोग किए जाने वाले पृष्ठ आकार सेटिंग्स। |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/watermark/) | वॉटरमार्क के विशिष्ट विकल्प। |

### उदाहरण

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Guides
`PdfConvertOptions` का उपयोग करने वाले टास्क गाइड्स:

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert a Document to Another Format](/conversion/python-net/guides/convert-document-to-another-format/)
* [Convert Files Within Document Containers](/conversion/python-net/guides/convert-files-within-document-containers/)
* [Add a Watermark to Converted Document](/conversion/python-net/guides/add-watermark-to-converted-document/)
* [Load File From Local Disk](/conversion/python-net/guides/load-file-from-local-disk/)
* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)

### साथ ही देखें
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
