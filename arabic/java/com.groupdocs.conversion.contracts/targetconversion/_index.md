---
title: "TargetConversion"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يمثل التحويل الهدف المحتمل وعلمًا يحدد ما إذا كان أساسيًا أم ثانويًا"
type: docs
weight: 14
url: /ar/java/com.groupdocs.conversion.contracts/targetconversion/
---
**Inheritance:**
java.lang.Object
```
public final class TargetConversion
```

يمثل التحويل الهدف المحتمل وعلمًا يحدد ما إذا كان أساسيًا أم ثانويًا

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getFormat()](#getFormat--) | تنسيق المستند الهدف |
|
|  | [isPrimary()](#isPrimary--) | هل التحويل أساسي |
|
|  | [getConvertOptions()](#getConvertOptions--) | خيارات التحويل المحددة مسبقًا والتي يمكن استخدامها للتحويل إلى النوع الحالي |
|
### getFormat() {#getFormat--}
```
public FileType getFormat()
```


تنسيق المستند الهدف


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - Target document format

### isPrimary() {#isPrimary--}
```
public boolean isPrimary()
```


هل التحويل أساسي


**Returns:**
منطقي - `true` إذا كان أساسيًا

### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


خيارات التحويل المحددة مسبقًا والتي يمكن استخدامها للتحويل إلى النوع الحالي


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions) - convert options

