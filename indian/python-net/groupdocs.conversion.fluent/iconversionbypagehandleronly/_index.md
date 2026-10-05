---
title: "IConversionByPageHandlerOnly क्लास"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "केवल पृष्ठ-वार रूपांतरण हैंडलर्स सेट करने के लिए एक सहज इंटरफ़ेस प्रदान करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/
is_root: false
weight: 50
---


## IConversionByPageHandlerOnly class

केवल पृष्ठ-वार रूपांतरण हैंडलर्स सेट करने के लिए एक सहज इंटरफ़ेस प्रदान करता है।

`Convert`/`Compress` के लिए [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/) को विरासत में लेता है; चरणबद्ध `OnConversion*` ओवरलोड को `new` कुंजीशब्द के माध्यम से रखा जाता है ताकि पिछली संगतता बनी रहे।

IConversionByPageHandlerOnly प्रकार निम्नलिखित सदस्य उजागर करता है:

### विधियाँ
| विधि | विवरण |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress/#options) | परिवर्तन परिणामों को संपीड़ित करता है; प्रविष्टि चरण में [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) के माध्यम से एक संपीड़ित‑स्ट्रीम हैंडलर पंजीकृत करें (`OnCompressionCompleted` सेट करते हुए) बजाय पुरानी सहज श्रृंखला विधि के उपयोग के। |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/convert/) | परिवर्तन श्रृंखला को निष्पादित करें। |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed/#on_completed) | जब पृष्ठ रूपांतरण सफलतापूर्वक पूर्ण हो जाए तो कॉलबैक को पंजीकृत करता है। |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_failed/#on_failed) | जब पृष्ठ रूपांतरण विफल हो जाए तो कॉलबैक को पंजीकृत करता है। |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_failed_action/) |  |

### साथ ही देखें
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
