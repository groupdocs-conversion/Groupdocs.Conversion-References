---
title: "convert_by_page_to मेथड"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "रूपांतरित पृष्ठ को स्ट्रीम के रूप में सहेजें।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionto/convert_by_page_to/
is_root: false
weight: 1010
---


## convert_by_page_to {#converted_stream_provider}

रूपांतरित पृष्ठ को स्ट्रीम के रूप में सहेजें।

```python
def convert_by_page_to(self, converted_stream_provider):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| converted_stream_provider | `Func[SavePageContext, io.RawIOBase]` | रूपांतरित दस्तावेज़ पृष्ठ स्ट्रीम प्रदाता। converted_stream_provider arg1arg1: सहेजने का संदर्भ। |

**Returns:** Page options or handler setup interface to continue conversion building.

### साथ ही देखें
* class [`IConversionTo`](/conversion/python-net/groupdocs.conversion.fluent/iconversionto/)
