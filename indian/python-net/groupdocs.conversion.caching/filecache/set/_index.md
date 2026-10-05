---
title: "सेट मेथड"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "कैश में एक कैश एंट्री डालता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.caching/filecache/set/
is_root: false
weight: 1040
---


## set {#key-value}

कैश में एक कैश एंट्री डालता है।

```python
def set(self, key, value):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| key | `str` | कैश एंट्री के लिए एक अद्वितीय पहचानकर्ता। |
| value | `Any` | डालने के लिए ऑब्जेक्ट। |

### उदाहरण

```python
from groupdocs.conversion import ConverterSettings, FileCache

# फ़ाइल-आधारित कैश के साथ कनवर्टर सेटिंग्स बनाएं
settings = ConverterSettings()
settings.cache = FileCache()

# कैश में एक ऑब्जेक्ट संग्रहीत करें
settings.cache.set("my_document", document)
```

### साथ ही देखें
* class [`FileCache`](/conversion/python-net/groupdocs.conversion.caching/filecache/)
