---
title: "compress विधि"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "परिवर्तन परिणामों को संपीड़ित करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/compress/
is_root: false
weight: 1010
---


## compress {#options}

परिवर्तन परिणामों को संपीड़ित करता है।

एंट्री चरण पर एक संकुचित‑स्ट्रीम हैंडलर को [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) के माध्यम से ( `OnCompressionCompleted` सेट करके) पंजीकृत करें, बजाय इसके कि लौटाए गए इंटरफ़ेस पर पुरानी फ़्लुएंट चेन मेथड का उपयोग किया जाए।

```python
def compress(self, options):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| options | `CompressionConvertOptions` | संकुचन रूपांतरण विकल्प। |

**Returns:** Continuation that proceeds to `Convert`.

### साथ ही देखें
* class [`IConversionOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/)
