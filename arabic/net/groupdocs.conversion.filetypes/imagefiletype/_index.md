---
title: "ImageFileType"
second_title: "GroupDocs.Conversion لـ .NET مرجع API"
description: "يحدد مستندات الصور. يتضمن أنواع الملفات التالية Ai./imagefiletype/ai Avif./imagefiletype/avif Bmp./imagefiletype/bmp Cdr./imagefiletype/cdr Cmx./imagefiletype/cmx Dcm./imagefiletype/dcm Dib./imagefiletype/dib DjVu./imagefiletype/djvu Dng./imagefiletype/dng Emf./imagefiletype/emf Emz./imagefiletype/emz Gif./imagefiletype/gif Heic./imagefiletype/heicIco./imagefiletype/ico J2c./imagefiletype/j2c J2k./imagefiletype/j2k Jls./imagefiletype/jls Jp2./imagefiletype/jp2 Jpc./imagefiletype/jpc Jfif./imagefiletype/jfif. Jpeg./imagefiletype/jpeg Jpf./imagefiletype/jpf Jpg./imagefiletype/jpg Jpm./imagefiletype/jpm Jpx./imagefiletype/jpx Odg./imagefiletype/odg Png./imagefiletype/png Psd./imagefiletype/psd Tif./imagefiletype/tif Tiff./imagefiletype/tiff Webp./imagefiletype/webp Wmf./imagefiletype/wmf. Wmz./imagefiletype/wmz. تعرف على المزيد حول صيغ الصور هناhttps//wiki.fileformat.com/image."
type: docs
weight: 1170
url: /ar/net/groupdocs.conversion.filetypes/imagefiletype/
---
## ImageFileType class

