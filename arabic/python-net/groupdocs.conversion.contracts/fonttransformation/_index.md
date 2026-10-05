---
title: "الفئة FontTransformation"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يصف تكوين تحويل الخط بما في ذلك سمات الخط، المطبق بعد تحميل المستند واستبدال الخط."
type: docs
url: /ar/python-net/groupdocs.conversion.contracts/fonttransformation/
is_root: false
weight: 200
---


## FontTransformation class

يصف تكوين تحويل الخط بما في ذلك سمات الخط، المطبق بعد تحميل المستند واستبدال الخط.

يعرض نوع FontTransformation الأعضاء التالية:

### الطرق
| طريقة | الوصف |
| :- | :- |
| [create](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create/#original_font-replacement_font) | إنشاء تحويل خط مع مطابقة دقيقة للخط (يجب أن يتطابق الحجم والنمط). |
| [create_by_name](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create_by_name/#original_font_name-replacement_font_name) | إنشاء تحويل خط بالاسم فقط، يطابق أي حجم ونمط، مع الحفاظ على حجم ونمط الخط الأصلي في الخط البديل. |
| [create_flexible](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create_flexible/#original_font-replacement_font-match_any_size-match_any_style) | إنشاء تحويل خط مع خيارات مطابقة مرنة. |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | يحدد ما إذا كان مثيلان لكائنين متساويين. (موروث من [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (موروث من [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (موروث من [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | يعمل كدالة التجزئة الافتراضية. (موروث من [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [match_any_size](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/match_any_size/) | تشير الخاصية إلى ما إذا كان يتم مطابقة أي حجم للخط الأصلي (true) أو فقط حجم الخط المحدد في `OriginalFont` (false). |
| [match_any_style](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/match_any_style/) | تحدد الخاصية ما إذا كان يتم مطابقة أي نمط للخط الأصلي (bold, italic, underline) (True) أو يلزم النمط المحدد في `OriginalFont` (False). |
| [original_font](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/original_font/) | مواصفات الخط الأصلي للمطابقة والاستبدال. |
| [replacement_font](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/replacement_font/) | مواصفات الخط البديل. |

### انظر أيضًا
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
