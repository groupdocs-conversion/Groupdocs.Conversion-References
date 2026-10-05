---
title: "compress विधि"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "रूपांतरण परिणामों को संकुचित करता है और एक निरंतरता लौटाता है जो Convert को आगे बढ़ाती है।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/compress/
is_root: false
weight: 1010
---


## compress {#options}

परिवर्तन परिणामों को संपीड़ित करता है और एक निरंतरता लौटाता है जो `Convert` की ओर आगे बढ़ती है।

प्रवेश चरण पर एक संकुचित‑स्ट्रीम हैंडलर को [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) के माध्यम से पंजीकृत करें (सेटिंग `OnCompressionCompleted`) बजाय इसके कि लौटाए गए इंटरफ़ेस पर पुरानी फ़्लुएंट चेन मेथड का उपयोग किया जाए।

```python
def compress(self, options):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| options | `CompressionConvertOptions` | संकुचन रूपांतरण विकल्प। |

**Returns:** Continuation that proceeds to `Convert`.

### साथ ही देखें
* class [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/)
