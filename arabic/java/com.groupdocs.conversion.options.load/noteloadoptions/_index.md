---
title: "NoteLoadOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "خيارات تحميل مستندات One."
type: docs
weight: 24
url: /ar/java/com.groupdocs.conversion.options.load/noteloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class NoteLoadOptions extends LoadOptions implements Serializable
```

خيارات تحميل مستندات One.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [NoteLoadOptions()](#NoteLoadOptions--) | ينشئ نسخة جديدة من الفئة [NoteLoadOptions](../../com.groupdocs.conversion.options.load/noteloadoptions) class. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | الخط الافتراضي لمستند Note. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | الخط الافتراضي لمستند Note. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | استبدال الخطوط المحددة عند تحويل مستند Note. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | استبدال الخطوط المحددة عند تحويل مستند Note. |
|
|  | [getPassword()](#getPassword--) | تعيين كلمة مرور لإلغاء حماية المستند المحمي. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | تعيين كلمة مرور لإلغاء حماية المستند المحمي. |
|
### NoteLoadOptions() {#NoteLoadOptions--}
```
public NoteLoadOptions()
```


ينشئ نسخة جديدة من الفئة [NoteLoadOptions](../../com.groupdocs.conversion.options.load/noteloadoptions) class.


### getFormat() {#getFormat--}
```
public final NoteFileType getFormat()
```


نوع ملف المستند الإدخالي


**Returns:**
[NoteFileType](../../com.groupdocs.conversion.filetypes/notefiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


الخط الافتراضي لمستند Note. سيتم استخدام الخط التالي إذا كان الخط مفقودًا.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


الخط الافتراضي لمستند Note. سيتم استخدام الخط التالي إذا كان الخط مفقودًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


استبدال الخطوط المحددة عند تحويل مستند Note.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


استبدال الخطوط المحددة عند تحويل مستند Note.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


تعيين كلمة مرور لإلغاء حماية المستند المحمي.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


تعيين كلمة مرور لإلغاء حماية المستند المحمي.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

