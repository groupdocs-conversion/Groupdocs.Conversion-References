---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يُنشئ مثيلًا جديدًا من Converter."
type: docs
url: /ar/python-net/groupdocs.conversion/converter/__init__/
is_root: false
weight: 10
---


## __init__ {#source_stream_provider}

يُنشئ مثيلًا جديدًا من Converter.

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | الطريقة التي تُرجع تدفقًا قابلًا للقراءة. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | يتم رفع الاستثناء عندما تكون `source_stream_provider` None. |

### مثال

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-settings}

يُنشئ مثيلًا جديدًا لـ [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

اعرف المزيد

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider, settings):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | الطريقة التي تُرجع تدفقًا قابلًا للقراءة. |
| settings | `Func[ConverterSettings]` | إعدادات Converter. |

### مثال

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-load_options-settings}

يُنشئ مثيلًا جديدًا لـ [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider, load_options, settings):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | قابل للاستدعاء يُعيد تدفق `io.RawIOBase` قابل للقراءة. |
| load_options | `Func[LoadContext, LoadOptions]` | قابل للاستدعاء [[`LoadContext`], `GroupDocs.Conversion.LoadOptions`] الذي يوفر خيارات التحميل للمستند. يحتوي معامل `LoadContext` على معلومات حول المستند الجاري تحميله. |
| settings | `Func[ConverterSettings]` | `ConverterSettings` يحدد إعدادات المحول. |

### مثال

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-load_options-settings-events}

يُنشئ Converter جديدًا مع أحداث تحويل صريحة.

```python
def __init__(self, source_stream_provider, load_options, settings, events):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | قابل للاستدعاء يُعيد تدفقًا قابلًا للقراءة. |
| load_options | `Func[LoadContext, LoadOptions]` | قابل للاستدعاء يوفر خيارات التحميل للمستند. |
| settings | `Func[ConverterSettings]` | إعدادات المحول. |
| events | `Func[ConversionEvents]` | قابل للاستدعاء يوفر `ConversionEvents` المجمعة المسجلة طوال عمر المحول. |

## __init__ {#source_stream_provider-settings-events}

يُنشئ مثيلًا جديدًا من Converter مع أحداث تحويل صريحة.

```python
def __init__(self, source_stream_provider, settings, events):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | قابل للاستدعاء يُعيد تدفقًا قابلًا للقراءة. |
| settings | `Func[ConverterSettings]` | إعدادات المحول. |
| events | `Func[ConversionEvents]` | المندوب الذي يوفر `ConversionEvents` المجمعة المسجلة طوال عمر المحول. |

### مثال

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path}

يُنشئ مثيلًا جديدًا من Converter.

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | `str` | مسار الملف للمستند المصدر. |

### مثال

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-settings}

يُنشئ مثيلًا جديدًا لـ [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

اعرف المزيد

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path, settings):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | `str` | مسار الملف للمستند المصدر. |
| settings | `Func[ConverterSettings]` | إعدادات Converter. |

### مثال

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-load_options-settings}

يُنشئ مثيلًا جديدًا من فئة [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

اعرف المزيد

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: <https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources>
- More about document loading options dependent on file type: <https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types>

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | `str` | مسار الملف للمستند المصدر. |
| load_options | `Func[LoadContext, LoadOptions]` | المندوب الذي يوفر خيارات التحميل للمستند. التوقيع: `Func<LoadContext, LoadOptions>`. يحتوي معامل `LoadContext` على معلومات حول المستند الجاري تحميله. |
| settings | `Func[ConverterSettings]` | إعدادات Converter. |

### مثال

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-load_options-settings-events}

يُنشئ Converter جديدًا مع أحداث تحويل صريحة.

```python
def __init__(self, file_path, load_options, settings, events):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | `str` | مسار الملف للمستند المصدر. |
| load_options | `Func[LoadContext, LoadOptions]` | المندوب الذي يوفر خيارات التحميل للمستند. |
| settings | `Func[ConverterSettings]` | إعدادات Converter. |
| events | `Func[ConversionEvents]` | المندوب الذي يوفر `ConversionEvents` المجمعة المسجلة طوال عمر المحول. |

### مثال

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-settings-events}

يُنشئ Converter جديدًا مع أحداث تحويل صريحة.

```python
def __init__(self, file_path, settings, events):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | `str` | مسار الملف للمستند المصدر. |
| settings | `Func[ConverterSettings]` | إعدادات Converter. |
| events | `Func[ConversionEvents]` | المندوب الذي يوفر ConversionEvents المجمعة المسجلة طوال عمر المحول. |

### مثال

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### انظر أيضًا
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
