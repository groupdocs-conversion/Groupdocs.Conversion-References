---
title: "with_options मेथड"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "लोड विकल्प सेट करें।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionloadoptions/with_options/
is_root: false
weight: 1010
---


## with_options {#load_options}

लोड विकल्प सेट करें।

```python
def with_options(self, load_options):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| load_options | `LoadOptions` | लोड विकल्प। |

## with_options {#load_options_provider}

वर्तमान में लोड हो रहे दस्तावेज़ के लिए लोड विकल्प प्रदान करता है।

```python
def with_options(self, load_options_provider):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| load_options_provider | `Func[LoadContext, LoadOptions]` | लोड विकल्प प्रदाता। प्रदाता लोड विकल्प संदर्भ प्राप्त करता है। |

### साथ ही देखें
* class [`IConversionLoadOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptions/)
