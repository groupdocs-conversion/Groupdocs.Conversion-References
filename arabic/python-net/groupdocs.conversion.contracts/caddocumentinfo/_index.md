---
title: "فئة CadDocumentInfo"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يحتوي على بيانات تعريف مستند Cad."
type: docs
url: /ar/python-net/groupdocs.conversion.contracts/caddocumentinfo/
is_root: false
weight: 50
---


## CadDocumentInfo class

يحتوي على بيانات تعريف مستند Cad.

[`DocumentInfo.pages_count`](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/pages_count/) counts the sheets the drawing offers under the load options it was read with.

بدون تحديد صريح لـ [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) تكون تلك الأوراق مساحة نموذجية، وهي دائمًا قابلة للطباعة وبالتالي دائمًا ورقة، بالإضافة إلى كل تخطيط مساحة ورقية يكون إعداد الصفحة المخزن له عرض وارتفاع إيجابيين، ويتم تضييقه بواسطة [`CadLoadOptions.layout_scope`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/). أسماء التخطيطات الصريحة تفوز مباشرةً بدلاً من ذلك: تصبح الأوراق حينها الأسماء المقدمة التي يحملها الرسم، مطابقة ترتيبياً، دون أن يقوم النطاق أو إعداد الصفحة بفلترتها.

بالنسبة إلى ملف DWF يتم الإبلاغ عن مجموعة الصفحات المنشورة. العد الواحد أقل من واحد يكون صفرًا، يُبلغ عنه عندما لا يتطابق النطاق المطلوب مع أي ورقة من رسم يقدم واحدة: لا تزال البيانات الوصفية تصف الرسم، ويشير الصفر إلى أن النطاق لا يختار شيئًا بدلاً من فشل المستدعي الذي سأل عما يحتويه الرسم. فعملية التحويل تحت نفس خيارات التحميل تفشل.

لذلك فإن العدد ليس حجم [`CadDocumentInfo.layouts`](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layouts/)، الذي يسرد كل تكوين رسم يحمّله الرسم بما في ذلك تلك التي لا يمكن نشر ورقة منها، ولا يتنبأ بعدد الصفحات التي ينتجها تحويل معين.

نوع CadDocumentInfo يعرض الأعضاء التالية:

### الطرق
| طريقة | الوصف |
| :- | :- |
| [get](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get/) |  |
| [get_file](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get_file/) |  |
| [get_string](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get_string/) |  |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [creation_date](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/creation_date/) | تاريخ إنشاء المستند. |
| [format](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/format/) | صيغة المستند. |
| [height](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/height/) | ارتفاع مستند CAD. |
| [layers](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layers/) | الطبقات في المستند. |
| [layouts](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layouts/) | التخطيطات في المستند. |
| [pages_count](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/pages_count/) | عدد صفحات المستند. |
| [property_names](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/property_names/) | القائمة القابلة للتعداد لجميع الخصائص التي يمكن استرجاعها لمعلومات المستند الحالية. |
| [size](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/size/) | حجم المستند بالبايت. |
| [width](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/width/) | عرض مستند CAD. |

### انظر أيضًا
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
