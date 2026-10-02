---
title: "RtfOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "خيارات التحويل إلى نوع ملف RTF."
type: docs
weight: 39
url: /ar/java/com.groupdocs.conversion.options.convert/rtfoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class RtfOptions extends ValueObject implements Serializable
```

خيارات التحويل إلى نوع ملف RTF.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [RtfOptions()](#RtfOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getExportImagesForOldReaders()](#getExportImagesForOldReaders--) | يحدد ما إذا كانت الكلمات المفتاحية لـ "القراء القدامى" تُكتب إلى RTF أم لا. |
|
|  | [setExportImagesForOldReaders(boolean value)](#setExportImagesForOldReaders-boolean-) | يحدد ما إذا كانت الكلمات المفتاحية لـ "القراء القدامى" تُكتب إلى RTF أم لا. |
|
### RtfOptions() {#RtfOptions--}
```
public RtfOptions()
```


### getExportImagesForOldReaders() {#getExportImagesForOldReaders--}
```
public final boolean getExportImagesForOldReaders()
```


يحدد ما إذا كانت الكلمات المفتاحية لـ "القراء القدامى" تُكتب إلى RTF أم لا.
يمكن لهذا أن يؤثر بشكل كبير على حجم مستند RTF. القيمة الافتراضية هي False.


**Returns:**
منطقي
### setExportImagesForOldReaders(boolean value) {#setExportImagesForOldReaders-boolean-}
```
public final void setExportImagesForOldReaders(boolean value)
```


يحدد ما إذا كانت الكلمات المفتاحية لـ "القراء القدامى" تُكتب إلى RTF أم لا.
يمكن لهذا أن يؤثر بشكل كبير على حجم مستند RTF. القيمة الافتراضية هي False.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

