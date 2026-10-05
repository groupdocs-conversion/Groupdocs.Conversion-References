---
title: "compress विधि"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "रूपांतरण परिणामों को संकुचित करता है; प्रवेश चरण पर एक संकुचित‑स्ट्रीम हैंडलर पंजीकृत करें IConversionSettings.withevents (setting OnCompressionCompleted) के बजाय पुरानी फ़्लुएंट…"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress/
is_root: false
weight: 1010
---


## compress {#options}

परिवर्तन परिणामों को संपीड़ित करता है; प्रविष्टि चरण में [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) के माध्यम से एक संपीड़ित‑स्ट्रीम हैंडलर पंजीकृत करें (`OnCompressionCompleted` सेट करते हुए) बजाय पुरानी सहज श्रृंखला विधि के उपयोग के।

```python
def compress(self, options):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| options | `CompressionConvertOptions` | संकुचन रूपांतरण विकल्प। |

**Returns:** Continuation that proceeds to `Convert`.

### साथ ही देखें
* class [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/)
