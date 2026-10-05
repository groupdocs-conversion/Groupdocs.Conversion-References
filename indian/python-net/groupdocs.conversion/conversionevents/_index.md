---
title: "ConversionEvents क्लास"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "परिवर्तन जीवनचक्र इवेंट हैंडलर्स को एकत्रित करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion/conversionevents/
is_root: false
weight: 20
---


## ConversionEvents class

परिवर्तन जीवनचक्र इवेंट हैंडलर्स को एकत्रित करता है।

एक उदाहरण को [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) कन्स्ट्रक्टर के `events` पैरामीटर में या फ्लुएंट `WithEvents` मेथड में पास करें।

व्यक्तिगत [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/) हैंडलर प्रॉपर्टीज़ के बजाय इसे प्राथमिकता दें, जो अब अप्रचलित हैं।

ConversionEvents प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/conversionevents/__init__/) |  |

### गुणधर्म
| गुण | विवरण |
| :- | :- |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion/conversionevents/on_compression_completed/) | परिवर्तन आउटपुट के कम्प्रेशन के पूर्ण होने पर फायर होने वाला इवेंट। केवल उन बिल्ड्स में बुलाया जाता है जिनमें कम्प्रेशन पाइपलाइन (LIB_ZIP) शामिल है। |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) | परिवर्तन प्रक्रिया समाप्त होने पर एक बार चलने वाली घटना, चाहे सफलता हो या विफलता। |
| [on_conversion_progress](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/) | परिवर्तन प्रगति प्रतिशत (0–100) के रूप में, समय-समय पर जारी की जाती है। |
| [on_conversion_started](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/) | परिवर्तन प्रक्रिया की शुरुआत में, किसी दस्तावेज़ को संसाधित करने से पहले, एक बार चलने वाली घटना। |
| [on_document_converted](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_converted/) | सफलतापूर्वक पूर्ण होने वाले पूरे दस्तावेज़ परिवर्तन पर एक बार चलने वाली घटना। |
| [on_document_failed](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_failed/) | विफल होने वाले पूरे दस्तावेज़ परिवर्तन पर एक बार चलने वाली घटना। |
| [on_font_substituted](/conversion/python-net/groupdocs.conversion/conversionevents/on_font_substituted/) | जब स्रोत दस्तावेज़ द्वारा संदर्भित फ़ॉन्ट उपलब्ध नहीं होता और उसे प्रतिस्थापित किया जाता है (या तो ग्राहक‑प्रदानित [`FontSubstitute`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitute/) नियम द्वारा, कॉन्फ़िगर किए गए डिफ़ॉल्ट फ़ॉन्ट द्वारा, या परिवर्तन पाइपलाइन की आंतरिक फ़ॉलबैक द्वारा)। |
| [on_page_converted](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_converted/) | प्रति पृष्ठ परिवर्तन सफलतापूर्वक पूर्ण होने पर प्रत्येक पृष्ठ पर एक बार चलने वाली घटना। |
| [on_page_failed](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_failed/) | प्रति पृष्ठ परिवर्तन विफल होने पर प्रत्येक पृष्ठ पर एक बार चलने वाली घटना। |

### साथ ही देखें
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
