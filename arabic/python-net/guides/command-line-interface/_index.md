---
title: "واجهة سطر الأوامر"
linkTitle: "Command Line Interface"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "حوّل المستندات مباشرةً من الطرفية باستخدام أداة سطر الأوامر groupdocs-conversion — لا حاجة لسكربت بايثون. افحص المستندات، قوّم الصيغ المدعومة، وطبّق الترخيص، كل ذلك من خلال الصدفة."
type: docs
url: /ar/python-net/guides/command-line-interface/
is_root: false
weight: 120
---


تثبيت حزمة `groupdocs-conversion-net` يضيف أيضًا سكريبت وحدة التحكم `groupdocs-conversion` إلى مسار `PATH` الخاص بك. إنها غلاف خفيف فوق واجهة برمجة تطبيقات بايثون، صُممت للحالات التي يكون فيها تشغيل سكربت بايثون مبالغًا فيه — أنابيب الصدفة، قواعد Make، خطوات CI، والتحويلات الفردية.

## Prerequisites

تأتي واجهة سطر الأوامر داخل الحزمة، لذا لا حاجة لتثبيت إضافي. تأكد من تثبيت `groupdocs-conversion-net` (انظر دليل البدء السريع [Quick Start Guide]()), ثم تحقق من توفر سكريبت وحدة التحكم:

```bash
groupdocs-conversion --version
```

يجب أن ترى نسخة الحزمة مطبوعة، على سبيل المثال `groupdocs-conversion 26.9.0`.

إذا لم يتم العثور على أمر `groupdocs-conversion`، قد لا يكون دليل سكريبت الحزمة موجودًا في `PATH` الخاص بك. يمكنك دائمًا استدعاء واجهة سطر الأوامر عبر نموذج وحدة بايثون بدلاً من ذلك: `python -m groupdocs.conversion`. الاثنين متكافئان.

## Commands

تُظهر واجهة سطر الأوامر أربع أوامر فرعية. نفّذ `groupdocs-conversion --help` للحصول على قائمة كاملة بالعلامات، أو `groupdocs-conversion <command> --help` للحصول على مساعدة لأمر فرعي محدد.

### convert

حوّل مستندًا إلى صيغة أخرى. يتم استنتاج الصيغة المستهدفة من امتداد ملف الإخراج؛ مرّر `--format` لتجاوزها.

```bash
# الامتداد يحدد الصيغة المستهدفة
groupdocs-conversion convert business-plan.docx business-plan.pdf

# تجاوز الصيغة عندما لا يحتوي اسم الإخراج على امتداد صالح للاستخدام
groupdocs-conversion convert business-plan.docx output.bin --format pdf

# حوّل صفحة واحدة (مؤشرها 1) — مفيد للأهداف النقطية
groupdocs-conversion convert annual-review.pdf page1.png --page 1 --count 1

# افتح مصدرًا محميًا بكلمة مرور
groupdocs-conversion convert protected.docx protected.pdf --password "secret"
```

| خيار | الوصف |
| :- | :- |
| `--format` | رمز الصيغة المستهدفة (يتجاوز امتداد الإخراج). |
| `--password` | كلمة المرور للمستند المصدر المحمي. |
| `--page` | الصفحة الأولى للتحويل، مفهرسة من 1. |
| `--count` | عدد الصفحات للتحويل. |

عند النجاح، يطبع الأمر مسار الإخراج ويخرج برمز `0`.

### info

اطبع المعلومات الأساسية عن المستند — الصيغة، الحجم، عدد الصفحات، وتاريخ الإنشاء إذا كان متوفرًا.

```bash
groupdocs-conversion info annual-review.pdf
```

```text
format:         pdf
size:           291788
pages_count:    10
```

استخدم `--password` للمصادر المحمية.

### list-formats

قائمة بكل صيغة هدف يمكن للمحرك إنتاجها لمستند إدخال معين، مقسمة إلى أهداف أساسية وثانوية.

```bash
groupdocs-conversion list-formats business-plan.docx
```

استخدم `--password` للمصادر المحمية.

### list-all-formats

اطبع مصفوفة التحويل الكاملة من المصدر إلى الهدف المعروفة للمحرك — كل صيغة إدخال والأهداف التي يمكن تحويلها إليها.

```bash
groupdocs-conversion list-all-formats
```

هذا الأمر لا يتطلب ملف إدخال.

## Global options

تنطبق هذه الخيارات على كل أمر:

| خيار | الوصف |
| :- | :- |
| `--license PATH` | طبق ملف الترخيص قبل تشغيل الأمر. |
| `--version` | اطبع نسخة سطر الأوامر (CLI) واخرج. |
| `--help` | اعرض مساعدة الاستخدام واخرج. |

طبق الترخيص مسبقًا بوضع `--license` قبل الأمر الفرعي:

```bash
groupdocs-conversion --license GroupDocs.Conversion.lic convert business-plan.docx business-plan.pdf
```

يُحترم سطر الأوامر (CLI) أيضًا متغير البيئة `GROUPDOCS_LIC_PATH` — إذا تم تعيينه، يُطبق الترخيص تلقائيًا ويمكنك حذف `--license`. راجع موضوع [Licensing]() للتفاصيل.

## Format tokens

`convert` يطابق امتداد الإخراج — أو قيمة `--format`، بالحروف الصغيرة — مع خيارات التحويل المطابقة ونوع الملف. الرموز المدعومة هي:

| الفئة | الرموز |
| :- | :- |
| PDF | `pdf` |
| معالجة النصوص | `doc`, `docx`, `rtf`, `odt`, `txt`, `md` |
| جدول بيانات | `xls`, `xlsx`, `xlsm`, `ods`, `csv`, `tsv` |
| عرض تقديمي | `ppt`, `pptx`, `pptm`, `odp` |
| ويب | `html`, `htm`, `mhtml` |
| صورة | `jpg`, `jpeg`, `png`, `bmp`, `gif`, `tiff`, `tif`, `webp`, `svg` |
| كتاب إلكتروني | `epub`, `mobi`, `azw3` |

رمز غير معروف يتسبب في خروج الأمر مع الرمز `2` وطباعة قائمة الرموز المقبولة.

## Exit codes

| كود | معنى |
| :- | :- |
| `0` | نجاح. |
| `2` | خطأ المستخدم — رمز تنسيق غير معروف أو ملف إدخال مفقود. |
| `1` | خطأ وقت التشغيل — يتم طباعة رسالة الاستثناء الأساسية في .NET إلى الخطأ القياسي. |

تجعل هذه الرموز سطر الأوامر (CLI) سهلًا للتفرع في سكريبتات الشل وأنابيب CI.

## When to use the Python API instead

يغطي سطر الأوامر (CLI) حالات التحويل الشائعة للوثائق الفردية. لأي شيء يتجاوز ذلك — ردود النداء لكل صفحة، التدفقات في الذاكرة، العلامة المائية، الخط، أو خيارات نطاق الخلايا، وتسلسلات الحاويات المتعددة الوثائق — استخدم واجهة برمجة تطبيقات بايثون مباشرة. إنها توفر سطحًا أكثر غنىً من علامات CLI. راجع [دليل المطور]() للحصول على مجموعة الميزات الكاملة.

## Next Steps

- [Quick Start Guide](): Convert your first document with the Python API.
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Apply a license to remove evaluation limits.
- [Technical Support](): Contact support if you encounter issues.
