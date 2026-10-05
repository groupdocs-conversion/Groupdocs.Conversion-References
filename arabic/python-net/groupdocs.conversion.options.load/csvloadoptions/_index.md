---
title: "فئة CsvLoadOptions"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يوفر خيارات لتحميل مستندات CSV."
type: docs
url: /ar/python-net/groupdocs.conversion.options.load/csvloadoptions/
is_root: false
weight: 80
---


## CsvLoadOptions class

يوفر خيارات لتحميل مستندات CSV.

نوع CsvLoadOptions يعرض الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/__init__/) | يُنشئ مثيلاً جديداً من [`CsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/). |

### الطرق
| طريقة | الوصف |
| :- | :- |
| [clone](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clone/) | ينسخ المثيل الحالي. (موروث من [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | يحدد ما إذا كان مثيلان لكائنين متساويين. (موروث من [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (موروث من [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (موروث من [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | يعمل كدالة التجزئة الافتراضية. (موروث من [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/clear_built_in_document_properties/) | الخاصية تزيل خصائص البيانات الوصفية المدمجة من المستند. |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/clear_custom_document_properties/) | الخاصية التي تزيل خصائص البيانات الوصفية المخصصة من المستند. |
| [convert_date_time_data](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/convert_date_time_data/) | تشير الخاصية إلى ما إذا كان النص في الملف يُحوَّل إلى تاريخ. القيمة الافتراضية هي True. |
| [convert_numeric_data](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/convert_numeric_data/) | العلم الذي يشير إلى ما إذا كانت النصوص في الملف تُحوَّل إلى قيم رقمية. القيمة الافتراضية هي True. |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/convert_owned/) | الخيار للتحكم فيما إذا كان يجب تحويل المستندات المملوكة في حاوية المستندات. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/convert_owner/) | الخيار للتحكم فيما إذا كان يجب تحويل حاوية المستندات نفسها؛ إذا كان true، ستكون الحاوية أول مستند يتم تحويله. |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/default_font/) | الخط الذي سيُستخدم إذا كان الخط مفقودًا. |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/depth/) | خيار العمق يتحكم في عدد المستويات التي يتم فيها إجراء التحويل. |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/encoding/) | الترميز المستخدم لملفات CSV. القيمة الافتراضية هي `Encoding.Default`. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/font_substitutes/) | بدائل الخط. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/format/) | نوع ملف المستند المدخل. |
| [has_formula](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/has_formula/) | تشير الخاصية إلى ما إذا كان النص صيغة إذا بدأ بـ "=". |
| [is_multi_encoded](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/is_multi_encoded/) | تشير الخاصية إلى ما إذا كان الملف يحتوي على عدة ترميزات. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/margin_settings/) | إعدادات هوامش الصفحة. |
| [separator](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/separator/) | الفاصل في ملف CSV. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/size_settings/) | إعدادات حجم الصفحة. |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/skip_external_resources/) | تشير الخاصية إلى ما إذا كانت الموارد الخارجية تُحمَّل. إذا كان True، لن يتم تحميل جميع الموارد الخارجية باستثناء تلك الموجودة في قائمة [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/). القيمة الافتراضية: True. |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/whitelisted_resources/) | الموارد الخارجية التي سيتم تحميلها دائمًا. |
| [all_columns_in_one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/all_columns_in_one_page_per_sheet/) | الخاصية تحدد ما إذا كان سيتم عرض جميع محتوى الأعمدة لورقة العمل على صفحة واحدة في النتيجة. (موروث من [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [auto_fit_rows](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/auto_fit_rows/) | يتم ضبط حجم الصفوف تلقائيًا عند التحويل. (موروث من [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [check_excel_restriction](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/) | الخاصية تحدد ما إذا كانت قيود ملف Excel تُفحص عند تعديل الكائنات المتعلقة بالخلايا. (موروث من [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [columns_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/columns_per_page/) | عدد الأعمدة لكل صفحة المستخدمة لتقسيم ورقة العمل إلى صفحات؛ الافتراضي هو 0، والذي يعطل الترميز. (موروث من [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [convert_range](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_range/) | النطاق الذي سيتم تحويله عند التحويل إلى تنسيق غير جدول بيانات، مثل "D1:F8". (موروث من [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [culture_info](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/culture_info/) | معلومات الثقافة النظامية المستخدمة عند تحميل الملف. (موروثة من [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [ignore_formula_calculation_errors](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/ignore_formula_calculation_errors/) | تشير الخاصية إلى ما إذا كان يجب تجاهل أخطاء حساب الصيغ. قد يكون الخطأ دالة غير مدعومة أو روابط خارجية، إلخ. القيمة الافتراضية هي False. (موروثة من [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/one_page_per_sheet/) | تشير الخاصية إلى ما إذا كان محتوى كل ورقة يُحوَّل إلى صفحة واحدة في مستند PDF. القيمة الافتراضية هي True. (موروثة من [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [optimize_pdf_size](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/optimize_pdf_size/) | يتم تحسين التحويل للحصول على حجم ملف أصغر بدلاً من جودة الطباعة عند ضبطه على True أثناء التحويل إلى PDF. (موروثة من [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [password](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/password/) | كلمة المرور المستخدمة لإلغاء حماية مستند محمي. (موروثة من [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/preserve_document_structure/) | العلم الذي يشير إلى ما إذا كان يجب الحفاظ على بنية المستند عند التحويل إلى PDF (القيمة الافتراضية هي False). (موروثة من [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [print_comments](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/print_comments/) | طريقة طباعة التعليقات مع الورقة. القيمة الافتراضية هي PrintNoComments. (موروثة من [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [reset_font_folders](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/reset_font_folders/) | يتم إعادة تعيين مجلدات الخطوط قبل تحميل المستند. (موروثة من [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [rows_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/rows_per_page/) | عدد الصفوف لكل صفحة المستخدمة لتقسيم ورقة العمل إلى صفحات، مع القيمة الافتراضية 0 التي تعني عدم وجود ترقيم صفحات. (موروثة من [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [sheet_indexes](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheet_indexes/) | قائمة مؤشرات الأوراق التي سيتم تحويلها. (موروثة من [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheets/) | اسم الورقة التي سيتم تحويلها. (موروثة من [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [show_grid_lines](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_grid_lines/) | الخيار لإظهار خطوط الشبكة عند تحويل ملفات Excel. (موروثة من [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [show_hidden_sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_hidden_sheets/) | الخيار لإظهار الأوراق المخفية عند تحويل ملفات Excel. (موروثة من [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [skip_empty_rows_and_columns](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_empty_rows_and_columns/) | الإعداد الذي يتخطى الصفوف والأعمدة الفارغة عند التحويل. (موروثة من [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [skip_footers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_footers/) | تحدد الخاصية ما إذا كان يتم تخطي التذييلات عند تحويل مستندات الجداول. القيمة الافتراضية: False. (موروثة من [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [skip_headers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_headers/) | الخيار لتخطي رؤوس الأعمدة عند تحويل مستندات الجداول. القيمة الافتراضية: False. (موروثة من [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |

### انظر أيضًا
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
