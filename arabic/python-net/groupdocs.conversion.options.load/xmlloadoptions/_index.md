---
title: "فئة XmlLoadOptions"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "الخيارات لتحميل مستندات XML."
type: docs
url: /ar/python-net/groupdocs.conversion.options.load/xmlloadoptions/
is_root: false
weight: 590
---


## XmlLoadOptions class

الخيارات لتحميل مستندات XML.

يعرض نوع XmlLoadOptions الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/__init__/) | ينشئ مثلاً جديداً من [`XmlLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/). |

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
| [custom_css_style](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/custom_css_style/) | نمط CSS المخصص الذي سيُطبق على المستند أثناء التحويل. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/format/) | نوع ملف المستند المدخل. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/margin_settings/) | إعدادات هوامش الصفحة. |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/orientation_settings/) | إعدادات توجيه الصفحة. |
| [page_layout_options](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/page_layout_options/) | مقياس تخطيط الصفحة الذي سيُطبق عند تحميل المستند. الافتراضي: لا شيء. |
| [page_numbering](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/page_numbering/) | العلم الخاص بإنشاء ترقيم الصفحات للمستند المحوَّل (القيمة الافتراضية: False). |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/size_settings/) | إعدادات حجم الصفحة. |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/skip_external_resources/) | الخاصية تشير إلى ما إذا كانت الموارد الخارجية محمّلة. |
| [use_as_data_source](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/use_as_data_source/) | يُستخدم مستند XML كمصدر للبيانات. |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/whitelisted_resources/) | الموارد الخارجية التي سيتم تحميلها دائمًا. |
| [xsl_fo_factory](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/xsl_fo_factory/) | تيار مستند XSL-FO لتحويل XML باستخدام ملف ترميز XSL-FO. |
| [xslt_factory](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/xslt_factory/) | تيار مستند XSLT لتحويل XML بإجراء تحويل XSL إلى HTML. |
| [base_path](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/base_path/) | المسار/الرابط الأساسي للـ html. (موروث من [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)) |
| [configure_headers](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/configure_headers/) | الإجراء المستخدم لتكوين رؤوس الطلب، حيث المعامل الأول هو الـ Uri. (موروث من [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)) |
| [credentials_provider](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/credentials_provider/) | مزوّد بيانات الاعتماد للـ Uri. (موروث من [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)) |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/encoding/) | الترميز الذي سيُستخدم عند تحميل المستند الويب. إذا تم تعيينه إلى لا شيء، سيتم تحديد الترميز من خاصية مجموعة الأحرف في المستند. (موروث من [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)) |
| [html_rendering_mode](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/html_rendering_mode/) | وضع عرض HTML يتحكم في كيفية عرض محتوى HTML. الافتراضي: AbsolutePositioning. (موروث من [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)) |
| [resource_loading_timeout](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/resource_loading_timeout/) | مهلة تحميل الموارد الخارجية. (موروث من [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)) |
| [use_pdf](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/use_pdf/) | تشير الخاصية إلى ما إذا كان سيتم استخدام PDF للتحويل (الافتراضي: False). (موروث من [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)) |
| [zoom](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/zoom/) | مستوى التكبير كنسبة مئوية يُطبق على وسم `<body>` في المستند قبل التحويل، مما يغير مظهر المستند البصري. (موروث من [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)) |

### انظر أيضًا
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
