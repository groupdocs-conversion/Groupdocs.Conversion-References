---
title: "लोड मेथड"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "स्रोत दस्तावेज़ फ़ाइल नाम सेट करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionfrom/load/
is_root: false
weight: 1010
---


## load {#file_name}

स्रोत दस्तावेज़ फ़ाइल नाम सेट करता है।

```python
def load(self, file_name):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_name | `str` | स्रोत दस्तावेज़। |

## load {#file_name}

स्रोत दस्तावेज़ों की सरणी सेट करता है।

```python
def load(self, file_name):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_name | `list[str]` | स्रोत दस्तावेज़ों का सेट। |

## load {#document_stream_provider}

स्रोत दस्तावेज़ स्ट्रीम सेट करें।

```python
def load(self, document_stream_provider):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| document_stream_provider | `Func[io.RawIOBase]` | स्रोत दस्तावेज़ स्ट्रीम प्रदाता। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `InvalidConverterSettingsException` | यदि कनवर्टर सेटिंग्स का सत्यापन विफल हो जाता है। |

## load {#document_stream_provider}

स्रोत दस्तावेज़ स्ट्रीम प्रदाता सेट करता है।

```python
def load(self, document_stream_provider):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| document_stream_provider | `Func[list[io.RawIOBase]]` | स्रोत दस्तावेज़ स्ट्रीम्स प्रदाता। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `InvalidConverterSettingsException` | यदि कनवर्टर सेटिंग्स का सत्यापन विफल हो जाता है। |

### साथ ही देखें
* class [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/)
