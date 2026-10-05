---
title: "set_license मेथड"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "वर्तमान प्रक्रिया में एक लाइसेंस लागू करें।"
type: docs
url: /hi/python-net/groupdocs.conversion/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

वर्तमान प्रक्रिया में एक लाइसेंस लागू करें।

```python
def set_license(self, license_source):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| license_source |  | या तो एक स्ट्रिंग पाथ जो ``.lic`` फ़ाइल की ओर इशारा करता है या एक रीडेबल फ़ाइल‑जैसा ऑब्जेक्ट जो लाइसेंस बाइट्स देता है। फ़ाइल‑जैसे इनपुट को ब्रिज को पास करने से पहले एक अस्थायी फ़ाइल में लिखा जाता है। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `TypeError` | यदि ``license_source`` न तो स्ट्रिंग पाथ है और न ही रीडेबल फ़ाइल‑जैसा ऑब्जेक्ट। |

### साथ ही देखें
* class [`License`](/conversion/python-net/groupdocs.conversion/license/)
