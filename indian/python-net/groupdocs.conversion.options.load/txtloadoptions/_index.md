---
title: "TxtLoadOptions क्लास"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "Txt दस्तावेज़ लोड करने के विकल्प।"
type: docs
url: /hi/python-net/groupdocs.conversion.options.load/txtloadoptions/
is_root: false
weight: 500
---


## TxtLoadOptions class

Txt दस्तावेज़ लोड करने के विकल्प।

सादा पाठ के लिए फ़ॉन्ट कॉन्फ़िगरेशन:

चूँकि TXT फ़ाइलों में फ़ॉन्ट जानकारी नहीं होती, रूपांतरण के दौरान सादा पाठ सामग्री को रेंडर करने के लिए फ़ॉन्ट निर्दिष्ट करने हेतु DefaultTextFont का उपयोग करें।

TxtLoadOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/__init__/) | एक नया [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/) इंस्टेंस प्रारंभ करता है। |

### विधियाँ
| विधि | विवरण |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | निर्धारित करता है कि दो ऑब्जेक्ट उदाहरण समान हैं या नहीं। (से विरासत में मिला [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (से विरासत में मिला [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (से विरासत में मिला [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | डिफ़ॉल्ट हैश फ़ंक्शन के रूप में कार्य करता है। (से विरासत में मिला [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### गुणधर्म
| गुण | विवरण |
| :- | :- |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/default_font/) | रूपांतरण के दौरान सादा पाठ सामग्री को रेंडर करने के लिए उपयोग किया जाने वाला फ़ॉन्ट। डिफ़ॉल्ट: Arial 10pt. |
| [detect_numbering_with_whitespaces](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/detect_numbering_with_whitespaces/) | यह प्रॉपर्टी निर्दिष्ट करती है कि सादा पाठ दस्तावेज़ के रूपांतरण पर क्रमांकित सूची आइटम कैसे पहचाने जाते हैं। डिफ़ॉल्ट मान True है। |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/encoding/) | Txt दस्तावेज़ लोड करते समय उपयोग किया जाने वाला एन्कोडिंग। None भी हो सकता है। डिफ़ॉल्ट None है। |
| [format](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/format/) | इनपुट दस्तावेज़ फ़ाइल प्रकार। |
| [leading_spaces_options](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/leading_spaces_options/) | प्रारंभिक स्पेस को संभालने के लिए पसंदीदा विकल्प। |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/margin_settings/) | मार्जिन सेटिंग्स, जैसा कि [`IPageMarginOptions`](/conversion/python-net/groupdocs.conversion.options/ipagemarginoptions/) द्वारा परिभाषित है। |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/size_settings/) | TXT दस्तावेज़ लोड करने के लिए पेज आकार विकल्प। |
| [trailing_spaces_options](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/trailing_spaces_options/) | ट्रेलिंग स्पेसेज़ को संभालने के लिए पसंदीदा विकल्प। डिफ़ॉल्ट मान है [`TxtTrailingSpacesOptions.trim`](/conversion/python-net/groupdocs.conversion.options.load/txttrailingspacesoptions/). |

### साथ ही देखें
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
