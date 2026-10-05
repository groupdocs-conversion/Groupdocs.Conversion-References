---
title: "الفئة FinanceFileType"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يعرف أنواع مستندات المالية."
type: docs
url: /ar/python-net/groupdocs.conversion.filetypes/financefiletype/
is_root: false
weight: 90
---


## FinanceFileType class

يعرف أنواع مستندات المالية.

يتضمن الأنواع التالية: [`FinanceFileType.xbrl`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/xbrl/), [`FinanceFileType.i_xbrl`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/), [`FinanceFileType.ofx`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/ofx/). تعرف على المزيد حول صيغ المالية هنا: https://docs.fileformat.com/finance/.

يعرض نوع FinanceFileType الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/__init__/) | يقوم بتهيئة FinanceFileType للتسلسل. |

### الطرق
| طريقة | الوصف |
| :- | :- |
| [compare_to](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to/) | يقارن الكائن الحالي بآخر. (موروث من [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [compare_to_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to_object/) | (موروث من [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals/) | يطبق مقارنة المساواة المعرفة في [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals/). (موروث من [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_enumeration](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals_enumeration/) | (موروث من [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals_object/) | (موروث من [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_display_name](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_display_name/) | (موروث من [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_extension/) | يحصل على FileType للامتداد المقدم للملف. (موروث من [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_filename/) | يعيد FileType للملف المحدد file_name. (موروث من [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_stream/) | يعيد FileType لتدفق المستند المقدم. (موروث من [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_value](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_value/) | (موروث من [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [get_all](/conversion/python-net/groupdocs.conversion.filetypes/filetype/get_all/) | (موروث من [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/enumeration/get_hash_code/) | يوفر دالة التجزئة الافتراضية. (موروث من [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [to_string](/conversion/python-net/groupdocs.conversion.filetypes/filetype/to_string/) | تمثيل النص لنوع الملف. (موروث من [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/filetype/description/) | وصف نوع الملف. (موروث من [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/extension/) | امتداد الملف. (موروث من [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/filetype/family/) | عائلة الملف. (موروث من [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/filetype/file_format/) | تنسيق الملف. (موروث من [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### الحقول
| حقل | الوصف |
| :- | :- |
| [XBRL](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/xbrl/) | XBRL هو معيار دولي مفتوح للتقارير التجارية الرقمية يُستخدم على نطاق واسع عالميًا. إنها لغة تعتمد على XML وتستخدم عناصر XBRL، المعروفة بالوسوم، لوصف كل عنصر من بيانات الأعمال لتشكيل البيانات لتصنيف التقارير وتحليلها. تعرف على المزيد حول هذا التنسيق هنا. |
| [IXBRL](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/ixbrl/) | داخل iXBRL، يتم تغليف محتويات XBRL في تنسيق ملف xHTML الذي يستخدم وسوم XML. مثل XBRL، هو العنصر الجذر لملفات iXBRL. يمثل تنسيق XHTML محتوياته كمجموعة من أنواع المستندات المختلفة والوحدات. جميع الملفات في XHTML تعتمد على تنسيق ملف XML وتلتزم بمعايير مستندات XML. تعرف على المزيد حول هذا التنسيق هنا. |
| [OFX](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/ofx/) | Open Financial Exchange (OFX) هو تنسيق تدفق بيانات لتبادل المعلومات المالية تطور من Open Financial Connectivity (OFC) الخاص بمايكروسوفت وتنسيقات ملف Open Exchange الخاصة بـ Intuit. تعرف على المزيد حول هذا التنسيق هنا. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | نوع ملف غير معروف (موروث من [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### انظر أيضًا
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
