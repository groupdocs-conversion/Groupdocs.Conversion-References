---
title: "`get_all_possible_conversions` मेथड"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "सभी समर्थित रूपांतरण प्राप्त करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion/converter/get_all_possible_conversions/
is_root: false
weight: 1070
---


## get_all_possible_conversions

सभी समर्थित रूपांतरण प्राप्त करता है।

समर्थित रूपांतरणों के बारे में अधिक जानें:
- [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
- [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

```python
def get_all_possible_conversions(cls):
    ...
```

**Returns:** Collection of all possible conversions.

### उदाहरण

```python
from groupdocs.conversion import Converter

# सभी संभावित रूपांतरण प्राप्त करें
all_conversions = list(Converter.get_all_possible_conversions())
print(f"Total supported source formats: {len(all_conversions)}")
```

### साथ ही देखें
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
