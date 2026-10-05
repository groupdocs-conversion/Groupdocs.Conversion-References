---
title: "فئة WebLoadOptions"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يوفر خيارات لتحميل مستندات الويب."
type: docs
url: /ar/python-net/groupdocs.conversion.options.load/webloadoptions/
is_root: false
weight: 550
---


## WebLoadOptions class

يوفر خيارات لتحميل مستندات الويب.

يعرض نوع WebLoadOptions الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/__init__/) | يُنشئ مثلاً جديدًا من [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/). |

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
| [base_path](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/base_path/) | المسار/الرابط الأساسي للـ html. |
| [configure_headers](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/configure_headers/) | الإجراء المستخدم لتكوين رؤوس الطلب، حيث المعامل الأول هو Uri. |
| [credentials_provider](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/credentials_provider/) | مُزود بيانات الاعتماد للـ Uri. |
| [custom_css_style](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/custom_css_style/) | الخاصية تُطبق [`ICustomCssStyleOptions.custom_css_style`](/conversion/python-net/groupdocs.conversion.options.load/icustomcssstyleoptions/custom_css_style/). |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/encoding/) | الترميز الذي سيُستخدم عند تحميل مستند الويب. إذا تم تعيينه إلى None، سيتم تحديد الترميز من سمة مجموعة الأحرف في المستند. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/format/) | نوع ملف المستند المدخل. |
| [html_rendering_mode](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/html_rendering_mode/) | وضع عرض HTML يتحكم في كيفية عرض محتوى HTML. القيمة الافتراضية: AbsolutePositioning. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/margin_settings/) | إعدادات الهوامش. |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/orientation_settings/) | إعدادات الاتجاه. |
| [page_layout_options](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/page_layout_options/) | خيارات تخطيط الصفحة المستخدمة عند تحميل مستندات الويب. |
| [page_numbering](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/page_numbering/) | العلم الذي يفعّل أو يعطل إنشاء ترقيم الصفحات في المستند المحوّل. القيمة الافتراضية: False. |
| [resource_loading_timeout](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/resource_loading_timeout/) | مهلة تحميل الموارد الخارجية. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/size_settings/) | إعدادات الحجم. |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/skip_external_resources/) | الخاصية تُطبق [`IResourceLoadingOptions.skip_external_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/skip_external_resources/). |
| [use_pdf](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/use_pdf/) | الخاصية تشير إلى ما إذا كان سيتم استخدام PDF للتحويل (القيمة الافتراضية: False). |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/whitelisted_resources/) | خاصية الموارد المسموح بها تُطبق [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/). |
| [zoom](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/zoom/) | مستوى التكبير كنسبة مئوية يُطبق على وسم `<body>` الخاص بالمستند قبل التحويل، مما يغيّر مظهر المستند البصري. |

### انظر أيضًا
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
