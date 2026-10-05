---
title: "with_options मेथड"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "परिवर्तन विकल्प सेट करें।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/with_options/
is_root: false
weight: 1080
---


## with_options {#convert_options}

परिवर्तन विकल्प सेट करें।

```python
def with_options(self, convert_options):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| convert_options | `ConvertOptions` | रूपांतरण विकल्प |

**Returns:** Interface to continue conversion building

## with_options {#convert_options_provider}

परिवर्तन विकल्प सेट करें।

```python
def with_options(self, convert_options_provider):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | विकल्प रूपांतरित करें। `ConvertContext`। |

**Returns:** Interface to continue conversion building.

### साथ ही देखें
* class [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/)
