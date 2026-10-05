---
title: "طريقة set"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يدرج إدخالًا في الذاكرة المؤقتة."
type: docs
url: /ar/python-net/groupdocs.conversion.caching/filecache/set/
is_root: false
weight: 1040
---


## set {#key-value}

يدرج إدخالًا في الذاكرة المؤقتة.

```python
def set(self, key, value):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| key | `str` | معرّف فريد لمدخل ذاكرة التخزين المؤقت. |
| value | `Any` | الكائن المراد إدراجه. |

### مثال

```python
from groupdocs.conversion import ConverterSettings, FileCache

# إنشاء إعدادات المحول باستخدام ذاكرة تخزين مؤقتة قائمة على الملفات
settings = ConverterSettings()
settings.cache = FileCache()

# تخزين كائن في الذاكرة المؤقتة
settings.cache.set("my_document", document)
```

### انظر أيضًا
* class [`FileCache`](/conversion/python-net/groupdocs.conversion.caching/filecache/)
