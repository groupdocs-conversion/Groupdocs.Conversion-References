---
title: "EmailLoadOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "خيارات تحميل مستندات البريد الإلكتروني."
type: docs
weight: 18
url: /ar/java/com.groupdocs.conversion.options.load/emailloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions), java.lang.Cloneable, java.io.Serializable
```
public final class EmailLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions, Cloneable, Serializable
```

خيارات تحميل مستندات البريد الإلكتروني.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [EmailLoadOptions()](#EmailLoadOptions--) | ينشئ نسخة جديدة من الفئة [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions). |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDisplayHeader()](#getDisplayHeader--) | خيار لعرض أو إخفاء رأس البريد الإلكتروني. |
|
|  | [setDisplayHeader(boolean value)](#setDisplayHeader-boolean-) | خيار لعرض أو إخفاء رأس البريد الإلكتروني. |
|
|  | [getDisplayFromEmailAddress()](#getDisplayFromEmailAddress--) | خيار لعرض أو إخفاء عنوان البريد الإلكتروني "from". |
|
|  | [setDisplayFromEmailAddress(boolean value)](#setDisplayFromEmailAddress-boolean-) | خيار لعرض أو إخفاء عنوان البريد الإلكتروني "from". |
|
|  | [getDisplayToEmailAddress()](#getDisplayToEmailAddress--) | خيار لعرض أو إخفاء عنوان البريد الإلكتروني "to". |
|
|  | [setDisplayToEmailAddress(boolean value)](#setDisplayToEmailAddress-boolean-) | خيار لعرض أو إخفاء عنوان البريد الإلكتروني "to". |
|
|  | [getDisplayCcEmailAddress()](#getDisplayCcEmailAddress--) | خيار لعرض أو إخفاء عنوان البريد الإلكتروني "Cc". |
|
|  | [setDisplayCcEmailAddress(boolean value)](#setDisplayCcEmailAddress-boolean-) | خيار لعرض أو إخفاء عنوان البريد الإلكتروني "Cc". |
|
|  | [getDisplayBccEmailAddress()](#getDisplayBccEmailAddress--) | خيار لعرض أو إخفاء عنوان البريد الإلكتروني "Bcc". |
|
|  | [setDisplayBccEmailAddress(boolean value)](#setDisplayBccEmailAddress-boolean-) | خيار لعرض أو إخفاء عنوان البريد الإلكتروني "Bcc". |
|
|  | [getTimeZoneOffset()](#getTimeZoneOffset--) | يحصل أو يضبط إزاحة التوقيت العالمي المنسق (UTC) لتواريخ الرسائل. |
|
| [getTimeZoneOffsetInternal()](#getTimeZoneOffsetInternal--) |  |
|  | [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | مهلة تحميل الموارد الخارجية |
|
|  | [setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)](#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-) | مهلة تحميل الموارد الخارجية (المُعيّن) |
|
|  | [setTimeZoneOffset(Double value)](#setTimeZoneOffset-java.lang.Double-) | يحصل أو يضبط إزاحة التوقيت العالمي المنسق (UTC) لتواريخ الرسائل. |
|
|  | [deepClone()](#deepClone--) | ينسخ النسخة الحالية. |
|
|  | [getFieldTextMap()](#getFieldTextMap--) | يحصل على التخطيط بين رسالة البريد الإلكتروني وتمثيل نص الحقل |
|
|  | [setFieldTextMap(Map<EmailField,String> fieldTextMap)](#setFieldTextMap-java.util.Map-com.groupdocs.conversion.options.load.EmailField-java.lang.String--) | يضبط التخطيط بين رسالة البريد الإلكتروني وتمثيل نص الحقل |
|
|  | [isPreserveOriginalDate()](#isPreserveOriginalDate--) | يحدد ما إذا كان يجب الاحتفاظ بسلسلة تاريخ الرأس الأصلية في رسالة البريد عند الحفظ أو لا (القيمة الافتراضية هي true) |
|
|  | [setPreserveOriginalDate(boolean preserveOriginalDate)](#setPreserveOriginalDate-boolean-) | يحدد ما إذا كان يجب الاحتفاظ بسلسلة تاريخ الرأس الأصلية في رسالة البريد عند الحفظ أو لا |
|
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
|  | [isDisplayAttachments()](#isDisplayAttachments--) | يحصل على خيار عرض أو إخفاء المرفقات في الرأس. |
|
|  | [setDisplayAttachments(boolean displayAttachments)](#setDisplayAttachments-boolean-) | يضبط خيار عرض أو إخفاء المرفقات في الرأس. |
|
|  | [isDisplaySubject()](#isDisplaySubject--) | يحصل على خيار عرض أو إخفاء الموضوع في الرأس. |
|
|  | [setDisplaySubject(boolean displaySubject)](#setDisplaySubject-boolean-) | يضبط خيار عرض أو إخفاء الموضوع في الرأس |
|
|  | [isDisplaySent()](#isDisplaySent--) | يحصل على خيار عرض أو إخفاء تاريخ/وقت الإرسال في الرأس. |
|
|  | [setDisplaySent(boolean displaySent)](#setDisplaySent-boolean-) | يضبط خيار عرض أو إخفاء تاريخ/وقت الإرسال في الرأس. |
|
|  | [isSkipExternalResources()](#isSkipExternalResources--) | يتخطى تحميل موارد http إذا كان true |
|
| [setSkipExternalResources(boolean skipExternalResources)](#setSkipExternalResources-boolean-) |  |
### EmailLoadOptions() {#EmailLoadOptions--}
```
public EmailLoadOptions()
```


ينشئ نسخة جديدة من الفئة [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions).


### getFormat() {#getFormat--}
```
public final EmailFileType getFormat()
```


نوع ملف المستند الإدخالي


**Returns:**
[EmailFileType](../../com.groupdocs.conversion.filetypes/emailfiletype)
### getDisplayHeader() {#getDisplayHeader--}
```
public final boolean getDisplayHeader()
```


خيار لعرض أو إخفاء رأس البريد الإلكتروني. الافتراضي: true.


**Returns:**
منطقي
### setDisplayHeader(boolean value) {#setDisplayHeader-boolean-}
```
public final void setDisplayHeader(boolean value)
```


خيار لعرض أو إخفاء رأس البريد الإلكتروني. الافتراضي: true.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getDisplayFromEmailAddress() {#getDisplayFromEmailAddress--}
```
public final boolean getDisplayFromEmailAddress()
```


خيار لعرض أو إخفاء عنوان البريد الإلكتروني "from". الافتراضي: true.


**Returns:**
منطقي
### setDisplayFromEmailAddress(boolean value) {#setDisplayFromEmailAddress-boolean-}
```
public final void setDisplayFromEmailAddress(boolean value)
```


خيار لعرض أو إخفاء عنوان البريد الإلكتروني "from". الافتراضي: true.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getDisplayToEmailAddress() {#getDisplayToEmailAddress--}
```
public final boolean getDisplayToEmailAddress()
```


خيار لعرض أو إخفاء عنوان البريد الإلكتروني "to". الافتراضي: true.


**Returns:**
منطقي
### setDisplayToEmailAddress(boolean value) {#setDisplayToEmailAddress-boolean-}
```
public final void setDisplayToEmailAddress(boolean value)
```


خيار لعرض أو إخفاء عنوان البريد الإلكتروني "to". الافتراضي: true.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getDisplayCcEmailAddress() {#getDisplayCcEmailAddress--}
```
public final boolean getDisplayCcEmailAddress()
```


خيار لعرض أو إخفاء عنوان البريد الإلكتروني "Cc". الافتراضي: false.


**Returns:**
منطقي
### setDisplayCcEmailAddress(boolean value) {#setDisplayCcEmailAddress-boolean-}
```
public final void setDisplayCcEmailAddress(boolean value)
```


خيار لعرض أو إخفاء عنوان البريد الإلكتروني "Cc". الافتراضي: false.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getDisplayBccEmailAddress() {#getDisplayBccEmailAddress--}
```
public final boolean getDisplayBccEmailAddress()
```


خيار لعرض أو إخفاء عنوان البريد الإلكتروني "Bcc". الافتراضي: false.


**Returns:**
منطقي
### setDisplayBccEmailAddress(boolean value) {#setDisplayBccEmailAddress-boolean-}
```
public final void setDisplayBccEmailAddress(boolean value)
```


خيار لعرض أو إخفاء عنوان البريد الإلكتروني "Bcc". الافتراضي: false.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public final Double getTimeZoneOffset()
```


يحصل أو يضبط إزاحة الوقت العالمي المتناسق (UTC) لتواريخ الرسائل. هذه الخاصية تحدد فرق المنطقة الزمنية بين الوقت المحلي وUTC.


**Returns:**
java.lang.Double
### getTimeZoneOffsetInternal() {#getTimeZoneOffsetInternal--}
```
public System.TimeSpan getTimeZoneOffsetInternal()
```




**Returns:**
com.aspose.ms.System.TimeSpan
### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public System.TimeSpan getResourceLoadingTimeout()
```


مهلة تحميل الموارد الخارجية


**Returns:**
com.aspose.ms.System.TimeSpan
### setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout) {#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-}
```
public void setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)
```


مهلة تحميل الموارد الخارجية (المُعيّن)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| resourceLoadingTimeout | com.aspose.ms.System.TimeSpan |  |

### setTimeZoneOffset(Double value) {#setTimeZoneOffset-java.lang.Double-}
```
public final void setTimeZoneOffset(Double value)
```


يحصل أو يضبط إزاحة الوقت العالمي المتناسق (UTC) لتواريخ الرسائل. هذه الخاصية تحدد فرق المنطقة الزمنية بين الوقت المحلي وUTC.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.Double |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


ينسخ النسخة الحالية.


**Returns:**
java.lang.Object -
### getFieldTextMap() {#getFieldTextMap--}
```
public Map<EmailField,String> getFieldTextMap()
```


يحصل على التخطيط بين رسالة البريد الإلكتروني وتمثيل نص الحقل


**Returns:**
java.util.Map<com.groupdocs.conversion.options.load.EmailField,java.lang.String> - التخطيط

### setFieldTextMap(Map<EmailField,String> fieldTextMap) {#setFieldTextMap-java.util.Map-com.groupdocs.conversion.options.load.EmailField-java.lang.String--}
```
public void setFieldTextMap(Map<EmailField,String> fieldTextMap)
```


يضبط التخطيط بين رسالة البريد الإلكتروني وتمثيل نص الحقل


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fieldTextMap | java.util.Map<com.groupdocs.conversion.options.load.EmailField,java.lang.String> | تخطيط |
|

### isPreserveOriginalDate() {#isPreserveOriginalDate--}
```
public boolean isPreserveOriginalDate()
```


يحدد ما إذا كان يجب الاحتفاظ بسلسلة تاريخ الرأس الأصلية في رسالة البريد عند الحفظ أو لا (القيمة الافتراضية هي true)


**Returns:**
boolean - احتفظ بالتاريخ الأصلي إذا كان true

### setPreserveOriginalDate(boolean preserveOriginalDate) {#setPreserveOriginalDate-boolean-}
```
public void setPreserveOriginalDate(boolean preserveOriginalDate)
```


يحدد ما إذا كان يجب الاحتفاظ بسلسلة تاريخ الرأس الأصلية في رسالة البريد عند الحفظ أو لا


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | preserveOriginalDate | منطقي | احتفظ بالتاريخ الأصلي |
|

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


يحصل على خيار للتحكم فيما إذا كان يجب تحويل حاوية المستندات نفسها


**Returns:**
منطقي
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| convertOwner | منطقي |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


خيار للتحكم فيما إذا كان يجب تحويل المستندات المملوكة في حاوية المستندات


**Returns:**
منطقي
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| convertOwned | منطقي |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


خيار للتحكم بعدد المستويات في العمق التي يتم فيها إجراء التحويل


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| depth | int |  |

### isDisplayAttachments() {#isDisplayAttachments--}
```
public boolean isDisplayAttachments()
```


يحصل على خيار لعرض أو إخفاء المرفقات في الرأس. الافتراضي: true.


**Returns:**
منطقي
### setDisplayAttachments(boolean displayAttachments) {#setDisplayAttachments-boolean-}
```
public void setDisplayAttachments(boolean displayAttachments)
```


يضبط خيار عرض أو إخفاء المرفقات في الرأس.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| displayAttachments | منطقي |  |

### isDisplaySubject() {#isDisplaySubject--}
```
public boolean isDisplaySubject()
```


يحصل على خيار لعرض أو إخفاء الموضوع في الرأس. الافتراضي: true.


**Returns:**
منطقي
### setDisplaySubject(boolean displaySubject) {#setDisplaySubject-boolean-}
```
public void setDisplaySubject(boolean displaySubject)
```


يضبط خيار عرض أو إخفاء الموضوع في الرأس


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| displaySubject | منطقي |  |

### isDisplaySent() {#isDisplaySent--}
```
public boolean isDisplaySent()
```


يحصل على خيار لعرض أو إخفاء تاريخ/وقت الإرسال في الرأس. الافتراضي: true.


**Returns:**
منطقي
### setDisplaySent(boolean displaySent) {#setDisplaySent-boolean-}
```
public void setDisplaySent(boolean displaySent)
```


يضبط خيار عرض أو إخفاء تاريخ/وقت الإرسال في الرأس.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| displaySent | منطقي |  |

### isSkipExternalResources() {#isSkipExternalResources--}
```
public boolean isSkipExternalResources()
```


يتخطى تحميل موارد http إذا كان true


**Returns:**
منطقي
### setSkipExternalResources(boolean skipExternalResources) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skipExternalResources)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| skipExternalResources | منطقي |  |

