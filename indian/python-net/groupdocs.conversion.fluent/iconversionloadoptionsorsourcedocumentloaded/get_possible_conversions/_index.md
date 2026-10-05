---
title: "get_possible_conversions मेथड"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "स्रोत दस्तावेज़ के लिए संभावित रूपांतरणों को प्राप्त करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/get_possible_conversions/
is_root: false
weight: 1080
---


## get_possible_conversions

स्रोत दस्तावेज़ के लिए संभावित रूपांतरणों को प्राप्त करता है।

वापसी किया गया ऑब्जेक्ट सभी कन्वर्ज़न विकल्पों तक पहुंच प्रदान करता है, जिसमें प्राथमिक और द्वितीयक फ़ॉर्मेट शामिल हैं, और स्रोत फ़ाइल के बारे में मेटाडेटा भी शामिल करता है।

```python
def get_possible_conversions(self):
    ...
```

**Returns:** GroupDocs.Conversion.Fluent.PossibleConversions: An object containing the source description and collections of conversion formats.

### उदाहरण

```python
from groupdocs.conversion import Converter

with Converter("report.xlsx") as converter:
    conversions = converter.get_possible_conversions()
    primary = [c.format for c in conversions.all if c.is_primary]
    print(f"Primary targets for {conversions.source.description}: {primary}")
```

### साथ ही देखें
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
