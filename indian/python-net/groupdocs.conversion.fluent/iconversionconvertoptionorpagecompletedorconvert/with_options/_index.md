---
title: "with_options मेथड"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "परिवर्तन विकल्प सेट करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/with_options/
is_root: false
weight: 1060
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

परिवर्तन विकल्प सेट करता है।

```python
def with_options(self, convert_options_provider):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | कन्वर्ट विकल्प। `ConvertContext` को प्रोवाइडर को पास किया जाता है। |

**Returns:** Interface to continue conversion building.

### साथ ही देखें
* class [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/)
