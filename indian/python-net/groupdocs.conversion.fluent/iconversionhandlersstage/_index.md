---
title: "IConversionHandlersStage क्लास"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "रूपांतरण हैंडलर्स चरण को सपाट रूप में दर्शाता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/
is_root: false
weight: 270
---


## IConversionHandlersStage class

रूपांतरण हैंडलर्स चरण को सपाट रूप में दर्शाता है।

`OnConversionCompleted` या `OnConversionFailed` को किसी भी क्रम में और किसी भी संख्या में सेट करने की अनुमति देता है, `Convert` / `Compress` की ओर बढ़ने से पहले। घटनाओं को इस चरण में करने के बजाय प्रारंभिक चरण में [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) के माध्यम से पंजीकृत किया जाना चाहिए।

IConversionHandlersStage प्रकार निम्नलिखित सदस्य उजागर करता है:

### विधियाँ
| विधि | विवरण |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress/#options) | परिवर्तन परिणामों को संपीड़ित करता है। |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/convert/) | परिवर्तन श्रृंखला को निष्पादित करें। |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed/#on_completed) | एक कॉलबैक पंजीकृत करता है जिसे दस्तावेज़ परिवर्तन सफलतापूर्वक पूर्ण होने पर बुलाया जाएगा, पुनः‑आह्वान पर पहले सेट किए गए हैंडलर को बदलते हुए। |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed/#on_failed) | जब दस्तावेज़ रूपांतरण विफल हो जाए तो कॉलबैक को पंजीकृत करता है। |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed_action/) |  |

### साथ ही देखें
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
