---
title: "ConvertOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "فئة خيارات التحويل العامة."
type: docs
weight: 12
url: /ar/java/com.groupdocs.conversion.options.convert/convertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions), java.lang.Cloneable
```
public abstract class ConvertOptions<TFileType> extends ValueObject implements Serializable, IConvertOptions, Cloneable
```

فئة خيارات التحويل العامة.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getFormat()](#getFormat--) | {@inheritDoc} |
|
|  | [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) | نوع الملف المطلوب الذي يجب تحويل المستند المدخل إليه. |
|
|  | [deepClone()](#deepClone--) | ينسخ نسخة الخيارات الحالية. |
|
|  | [getFormat_ConvertOptions_New()](#getFormat-ConvertOptions-New--) | نوع الملف المطلوب الذي يجب تحويل المستند المدخل إليه. |
|
|  | [setFormat_ConvertOptions_New(TFileType value)](#setFormat-ConvertOptions-New-TFileType-) | نوع الملف المطلوب الذي يجب تحويل المستند المدخل إليه. |
|
### getFormat() {#getFormat--}
```
public FileType getFormat()
```


يحصل على نوع الملف المطلوب الذي يجب تحويل المستند المدخل إليه.


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


نوع الملف المطلوب الذي يجب تحويل المستند المدخل إليه.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


ينسخ نسخة الخيارات الحالية.


**Returns:**
java.lang.Object -
### getFormat_ConvertOptions_New() {#getFormat-ConvertOptions-New--}
```
public final TFileType getFormat_ConvertOptions_New()
```


نوع الملف المطلوب الذي يجب تحويل المستند المدخل إليه.


**Returns:**
TFileType
### setFormat_ConvertOptions_New(TFileType value) {#setFormat-ConvertOptions-New-TFileType-}
```
public final void setFormat_ConvertOptions_New(TFileType value)
```


نوع الملف المطلوب الذي يجب تحويل المستند المدخل إليه.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | TFileType |  |

