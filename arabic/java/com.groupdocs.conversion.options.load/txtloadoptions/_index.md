---
title: "TxtLoadOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "خيارات تحميل مستندات Txt."
type: docs
weight: 34
url: /ar/java/com.groupdocs.conversion.options.load/txtloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class TxtLoadOptions extends LoadOptions implements Serializable
```

خيارات تحميل مستندات Txt.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [TxtLoadOptions()](#TxtLoadOptions--) | ينشئ نسخة جديدة من الفئة [TxtLoadOptions](../../com.groupdocs.conversion.options.load/txtloadoptions) class. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDetectNumberingWithWhitespaces()](#getDetectNumberingWithWhitespaces--) | يسمح بتحديد كيفية التعرف على عناصر القوائم المرقمة عند تحويل مستند نص عادي. |
|
|  | [setDetectNumberingWithWhitespaces(boolean value)](#setDetectNumberingWithWhitespaces-boolean-) | يسمح بتحديد كيفية التعرف على عناصر القوائم المرقمة عند تحويل مستند نص عادي. |
|
|  | [getTrailingSpacesOptions()](#getTrailingSpacesOptions--) | يحصل أو يعيّن الخيار المفضل لمعالجة المسافات المتتبعة. |
|
|  | [setTrailingSpacesOptions(TxtTrailingSpacesOptions value)](#setTrailingSpacesOptions-com.groupdocs.conversion.options.load.TxtTrailingSpacesOptions-) | يحصل أو يعيّن الخيار المفضل لمعالجة المسافات المتتبعة. |
|
|  | [getLeadingSpacesOptions()](#getLeadingSpacesOptions--) | يحصل أو يعيّن الخيار المفضل لمعالجة المسافات البادئة. |
|
|  | [setLeadingSpacesOptions(TxtLeadingSpacesOptions value)](#setLeadingSpacesOptions-com.groupdocs.conversion.options.load.TxtLeadingSpacesOptions-) | يحصل أو يعيّن الخيار المفضل لمعالجة المسافات البادئة. |
|
|  | [getEncoding()](#getEncoding--) | يحصل أو يعيّن الترميز الذي سيُستخدم عند تحميل مستند Txt. |
|
| [getEncodingInternal()](#getEncodingInternal--) |  |
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | يحصل أو يعيّن الترميز الذي سيُستخدم عند تحميل مستند Txt. |
|
### TxtLoadOptions() {#TxtLoadOptions--}
```
public TxtLoadOptions()
```


ينشئ نسخة جديدة من الفئة [TxtLoadOptions](../../com.groupdocs.conversion.options.load/txtloadoptions) class.


### getFormat() {#getFormat--}
```
public WordProcessingFileType getFormat()
```


نوع ملف المستند الإدخالي


**Returns:**
[WordProcessingFileType](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype)
### getDetectNumberingWithWhitespaces() {#getDetectNumberingWithWhitespaces--}
```
public final boolean getDetectNumberingWithWhitespaces()
```


يسمح بتحديد كيفية التعرف على عناصر القوائم المرقمة عند تحويل مستند نص عادي.
القيمة الافتراضية هي true.

<br />

*** ** * ** ***

إذا تم ضبط هذا الخيار على false، يكتشف خوارزمية التعرف على القوائم فقرات القوائم عندما تنتهي أرقام القوائم بـ
إما نقطة أو قوس يميني أو رموز نقطية (مثل "\\u2022", "*", "-" أو "o").

إذا تم ضبط هذا الخيار على true، تُستخدم المسافات أيضًا كفواصل لأرقام القوائم:
خوارزمية التعرف على القوائم لتنسيق الترقيم العربي (1., 1.1.2.) تستخدم كلًا من المسافات والنقطة (".") كرموز.

<br />



**Returns:**
منطقي
### setDetectNumberingWithWhitespaces(boolean value) {#setDetectNumberingWithWhitespaces-boolean-}
```
public final void setDetectNumberingWithWhitespaces(boolean value)
```


يسمح بتحديد كيفية التعرف على عناصر القوائم المرقمة عند تحويل مستند نص عادي.
القيمة الافتراضية هي true.

<br />

*** ** * ** ***

إذا تم ضبط هذا الخيار على false، يكتشف خوارزمية التعرف على القوائم فقرات القوائم عندما تنتهي أرقام القوائم بـ
إما نقطة أو قوس يميني أو رموز نقطية (مثل "\\u2022", "*", "-" أو "o").

إذا تم ضبط هذا الخيار على true، تُستخدم المسافات أيضًا كفواصل لأرقام القوائم:
خوارزمية التعرف على القوائم لتنسيق الترقيم العربي (1., 1.1.2.) تستخدم كلًا من المسافات والنقطة (".") كرموز.

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getTrailingSpacesOptions() {#getTrailingSpacesOptions--}
```
public final TxtTrailingSpacesOptions getTrailingSpacesOptions()
```


يحصل أو يعيّن الخيار المفضل لمعالجة المسافات المتتبعة.
القيمة الافتراضية هي [TxtTrailingSpacesOptions.Trim](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions#Trim).


**Returns:**
[TxtTrailingSpacesOptions](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions)
### setTrailingSpacesOptions(TxtTrailingSpacesOptions value) {#setTrailingSpacesOptions-com.groupdocs.conversion.options.load.TxtTrailingSpacesOptions-}
```
public final void setTrailingSpacesOptions(TxtTrailingSpacesOptions value)
```


يحصل أو يعيّن الخيار المفضل لمعالجة المسافات المتتبعة.
القيمة الافتراضية هي [TxtTrailingSpacesOptions.Trim](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions#Trim).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TxtTrailingSpacesOptions](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions) |  |

### getLeadingSpacesOptions() {#getLeadingSpacesOptions--}
```
public final TxtLeadingSpacesOptions getLeadingSpacesOptions()
```


يحصل أو يعيّن الخيار المفضل لمعالجة المسافات البادئة.
القيمة الافتراضية هي [TxtLeadingSpacesOptions.ConvertToIndent](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions#ConvertToIndent).


**Returns:**
[TxtLeadingSpacesOptions](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions)
### setLeadingSpacesOptions(TxtLeadingSpacesOptions value) {#setLeadingSpacesOptions-com.groupdocs.conversion.options.load.TxtLeadingSpacesOptions-}
```
public final void setLeadingSpacesOptions(TxtLeadingSpacesOptions value)
```


يحصل أو يعيّن الخيار المفضل لمعالجة المسافات البادئة.
القيمة الافتراضية هي [TxtLeadingSpacesOptions.ConvertToIndent](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions#ConvertToIndent).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TxtLeadingSpacesOptions](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions) |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


يحصل أو يعيّن الترميز الذي سيُستخدم عند تحميل مستند Txt. يمكن أن يكون null. القيمة الافتراضية هي null.


**Returns:**
java.nio.charset.Charset
### getEncodingInternal() {#getEncodingInternal--}
```
public System.Text.Encoding getEncodingInternal()
```




**Returns:**
com.aspose.ms.System.Text.Encoding
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


يحصل أو يعيّن الترميز الذي سيُستخدم عند تحميل مستند Txt. يمكن أن يكون null. القيمة الافتراضية هي null.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.nio.charset.Charset |  |

