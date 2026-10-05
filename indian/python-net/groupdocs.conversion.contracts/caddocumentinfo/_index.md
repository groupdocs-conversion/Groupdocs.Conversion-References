---
title: "CadDocumentInfo क्लास"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "Cad दस्तावेज़ मेटाडेटा शामिल है।"
type: docs
url: /hi/python-net/groupdocs.conversion.contracts/caddocumentinfo/
is_root: false
weight: 50
---


## CadDocumentInfo class

Cad दस्तावेज़ मेटाडेटा शामिल है।

[`DocumentInfo.pages_count`](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/pages_count/) counts the sheets the drawing offers under the load options it was read with.

स्पष्ट रूप से [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) नहीं दिया गया तो ये शीटें मॉडल स्पेस होती हैं, जो हमेशा प्लॉटेबल होती हैं और इसलिए हमेशा एक शीट होती है, साथ ही प्रत्येक पेपर-स्पेस लेआउट जिसका संग्रहीत पेज सेटअप में सकारात्मक चौड़ाई और ऊँचाई होती है, इसे [`CadLoadOptions.layout_scope`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/) द्वारा संकीर्ण किया जाता है। स्पष्ट लेआउट नाम सीधे जीतते हैं: तब शीटें वह आपूर्ति किए गए नाम होते हैं जो ड्राइंग लेती है, क्रमिक रूप से मिलते हैं, और न तो स्कोप और न ही पेज सेटअप उन्हें फ़िल्टर करता है।

एक DWF के लिए प्रकाशित पृष्ठ सेट रिपोर्ट किया जाता है। एक से कम की गिनती शून्य होती है, जो तब रिपोर्ट की जाती है जब अनुरोधित स्कोप उस ड्रॉइंग की किसी भी शीट से मेल नहीं खाता जो एक प्रदान करती है: मेटाडेटा अभी भी ड्रॉइंग का वर्णन करता है, और शून्य दर्शाता है कि स्कोप कुछ भी नहीं चुनता है बजाय उस कॉलर को विफल करने के जो पूछता है कि ड्रॉइंग में क्या है। वही लोड विकल्पों के तहत एक रूपांतरण विफल हो जाता है।

इसलिए गिनती [`CadDocumentInfo.layouts`](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layouts/) का आकार नहीं है, जो ड्राइंग द्वारा ले जाए गए प्रत्येक प्लॉट कॉन्फ़िगरेशन को सूचीबद्ध करता है, जिसमें वे भी शामिल हैं जिनसे कोई शीट प्रकाशित नहीं की जा सकती, और यह भविष्यवाणी नहीं करता कि किसी विशेष रूपांतरण में कितने पृष्ठ उत्पन्न होंगे।

CadDocumentInfo प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### विधियाँ
| विधि | विवरण |
| :- | :- |
| [get](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get/) |  |
| [get_file](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get_file/) |  |
| [get_string](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get_string/) |  |

### गुणधर्म
| गुण | विवरण |
| :- | :- |
| [creation_date](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/creation_date/) | दस्तावेज़ निर्माण तिथि। |
| [format](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/format/) | दस्तावेज़ प्रारूप। |
| [height](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/height/) | CAD दस्तावेज़ की ऊँचाई। |
| [layers](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layers/) | दस्तावेज़ में लेयर्स। |
| [layouts](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layouts/) | दस्तावेज़ में लेआउट्स। |
| [pages_count](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/pages_count/) | दस्तावेज़ पृष्ठों की संख्या। |
| [property_names](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/property_names/) | वर्तमान दस्तावेज़ जानकारी के लिए प्राप्त किए जा सकने वाले सभी गुणों की सूची। |
| [size](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/size/) | दस्तावेज़ का आकार बाइट्स में। |
| [width](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/width/) | CAD दस्तावेज़ की चौड़ाई। |

### साथ ही देखें
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
