---
title: "WordProcessingLoadOptions क्लास"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "WordProcessing दस्तावेज़ लोड करने के विकल्प प्रदान करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/
is_root: false
weight: 580
---


## WordProcessingLoadOptions class

WordProcessing दस्तावेज़ लोड करने के विकल्प प्रदान करता है।

फ़ॉन्ट प्रोसेसिंग पाइपलाइन:

चरण 1 - फ़ॉन्ट प्रतिस्थापन (दस्तावेज़ लोडिंग के दौरान):
- Handles missing/unavailable fonts using FontSubstitutes, DefaultFont, and system substitution
- Processing order: FontName → FontConfig → FontSubstitutes → FontInfo → DefaultFont

चरण 2 - फ़ॉन्ट प्रतिस्थापन (दस्तावेज़ लोडिंग के बाद):
- Modifies any existing fonts in the loaded document using FontReplacements
- Applied after all font substitution is complete

WordProcessingLoadOptions प्रकार निम्नलिखित सदस्य उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/__init__/) | एक नया उदाहरण प्रारंभ करता है [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/). |

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
| [auto_detect_rtl_direction](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/auto_detect_rtl_direction/) | auto_detect_rtl_direction प्रॉपर्टी निर्धारित करती है कि क्या पैराग्राफ़ और रन, जिनमें मुख्यतः दाएँ‑से‑बाएँ पाठ है, रूपांतरण से पहले उनके बिडी फ़्लैग्स को ठीक किया जाता है। |
| [bookmark_options](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/bookmark_options/) | बुकमार्क विकल्प। |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/clear_built_in_document_properties/) | फ़्लैग जो दर्शाता है कि क्या Word प्रोसेसिंग दस्तावेज़ लोड करते समय अंतर्निहित दस्तावेज़ गुण साफ़ किए जाते हैं। |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/clear_custom_document_properties/) | ClearCustomDocumentProperties प्रॉपर्टी। |
| [comment_display_mode](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/comment_display_mode/) | कमेन्ट डिस्प्ले मोड निर्दिष्ट करता है कि आउटपुट दस्तावेज़ में कमेंट्स कैसे दिखाए जाएँ। डिफ़ॉल्ट `ShowInBalloons` है। |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/convert_owned/) | यह प्रॉपर्टी लागू करती है [`IDocumentsContainerLoadOptions.convert_owned`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owned/). डिफ़ॉल्ट False है। |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/convert_owner/) | convert_owner फ़्लैग दर्शाता है कि क्या दस्तावेज़ मालिक को रूपांतरित किया जाए। डिफ़ॉल्ट True है। |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/default_font/) | WordProcessing दस्तावेज़ के लिए डिफ़ॉल्ट फ़ॉन्ट। |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/depth/) | दस्तावेज़ कंटेनर लोड विकल्पों की गहराई। डिफ़ॉल्ट 1 है। |
| [embed_true_type_fonts](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/embed_true_type_fonts/) | embed_true_type_fonts प्रॉपर्टी निर्धारित करती है कि क्या ट्रू टाइप फ़ॉन्ट्स आउटपुट दस्तावेज़ में एम्बेड किए जाएँ। डिफ़ॉल्ट True है। |
| [font_config_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_config_substitution_enabled/) | यह प्रॉपर्टी सिस्टम FontConfig के आधार पर लापता फ़ॉन्ट्स के स्वचालित प्रतिस्थापन को सक्षम करती है। डिफ़ॉल्ट False है। |
| [font_info_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_info_substitution_enabled/) | फ़्लैग जो दस्तावेज़ में FontInfo के आधार पर लापता फ़ॉन्ट्स के स्वचालित प्रतिस्थापन को सक्षम करता है। डिफ़ॉल्ट: False। |
| [font_name_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_name_substitution_enabled/) | यह प्रॉपर्टी दर्शाती है कि क्या लापता फ़ॉन्ट्स फ़ॉन्ट नाम के आधार पर स्वचालित रूप से प्रतिस्थापित किए जाते हैं। डिफ़ॉल्ट: False। |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_substitutes/) | WordProcessing दस्तावेज़ रूपांतरण के दौरान उपयोग किए जाने वाले फ़ॉन्ट प्रतिस्थापन। |
| [font_transformations](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_transformations/) | दस्तावेज़ लोडिंग और फ़ॉन्ट प्रतिस्थापन पूर्ण होने के बाद लागू किए गए फ़ॉन्ट ट्रांसफ़ॉर्मेशन, जो दस्तावेज़ में किसी भी फ़ॉन्ट को संशोधित करने की अनुमति देते हैं, जिसमें सफलतापूर्वक लोड किए गए फ़ॉन्ट भी शामिल हैं। |
| [format](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/format/) | इनपुट दस्तावेज़ फ़ाइल प्रकार। |
| [hide_word_tracked_changes](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/hide_word_tracked_changes/) | hide_word_tracked_changes प्रॉपर्टी Word दस्तावेज़ों के लिए मार्कअप और ट्रैक चेंजेज़ को छिपाती है। |
| [hyphenation_options](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/hyphenation_options/) | WordProcessing दस्तावेज़ों के लिए हाइफ़नेशन विकल्प। |
| [keep_date_field_original_value](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/keep_date_field_original_value/) | keep_date_field_original_value प्रॉपर्टी निर्धारित करती है कि क्या तिथि फ़ील्ड का मूल मान रखा जाए। डिफ़ॉल्ट False है। |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/margin_settings/) | मार्जिन सेटिंग्स। |
| [page_numbering](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/page_numbering/) | रूपांतरित दस्तावेज़ के लिए पेज नंबरिंग जेनरेशन फ़्लैग (डिफ़ॉल्ट: False)। |
| [password](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/password/) | संरक्षित दस्तावेज़ को अनप्रोटेक्ट करने के लिए पासवर्ड। |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/preserve_document_structure/) | PDF में परिवर्तित करते समय दस्तावेज़ संरचना को संरक्षित किया जाना चाहिए या नहीं, यह दर्शाने वाला फ़्लैग (डिफ़ॉल्ट रूप में False)। |
| [preserve_form_fields](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/preserve_form_fields/) | यह प्रॉपर्टी दर्शाती है कि परिणामस्वरूप PDF में Microsoft Word फ़ॉर्म फ़ील्ड्स को फ़ॉर्म फ़ील्ड्स के रूप में संरक्षित किया जाता है या टेक्स्ट में परिवर्तित किया जाता है। डिफ़ॉल्ट रूप में False। |
| [show_full_commenter_name](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/show_full_commenter_name/) | जब True सेट किया जाता है तो टिप्पणी में पूर्ण टिप्पणीकर्ता का नाम दिखाया जाता है। डिफ़ॉल्ट रूप में False। |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/size_settings/) | WordProcessing दस्तावेज़ के आकार सेटिंग्स ([`IPageSizeOptions`](/conversion/python-net/groupdocs.conversion.options/ipagesizeoptions/)). |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/skip_external_resources/) | दस्तावेज़ लोड करते समय बाहरी संसाधनों को छोड़ दिया जाए या नहीं, यह निर्धारित करने वाला फ़्लैग। |
| [update_fields](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/update_fields/) | लोड करने के बाद फ़ील्ड्स को अपडेट करने का विकल्प। डिफ़ॉल्ट: False। |
| [update_page_layout](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/update_page_layout/) | लोड करने के बाद पेज लेआउट अपडेट किया जाता है। डिफ़ॉल्ट: False। |
| [use_text_shaper](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/use_text_shaper/) | बेहतर कर्निंग डिस्प्ले के लिए टेक्स्ट शेपर का उपयोग किया जाए या नहीं, यह दर्शाने वाली प्रॉपर्टी। डिफ़ॉल्ट रूप में False। |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/whitelisted_resources/) | बाहरी सामग्री लोड करने के लिए व्हाइटलिस्टेड संसाधन, जो [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/) को लागू करता है। |

### उदाहरण

```python
from groupdocs.conversion.options.load import WordProcessingLoadOptions

load_options = WordProcessingLoadOptions()
load_options.password = "secret"
```

### Guides
`WordProcessingLoadOptions` का उपयोग करने वाले टास्क गाइड्स:

* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)

### साथ ही देखें
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
