---
title: "DocumentInfo فئة"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "التنفيذ الأساسي لاسترجاع معلومات المستند المتعدد الأشكال."
type: docs
url: /ar/python-net/groupdocs.conversion.contracts/documentinfo/
is_root: false
weight: 120
---


## DocumentInfo class

التنفيذ الأساسي لاسترجاع معلومات المستند المتعدد الأشكال.

يتم إرجاع الكائنات بواسطة `Converter.get_document_info()` وتكشف عن بيانات التعريف مثل التنسيق، عدد الصفحات، تاريخ الإنشاء، الحجم، والخصائص الخاصة بالتنسيق.

نوع DocumentInfo يكشف عن الأعضاء التالية:

### الطرق
| طريقة | الوصف |
| :- | :- |
| [get](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get/) |  |
| [get_file](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get_file/) |  |
| [get_string](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get_string/) |  |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [creation_date](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/creation_date/) | تاريخ إنشاء المستند. |
| [format](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/format/) | تنسيق المستند. |
| [pages_count](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/pages_count/) | العدد الإجمالي للصفحات في المستند. |
| [property_names](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/property_names/) | الخاصية تنفذ [`IDocumentInfo.property_names`](/conversion/python-net/groupdocs.conversion.contracts/idocumentinfo/property_names/). |
| [size](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/size/) | حجم المستند بالبايت. |

### مثال

```python
from groupdocs.conversion import Converter

def show_document_info(path):
    with Converter(path) as converter:
        info = converter.get_document_info()
        print("Format:", info.format)
        print("Pages count:", info.pages_count)
        print("Creation date:", info.creation_date)
        print("Size (bytes):", info.size)

# مثال على الاستخدام
show_document_info("./lorem-ipsum.txt")
```

### انظر أيضًا
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
