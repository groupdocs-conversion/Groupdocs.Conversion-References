---
title: "ImageConvertOptions"
second_title: "GroupDocs.Conversion لـ .NET مرجع API"
description: "خيارات التحويل إلى نوع ملف الصورة."
type: docs
weight: 1950
url: /ar/net/groupdocs.conversion.options.convert/imageconvertoptions/
---
## ImageConvertOptions class

خيارات التحويل إلى نوع ملف الصورة.

```csharp
public sealed class ImageConvertOptions : CommonConvertOptions<ImageFileType>, IUsePdfConvertOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ImageConvertOptions](imageconvertoptions)() | يُنشئ مثيلًا جديدًا من الفئة [`ImageConvertOptions`](../imageconvertoptions). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.convert/imageconvertoptions/backgroundcolor) { get; set; } | يضبط لون الخلفية حيث يدعم ذلك تنسيق المصدر. |
| [Brightness](../../groupdocs.conversion.options.convert/imageconvertoptions/brightness) { get; set; } | يضبط سطوع الصورة. |
| [CapResolutionToPageContent](../../groupdocs.conversion.options.convert/imageconvertoptions/capresolutiontopagecontent) { get; set; } | عند التفعيل، يحد من دقة عرض PDF لكل صفحة إلى دقة البكسل الأصلية للصفحة بحيث لا يتم عرض أي صفحة بدقة DPI أعلى من تلك الموجودة في الصورة المدمجة، ويصدر تلك الصفحة بأبعاد بكسل أصغر ودقة DPI الأصلية في الناتج النهائي بدلاً من توسيعها إلى DPI المطلوب. تتأثر فقط الصفحات التي تهيمن عليها الصور (المسح). الصفحات التي تحتوي على نص أو محتوى متجهي لا يتم تخفيفها أبداً وتصدر بدقة DPI المطلوبة. يتم تخطي ذلك عندما يتم تعيين قيمة صريحة للمخرجات [`Width`](./width) أو [`Height`](./height). القيمة الافتراضية هي `false` (بدون تحديد حد؛ كل صفحة تُعرض وتُصدر بدقة DPI المطلوبة). |
| [Contrast](../../groupdocs.conversion.options.convert/imageconvertoptions/contrast) { get; set; } | يضبط تباين الصورة. |
| [CropArea](../../groupdocs.conversion.options.convert/imageconvertoptions/croparea) { get; set; } | قص منطقة صورة البكسل بعد التحويل. |
| [FlipMode](../../groupdocs.conversion.options.convert/imageconvertoptions/flipmode) { get; set; } | وضع انعكاس الصورة. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | نوع الملف المطلوب تحويل المستند الإدخالي إليه. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | ينفذ [`Format`](../iconvertoptions/format) |
| [Gamma](../../groupdocs.conversion.options.convert/imageconvertoptions/gamma) { get; set; } | يضبط جاما الصورة. |
| [Grayscale](../../groupdocs.conversion.options.convert/imageconvertoptions/grayscale) { get; set; } | يشير إلى ما إذا كان سيتم التحويل إلى صورة رمادية. |
| [Height](../../groupdocs.conversion.options.convert/imageconvertoptions/height) { get; set; } | ارتفاع الصورة المطلوب بعد التحويل. |
| [HorizontalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/horizontalresolution) { get; set; } | الدقة الأفقية المطلوبة للصورة بعد التحويل. الدقة الافتراضية هي دقة ملف الإدخال أو 96 dpi. |
| [JpegOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/jpegoptions) { get; set; } | خيارات التحويل الخاصة بـ Jpeg. |
| [MinResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/minresolution) { get; set; } | الحد الأدنى لكل محور يُطبق على DPI العرض المحدود عندما يكون [`CapResolutionToPageContent`](./capresolutiontopagecontent) مفعلاً. لا يتم خفض DPI المحدود إلى أقل من هذه القيمة. القيمة الافتراضية هي `0` (بدون حد أدنى). |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | ينفذ [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | يطبق [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | يطبق [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [PsdOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/psdoptions) { get; set; } | خيارات التحويل الخاصة بـ Psd. |
| [RotateAngle](../../groupdocs.conversion.options.convert/imageconvertoptions/rotateangle) { get; set; } | زاوية دوران الصورة. |
| [TiffOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/tiffoptions) { get; set; } | خيارات التحويل الخاصة بـ Tiff. |
| [UsePdf](../../groupdocs.conversion.options.convert/imageconvertoptions/usepdf) { get; set; } | إذا كان `true`، يتم أولاً تحويل المدخل إلى PDF ثم إلى الصيغة المطلوبة. |
| [VerticalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/verticalresolution) { get; set; } | الدقة العمودية المطلوبة للصورة بعد التحويل. الدقة الافتراضية هي دقة ملف الإدخال أو 96 نقطة في البوصة. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | يطبق [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [WebpOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/webpoptions) { get; set; } | خيارات التحويل الخاصة بـ Webp. |
| [Width](../../groupdocs.conversion.options.convert/imageconvertoptions/width) { get; set; } | العرض المطلوب للصورة بعد التحويل. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | ينسخ نسخة من كائن الخيارات الحالي. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | يحدد ما إذا كان مثيلان للكائن متساويين. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | يحدد ما إذا كان مثيلان للكائن متساويين. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | يعمل كدالة التجزئة الافتراضية. |

### انظر أيضًا

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [ImageFileType](../../groupdocs.conversion.filetypes/imagefiletype)
* interface [IUsePdfConvertOptions](../iusepdfconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
