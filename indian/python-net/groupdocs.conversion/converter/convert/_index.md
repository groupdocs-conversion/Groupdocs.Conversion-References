---
title: "convert विधि"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "स्रोत दस्तावेज़ को रूपांतरित करता है और पूरी रूपांतरित दस्तावेज़ को सहेजता है।"
type: docs
url: /hi/python-net/groupdocs.conversion/converter/convert/
is_root: false
weight: 1010
---


## convert {#target_stream_provider-convert_options}

स्रोत दस्तावेज़ को रूपांतरित करता है और पूरी रूपांतरित दस्तावेज़ को सहेजता है।

और अधिक जानें:
- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, target_stream_provider, convert_options):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| target_stream_provider | `Func[SaveContext, io.RawIOBase]` | एक कॉलेबल जो एक स्ट्रीम प्राप्त करता है और परिवर्तित दस्तावेज़ को उसमें सहेजता है। |
| convert_options | `ConvertOptions` | इच्छित लक्ष्य फ़ाइल प्रकार के लिए विशिष्ट रूपांतरण विकल्प। |

### उदाहरण

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document_to_pdf():
    # इनपुट दस्तावेज़ के साथ Converter को इंस्टैंशिएट करें
    with Converter("./business-plan.docx") as converter:
        # PDF आउटपुट के लिए रूपांतरण विकल्प निर्धारित करें
        pdf_options = PdfConvertOptions()
        # दस्तावेज़ को रूपांतरित करें और PDF के रूप में सहेजें।
        converter.convert("./business-plan.pdf", pdf_options)

if __name__ == "__main__":
    convert_document_to_pdf()
```

## convert {#convert_options-document_completed}

स्रोत दस्तावेज़ को रूपांतरित करता है और संपूर्ण रूपांतरित दस्तावेज़ को सहेजता है।

और अधिक जानें:
- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, convert_options, document_completed):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| convert_options | `ConvertOptions` | वांछित लक्ष्य फ़ाइल प्रकार के लिए विशिष्ट रूपांतरण विकल्प। |
| document_completed | `Action[ConvertedContext]` | डेलीगेट जो परिवर्तित दस्तावेज़ स्ट्रीम प्राप्त करता है। हस्ताक्षर: `Action<ConvertedContext>`। `ConvertedContext` पैरामीटर में परिवर्तित दस्तावेज़ स्ट्रीम और मेटाडेटा शामिल हैं। |

### उदाहरण

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#target_stream_provider-convert_options_provider}

स्रोत दस्तावेज़ को रूपांतरित करता है और संपूर्ण रूपांतरित दस्तावेज़ को सहेजता है।

और अधिक जानें:
- More about document conversion basic scenarios: https://docs.groupdocs.com/display/conversionnet/Convert+document
- Conversion use cases, advanced settings and customizations: https://docs.groupdocs.com/display/conversionnet/Converting

```python
def convert(self, target_stream_provider, convert_options_provider):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| target_stream_provider | `Func[SaveContext, io.RawIOBase]` | Callable[[SaveContext], io.RawIOBase] जो परिवर्तित दस्तावेज़ को सहेजने के लिए स्ट्रीम प्रदान करता है। |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], GroupDocs.Conversion.ConvertOptions] जो रूपांतरण विकल्प प्रदान करता है। |

**Returns:** None.

### उदाहरण

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert(
            lambda ctx: open("output.pdf", "wb"),
            lambda ctx: PdfConvertOptions(),
            cancellationToken=None
        )
