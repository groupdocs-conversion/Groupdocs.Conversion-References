---
title: "طريقة convert_to"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "احفظ المستند المحوّل كملف."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversionto/convert_to/
is_root: false
weight: 1030
---


## convert_to {#file_name}

احفظ المستند المحوّل كملف.

```python
def convert_to(self, file_name):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_name | `str` | المستند المحول |

**Returns:** Options or handler setup interface to continue conversion building

## convert_to {#converted_stream_provider}

يحفظ المستند المحوّل كتيار.

```python
def convert_to(self, converted_stream_provider):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| converted_stream_provider | `Func[SaveContext, io.RawIOBase]` | مزود تدفق المستند المحول. سياق الحفظ. |

**Returns:** Options or handler setup interface to continue conversion building.

### انظر أيضًا
* class [`IConversionTo`](/conversion/python-net/groupdocs.conversion.fluent/iconversionto/)
