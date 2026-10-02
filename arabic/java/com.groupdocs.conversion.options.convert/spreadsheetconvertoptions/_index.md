---
title: "SpreadsheetConvertOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "خيارات التحويل إلى نوع ملف جدول البيانات."
type: docs
weight: 40
url: /ar/java/com.groupdocs.conversion.options.convert/spreadsheetconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public class SpreadsheetConvertOptions extends CommonConvertOptions<SpreadsheetFileType> implements Serializable
```

خيارات التحويل إلى نوع ملف جدول البيانات.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [SpreadsheetConvertOptions()](#SpreadsheetConvertOptions--) | ينشئ مثلاً جديداً من الفئة [SpreadsheetConvertOptions](../../com.groupdocs.conversion.options.convert/spreadsheetconvertoptions). |
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
|  | [getSeparator()](#getSeparator--) | يحدد الفاصل الذي سيُستخدم عند التحويل إلى صيغ مفصولة. |
|
| [setSeparator(char separator)](#setSeparator-char-) |  |
| [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) |  |
### SpreadsheetConvertOptions() {#SpreadsheetConvertOptions--}
```
public SpreadsheetConvertOptions()
```


ينشئ مثلاً جديداً من الفئة [SpreadsheetConvertOptions](../../com.groupdocs.conversion.options.convert/spreadsheetconvertoptions).


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


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


يحدد مستوى التكبير بالنسبة المئوية. القيمة الافتراضية هي 100.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getSeparator() {#getSeparator--}
```
public char getSeparator()
```


يحدد الفاصل الذي سيُستخدم عند التحويل إلى صيغ مفصولة.


**Returns:**
حرف
### setSeparator(char separator) {#setSeparator-char-}
```
public void setSeparator(char separator)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الفاصل | حرف |  |

### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


نوع الملف المطلوب الذي يجب تحويل المستند المدخل إليه.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