```

## convert {#convert_options_provider-document_completed}

स्रोत दस्तावेज़ को रूपांतरित करता है और संपूर्ण रूपांतरित दस्तावेज़ को सहेजता है।

और अधिक जानें

- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, convert_options_provider, document_completed):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], GroupDocs.Conversion.ConvertOptions] रूपांतरण विकल्प प्रदान करता है। `ConvertContext` पैरामीटर में रूपांतरण ऑपरेशन की जानकारी होती है। |
| document_completed | `Action[ConvertedContext]` | Callable[[ConvertedContext], None] परिवर्तित दस्तावेज़ स्ट्रीम प्राप्त करता है। `ConvertedContext` पैरामीटर में परिवर्तित दस्तावेज़ स्ट्रीम और मेटाडेटा होते हैं। |

**Returns:** None.

## convert {#file_path-convert_options}

स्रोत दस्तावेज़ को रूपांतरित करता है और संपूर्ण रूपांतरित दस्तावेज़ को सहेजता है।

और अधिक जानें:
- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, file_path, convert_options):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | `str` | स्रोत दस्तावेज़ का फ़ाइल पथ। |
| convert_options | `ConvertOptions` | वांछित लक्ष्य फ़ाइल प्रकार के लिए विशिष्ट रूपांतरण विकल्प। |

### उदाहरण

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#target_stream_provider-convert_options_provider}

स्रोत दस्तावेज़ को रूपांतरित करता है और रूपांतरित दस्तावेज़ को पृष्ठ दर पृष्ठ सहेजता है।

और अधिक जानें

- More about document conversion basic scenarios: How to convert document in 3 steps (https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: Convert document with advanced settings (https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, target_stream_provider, convert_options_provider):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| target_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Callable[[SavePageContext], io.RawIOBase] जो प्रत्येक परिवर्तित पृष्ठ को सहेजने के लिए स्ट्रीम प्रदान करता है। `SavePageContext` पैरामीटर में पृष्ठ संख्या और दस्तावेज़ जानकारी होती है। |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], ConvertOptions] जो रूपांतरण विकल्प प्रदान करता है। `ConvertContext` पैरामीटर में रूपांतरण ऑपरेशन की जानकारी होती है। |

**Returns:** None.

## convert {#target_stream_provider-convert_options}

स्रोत दस्तावेज़ को रूपांतरित करता है और रूपांतरित दस्तावेज़ को पृष्ठ दर पृष्ठ सहेजता है।

और अधिक जानें
- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, target_stream_provider, convert_options):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| target_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Callable जो प्रत्येक परिवर्तित पृष्ठ को सहेजने के लिए स्ट्रीम प्रदान करता है। हस्ताक्षर: `Func<SavePageContext, Stream>`। `SavePageContext` पैरामीटर में पृष्ठ संख्या और दस्तावेज़ जानकारी होती है। |
| convert_options | `ConvertOptions` | वांछित लक्ष्य फ़ाइल प्रकार के लिए विशिष्ट रूपांतरण विकल्प। |

**Returns:** None.

### उदाहरण

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#convert_options-document_completed}

स्रोत दस्तावेज़ को रूपांतरित करता है और रूपांतरित दस्तावेज़ को पृष्ठ दर पृष्ठ सहेजता है।

और अधिक जानें

- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, convert_options, document_completed):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| convert_options | `ConvertOptions` | वांछित लक्ष्य फ़ाइल प्रकार के लिए विशिष्ट रूपांतरण विकल्प। |
| document_completed | `Action[ConvertedPageContext]` | Callable जो प्रत्येक परिवर्तित पृष्ठ को प्राप्त करता है। `ConvertedPageContext` पैरामीटर में पृष्ठ संख्या, स्ट्रीम, स्रोत फ़ाइल नाम, और लक्ष्य फ़ाइल प्रकार होते हैं। |

### उदाहरण

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("./business-plan.docx") as converter:
    converter.convert("./business-plan.pdf", PdfConvertOptions())
```

## convert {#convert_options_provider-document_completed}

स्रोत दस्तावेज़ को रूपांतरित करता है और रूपांतरित दस्तावेज़ को पृष्ठ दर पृष्ठ सहेजता है।

और अधिक जानें

- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, convert_options_provider, document_completed):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | डेलीगेट जो रूपांतरण विकल्प प्रदान करता है। `ConvertContext` पैरामीटर में रूपांतरण ऑपरेशन की जानकारी होती है। |
| document_completed | `Action[ConvertedPageContext]` | डेलीगेट जो प्रत्येक परिवर्तित पृष्ठ को प्राप्त करता है। `ConvertedPageContext` पैरामीटर में पृष्ठ संख्या, स्ट्रीम, स्रोत फ़ाइल नाम, और लक्ष्य फ़ाइल प्रकार होते हैं। |

### उदाहरण

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

### साथ ही देखें
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
