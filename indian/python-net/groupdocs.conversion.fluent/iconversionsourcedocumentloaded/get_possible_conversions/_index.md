---
title: "get_possible_conversions मेथड"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "स्रोत दस्तावेज़ के लिए संभावित रूपांतरणों को प्राप्त करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/get_possible_conversions/
is_root: false
weight: 1080
---


## get_possible_conversions

स्रोत दस्तावेज़ के लिए संभावित रूपांतरणों को प्राप्त करता है।

```python
def get_possible_conversions(self):
    ...
```

### उदाहरण

```python
from groupdocs.conversion import Converter

with Converter("report.xlsx") as converter:
    conversions = converter.get_possible_conversions()
    primary = [c.format for c in conversions.all if c.is_primary]
    print(f"Primary targets for {conversions.source.description}: {primary}")
```

### साथ ही देखें
* class [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/)
