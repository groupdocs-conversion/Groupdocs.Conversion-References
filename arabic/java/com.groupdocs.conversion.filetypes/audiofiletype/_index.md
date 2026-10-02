---
title: "AudioFileType"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يحدد مستندات الصوت. يتضمن الأنواع التالية          تعرف على المزيد حول صيغ الصوت هنا."
type: docs
weight: 10
url: /ar/java/com.groupdocs.conversion.filetypes/audiofiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public class AudioFileType extends FileType
```

يحدد مستندات الصوت. يتضمن الأنواع التالية: , , , , , , , , , تعرف على المزيد حول صيغ الصوت [هنا](../https://docs.fileformat.com/audio/).

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [AudioFileType()](#AudioFileType--) | منشئ التسلسل |
|
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Mp3](#Mp3) | الملفات ذات امتداد .mp3 هي صيغ ملفات مشفرة رقمياً للملفات الصوتية تعتمد رسمياً على MPEG-1 Audio Layer III أو MPEG-2 Audio Layer III. |
|
|  | [Aac](#Aac) | AAC (Advanced Audio Coding) يشير إلى معيار ترميز صوتي رقمي يمثل ملفات صوتية تعتمد على ضغط صوتي فقدان البيانات. |
|
|  | [Aiff](#Aiff) | AIFF (Audio Interchange File Format) هو صيغة ملف صوتي غير مضغوط تم تطويرها بواسطة Apple في عام 1998، لكنها تعتمد على EA IFF 85 تعرف على المزيد حول صيغة الملف هذه [هنا](../https://docs.fileformat.com/audio/aiff/). |
|
|  | [Flac](#Flac) | FLAC(Free Lossless Audio Codec) هو تنسيق ترميز صوتي ضغط بدون فقدان تم تطويره بواسطة Xiph.Org Foundation تعرف على المزيد حول هذا التنسيق [هنا](../https://docs.fileformat.com/audio/flac/). |
|
|  | [M4a](#M4a) | تنسيق ملف M4A هو ملف صوتي تم إنشاؤه باستخدام AAC (Advanced Audio Coding) المعروف بأنه ضغط فقدان. |
|
|  | [Wma](#Wma) | الملف ذو الامتداد .wma يمثل ملفًا صوتيًا يتم حفظه بتنسيق Advanced Systems Format (ASF). |
|
|  | [Ac3](#Ac3) | الملف ذو الامتداد .ac3 هو ملف Audio Codec 3، تم تقديمه من قبل Dolby Laboratories. |
|
|  | [Ogg](#Ogg) | OGG هو ملف صوتي مضغوط Ogg Vorbis يتم حفظه بالامتداد .ogg. |
|
|  | [Wav](#Wav) | WAV، المعروف بـ WAVE (Waveform Audio File Format)، هو جزء من مواصفة Resource Interchange File Format (RIFF) الخاصة بـ Microsoft لتخزين ملفات الصوت الرقمية. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### AudioFileType() {#AudioFileType--}
```
public AudioFileType()
```


منشئ التسلسل


### Mp3 {#Mp3}
```
public static final AudioFileType Mp3
```


الملفات ذات الامتداد .mp3 هي تنسيقات ملفات مشفرة رقميًا للملفات الصوتية تعتمد رسميًا على MPEG-1 Audio Layer III أو MPEG-2 Audio Layer III. تعرف على المزيد حول هذا التنسيق [هنا](../https://docs.fileformat.com/audio/mp3/).


### Aac {#Aac}
```
public static final AudioFileType Aac
```


AAC (Advanced Audio Coding) يشير إلى معيار ترميز صوتي رقمي يمثل ملفات صوتية تعتمد على ضغط صوتي فقدان. تعرف على المزيد حول هذا التنسيق [هنا](../https://docs.fileformat.com/audio/aac/).


### Aiff {#Aiff}
```
public static final AudioFileType Aiff
```


AIFF (Audio Interchange File Format) هو صيغة ملف صوتي غير مضغوط تم تطويرها بواسطة Apple في عام 1998، لكنها تعتمد على EA IFF 85 تعرف على المزيد حول صيغة الملف هذه [هنا](../https://docs.fileformat.com/audio/aiff/).


### Flac {#Flac}
```
public static final AudioFileType Flac
```


FLAC(Free Lossless Audio Codec) هو تنسيق ترميز صوتي ضغط بدون فقدان تم تطويره بواسطة Xiph.Org Foundation تعرف على المزيد حول هذا التنسيق [هنا](../https://docs.fileformat.com/audio/flac/).


### M4a {#M4a}
```
public static final AudioFileType M4a
```


تنسيق ملف M4A هو ملف صوتي تم إنشاؤه باستخدام AAC (Advanced Audio Coding) المعروف بأنه ضغط فقدان. تعرف على المزيد حول هذا التنسيق [هنا](../https://docs.fileformat.com/audio/m4a/).


### Wma {#Wma}
```
public static final AudioFileType Wma
```


الملف ذو الامتداد .wma يمثل ملفًا صوتيًا يتم حفظه بتنسيق Advanced Systems Format (ASF). تعرف على المزيد حول هذا التنسيق [هنا](../https://docs.fileformat.com/audio/wma/).


### Ac3 {#Ac3}
```
public static final AudioFileType Ac3
```


الملف ذو الامتداد .ac3 هو ملف Audio Codec 3، تم تقديمه من قبل Dolby Laboratories. وهو تنسيق صوتي يمكنه احتواء ما يصل إلى ست قنوات إخراج صوتي. تعرف على المزيد حول هذا التنسيق [هنا](../https://docs.fileformat.com/audio/ac3/).


### Ogg {#Ogg}
```
public static final AudioFileType Ogg
```


OGG هو ملف صوتي مضغوط Ogg Vorbis يتم حفظه بالامتداد .ogg. تُستخدم ملفات OGG لتخزين البيانات الصوتية ويمكنها أيضًا تضمين معلومات الفنان والمسار والبيانات الوصفية. تعرف على المزيد حول هذا التنسيق [هنا](../https://docs.fileformat.com/audio/ogg/).


### Wav {#Wav}
```
public static final AudioFileType Wav
```


WAV، المعروف بـ WAVE (Waveform Audio File Format)، هو جزء من مواصفة Resource Interchange File Format (RIFF) الخاصة بـ Microsoft لتخزين ملفات الصوت الرقمية. تعرف على المزيد حول هذا التنسيق [هنا](../https://docs.fileformat.com/audio/ogg/).


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
