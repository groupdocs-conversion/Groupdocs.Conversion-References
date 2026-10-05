---
title: "with_options मेथड"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "परिवर्तन विकल्प सेट करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionconvertbypageoptions/with_options/
is_root: false
weight: 1010
---


## with_options {#convert_options}

परिवर्तन विकल्प सेट करता है।

```python
def with_options(self, convert_options):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| convert_options | `ConvertOptions` | रूपांतरण विकल्प |

**Returns:** Interface to continue conversion building.

## with_options {#convert_options_provider}

परिवर्तन विकल्प सेट करें।

```python
def with_options(self, convert_options_provider):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | रूपांतरण विकल्प। कॉलेबल एक `ConvertContext` प्राप्त करता है। |

**Returns:** Interface to continue conversion building.

### साथ ही देखें
* class [`IConversionConvertByPageOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertbypageoptions/)
