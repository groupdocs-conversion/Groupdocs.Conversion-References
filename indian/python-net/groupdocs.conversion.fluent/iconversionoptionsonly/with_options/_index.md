---
title: "with_options मेथड"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "रूपांतरण प्रक्रिया के लिए रूपांतरण विकल्प सेट करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/with_options/
is_root: false
weight: 1010
---


## with_options {#convert_options}

रूपांतरण प्रक्रिया के लिए रूपांतरण विकल्प सेट करता है।

```python
def with_options(self, convert_options):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| convert_options | `ConvertOptions` | रूपांतरण विकल्प। |

**Returns:** Handler setup interface to continue conversion building.

## with_options {#options_provider}

प्रोवाइडर फ़ंक्शन का उपयोग करके रूपांतरण विकल्प सेट करता है।

```python
def with_options(self, options_provider):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| options_provider | `Func[ConvertContext, ConvertOptions]` | एक फ़ंक्शन जो रूपांतरण संदर्भ के आधार पर रूपांतरण विकल्प प्रदान करता है। |

**Returns:** Handler setup interface to continue conversion building.

### साथ ही देखें
* class [`IConversionOptionsOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/)
