---
title: "الفئة EmailFileType"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يعرف صيغ ملفات البريد الإلكتروني المستخدمة من قبل تطبيقات البريد لتخزين الرسائل، المرفقات، المجلدات، دفاتر العناوين، وغيرها من البيانات."
type: docs
url: /ar/python-net/groupdocs.conversion.filetypes/emailfiletype/
is_root: false
weight: 70
---


## EmailFileType class

يعرف صيغ ملفات البريد الإلكتروني المستخدمة من قبل تطبيقات البريد لتخزين الرسائل، المرفقات، المجلدات، دفاتر العناوين، وغيرها من البيانات.

يتضمن أنواع الملفات التالية:
- [`EmailFileType.eml`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/eml/)
- [`EmailFileType.emlx`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/emlx/)
- [`EmailFileType.msg`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/msg/)
- [`EmailFileType.vcf`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/vcf/)
- [`EmailFileType.mbox`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/mbox/)
- [`EmailFileType.pst`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/pst/)
- [`EmailFileType.ost`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/ost/)
- [`EmailFileType.olm`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/olm/)

تعرف على المزيد حول صيغ البريد الإلكتروني على https://wiki.fileformat.com/email.

نوع EmailFileType يكشف عن الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/__init__/) | يُهيئ كائن EmailFileType جديد للتسلسل. |

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
| [MSG](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/msg/) | MSG هو تنسيق ملف يستخدمه Microsoft Outlook و Exchange لتخزين رسائل البريد الإلكتروني، جهات الاتصال، المواعيد، أو مهام أخرى. تعرف على المزيد حول هذا التنسيق هنا. |
| [EML](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/eml/) | تنسيق ملف EML يمثل رسائل البريد الإلكتروني المحفوظة باستخدام Outlook وتطبيقات أخرى ذات صلة. تدعم تقريبًا جميع عملاء البريد هذا التنسيق لامتثاله لمعيار RFC-822 لتنسيق الرسائل على الإنترنت. تعرف على المزيد حول هذا التنسيق هنا. |
| [EMLX](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/emlx/) | تم تنفيذ وتطوير تنسيق ملف EMLX بواسطة Apple. يستخدم تطبيق Apple Mail تنسيق ملف EMLX لتصدير الرسائل الإلكترونية. تعرف على المزيد حول هذا التنسيق هنا. |
| [VCF](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/vcf/) | VCF (Virtual Card Format) أو vCard هو تنسيق ملف رقمي لتخزين معلومات الاتصال. يُستخدم هذا التنسيق على نطاق واسع لتبادل البيانات بين تطبيقات تبادل المعلومات الشهيرة. تعرف على المزيد حول هذا التنسيق هنا. |
| [MBOX](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/mbox/) | تنسيق ملف MBox هو مصطلح عام يمثل حاوية لمجموعة من رسائل البريد الإلكتروني. تُخزن الرسائل داخل الحاوية مع مرفقاتها. تعرف على المزيد حول هذا التنسيق هنا. |
| [PST](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/pst/) | الملفات ذات الامتداد .PST تمثل ملفات تخزين شخصية Outlook (وتسمى أيضًا Personal Storage Table) التي تخزن مجموعة متنوعة من معلومات المستخدم. تعرف على المزيد حول هذا التنسيق هنا. |
| [OST](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/ost/) | OST أو ملفات التخزين غير المتصلة تمثل بيانات صندوق بريد المستخدم في وضع غير متصل على الجهاز المحلي عند التسجيل في Exchange Server باستخدام Microsoft Outlook. تعرف على المزيد حول هذا التنسيق هنا. |
| [OLM](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/olm/) | الملف ذو الامتداد .olm هو ملف Microsoft Outlook لنظام تشغيل Mac. يخزن ملف OLM رسائل البريد الإلكتروني، اليوميات، بيانات التقويم، وأنواع أخرى من بيانات التطبيق. هذه مشابهة لملفات PST المستخدمة من قبل Outlook على نظام تشغيل Windows. ومع ذلك، لا يمكن فتح ملفات OLM التي أنشأها Outlook لنظام Mac في Outlook لنظام Windows. تعرف على المزيد حول هذا التنسيق هنا. |
| [ICS](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/ics/) | تنسيق ملف ICS (iCalendar) يُستخدم لتمثيل وتبادل معلومات التقويم والجدولة مثل الأحداث، والمهام، وبيانات الحالة المتاحة/المشغولة. تعرف على المزيد حول هذا التنسيق هنا. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | نوع ملف غير معروف (موروث من [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### انظر أيضًا
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
