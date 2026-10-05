---
title: "الفئة SpreadsheetLoadOptions"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يوفر خيارات لتحميل مستندات Spreadsheet."
type: docs
url: /ar/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/
is_root: false
weight: 440
---


## SpreadsheetLoadOptions class

يوفر خيارات لتحميل مستندات Spreadsheet.

يعرض نوع SpreadsheetLoadOptions الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/__init__/) | يُنشئ مثلاً جديداً من [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/). |

### الطرق
| طريقة | الوصف |
| :- | :- |
| [clone](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clone/) | ينسخ النسخة الحالية. |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | يحدد ما إذا كان مثيلان لكائنين متساويين. (موروث من [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (موروث من [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (موروث من [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | يعمل كدالة التجزئة الافتراضية. (موروث من [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [all_columns_in_one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/all_columns_in_one_page_per_sheet/) | تحدد الخاصية ما إذا كان يتم عرض كل محتوى الأعمدة في ورقة على صفحة واحدة في النتيجة. |
| [auto_fit_rows](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/auto_fit_rows/) | يتم ضبط حجم الصفوف تلقائيًا عند التحويل. |
| [check_excel_restriction](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/) | تحدد الخاصية ما إذا كانت قيود ملف Excel تُفحص عند تعديل الكائنات المتعلقة بالخلايا. |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clear_built_in_document_properties/) | تحدد الخاصية ClearBuiltInDocumentProperties ما إذا كانت خصائص المستند المدمجة تُمسح عند تحميل جدول بيانات. |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clear_custom_document_properties/) | خاصية ClearCustomDocumentProperties. |
| [columns_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/columns_per_page/) | عدد الأعمدة لكل صفحة المستخدمة لتقسيم ورقة العمل إلى صفحات؛ القيمة الافتراضية هي 0، والتي تعطل الترميز. |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_owned/) | تطبق الخاصية [`IDocumentsContainerLoadOptions.convert_owned`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owned/) وتكون القيمة الافتراضية False. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_owner/) | الخاصية التي تطبق [`IDocumentsContainerLoadOptions.convert_owner`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owner/). القيمة الافتراضية True. |
| [convert_range](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_range/) | النطاق المراد تحويله عند التحويل إلى تنسيق غير جدول بيانات، مثل "D1:F8". |
| [culture_info](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/culture_info/) | معلومات الثقافة النظامية المستخدمة عند تحميل الملف. |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/default_font/) | الخط الافتراضي لمستند جدول بيانات. |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/depth/) | عمق خيارات تحميل حاوية المستندات. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/font_substitutes/) | بدائل الخط المستخدمة عند تحويل مستند جدول بيانات. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/format/) | نوع ملف المستند المدخل. |
| [ignore_formula_calculation_errors](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/ignore_formula_calculation_errors/) | تشير الخاصية إلى ما إذا كان يجب تجاهل أخطاء حساب الصيغ. قد يكون الخطأ دالة غير مدعومة، روابط خارجية، إلخ. القيمة الافتراضية False. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/margin_settings/) | إعدادات الهوامش. |
| [one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/one_page_per_sheet/) | تشير الخاصية إلى ما إذا كان محتوى كل ورقة يُحول إلى صفحة واحدة في مستند PDF. القيمة الافتراضية True. |
| [optimize_pdf_size](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/optimize_pdf_size/) | يتم تحسين التحويل للحصول على حجم ملف أصغر بدلاً من جودة الطباعة عندما تكون القيمة True أثناء التحويل إلى PDF. |
| [password](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/password/) | كلمة المرور المستخدمة لإلغاء حماية مستند محمي. |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/preserve_document_structure/) | العلم الذي يشير إلى ما إذا كان يجب الحفاظ على بنية المستند عند التحويل إلى PDF (الإعداد الافتراضي هو False). |
| [print_comments](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/print_comments/) | طريقة طباعة التعليقات مع الورقة. القيمة الافتراضية PrintNoComments. |
| [reset_font_folders](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/reset_font_folders/) | يتم إعادة ضبط مجلدات الخطوط قبل تحميل المستند. |
| [rows_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/rows_per_page/) | عدد الصفوف لكل صفحة المستخدمة لتقسيم ورقة العمل إلى صفحات، مع القيمة الافتراضية 0 التي تعني عدم وجود ترقيم. |
| [sheet_indexes](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheet_indexes/) | قائمة فهارس الأوراق للتحويل. |
| [sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheets/) | اسم الورقة للتحويل. |
| [show_grid_lines](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_grid_lines/) | الخيار لإظهار خطوط الشبكة عند تحويل ملفات Excel. |
| [show_hidden_sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_hidden_sheets/) | الخيار لإظهار الأوراق المخفية عند تحويل ملفات Excel. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/size_settings/) | إعدادات الحجم، كما هو معرف في [`IPageSizeOptions`](/conversion/python-net/groupdocs.conversion.options/ipagesizeoptions/). |
| [skip_empty_rows_and_columns](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_empty_rows_and_columns/) | الإعداد الذي يتخطى الصفوف والأعمدة الفارغة عند التحويل. |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_external_resources/) | الخاصية تُطبق [`IResourceLoadingOptions.skip_external_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/skip_external_resources/). |
| [skip_footers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_footers/) | الخاصية تحدد ما إذا كان يتم تخطي التذييلات عند تحويل مستندات الجداول. الافتراضي: False. |
| [skip_headers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_headers/) | الخيار لتخطي رؤوس الأعمدة عند تحويل مستندات الجداول. الافتراضي: False. |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/whitelisted_resources/) | الموارد المسموح بها كما هو معرف في [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/). |

### انظر أيضًا
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
