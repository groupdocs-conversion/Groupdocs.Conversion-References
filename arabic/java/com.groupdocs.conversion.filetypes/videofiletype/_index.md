---
title: "VideoFileType"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يحدد مستندات الفيديو ويشمل الأنواع التالية        تعرف على المزيد حول تنسيقات الفيديو هنا."
type: docs
weight: 26
url: /ar/java/com.groupdocs.conversion.filetypes/videofiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public class VideoFileType extends FileType
```

يحدد مستندات الفيديو ويشمل الأنواع التالية: , , , , , , , تعرف على المزيد حول تنسيقات الفيديو [هنا](../https://docs.fileformat.com/video/).

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [VideoFileType()](#VideoFileType--) | منشئ التسلسل |
|
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Mp4](#Mp4) | MP4 (اختصار لـ MPEG-4 Part 14) هو تنسيق ملف يعتمد على ISO/IEC 14496-12:2004 وهو مبني على تنسيق ملف QuickTime لكنه يحدد رسميًا دعم Initial Object Descriptors (IOD) وميزات MPEG الأخرى. |
|
|  | [Avi](#Avi) | تنسيق ملف AVI هو حاوية وسائط متعددة صوتية وفيديو تم تقديمه من قبل Microsoft. |
|
|  | [Flv](#Flv) | FLV (Flash Video) هو تنسيق ملف حاوية بامتداد .flv. |
|
|  | [Mkv](#Mkv) | MKV (Matroska Video) هو حاوية وسائط متعددة مشابهة لتنسيقي MOV و AVI ولكنه يدعم أكثر من مسار صوتي ومسار ترجمة في نفس الملف. |
|
|  | [Mov](#Mov) | تنسيق ملف MOV أو QuickTime هو حاوية وسائط متعددة تم تطويرها بواسطة Apple: يحتوي على مسار واحد أو أكثر، كل مسار يحمل نوعًا معينًا من البيانات مثل. |
|
|  | [Webm](#Webm) | الملف ذو الامتداد .webm هو ملف فيديو يعتمد على تنسيق WebM المفتوح والخالي من الرسوم. |
|
|  | [Wmv](#Wmv) | Windows Media Video هو تنسيق فيديو مضغوط تم تطويره من قبل Microsoft. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### VideoFileType() {#VideoFileType--}
```
public VideoFileType()
```


منشئ التسلسل


### Mp4 {#Mp4}
```
public static final VideoFileType Mp4
```


MP4 (اختصار لـ MPEG-4 Part 14) هو تنسيق ملف يعتمد على ISO/IEC 14496-12:2004 وهو مبني على تنسيق ملف QuickTime لكنه يحدد رسميًا دعم Initial Object Descriptors (IOD) وميزات MPEG الأخرى. تعرف على المزيد حول تنسيق الملف هذا [هنا](../https://docs.fileformat.com/video/mp4/).


### Avi {#Avi}
```
public static final VideoFileType Avi
```


تنسيق ملف AVI هو حاوية وسائط متعددة صوتية وفيديو تم تقديمه من قبل Microsoft. يحتوي على بيانات الصوت والفيديو التي تم إنشاؤها وضغطها باستخدام عدة مشفرات/فكّ مشفرات (Coders/Decoders) مثل XVid و DivX. تعرف على المزيد حول تنسيق الملف هذا [هنا](../https://docs.fileformat.com/video/avi/).


### Flv {#Flv}
```
public static final VideoFileType Flv
```


FLV (Flash Video) هو تنسيق ملف حاوية بامتداد .flv. يُستخدم FLV لتوصيل محتوى الصوت/الفيديو عبر الإنترنت باستخدام Adobe Flash Player أو Adobe Air. تعرف على المزيد حول تنسيق الملف هذا [هنا](../https://docs.fileformat.com/video/flv/).


### Mkv {#Mkv}
```
public static final VideoFileType Mkv
```


MKV (Matroska Video) هو حاوية وسائط متعددة مشابهة لتنسيق MOV و AVI لكنها تدعم أكثر من مسار صوتي ومسار ترجمة في نفس الملف. ملف MKV هو تنسيق حاوية وسائط Matroska يُستخدم للفيديو. تعرف على المزيد حول هذا التنسيق [هنا](../https://docs.fileformat.com/video/mkv/).


### Mov {#Mov}
```
public static final VideoFileType Mov
```


تنسيق ملف MOV أو QuickTime هو حاوية وسائط متعددة تم تطويرها بواسطة Apple: يحتوي على مسار واحد أو أكثر، كل مسار يحمل نوعًا معينًا من البيانات مثل الفيديو، الصوت، النص، إلخ. تعرف على المزيد حول هذا التنسيق [هنا](../https://docs.fileformat.com/video/mov/).


### Webm {#Webm}
```
public static final VideoFileType Webm
```


الملف ذو الامتداد .webm هو ملف فيديو يعتمد على تنسيق WebM المفتوح والخالي من الرسوم. تم تصميمه لمشاركة الفيديو على الويب ويحدد بنية حاوية الملف بما في ذلك صيغ الفيديو والصوت. تعرف على المزيد حول هذا التنسيق [هنا](../https://docs.fileformat.com/video/webm//).


### Wmv {#Wmv}
```
public static final VideoFileType Wmv
```


Windows Media Video هو تنسيق فيديو مضغوط تم تطويره بواسطة Microsoft. بعد التقييس من قبل جمعية مهندسي الصور المتحركة والتلفزيون (SMPTE)، يُعتبر WMV الآن تنسيقًا مفتوحًا قياسيًا. تعرف على المزيد حول هذا التنسيق [هنا](../https://docs.fileformat.com/video/wmv/).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


إعداد خيارات التحميل الافتراضية لنوع ملف المصدر


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


إعداد خيارات التحويل الافتراضية لنوع الملف


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
