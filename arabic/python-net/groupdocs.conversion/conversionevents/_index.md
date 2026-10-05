---
title: "فئة ConversionEvents"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يجمع معالجات أحداث دورة حياة التحويل."
type: docs
url: /ar/python-net/groupdocs.conversion/conversionevents/
is_root: false
weight: 20
---


## ConversionEvents class

يجمع معالجات أحداث دورة حياة التحويل.

مرّر مثلاً إلى معامل `events` في مُنشئ [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) أو إلى طريقة `WithEvents` المتسلسلة.

فضّل هذا على خصائص المعالج الفردية لـ [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/) التي أصبحت مهجورة.

يعرض نوع ConversionEvents الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/conversionevents/__init__/) |  |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion/conversionevents/on_compression_completed/) | الحدث الذي يُطلق عندما يكتمل ضغط مخرجات التحويل. يُستدعى فقط في الإصدارات التي تتضمن خط أنابيب الضغط (LIB_ZIP). |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) | الحدث الذي يُطلق مرة واحدة عند انتهاء تشغيل التحويل، بغض النظر عن النجاح أو الفشل. |
| [on_conversion_progress](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/) | تقدم التحويل كنسبة مئوية (0–100)، يُطلق بشكل دوري. |
| [on_conversion_started](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/) | الحدث الذي يُطلق مرة واحدة في بداية تشغيل التحويل، قبل معالجة أي مستند. |
| [on_document_converted](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_converted/) | يُطلق الحدث مرة واحدة لكل **whole-document conversion** التي تكتمل بنجاح. |
| [on_document_failed](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_failed/) | يُطلق الحدث مرة واحدة لكل **whole-document conversion** التي تفشل. |
| [on_font_substituted](/conversion/python-net/groupdocs.conversion/conversionevents/on_font_substituted/) | يُطلق الحدث عندما لا يكون الخط المشار إليه في المستند المصدر متاحًا ويتم استبداله (إما بواسطة قاعدة [`FontSubstitute`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitute/) التي يوفرها العميل، أو بواسطة الخط الافتراضي المُكوَّن، أو بواسطة آلية fallback الداخلية لأنابيب التحويل). |
| [on_page_converted](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_converted/) | يُطلق الحدث مرة واحدة لكل صفحة عندما يكتمل التحويل لكل صفحة بنجاح. |
| [on_page_failed](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_failed/) | يُطلق الحدث مرة واحدة لكل صفحة عندما يفشل التحويل لكل صفحة. |

### انظر أيضًا
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
