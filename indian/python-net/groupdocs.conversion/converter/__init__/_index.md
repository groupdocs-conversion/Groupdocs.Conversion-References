---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "Converter का नया उदाहरण प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion/converter/__init__/
is_root: false
weight: 10
---


## __init__ {#source_stream_provider}

Converter का नया उदाहरण प्रारंभ करता है।

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | वह मेथड जो पढ़ने योग्य स्ट्रीम लौटाता है। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | जब `source_stream_provider` None हो तो उत्पन्न होता है। |

### उदाहरण

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-settings}

नया [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) उदाहरण प्रारंभ करता है।

और अधिक जानें

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider, settings):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | वह मेथड जो पढ़ने योग्य स्ट्रीम लौटाता है। |
| settings | `Func[ConverterSettings]` | कनवर्टर सेटिंग्स। |

### उदाहरण

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-load_options-settings}

नया [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) उदाहरण प्रारंभ करता है।

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider, load_options, settings):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | एक कॉलेबल जो पढ़ने योग्य `io.RawIOBase` स्ट्रीम लौटाता है। |
| load_options | `Func[LoadContext, LoadOptions]` | एक कॉलेबल[[`LoadContext`], `GroupDocs.Conversion.LoadOptions`] जो दस्तावेज़ के लिए लोड विकल्प प्रदान करता है। `LoadContext` पैरामीटर में लोड हो रहे दस्तावेज़ की जानकारी होती है। |
| settings | `Func[ConverterSettings]` | `ConverterSettings` जो कनवर्टर सेटिंग्स निर्दिष्ट करता है। |

### उदाहरण

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-load_options-settings-events}

स्पष्ट रूपांतरण घटनाओं के साथ नया Converter प्रारंभ करता है।

```python
def __init__(self, source_stream_provider, load_options, settings, events):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | एक कॉलेबल जो पढ़ने योग्य स्ट्रीम लौटाता है। |
| load_options | `Func[LoadContext, LoadOptions]` | एक कॉलेबल जो दस्तावेज़ के लिए लोड विकल्प प्रदान करता है। |
| settings | `Func[ConverterSettings]` | कनवर्टर सेटिंग्स। |
| events | `Func[ConversionEvents]` | एक कॉलेबल जो कनवर्टर के जीवनकाल के लिए पंजीकृत सम्मिलित `ConversionEvents` प्रदान करता है। |

## __init__ {#source_stream_provider-settings-events}

स्पष्ट रूपांतरण घटनाओं के साथ नया Converter उदाहरण प्रारंभ करता है।

```python
def __init__(self, source_stream_provider, settings, events):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | एक कॉलेबल जो पढ़ने योग्य स्ट्रीम लौटाता है। |
| settings | `Func[ConverterSettings]` | कनवर्टर सेटिंग्स। |
| events | `Func[ConversionEvents]` | डेलीगेट जो कनवर्टर के जीवनकाल के लिए पंजीकृत सम्मिलित `ConversionEvents` प्रदान करता है। |

### उदाहरण

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path}

नया Converter उदाहरण प्रारंभ करता है।

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | `str` | स्रोत दस्तावेज़ का फ़ाइल पथ। |

### उदाहरण

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-settings}

नया [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) उदाहरण प्रारंभ करता है।

और अधिक जानें

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path, settings):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | `str` | स्रोत दस्तावेज़ का फ़ाइल पथ। |
| settings | `Func[ConverterSettings]` | कनवर्टर सेटिंग्स। |

### उदाहरण

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-load_options-settings}

[`Converter`](/conversion/python-net/groupdocs.conversion/converter/) क्लास का नया उदाहरण प्रारंभ करता है।

और अधिक जानें

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: <https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources>
- More about document loading options dependent on file type: <https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types>

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | `str` | स्रोत दस्तावेज़ का फ़ाइल पथ। |
| load_options | `Func[LoadContext, LoadOptions]` | डेलीगेट जो दस्तावेज़ के लिए लोड विकल्प प्रदान करता है। हस्ताक्षर: `Func<LoadContext, LoadOptions>`। `LoadContext` पैरामीटर में लोड हो रहे दस्तावेज़ की जानकारी होती है। |
| settings | `Func[ConverterSettings]` | कनवर्टर सेटिंग्स। |

### उदाहरण

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-load_options-settings-events}

स्पष्ट रूपांतरण घटनाओं के साथ नया Converter प्रारंभ करता है।

```python
def __init__(self, file_path, load_options, settings, events):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | `str` | स्रोत दस्तावेज़ का फ़ाइल पथ। |
| load_options | `Func[LoadContext, LoadOptions]` | डेलीगेट जो दस्तावेज़ के लिए लोड विकल्प प्रदान करता है। |
| settings | `Func[ConverterSettings]` | कनवर्टर सेटिंग्स। |
| events | `Func[ConversionEvents]` | डेलीगेट जो कनवर्टर के जीवनकाल के लिए पंजीकृत सम्मिलित `ConversionEvents` प्रदान करता है। |

### उदाहरण

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-settings-events}

स्पष्ट रूपांतरण घटनाओं के साथ नया Converter प्रारंभ करता है।

```python
def __init__(self, file_path, settings, events):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | `str` | स्रोत दस्तावेज़ का फ़ाइल पथ। |
| settings | `Func[ConverterSettings]` | कनवर्टर सेटिंग्स। |
| events | `Func[ConversionEvents]` | डेलीगेट जो कनवर्टर के जीवनकाल के लिए पंजीकृत सम्मिलित ConversionEvents प्रदान करता है। |

### उदाहरण

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### साथ ही देखें
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
