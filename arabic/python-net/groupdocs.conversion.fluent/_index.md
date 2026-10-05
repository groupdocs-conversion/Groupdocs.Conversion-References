---
title: "groupdocs.conversion.fluent"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "أنواع تحت groupdocs.conversion.fluent."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/
is_root: false
weight: 50
---


أنواع تحت `groupdocs.conversion.fluent`.

### الفئات
| الفئة | الوصف |
| :- | :- |
| [`IConversionByPageCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/) | يتعامل مع إكمال صفحة التحويل. |
| [`IConversionByPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/) | يتعامل مع إكمال التحويل أو ينفّذ التحويل. |
| [`IConversionByPageHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/) | يوفر واجهة سلسة بعد تعيين `OnConversionFailed` لتحويل الصفحات. يسمح بتعيين `OnConversionCompleted` أو المتابعة إلى `Convert`/`Compress`. |
| [`IConversionByPageHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/) | يمثل الواجهة السلسة بعد تعيين `OnConversionCompleted` لتحويل الصفحات، مما يسمح بتكوين `OnConversionFailed` أو المتابعة إلى `Convert`/`Compress`. |
| [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/) | يوفر واجهة سلسة لتعيين معالجات التحويل حسب الصفحة فقط. |
| [`IConversionByPageHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/) | يوفر واجهة سلسة لتعيين معالجات تحويل الصفحات. |
| [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/) | يمثل مرحلة مسطحة لمعالجات التحويل حسب الصفحة. |
| [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/) | الواجهة السلسة لتعيين خيارات التحويل حسب الصفحة أو إعداد المعالج. |
| [`IConversionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompleted/) | يتعامل مع إكمال التحويل. |
| [`IConversionCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/) | تعامل مع إكمال التحويل أو نفّذ التحويل. |
| [`IConversionCompressResult`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresult/) | يضغط جميع نتائج التحويل في أرشيف واحد. |
| [`IConversionCompressResultCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/) | يتعامل مع إكمال الضغط. |
| [`IConversionCompressResultCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/) | الاستمرار بعد `Compress(...)`. المتابعة مباشرةً مع `Convert`؛ الـ [`IConversionCompressResultCompleted.OnCompressionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/on_compression_completed/) الموروث أصبح غير صالح — سجّل المعالج في مرحلة الدخول عبر [`IConversionSettings.WithEvents`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) بدلاً من ذلك. |
| [`IConversionConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvert/) | نفّذ التحويل. |
| [`IConversionConvertByPageOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertbypageoptions/) | يمثل خيارات تحويل التحويل. |
| [`IConversionConvertOptionOrCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/) | يمثل خيارات التحويل، معالجة الإكمال، أو التنفيذ لتحويل. |
| [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/) | يمثل خيارات التحويل، معالجة الإكمال، أو التنفيذ. |
| [`IConversionConvertOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptions/) | يمثل خيارات تحويل التحويل. |
| [`IConversionConvertOrCompress`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertorcompress/) | ضغط أو تحويل. |
| [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/) | يُعدّ المصدر للتحويل. |
| [`IConversionGetDocumentInfo`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetdocumentinfo/) | يسترجع معلومات المستند المصدر، بما في ذلك عدد الصفحات وغيرها من الخصائص الخاصة بنوع الملف. |
| [`IConversionGetPossibleConversions`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetpossibleconversions/) | يحصل على التحويلات الممكنة للمستند المصدر. |
| [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/) | يمثل الواجهة السلسة بعد تعيين `OnConversionFailed`، مما يسمح بتعيين `OnConversionCompleted` أو المتابعة إلى `Convert`/`Compress`. |
| [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/) | يوفر واجهة سلسة بعد تعيين `OnConversionCompleted`، مما يسمح بتكوين `OnConversionFailed` أو المتابعة إلى `Convert`/`Compress`. |
| [`IConversionHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/) | يوفر واجهة سلسة لتعيين معالجات التحويل فقط. |
| [`IConversionHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/) | يوفر واجهة سلسة لتعيين معالجات التحويل. يسمح بتعيين `OnConversionCompleted` و/أو `OnConversionFailed` بأي ترتيب، مرة واحدة كحد أقصى لكل منهما، أو تخطيهما. |
| [`IConversionHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/) | يمثل مرحلة مسطحة لمعالجات التحويل. |
| [`IConversionIsPasswordProtected`](/conversion/python-net/groupdocs.conversion.fluent/iconversionispasswordprotected/) | يتحقق مما إذا كان المستند المصدر محميًا بكلمة مرور. |
| [`IConversionLoadOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptions/) | يمثل خيارات تحميل التحويل. |
| [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/) | يمثل خيارات تحميل التحويل أو الإجراءات مع مستند محمَّل. |
| [`IConversionOptionsOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/) | يوفر واجهة سلسة لتعيين خيارات التحويل فقط. |
| [`IConversionOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/) | يمثل خيارات التحويل أو إعداد معالج التحويل. |
| [`IConversionSettings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/) | إعداد إعدادات التحويل أو الأحداث في مرحلة الدخول (قبل `Load`). |
| [`IConversionSettingsOrConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/) | يمثل إعدادات التحويل أو مصدر التحويل. |
| [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/) | يوفر الإجراءات الممكنة مع المستند المحمَّل. |
| [`IConversionTo`](/conversion/python-net/groupdocs.conversion.fluent/iconversionto/) | يحدد كيفية تخزين المستند المحوَّل. |
