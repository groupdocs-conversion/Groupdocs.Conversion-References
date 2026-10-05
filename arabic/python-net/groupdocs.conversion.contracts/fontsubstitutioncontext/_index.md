---
title: "FontSubstitutionContext فئة"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يصف استبدال خط واحد حدث أثناء تحميل أو عرض مستند المصدر."
type: docs
url: /ar/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/
is_root: false
weight: 190
---


## FontSubstitutionContext class

يصف استبدال خط واحد حدث أثناء تحميل أو عرض مستند المصدر.

يتم تمرير الكائنات إلى [`ConversionEvents.on_font_substituted`](/conversion/python-net/groupdocs.conversion/conversionevents/on_font_substituted/).

نوع FontSubstitutionContext يكشف عن الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/__init__/#source_file_name-original_font_name-substitute_font_name-reason) | يُنشئ FontSubstitutionContext جديد. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [original_font_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/original_font_name/) | اسم الخط المشار إليه في المستند المصدر ولكنه غير متوفر في خط أنابيب التحويل. |
| [reason](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/) | رسالة الاستبدال كما تم الإبلاغ عنها من قبل خط أنابيب التحويل، حرفيًا وغير مُحلَّلة. |
| [source_file_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/source_file_name/) | اسم الملف للمستند المصدر الذي يتم تحويله. عندما يتم توفير المصدر كدفق ليس من نوع `io.RawIOBase`، يحتوي هذا على معرف مُولد بدلاً من اسم ملف حقيقي. |
| [substitute_font_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/substitute_font_name/) | اسم الخط المستخدم كبديل. قد يكون None للمستندات التي يُبلغ محركها عن الاستبدال كنص وصفي فقط — في هذه الحالة اقرأ [`FontSubstitutionContext.reason`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/). |

### انظر أيضًا
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
