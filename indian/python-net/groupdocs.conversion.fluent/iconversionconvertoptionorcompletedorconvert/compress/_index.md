---
title: "compress विधि"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "रूपांतरण के परिणामों को संपीड़ित करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/compress/
is_root: false
weight: 1010
---


## compress {#options}

रूपांतरण के परिणामों को संपीड़ित करता है।

संपीड़ित‑स्ट्रीम हैंडलर को एंट्री चरण पर [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) के माध्यम से (सेटिंग `OnCompressionCompleted`) पंजीकृत करें, बजाय इसके कि लौटाए गए इंटरफ़ेस पर पुरानी फ़्लुएंट चेन मेथड का उपयोग किया जाए।

```python
def compress(self, options):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| options | `CompressionConvertOptions` | संकुचन रूपांतरण विकल्प। |

**Returns:** Continuation that proceeds to `Convert`.

### साथ ही देखें
* class [`IConversionConvertOptionOrCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/)
