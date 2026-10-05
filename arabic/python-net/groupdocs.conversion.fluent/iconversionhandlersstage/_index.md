---
title: "الفئة IConversionHandlersStage"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يمثل مرحلة مسطحة لمعالجات التحويل."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/
is_root: false
weight: 270
---


## IConversionHandlersStage class

يمثل مرحلة مسطحة لمعالجات التحويل.

يسمح بتعيين `OnConversionCompleted` أو `OnConversionFailed` بأي ترتيب وعدد مرات قبل المتابعة إلى `Convert` / `Compress`. يجب تسجيل الأحداث في المرحلة المبكرة عبر [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) بدلاً من هذه المرحلة.

يعرض النوع IConversionHandlersStage الأعضاء التالية:

### الطرق
| طريقة | الوصف |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress/#options) | يضغط نتائج التحويل. |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/convert/) | نفّذ سلسلة التحويل. |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed/#on_completed) | يسجّل رد نداء يتم استدعاؤه عند إكمال تحويل المستند بنجاح، مستبدلاً أي معالج تم تعيينه مسبقًا عند إعادة الاستدعاء. |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed/#on_failed) | يسجل ردًا استدعائيًا يتم استدعاؤه عندما يفشل تحويل المستند. |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed_action/) |  |

### انظر أيضًا
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
