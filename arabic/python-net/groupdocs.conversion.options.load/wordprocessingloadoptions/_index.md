---
title: "فئة WordProcessingLoadOptions"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يوفر خيارات لتحميل مستندات WordProcessing."
type: docs
url: /ar/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/
is_root: false
weight: 580
---


## WordProcessingLoadOptions class

يوفر خيارات لتحميل مستندات WordProcessing.

خط أنابيب معالجة الخطوط:

المرحلة 1 - استبدال الخطوط (أثناء تحميل المستند):
- Handles missing/unavailable fonts using FontSubstitutes, DefaultFont, and system substitution
- Processing order: FontName → FontConfig → FontSubstitutes → FontInfo → DefaultFont

المرحلة 2 - استبدال الخطوط (بعد تحميل المستند):
- Modifies any existing fonts in the loaded document using FontReplacements
- Applied after all font substitution is complete

نوع WordProcessingLoadOptions يكشف عن الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/__init__/) | ينشئ مثلاً جديداً من [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/). |

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
| [auto_detect_rtl_direction](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/auto_detect_rtl_direction/) | تحدد الخاصية auto_detect_rtl_direction ما إذا كانت الفقرات والقطع التي تحتوي على نص من اليمين إلى اليسار بشكل أساسي يتم إصلاح أعلام bidi الخاصة بها قبل التحويل. |
| [bookmark_options](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/bookmark_options/) | خيارات العلامات المرجعية. |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/clear_built_in_document_properties/) | العلم الذي يحدد ما إذا كانت خصائص المستند المدمجة تُمسح عند تحميل مستند معالجة كلمة. |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/clear_custom_document_properties/) | خاصية ClearCustomDocumentProperties. |
| [comment_display_mode](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/comment_display_mode/) | وضع عرض التعليقات يحدد كيف يجب عرض التعليقات في المستند الناتج. القيمة الافتراضية هي `ShowInBalloons`. |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/convert_owned/) | الخاصية تنفّذ [`IDocumentsContainerLoadOptions.convert_owned`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owned/). القيمة الافتراضية هي False. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/convert_owner/) | العلم convert_owner يحدد ما إذا كان يجب تحويل مالك المستند. القيمة الافتراضية هي True. |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/default_font/) | الخط الافتراضي لمستند WordProcessing. |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/depth/) | عمق خيارات تحميل حاوية المستند. القيمة الافتراضية هي 1. |
| [embed_true_type_fonts](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/embed_true_type_fonts/) | خاصية embed_true_type_fonts تحدد ما إذا كانت خطوط TrueType مدمجة في المستند الناتج. القيمة الافتراضية هي True. |
| [font_config_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_config_substitution_enabled/) | الخاصية تمكّن الاستبدال التلقائي للخطوط المفقودة بناءً على FontConfig النظام. القيمة الافتراضية هي False. |
| [font_info_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_info_substitution_enabled/) | العلم الذي يتيح الاستبدال التلقائي للخطوط المفقودة بناءً على FontInfo في المستند. القيمة الافتراضية: False. |
| [font_name_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_name_substitution_enabled/) | الخاصية تشير إلى ما إذا كانت الخطوط المفقودة تُستبدل تلقائيًا بناءً على اسم الخط. القيمة الافتراضية: False. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_substitutes/) | بدائل الخطوط المستخدمة عند تحويل مستند WordProcessing. |
| [font_transformations](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_transformations/) | تحويلات الخطوط التي تُطبق بعد اكتمال تحميل المستند واستبدال الخطوط، مما يسمح بتعديل أي خطوط في المستند، بما في ذلك تلك التي تم تحميلها بنجاح. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/format/) | نوع ملف المستند المدخل. |
| [hide_word_tracked_changes](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/hide_word_tracked_changes/) | خاصية hide_word_tracked_changes تخفي العلامات وتتبع التغييرات لمستندات Word. |
| [hyphenation_options](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/hyphenation_options/) | خيارات التجزئة لكلمات المستندات WordProcessing. |
| [keep_date_field_original_value](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/keep_date_field_original_value/) | خاصية keep_date_field_original_value تحدد ما إذا كانت القيمة الأصلية لحقل التاريخ تُحفظ. القيمة الافتراضية هي False. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/margin_settings/) | إعدادات الهوامش. |
| [page_numbering](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/page_numbering/) | العلم الخاص بإنشاء ترقيم الصفحات للمستند المحوَّل (القيمة الافتراضية: False). |
| [password](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/password/) | كلمة المرور لإلغاء حماية مستند محمي. |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/preserve_document_structure/) | العلم الذي يشير إلى ما إذا كان يجب الحفاظ على بنية المستند عند التحويل إلى PDF (الإعداد الافتراضي هو False). |
| [preserve_form_fields](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/preserve_form_fields/) | الخاصية التي تشير إلى ما إذا كانت حقول نماذج Microsoft Word تُحافظ عليها كحقول نماذج في ملف PDF الناتج أو تُحول إلى نص. الإعداد الافتراضي هو False. |
| [show_full_commenter_name](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/show_full_commenter_name/) | يتم عرض الاسم الكامل للمعلق في التعليقات عندما يتم تعيينه إلى True. الإعداد الافتراضي هو False. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/size_settings/) | إعدادات الحجم لمستند WordProcessing ([`IPageSizeOptions`](/conversion/python-net/groupdocs.conversion.options/ipagesizeoptions/)). |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/skip_external_resources/) | العلم الذي يحدد ما إذا كانت الموارد الخارجية تُتخطى عند تحميل المستند. |
| [update_fields](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/update_fields/) | الخيار لتحديث الحقول بعد التحميل. الإعداد الافتراضي: False. |
| [update_page_layout](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/update_page_layout/) | يتم تحديث تخطيط الصفحة بعد التحميل. الإعداد الافتراضي: False. |
| [use_text_shaper](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/use_text_shaper/) | الخاصية التي تشير إلى ما إذا كان يجب استخدام مُشكل نص لتحسين عرض التباعد بين الحروف. الإعداد الافتراضي هو False. |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/whitelisted_resources/) | الموارد المدرجة في القائمة البيضاء لتحميل المحتوى الخارجي، التي تُطبق [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/). |

### مثال

```python
from groupdocs.conversion.options.load import WordProcessingLoadOptions

load_options = WordProcessingLoadOptions()
load_options.password = "secret"
```

### Guides
دلائل المهام التي تستخدم `WordProcessingLoadOptions`:

* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)

### انظر أيضًا
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
