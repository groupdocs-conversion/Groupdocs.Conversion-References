---
title: "FontTransformation वर्ग"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "दस्तावेज़ लोडिंग और फ़ॉन्ट प्रतिस्थापन के बाद लागू होने वाले फ़ॉन्ट एट्रिब्यूट्स सहित फ़ॉन्ट ट्रांसफ़ॉर्मेशन कॉन्फ़िगरेशन का वर्णन करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.contracts/fonttransformation/
is_root: false
weight: 200
---


## FontTransformation class

दस्तावेज़ लोडिंग और फ़ॉन्ट प्रतिस्थापन के बाद लागू होने वाले फ़ॉन्ट एट्रिब्यूट्स सहित फ़ॉन्ट ट्रांसफ़ॉर्मेशन कॉन्फ़िगरेशन का वर्णन करता है।

FontTransformation प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### विधियाँ
| विधि | विवरण |
| :- | :- |
| [create](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create/#original_font-replacement_font) | सटीक फ़ॉन्ट मिलान (आकार और शैली मिलनी चाहिए) के साथ फ़ॉन्ट परिवर्तन बनाता है। |
| [create_by_name](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create_by_name/#original_font_name-replacement_font_name) | केवल नाम द्वारा फ़ॉन्ट परिवर्तन बनाता है, किसी भी आकार और शैली से मेल खाता है, तथा प्रतिस्थापन फ़ॉन्ट मूल फ़ॉन्ट के आकार और शैली को संरक्षित रखता है। |
| [create_flexible](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create_flexible/#original_font-replacement_font-match_any_size-match_any_style) | लचीले मिलान विकल्पों के साथ फ़ॉन्ट परिवर्तन बनाता है। |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | निर्धारित करता है कि दो ऑब्जेक्ट उदाहरण समान हैं या नहीं। (से विरासत में मिला [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (से विरासत में मिला [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (से विरासत में मिला [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | डिफ़ॉल्ट हैश फ़ंक्शन के रूप में कार्य करता है। (से विरासत में मिला [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### गुणधर्म
| गुण | विवरण |
| :- | :- |
| [match_any_size](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/match_any_size/) | यह गुण दर्शाता है कि मूल फ़ॉन्ट नाम के लिए कोई भी फ़ॉन्ट आकार मेल खाता है (true) या केवल `OriginalFont` में निर्दिष्ट सटीक फ़ॉन्ट आकार मेल खाता है (false)। |
| [match_any_style](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/match_any_style/) | यह गुण निर्धारित करता है कि मूल फ़ॉन्ट की कोई भी शैली (बोल्ड, इटैलिक, अंडरलाइन) मेल खाती है (True) या `OriginalFont` में निर्दिष्ट सटीक फ़ॉन्ट शैली आवश्यक है (False)। |
| [original_font](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/original_font/) | मिलाने और बदलने के लिए मूल फ़ॉन्ट विनिर्देश। |
| [replacement_font](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/replacement_font/) | प्रतिस्थापन फ़ॉन्ट विनिर्देश। |

### साथ ही देखें
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