يحدد مستندات الصور. يتضمن أنواع الملفات التالية: [`Ai`](./ai), [`Avif`](./avif), [`Bmp`](./bmp), [`Cdr`](./cdr), [`Cmx`](./cmx), [`Dcm`](./dcm), [`Dib`](./dib), [`DjVu`](./djvu), [`Dng`](./dng), [`Emf`](./emf), [`Emz`](./emz), [`Gif`](./gif), [`Heic`](./heic)[`Ico`](./ico), [`J2c`](./j2c), [`J2k`](./j2k), [`Jls`](./jls), [`Jp2`](./jp2), [`Jpc`](./jpc), [`Jfif`](./jfif). [`Jpeg`](./jpeg), [`Jpf`](./jpf), [`Jpg`](./jpg), [`Jpm`](./jpm), [`Jpx`](./jpx), [`Odg`](./odg), [`Png`](./png), [`Psd`](./psd), [`Tif`](./tif), [`Tiff`](./tiff), [`Webp`](./webp), [`Wmf`](./wmf). [`Wmz`](./wmz). تعرف على المزيد حول صيغ الصور [هنا](https://wiki.fileformat.com/image).

```csharp
public sealed class ImageFileType : FileType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ImageFileType](imagefiletype)() | منشئ التسلسل |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | وصف نوع الملف |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | امتداد الملف |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | عائلة الملف |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | صيغة الملف |
| [IsRaster](../../groupdocs.conversion.filetypes/imagefiletype/israster) { get; } | يحدد ما إذا كانت الصورة نقطية |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | يقارن الكائن الحالي بآخر. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | ينفذ [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | يحدد ما إذا كان مثيلان للكائن متساويين. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | يعمل كدالة التجزئة الافتراضية. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | تمثيل النص |

## الحقول

| الاسم | الوصف |
| --- | --- |
| static readonly [Ai](../../groupdocs.conversion.filetypes/imagefiletype/ai) | AI، Adobe Illustrator Artwork، يمثل رسومات متجهية ذات صفحة واحدة إما بصيغة EPS أو PDF. |
| static readonly [Avif](../../groupdocs.conversion.filetypes/imagefiletype/avif) | AVIF (AV1 Image File Format) هو تنسيق ملف صورة يخزن الصور مضغوطة باستخدام AV1 في تنسيق ملف HEIF. تُحفظ ملفات AVIF بامتداد .avif. تم الانتهاء من الإصدار 1 من AVIF في فبراير 2019. يحتوي على ميزات مثل النطاق الديناميكي العالي (HDR)، ودعم عمق اللون 8 و10 و12، ودعم أي مساحة لون (ملفات تعريف ISO/IEC CICP و ICC، نطاق ألوان واسع)، إلخ. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/image/avif/). |
| static readonly [Bmp](../../groupdocs.conversion.filetypes/imagefiletype/bmp) | BMP تمثل ملفات صورة بتنسيق Bitmap تُستخدم لتخزين الصور الرقمية النقطية. هذه الصور مستقلة عن محول الرسومات وتُسمى أيضًا بتنسيق bitmap المستقل عن الجهاز (DIB). تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/bmp). |
| static readonly [Cdr](../../groupdocs.conversion.filetypes/imagefiletype/cdr) | ملف CDR هو ملف صورة رسم متجه يتم إنشاؤه أصلاً باستخدام CorelDRAW لتخزين الصورة الرقمية المشفرة والمضغوطة. يحتوي مثل هذا الملف على نصوص وخطوط وأشكال وصور وألوان وتأثيرات لتمثيل المتجه لمحتويات الصورة. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/cdr). |
| static readonly [Cmx](../../groupdocs.conversion.filetypes/imagefiletype/cmx) | الملفات ذات امتداد CMX هي تنسيق ملف صورة Corel Exchange يُستخدم كعرض من قبل تطبيقات CorelSuite. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/cmx). |
| static readonly [Dcm](../../groupdocs.conversion.filetypes/imagefiletype/dcm) | الملفات ذات امتداد .DCM تمثل صورة رقمية تخزن معلومات طبية للمرضى مثل صور الرنين المغناطيسي (MRI)، والمسحات المقطعية (CT) وصور الموجات فوق الصوتية. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/dcm). |
| static readonly [Dib](../../groupdocs.conversion.filetypes/imagefiletype/dib) | ملف DIB (Device Independent Bitmap) هو ملف صورة نقطية يشبه في هيكله ملفات Bitmap القياسية (BMP) لكنه يحتوي على رأس مختلف. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/dib). |
| static readonly [Dicom](../../groupdocs.conversion.filetypes/imagefiletype/dicom) | الملفات ذات امتداد .DICOM تمثل صورة رقمية تخزن معلومات طبية للمرضى مثل صور الرنين المغناطيسي (MRI)، والمسحات المقطعية (CT) وصور الموجات فوق الصوتية. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/dicom). |
| static readonly [DjVu](../../groupdocs.conversion.filetypes/imagefiletype/djvu) | DjVu هو تنسيق ملف رسومي مخصص للمستندات والكتب الممسوحة ضوئياً، خاصة تلك التي تحتوي على مزيج من النصوص والرسومات والصور والفوتوغرافات. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/djvu). |
| static readonly [Dng](../../groupdocs.conversion.filetypes/imagefiletype/dng) | DNG هو تنسيق صورة كاميرا رقمية يُستخدم لتخزين الملفات الخام. تم تطويره بواسطة Adobe في سبتمبر 2004. تم تطويره أساساً للتصوير الفوتوغرافي الرقمي. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/dng). |
| static readonly [Emf](../../groupdocs.conversion.filetypes/imagefiletype/emf) | تنسيق الملف التعريفي المحسن (EMF) يخزن الصور الرسومية بشكل مستقل عن الجهاز. تتألف ملفات EMF من سجلات ذات طول متغير بترتيب زمني يمكنها عرض الصورة المخزنة بعد التحليل على أي جهاز إخراج. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/emf). |
| static readonly [Emz](../../groupdocs.conversion.filetypes/imagefiletype/emz) | ملف EMZ هو في الواقع نسخة مضغوطة من ملف Microsoft EMF. يتيح ذلك توزيع الملف بسهولة عبر الإنترنت. عندما يتم ضغط ملف EMF باستخدام خوارزمية الضغط .GZIP، يُعطى الامتداد .emz. |
| static readonly [Fodg](../../groupdocs.conversion.filetypes/imagefiletype/fodg) | FODG هو ملف بصيغة XML غير مضغوط يُستخدم لتخزين بيانات نصية من OpenDocument. يرتبط امتداد FODG بحزم الإنتاجية المكتبية مفتوحة المصدر LibreOffice وOpenOffice.org. |
| static readonly [Gif](../../groupdocs.conversion.filetypes/imagefiletype/gif) | GIF أو Graphical Interchange Format هو نوع من الصور ذات الضغط العالي. عادةً يسمح GIF لكل صورة بحد أقصى 8 بت لكل بكسل وتدعم حتى 256 لونًا عبر الصورة. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/gif). |
| static readonly [Heic](../../groupdocs.conversion.filetypes/imagefiletype/heic) | ملف HEIC هو تنسيق ملف صورة حاوية عالية الكفاءة يمكنه تخزين صور متعددة كمجموعة في ملف واحد. اعتمدت Apple هذا التنسيق كمتغير من HEIF مع إطلاق iOS 11. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/image/heic/). |
| static readonly [Ico](../../groupdocs.conversion.filetypes/imagefiletype/ico) | الملفات ذات امتداد ICO هي أنواع ملفات صورة تُستخدم كأيقونات لتمثيل تطبيق على نظام Microsoft Windows. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/ico). |
| static readonly [J2c](../../groupdocs.conversion.filetypes/imagefiletype/j2c) | تنسيق مستند J2c |
| static readonly [J2k](../../groupdocs.conversion.filetypes/imagefiletype/j2k) | ملف J2K هو صورة مضغوطة باستخدام ضغط الموجة بدلاً من ضغط DCT. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/j2k). |
| static readonly [Jfif](../../groupdocs.conversion.filetypes/imagefiletype/jfif) | JFIF (JPEG File Interchange Format) هو تنسيق ملف صورة يستخدم الامتداد .jfif. يبني JFIF على JIF (JPEG Interchange Format) من خلال تقليل التعقيد وحل قيوده. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/image/jfif/). |
| static readonly [Jls](../../groupdocs.conversion.filetypes/imagefiletype/jls) | تنسيق مستند Jls |
| static readonly [Jp2](../../groupdocs.conversion.filetypes/imagefiletype/jp2) | JPEG 2000 (JP2) هو نظام ترميز صور ومعيار ضغط صور متقدم. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/jp2). |
| static readonly [Jpc](../../groupdocs.conversion.filetypes/imagefiletype/jpc) | تنسيق مستند Jpc |
| static readonly [Jpeg](../../groupdocs.conversion.filetypes/imagefiletype/jpeg) | JPEG هو نوع من تنسيقات الصور يتم حفظه باستخدام طريقة الضغط الفاقد. الصورة الناتجة، نتيجة الضغط، هي مقايضة بين حجم التخزين وجودة الصورة. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/jpeg). |
| static readonly [Jpf](../../groupdocs.conversion.filetypes/imagefiletype/jpf) | تنسيق مستند Jpf |
| static readonly [Jpg](../../groupdocs.conversion.filetypes/imagefiletype/jpg) | JPG هو نوع من تنسيقات الصور يتم حفظه باستخدام طريقة الضغط الفاقد. الصورة الناتجة، نتيجة الضغط، هي مقايضة بين حجم التخزين وجودة الصورة. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/jpeg). |
| static readonly [Jpm](../../groupdocs.conversion.filetypes/imagefiletype/jpm) | تنسيق مستند Jpm |
| static readonly [Jpx](../../groupdocs.conversion.filetypes/imagefiletype/jpx) | تنسيق مستند Jpx |
| static readonly [Odg](../../groupdocs.conversion.filetypes/imagefiletype/odg) | تنسيق ملف ODG يُستخدم بواسطة تطبيق Draw في Apache OpenOffice لتخزين عناصر الرسم كصورة متجهة. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/odg). |
| static readonly [Otg](../../groupdocs.conversion.filetypes/imagefiletype/otg) | ملف OTG هو قالب رسم يتم إنشاؤه باستخدام معيار OpenDocument الذي يتبع مواصفة OASIS Office Applications 1.0. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/otg). |
| static readonly [Png](../../groupdocs.conversion.filetypes/imagefiletype/png) | PNG، Portable Network Graphics، يشير إلى نوع من تنسيقات ملفات الصور النقطية التي تستخدم ضغطًا غير فقدان. تم إنشاء هذا التنسيق كبديل لتنسيق Graphics Interchange Format (GIF) ولا يحتوي على قيود حقوق النشر. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/png). |
| static readonly [Psb](../../groupdocs.conversion.filetypes/imagefiletype/psb) | Adobe Photoshop يحفظ الملفات بنسقين. الملفات التي حجمها 30,000 × 30,000 بكسل تُحفظ بامتداد PSD والملفات الأكبر من PSD حتى 300,000 × 300,000 بكسل تُحفظ بامتداد PSB المعروف باسم “Photoshop Big”. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/image/psb). |
| static readonly [Psd](../../groupdocs.conversion.filetypes/imagefiletype/psd) | PSD، Photoshop Document، يمثل تنسيق الملف الأصلي لـ Adobe Photoshop المستخدم في تصميم وتطوير الرسومات. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/psd). |
| static readonly [Tga](../../groupdocs.conversion.filetypes/imagefiletype/tga) | الملف ذو امتداد .tga هو تنسيق رسومي نقطي تم إنشاؤه بواسطة Truevision Inc. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/image/tga). |
| static readonly [Tif](../../groupdocs.conversion.filetypes/imagefiletype/tif) | TIF، Tagged Image File Format، يمثل صورًا نقطية مخصصة للاستخدام على مجموعة متنوعة من الأجهزة التي تتوافق مع معيار هذا التنسيق. يمكنه وصف بيانات الصور ذات المستوى الثنائي، التدرج الرمادي، ألوان اللوحة، والألوان الكاملة في عدة فضاءات لونية. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/tiff). |
| static readonly [Tiff](../../groupdocs.conversion.filetypes/imagefiletype/tiff) | TIFF، Tagged Image File Format، يمثل صورًا نقطية مخصصة للاستخدام على مجموعة متنوعة من الأجهزة التي تتوافق مع معيار هذا التنسيق. يمكنه وصف بيانات الصور ذات المستوى الثنائي، التدرج الرمادي، ألوان اللوحة، والألوان الكاملة في عدة فضاءات لونية. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/tiff). |
| static readonly [Webp](../../groupdocs.conversion.filetypes/imagefiletype/webp) | WebP، الذي قدمته Google، هو تنسيق ملف صورة ويب نقطي حديث يعتمد على الضغط غير الفاقد والفاقد. يوفر نفس جودة الصورة مع تقليل حجم الصورة بشكل كبير. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/webp). |
| static readonly [Wmf](../../groupdocs.conversion.filetypes/imagefiletype/wmf) | الملفات ذات امتداد WMF تمثل Microsoft Windows Metafile (WMF) لتخزين بيانات الصور المتجهة وكذلك بصيغة bitmap. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/wmf). |
| static readonly [Wmz](../../groupdocs.conversion.filetypes/imagefiletype/wmz) | ملف WMZ هو في الواقع نسخة مضغوطة من ملف Microsoft WMF. هذا يسمح بتوزيع أسهل للملف عبر الإنترنت. عندما يتم ضغط ملف EWMFMF باستخدام خوارزمية الضغط .GZIP، يُعطى لاحقًا امتداد .wmz. |

### انظر أيضًا

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
