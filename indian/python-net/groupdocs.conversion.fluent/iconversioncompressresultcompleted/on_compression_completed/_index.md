---
title: "on_compression_completed मेथड"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "संपीड़ित दस्तावेज़ स्ट्रीम प्राप्त करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/on_compression_completed/
is_root: false
weight: 1010
---


## on_compression_completed {#compressed_document_stream}

संपीड़ित दस्तावेज़ स्ट्रीम प्राप्त करता है।

`Compress(CompressionConvertOptions)` सेट होने पर ही सक्रिय होता है।

```python
def on_compression_completed(self, compressed_document_stream):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| compressed_document_stream | `Action[io.RawIOBase]` | संकुचित दस्तावेज़ स्ट्रीम कॉलबैक। |

**Returns:** Interface to continue conversion building.

### साथ ही देखें
* class [`IConversionCompressResultCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/)
