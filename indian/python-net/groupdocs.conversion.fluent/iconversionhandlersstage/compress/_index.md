---
title: "compress विधि"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "परिवर्तन परिणामों को संपीड़ित करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress/
is_root: false
weight: 1010
---


## compress {#options}

परिवर्तन परिणामों को संपीड़ित करता है।

प्रवेश चरण पर एक संकुचित‑स्ट्रीम हैंडलर पंजीकृत करें via [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (setting `OnCompressionCompleted`) के बजाय लौटाए गए इंटरफ़ेस पर पुरानी फ़्लुएंट चेन मेथड का उपयोग करने के।

```python
def compress(self, options):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| options | `CompressionConvertOptions` | संपीड़न रूपांतरण विकल्प |

**Returns:** Continuation that proceeds to `Convert`.

### साथ ही देखें
* class [`IConversionHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/)
