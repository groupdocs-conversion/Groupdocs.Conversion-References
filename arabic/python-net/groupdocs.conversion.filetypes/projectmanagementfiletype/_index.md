---
title: "فئة ProjectManagementFileType"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يحدد صيغ ملفات المشروع التي يتم إنشاؤها بواسطة برامج إدارة المشاريع مثل Microsoft Project، Primavera P6 وغيرها."
type: docs
url: /ar/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/
is_root: false
weight: 170
---


## ProjectManagementFileType class

يحدد صيغ ملفات المشروع التي يتم إنشاؤها بواسطة برامج إدارة المشاريع مثل Microsoft Project، Primavera P6 وغيرها.

ملف المشروع هو مجموعة من المهام والموارد وجدولتها للحصول على مخرجات قابلة للقياس على شكل منتج أو خدمة. مستندات إدارة المشاريع. يتضمن أنواع الملفات التالية: [`ProjectManagementFileType.mpp`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpp/), [`ProjectManagementFileType.mpt`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpt/), [`ProjectManagementFileType.mpx`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpx/). تعرف على المزيد حول صيغ إدارة المشاريع هنا: https://wiki.fileformat.com/project-management.

نوع ProjectManagementFileType يعرض الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/__init__/) | يقوم بتهيئة ProjectManagementFileType للتسلسل. |

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
| [MPT](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpt/) | ملفات قالب Microsoft Project، تحتوي على معلومات أساسية وبنية بالإضافة إلى إعدادات المستند لإنشاء ملفات .MPP. تعرف على المزيد حول هذا التنسيق هنا. |
| [MPP](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpp/) | MPP هو ملف بيانات Microsoft Project يخزن معلومات متعلقة بإدارة المشروع بطريقة متكاملة. تعرف على المزيد حول هذا التنسيق هنا. |
| [MPX](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpx/) | Microsoft Exchange File Format هو تنسيق ملف ASCII لنقل معلومات المشروع بين Microsoft Project (MSP) وتطبيقات أخرى تدعم تنسيق MPX مثل Primavera Project Planner وSciforma وTimerline Precision Estimating. تعرف على المزيد حول هذا التنسيق هنا. |
| [XER](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/xer/) | تنسيق ملف XER هو تنسيق ملف مشروع مملوك يستخدمه تطبيق Primavera P6 لتخطيط وإدارة المشاريع. تعرف على المزيد حول هذا التنسيق هنا. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | نوع ملف غير معروف (موروث من [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### انظر أيضًا
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
