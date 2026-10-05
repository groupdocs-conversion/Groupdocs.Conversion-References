---
title: "نظرة عامة على الميزات"
linkTitle: "Features overview"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "الميزات الرئيسية لـ GroupDocs.Conversion للبايثون عبر .NET — أكثر من 10,000 زوج تنسيق، اختيار الصفحات، خيارات التحميل/التحويل، العلامات المائية، فحص المستندات، وتكامل خط أنابيب الذكاء الاصطناعي."
type: docs
url: /ar/python-net/guides/features-overview/
is_root: false
weight: 30
---


## Overview

GroupDocs.Conversion للبايثون عبر .NET يحول المستندات بين **10,000+ format pairs** — Microsoft Office، PDF، OpenDocument، الصور، CAD، البريد الإلكتروني، الأرشيفات، الكتب الإلكترونية، HTML، TeX، ولغات وصف الصفحات. يعمل بالكامل داخل المؤسسة، ولا يتطلب تثبيت Microsoft Office أو Adobe Acrobat، ويُوزَّع كحزمة wheel مُعدة مسبقًا على Windows وLinux وmacOS.

اطلع على القائمة الكاملة لـ [الصيغ المدعومة]() أو تصفح [دليل المطور]() للحصول على أمثلة قابلة للتنفيذ لكل واجهة برمجة تطبيقات.

## File Conversion

القدرة الأساسية هي تحويل أي مستند مصدر مدعوم إلى أي تنسيق هدف مدعوم. جميع التحويلات ممكنة دون تثبيت Microsoft Office أو LibreOffice أو Adobe Acrobat. تقدم GroupDocs.Conversion مجموعة مرنة من الخيارات لتخصيص خط الأنابيب.

### Convert specific document pages

حوّل المستندات بالكامل، أو صفحات فردية، أو نطاقات من الصفحات. استخدم إما قائمة `pages` صريحة أو نطاق `page_number` + `pages_count` على الفئة [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/). راجع [Convert a Document to Another Format]() للحصول على أمثلة قابلة للتنفيذ.

### Per-page file output

أنشئ ملف إخراج واحد لكل صفحة — مفيد للعروض التقديمية، ملفات PDF متعددة الصفحات، وتحويل المستندات إلى صور. كرّر خاصية `page_number` مع الحفاظ على `pages_count = 1`. راجع [Convert a Document to Multiple Page Files]().

### Auto-detect source document format

عندما يصل ملف المصدر كتيار بايت دون اسم ملف، يقوم GroupDocs.Conversion باكتشاف التنسيق تلقائيًا عن طريق فحص رأس التيار. راجع [Load File From Stream](#example-2-load-file-from-stream-and-detect-file-type-automatically).

### Load source document with extended options

كل فئة خيارات التحميل تكشف عن إعدادات خاصة بالتنسيق:

- **Passwords** — open [password-protected documents]() by setting `WordProcessingLoadOptions.password`, `PdfLoadOptions.password`, `SpreadsheetLoadOptions.password`, etc.
- **PDF load options** — hide annotations, flatten form fields, remove embedded files via [`PdfLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/).
- **Spreadsheet load options** — pick specific sheet indexes, show grid lines, convert a cell range (`convert_range`), skip empty rows and columns via [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/).
- **Word Processing load options** — hide comments, hide tracked changes, substitute fonts via [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/).
- **Email load options** — alter header visibility, change field labels via [`EmailLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/).
- **Text load options** — set encoding, control leading/trailing spaces via [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/) / [`CsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/).

### Discover possible conversions

استعلم عن تنسيقات الهدف المدعومة من المحرك قبل تشغيل خط الأنابيب — على مستوى المكتبة بالكامل، حسب الامتداد، أو لمستند محمَّل محدد. راجع [Get Possible Conversions]() للحصول على الثلاثة إصدارات.

### Watermark the converted document

أضف علامة مائية نصية أثناء التحويل — سيطر على اللون، الحجم، الدوران، الشفافية، ووضعية الخلفية / المقدمة. راجع [Add a Watermark to Converted Document]().

### Convert files inside a container

افتح حاويات ZIP أو RAR أو 7Z أو OST أو PST، حوّل المحتويات، واكتب مستند إخراج موحد في استدعاء واحد. راجع [Convert Files Within Document Containers]().

## Document Information Extraction

يمكن لـ GroupDocs.Conversion قراءة البيانات الوصفية من مستند المصدر دون تحويله فعليًا — التنسيق، عدد الصفحات أو الشرائح، المؤلف، تاريخ الإنشاء، الأبعاد، جدول المحتويات، وتفاصيل خاصة بالتنسيق. راجع [Getting Document Information]() لجميع الأنواع التسعة:

- **PDF** — author, title, TOC, version, page dimensions, encryption flag.
- **Word Processing** — author, title, TOC, word count, line count.
- **Spreadsheet** — author, title, worksheet count.
- **Presentation** — author, title, slide count.
- **Image** — width, height, bits per pixel.
- **CAD** — layouts and layers list, drawing dimensions.
- **Project Management** — task count, start / end dates.
- **Email** — encryption flag, attachment list, HTML-body flag.

## Load Documents From Different Sources

يقبل مُنشئ Python [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) كلًا من مسار الملف وكائن ملف ثنائي شبيه بالملف، لذا يمكنك تحميل المستندات من:

- Local disk — see [Load File From Local Disk]().
- Any stream — `open("file.docx", "rb")`, `io.BytesIO(data)`, or a file handle returned from `boto3`, `azure-storage-blob`, `requests`, etc. See [Load File From Stream]().

يعمل التخزين السحابي (Amazon S3، Azure Blob Storage، Google Cloud Storage) عن طريق جلب البايتات إلى مخزن `BytesIO` وتمريره إلى مُنشئ [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

## Logging and Diagnostics

قم بربط [`ConsoleLogger`](/conversion/python-net/groupdocs.conversion.logging/consolelogger/) عبر [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/) لتتبع خط أنابيب التحويل — اختيار المحمل، بدء التحويل وإكماله، وأي تحذيرات يصدرها المحرك. راجع [Logging and Diagnostics]().

## AI and LLM Integration

تم تصميم GroupDocs.Conversion ليكون وحدة بناء أساسية من الدرجة الأولى لسلاسل معالجة مستندات الذكاء الاصطناعي. حزمة `groupdocs-conversion-net` على pip تُرفق ملف `AGENTS.md` داخل العجلة حتى يتمكن مساعدو الترميز المدعومين بالذكاء الاصطناعي من اكتشاف واجهة برمجة التطبيقات تلقائيًا، وتُشغّل GroupDocs خادمًا عامًا [MCP server](https://docs.groupdocs.com/mcp) للبحث عن الوثائق عند الطلب. راجع [Agents and LLM Integration]() للقصة الكاملة — بما في ذلك كيفية ربط GroupDocs.Conversion مع GroupDocs.Markdown لإدخال RAG نظيف.

## On-Premise Deployment

لا توجد مكالمات سحابية، ولا حركة مرور شبكة صادرة، ولا تبعيات برمجية من طرف ثالث تتجاوز ما يوفره نظام التشغيل بالفعل. العجلة مكتفية ذاتيًا على Windows وتُرفق مكتبات تشغيل أصلية خاصة بها على Linux و macOS. راجع [System Requirements]() للقائمة المختصرة للحزم الأصلية الاختيارية (ICU، fontconfig، خطوط Microsoft الأساسية).
