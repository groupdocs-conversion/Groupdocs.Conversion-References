---
title: "طريقة التحميل"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "تكوين المستند المصدر للتحويل."
type: docs
url: /ar/python-net/groupdocs.conversion/fluentconverter/load/
is_root: false
weight: 1010
---


## load {#file_name}

تكوين المستند المصدر للتحويل.

```python
def load(cls, file_name):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_name | `str` | المستند المصدر. |

## load {#file_name}

تكوين مجموعة من المستندات المصدر.

```python
def load(cls, file_name):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_name | `list[str]` | مصفوفة من ملفات المصدر. |

## load {#document_stream_provider}

تكوين تدفق المستند المصدر.

```python
def load(cls, document_stream_provider):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| document_stream_provider | `Func[io.RawIOBase]` | مزود تدفق المستند المصدر. |

## load {#document_stream_provider}

تكوين مجموعة من تدفقات المستندات المصدر.

```python
def load(cls, document_stream_provider):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| document_stream_provider | `Func[list[io.RawIOBase]]` | مجموعة موفر تدفقات مستندات المصدر. |

### انظر أيضًا
* class [`FluentConverter`](/conversion/python-net/groupdocs.conversion/fluentconverter/)
