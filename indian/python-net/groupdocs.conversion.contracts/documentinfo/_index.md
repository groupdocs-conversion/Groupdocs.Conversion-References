---
title: "DocumentInfo क्लास"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "यह बहु-रूपीय दस्तावेज़ जानकारी प्राप्त करने के लिए बेस कार्यान्वयन।"
type: docs
url: /hi/python-net/groupdocs.conversion.contracts/documentinfo/
is_root: false
weight: 120
---


## DocumentInfo class

यह बहु-रूपीय दस्तावेज़ जानकारी प्राप्त करने के लिए बेस कार्यान्वयन।

`Converter.get_document_info()` द्वारा इंस्टेंस लौटाए जाते हैं और फ़ॉर्मेट, पृष्ठ गिनती, निर्माण तिथि, आकार, और फ़ॉर्मेट‑विशिष्ट गुणों जैसी मेटाडेटा को उजागर करते हैं।

DocumentInfo प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### विधियाँ
| विधि | विवरण |
| :- | :- |
| [get](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get/) |  |
| [get_file](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get_file/) |  |
| [get_string](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get_string/) |  |

### गुणधर्म
| गुण | विवरण |
| :- | :- |
| [creation_date](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/creation_date/) | दस्तावेज़ की निर्माण तिथि। |
| [format](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/format/) | दस्तावेज़ का फ़ॉर्मेट। |
| [pages_count](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/pages_count/) | दस्तावेज़ में कुल पृष्ठों की संख्या। |
| [property_names](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/property_names/) | यह प्रॉपर्टी [`IDocumentInfo.property_names`](/conversion/python-net/groupdocs.conversion.contracts/idocumentinfo/property_names/) को लागू करती है। |
| [size](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/size/) | बाइट्स में दस्तावेज़ का आकार। |

### उदाहरण

```python
from groupdocs.conversion import Converter

def show_document_info(path):
    with Converter(path) as converter:
        info = converter.get_document_info()
        print("Format:", info.format)
        print("Pages count:", info.pages_count)
        print("Creation date:", info.creation_date)
        print("Size (bytes):", info.size)

# उदाहरण उपयोग
show_document_info("./lorem-ipsum.txt")
```

### साथ ही देखें
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
