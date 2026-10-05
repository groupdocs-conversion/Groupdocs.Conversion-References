---
title: "طريقة التحميل"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يضبط اسم ملف المستند المصدر."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/load/
is_root: false
weight: 1010
---


## load {#file_name}

يضبط اسم ملف المستند المصدر.

```python
def load(self, file_name):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_name | `str` | المستند المصدر. |

## load {#file_name}

تعيين مصفوفة مستندات المصدر.

```python
def load(self, file_name):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_name | `list[str]` | مجموعة من المستندات المصدر. |

## load {#document_stream_provider}

اضبط تدفق المستند المصدر.

```python
def load(self, document_stream_provider):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| document_stream_provider | `Func[io.RawIOBase]` | مزود تدفق مستند المصدر |

| يُثير | الوصف |
| :- | :- |
| `InvalidConverterSettingsException` | إذا فشل التحقق من صحة إعدادات المحول، سيتم رمي هذا الاستثناء |

## load {#document_stream_provider}

تعيين مصفوفة تدفقات مستند المصدر.

```python
def load(self, document_stream_provider):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| document_stream_provider | `Func[list[io.RawIOBase]]` | مزود تدفقات المستند المصدر. |

| يُثير | الوصف |
| :- | :- |
| `InvalidConverterSettingsException` | إذا فشل التحقق من إعدادات المحول. |

### انظر أيضًا
* class [`IConversionSettingsOrConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/)
