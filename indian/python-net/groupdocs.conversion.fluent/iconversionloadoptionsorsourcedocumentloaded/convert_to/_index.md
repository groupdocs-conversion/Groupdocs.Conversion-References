---
title: "convert_to मेथड"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "रूपांतरित दस्तावेज़ को फ़ाइल के रूप में सहेजें।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/convert_to/
is_root: false
weight: 1030
---


## convert_to {#file_name}

रूपांतरित दस्तावेज़ को फ़ाइल के रूप में सहेजें।

```python
def convert_to(self, file_name):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_name | `str` | परिवर्तित दस्तावेज़। |

**Returns:** Options or handler setup interface to continue conversion building.

## convert_to {#converted_stream_provider}

रूपांतरित दस्तावेज़ को स्ट्रीम के रूप में सहेजता है।

```python
def convert_to(self, converted_stream_provider):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| converted_stream_provider | `Func[SaveContext, io.RawIOBase]` | रूपांतरित दस्तावेज़ स्ट्रीम प्रदाता। सहेजने का संदर्भ। |

**Returns:** Options or handler setup interface to continue conversion building.

### साथ ही देखें
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
