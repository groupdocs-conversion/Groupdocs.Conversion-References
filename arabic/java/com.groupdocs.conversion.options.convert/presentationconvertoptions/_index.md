---
title: "PresentationConvertOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يصف خيارات التحويل إلى نوع ملف العرض التقديمي."
type: docs
weight: 33
url: /ar/java/com.groupdocs.conversion.options.convert/presentationconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public class PresentationConvertOptions extends CommonConvertOptions<PresentationFileType> implements Serializable
```

يصف خيارات التحويل إلى نوع ملف العرض التقديمي.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [PresentationConvertOptions()](#PresentationConvertOptions--) | ينشئ مثيلًا جديدًا من الفئة [PresentationConvertOptions](../../com.groupdocs.conversion.options.convert/presentationconvertoptions). |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPassword()](#getPassword--) | عيّن هذه الخاصية إذا كنت تريد حماية المستند المحوّل بكلمة مرور. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | عيّن هذه الخاصية إذا كنت تريد حماية المستند المحوّل بكلمة مرور. |
|
|  | [getZoom()](#getZoom--) | يحدد مستوى التكبير بالنسبة المئوية. |
|
|  | [setZoom(int value)](#setZoom-int-) | يحدد مستوى التكبير بالنسبة المئوية. |
|
### PresentationConvertOptions() {#PresentationConvertOptions--}
```
public PresentationConvertOptions()
```


ينشئ مثيلًا جديدًا من الفئة [PresentationConvertOptions](../../com.groupdocs.conversion.options.convert/presentationconvertoptions).


### getPassword() {#getPassword--}
```
public final String getPassword()
```


عيّن هذه الخاصية إذا كنت تريد حماية المستند المحوّل بكلمة مرور.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


عيّن هذه الخاصية إذا كنت تريد حماية المستند المحوّل بكلمة مرور.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


يحدد مستوى التكبير بالنسبة المئوية. القيمة الافتراضية هي 100.
يتم دعم التكبير الافتراضي حتى Microsoft Powerpoint 2010. بدءًا من Microsoft Powerpoint 2013 لم يعد يتم تعيين التكبير الافتراضي للمستند، بل يبدو أنه يستخدم عامل التكبير للوثيقة الأخيرة التي تم فتحها.


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


يحدد مستوى التكبير بالنسبة المئوية. القيمة الافتراضية هي 100.
يتم دعم التكبير الافتراضي حتى Microsoft Powerpoint 2010. بدءًا من Microsoft Powerpoint 2013 لم يعد يتم تعيين التكبير الافتراضي للمستند، بل يبدو أنه يستخدم عامل التكبير للوثيقة الأخيرة التي تم فتحها.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

