---
title: "ConverterSettings क्लास"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "कनवर्टर व्यवहार को अनुकूलित करने के लिए सेटिंग्स को परिभाषित करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion/convertersettings/
is_root: false
weight: 90
---


## ConverterSettings class

कनवर्टर व्यवहार को अनुकूलित करने के लिए सेटिंग्स को परिभाषित करता है।

ConverterSettings प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/convertersettings/__init__/) | डिफ़ॉल्ट मानों के साथ ConverterSettings का नया उदाहरण आरंभ करता है। |

### गुणधर्म
| गुण | विवरण |
| :- | :- |
| [cache](/conversion/python-net/groupdocs.conversion/convertersettings/cache/) | परिवर्तन परिणामों को संग्रहीत करने के लिए उपयोग की जाने वाली कैश कार्यान्वयन। |
| [font_directories](/conversion/python-net/groupdocs.conversion/convertersettings/font_directories/) | कस्टम फ़ॉन्ट निर्देशिका पथ। |
| [listener](/conversion/python-net/groupdocs.conversion/convertersettings/listener/) | परिवर्तन स्थिति और प्रगति की निगरानी के लिए उपयोग किया जाने वाला कनवर्टर लिस्नर कार्यान्वयन, जिसके Started, Progress, और Completed कॉलबैक को [`ConversionEvents.on_conversion_started`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/), [`ConversionEvents.on_conversion_progress`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/), और [`ConversionEvents.on_conversion_completed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) पर अग्रेषित किया जाता है, जब [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) का निर्माण किया जाता है। |
| [logger](/conversion/python-net/groupdocs.conversion/convertersettings/logger/) | परिवर्तन प्रक्रिया को लॉग करने के लिए उपयोग किया जाने वाला लॉगर कार्यान्वयन। |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion/convertersettings/on_compression_completed/) | कम्प्रेशन पूर्ण होने के लिए इवेंट हैंडलर। |
| [on_conversion_by_page_failed](/conversion/python-net/groupdocs.conversion/convertersettings/on_conversion_by_page_failed/) | पृष्ठ द्वारा परिवर्तन विफल होने पर बुलाया जाने वाला इवेंट हैंडलर। |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion/convertersettings/on_conversion_failed/) | परिवर्तन विफल होने पर बुलाया जाने वाला इवेंट हैंडलर। |
| [scan_font_directories_recursively](/conversion/python-net/groupdocs.conversion/convertersettings/scan_font_directories_recursively/) | जब True सेट किया जाता है, तो कनवर्टर फ़ॉन्ट निर्देशिकाओं को पुनरावर्ती रूप से स्कैन करता है। |
| [temp_folder](/conversion/python-net/groupdocs.conversion/convertersettings/temp_folder/) | परिवर्तन के लिए उपयोग किया जाने वाला टेम्प फ़ोल्डर। |

### उदाहरण

```python
from groupdocs.conversion import Converter, ConverterSettings
from groupdocs.conversion.logging import ConsoleLogger
from groupdocs.conversion.options.convert import PdfConvertOptions

settings = ConverterSettings()
settings.logger = ConsoleLogger()

with Converter("input.docx", settings) as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### साथ ही देखें
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
