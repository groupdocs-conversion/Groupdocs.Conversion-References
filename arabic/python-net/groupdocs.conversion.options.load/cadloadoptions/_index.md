---
title: "فئة CadLoadOptions"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يوفر خيارات لتحميل مستندات CAD."
type: docs
url: /ar/python-net/groupdocs.conversion.options.load/cadloadoptions/
is_root: false
weight: 60
---


## CadLoadOptions class

يوفر خيارات لتحميل مستندات CAD.

نوع CadLoadOptions يعرض الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/__init__/) | ينشئ مثيلاً جديداً من فئة [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/). |

### الطرق
| طريقة | الوصف |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | يحدد ما إذا كان مثيلان لكائنين متساويين. (موروث من [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (موروث من [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (موروث من [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | يعمل كدالة التجزئة الافتراضية. (موروث من [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [background_color](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/background_color/) | لون الخلفية. |
| [ctb_sources](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/ctb_sources/) | مصادر CTB. |
| [draw_color](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/draw_color/) | لون المقدمة. |
| [draw_type](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/draw_type/) | نوع الرسم. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/format/) | نوع ملف المستند المدخل. |
| [layout_names](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) | أسماء التخطيط التي سيتم تحويلها. |
| [layout_scope](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/) | نطاق التخطيط الذي يحدد أي مساحات الرسم يتم تحويلها. القيمة الافتراضية هي [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/)، والتي لا تقيد التحويل. يتم تجاهلها عندما يتم توفير [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/)، لأن أسماء التخطيط الصريحة دائمًا تفوز. تُعامل القيمة `None` كـ [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/). |

### انظر أيضًا
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
