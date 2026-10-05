---
title: "فئة TxtLoadOptions"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "خيارات لتحميل مستندات Txt."
type: docs
url: /ar/python-net/groupdocs.conversion.options.load/txtloadoptions/
is_root: false
weight: 500
---


## TxtLoadOptions class

خيارات لتحميل مستندات Txt.

إعدادات الخط للنص العادي:

نظرًا لأن ملفات TXT لا تحتوي على معلومات الخط، استخدم DefaultTextFont لتحديد الخط لعرض محتوى النص العادي أثناء التحويل.

نوع TxtLoadOptions يعرض الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/__init__/) | ينشئ مثيلًا جديدًا من [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/). |

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
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/default_font/) | الخط المستخدم عند عرض محتوى النص العادي أثناء التحويل. الافتراضي: Arial 10pt. |
| [detect_numbering_with_whitespaces](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/detect_numbering_with_whitespaces/) | الخاصية تحدد كيفية التعرف على عناصر القوائم المرقمة عند تحويل مستند نص عادي. القيمة الافتراضية هي True. |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/encoding/) | الترميز المستخدم عند تحميل مستند Txt. يمكن أن يكون None. القيمة الافتراضية هي None. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/format/) | نوع ملف المستند المدخل. |
| [leading_spaces_options](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/leading_spaces_options/) | الخيار المفضل للتعامل مع المسافات البادئة. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/margin_settings/) | إعدادات الهوامش، كما هو معرف بواسطة [`IPageMarginOptions`](/conversion/python-net/groupdocs.conversion.options/ipagemarginoptions/). |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/size_settings/) | خيارات حجم الصفحة لتحميل مستند TXT. |
| [trailing_spaces_options](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/trailing_spaces_options/) | الخيار المفضل لمعالجة المسافات المتتبقية. القيمة الافتراضية هي [`TxtTrailingSpacesOptions.trim`](/conversion/python-net/groupdocs.conversion.options.load/txttrailingspacesoptions/). |

### انظر أيضًا
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
