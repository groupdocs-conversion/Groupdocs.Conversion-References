---
title: "FontSubstitutionContext क्लास"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "स्रोत दस्तावेज़ को लोड या रेंडर करते समय हुई एकल फ़ॉन्ट प्रतिस्थापन का वर्णन करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/
is_root: false
weight: 190
---


## FontSubstitutionContext class

स्रोत दस्तावेज़ को लोड या रेंडर करते समय हुई एकल फ़ॉन्ट प्रतिस्थापन का वर्णन करता है।

इंस्टेंस को [`ConversionEvents.on_font_substituted`](/conversion/python-net/groupdocs.conversion/conversionevents/on_font_substituted/) को पास किया जाता है।

FontSubstitutionContext प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/__init__/#source_file_name-original_font_name-substitute_font_name-reason) | एक नया FontSubstitutionContext प्रारंभ करता है। |

### गुणधर्म
| गुण | विवरण |
| :- | :- |
| [original_font_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/original_font_name/) | स्रोत दस्तावेज़ द्वारा संदर्भित फ़ॉन्ट का नाम, जो रूपांतरण पाइपलाइन के लिए उपलब्ध नहीं है। |
| [reason](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/) | परिवर्तन पाइपलाइन द्वारा रिपोर्ट किया गया प्रतिस्थापन संदेश बिल्कुल जैसा है, शब्दशः और अपरिष्कृत। |
| [source_file_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/source_file_name/) | परिवर्तित हो रहे स्रोत दस्तावेज़ का फ़ाइल नाम। जब स्रोत को एक स्ट्रीम के रूप में प्रदान किया गया हो जो `io.RawIOBase` नहीं है, तो यह वास्तविक फ़ाइल नाम के बजाय एक उत्पन्न पहचानकर्ता रखता है। |
| [substitute_font_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/substitute_font_name/) | प्रतिस्थापन के रूप में उपयोग किए गए फ़ॉन्ट का नाम। उन दस्तावेज़ों के लिए None हो सकता है जिनके इंजन केवल वर्णनात्मक पाठ के रूप में प्रतिस्थापन रिपोर्ट करते हैं — ऐसे मामले में पढ़ें [`FontSubstitutionContext.reason`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/). |

### साथ ही देखें
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
