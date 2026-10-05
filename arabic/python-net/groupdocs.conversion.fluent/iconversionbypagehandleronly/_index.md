---
title: "الفئة IConversionByPageHandlerOnly"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يوفر واجهة سلسة لتعيين معالجات التحويل حسب الصفحة فقط."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/
is_root: false
weight: 50
---


## IConversionByPageHandlerOnly class

يوفر واجهة سلسة لتعيين معالجات التحويل حسب الصفحة فقط.

يرث [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/) لـ `Convert`/`Compress`؛ تُحافظ على التحميلات المتدرجة `OnConversion*` عبر كلمة المفتاح `new` للحفاظ على التوافقية السابقة.

يعرض النوع IConversionByPageHandlerOnly الأعضاء التالية:

### الطرق
| طريقة | الوصف |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress/#options) | يضغط نتائج التحويل؛ سجّل معالج تدفق مضغوط في مرحلة الدخول عبر [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (تعيين `OnCompressionCompleted`) بدلاً من استخدام طريقة السلسلة السائلة القديمة. |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/convert/) | نفّذ سلسلة التحويل. |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed/#on_completed) | يسجل ردًا استدعائيًا يتم استدعاؤه عندما يكتمل تحويل الصفحة بنجاح. |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_failed/#on_failed) | يسجل ردًا استدعائيًا يتم استدعاؤه عندما يفشل تحويل الصفحة. |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_failed_action/) |  |

### انظر أيضًا
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
