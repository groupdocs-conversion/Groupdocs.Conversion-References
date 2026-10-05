---
title: "get_possible_conversions मेथड"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "स्रोत दस्तावेज़ के लिए संभावित रूपांतरणों को प्राप्त करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion/converter/get_possible_conversions/
is_root: false
weight: 1090
---


## get_possible_conversions

स्रोत दस्तावेज़ के लिए संभावित रूपांतरणों को प्राप्त करता है।

- Learn more about supported conversions: [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
- Learn more about available conversions: [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

```python
def get_possible_conversions(self):
    ...
```

**Returns:** PossibleConversions

### उदाहरण

```python
from groupdocs.conversion import Converter

with Converter("report.xlsx") as converter:
    conversions = converter.get_possible_conversions()
    primary = [c.format for c in conversions.all if c.is_primary]
    print(f"Primary targets for {conversions.source.description}: {primary}")
```

### साथ ही देखें
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
